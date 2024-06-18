[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15244162&assignment_repo_type=AssignmentRepo)

# Dev_Setup

Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1.  Select Your Operating System (OS):
    Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

    Documentation:

    My best Operating system that suits my preference and project requirements is Windows. So, I have installed Windows 11 and the following are all steps and process I passed through during installation:

    1.  I have downloaded window from https://www.microsoft.com/software-download/windows11

    2.  I used flash drive of 16GB, app called Rufus and also other laptop for putting the window to the flash.

    3.  Format the drive and set the primary partition as active.

        1. I connected the USB flash drive to my technician PC.
        2. I Right-clicked on Start and then I chose Disk Management.
        3. I Right-clicked the USB drive partition and then I chose Format and I selected the FAT32 file system.
        4. I Right-clicked the USB drive partition and then marked Partition as Active.

    4.  Copy Windows Setup to the USB flash drive.

        I used File Explorer to copy and paste the entire contents of the Windows product DVD or ISO to the USB flash drive.

    5.  Install Windows to the new PC.

        1.  I connected the USB flash drive to a my PC.
        2.  Turned on the PC and press the F12 key and then use arrow keys to choose USB drive.
        3.  Therefor, Windows Setup started and I followed the instructions until thevinstallation of Windows finished.
        4.  After the process finished, I removed the USB flash drive.

2.  Install a Text Editor or Integrated Development Environment (IDE):
    Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

Documentation:

The following are the process and steps of setting up the text editor(Visual Studio Code) but due to that I have already installed it, I will not be able to share the screenshots of that process:

1.  Downloading Visual Studio Code through thefollowing link: https://code.visualstudio.com/Download

2.  After the Visual studio Code was downloaded, I runned the Installer and during the istallation I chose Visual Studio workload.

3.  Based on my requirements and desire, I chose some workloads and components like Web Development and others

4.  After that I clicked Intall button to start the installation.

5.  Finaly, I launched Visual studio code and then modified few things like auto-save, colors, fonts, ... and then I started to code.

3.  Set Up Version Control System:
    Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

    Documentation:

    The following are steps I passed through while istalling and configuring git and opening github account:

    Step 1: Install Git
    Download Git:

    - Visited the official Git website: https://git-scm.com
    - Clicked on "Download" and choose Windows.
      Install Git:

    Runned the downloaded installer and followed the installation wizard, leaving all options as default.

    Step 2: Configure Git
    Openned Terminal

    - Set my username: git config --global user.name "UserName"
    - Set my email: git config --global user.email "my-email"

    Step 3: Create a GitHub Account

    1.  Visit GitHub: https://github.com.

    - Sign Up: I clicked on "Sign up" and follow the instructions to create a new account.

    This is my Github created account: https://github.com/Jdamour12

    Step 4: Create a Repository on GitHub

    1.  Create a new repository:

        - Clicked on the "+" icon in the top right corner and selected "New repository".
        - Fill in the repository name, and chose the visibility.
        - Clicked "Create repository".

    This is my created repository: https://github.com/Jdamour12/E-Shopping

    Step 5: Initialize a Git Repository Locally

    1. Navigated to my project directory: cd /path
    2. Initialize a Git repository: git init

    Step 6: Made my First Commit

    - Add files to the staging area: git add .
    - Commit the files: git commit -m "message"

    Step 7: Link Local Repository to GitHub

- Add the remote repository URL:
  git remote add origin https://github.com/Jdamour12/E-Shopping.git

- Push my changes to GitHub:
  git push -u origin master

4.  Install Necessary Programming Languages and Runtimes:
    Install Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

    Documentation:

    The following are all steps and process I passed through during the installation python and do all necessary so that my codes can run:

    Step 1: Install Python
    Download Python:

    - I visited the official Python website: https://www.python.org.
    - I clicked on the "Downloads" tab and select the appropriate version for my operating system (Windows, macOS, or Linux).
      Install Python:

    - After downloading the installer, I runned it.
    - I ensured to check the box that says "Add Python to PATH" before clicking "Install Now".
    - I openned a terminal and type: python --version; This displayed the version of Python that I installed.

    Step 2: Install Necessary Tools and Libraries

    1. Pip Package Manager:

