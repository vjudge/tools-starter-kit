# git 安装


### CentOS 安装
```
$ cd /tmp
$ wget https://mirrors.edge.kernel.org/pub/software/scm/git/git-2.30.2.tar.gz
$ tar -xvzf git-2.30.2.tar.gz
$ cd git-2.30.2/
$ ./configure
$ make
$ sudo make install
$ git --version # 输出 git 版本号，说明安装成功
```



### 安装完成后配置
```
# 设置用户名
$ git config --global user.name "vjudge"
# 设置邮箱
$ git config --global user.email "gradonday@gmail.com"
# 设置 Git，保存用户名和密码
$ git config --global credential.helper store
# 解决 Git 中 'Filename too long' 的错误
$ git config --global core.longpaths true
# 配置国内镜像网站访问 github
$ git config --global url."https://github.com.cnpmjs.org/".insteadOf "https://github.com/"
# 放开 github 最大只能克隆 100M 的限制
$ git lfs install --skip-repo
# 可选: 非 ASCII 在终端输出显示方式
$ git config --global core.quotepath off
```
