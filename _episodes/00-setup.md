---
title: "Setup"
teaching: 0
exercises: 10
questions:
- "How do I setup the software for this workshop?"
- "What are the workshop materials for this workshop?"
- "What data are we using for this workshop?"
- "What is the pre-requisite knowledge I need and where do I get it?"
- "What other information do I need to know before I begin?"
objectives:
- "Install necessary software for this workshop"
- "Download data and other setup files for this workshop"
- "Get context of data used in this workshop"
- "Confirm I have the previous knowledge necessary to participate in this workshop"

keypoints:
- "Install X software"
- "Install Y software"
- "Download data/setup files x,y,z"
- "Workshop data is from x, in y format and includes x,y,z types of data"
---

## Software setup
We will be using Jupyter notebook for this workshop. We install the Anaconda navigator. Anaconda is an open source distribution, which provides the easiest way to code in python, especially for data science.

INSTALLATION:
<br></br>
FOR WINDOWS USERS:

1) Go to the following link: https://www.anaconda.com/products/individual
2) Click on the download button and wait for the .EXE file to be downloaded.
3) Double click on the dowloaded file to launch the installer.
4) Click Next.
5) Read the Licensing agreement and click "I agree".
6) Select "Just me" and click "Next"
7) Select a destination folder to install Anaconda and click the Next button.
8) Uncheck the add Anaconda to your PATH environment variable and check the register Anaconda as your default Python. Click Install
9) Click Next
10) Click Next. There is an option to install Pycharm. However, we do not need this tool for this workshop.
11) After a successful installation you will see the “Thanks for installing Anaconda” dialog box

FOR MAC USERS:

1) Download the macos installer by going to the following link https://www.anaconda.com/products/individual and clock on download
2) Open the file my double clicking on it and start the installation.
3) Answer the prompts on the screen.
4) In stallation type, select "Install for me only"
5) Click on continue.
6) After a successful installation you will see the “Thanks for installing Anaconda” dialog box

NOTE:
While we are using jupyter notebook for the purpose of this workshop, we can use any text editor to write our program and run it using the terminal/command prompt.
To do so-
1) Open the command prompt/terminal and type pip install python3
2) Once the installation is complete, open any editor and type you code in it. Make sure you save the file with a .py extension.
3) Go to the command prompt/terminal and navigate to the filder where the file is saved.
4) type python3 "name of the file".py 

  FIXME add/edit  install instructions (automated, see comment)

{% comment %} to add automated software install instructions, add instructions available in the install instructions 
folder \_includes/install_instructions by using code seen below. Add or remove install instructions as needed. {% endcomment %}

{% include install_instructions/editor.html %}
{% include install_instructions/videoconferencing.html %}

## Setup files:

Please download the following files to particpate in the workshop:

FIXME data: 
FIXME script: 

FIXME add links to setup files in `files` folder OR if there are many files, zip setup files, add to `files` folder
and add link to zip file here

## About the Data Used in this Workshop:

(if the workshop uses data)

FIXME add intro/description of data. Including file format and any disciplinary background needed to understand
why the data is gathered and how it is used.

{% include links.md %}
