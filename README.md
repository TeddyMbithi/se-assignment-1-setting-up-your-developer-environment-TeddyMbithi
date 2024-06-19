[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15283937&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

   Step 3: Download the Windows 11 installation media

Go to the official Microsoft website and download the Windows 11 installation media (ISO file).
Alternatively, use the Media Creation Tool to create a bootable USB drive.
Step 1: Create a bootable USB drive (optional)

If you downloaded the ISO file, you can create a bootable USB drive using a tool like Rufus.
Insert a blank USB drive and follow the instructions to create a bootable drive.
Step 2: Boot from the installation media

Insert the bootable USB drive or CD/DVD and restart your PC.
Enter the BIOS settings and set the USB drive or CD/DVD as the first boot device.
Save the changes and restart your PC.
Step 3: Start the installation process

The Windows 11 installation wizard will start automatically.
Follow the prompts to select your language, time zone, and other settings.
Step 4: Accept the license agreement

Read and accept the Windows 11 license agreement.
Step 5: Choose the installation type

Choose whether to keep your files, apps, and settings (Upgrade) or start with a clean installation (Clean Install).
Step 6: Install Windows 11

The installation process will begin, which may take several minutes or hours depending on your PC’s specifications.
Step 7: Set up your Windows 11 account

Create a new Microsoft account or sign in with an existing one.
Set up your Windows 11 desktop, including your wallpaper, theme, and settings.
Step 8: Install updates and drivers

Windows 11 will automatically install any available updates and drivers.
You may need to restart your PC multiple times during this process.
Step 9: Finalize your Windows 11 installation

Once the installation is complete, you’ll be prompted to set up your Windows 11 desktop, including your wallpaper, theme, and settings.
You can also install any additional software or apps you need.


2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

Step 1: Run the Installer

Once the download is complete, run the installer by double-clicking on the downloaded file.
Follow the prompts to accept the terms and conditions and choose the installation location.
Step 2: Choose the Installation Options

Choose the installation options:
Add to PATH: Adds Visual Studio Code to your system’s PATH environment variable, allowing you to open VS Code from the command line.
Register Code as an editor for supported file types: Registers VS Code as the default editor for supported file types.
Check the box to add VS Code to your PATH: Adds VS Code to your system’s PATH environment variable.
Step 3: Install Visual Studio Code

Click the “Install” button to begin the installation process.
Wait for the installation to complete.
Step 4: Launch Visual Studio Code

Once the installation is complete, click the “Finish” button.
Launch Visual Studio Code by double-clicking on the VS Code icon on your desktop or by searching for it in the Start menu.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

         Step 1: Install Git

         Install Git on your operating system:
         For Windows: Download and install the latest version of Git from the official Git website.
         For Linux: Install Git using your distribution’s package manager (e.g., sudo apt-get install git on Ubuntu-based systems).
         For Mac: Install Git using Homebrew (if you have it installed) or download the latest version from the official Git website.
         Step 2: Set up Git Environment

         Set up your Git environment by configuring your username and email address:
         Run the command git config --global user.name "Your Name" to set your username.
         Run the command git config --global user.email "your_email@example.com" to set your email address.
         Step 3: Initialize a New Git Repository

         Create a new directory for your project and navigate to it:
         Run the command mkdir myproject to create a new directory named myproject.
         Run the command cd myproject to navigate to the myproject directory.
         Initialize a new Git repository by running the command git init.
         Step 4: Add Files to the Repository

         Add files to your repository by running the command git add <file_name> (replace <file_name> with the name of the file you want to add).
         To add all files in the current directory, run the command git add ..
         Step 5: Commit Changes

         Commit your changes by running the command git commit -m "Initial commit" (replace "Initial commit" with a meaningful commit message).

4. Install Necessary Programming Languages and Runtime:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtime. Ensure you have the necessary tools to build and execute your code.

            
            Go to the official Python website at www.python.org.
            Click on the “Download” button and select the version of Python you want to install (e.g., Python 3.9.6).
            Follow the prompts to download and install Python.
            Choose the installation location and select the components you want to install (e.g., IDLE, pip, and documentation).
            If you want to be able to run Python from the command line without specifying the full path, you need to add Python to your system’s PATH environment variable.
            Right-click the Start button and select System.
            Click on Advanced system settings.
            Click on Environment Variables.
            Under the System Variables section, scroll down and find the Path variable, then click Edit.
            Click New and enter the path to the Python executable (e.g., C:\Python39\bin).
            Click OK to close all the windows.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

               Download MySQL Installer from https://dev.mysql.com/downloads/installer/ and execute it.
               Determine the setup type to use for the initial installation of MySQL products. For example:

               Developer Default: Provides a setup type that includes the selected version of MySQL Server and other MySQL tools related to MySQL development, such as MySQL Workbench.

               Server Only: Provides a setup for the selected version of MySQL Server without other products.

               Custom: Enables you to select any version of MySQL Server and other MySQL products.

               Install the server instance (and products) and then begin the server configuration by following the onscreen instructions. For more information about each individual step, see Section 2.3.3.3.1, “MySQL Server Configuration with MySQL Installer”.

               MySQL is now installed. If you configured MySQL as a service, then Windows automatically starts the MySQL server every time you restart the system. Also, this process installs the MySQL Installer application on the local host, which you can use later to upgrade or reconfigure MySQL server.


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
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
