# ZERO_GIT_TUTORIAL
SNUZERO 2019 Git tutorial
-------------------------
1. Git clone

Cloning this directory.

    $ git clone https://github.com/tkdals9082/ZERO_GIT_TUTORIAL.git

2. Git add

Save your changes in working directory to the stage.

    $ git add WHAT_YOU_WANT_TO_SAVE
or

    $ git add *

to add all the files that you change.

3. Git commit

Save your changes to the HEAD.

    $ git commit -m "SOME_COMMENT"

4. Git push

Push your changes to the remote server.

    $ git push origin master

5. Git branch

make new branch and go to the branch

    $ git checkout -b NEW_BRANCH_NAME

move between branches

    $ git checkout BRANCH_NAME

delete local branch

    $ git branch -d BRANCH_NAME

delete remote branch

    $ git push origin :BRANCH_NAME

push your branch

    $ git push origin BRANCH_NAME

merge branch

    $ git merge BRANCH_NAME