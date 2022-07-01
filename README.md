---
title: "Project"
Due date: 2018-07-17T16:00:00-00:00
draft: false
weight: 100
---

## Introduction

This week we will have a relatively simple project.
There are many ways to figure it out, try to find the most elegant, but remember the most important thing is that at the end of the day you meet the requirements!

![scripts](/images/scripts-automation.png)

## Project Overview

In this project we will understand  how to manage code with Git. The project will consist of creating a python program and storing it in the main branch of your public git repository hosted in the service of your choice (Github, Gitlab, Bitbucket, Azure DevOps, etc). Then, you will be asked to add a new functionality in a feature branch and create a pull request.

## Goals

- Create a public git repository in the tool of your choice (Github, Gitlab, Azure DevOps)

- Write a password validator python program as described below and store it in the main branch of your git repository
  - Write a python program to validate password strength with the following requirements:
    - Length – minimum of 10 characters.
    - Contain both alphabet and number.
    - Include both the small and capital case letters.
    - Color the output green if it passed the validation and red if it didn’t.
    - Return exit code 0 if it passed the validation and exit code 1 if it didn’t.
    - If a validation failed provide a message explaining why
    - Make sure your script can run automatically without the need for human intervention
    - Write the script in the best possible way (for performance and UX)
    - Name your script "password_validator.py" (case sensitive)
  - Usage example:

    ```
    Python ./password_validator.py "MyP@ssw0rd!"
    ```

- Create a feature branch to improve the script as described below
  - Name the branch "feature" (case sensitive)
  - Extend the script by adding the following capability:
    - If the option "-f" is added the password should be retrieved from a file
  - Usage example:

    ```
    Python ./password_validator.py -f "/mypath/password.txt"
    ```

- Create a pull request to integrate your feature branch into the main branch (DO NOT complete the merge)

- Create a scond barch that split from where the "feature" was splited
  - Name the branch "HomeWork" (case sensitive)
  - Each commit should includ a singel working version of the homework task given katya (Total 4 Commits)
  - The commit messages should be "home work number <X>" X is the nuber of the assignment 
  - when I will checkout one of the commit will see onely one assignment
## Considerations

- Make sure you meet each of the project requirements
- Make sure your code is clean and well documented, this will be evaluated
- From now on we expect you to manage all the code related to the bootcamp using Git

