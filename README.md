![N|Solid](https://www.freecodecamp.org/news/content/images/2022/07/git-github.png)
# Introduction to GitHub

### Table of content

Introduction

What is GitHub

Why GitHub

Git vs. GitHub

Clone 

Pull request 

Commit 

GitHub Desktop vs. Github CLI

Conclusion




## Introduction
This article is dedicated to explaining what GitHub is, what is the difference between Git and GitHub, GitHub Desktop vs. Github CLI and it will also help you execute some commands on Git.

## What is GitHub

GitHub  is a Git—based web service that helps to jointly develop IT projects. On GitHub, developers publish their own and edit someone else's code, comment on projects and follow the news of other users.

## Why GitHub
The GitHub web service is in demand for hosting IT projects and joint development. The developers of the system call it a "social network" for programmers. Here they combine repositories, comment on examples of someone else's code and use the platform as a cloud storage with the ability to quickly transfer to the customer. GitHub also boasts access control, bug tracking, task management, and a wiki for each project. The goal of GitHub is to facilitate developer interaction.


## Git vs. GitHub
Git is a distributed version control system that allows developers to track changes in files and work on one project together with colleagues and GitHub is an online repository hosting service that has all the functions of distributed version control and source code management functionality — everything that supports Git and even more.

Benefits of Git | Benefits of GitHub |
:-----: | :----: |
Free and open-source. You can download it for free and make any changes to the source code  | You can create an unlimited number of repositories under each free account, but they will be public| 
Small and fast. Performs all operations locally, which increases its speed. In addition, Git locally saves the entire repository into a small file without loss of data quality | On GitHub, you can build a portfolio. Project descriptions are linked to a public repository from which the source code can be viewed | 
Git is effective at storing backups, so there are few known cases of people losing data while using Git  | Global search. For developers: project search, error analysis, code with comments. For recruiters: search for employees by CV|
| Simple branching. In other version control systems, creating branches is a tedious and time—consuming task, since all the code is copied to a new branch. In Git, branch management is implemented much easier and more efficiently  | You can find out the profile's activity, what contributions have been made and the number of followers. | 

## Clone 

To clone a folder (repository or fork) means to download it to work with the code on your computer. 

1. To clone a repository, go to the repository page you want to clone. This can be done using the side column on the dashboard.
2. Click clone or upload.
3. Copy the code that appears after clicking the button.
![clone_1](https://github.com/Diana1465/techwritermentorship_assignment1/blob/main/clone_1.png)
4. After that, open Git Bash on your system.

![clone_2](https://github.com/Diana1465/techwritermentorship_assignment1/blob/main/clone_2.png)

5. Check the directories (or repositories) already created in this directory (using the ls command). As you can see in the picture, I have only one repository in the techwriter_mentorship directory.

![clone_3](https://github.com/Diana1465/techwritermentorship_assignment1/blob/main/clone_3.png)

6. Type the git clone "URL" command to clone the repository. The URL here is the same URL that we copied in the third step.
![clone_4](https://github.com/Diana1465/techwritermentorship_assignment1/blob/main/clone_4.png)
```sh
$ git clone https://github.com/USERNAME/REPOSITORYNAME
```
The URL is a link to the GitHub repository. You can type this into the address bar of your browser and check whether the repository page opens or not.

7. When you press enter, the following message will appear.
![clone_5](https://github.com/Diana1465/techwritermentorship_assignment1/blob/main/clone_5.png)

It will take a few seconds to clone the storage on your system. Please note that cloning depends on your internet connection, and the time will depend on your connection. If Git cannot clone due to a weak connection, it will display an error. The user will be prompted to try again until the above message appears.

8. Check the directories with the ls command, which lists all files and folders. Make sure that the cloned repository appears.
![clone_6](https://github.com/Diana1465/techwritermentorship_assignment1/blob/main/clone_6.png)

## Pull request
Pull request is an offer to change the code in the repository. 

To create a pull request, go to your fork page on GitHub. The Compare & pull request bar appeared at the top, and you can also go to the **Pull Requests** tab.
1. Go to your fork page on GitHub. The Compare & pull request bar appeared at the top, and you can also go to the Pull Requests tab.
![pullrequest_1](https://github.com/Diana1465/techwritermentorship_assignment1/blob/main/pullrequest_1.png)
2. Click on it and you will find yourself on the page of opening a pull request. Check the description and click **create a pull request**.
![pullrequest_2](https://github.com/Diana1465/techwritermentorship_assignment1/blob/main/pullrequest_2.png)
4. Wait for the approval of the pull request or comments on it.


## Commit
To commit means to commit all the saved changes and give them a name. This is done using the commit command.
```sh
git commit -m "your message"
```

## GitHub Desktop vs. Github CLI
GitHub Desktop allows you to interact with files by having a clear application interface and clicking buttons, while the CLI requires you to enter commands manually. However, many developers and programmers prefer the second option, since it gives access to every single git function available.
The message text should be concise and at the same time report what the commit is doing (the changes made).

## Conclusion
This article was written to let you understand a little more about what Git is, the difference between Git and GitHub, and how to work with Git on your computer. Do not stop your practice of using these tools and you will definitely master it soon.
