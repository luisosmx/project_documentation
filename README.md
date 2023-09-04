# How to install and authenticate GitHub Desktop on Windows

## Introduction of the project

GitHub Desktop is a powerful tool that simplifies the process of collaboration and project management using Git and GitHub. With an intuitive and easy-to-use interface, GitHub Desktop makes it easy to create, clone, and manage repositories, letting you focus on software development without the complexity of command line commands.

This guide will take you through the steps required to install GitHub Desktop on your Windows operating system. You'll learn how to download the installer, set up the tool, and make initial settings to start getting the most out of this collaborative development platform.

## Previous requirements

Before you begin installing GitHub Desktop, make sure you meet the following requirements:

- A Windows operating system (Windows 7 or higher).
- Internet access to download the installer.
- A GitHub account (if you don't already have one, you can create one for free at https://github.com).


### Installation process in Windows

Here are the steps you need to follow to install GitHub Desktop on your Windows system:

1.  Download the Installer: Access the official GitHub Desktop site at https://desktop.github.com/ and download the installer by clicking "Download for Windows".

    ![Alt text](imgs/git_dekt_down.png)



2. Run the installer: Locate the downloaded file, usually called GitHubDesktopSetup.exe, and double-click it to run it.

    ![Alt text](imgs/download_program.png)
    - When executed, a screen like the following will appear:
    ![Alt text](imgs/git_install.png)

3. Installation: Follow the instructions of the installation wizard, accepting the license terms and choosing the installation options.
    - We select the option to enter github.com
    ![Alt text](imgs/git_init.png)

    > **NOTE**  
    If you select the "GitHub Enterprise" option when logging in, you can enter the URLs and credentials of your GitHub Enterprise instance instead of using GitHub.com. This is useful for organizations that have deployed their own GitHub Enterprise instance and want to manage their repositories and workflows in their controlled environment.    
        
4. Sign in: After installation, start GitHub Desktop and sign in with your GitHub account.
    
    -  When making the selection, a web page like the following will open, in which we must enter our email and password that we have registered in GitHub. After entering these data we select the "Login" button.

        ![!\[Alt text\](imgs/git_init.png)](imgs/Screenshot_17.png)



    - We select the "Authorize desktop" button to sync GitHub Desktop and the GitHub website.

         ![Alt text](imgs/Screenshot_18.png)


5. Initial Configuration (Optional): Customize GitHub Desktop preferences to suit your needs.
    - Enter your username and password.

        ![Alt text](imgs/Screenshot_20.png)

    > **NOTE**  
    Usually the platform autofills the fields when we select the option "Use my GitHub account name and email address".

    - GitHub Desktop gives you options to start working with Git repositories on your local computer. You can choose the option that best suits your current needs and start collaborating on software development projects.

        #### Clone a Repository: 
        This option allows you to clone (download) a GitHub repository to your local computer. Simply provide the URL of the repository you want to clone and select the location on your computer where you want to save the repository.

        #### Create a Repository: 
        If you want to start a new project, you can create a repository from scratch directly from GitHub Desktop. This will set up a new local repository and allow you to commit and push changes to a remote GitHub repository.

        #### Add an Existing Repository: 
        If you already have a Git repository on your local computer that you want to manage with GitHub Desktop, you can select this option. Just choose the folder where the repository is located and GitHub Desktop will recognize it.

    - This time ***Clone a Repository*** will be used.

        ![Alt text](imgs/Screenshot_21.png)
    

    ![Alt text](imgs/Screenshot_22.png)


