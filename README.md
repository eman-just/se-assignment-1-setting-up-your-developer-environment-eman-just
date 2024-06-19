[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15294538&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
  
   UPGRADING TO WINDOWS 11:
First, make sure your PC meets the minimum requirements. To check, do the following:

Open the Settings app.
Next, click on "Update & Security" and then "Windows Update". 
Click the "Check for updates" button to see if Windows 11 is available for download.
When the upgrade is ready, see the option to download and install it, click on it and follow the on-screen prompts.

   DOWNLOADING AND INSTALLATION  WINDOWS 11
After downloading Windows 11, create an installation media:
Visit the Microsoft website at https://www.microsoft.com/software-download/windows11.
Select Windows 11 and download the installation file, which is straightforward.

   To install Windows 11: 
Insert the USB drive with the installation file into your computer and restart it.
During setup, chose your language, enter your product key, and select where to install Windows (usually the main hard drive).
Wait for the installation to finish, which takes some time.

2. Install a Text Editor or Integrated Development Environment (IDE):

   DOWNLOADING AND INSTALLING VISUAL STUDIO CODE :

Visit https://code.visualstudio.com/Download on your browser.
Find the download link suitable for your Windows and click to begin the download.
Once the downloaded, navigate to your Downloads folder or the path you saved it to go using File Explorer.
Right-click on the downloaded file and chose "Run as administrator".
In the setup menu that appears, click on "Accept the agreement" and then proceeded with "Next".
The setup process is quite straightforward; just keep clicking "Next" until you reach the "Select Additional Tasks" step.
Here, check the options for "Open with Code" as you want it to integrate with your system.
After that, click "Next", followed by "Install".
Once the installation completed, click on "Finish".

3. Set Up Version Control System:
   GIT INSTALLATION:
On your browser, type "download Git" and enter.
Click on the download link for the latest version of Git for Windows.
After downloading, open the executable (.exe) file.
In the setup menu, click "Next" to continue.
At the "Select Components" step on the setup menu, make sure to check "Additional icons". 
Continue clicking "Next" until you reach the "Install" button.
Finally, click "Install", and then "Finish" once the installation completed.

   SETTING UP GIT AND GITHUB:
Next, you need to configure Git with your username and email.
Open Git Bash, which is installed along with Git (Run as an administrator).
Type in the following commands, replacing "Your Name" and "your_email@example.com" with your own information:

{git config --global user.name "Your Name"}
{git config --global user.email "your_email@example.com"}

After configuring Git, create a GitHub account:
Visit https://github.com/ and sign up for a new account. 
Follow the steps to verify your email address and set up your profile.

Then, initialize a Git repository for your project:
Navigate to your project directory using File Explorer.
Right-click inside the folder and select "Git Bash Here" to open Git Bash.
Inside Git Bash, initialize a new Git repository with the command:
{git init}

Finally, make your first commit to the repository:
Add all the files in your project to the staging area with the command:
{git add .}

Commit the changes with a message:
{git commit -m "Initial commit"}

4. Install Necessary Programming Languages and Runtimes:
  
  PYTHON INSTALLATION:
Visit http://www.python.org in your browser.
Click on the download link to get the latest version of Python.
Once the download is complete, click on the downloaded executable (.exe) file to start the installation.
During the installation process, make sure to select the option to "add Python to PATH". 
Continue with the default settings and click "Install".
After installation, verify Python is installed correctly by opening Command Prompt and typing:
{python --version}

5. Install Package Managers:

  INSTALL PIP (PYTHON):
Python installations usually come with pip. 
To check, type the following code in command prompt. (remember to run as admin):
{python -m pip --version}

6. Configure a Database (MySQL):

Visit https://dev.mysql.com/downloads/windows/installer/5.7.html in your browser.
Check on the installer for windows with the bigger size, not the one for web community and click download.
Don't sign up or login.
click on the  part that says, "No thanks, just start your download".
Once the download is complete, click on the downloaded executable (.exe) file to start the installation.
Continue with the default settings and click "Install".

7. Explore Extensions and Plugins:

  	EXTENSIONS WITHIN VISUAL STUDIO CODE:
Open Visual Studio Code.
Navigate to Extensions icon on the  right of the screen or use the following key combination (Ctrl+Shift+X).
Type in the search bar the name of the extension you would like to instalL.
Always select the one that is verified by microsoft- it has a blue tick below it.
Proceed to install.
