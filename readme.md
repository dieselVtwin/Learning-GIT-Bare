# Learning about Bare Repos

Just trying to understand fetching from a remote, like GitHub, into a bare repo.

Maybe I need to use 'git remote update' from the bare repo?
- that didn't get all of the branched...

Maybe I need to do this to fix it...
    git config --global remote.origin.fetch "+refs/heads/*:refs/remotes/GitHub/*"
... and then retry...
    git fetch GitHub
