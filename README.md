# GIT HELPER SCRIPTS

Some scripts I wrote when working with "git". The convention is
to name them `git-h-DESCRIPTION`, feel free to make pull requests.

## Help

git-h-config

    Usage: git-h-config ...
    
    Configure the Git environment to my needs.
    
    ... g-gitignore  : Configure global `~/.gitignore`.
    ... g-gitmessage : Configure ~/.gitmessage.txt template.
    ... g-gitconfig  : Set text editor, filemode, etc.

git-h-delete

    Usage: git-h-delete
    
    Perform 'git rm' in all the files that where deleted.

git-h-get-branch

    Usage: git-h-get-branch
    
    Print the current branch of the project.

git-h-ls-branches

    Usage: git-h-ls-branches
    
    List branches in the project with committer's name and last
    commit date.

git-h-ls-submodules

    Usage: git-h-ls-submodules ...
    
    List submodules in the project recursively.

git-h-my-branch

    Usage: git-h-my-branch [-e] [-s BRANCH]
    
    Print the branch you should be working on. You can set it
    in `BRANCH_FILE` or `~/.branches` with WILDCARD BRANCH
    format.

git-h-sync

    Usage: git-h-sync
    
    Interactively fetch changes from the repository.

git-h-update-submodules

    Usage: git-h-update-submodules [--remote] ...
    
    Update submodules with `--init --recursive`.

git-ssh

    Usage: git-ssh [-s SECT][-S][-r SSH][-v] COMMAND OPTS...
    
    Manage a git repository in a remote SSH machine.
    
    ... show            : Show configuration.
    ... i|install       : Install GIT.
    ... l|list          : List repositories.
    ... n|new [NAME]    : Create repository with name.
    ... d|del NAME      : Delete repository.
    ... r|remote [NAME] : Set remote.
    ... c|clone NAME    : Clone project.
    ... u|url [NAME]    : Calculate URL.

## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)

