# How to find the Git commit that introduced a string in any branch

[How to find the Git commit that introduced a string in any branch?](https://stackoverflow.com/a/5816177) (stackoverflow.com)

```shell
git log -S <whatever> --source --all
```

> To find all commits that added or removed the **fixed string** `whatever`. The `--all` parameter means to start from every branch and `--source` means to show which of those branches led to finding that commit.

> It's often useful to add `-p` to show the patches that each of those commits would introduce as well.

> Versions of git since 1.7.4 also have a similar **`-G` option, which takes a regular expression**. This actually has different (and rather more obvious) semantics, explained in [this blog post from Junio Hamano](http://gitster.livejournal.com/48191.html).