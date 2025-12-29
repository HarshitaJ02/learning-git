# learning-git

This repository is a look up for quick concepts and commands needed for git and github.

> Easiest way: 

_You can always look for cheatsheets for quick commands_
https://education.github.com/git-cheat-sheet-education.pdf

#  **Very Important:** Git and GitHub are **two different things**.  
> - **Git** is a tool  
> - **GitHub** is a platform where Git repositories are hosted  

---

##  Git

<p align="center">
  <!-- Add Git icon here -->
  <img src="https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png" alt="Git Icon" width="80"/>
</p>

###  What is Git?
**Git** is a tool used to track changes in code over time.  
It is known as a **distributed version control system**, which means:

- Multiple people can work on the same code at the same time  
- Every change is recorded safely  
- You can always go back and view older versions of the code  
- No one’s work gets accidentally lost   

In simple words, Git helps developers **collaborate without chaos**.

---

##  Quick History of Git

### Timeline

- **2005** 
  Git was created by **Linus Torvalds**

- **Why?**  
  While developing the **Linux kernel**, Linus faced challenges managing code changes and collaboration.

- **The Solution**  
  He built Git to be:
  - Fast  
  - Reliable   
  - Perfect for large projects with many contributors  

And that’s how Git was born, out of a real problem, with a very smart solution.

##  First Git Commands We Usually Practice

### 1️. Basic Commands You Must Know

These are **terminal commands** (not Git commands yet) that help you move around and manage files on your computer:

- `mkdir` → Creates a new folder  
- `cd` → Moves you into a folder  
- `ls` → Shows a list of files and folders  
- `mv` → Moves or renames a file/folder  
- `cp` → Copies a file or folder  

These commands help you **navigate and organize your project** before using Git.

---

### 2️. Git Configuration

Before using Git, we need to **configure it**.  
Configuring Git means telling Git **who you are**, so every change you make is properly labeled with your name and email.

This information is stored globally and used for all your Git projects.

```bash
git config --global user.name "firstname lastname"
git config --global user.email "valid-email"
```