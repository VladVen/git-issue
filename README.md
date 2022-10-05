# Git Training
> This repository will guide you to the different git situation and will help you to get some practical experience with git
---
> __Side note:__ We are assuming that you are __familiar__ with basic git commands such as `git add`, `git push`, `git commit`, etc. If you are not, then please check [this](https://www.freecodecamp.org/news/git-and-github-for-beginners/) and [this](https://learngitbranching.js.org/) first.
---

## Setup
To get started simple [fork](https://docs.gitlab.com/ee/user/project/repository/forking_workflow.html) this repository and start doing assignments described below.

## 1. Oh, no! Wrong name
Let's imagine the next situation. You accidentally made a commit with wrong name or email.
In basic situation, when you figured that you last commit have wrong author, you can fix it quickly. Simply run this command `git commit --amend --author="Author Name <email@address.com>" --no-edit` with proper author. You can find detailed explanation of `--amend` flag [here](https://www.atlassian.com/git/tutorials/rewriting-history#git-commit--amend)