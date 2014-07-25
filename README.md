MyRepository
============

Personal resource
个人资源


Username ZZHGit
Mail zhaozhenhua121@sina.com
Password *********

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