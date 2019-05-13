---

title: Xampp - Linux install 安装及基本命令

categories: xampp

---

**安装**

---

**_1、切换到home目录 也可以是别的目录_**

`# cd /home/`

---


**_2、下载文件_**

`# sudo wget https://www.apachefriends.org/xampp-files/5.6.31/xampp-linux-x64-5.6.31-0-installer.run`

---


**_3、设置权限_**

`# chmod 777 xampp-linux-x64-5.6.31-0-installer.run`

---

**_4、运行文件_**

`./xampp-linux-x64-5.6.31-0-installer.run`

---

_运行成功会提示选择一些选项 一路Y即可_

---

**_修改hosts域名解析_**

`vim /etc/hosts`

---

**_重启xampp:_**

`/opt/lampp/./lampp restart`

---


**_启动xampp：_**

`/opt/lampp/./lampp start`

---


**_停止xampp：_**

`/opt/lampp/./lampp stop`

---


**_卸载xampp：_**

`rm -rf /opt/lampp`

---


**_停止xampp：_**

`/opt/lampp/./lampp stop`