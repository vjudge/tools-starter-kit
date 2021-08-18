# git branch


### 不带参数：列出本地已经存在的分支
```
git branch
```


### 创建名为dev的分支，创建分支但依然停留在当前分支
```
git branch dev
```


### 删除dev分支
```
git branch -d dev
# 强制删除dev分支
git branch -D dev
```


### 查看远程版本库分支列表
```
git branch -r
```


### 查看所有分支列表，包括本地和远程
```
git branch -a
```


### 查看本地分支对应的远程分支
```
git branch -vv 
```


### 重命名分支
```
git branch -m oldName newName
```










