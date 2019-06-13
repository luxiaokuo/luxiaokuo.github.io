---
title: laravel 自定义公共函数

categories: laravel

date: 2018-08-09
---

**1. 在app目录下建立Helpers文件夹**

`mkdir Helpers`

------

**2. Helpers文件夹下建立functions.php文件**

`touch function.php`

------

**3. 在根目录composer.json中修改autoload加入以下代码**

```php
"files": [
    "app/Helpers/functions.php"
]
```

------

**效果如下**：

![想输入的提示名字，可不输入](https://i.loli.net/2019/06/13/5d01bc641508157240.png)

------

**4. 执行`composer`命令让其自动加载**

`composer dump-auto`

------

**效果如下：**

![](https://i.loli.net/2019/06/13/5d01be589a06172766.png)

