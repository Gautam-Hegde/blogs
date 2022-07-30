---
layout: post
title: 'Git and GitHub : A Beginners guide!'
date: 2022-7-30
categories: ["git", "GitHub", "VCS"]
---

Regardless of their specialty, every developer should get familiar with the technologies Git and GitHub.
Beginner developers might mistakenly believe that these two phrases indicate the same thing, but they actually mean something quite different.
This post will explain what Git and version control are, the fundamental commands you must know for Git, how to leverage Git's capabilities to increase your work productivity, and how to use GitHub to extend these features.

## What is Git(*time-machine*)? ##
if you do a Google search for source code control you can read how Wikipedia defines Source control, as:
“Revision control (also known as version control, source control or (source) code management (SCM)) is the management of multiple revisions of the same unit of information.”
In short: Git is a version control programme that enables you to keep track of the changes you make to your files over time. You can change the statuses of your files using Git. You can also duplicate your file, edit that copy, then merge the modified copy back into the original.

## Installing Git ##
On the official website, you can download the most recent version to accomplish this. From the available options, you can download for your operating system.
https://git-scm.com/downloads
To verify, you can run this command on the command line: `$ git --version`. This shows you the current version installed on you PC.

## Set your identity ##
The first thing you should do when you install Git is to set your user name and email address. This is important because every Git commit uses this information, and it’s immutably baked into the commits you start creating:
`$ git config --global user.name "yourname"`
`$ git config --global user.email yourmail@example.com`

*Now you are all set and ready to explore*

## Create and Initialize a Project in Git ##
Here are a few ways to create a repository:
- Using the `git init` command (with or without its flags)
- Creating a remote repository using GitHub, Bitbucket or other server first and cloning it locally
- Copying and pasting an existing folder that is a Git repository and changing those specific settings(dangerous)

## Basic Concepts ##
I'll quickly go over some fundamental version control principles in this section. These phrases are used in many SCM systems, some of which are applicable to Git and GitHub and others to other systems.
Repository/repo: The database storing the files.
- *Branch*: Branching means you diverge from the main line of development and continue to do work without messing with that main line. In many VCS tools, this is a somewhat expensive process, often requiring you to create a new copy of your source code directory, which can take a long time for large projects.
- *Revert/rollback*: Go back to a previously saved version of the codebase/repo.
- *Push*: Push is an access level on the repo, if you have no push access you will need to make a pull request.
- *Pull*: If you have no Push access you can make a pull request which will notify the repo owner you want to merge your changes into their code.
- *Check-out*: make a copy of the repository you wanted to make changes to on your machine, once you have made your change then, Check-in your changes.
- *Check-in*: add your changes back to the repository with an accompanying message detailing the change you have made.
- *Merge*: merge your changes into the main line of development.
- *Rebase*: rebase your changes onto the main line of development.
- *Tag*: create a label for a specific version of the codebase.
- *Stash*: stash your changes, you can then restore them later.

It's time to experiment and have some fun now. 
#### A git cheat sheet is embedded for your convenience. ####
![git-cheat-sheet](https://user-images.githubusercontent.com/85569489/181935040-00ed5e54-9716-4bc7-9435-bc306a5d39cd.png)

## What is GitHub(*online hosting service for Git repositories*)? ##
One of the largest developer communities in the world is GitHub. It is a complex platform that encourages developer cooperation and communication. In addition to allowing development teams to collaborate on the same project and simply produce new software versions without interfering with the existing versions, GitHub has a number of other helpful capabilities.
GitHub is complex, but understanding a few basics will help you get started. In order to use GitHub, you’ll need to first be able to complete these few steps. 
*How to use GitHub:*

- Sign up for GitHub
- Create a Repository
- Connect to remote repository 
- Create a Branch
- Create and Commit Changes to a Branch
- Open a Pull Request
- Merge Your Pull Request etc.

*Check out github's official documentation; it serves as a one-stop shop for all of your needs.*
 <https://docs.github.com/en/get-started/quickstart>

## Conclusion ##
The fundamental commands that will get you started using Git were covered in this tutorial. Additionally, we began learning how to use GitHub.
You are ready to proceed if you have followed through up until this point. Git is now compatible with all programming languages, so you may use it in any of your projects.
- *More on ‘Power of open source technology’ will be published soon.*
- *PS. Don’t hesitate to open a PR on my github account to get started.*
<https://github.com/Gautam-Hegde>

#### These are some additional resources: ####
- <https://git-scm.com/book/en/v2>
- <https://www.freecodecamp.org/news/git-cheat-sheet/>
- <https://www.youtube.com/watch?v=RGOj5yH7evk>

