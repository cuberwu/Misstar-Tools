工具箱安装：说了这么多，这个工具箱到底怎么安装？其实很简单，

首先确定你的路由器是R1D,R2D,R3,mini,R3P,R3D这几个的其中一个

其次你需要刷开发版并且开启SSH，SSH的开启和使用论坛已经有太多相关帖子，这里就不多说了！附上官方SSH链接https://d.miwifi.com/rom/ssh （注意，开启SSH意味着放弃保修）

最后用软件登上SSH（putty xshell bash等随便啦）输入下面这一段安装命令，按照说明操作即可，整个过程不用1分钟。安装完直接登录后台管理页面就可以看到MT工具箱了，然后之后就不用ssh工具了！

安装命令如下：
wget https://github.com/cuberwu/Misstar-Tools/raw/master/install.sh -O /tmp/install.sh && chmod +x /tmp/install.sh && /tmp/install.sh

(注意:此插件仅适用于R1D,R2D,R3)