Python comes with pip, the package installer. I ensured it's up to date by running: python -m pip install --upgrade pip

2.Install Project Dependencies:

If my project requires specific libraries, I will install them using pip. For example, if I need numpy and requests, I will run: pip install numpy requests

Step 3: Verify Tools to Build and Execute Code

1.  Check for Python:

- I will open a terminal or command prompt and run: python; this should open the Python interactive shell, indicating that Python is installed correctly.

2.  Install a Code Editor or IDE:

    I will use Visual Studio Code as my code editor or IDE.

    Step 4: Set Up Virtual Environment

    1. Create a Virtual Environment:

    I will create a virtual environment for my project to manage dependencies. I will navigate to my project directory and run: python -m venv env

    2. Activate the Virtual Environment: source env\Scripts\activate

    3. Install Dependencies in Virtual Environment:

       With the virtual environment activated, I will install the required libraries: pip install library-name requests

5.  Install Package Managers:
    If applicable, install package managers like pip (Python).

    Summary of Installing Package Managers

    Installed Pip for Python:

    - I downloaded and installed Python from the official website, which included pip, the package manager for Python.
    - I upgraded pip to the latest version using: python -m pip install --upgrade pip
    Verified Installation:

    - I verified that pip was installed and functioning by running: pip --version

By following these steps, I successfully installed and verified the package managers necessary for my project's dependencies.

6.  Configure a Database (MySQL):
    Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

    Summary of Configuring MySQL Database

    1. Downloaded and Installed MySQL:

       - I visited the MySQL download page and downloaded the MySQL Installer for Windows.
       - I ran the installer and followed the setup wizard to install MySQL.

    2. Configured MySQL:

       - During the installation, I configured MySQL by setting up the server type, connectivity options, and security settings.
       - I created a root password and, if needed, additional user accounts.

    3. Verified MySQL Installation:

       - I opened the MySQL Command Line Client and logged in using the root account to verify the installation: mysql -u root -p

    4. Created a Database:

       - I created a new database for my project using the following command: CREATE DATABASE my_project_db;

By following these steps, I successfully installed, configured, and verified the MySQL database necessary for my project.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

   Summary of Setting Up Development Environments and Virtualization

   1. Installed Docker:

   - Downloaded and installed Docker from the official site.
   - Verified installation by running: docker --version

   2. Configured Docker:

   - Set up a Dockerfile for my project to define the environment.
   - Built and ran the Docker container: docker build -t my_project .
     docker run -d -p 8000:8000 my_project

   3. Created a Virtual Machine (Optional):

   - Used VirtualBox to create and configure a VM for my project.
   - Installed the necessary OS and dependencies inside the VM.

By using Docker and VirtualBox, I ensured isolated and consistent development environments for my project.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

   Summary of Exploring Extensions and Plugins

   1. Installed Visual Studio Code:

      Downloaded and installed Visual Studio Code (VS Code) from the official site.

   2. Explored and Installed Extensions:

      - Python Extension: For Python development, including syntax highlighting, debugging, and IntelliSense.
      - ESLint: For linting JavaScript code to ensure code quality.
      - Prettier: For code formatting to maintain consistent style.
      - GitLens: To enhance Git capabilities and provide insights into version control.

   3. Configured Extensions:

      Customized settings for each extension to fit my workflow and project requirements.

By exploring and installing these extensions, I enhanced the functionality of my text editor, improving productivity and code quality.

9. Document Your Setup:
   Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process.

   All of the steps I used in my whole setup have been documented above, including the configurations, customizations, and troubleshooting.

   The following are my Github and Github repository:

   Github account: https://github.com/Jdamour12
   Github repository: https://github.com/https://github.com/Jdamour12/E-Shopping.git

#Deliverables:

- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).

- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:\*\*

- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
