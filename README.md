Introduction to Git(hub)
================
2021-07-07

## What is Git?

![<https://xkcd.com/1597/>](https://imgs.xkcd.com/comics/git.png)

Git is an **Open Source Distributed Version Control System**.

-   tracks changes in “any set of files”
-   multiple people can add and edit code in parallel
-   Git has a **remote repository** which is stored on a server
-   and a **local repository** which is stored on the computer of each
    developer.

This means that the code is not just stored on a central server, but a
full copy of the code and its history is present on each of the
developers’ computers.

## Getting started

Git itself is a version control system that can be installed on any
server.

However, we’ll be using Github (<https://github.com>), as a remote Git
repository.

Key features provided by GitHub include:

-   Issues
-   Discussions
-   Pull requests
-   Notifications
-   Labels
-   Actions
-   Forks
-   Projects

For more details and some good instructions, see:
<https://guides.github.com/>

## Registration

If you have not done so, go to <https://github.com/> and create an
account.

### Student Developer Pack

It is strongly recommended that you get a free “student” account.

A normal, free GitHub account does not allow you to create “private”
repositories, while a student account allows you up to 5 private
repositories.

**Unless you use a private repository, any code you push to GitHub is
automatically public and accessible by anyone.**

In order to extend your account to a student account, go to
<https://education.github.com/pack> and register for a “student pack”,
after you have registered for a normal account.´

### **Don’t do this now, but after our session!**

## Installing Git on Your Machine

If you want to use Git on your own personal machine, then you may need
to install a Git client.

There are many options out there and you are encouraged to explore them.

Git has released its own graphical user interface clients which are
available for free for both Windows and Mac:

-   Windows: <https://windows.github.com/>
-   Mac: <https://mac.github.com>

## Basic procedure

### 1. Create remote repository

### 2. Create local repository

### 3. Stage file(s)

### 4. Commit file(s)

### 5. Push commit

## Basic procedure

### 1. Create remote repository

After registering in the GitHub homepage:

1.  In the upper right corner, next to your avatar or identicon, click
    and then select “New repository”.
2.  Give the repository a name and optionally also a description
3.  Choose if the repository should be “public” or “private”
4.  Add README, .gitignore and license
5.  click “Create Repository”

**Note:** Apart from step one, all other steps can be easily done in
**RStudio**. And I’ll show you how to do this after the presentation.

### 2. Create your local Git repository

-   Basically this means that you download the created remote repository
    to your local machine.

### 3. Stage file(s)

-   Adding files to the index of the repository

### 4. Commit file(s)

-   Commit means to register the changes you have made, so that others
    can eventually see them, too.
-   Alway add an “Update message” to your commit.
-   The “Update message” should be as descriptive as possible, so you
    are able to find certain changes later on.

### 5. Push commit

-   With push you upload your changes to the main branch in the local
    repository to the main branch in the remote repository.
-   Thus, **only after this is a copy of your changes are stored on the
    server**.

## Other commands

### Pull

-   Pull is used to pull the latest changes from the remote repository
    to the local repository.
-   If multiple people work on one repository, the remote repository is
    updated continuously by various people, hence git pull is necessary.

### Clone

-   Cloning is used to clone an existing remote repository into your
    computer.

### Fork

-   Forking is the process of creating a copy of a repository from
    another user.
-   When a user forks a repository, all the files in the repository are
    copied to the user’s account on GitHub.
-   This process is similar to copying a folder from one drive to
    another drive in a computer.

### Branching

-   Branching is the way to work on different versions of a repository
    at one time.
-   The default branch, which is created when you initialize a
    repository, is commonly named **main**.
-   We use branches to experiment and make edits before committing them
    to main.
-   The head of the current branch is named HEAD.
-   Branches are an incredibly useful feature of Git because it supports
    multiple parallel development, which can automatically be merged
    into the default branch later on.

![Branching](https://guides.github.com/activities/hello-world/branching.png)

### Merging

With merge you can bring the changes implemented within a sub-branch
back to your **main** branch.

![Branching](https://guides.github.com/activities/hello-world/branching.png)

# Now, let’s try it out ourselves.
