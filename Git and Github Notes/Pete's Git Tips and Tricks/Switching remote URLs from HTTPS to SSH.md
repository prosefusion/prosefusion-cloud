# Switching remote URLs from HTTPS to SSH

_from https://docs.github.com/en/get-started/getting-started-with-git/managing-remote-repositories_

1.  List your existing remotes in order to get the name of the remote you want to change.
    
    ```shell
    $ git remote -v
    > origin  https://github.com/USERNAME/REPOSITORY.git (fetch)
    > origin  https://github.com/USERNAME/REPOSITORY.git (push)
    ```
    
2.  Change your remote's URL from HTTPS to SSH with the `git remote set-url` command.
    
    ```shell
    $ git remote set-url origin git@github.com:USERNAME/REPOSITORY.git
    ```
    
3.  Verify that the remote URL has changed.
    
    ```shell
    $ git remote -v
    # Verify new remote URL
    > origin  git@github.com:USERNAME/REPOSITORY.git (fetch)
    > origin  git@github.com:USERNAME/REPOSITORY.git (push)
    ```