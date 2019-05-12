---

title: Vim - 编辑器安装

---

**_Centos_** 默认安装了Vim

---

但**_Vim_** 编辑器是没安装或者未完全安装的

---

**检测是否已经安装过Vim**：

---

`$ rpm -qa|grep vim`


![想输入的提示名字，可不输入](https://i.loli.net/2019/05/11/5cd6c5118f758.png)

---

若是**缺少Vim**包名：则使用命令： 

---

比如说： ***vim-enhanced*** 这个包少了

---

执行：

`$ yum -y install vim-enhanced`

会自动下载安装。

---

下载完成进行安装： 

`$ yum -y install vim*`