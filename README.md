
---

# Git Commands Reference

---

## Repository Initialization

### git init

Initializes a new local repository in your current directory.

```bash
git init
```

---

## Staging Files

### git add

Adds files to the staging area.

```bash
git add .
```

---

## Committing Changes

### git commit

Commits your staged changes with a message.

```bash
git commit -m "Your commit message"
```

---

## Remote Repository

### git remote add origin

Connects your local repository to a remote repository.

```bash
git remote add origin https://github.com/username/repository.git
```

---

### git push origin master

Pushes your local repository content to the remote repository.

```bash
git push origin master
```

> Note: Some repositories use `main` instead of `master`.

---

### git clone

Clones the entire repository from remote to your local machine.

```bash
git clone https://github.com/username/repository.git
```

---

### git pull

Brings the latest changes from the remote repository to your local repository.

```bash
git pull origin main
```

---

## GitHub Feature

### Fork

A Fork is a personal copy of someone else’s repository on GitHub.

---

## Branching

### git branch

Lists all branches.

```bash
git branch
```

---

### git branch branch-name

Creates a new branch.

```bash
git branch new-branch
```

---

### git checkout branch-name

Switches to another branch.

```bash
git checkout branch-name
```

---

### git checkout -b new-branch

Creates a new branch and switches to it.

```bash
git checkout -b new-branch
```

---

### git branch -d branch-name

Deletes a branch.

```bash
git branch -d branch-name
```

---

## Viewing History

### git log

Shows the history of commits.

```bash
git log
```

---

### git log --oneline

Shows each commit in a single line.

```bash
git log --oneline
```

---

### git show

Shows detailed information about a commit.

```bash
git show
```

---

## Undo & Recovery

### git restore

Restores or unstages tracked files.

```bash
git restore file-name
```

---

### git merge

Adds changes from one branch into another branch.

```bash
git merge branch-name
```

---

### git rebase

Moves or replays commits from one branch onto another.

```bash
git rebase main
```

---

### git reset

Undoes commits and moves back to a previous commit.

```bash
git reset --hard HEAD~1
```

---

### git revert

Creates a new commit that undoes a previous commit.

```bash
git revert commit-id
```

---

