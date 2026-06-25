# Create a Repository with Forking

**Date:** 2026-06-25

## Objective

Practice a complete Git and GitHub workflow using a repository created from scratch.

## Workflow Completed

- Created a new GitHub repository
- Cloned the repository locally
- Verified repository status
- Created a feature branch
- Updated the README
- Reviewed changes with `git diff`
- Staged changes with `git add`
- Committed changes
- Pushed the feature branch to GitHub
- Opened a Pull Request
- Merged the Pull Request
- Pulled the updated `main` branch locally
- Deleted the feature branch locally and remotely

## Commands Practiced

```bash
git clone
git switch -c feature/update-readme
git status
git diff
git add README.md
git commit -m "docs: update README for forking lab"
git push -u origin feature/update-readme
git pull
git branch -d feature/update-readme

## Lessons Learned
- Feature branches isolate work from main.
- git diff is useful for reviewing changes before committing.
- Pull Requests are the standard workflow for merging changes.
- Cleaning up merged branches keeps a repository organized.
- Local Git and GitHub work together as one development workflow.


## Reflection

This was my first complete GitHub workflow performed on my own repository rather than only following the Coursera environment. Creating the repository, cloning it, developing on a feature branch, opening a Pull Request, merging it, synchronizing my local repository, and cleaning up the branches helped connect the individual Git commands into one complete workflow. I now have a much better understanding of how this process is used in real software development.