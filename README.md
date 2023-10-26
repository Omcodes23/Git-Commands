# Git Commands

This README file provides a quick reference guide to some essential Git commands for version control. Whether you're a beginner or an experienced developer, these commands will help you manage your Git repositories effectively. Make sure you have Git installed on your system before using these commands.

## Table of Contents
- [Git Configuration](#git-configuration)
- [Creating a New Repository](#creating-a-new-repository)
- [Cloning a Repository](#cloning-a-repository)
- [Adding and Committing Changes](#adding-and-committing-changes)
- [Branching](#branching)
- [Merging](#merging)
- [Remote Repositories](#remote-repositories)
- [Undoing Changes](#undoing-changes)
- [Viewing Information](#viewing-information)

### Git Configuration

Before using Git, it's essential to configure your name and email address:

```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```

### Creating a New Repository

To create a new Git repository:

```bash
git init
```

### Cloning a Repository

To clone an existing repository from a remote URL:

```bash
git clone <repository_url>
```

### Adding and Committing Changes

1. To stage changes for commit:

```bash
git add <filename>   # Stage a specific file
git add .            # Stage all changes
```

2. To commit staged changes:

```bash
git commit -m "Your commit message"
```

### Branching

1. Create a new branch:

```bash
git branch <branch_name>
```

2. Switch to a branch:

```bash
git checkout <branch_name>
```

3. Create a new branch and switch to it:

```bash
git checkout -b <new_branch_name>
```

### Merging

1. Merge changes from one branch into the current branch:

```bash
git merge <branch_name>
```

### Remote Repositories

1. Add a remote repository:

```bash
git remote add <remote_name> <repository_url>
```

2. Push changes to a remote repository:

```bash
git push <remote_name> <branch_name>
```

3. Pull changes from a remote repository:

```bash
git pull <remote_name> <branch_name>
```

### Undoing Changes

1. Discard changes in a file:

```bash
git checkout -- <filename>
```

2. Unstage changes:

```bash
git reset
```

3. Amend the last commit (use with caution):

```bash
git commit --amend -m "New commit message"
```

### Viewing Information

1. View the status of your repository:

```bash
git status
```

2. View the commit history:

```bash
git log
```

3. View a list of branches:

```bash
git branch
```

4. View changes made in a specific commit:

```bash
git show <commit_hash>
```

These are some of the most commonly used Git commands. Explore Git's documentation for more advanced features and options. Don't forget to commit your work regularly and write clear and concise commit messages to maintain a clean and organized version history. Happy coding!
