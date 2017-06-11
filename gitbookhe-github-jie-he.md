github引入的原因说明：

本来是使用公司的svn版本管理进行手册版本管理的，但最后发现git和svn还是存在冲突，没找到共存的方案，因此转到github上。

gitbook官网：[www.gitbook.com](/www.gitbook.com)

github官网：[https://github.com/](https://github.com/)

github仓库地址：[https://github.com/iceaugust/increator.git](https://github.com/iceaugust/increator.git)

使用方法：

1、注册github账号，并在gitbook中使用此账号登录，不登录也可，但在同步项目时还是会提示登录。

2、在gitbook中选择工作区，比如e:\gitbook\_work，并创建新book，待生成一个新手册。![](/assets/import.png)

3、gitbook中设置仓库目录，为上面指定的仓库目录，确定。再点pull（相当于check out）表示从仓库中获取项目文件，及开发手册源文件，等待同步完成即可。这中间可能会提示输入github账号密码。

4、日常编辑修改，保存完本地文件后，会在右上角显示待同步的文件数量，如下图所示，需要上传到github仓库时，点击这个按钮即相当于check in或commit的操作。

