# Instead of "git pull", if you know you don't want to keep any local changes

## fast-forward (read more about this)

[merge \- Can I make fast forwarding be off by default in git? \- Stack Overflow](https://stackoverflow.com/questions/2500296/can-i-make-fast-forwarding-be-off-by-default-in-git)

## git fetch && git reset

```shell
git fetch origin main && git reset --hard origin/main
```

"Considering the definition of git pull is git fetch && git merge, the merge isn't unexpected." - https://stackoverflow.com/a/12645821

Also see: [version control \- What is the difference between 'git pull' and 'git fetch'? \- Stack Overflow](https://stackoverflow.com/questions/292357/what-is-the-difference-between-git-pull-and-git-fetch?rq=1)

> Our alternative approach has become git fetch; git reset --hard origin/master as part of our workflow. It blows away local changes, keeps you up to date with master BUT makes sure you don't just pull in new changes on top on current changes and make a mess. We've used it for a while and it basically feels a lot safer in practice. Just be sure to add/commit/stash any work-in-progress first ! - https://stackoverflow.com/questions/292357/what-is-the-difference-between-git-pull-and-git-fetch?rq=1#comment35959558_292357


## git pull --rebase

```shell
git pull --rebase
```

<https://stackoverflow.com/questions/52123938/how-is-git-pull-rebase-different-than-git-reset-soft-origin-b#comment91200789_52123938>:

> `git pull` is just a shorthand for `git fetch` + `git merge`. `git pull --rebase` is `git fetch` + `git rebase` instead.

and <https://stackoverflow.com/a/52124906>:

> No, they are quite different.

also:

- [git pull vs git pull \-\-rebase explained with examples \| GoLinuxCloud](https://www.golinuxcloud.com/git-pull-vs-git-pull-rebase/)
- [What is the difference between "git reset" vs "git rebase"? \- Stack Overflow](https://stackoverflow.com/questions/11225293/what-is-the-difference-between-git-reset-vs-git-rebase)