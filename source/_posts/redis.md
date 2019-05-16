---

title: PHP - Redis 安装及扩展安装

categories: redis

date: 2017-03-01

---

文章参考:


https://blog.csdn.net/sinat_15955423/article/details/78920489

---

https://blog.csdn.net/leesin2011/article/details/72801629

---

https://www.cnblogs.com/hopelooking/p/6441008.html

---

https://pecl.php.net/package/redis

---

步骤操作:

---

1.[点我进入下载](https://github.com/MSOpenTech/redis/releases) redis-x 64-3.2.100.zip

---

2.解压到redis目录

---

3.cmd 进入redis 目录

---

4.使用命令 **启动后勿关闭cmd**

`redis-server  redis.windows.conf `

---

5.cmd 再次进入redis目录

---

6.使用命令

```
set name abc

get name

```

---

7.安装redis 扩展 [点我下载](https://pecl.php.net/package/redis) DLL下载对应版本 Non Thread Safe(NTS) x64

---

8.找到php版本目录 找到ext 把扩展中 **php_redis.dll**  和  **php_redis.pdb** 放入

---

9.修改php.ini

`extension=php_redis.dll`

重启服务

---

10.localhost/phpinfo.php

---

11.Redis启动命令  进入redis目录

---

开启redis

`redis-server --service-start  `

---

关闭redis

`redis-server --service-stop  `

---

12.开机自动启动redis

`redis-server --service-install redis.windows.conf  `

---

可以在计算机管理 服务中查看

![](https://i.loli.net/2019/05/17/5cddad058872d75680.png)