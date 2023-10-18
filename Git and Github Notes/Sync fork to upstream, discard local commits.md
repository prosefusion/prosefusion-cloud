# Sync fork to upstream, discard local commits

Check for upstream.

```shell
git remote -v
```

If necessary, add an upstream.

```shell
git remote add upstream git@git.example.com:some-gatekeeper-maintainer/some-project.git
```

Confirm upstream.

```shell
git remote -v
```

Confirm you're on `main`, reset.

```shell
git checkout main
git fetch upstream
git reset --hard upstream/master
git push --force
```
