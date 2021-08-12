# git add


### 语法
```
git add [file1] [file2] ...
```

### 提交所有变化
```
git add -A
```


### 提交所有修改的和新建的数据暂存区，会根据.gitignore做过滤
```
git add .
```


### 提交所有修改的和新建的数据暂存区，会忽略.gitignore把任何文件都加入
```
git add *
```


### 提交所有被删除和修改的文件到数据暂存区，不包括新文件(new)
```
git add -u
git add –update
```












