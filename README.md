# Git

## Before Getting Started
[Download Git](https://git-scm.com/) - Git is an open source, distributed version-control system.

[Create Github Account](https://github.com/join?ref_cta=Sign+up) - Github is a platform for hosting and collaborating on Git repositories

## Important Terms

### Repository (Repo)
This is the term used to refer to the whole project. This includes all files that are in the project, along with the revision history for each file.

### Branch
A branch is a line of development. The first commit on a branch points to the commit on another branch that was used to create this branch. 

### Commit
A single point in the Git history. This is similar to a a save point. It is a snapshot of the repository.

## Basic Commands
```
git [command] -h
```
Add "-h" after any command to retrieve the usage message for that command

```
git init
```
Initializes a new Git repository in the present working directory.

```
git clone
```
Creates a local copy of a remote repository.

```
git add
```
Stages a change. Any changes to a file must be staged to have them included in the project's history.

```
git commit
```
Saves a new snapshot to the project history that includes any staged changes.

```
git merge
```
Merges branches together. This is typically used to combine two branches with changes.

```
git pull
```
Updates the local branch with any updates from a remote counterpart.

```
git push
```
Updates the remote branch with any commits that have been made locally

## Git Flow
1. Create a branch
```
git branch [branch-name]
```

2. Stage changes
```
git add file1.txt file2.txt
```
```
git add .
```

3. Add commits
```
git commit -m "[commit message]"
```

6. Merge
```
git checkout [branch-to-merge-into]
git merge [branch-with-changes]
```

## Further Reading
[Git Cheat Sheet](https://training.github.com/downloads/github-git-cheat-sheet/)

[Git Glossary](https://git-scm.com/docs/gitglossary)


