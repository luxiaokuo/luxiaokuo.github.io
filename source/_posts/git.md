---

title: Git - Windows安装及基本命令

categories: git

date: 2018-07-22

---

_**git官网**_

_https://git-scm.com/downloads_

---

_**国内镜像**_

_https://pan.baidu.com/s/1kU5OCOB#list/path=%2Fpub%2Fgit_

---

_**分布式版本控制系统**_


--->   **默认选项安装** 即可。

---

_**安装完成后**_


找到 git -> git bash

---

_**输入命令**_

`$ git config --global user.name="Your Name"`

`$ git config --global user.email="email@example.com"`

---

_**创建版本库**_

---

_**创建repository**_

`$ mkdir repository`

---

_**切换到repository**_

`$ cd repository`

---

_**显示当前路径**_

`$ pwd`

---

_**变成Git可以管理的仓库**_

`$ git init`

---

**_添加文件**_

`$ git add filename`

---

_**提交文件  commit可以一次提交很多文件**_

`$ git commit -m "luxiaokuo"`

---

_**提交记录**_

`$ git log`

---

_**更清晰展现提交记录**_

`$ git log --pretty=oneline`

---

_**查看文件**_

`$ cat filename`

---

HEAD表示当前版本上一个版本就是HEAD^，上上一个版本就是HEAD^^，当然往上100个版本写100个^比较容易数不过来，所以写成HEAD~100。

回退上1版本

`$ git --hard HEAD^`

_**原版号**_

`$ git reset --hard`

---

_**关闭终端之后没有版本号的话**_

---

_**可查看所有命令记录**_

`$ git reflog`


