# Git

My most used git commands that I cannot remember

## Commands

### Undoing changes

```bash
git fetch --all
git reset --hard HEAD
```

Fetch all remote repositories, then rest to HEAD which is the most recent commit in the current branch.

```bash
git reset --soft HEAD~1
```

Reset current HEAD branch to one revision before most current.

```bash
git reset --hard HEAD~1
```

Use `--hard` to get rid of all changes to your local files.

```bash
git reset --hard 0ad5a7a6
```

Return to a specific version.

### Change branch

```bash
git checkout <branch name>
```

This will change all files to specified branch. Some notes; if this exists locally you will change to it. If it does not exist locally, and does exist on the remote, then it will create it locally and pull from the remote. If it doesn't exist in either, it will just be created locally.

### Reset
