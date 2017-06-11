# github引入的原因说明：

本来是使用公司的svn版本管理进行手册版本管理的，但最后发现git和svn还是存在冲突，没找到共存的方案，因此转到github上。

gitbook官网：[www.gitbook.com](/www.gitbook.com)

github官网：[https://github.com/](https://github.com/)

github仓库地址：[https://github.com/iceaugust/increator.git](https://github.com/iceaugust/increator.git)

# 使用方法：

* 1、注册github账号，并在gitbook中使用此账号登录，不登录也可，但在同步项目时还是会提示登录。
* 2、在gitbook中选择工作区，比如e:\gitbook\_work，并创建新book，待生成一个新手册。![](/assets/import.png)

* 3、gitbook中设置仓库目录，为上面指定的仓库目录，确定。再点pull（相当于check out）表示从仓库中获取项目文件，及开发手册源文件，等待同步完成即可。这中间可能会提示输入github账号密码。

* 4、日常编辑修改，保存完本地文件后，会在右上角显示待同步的文件数量，如下图所示，需要上传到github仓库时，点击这个按钮即相当于check in或commit的操作，应该也是等同于菜单中的“push”。

![](/assets/push.png)

# 在线编辑gitbook

编辑gitbook除了本地客户端安装gitbook外，也可以直接在浏览器中使用。

使用gitgub账号，直接访问官网：ww.gitbook.com。

将账号与仓库进行绑定，已验证，多个账号都可以在gitbook上与同一个仓库地址绑定。

![](/assets/creatbook_fromgit.png)

# 发布gitbook

发布手册有两种方式

方式一：使用离线工具发布成本地的html的web目录手册。



方式二：全用在线的发布功能，发布，详见下图：

![](/assets/publish2.png)![](/assets/publish3.png)

