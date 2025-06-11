# git add . 和 git add * 的区别
## git add .
添加当前目录及其子目录中的所有文件（包括隐藏文件）。    
## git add * 
添加当前目录下的非隐藏文件，而不包括子目录中的文件。

## git fetch origin
拉取远程仓库的最新信息（获取所有分支的更新）


## git branch
查看当前所在的分支（通常是 main 或 master）


## git merge origin/main
合并远程对应分支到本地当前分支（例如 main 分支）


# 将新项目上传仓库

## 准备本地项目
### 初始化Git仓库
git init

## 添加文件到本地仓库
### 添加所有文件到暂存区
git add .
### 提交更改
git commit -m "Initial commit"

## 关联 GitHub 远程仓库
### 复制 GitHub 仓库的 ‌HTTPS/SSH 地址
### 添加远程仓库地址（将 <url> 替换为复制的地址）
git remote add origin <url>

## 推送代码到 GitHub
git push -u origin main(本地分支名)


# 远程仓库操作
## 查看当前远程地址
git remote -v

## 修改远程仓库地址
git remote set-url origin [新仓库地址]

## 验证修改结果
git remote -v




