# GIT HELPER SCRIPTS

Some scripts I wrote when working with "git". The convention is
to name them `git-h-DESCRIPTION`, feel free to make pull requests.

## Dependencies

- Git
- A POSIX Shell.
- gh (Github CLI) for github-h-desc.

## Help

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

git-traverse

    Usage: git-traverse [-m]
    
    Read a directory list from the standard input and present a fast
    git operations menu. With -m only those with changes.

github-h-desc

    Usage: github-h-desc [USERNAME/]PROJECT
    
    Print Github project's description using `gh` and `github-h-url`.

github-h-url

    Usage: github-h-url [USERNAME/]PROJECT
    
    Print the Github project's URL. If USERNAME is not specified
    then the environment variable GITHUB_USERNAME is used.

projectm

    Usage: projectm ...
    
    This script helps managing your git projects. For this write
    a file in $PROJECTM_FILE with the following format.
    
        G <group> <title>
        C <group> <category> <description>
        D <dir>
        P <dir>/<name> <origin> <category> <tags...>
    
    You can set where the <dir> are located setting $PROJECTM_PATH. You
    can view the configuration with `projectm show`.
    
    ... dirs|prjs           : Print listed directory and project pathnames.
    ... grps|cats [<group>] : Print listed groups and categories.
    ... prjs-new            : List projects not listed in $PROJECTM_FILE.
    ... prjs-rem <origin>   : List projects in $PROJECTM_FILE with <origin>.
    ... prjs-cat <category> : List projects in $PROJECTM_FILE with <category>.
    ... grp-title <group>   : Get group's title.

projectm-github

    Usage: projectm-github -u
    
    Perform common Github operations on your projects.
    
        -l        : List Github projects.
        -u [DIRS] : Update descriptions from Github.
        -p [DIRS] : Print 'PROJECT: DESCRIPTION' summary.

projectm-github-page

    Usage: projectm-github-page ...
    
    Print my project list in Gopher/Gemini format.
    
    ... gopher : Print gopher page.
    ... gemini : Print gemini page.

## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)

