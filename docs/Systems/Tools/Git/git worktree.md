# git worktree

> open multiple [[Git]] branches/commits in different folders. Helps to eliminate needless commits and [[git-stash|stash]]

I find this very helpful when I need to open multiple versions/branches at the same time. 
This is especially useful to open different [[git-branch|branches]] of [[LS-DYNA]] model files, as each one would have a different output files.

## Examples

`git worktree add dir1 branch1`

This starts a new folder `dir1`  and checks out branch1

`git worktree add ../foldername branch-name`

`git worktree add ../foldername commit-hash`




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
- [Simple git worktree tutorial](https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/Use-this-git-worktree-add-example-and-never-switch-branches-again)  
