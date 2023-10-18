# Delete all local branches

from <https://stackoverflow.com/a/10610669>:

```shell
git branch --merged | grep -v \* | xargs git branch -D 
```

Also see: [[Delete any local branches that have been deleted upstream]]