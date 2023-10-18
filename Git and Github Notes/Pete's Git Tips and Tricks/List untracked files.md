# List untracked files

From <https://stackoverflow.com/a/3801554> by PEdroArthur.

To list untracked files try:

```
git ls-files --others --exclude-standard
```

If you need to pipe the output to `xargs`, it is wise to mind white spaces using `git ls-files -z` and `xargs -0`:

```
git ls-files -z -o --exclude-standard | xargs -0 git add
```

For reference: [git-ls-files](http://git-scm.com/docs/git-ls-files)