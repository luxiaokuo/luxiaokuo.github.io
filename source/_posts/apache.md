---

title: Apache 基本命令

categories: apache

---

**_基本操作 ( 不定时更新 )_**

---

**安装**: 

`yum install httpd httpd-devel`

---

**状态**: 

`systemctl status httpd.service`

---

**停止**: 

`systemctl stop httpd.service`

---

**启动**: 

`systemctl start httpd.service`

---

**开启启动**: 

`systemctl enable httpd.service`

---

**重启**: 

`systemctl restart httpd.service`

---

**开机不启动**: 

`systemctl disable httpd.service`