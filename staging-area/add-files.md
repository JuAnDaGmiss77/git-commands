# Add Files to Staging Area

This command is used to add files to the staging area in preparation for a commit.

```bash
git add <file1> <file2> ...
```

This command stages the specified files for the next commit. It adds them to the staging area, also known as the index, where changes are marked for inclusion in the next commit.

To add all modified and new files to the staging area, you can use:


```bash
git add .
```
To add all changes, including deletions, you can use:

```bash
git add -A
```