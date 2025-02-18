# Git, WebStorm, and GitHub Tutorial

This tutorial will guide you through the process of using Git for version control, WebStorm as your Integrated Development Environment (IDE), and GitHub for remote repository hosting and collaboration.

## Table of Contents
1. [Setting Up Git](#setting-up-git)
2. [Configuring WebStorm](#configuring-webstorm)
3. [Creating a GitHub Account](#creating-a-github-account)
4. [Creating a New Repository](#creating-a-new-repository)
5. [Cloning a Repository](#cloning-a-repository)
6. [Making Changes and Committing](#making-changes-and-committing)
7. [Pushing Changes to GitHub](#pushing-changes-to-github)
8. [Creating and Managing Branches](#creating-and-managing-branches)
9. [Merging Branches](#merging-branches)
10. [Collaborating with Others](#collaborating-with-others)
11. [References](#references)

## Setting Up Git

1. Download and install Git from [https://git-scm.com/downloads](https://git-scm.com/downloads)
2. Open a terminal or command prompt and configure your Git username and email:

```
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

## Configuring WebStorm

1. Download and install WebStorm from [https://www.jetbrains.com/webstorm/download/](https://www.jetbrains.com/webstorm/download/)
2. Open WebStorm and go to File > Settings (on Windows/Linux) or WebStorm > Preferences (on macOS)
3. Navigate to Version Control > Git
4. Ensure that the path to the Git executable is correct
5. Click "Test" to verify that WebStorm can use Git

## Creating a GitHub Account

1. Go to [https://github.com/](https://github.com/)
2. Click "Sign up" and follow the registration process
3. Verify your email address

## Creating a New Repository

1. Log in to your GitHub account
2. Click the "+" icon in the top-right corner and select "New repository"
3. Fill in the repository name, description, and other settings
4. Click "Create repository"

## Cloning a Repository

To clone a repository from GitHub to your local machine using WebStorm:

1. In WebStorm, go to File > New > Project from Version Control
2. Paste the repository URL from GitHub
3. Choose the directory where you want to clone the repository
4. Click "Clone"

Alternatively, you can use the command line:

```
git clone https://github.com/username/repository.git
```

## Making Changes and Committing

1. Open the project in WebStorm
2. Make changes to your files
3. In the "Version Control" tool window, you'll see the changed files
4. Select the files you want to commit
5. Write a commit message describing your changes
6. Click "Commit"

Using the command line:

```
git add .
git commit -m "Your commit message here"
```

## Pushing Changes to GitHub

After committing your changes:

1. In WebStorm, click "Push" in the "Version Control" tool window
2. Review the changes and click "Push"

Using the command line:

```
git push origin main
```

## Creating and Managing Branches

To create a new branch in WebStorm:

1. Go to Git > New Branch
2. Enter the branch name and click "Create"

Using the command line:

```
git branch new-branch-name
git checkout new-branch-name
```

Or, to create and switch to a new branch in one command:

```
git checkout -b new-branch-name
```

## Merging Branches

To merge branches in WebStorm:

1. Checkout the branch you want to merge into
2. Go to Git > Merge Changes
3. Select the branch you want to merge from
4. Click "Merge"

Using the command line:

```
git checkout main
git merge feature-branch
```

## Collaborating with Others

1. To collaborate, invite team members to your GitHub repository
2. Team members can clone the repository and create their own branches
3. Use Pull Requests on GitHub to review and merge changes:
   - Go to the repository on GitHub
   - Click "Pull requests"
   - Click "New pull request"
   - Select the branch to merge
   - Add a title and description
   - Click "Create pull request"

## References

1. Git Documentation. (n.d.). Retrieved from https://git-scm.com/doc
2. GitHub Docs. (n.d.). Retrieved from https://docs.github.com/en
3. JetBrains. (n.d.). WebStorm Documentation. Retrieved from https://www.jetbrains.com/help/webstorm/
4. Chacon, S., & Straub, B. (2014). Pro Git. Apress. Retrieved from https://git-scm.com/book/en/v2
5. GitHub Guides. (n.d.). Retrieved from https://guides.github.com/
