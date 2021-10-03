# Project 0x03. Git

## Concepts

For this project, students are expected to look at these concepts:

* Source code management
* Git and Github cheat sheet - Everything in less than 30 seconds
* The Framework
* Approaching a Project

## Resources

__Read or watch:__

* Resources to learn Git
* About READMEs
* How to write a Git commit message

__Resources for advanced tasks (Read only after finishing the mandatory tasks):__

* Learning branching
* Effective pull requests and other good practices for teams using GitHub

## Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

### General

* What is source code management
* What is Git
* What is GitHub
* What is the difference between Git and GitHub
* How to create a repository
* What is a README
* How to write good READMEs
* How to commit
* How to write helpful commit messages
* How to push code
* How to pull updates
* How to create a branch
* How to merge branches
* How to work as collaborators on a project
* Which files should and which files should not appear in your repo

## Requirements

### General

* A `README.md` file at the root of the repo, containing a description of the repository
* A `README.md` file, at the root of the folder of this project (i.e. `0x03-git`), describing what this project is about
* Do not use GitHub’s web UI, but the command line to perform the exercise (except for operations that can not possibly be done any other way than through the web UI). You won’t be able to perform many of the task requirements on the web UI, and you should start getting used to the command line for simple tasks because many complex tasks can only be done via the command line.
* Your answer files should only contain the command, and nothing else

## More Info

### Install 'git'

If `git` is not already installed on your terminal:

* `$ sudo apt-get update`
* `$ sudo apt-get upgrade`
* `$ sudo apt-get install git`

### Basic usage

At the end of this project you should be able to reproduce and understand these command lines:

* `$ git clone <repo>`
* `$ touch test`
* `$ git add test`
* `$ git commit -m "Initial commit"`
* `$ git push origin main`

## Tasks

| Task name | Description |
| --- | --- |
| 0. Create and setup your Git and GitHub account | You pushed your first file in your first repository of the first task of your first School project. |
| 1. Repo-session | Create a new directory called 0x03-git in your zero_day repo. |
| 2. Coding fury road | * Create these directories at the root of your project: `bash`, `c`, `js` * Create these empty files: `c/c_is_fun.c`, `js/main.js`, `js/index.js` * Create a file `bash/best` with these two lines inside: `#!/bin/bash` and `echo "Best"` * Create a file `bash/school` with these two lines inside: `#!/bin/bash` and `echo "School"` * Add all these new files to git * Commit your changes (message: “Starting to code today, so cool”) and push to the remote server | 