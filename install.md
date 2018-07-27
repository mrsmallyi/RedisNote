### Linux环境安装Reids

1. 安装步骤
```
(1)下载redis指定版本的源码压缩包到当前目录
$ wget http://download.redis.io/releases/redis-3.0.6.tar.gz
(2)解压redis源码压缩包
$ tar zxf redis-3.0.6.tar.gz
(3)建立一个redis目录的软件连接，指向redis-3.0.6
$ ln -s redis-3.0.6 redis
(4)进入redis目录
$ cd redis
(5)编译
$ make
(6)安装
$ make install
```
