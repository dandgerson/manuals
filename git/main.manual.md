# Git Manual

## Checkout **remote** git branch on my local rep

Go to remote branch

```bash
  > git branch -r // check remote branches
  
  -> origin/1-js/02-first-steps/12-while-for // check your need branch
  origin/1-js/02-first-steps/13-switch
  origin/1-js/02-first-steps/14-function-basics
  origin/1-js/02-first-steps/15-function-expressions-arrows
  origin/1-js/04-object-basics/05-object-toprimitive
  origin/HEAD -> origin/master
  origin/master
  origin/sync-19223ae7

  > git checkout -b 1-js/02-first-steps/12-while-for origin/1-js/02-first-steps/12-while-for // done

```

## Update fork with original repository

Sync fork and original

```bash
  > git checkout master
  > $ git pull https://github.com/ORIGINAL_OWNER/ORIGINAL_REPOSITORY.git BRANCH_NAME
  > git push

```

## Delete branch

Delete local branch

```bash
  > git branch -D BRANCH_NAME

```

## Push New Created Branch

```bash
  > git push --set-upstream origin BRANCH_NAME

```