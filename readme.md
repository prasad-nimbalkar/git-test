# Learn from Open source

# Git & GitHub Setup Guide

## Install Git

```bash
git --version
```

Windows:
https://git-scm.com

macOS:
```bash
brew install git
```

Linux (Ubuntu/Debian):
```bash
sudo apt install git
```

## Configure Git

```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
git config --global --list
git config --global init.defaultBranch main
```

## Create Local Repository

```bash
mkdir my-project
cd my-project
git init
```

## First Commit

```bash
echo "# My Project" > README.md
git add .
git commit -m "Initial commit"
```

## Connect to GitHub

```bash
git remote add origin https://github.com/USERNAME/REPO.git
git remote -v
```

## Push to GitHub

```bash
git push -u origin main
```

## Daily Commands

```bash
git status
git add .
git commit -m "message"
git pull
git push
```

## Branching

```bash
git checkout -b new-branch
git checkout main
git merge new-branch
```
