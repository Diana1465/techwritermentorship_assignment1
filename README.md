
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


![N|Solid](https://www.freecodecamp.org/news/content/images/2022/07/git-github.png)


## Introduction
This article is dedicated to explaining what Github is, what is the difference between Git and Github, and it will also help you execute some commands in Git.

## What is GitHub

GitHub  is a Git—based web service that helps to jointly develop IT projects. On Github, developers publish their own and edit someone else's code, comment on projects and follow the news of other users.

## Why GitHub
The GitHub web service is in demand for hosting IT projects and joint development. The developers of the system call it a "social network" for programmers. Here they combine repositories, comment on examples of "someone else's" code and use the platform as a cloud storage with the ability to quickly transfer to the customer.


## Git vs. GitHub
Git is a distributed version control system that allows developers to track changes in files and work on one project together with colleagues and GitHub is an online repository hosting service that has all the functions of distributed version control and source code management functionality — everything that supports Git and even more

## Clone 
To clone a folder (fork) means to download it to work with the code on your computer. 
1. From Github Repository, click on Clone
2. Copy the clone URL
3. In Terminal (Mac) or command line (Windows git bash) go to the current directory where you want the cloned directory to be added
```sh
$ cd '/c/Users/j-c.chouinard/My First Git Project'
```
4. Use the git clone command along with the copied URL from earlier
```sh
$ git clone https://github.com/USERNAME/REPOSITORY
```
5. Tap Enter.
```sh
$ git clone https://github.com/USERNAME/REPOSITORY
Cloning into Git …
remote: Counting objects: 13, done.
remote: Compressing objects: 100% (13/13), done.
remove: Total 13 (delta 1), reused 0 (delta 1)
Unpacking objects: 100% (13/13), done.
```

## Pull request
Pull request is an offer to change the code in the repository. Pull request should be checked by the administrator of the master repository - it can be a fellow developer, a technical assistant or a mentor on the course.
1. Go to your fork page on GitHub. The Compare & pull request bar appeared at the top, and you can also go to the Pull Requests tab.
2. Click on it and you will find yourself on the page of opening a poolquest. Check the description and click Create pull request.
3. Wait for the approval of the request pool or comments on it.


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
