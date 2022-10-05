# Git Training
> This repository will guide you to the different git situation and will help you to get some practical experience with git

> __Although, it is REQUIRED to google topics by yourself and try to understand every step. Don't hesitate to ask questions if any.__
---
> __Side note:__ We are assuming that you are __familiar__ with basic git commands such as `git add`, `git push`, `git commit`, etc. If you are not, then please check [this](https://www.freecodecamp.org/news/git-and-github-for-beginners/) and [this](https://learngitbranching.js.org/) first.
---

## Setup
To get started simple [fork](https://docs.gitlab.com/ee/user/project/repository/forking_workflow.html) this repository and start doing assignments described below.

---
## 1. Oh, no! Wrong name
Let's imagine the next situation. You accidentally made a commit with wrong name or email.
In basic situation, when you figured that you last commit have wrong author, you can fix it quickly. Simply run this command `git commit --amend --author="Author Name <email@address.com>" --no-edit` with proper author. You can find detailed explanation of `--amend` flag [here](https://www.atlassian.com/git/tutorials/rewriting-history#git-commit--amend).

You can find a branch named `wrong-name` which contains commit with message`Wrong commit`. Your __first task__ is to fix that commit with you actual name.
> *Will be better if you fix commit message too (read `--amend` documentation)
 
> If commit is already pushed to the remote, you can override it using `git push -f`, be __careful__ with `-f` flag it will override you target branch

---
## 2. Merge
This one is pretty basic, you need to merge the `master` branch to the target `merge` branch (checkout to the `merge`). See docs for merge [here](https://www.w3schools.com/git/git_branch_merge.asp).

---
## 3. Merge conflict
Merge conflicts in git happen, when two branches were changed on the same line or in the same content of a file before a merge. If you just extend a file or append something, git usually just figures it out by itself. You next task is to merge `master` to the target `merge-conflict` branch and fix all conflicts

---
## 4. Merge request
A merge request (MR) is a request from someone to merge in code from one branch to another. In this task you need to create a new branch, name is up to you. Then add a new file named `index.html` and push those change to the remote. Use [this](https://docs.gitlab.com/ee/user/project/merge_requests/creating_merge_requests.html) guide to create MR

___
### 5. Rebase
Rebasing is the process of moving or combining a sequence of commits to a new base commit. It is crucial to understand the difference between merge and rebase. For this, check the next [link](https://www.atlassian.com/git/tutorials/merging-vs-rebasing), [link](https://medium.datadriveninvestor.com/git-rebase-vs-merge-cc5199edd77c)

Your task is to rebase the `master` branch to the target `rebase` branch (checkout to the `rebase`). And fix all conflicts