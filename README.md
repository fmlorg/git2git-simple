# git2git-simple

a simple shell script to move GIT repositry from there to here.
This script is 100+ lines,
so it must be suitable to learn a shell script writing.


## Getting Started

Get the repository
```
git clone https://github.com/fmlorg/git2git-simple

or

git clone   ssh://git@github.com/fmlorg/git2git-simple
```

## How to use

run
```
sh git2git-simple.sh SRC_REPO DST_REPO
```
where
SRC_REPO and DST_REPO should be a github format e.g. ssh://git@github.com/id/repo.


## Examples

If you want to move an old repository "fmlorg/git2git-simple" to a new repository "example/git-move"
on the github.com, 

1. create "example/git-move" repository on the github.com
2. run the following command
   ```
   sh git2git-simple.sh ssh://git@github.com/fmlorg/git2git-simple ssh://git@github.com/example/git-move
   ```
   1. this script clone the old repository
   1. upload the old repository content to the new repository
