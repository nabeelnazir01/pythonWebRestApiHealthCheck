## Installations & Setup Steps:
* Install python from here https://www.python.org/downloads/

<img align="center" src="Images/1.png">

* Set paths for python directory and scripts where pip is in windows environment variables
Directory where python is installed:

<img align="center" src="Images/2.png"> 

Directory where scripts like pip are:

<img align="center" src="Images/3.png"> 

Now set these paths in PATH under System variables:

<img align="center" src="Images/4.png"> 

* IDE – Visual Studio Code Installation

Go to https://code.visualstudio.com/.Click Download for Windows

<img align="center" src="Images/5.png"> 

Click Save

<img align="center" src="Images/6.png"> 

Click Run

<img align="center" src="Images/7.png"> 

Select “I accept the agreement”. Than Click Next

<img align="center" src="Images/8.png"> 

Click Next

<img align="center" src="Images/9.png"> 

Click Next

<img align="center" src="Images/10.png"> 

Click Next

<img align="center" src="Images/11.png"> 

Click Install

<img align="center" src="Images/12.png"> 

Click Finish

<img align="center" src="Images/13.png"> 

## VS Code Configuration:

Now launch VS code IDE and open the python folder containing script. You will
notice it will prompt you to set interpreter

<img align="center" src="Images/14.png">

First click on it and you will see the prompt on top and select the path for python

<img align="center" src="Images/15.png"> 

You will notice this error prompt

<img align="center" src="Images/16.png"> 

In order to fix this manually we will set the path in settings.json file in your
project folder. Navigate to project folder in my case its here. You will see
the .vscode folder, open it

<img align="center" src="Images/17.png"> 

You will see the settings.json file. Now open this in notepad++

<img align="center" src="Images/18.png"> 

It will look like this

<img align="center" src="Images/19.png"> 

Just add the ‘,‘ at the end of first line after true and ensure python.pythonPath
points to where python application is residing.
Save and close this file. Close VScode and relaunch you might have to re-add the interpreter sometimes it takes time for VSCode to read path. Once its
set you will notice in the same place displaying correct version of python installed

<img align="center" src="Images/20.png"> 

Next you will see an error prompt for pylint requesting to install Click on install

<img align="center" src="Images/21.png"> 

Pylint is a tool that checks for errors in Python code, tries to enforce a coding
standard and looks for code smells. It can also look for certain type errors, it can
recommend suggestions about how particular blocks can be refactored and can
offer you details about the code's complexity.

You will see it installing pylint

<img align="center" src="Images/22.png"> 

Now close VScode and re-launch it.

## Pre-requisite Python Modules Installation:

4. Now install the following python libraries:

Lets try to run code. Right click in the script area and select Run Python File in
Terminal

<img align="center" src="Images/23.png"> 

You will notice in the terminal it states we have imported pandas but not installed the library

<img align="center" src="Images/24.png"> 

On the terminal type the following commands:

pip install pandas

pip install requests

pip install xlsxwriter

pip install xlrd

pip install openpyxl