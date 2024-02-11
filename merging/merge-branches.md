# Merge Branches

This command is used to integrate changes from one branch into another.

**Usage:**

```bash
git merge <branch-name>
```

This command merges the specified branch into the current branch. It combines the changes made in the specified branch with the changes in the current branch. If there are no conflicts, Git will automatically perform the merge. If there are conflicts, manual intervention may be required to resolve them.

To merge a branch into the current branch and automatically create a merge commit, you can use:

```bash
git merge --no-ff <branch-name>
```

This will prevent Git from performing a fast-forward merge and create a new merge commit, even if the merge could be resolved automatically.

If you want to abort the merge process and return to the state before the merge started, you can use:

```bash
git merge --abort
```
This will undo the merge and leave the branch in its pre-merge state.