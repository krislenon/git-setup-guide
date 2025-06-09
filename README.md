# Introduction
This guide will help you install Git and clone a Git repository in your Windows environment. 

# Prerequisites
## What will you need?
- A Windows PC
- An internet connection
- Access to GitHub


## Step 1: Download & Install Git
1. Go to the Git official website: [https://git-scm.com/downloads](https://git-scm.com/downloads)
2. Download the latest version for Windows.
3. Run the installer and proceed through the setup wizard.
4. You can leave the default options selected during installation.


## Step 2: Verify Installation
1. Open **Command Prompt**.
2. Type the following command:
  ```
  git --version
  ```
3. If Git is installed correctly, you’ll see a version number (e.g., `git version 2.42.0`).


## Step 3: Clone a Repository
1. Go to the GitHub page of the repository you want to clone.
2. Click the green **Code** button and copy the HTTPS link.
3. In Command Prompt, navigate to the folder where you want to store the repository.
4. Run the following command (replace the URL with your copied link):
  ```
  git clone <URL>
  ```
5. The repository will be downloaded into your current directory.

# Conclusion / Next Steps
After cloning, you can navigate into the repository folder using:
  ```
  cd repo-name
  ```
From here, you can start exploring or editing the code!
