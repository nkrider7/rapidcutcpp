 #  💻 Setting Up Your Environment C++

<br>Setting up C++ requires a few steps, including installing a compiler, configuring an Integrated Development Environment (IDE), and creating a new C++ project.
<br><br> 

 - [Window](#window)
 - [MacOS](#mac)
 - [linux](#linux)

 ## 1. Installing a Compiler
A compiler is required to convert C++ code into machine language. Some popular C++ compilers include:

 - GCC (GNU Compiler Collection) for Linux and macOS
 - MinGW (Minimalist GNU for Windows) for Windows
 - Microsoft Visual C++ for Windows
To install a compiler, simply follow the instructions provided by the respective websites.

 ## 2. Configuring an IDE
An IDE is a software application that provides facilities for programming, such as code editing, debugging, and building. Some popular C++ IDEs include:

 - Visual Studio (Windows, macOS)
 - Eclipse (Windows, macOS, Linux)
 - Code::Blocks (Windows, macOS, Linux)
After downloading and installing an IDE, you might need to configure it to use the installed compiler. Check the documentation of the respective IDE for instructions on how to do this.

 ## 3. Creating a New C++ Project
Once you have your IDE and compiler set up, you can create a new C++ project and start writing code. In general, follow these steps to create a new C++ project:

 - Open the IDE and create a new project.
 - Select the project type (C++ Application or Console Application).
 - Specify the project name and location.
 - Let the IDE generate the main.cpp and build files (such as Makefile or CMakeLists.txt) for you.
 ## Example: Hello World in C++
Create a new file called main.cpp within your project and include this code:
```
#include <iostream>

int main() {
    std::cout << "Hello, World!" << std::endl;
    return 0;
}
```
Then, follow the IDE’s instructions to build and run your program. You should see “Hello, World!” displayed in the console.

 ##  Summary
Setting up C++ involves:

 - Installing a compiler (e.g. GCC, MinGW, or MSVC)
 - Configuring an IDE (e.g. Visual Studio, Eclipse, or Code::Blocks)
 - Creating a new C++ project and writing code
By following these steps, you’ll be ready to start developing C++ applications!
<hr>
 # Installing C++ 🧩
 Before you can start programming in C++, you will need to have a compiler installed on your system. A compiler is a program that converts the C++ code you write into an executable file that your computer can run. There are several popular C++ compilers to choose from, depending on your operating system and preference.

 ## Windows <a name ="window"></a>
For Windows, one popular option is to install the Microsoft [Visual Studio](https://visualstudio.microsoft.com/vs/) IDE, which includes the Microsoft Visual C++ compiler.

Alternatively, you can also install the MinGW-w64 compiler, which is a Windows port of the GNU Compiler Collection (GCC). To install MinGW-w64, follow these steps:

 - Download the installer from [here](https://sourceforge.net/projects/mingw-w64/files/).
 - Run the installer and select your desired architecture, version, and install location.
 - Add the bin folder inside the installation directory to your system’s PATH environment variable.

 ## macOS <a name ="mac"></a>
For macOS, you can install the Apple LLVM clang compiler which is part of the Xcode Command Line Tools. To do this, open a terminal and enter:
```
xcode-select --install
```
This will prompt a dialog to install the Command Line Tools, which includes the clang compiler.

 ## Linux <a name ="linux"></a>
On Linux, you can install the GNU Compiler Collection (GCC) through your distribution’s package manager. Here are some examples for popular Linux distributions:

 - Ubuntu, Debian, and derivatives:
```
sudo apt-get install g++ build-essential
```
 - Fedora, CentOS, RHEL, and derivatives:
```
sudo dnf install gcc-c++ make
```
 - Arch Linux and derivatives:
```
sudo pacman -S gcc make
```
 ### Checking the Installation
To confirm that the compiler is installed and available on your system, open a terminal/command prompt, and enter the following command:
```
g++ --version
```
You should see output displaying the version of your installed C++ compiler.

Now you’re ready to start writing and compiling your C++ code!

 # Code Editors 🧰
Code editors are programs specifically designed for editing, managing and writing source code. They offer a wide range of features that make the development process easier and faster. Here’s a brief introduction to some of the most popular code editors for C++:

 - [Visual Studio Code (VSCode)](https://code.visualstudio.com/): Visual Studio Code is a popular, free, open-source, and lightweight code editor developed by Microsoft. It has built-in support for C++, along with an extensive library of extensions and plugins.

 - [Sublime Text](https://www.sublimetext.com/): Sublime Text is a cross-platform text editor that is quite popular among developers due to its speed and minimalist design. It supports C++ with the help of plugins and has a variety of themes and packages available for customization

 - [Dev-C++](https://www.bloodshed.net/): is a free full-featured integrated development environment (IDE) distributed under the GNU General Public License for programming in C and C++. It was originally developed by Colin Laplace and first released in 1998. It is written in Delphi. It is bundled with, and uses, the MinGW or TDM-GCC 64bit port of the GCC as its compiler
These are just a few examples, and there are many other code editors available, including Atom, Notepad++, and Geany. They all have their features and may suit different developers’ needs. Finding the right code editor is often a matter of personal preference and workflow.

To work with C++ in your chosen code editor, you often need to install some additional tools and add-ons, such as compilers, linters, and debugger support. Make sure to follow the instructions provided by the editor’s documentation to set up C++ correctly.



