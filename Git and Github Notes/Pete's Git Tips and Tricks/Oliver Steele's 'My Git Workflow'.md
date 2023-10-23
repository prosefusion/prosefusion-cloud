# Oliver Steele's 'My Git Workflow'

https://blog.osteele.com/2008/05/my-git-workflow/

Nice diagram:

![[oliver-steele-git-transport.png]]

Explains Git's overall model, and makes a really good point about Git's complexity:

> But first, a piece of background that helps in understanding Git. Git isn’t at its core a VCS. It’s really a distributed versioning file system, down to its own [fsck](https://www.kernel.org/pub/software/scm/git/docs/git-fsck.html) and [gc](https://www.kernel.org/pub/software/scm/git/docs/git-gc.html). It was developed as the bottom layer of a VCS, but the VCS layer, which provides the conventional VCS commands (`commit`, `checkout`, `branch`), is more like an uneven veneer than like the “porcelain” it’s sometimes called: bits of file system (git core) internals poke through.
> 
> The disadvantage of this (leaky) layering is that Git is complicated. If you look up how to diff against yesterday’s 1pm sources in [git diff](https://www.kernel.org/pub/software/scm/git/docs/git-diff.html), it will send you to [git rev-parse](https://www.kernel.org/pub/software/scm/git/docs/git-rev-parse.html) from the core; if you look up [git checkout](https://www.kernel.org/pub/software/scm/git/docs/git-checkout.html), you may end up at [git-check-ref-format](https://www.kernel.org/pub/software/scm/git/docs/git-check-ref-format.html). Most of this you can ignore, but it takes some reading to figure out which.
> 
> The advantage of the layering is that you can use Git to build your own workflows. Some of these workflows involve the index. Like the other fancy Git features, building your own workflows is something that you can ignore initially, and add when you get to where you need it. This is, historically, how I’ve used the index: I ignored it until I was comfortable with more of Git, and now I use it for a more productive workflow than I had with other VCS’s. It’s not my main reason for using Git, but it’s turned to a strength from being a liability.