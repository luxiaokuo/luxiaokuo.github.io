---

title: Thinkphp - URl访问地址

categories: thinkphp

date: 2017-02-09

---

访问地址

---

**1.** _基本get模式_

`http://网址/index.php?m=XX &c=XX &a=XX`

---

**2.** _路径模式pathinfo_

`http://网址/index.php/模块/控制器/操作方法`

---

**3.** _rewrite重写模式_

`http://网址/模块/控制器/操作方法`

---

**4.** _兼容模式_

`http://网址/index.php?s=/模块/控制器/方法`

---


具体url地址模式设置(thinkPHP/conf/convertion.php)

---

**url_model = 0/1/2/3** 分别代表4种url地址模式

---

thinkphp_3.2.3_full\Application\Common\Conf\conf.php

---

我们当前自己项目的配置文件

---

修改conf.php增加配置以后 会把convertion.php里的值覆盖掉

---

修改url默认怎么修改

---

在 **_ThinkPHP/Conf/concention.php_** 配置文件中

---

**46**-**48**行

---

默认模块

`'DEFAULT_MODULE'        =>  'Home',`

---


默认控制器名称

`'DEFAULT_CONTROLLER'    =>  'Index',`

---

默认操作名称

`'DEFAULT_ACTION'        =>  'index',`

---

修改后 **默认模块** 和 **控制器** 和 **操作名称** 就会被更改