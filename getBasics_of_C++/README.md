Getting Started With C++
C++ is a general-purpose programming language that supports object-oriented programming.

You can run C++ on your computer using the following two methods:

Run C++ online
Install C++ on your computer
In this tutorial, you will learn both methods.

Run C++ Online
To run C++ code, you need to have a C++ compiler installed on your system. However, if you want to start immediately, you can use our free online C++ compiler.

Online C++ Compiler
Online C++ Compiler
The online compiler enables you to run C++ code directly in your browser—no installation required.

Install C++ on Your Computer
For those who prefer to install C++ on your computer, this guide will walk you through the installation process on Windows, macOS, or Linux (Ubuntu).

Windows | Mac | Linux

To setup a C++ programming environment on Windows, you'll need two main components:

VS Code: A text editor to write your code,
MinGW: A compiler that turns your C++ code into an executable program.
Follow the steps below to install C++ on Windows:

Install VS Code
Download MinGW Compiler
Run the Installer
Add MinGW to System PATH
Install C/C++ Extension in VS Code
Here's a detailed explanation of each of the steps.

Step 1: Install VS Code
Go to the VS Code Official website and download the Windows installer. Once the download is complete, run the installer and follow the installation process.

Click Finish to complete the installation process.

Step 2: Download MinGW Compiler
Go to MinGW Compiler Download and download the MinGW installation manager.

C++ MinGW Installation
C++ MinGW Installation
Step 3: Run the Installer
Now, go to your downloads folder and run the installer you just downloaded. You will be prompted to this screen.

C++ Run MinGW Installer
C++ Run MinGW Installer
Click on Continue and wait till the download is completed.

Include gcc-core package

During installation, you will be prompted to select the components to install. Mark mingw32-base and mingw32-gcc-g++ for installation, click on installation, and apply changes.

C++ GCC-Core Package Installation
C++ GCC-Core Package Installation
Step 4: Add MinGW to System PATH
Go to the folder, double-click on the MinGW folder, and copy its location.

C:\MinGW\bin
Search environment variable on the terminal. In system properties, click on environment variables. You will be prompted to the screen below.

C++ Setting Environment Variables
C++ Setting Environment Variables
Then, find the Path variable in the System variables section and click on Edit. Click New and add the path to the bin directory within your MinGW installation (i.e. C:\MinGW\bin)

Finally, close all the dialogues with the Ok button.

Step 5: Install C/C++ Extension in VS Code
Open VS Code and click on Extensions on the left side of the window.

Then, search for C/C++ by Microsoft in the Extensions and click on install.

Installing C++ Extension in Windows
Installing C++ Extension in Windows
Now, you are all set to run C++ code inside your VS Code.

Run Your First C++ Program
First open VS Code, click on the File in the top menu and then select New File.

Create a New File in VS Code
Create a New File in VS Code
Then, save this file with a .cpp extension by clicking on File again, then Save As, and type your filename ending in .cpp. (Here, we are saving it as hello.cpp)

Now, write the following code into your file:

To install C++ on your Mac, you'll need two main components:

VS Code: A text editor to write your code,
Clang: A default compiler in mac that turns your C++ code into an executable program.
Follow the steps below to install C++ on macOs,

Install VS Code
Install C++ Extension
Check for C++ Compiler
Here is a detailed explanation of each of the steps:

Step 1: Install VS Code
Go to the VS Code official website and download the zipped file. Once the download is complete, open the zipped file.

In Finder, open a new window and navigate to the Applications folder. Drag the VS Code application from the zip file into the Applications folder to install it.

You can now launch VS Code directly from the Applications folder.

Step 2: Install C++ Extension
Open VS Code and click on the Extension in the right side of the screen. Search for C/C++ by Microsoft in the Extensions and click on install.

Installing C++ Extension in macOS
Installing C Extension in macOS
Step 4: Check for C++ Compiler
The macOS generally comes with Clang installed, which can be used as a C++ compiler. You can verify its installation by typing the following command in the terminal.

clang –-version
Checking Clang Version
Checking Clang Version
If the output on your screen does not match the screenshot above showing the version of Clang, you may need to install Xcode Command Line Tools. You can do this by running the following command in your terminal

xcode-select --install
Now, you are all set to run C++ code inside your VS Code.

Linux has various distributions, and the installation process differs slightly from each other. For now, we will focus on Ubuntu distribution.

To run a C++ program in Linux, you need two things:

VS Code: An editor to craft your code.
g++: A part of the GNU Compiler Collection, g++ compiles C++ code into executable programs.
Install VS Code
Install g++
Step 1: Install VS Code
Open the Terminal and type

sudo apt update 
This command updates your package lists to ensure you get the latest versions of your software.

Proceed to install VS Code with

sudo snap install code --classic 
Install VS Code in Linux
Install VS Code in Linux
Step 2: Install g++
Most linux distros including Ubuntu come with g++ preinstalled. You can check this by using the following command in the terminal.

g++ --version
If you don't have one, you can install it with:

sudo apt install g++
Run Your First C++ Program
First open VS Code, click on the File in the top menu and then select New File.

Create a New File in VS Code
Create a New File in VS Code
Then, save this file with a .cpp extension by clicking on File again, then Save As, and type your filename ending in .cpp. (Here, we are saving it as hello.cpp)

Now, write the following code into your file:

#include <iostream>
int main() {
    std::cout << "Hello World";
    return 0;
}
Run Code
Then click on the run button on the top right side of your screen.

Hello World in C++
Hello World in C++
You should see Hello World printed to the command prompt.

For Linux System

To run your C++ program on Linux, go to the Terminal, navigate to the directory containing your file, and type:

g++ hello.cpp -o hello 
Run your program using

./hello 
Now that you have set everything up to run C++ programs on your computer, you'll be learning how the basic program works in C++ in the next tutorial.

