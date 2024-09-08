# 创建git本地仓库
```
git init
```
# 远程仓库两种连接方式
### 添加远程仓库地址
#### 1. HTTPS
git remote add origin https://github.com/GavinWz/practice.git 

#### 2. SSH
git remote add origin git@github.com:GavinWz/practice.git

### 查看本地仓库状态
git status 

### 查看提交日志
git log

### 添加本地更改 （暂存区）
git add <file names>  # 将本地修改过的文件，添加到本地暂存区
git add . # 将本地所有更改添加到暂存区（除了gitignore中指明的文件）

git commit -m "评论信息"  # 提交本地已经添加的修改，并添加评论

git commit -am "评论信息"  # 将git add . 和git commit -m "评论" 合并

### 创建main仓库
git branch -M main

### 将本地仓库中的main分支推送到远程仓库的main分支
git push -u origin main  (第一次提交时)
之后提交只需要：
git push

## 分支操作
1. 查看分支
git banch 

2. 添加分支
git branch 分支名
NOTE: 基于现在所在的分支上去新建分支，当前分支之前的修改也会记录在新分支中

3. 切换分支
git checkout 分支名
切换分支之前要提交当前分支的所有更改

4. 删除分支
* 先切换到其他分支
* git branch -d 分支名

5. 将本地分支推送到远程
git push -u origin b1

6. 将远程分支的修改拉取到本地分支
应该用git pull命令


