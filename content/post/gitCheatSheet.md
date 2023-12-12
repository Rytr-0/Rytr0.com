+++
title = 'Git Cheat Sheet'
date = 2023-12-12T10:42:12-05:00
draft = false
description =' '
summary = ' ' 
+++

>
# Commands:
>
## Branches:
>
- list the brnaches:

  `git branch`

- swtich branch:

  `git checkout other-branch`

- rename the local branch:

  `git branch -m master main`

- delete a local branch:

`git branch -d branch_name`

- delete a local branch but **force**:

`git branch -D branch_name`

- to delete a remote branch:

`git push origin --delete <remote-branch-name>`

## Merge:

- Merge a specific file from another branch to the master branch:

`git checkout feature-branch -- example.txt`

## Push:

- push the changes to an added repo:

  `git push -u origin main`

- Update Local Repositories

  `git fetch --all`

## History:

- Basic Commit History:

`git log`

- Limit the Number of Commits:

`git log -n 5`

-  Detailed Commit Information:

`git log -p`

- filter by file:

`git log -- filename.txt`


## Other:

- check your ssh connection to github:

`ssh -T git@github.com`

- Check the Current Remote URL:

`git remote -v`

- Change/Set remote URL but HTTP:

`git remote add origin https://github.com/username/repository.git`

- Change/Set remote URL but SSH:

`git remote set-url origin git@github.com:username/repository.git`
