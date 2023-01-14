# Week 1 - Getting Started 

Let's get started on how to log into your course-specific account on **ieng6**

## Installing VScode

* Go to the Visual Studio Code website: [VSCode](https://code.visualstudio.com/)
* Follow the instructions on the page - download the correct OS file depending on your device OS
* When installed and opened, the page should look something like this: 

<img src = "images/vscode.png" width = "700">

## Remotely Connecting 

We are going to connect our terminal to a computer in the CSE basement. 

* First we need to install [git](https://git-scm.com/downloads)on our device
* Once installed, we must set our default terminal to use the git bash in VSCode. Here is a thread on how to do this: 
[gitbash-setup](https://stackoverflow.com/questions/42606837/how-do-i-use-bash-on-windows-from-the-visual-studio-code-integrated-terminal/50527994#50527994) 
* Now, to use the ssh command, open the terminal in VSCode by pressing "Cntrl/Cmd" & "`"
* Type in *ssh cs15lwi23zz@ieng6.ucsd.edu* but with the "zz" replaced with the letters of your course specific account 
* If you get the message below, type yes in the terminal followed with your account password. 

**⤇ ssh cs15lwi23zz@ieng6.ucsd.edu
The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])?**

* 
