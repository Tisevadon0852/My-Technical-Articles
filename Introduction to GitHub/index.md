# Introduction to GitHub

## **Table of Contents**

- [Introduction to GitHub](#introduction-to-github)
  - [**Table of Contents**](#table-of-contents)
  - [Introduction to Git and GitHub](#introduction-to-git-and-github)
  - [What is Git](#what-is-git)
  - [What is Distributed Version Control System](#what-is-distributed-version-control-system)
  - [What is GitHub](#what-is-github)
  - [Why Learn About Git and GitHub](#why-learn-about-git-and-github)
  - [Differences Between Git and GitHub](#differences-between-git-and-github)
  - [Getting Started With Git GitHub](#getting-started-with-git-github)
  - [Step 0 - Installing Git](#step-0---installing-git)
  - [Step 1 - Create a GitHub Account](#step-1---create-a-github-account)
  - [Step 2 - Configure Git](#step-2---configure-git)

## Introduction to Git and GitHub

It is common to become confused when learning the concepts of Git and GitHub for the first time. You might mistakenly believe that Git and GitHub are the same things if you're new to utilizing version control, but they're not.

After reading this article, you will know what Git and GitHub are, how to create and clone a GitHub repository, how to push your work to GitHub, and many other terminologies that are connected.

## What is Git

Git, often known as a "Distributed Version Control System," enables programmers to keep track of changes made to their codebases and collaborate with others. As a result, programmers may quickly compare versions of their code to see what has changed or go to previous versions. Git is installed on a developer's computer.

Linus Torvalds created Git in 2005, which has now evolved into an essential tool for software development.

## What is Distributed Version Control System

It is a software system that enables multiple users to collaborate on the same codebase while keeping a history of changes made to the code. In a Distributed Version Control System, each user has their own local copy of the code repository, which they can work on independently, and the system manages the synchronization of changes made by different users.

## What is GitHub

GitHub is a web-based platform used for version control and collaboration on software development projects. It allows users to store and manage their code repositories, track changes made to code over time, and collaborate with others on code development and management.

In addition, GitHub is also used by individuals and organizations to store and share various types of files.

## Why Learn About Git and GitHub

Learning Git and GitHub is esssential for anyone who wants to work in software development, particularly in collaboration projects. It is a valuable investment because these tools provide a powerful and flexible platform for managing code and working with others.

## Differences Between Git and GitHub

Git is a command line tool that is installed on a developer's computer, that allows multiple developers to work on the same codebase simultaneously and it is used to manage code changes locally, while GitHub is a web-based platform for hosting and sharing Git repositories, and it provides a range of collaboration tools and features, as well as additional features like issue tracking, pull requests, and code review.

Additionally, Git is open-source software that can be freely downloaded and installed on any operating system, while GitHub is a commercial service that offers both free and paid plans, with additional features available on the paid plans.

## Getting Started With Git GitHub

You have gotten this far. Conratulations! This is the time make things easier by using practical examples in explaining all the concepts we have talked about so far. Let us journey together...

## Step 0 - Installing Git

it is time to install Git. But before trying the installation process, first check if you have git installed in your computer already.

To check if Git is insatlled on your computer:

- a. On your Windows computer, go to _search bar_
- b. On the **search bar**, type **command prompt**
- c. Launch the terminal.
- d. Then type this command

  ```
  git --version

  ```

- . If you have Git installed, it will output version of the on your computer as shown below.

But if Git is not installed, follow these processes to install it:

**For Windows and MacOS**

- a. Go to [Install Git](https://git-scm.com/downloads)
- b. Click on either Windows or macOS, depending on which Operating System that you are using, then click on _download_
- c. After it has successfully downloaded, double-click the downloaded file to open the installer. Follow the prompts in the installer to choose the installation directory and configure your Git installation options.

**For Linux**

- Open your terminal and run the following command

```
sudo apt-get update
```

```
sudo apt-get install git
```

After going through the installation proccesses, it is necessary to _restart_ your computer. After which your run

```
git --version
```

command again, this time you will have the same output like I have in the image above.

## Step 1 - Create a GitHub Account

If you do not have a GitHub account, go to the [GitHub homepage](https://github.com/) and follow the prompt. Once you have completed the verification process, your GitHub account with be created.

## Step 2 - Configure Git

Since you have Git installed on your computer, it is configuration time now. This time, we are not using _Command Prompt_, instaed we are using the Git software you installed. So go to _search bar_ and type _Git Bash_, that is what we will be using from now.

For now, you will set up your email, name and also maing your favourite editor the default editor. You can launch your Git Bash now.

- To set up your email, run this command on your Git Bash terminal

```
git config --global user.email "youremail@example.com"
```

Replace "youremail@example.com" with your email address

- To set up your name

  ```
  git config --global user.name "your name"
  ```

  Replace "your name" with your actual name

- To configure your editor: Git uses a default text editor to open and edit commit messages. If you prefer to use sublime text, emacs or VS Code, you can configure Git to use by entering the following command:

```
git config --global core.editor "code"
```

To verify your configuration, run this command

```
git config --list
```

As you can see, the above command displays a list of all the configuration settings for Git on your computer.

If the output on your terminal is the same as mine, it means you have successfully configured your Git. Congratulations! It is time to start using Git to manage your codebase by creating a new repository, a new file on your computer, adding and commiting changes made to file and pushing it to your new GitHub repository.

Let us get started!
