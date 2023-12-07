
# Git and GitHub Learning

This repo gives a breif introduction to Git Commands for beginners.




## Authors

- muskanqed




## 🔗 Links

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muskan-badeghar-65aa6a176/)



## 🚀 About Me
Passionate SQL Developer with of hands-on experience in designing and optimizing database systems. Currently on an exciting journey to become a proficient Full-Stack Developer. 🚀


## Documentation

## Introduction: 

- Version Control System is a tool to track changes in code.
- Git is a version control System.
- Used to track and collaborate the code history.

Download link: https://git-scm.com/community

## You can check the Git version using below command

``` git --version ```

## Configuring Git in system using below command

```git config --global user.name "my name" ```

``` git config --global user.email "my email" ```

``` git config --list ```

## Clone a repo

``` git clone <repo link> ```

## Check the Status

``` git status ```

- Untracked: new files that git has not tracked yet.
- modified: changed files 
- unmodified: unchanged files
- staged: file is ready to commit

## Adding files from local to remote 

Just follow the commands

- ``` git init ```

- ``` git remote add origin <link> ```

- ``` git remote -v ```

- ``` git branch ```

- ``` git branch -M main ```

## To create new Git Branch and delete a branch

``` git checkout -b <new branch name> ```

``` git branch -d <branch name> ```

## Merging code

- Way-01:

``` git diff <branch name> ```

``` git merge <source_branch> <target_branch> ```

- Way-02:

Create a Pull request(PR) from GitHub

## Undoing changes

- case-01: Staged changes

``` git reset <filename> ```
            OR
``` git reset ```

- case-02: Committed changes

``` git reset HEAD~1 ```

- case-03: Committed changes(more then one)

```git log ```

```git reset <commit hash> ```

``` git reset --hard <commit hash> ```













