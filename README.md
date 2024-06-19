[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15290497&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
  **RESPONSE:**
- I visited the official Windows 11 download page Windows 11 Download and clicked on the "Download Now" button to get the Windows 11 Installation Assistant.
- Following the instructions, I created a bootable USB drive using the Media Creation Tool available on the download page.
- I inserted the bootable USB drive into my PC and restarted it.
- By accessing the boot menu, I selected the USB drive to start the Windows 11 installation process. I followed the on-screen prompts, choosing to perform a clean installation to ensure a fresh start.
- After the installation was complete, I configured my system settings such as language, region, and network connection. I signed in with my Microsoft account to finalize the setup.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
   **RESPONSE**
 - I navigated to the VS Code Download page and downloaded the version for Windows.
 - I ran the downloaded installer and followed the setup wizard's instructions. During the installation, I customized a few options, such as creating a desktop shortcut and adding VS Code to the system PATH for easy command-line access.
 - Upon launching VS Code, I configured my initial settings like choosing a dark theme, setting the font size, and selecting my preferred file icon themes.
   
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   **RESPONSE**
- I visited the Git Download page and downloaded the installer for Windows.
- After downloading, I ran the installer and followed the recommended settings in the setup wizard.
Post-installation, I opened Git Bash to configure my Git settings using the commands:
        - git config --global user.name "Samuel Oluwagbemi"
        - git config --global user.email "samoluwagbemi22@gmail.com"
- I signed up for a GitHub account at GitHub and completed the registration process
- I created a new directory for my project, initialized it as a Git repository, and made my first commit with a README file with the commands:
       - mkdir my_project
       - cd my_project
       - git init
       - echo "# My Project" > README.md
       - git add README.md
       - git commit -m "Initial commit"
  
4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
   **RESPONSE**
- I went to the Python Download page and downloaded the latest Python installer for Windows.
- I ran the installer and made sure to check the option to "Add Python to PATH" for easy command-line usage.
- I followed the installation prompts to complete the setup.
- To confirm that Python was installed correctly, I opened the command prompt and typed python --version.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).
- Since pip comes bundled with Python, I verified its availability by running pip --version in the command prompt.
- As an example, I installed the requests library by executing the command: pip install requests

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
   **RESPONSE**
- I visited the MySQL Installer page and downloaded the Windows installer.
- I ran the installer, selecting the "Developer Default" setup type to include the MySQL server and other necessary components.
- I followed the prompts to set the root password and configured other settings as needed.
- After the installation, I used MySQL Workbench to manage the MySQL server and tested the connection using my root credentials.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
   **RESPONSE**
- 

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
    **RESPONSE**
- I opened VS Code and accessed the Extensions view by clicking the Extensions icon or pressing Ctrl+Shift+X.
- I searched for and installed several useful extensions, including:
         Python: For Python development, including IntelliSense, linting, and debugging.
         GitLens: To enhance Git capabilities within VS Code.
         Prettier: For automatic code formatting.
         Docker: For managing Docker containers directly from VS Code.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process.
   **Summary of My Setup**
- Operating System: I installed and configured Windows 11 for a fresh and modern operating environment.
- IDE: I chose Visual Studio Code, installed it, and set it up with my preferred settings.
- Version Control: I installed Git, set up my user identity, and created a new GitHub account. I also initialized a project repository and made my first commit.
- Programming Language: I installed Python, verified its installation, and tested package installation using pip.
- Database: I installed MySQL, configured it with default developer settings, and connected to it using MySQL Workbench.
- Virtualization: I installed Docker Desktop to manage containerized environments.
Extensions: I installed and configured several extensions in VS Code to enhance my development productivity.

  **Reflection on Challenges:**
During the setup process, I encountered several challenges:
- Compatibility Issues: When installing MySQL, I faced issues with the MySQL Workbench not being fully compatible with Windows 11. I resolved this by ensuring I was using the latest version of MySQL Workbench.
- Configuration Complexities: Setting up Docker Desktop required enabling WSL 2, which was a bit confusing at first. I overcame this by following the detailed instructions provided in the Docker documentation.
- Network or Permission Issues: While installing some software, I ran into permission issues, especially with Git. Running the installers with administrative privileges helped resolve these problems.


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
