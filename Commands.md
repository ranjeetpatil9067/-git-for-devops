# Git Commands Reference

## Checking Repository Status

    git status

## Viewing Commit History

    git log
    git log --oneline

## Creating and Switching Branches

    git branch
    git branch <branch_name>
    git checkout <branch_name>
    git checkout -b <new_branch>

## Staging and Committing Changes

    git add <file_name>
    git add .
    git commit -m "Your commit message"

## Removing Files

    rm <file_name>
    git rm <file_name>

## Merging Branches

    git checkout <target_branch>
    git merge <source_branch>

## Deleting Branches

    git branch -d <branch_name>
    git push origin --delete <branch_name>

## Checking Out Specific Commits

    git checkout <commit_hash>

## Undoing Changes

    git reset HEAD
    git checkout --
    git revert <commit_hash>

## Pushing and Pulling Changes

    git push origin <branch_name>
    git pull origin <branch_name>

## Creating and Switching to a New Branch from an Existing Branch

    git checkout -b <new_branch> <existing_branch>

## Viewing Remote Repositories

    git remote -v

## Cloning a Repository

    git clone <repo_url>

## Fetching Remote Changes

    git fetch origin

## Checking the Last Commit

    git show
