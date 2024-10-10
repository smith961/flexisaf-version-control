
# Version Control

Practicing various git command and their executions


## Creating a Repository

 - created on my GitHub account
 

## Cloning a Repository

 - git init
 - git clone <repository-url>
 - git clone https://github.com/smith961/flexisaf-version-control.git

## Create new-branch

- git branch <branch-name>
- git branch Smitho
 
## Change to new-branch

- git checkout <branch-name>
- git checkout Smitho

 ## Committing Changes

- git add <file-name> or git add .
- git add .

## Adding Commit message

- git commit -m 'initial commit'
- git commit -m "<commit-message>"

## Reverting Commits

- git revert <commit-hash>
- git revert commit - git log --oneline | -git revert
- quit editor - q | - git push

## Pulling Changes (Downstream and Upstream)

- git pull <remote-name> <branch-name>
- git pull Version-Control-Repo main

## Pushing Changes (Downstream and Upstream)

- git push <remote-name> <branch-name>
- git push Version-Control-Repo main

## Fetching Changes

- git fetch <remote-name>
- git fetch Version-Control-Repo

## Merging Branches

- git merge <branch-name>
- git merge Smitho

## Renaming Branches

- git branch -m <new-branch-name>
- git branch -m Smitho
- git push origin -u Smitho

## Creating Pull Requests

- pull request was created and done on the github repository online.

## Reverting Pull Requests

- git log
- git revert <merge-commit-hash>
