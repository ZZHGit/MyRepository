﻿MyRepository
============

Personal resource
个人资源


Username ZZHGit
Mail zhaozhenhua121@sina.com
Password *********
Git help git
MsysGit安装
Fork the repository
Clone your fork
git clone https://github.com/username/Spoon-Knife.git
git clone https://github.com/username/Spoon-Knife.git
cd Spoon-Knife
git remote add upstream https://github.com/octocat/Spoon-Knife.git
获取远程更新,但不修改本地文件
git fetch upstream
合并到本地文件
git merge upstream/master
git push origin master

获取并合并
git pull upstream master

git branch mybranch
# Creates a new branch called "mybranch"
git checkout mybranch（To switch between branches, use git checkout.）
# Makes "mybranch" the active branch

git checkout master
# Makes "master" the active branch
git merge mybranch
# Merges the commits from "mybranch" into "master"
git branch -d mybranch
# Deletes the "mybranch" branch

实际上 Git 只不过暂存了你运行 git add 命令时的版本，如果现在提交，
那么提交的是添加注释前的版本，而非当前工作目录中的版本。
所以，运行了git add 之后又作了修订的文件，需要重新运行 git add 
把最新版本重新暂存起来.

给 git commit 加上 -a 选项，Git 就会自动把所有已经跟踪过的文件暂存起来一并提交，从而跳过 git add步骤
Git log
git log --pretty=format:"%h - %an, %ar : %s"
git log --since=2.weeks

取消已经暂存的文件
git reset HEAD <file>..

