# iojs
## 下载
https://iojs.org/dist/v1.6.3/iojs-v1.6.3-linux-x64.tar.xz

### 解压
````
tar xf archive.tar.xz
tar xf archive.tar.gz
tar xf archive.tar
````

### 改名
mv iojs-v1.6.3-linux-x64 iojs

### 设置环境变量
1. 当前session 
````
EXPORT IO_JS=<PATH to iojs>
EXPORT PATH=$PATH:$IO_JS/bin
````
2. 在profile中设置PATH
````
sudo vim /etc/profile
EXPORT IO_JS=<PATH to iojs>
EXPORT PATH=$PATH:$IO_JS/bin
````
3. 在当前用户的profile中设置PATH
````
vim ~/.bash_profile
````
4. 刷新bash
````
source ~/.bash_profile
or
. ~/.bash_profile
````

### 新加用户
``
sudo adduser <username> sudo
``
### 或者给已有用户增加sudo权限
``
sudo usermod -a -G sudo <username>
``

### 切换用
``
su <username>
``

