## db.properties

```
引起乱码写法，在5.7数据库时正常，但在5.5版本库中中文乱码,&amp;转义符问题
jdbc.url=jdbc:mysql://172.16.200.200:3306/manageplat?useUnicode=true&amp;characterEncoding=utf-8  

正确写法
jdbc.url=jdbc:mysql://172.16.200.200:3306/manageplat?useUnicode=true&characterEncoding=utf-8
```



