# Manual multi-file push scenario

This commit modifies existing files and adds this directory to exercise
selective object recovery and recursive tree comparison in Git Bouncer.

The accompanying JSON contains synthetic, non-sensitive configuration.

Push this branch with:

```sh
git push --progress -u origin HEAD
```

Expected result: progress messages during analysis, followed by an allowed push.
