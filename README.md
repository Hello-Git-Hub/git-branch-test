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

    # how to merge remote main to local branch b1 
    git checkout main   # first go to main branch
    git pull       # pull remote main to local main branch
    git checkout b1 # then go to b1 branch
    git merge main  # merge local main to b1



