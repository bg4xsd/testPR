
## Global setting for Github:
git config --global user.name "bfcat" 

git config --global user.email "bfcat.cn@outlook.com" 

git config --global credential.helper store

## Check config list
git config --list

git remote -v

if not remote setting, add below

git remote add origin https://gitee.com/bfcatlu/tsalab.git

## Pull & Push
git pull origin main # for the first time

git push origin main # necessary step For new repository

It will prompt enter username and pwd

## Fix long path problem
git config --global core.longpaths true