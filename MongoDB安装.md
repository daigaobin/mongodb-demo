# mongodb-demo
Mongodb简单Demo程序

# 安装Mongodb
软件下载地址：https://www.mongodb.com/download-center#community

## window安装不在详述

## mac安装步骤：
1、进入 /usr/local
```
cd /usr/local
```
2、下载
```
sudo curl -O https://fastdl.mongodb.org/osx/mongodb-osx-x86_64-3.4.2.tgz
```
3、解压
```
sudo tar -zxvf mongodb-osx-x86_64-3.4.2.tgz
```
4、重命名为 mongodb 目录
```
sudo mv mongodb-osx-x86_64-3.4.2 mongodb
```
或者可以把tgz包下载到本地，自己解压，然后拷贝到相应目录下即可

## 添加PATH路径
```
export PATH=/usr/local/mongodb/bin:$PATH
```
## 运行MongoDB
```
sudo mongod
```
### 再打开一个终端进入执行以下命令：
```
sudo mongo
```