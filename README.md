README for myGitHub
===
## CREATE related command

To create a local repository
`git init`

to clone an repository from remote server
`git clone`

list changed files in your working directory
`git status`

List changed to traked files
`git diff`

Add all current changed in file to the next commit
`git add`

Add all current changed to the next commit
`git add .`

Delete file and add its deletion to next commit
`git rm`

Commit all local changes in tracked files
`git commit -a`

Download all changes from remote, but don't merge into HEAD
从远程库更新所有的信息到本地，但是不合并
`git fetch <remote>`

Download changes and directly merge into HEAD
从远程库更新数据并立即合并数据
`git pull <remote><branch>`

Publish local changes on a remote
`git push <remote><branch>`

Show information about a submodule
显示远程库信息
`git remote show <remote>`

Discarding local changes
回退到某个版本
`git rest --hard <commit>
回退到某个版本并保存未追踪的改动
`git reset <commit>`

回退到某个版本并保存未提交的改动
`git reset --keep <commit> `
