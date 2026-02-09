# Learning about Bare Repos

Just trying to understand fetching from a remote, like GitHub, into a bare repo.

Maybe I need to use 'git remote update' from the bare repo?

- that didn't get all of the branched...

Maybe I need to do this to fix it...
    git config --global remote.GitHub.fetch "+refs/heads/*:refs/remotes/GitHub/*"
... and then retry...
    git fetch GitHub

That still didn't work, but I think I'm getting close.

More later...
