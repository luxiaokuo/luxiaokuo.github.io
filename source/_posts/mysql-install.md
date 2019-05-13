---

title: Mysql - install 安装及基本命令

categories: mysql

date: 2018-08-10

---

**Mysql** ( _mysql -u root -p访问mysql_ )

---

**_1.下载mysql源安装包_**

`wget http://dev.mysql.com/get/mysql57-community-release-el7-11.noarch.rpm`

---

**_2.安装mysql源_**

`yum localinstall mysql57-community-release-el7-11.noarch.rpm`

---

**_3.查看是否安装成功_**

`yum repolist enabled | grep "mysql.*-community.*"`

---

**_4.这个指令可以修改安装版本(一般不用改，默认安装你的5.7)_**

`vim /etc/yum.repos.d/mysql-community.repo`

---

**_5.安装mysql_**

`yum install mysql-community-server`

---

**_6.启动MySql_**

---

**启动**

`systemctl start mysqld`

**状态**

`systemctl status mysqld`

**重启**

`/bin/systemctl restart mysqld.service`

---

**7.开机自启**

`systemctl enable mysql`

`systemctl daemon-reload`