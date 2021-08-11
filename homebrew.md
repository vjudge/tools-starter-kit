# homebrew
* [homebrew](https://brew.sh/index_zh-cn)
* 使用 Homebrew 安装 Apple（或您的 Linux 系统）没有预装但需要的东西。Homebrew 会将软件包安装到独立目录，并将其文件软链接至 /usr/local 。

### 安装
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```


### 更新 brew
```
brew update
```


### 显示包信息
```
brew info [pkg_name]
# 显示安装了包数量，文件数量，和总占用空间
brew info 
```


### 
```
# 可以显示包的依赖关系，查看已安装的包的依赖，然后判断哪些包是可以安全删除的
brew deps 
# 查看已安装的包的依赖，树形显示  
brew deps --installed --tree         
```


### 更新包
```
# 更新指定的包
brew upgrade [pkg_name]
# 更新所有的包
brew upgrade
# 会安装新版本的包，但旧版本仍然会保留
brew outdated
```


### 清理安装的包
```
# 清理指定包的版本
brew cleanup [pkg_name]
# 清理所有包的旧版本
brew cleanup 
# 查看可清理的旧版本包，不执行实际操作
brew cleanup -n
```


### 锁定包
```
# 锁定某个包
brew pin $FORMULA  
# 取消锁定    
brew unpin $FORMULA    
```


























