---

title: Firewall 基本命令

categories: firewall

---

**查看运行状态**


`firewall-cmd --state`

---

**启动服务**

`systemctl start firewalld`

---

**设为开机启动**

`systemctl enable firewalld`

---


**查看是否启动成功**

`systemctl status firewalld`

---


**重启**

`firewall-cmd --reload`

---

**查看所有端口**

`firewall-cmd --list-ports`

---


**开启80端口**

`firewall-cmd --zone=public --add-port=80/tcp --permanent`

---


**开启3306**

`firewall-cmd --zone=public --add-port=3306/tcp --permanent`