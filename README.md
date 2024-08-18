# Git & GitHub Commands

## Init Command
Init Command to used to create & initialize the git repo.

```bash
git init
```

## Git Remote

Git Remote Command to add the remote repository.
```bash
git remote add origin <-repository-url->
```

### Verify remote repository

To verify remote repositery, Use the below command. It will show the link of the repositery.
```bash
git remote -v
```

## Git Branch
We use Git Branch, When multiple developers are working on the same project.

### Create New Branch

The below Git Branch Command to create a new branch.
```bash
git checkout -b <-new-branch-name->
```

### Check Branch
To check the current branch, use the below command.
```bash
git branch
```

### Rename Branch

Rename the branch using the below command.
```bash
git branch -M <-new-branch-name->
```

### Navigate to another Branch

Navigate to another branch using the below command.
```bash
git checkout <-branch-name->
```

### Delete Branch

Delete the branch using the below command.
```bash
git branch -d <branch-name>
```

## Pull Command

Pull command is used to download the latest changes from the remote repository.
```bash
git pull origin main
```

## Undoing Changes

### Case 1: Staged changes

```bash
git reset <-file-name->
```
OR
```bash
git reset
```

### Case 2: Commited Changes (for one commit)

The below command to reset changes (for one commit)
```bash
git reset HEAD~1
```

### Case 2: Commited changes (for many commits)

```bash
git reset <-commit-hash->
```

To reflect the changes in VS Code, Use the below command
```bash
git reset --hard <-commit-hash->
```

## Fork
A Fork is a new respositery that shares code and visibilty settings with original "upstream" respositery.

Fork is a rough copy.