# Git Commands and Workflows

## Basic Commands

### Configuration
- Set your username:
  git config --global user.name "Your Name"
  
- Set your email:
  git config --global user.email "you@example.com"

### Creating a Repository
- Initialize a new repository:
  git init

### Cloning a Repository
- Clone an existing repository:
  git clone <repository-url>

## Working with Changes

### Staging Changes
- Stage a file:
  git add <file-name>
  
- Stage all changes:
  git add .

### Committing Changes
- Commit staged changes:
  git commit -m "Commit message"

### Viewing Changes
- View the status of your repository:
  git status
  
- View the commit history:
  git log

## Branching

### Creating and Switching Branches
- Create a new branch:
  git branch <branch-name>
  
- Switch to a branch:
  git checkout <branch-name>
  
- Create and switch to a new branch:
  git checkout -b <branch-name>

### Merging Branches
- Merge a branch into the current branch:
  git merge <branch-name>

## Remote Repositories

### Adding a Remote
- Add a remote repository:
  git remote add origin <repository-url>

### Pushing Changes
- Push changes to a remote repository:
  git push origin <branch-name>

### Pulling Changes
- Pull changes from a remote repository:
  git pull origin <branch-name>

## Best Practices
- Commit often with clear messages.
- Use branches for new features or bug fixes.
- Regularly pull changes from the main branch to stay updated.
- Review changes before merging branches.