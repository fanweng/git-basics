# Git

Documentation: [https://git-scm.com/docs](https://git-scm.com/docs)

# Clone A Repository

`$ git clone <repository_url>`

# Create New Repository Procedure

Firstly, create a repository on Github and get *your_repo_url*. Secondly, go to your local project directory and initialize *git*:

`$ git init`

`$ git add README.md`

`$ git status`

`$ git add <file_name_1>...`

`$ git rm <file_name_1>...`

`$ git status`

`$ git commit -m "your_comment"`

`$ git remote add origin <your_repo_url>` from now on 'origin' means your repository

`$ git push -u origin <master_or_other_branch>` uses '-u' for the first time, it can be ignored afterwards

# Discard Working Directory Changes

`$ git checkout -- <file_name_1>...`

# Unstage Changes to Working Directory

`$ git reset HEAD <file_name_1>...`

# Undo a Local Commit

`$ git reset HEAD~1`

# Show Logs and History

`$ git log --oneline` shows current HEAD and its ancestry

`$ git log --graph --pretty=oneline --abbrev-commit` draws graph of branch structure

`$ git reflog` shows the entire history

# Reset to A Version

`$ git reset --hard <commit_id>` where commit_id can be found in the log/history

# Branch

`$ git branch (-a)` shows a list of branches

`$ git checkout -b <branch_name>` equals two following commands combined

`$ git branch <branch_name>` creates a new branch

`$ git checkout <branch_name>` checkouts or switches to an existing branch

`$ git merge <branch_name>`

`$ git branch -d <branch_name>` deletes a branch

# Remote Info

`$ git remote -v`

`$ git remote -v update` checks if the branch gets updated

`$ git remote show origin` shows the original information of the cloned repository

# Work Collaboration Procedure

`$ git push origin <branch_name>`

`$ git pull`

`$ git branch --set-upstream <branch_name> <origin/branch_name>`

# Tag

`$ git tag <tag_name>` default will tag HEAD

`$ git tag <tag_name> <commit_id>`

`$ git tag` show tag list

`$ git tag -a <tag_name> -m "your tag message" <commit_id>` add tag message

`$ git show <tag_name>` show tag information

`$ git push origin <tag_name>`
`$ git push --tag`

# Diff

`$ git diff file` show diff of the file that hasn't been git-added

`$ git diff --cached file` show diff of the added file

# Reference

[A Beginner's Git and GitHub Tutorial](https://blog.udacity.com/2015/06/a-beginners-git-github-tutorial.html)

[Git - Simple Guide](http://rogerdudler.github.io/git-guide/)

[Xuefeng Liao's Git Tutorial](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)
