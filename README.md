# git branch&merge cheatsheet

    # list branches
    git branch -a

    # create local branch
    git branch b1

    # merge branch b1 to main
    git checkout main
    git merge b1

    # discart merge
    git merge --abort

    # push newly created branch to remote
    git push origin -u b1

    # delete remote branch b2
    git push origin --delete b1

    # merge master to branch b1 (way1)
    git checkout b1
    git merge master b1

    # merge master to branch b1 (way2)
    git checkout b1
    git pull origin master

