# Submodule guide

## Adding an existing Git repository as a submodule of the repository that we’re working on

Add submodule

> git submodule add [submodule-repo-url]

> git commit -am 'Add submodule module'

> git push origin master

## Cloning a repository including its submodules
> git clone --recursive [repo-url]


## Pull all changes of branch master for the submodules
> git submodule update --remote


## Set a specific submodule track branch   

> git config -f .gitmodules submodule.DbConnector.branch [branch name]

