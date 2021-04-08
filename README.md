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
and
run the `sh git2git-simple.sh SRC_REPOSITORY DST_REPOSITORY`
where
*_REPOSITORY are e.g. ssh://git@github.com/fmlorg/git2git-simple.

For example, if you want to move an old repository fmlorg/git2git-simple to a new repository prisoner-no6/git-move on the github.com, run
```
sh git2git-simple.sh ssh://git@github.com/fmlorg/git2git-simple ssh://git@github.com/prisoner-no6/git-move
```
Pay attention you need to create the corresponding github repository e.g. prisoner-no6/git-move in this case before you run the above command.

