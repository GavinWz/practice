# 创建git本地仓库

```
git init
```

# 远程仓库两种连接方式
### 添加远程仓库地址
### 1. HTTPS

git remote add origin https://github.com/GavinWz/practice.git 

### 查看本地仓库状态
git status

### 添加本地更改 （暂存区）
git add <file names>  # 将本地修改过的文件，添加到本地暂存区
git add . # 将本地所有更改添加到暂存区（除了gitignore中指明的文件）

git commit -m "评论信息"  # 提交本地已经添加的修改，并添加评论

## 创建main仓库
