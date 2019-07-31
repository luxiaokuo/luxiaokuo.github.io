---

title: PHP - 实时输出内容

categories: php

date: 2016-09-11

---

```PHP
for ($i=0; $i < 10 ; $i++) {
    echo $i;
    echo str_repeat ( " " , 1024 ) ;
    ob_flush ( ) ;
    flush ( ) ;
    sleep(1);
}


ob_end_clean();
ob_implicit_flush(1);
for ($i=0; $i < 10 ; $i++) {
    echo $i;
    //浏览器需要凑够一定的字节数才会输出
    echo str_repeat ( " " , 1024 ) ;
    sleep(1);
}
```

