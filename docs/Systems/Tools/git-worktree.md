---
aliases: Git Worktree
---

# Git Worktree

open multiple [[Git]] branches/commits in  different folders

I find this very helpful when I need to open multiple versions/branches at the same time. 
This is especially useful to open different [[_LS-DYNA|LS-DYNA]] version-controlled branches as each one would have a different set off output files.

## Example

`git workflow add sim1 branch1`

This start a new folder `sim1`  and checkout branch1


##  Commands

```
git worktree add <path> [<commit-ish/branch>]
git worktree list [<options>]
git worktree lock [<options>] <path>
git worktree move <worktree> <new-path>
git worktree prune [<options>]
git worktree remove [<options>] <worktree>
git worktree unlock <path>
```

## Resources

- Demo by [ThePrimeagen](https://www.youtube.com/watch?v=2uEqYw-N8uE)