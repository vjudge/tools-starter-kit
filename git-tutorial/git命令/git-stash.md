# git stash


### 将消息存入存储列表
```
git stash save “Your stash message”
git stash save -u
git stash save --include-untracked
```


### 查看存储列表
```
git stash list
```


### 将工作栈中最上面的 stash 应用到仓库中
```
# 通过 stash id 将某个 stash 应用到仓库中
git stash apply stash@{1}
```


### 从存储列表中删除
```
# 最上面的 stash 被删除了
git stash pop
# 通过特定的 stash id 来 pop 某个 stash
git stash pop stash@{1}
```


### 显示 stash 差异总结。只考虑和最近的 stash 比较。
```
git stash show
# 查看完整的差异
git stash show -p
# 通过 stash id 来查看某个 stash 的差异总结
git stash show stash@{1}
```


### 清空存储列表（删除存储列表所有数据）
```
git stash clear
```


### 删除工作栈中最近的 stash
```
git stash drop
git stash drop stash@{1}
```







