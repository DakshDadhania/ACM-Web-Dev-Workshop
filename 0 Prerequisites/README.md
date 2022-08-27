# Welcome to ACM-Web-Dev-Workshop-2022
![ACM](https://dl.acm.org/specs/products/acm/releasedAssets/images/acm-logo-1.png)


Welcome to the ACM Complete Web Development Workshop 2022! We, at ACM present before you all the web development bootcamp in which we will be teaching you everything you need to know about web dev to get started.  From HTML, CSS, JS to further experimenting with the DOM and to complete MERN stack, in the most concise manner possible. All of this would be accompanied by fun tasks and doubt-solving sessions each week.

# Tools required 
1) VS Code 
2) Git (installed in your computer)
3) Figma installed
4) Live server Extension in VS CODE

# Git and Github
Git is an open-source system, that is used for version control while developing software. It is used for tracking changes, and is meant for easy collaborations.
Github is where you can host your git repositories, and collaborate using git on the internet. Github can be used from the browser or from the git command line.

# Introduction to Github

Github is a free and open-source version control system, that helps you keep track of changes to files in a filesystem or repository over time. It helps you track all the changes made to a file or a directory in general, thus enabling development in teams or organizations. Git comes with the git-shell which has a set of commands that can help you perform different operations on your repositories. Github is a service that hosts your repositories online and lets you collaborate with others through it. You can use Github through the browser or the git-shell on your pc.

**How to Install Git and Github**

* Installing Git on Windows

Download Git from [Git for Windows](https://gitforwindows.org/) and install it

* Installing Git on Linux

Determine which Linux distribution your system is based on. [See List of Linux distributions](https://en.wikipedia.org/wiki/List_of_Linux_distributions) – Wikipedia for a list of different Linux Distributions. Most Linux systems – including Ubuntu – are Debian-based.

Debian-based Linux Systems
[Open a terminal window](https://help.ubuntu.com/community/UsingTheTerminal). Copy & paste the following into the terminal window and hit Return. You may be prompted to enter your password.

    sudo apt-get update 
    sudo apt-get upgrade
    sudo apt-get install git

You can use Git now.

* **Installing Git on a Mac** 

[Open a terminal window.](https://www.youtube.com/watch?v=zw7Nd67_aFw)

Step 1 – Install [Homebrew](https://brew.sh/)
Homebrew simplifies the installation of software on the Mac OS X operating system.


Copy & paste the following into the terminal window and hit Return.


    ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
    brew doctor

You will be offered to install the Command Line Developer Tools from Apple. Confirm by clicking Install. After the installation finished, continue installing Homebrew by hitting **Return** again.

Step 2 – Install Git

Copy & paste the following into the terminal window and hit Return.

    brew install git

You can use Git now.

# Commands you'll need in this project

First, create a Github ID, then move on.

Clone the ACM-Web-Dev-Workshop repository 

`git clone https://github.com/DakshDadhania/ACM-Web-Dev-Workshop.git`

Create a branch---  `git checkout -b <branch-name>`

Change into another branch---  `git checkout <branch-name>`

Adding Files to be committed

`git add <filename1> <folder_name>\<filename2>` - Adds filename1 in current directory and filename2 in the folder.

`git add .` - Adds all files in the current directory

Adding a commit message---  `git commit -m "<message>"`

To check the status of files---  `git status`

Pushing the committed changes to the GitHub repository---  `git push origin <branch-name>`

Note: Never push to the main branch, create your own branch and change into that and then push.

Pulling changes from the GitHub repository--- `git pull origin <branch-name>`

A detailed Article on Git and Github

# Visual Studio Code
We Highly recommend using VS Code with its live compiler extension for web development.

Install it from their official [website](https://code.visualstudio.com/)

Set up `Live Server` by going through this [website](https://www.freecodecamp.org/news/vscode-live-server-auto-refresh-browser/)

# Setting up this repository on your device

Open the Terminal in your project's location if you're using Mac or Linux. Windows users can open Git Bash which is a terminal installed along with Git(Right-click and click on Git Bash here).
Configure user information for all local repositories:
Sets the name you want attached to your commit transactions 
`**git config --global user.name "<name>"**`

Sets the email you want attached to your commit transactions   
`**git config --global user.email "<email address>"**`

Cloning and pull codes:
Clone the repository using  
`**git clone https://github.com/DakshDadhania/ACM-Web-Dev-Workshop.git** `

Move to this directory using 
`**cd ACM-Web-Dev-Workshop**`

Create a new branch with your name using the command 
`**git checkout -b <branch-name>**`
with branch name in format "-". eg.- 
`**git checkout -b <your-name-here>**`

All commits should be made to your own branch, Never commit to master. To prevent this always check what branch you're on before committing any changes, the command to check current branch "  `git branch  "`, the command to checkout(change to) a branch, 
`**git checkout <branch-name>**`

To pull solutions after they are uploaded to main, change branch to master and do a git pull.
`**git checkout main  |  git pull origin main**`

Make Sure to switch back to your own branch after viewing the solutions

# Task Submission
Open Git Bash in your project folder and run the following commands to make a folder for each week

Example:
**mkdir week1**

**cd week1**

**code .**

After your task is done you need to push it to GitHub
Make sure you are in the root of your project and not in your week folder before running these commands. You can come out of your week folder with the command
`**cd ..**`

Add files to be committed using the command 
    `**git add .**` 

(the "." after add means all files in the current directory will be added)

Add a descriptive commit message for the same. Command- 
    `**git commit -m "<message>".**`

Mention any errors or issues in the code in the commit message, if any.

Finally, push your code. command - 
    `**git push origin <branch-name>**`

    git checkout -b <branch-name> // Use your full name in the format first-last for your branch name
    git checkout <branch-name>	// to make sure you are in your own branch
    git add .	// adds all files and subfolders to be committed in the current directory
    git commit -m "message"
    git push origin <branch-name>

All tasks and resources will be posted [here](https://github.com/DakshDadhania/ACM-Web-Dev-Workshop/)

Approach me in case on any queries.. :)







[wiki](https://github.com/DakshDadhania/ACM-Web-Dev-Workshop/) for further instructions

<br>

[![Website](https://img.shields.io/badge/ACM_Website-5237B5?style=for-the-badge&logo=About.ACM&logoColor=white)](https://manipal.acm.org/) &nbsp;
[![Instagram](https://img.shields.io/badge/ACM-Manipal-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)](https://www.instagram.com/acm_manipal/?hl=en) &nbsp;
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/school/acm-manipal/) &nbsp;









This Repository contains all the workshop material for ACM Web Dev Workshop
