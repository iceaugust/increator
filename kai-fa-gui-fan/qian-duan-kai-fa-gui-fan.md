# 开发页面务必要看

## 1、bootstrap开发规范

[http://codeguide.bootcss.com/\#html-syntax](http://codeguide.bootcss.com/#html-syntax)

## 2、font字体库用法

### 2.1 字体库网站

[www.iconfont.cn](/www.iconfont.com)

![](/assets/01.png)  
![](/assets/02.png)  
![](/assets/03.png)  
![](/assets/04.png)

### 2.2  FontIconCreator

这个工具类用来生成已有css图标样式文件，但又缺少demo直接图，可以用这个工具生成一个html预览页，详见下图所示。

![](/assets/FontIconCreator.png)

### 2.1 自定义图标改造

除了框架自带的图标外，可以按照需要加入自定义图标，**但必须按照规范操作**，否则图标会越来越多，越来越乱。

自定义图标目录：![](/assets/font_increator_dir.png)

操作方法如下：

* 在图标库[http://www.iconfont.cn/](http://www.iconfont.cn/)   上注册账号，并创建项目，同一个项目用一个账号，可以用于后期想增加图标时以免覆盖原来已经在使用的图标。
* 将需要的图标加入购物车，再从购物车中批量加入项目，再从项目中批量下载。
* 下截完后的压缩包中包含css、字体文件、demo等文件，先对字体文件进行更名为“font-increator”，然后对css文件顶部几行引用文件名的地方相应的进行修改即可。

![](/assets/myproject.png)![](/assets/myproject_edit.png)

![](/assets/fontcss.png)

