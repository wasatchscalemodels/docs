# FireBox : Set Up a Development Environment

Setting up a development environment to make changes to the FireBox command station's operation is a simple process. You will need to install Visual Studio code, install the PlatformIO extension, and clone the code onto your computer.

## 1 - Install VSCode and PlatformIO
Follow the instructions at https://platformio.org/install/ide?install=vscode to install PlatformIO on top of VSCode.

## 2 - Install Github Desktop
To get the source code for FireBox onto your computer, we will use Git. Git is a version control system that allows you to quickly and easily retrieve the most recent version of the code. 

If you're already familiar with Git and Github, you can skip ahead to the next step. 

We will use the Github Desktop GUI since it is the most simple way to get the code on your computer. It runs on MacOS and Windows. If you're using Linux, you can use the command line or other GUI programs like SourceTree.

Start by installing Github Desktop on your system: https://desktop.github.com/

## 3 - Clone the Repository 

Once you've installed Github Desktop (or if you already know Git), head on over to https://github.com/DCC-EX/CommandStation. Log into Github and click the ```Fork``` button in the top right hand corner of the screen. This will create a copy of the code for you that you can work on and save your changes to. 

From the page containing your newly forked code, click the Clone button, and copy the URL that pops up. Head back on over to Github Desktop, and go to ```File -> Clone Repository```. Select the URL option, paste the URL from your fork in, and select where to put the files. Click clone, and that's it!

## 4 - Start Coding

Go to Visual Studio Code, open PlatformIO Home, and select open project. Navigate to the folder that you just cloned onto your system, and click ```Open```. 

Configuration settings can be changed in the Config.h file, located in the main (root) folder.

_work in progress_