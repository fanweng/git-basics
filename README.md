# Git

Documentation: [https://git-scm.com/docs](https://git-scm.com/docs)

# Clone A Repository

`$ git clone repository_url`

# Create New Repository Procedure

Firstly, create a repository on Github and get *your_repo_url*. Secondly, go to your local project directory and initialize *git*:

`$ git init`

`$ git add README.md`

`$ git status`

`$ git add <file_name_1>...`

`$ git rm <file_name_1>...`

`$ git status`

`$ git commit -m "your_comment"`

`$ git remote add origin your_repo_url` from now on 'origin' means your repository

`$ git push -u origin master_or_other_branch` uses '-u' for the first time, it can be ignored afterwards

# Discard Working Directory Changes

`$ git checkout -- <file_name_1>...`

# Unstage Changes to Working Directory

`$ git reset HEAD <file_name_1>...`

# Show Logs and History

`$ git log --oneline` shows current HEAD and its ancestry

`$ git log --graph --pretty=oneline --abbrev-commit` draws graph of branch structure

`$ git reflog` shows the entire history

# Reset to A Version

`$ git reset --hard commit_id` where commit_id can be found in the log/history

# Branch

`$ git checkout -b branch_name` equals two following commands combined

`$ git branch branch_name`

`$ git checkout branch_name`

`$ git merge branch_name`

`$ git branch -d branch_name`

# Remote Info

`$ git remote -v`

# Work Collaboration

`$ git push origin branch_name`

`$ git

# Reference

[A Beginner's Git and GitHub Tutorial](https://blog.udacity.com/2015/06/a-beginners-git-github-tutorial.html)

[Git - Simple Guide](http://rogerdudler.github.io/git-guide/)

[Xuefeng Liao's Git Tutorial](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)
