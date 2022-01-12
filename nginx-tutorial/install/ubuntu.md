# 安装 nginx


### 预安装
```shell
sudo apt-get update
sudo apt-get install build-essential
sudo apt-get install libpcre3 libpcre3-dev
sudo apt-get install openssl libssl-dev
sudo apt-get install zlib1g-dev
```


### 下载
http://nginx.org，打开 download，找到合适版本，进行下载
```shell
wget  http://nginx.org/download/nginx-1.20.1.tar.gz
```


### 解压
```shell
tar -xzf nginx-1.20.1.tar.gz
```


### 指定目录
```shell
./configure --prefix=/home/ubuntu/nginx
```


### 
```shell
make
make install
```


### 启动
```shell
sudo ./sbin/nginx
```
