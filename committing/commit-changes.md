# Commit Changes

This command is used to record changes to the repository.

**Usage:**

```bash
git commit -m "Commit message"
```

This command creates a new commit containing the changes staged in the index. It opens a text editor to enter a commit message if the -m flag is not used. The commit message should briefly describe the changes made in the commit.

To commit all staged changes, you can use:

```bash
git commit -a -m "Commit message"
```

This will automatically stage any modified files before committing them.

To amend the last commit, preserving its message, you can use:

```bash
git commit --amend
```

To amend the last commit, rename its message, you can use:

```bash
git commit --amend "Rename commit message"
```