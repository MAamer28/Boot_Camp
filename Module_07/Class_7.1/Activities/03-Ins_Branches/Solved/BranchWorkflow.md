# Branching in Git

This document contains a branching workflow cheatsheet.

## Branching Workflow

1. Create a branch: `git branch <branch_name>`
2. Checkout the new branch: `git checkout <branch_name>`
3. Use `git add` and `commit` as normal.
4. When you want to push your branch to GitHub, do: `git push origin <branch_name>`
5. When you want to merge your new branch into main, do the following four steps:
   1. `git checkout main`
   2. `git pull origin main`
   3. `git merge <branch_name>`

Note that you can do `git checkout --branch <branch_name>` to create a new branch _and_ immediately check it out with a single command.

- - -

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
