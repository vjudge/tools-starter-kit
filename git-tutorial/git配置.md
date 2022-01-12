# git配置


### 配置user信息
* 针对所有的git仓库生效。
```
git config --global user.name "your name"
git config --global user.email "your_email@domain.com"

```

* 只对当前工作的git仓库生效。
```
git config --local
```

* 对系统设置的所有系统生效。
```
git config --system
```


### 查看config的配置
```
git config --list  # 查看所有git配置
git config --list --global
git config --list --local
git config --list --system
```









