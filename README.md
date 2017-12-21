# A git hooks playground

The git hooks are normally located at `.git/hooks/` directory.  Unfortunately, hooks created in that directory is not pushed to git repo.

The easiest solution is to ask git to look at the `hooks` directory else where.  In this case, at the project root by running the following command:

```
git config core.hooksPath hooks
```

ref: https://stackoverflow.com/questions/427207/can-git-hook-scripts-be-managed-along-with-the-repository
