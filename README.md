[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15278228&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
   PROCEDURE OF INSTALLING WINDOWS 11:
1.Check System Requirements:
 You have to Verify that your PC meets the minimum hardware requirements for Windows 11. These typically include a compatible processor, sufficient RAM, and TPM (Trusted Platform Module) version 2.0.
Make sure your system BIOS/UEFI firmware is up to date.
2.Backup Your Data:
Before proceeding with the installation, back up any important files and data to an external drive or cloud storage.
3.Create Installation Media:
Download the Windows 11 installation files from the official Microsoft website or use the Media Creation Tool to create a bootable USB drive.
4.Boot from Installation Media:
Insert the bootable USB drive into your PC and restart it.And
Enter the BIOS/UEFI settings (usually by pressing a key like F2, F12, Delete during startup) and set the USB drive as the primary boot device.
5.Install Windows 11:
Follow the on-screen instructions to start the Windows 11 installation process.Select your language, time, and keyboard preferences.
6.Partition and Format:
Choose the partition where you want to install Windows 11. You can format the partition if needed.
7.Set Up Windows 11:
Once installed, follow the on-screen prompts to personalize your settings, such as choosing your region, keyboard layout, and Wi-Fi network.





2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
   PROCEDURE ON HOW TO INSTALL VS CODE
a)Download the Installer:
Go to the official VS Code website and download the installer for Windows.
b)Run the Installer:
Once the download completes, run the installer (.exe file).
c)Follow Setup Wizard:
Follow the prompts in the setup wizard. You can customize installation options if needed.
d)Finish Installation:
Click "Finish" once the installation completes.
e)Open VS Code:
VS Code should now be installed on your system. You can open it from the Start menu or desktop shortcut.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   GIT INSTALLATION AND CONFIGURATION
   1.Git installation.
1)Download Git Installer:
Visit the official Git website and download the Windows installer.
2)Run the Installer:Once the download is complete, run the installer (.exe file).
3)Follow Setup Wizard:
Follow the prompts in the setup wizard. You can choose the default options or customize as needed (e.g., choosing the editor, adjusting PATH environment).
4)Finish Installation:
Click "Finish" once the installation completes.
5)Verify Installation:
Open a command prompt (cmd) or Git Bash (installed alongside Git) and type git --version. You should see the Git version information if installed correctly.
2.Creating github account
a)Visit GitHub Website:
Open your web browser and go to GitHub's website.
b)Sign Up:
Click on the "Sign up" button located at the top right corner of the GitHub homepage.
c)Enter Your Information:
Fill out the sign-up form with the following details:
Username: Choose a unique username that will be your identity on GitHub.
Email Address: Provide a valid email address. This will be used for account notifications and password recovery.
Password: Create a strong password to secure your account.Verify Your Email Address:fter signing up, GitHub will send a verification email to the email address you provided. Check your inbox and click on the verification link in the email to verify your email address.
After signing up, GitHub will send a verification email to the email address you provided. Check your inbox and click on the verification link in the email to verify your email address.
d)Set Up Your Profile:Once verified, you can set up your profile by adding a profile picture, bio, and other details. This helps other users identify you and learn more about your contributions.
3.Initializing Git repository
Navigate to Your Project Directory:Open your terminal  in Git Bash on Windows.Use the cd command to navigate to your project directory.
Initialize Git:
Once you are in your project directory, initialize a new Git repository using the git init command:This command initializes a new Git repository in the current directory. It creates a hidden .git directory where Git stores all the metadata and configuration for your repository.
Verify Initialization:
After running git init, you should see a message like/path/to/your/project/.git/
4.Adding Files to the Repository.
a0Add Your Project Files:
Start adding files to your project directory that you want Git to track. For example, create a new file or move existing project files into this directory.
b)Stage and Commit Changes:
Use the following commands to stage your changes (tell Git which files to track) and commit them (save changes to the repository):# Stage all files in the current directory
git add .
# Commit the staged changes with a commit message
git commit -m "Initial commit"









4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  PYTHON INSTALLATION AND ENVIROMENTAL SETUP GUIDE:
1)Download Python Installer:
Visit the official Python website http://wwww.python.org  and download the latest version of Python.
2) Run the Installer:Run the downloaded .exe file.
3)Verify Installation:After installation, open a terminal or command prompt and type python --version  # or python3 --version on some systems

set up a virtual environment (recommended), installed packages using pip, and optionally set up an IDE. This setup provides you with a powerful environment to develop Python applications efficiently. Adjust the steps according to your operating system and preferences to suit your development needs.



5. Install Package Managers:
   If applicable, install package managers like pip (Python).
   PYTHON PACKAGE MANAGERS:pip is the default package manager for Python and is used to install packages from the Python Package Index (PyPI) and other repositories.
   How to install pip:
   1)Ensure Python is Installed.
   2)Install pip.python get-pip.py
   Installing Packages:pip install package_name
   verfy installation:pip --version to confirm the version of pip that you have.






6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
By following these steps, you'll successfully install MySQL on your system and be ready to start using it for database management and development.
1)Download MySQL Installer:download mysql installer from the following link https://dev.mysql.com/downloads/windows/installer/5.7.html
2)Run the Installer:Once the download is complete, run the downloaded .msi file.
3)Choose Setup Type:Select "Custom" setup to choose individual components or "Complete" for a full installation.And then click next.
4)Select Products:Choose MySQL Server and any other components you need (e.g., MySQL Workbench for GUI management).
5)Configure MySQL Server:Configure the MySQL Server installation by setting the root password and other options as needed.
6)Execute Installation:Click "Execute" to start the installation process.
7)Complete Installation:Once installation finishes, click "Finish" to exit the installer.
7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 


- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
