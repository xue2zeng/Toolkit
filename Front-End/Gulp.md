#Gulp

Gulp和所有插件都通过JavaScript编写并依托Node.js平台

下载NodeJS源码进行源码安装

    [root@localhost ~]# cd $NODEJS_PATH/.configure
    [root@localhost ~]# make
    [root@localhost ~]# make install

升级NPM管理包

    [root@localhost ~]# npm -g install npm

安装gulp

    [root@localhost ~]# npm install --global gulp
    [root@localhost ~]# sudo chown -R $USER /usr/local


使用gulp-ruby-sass插件,需要用到ruby，所以需要先安装ruby环境

    [root@localhost ~]# dnf install ruby
    [root@localhost ~]# gem install sass //通过ruby的gem安装sass

如果出现如下图所示：则说明被国内防火墙拦截。解决办法：将gem的镜像更换成淘宝的镜像

    删除gem原镜像：命令提示符输入：gem source -remove https://rubygems.org/
    添加淘宝镜像：命令提示符输入：gem source -a https://ruby.taobao.org/
    查看gem镜像，确保只有ruby.taobao.org，命令提示符输入：gem sources -l
    重新安装sass，命令提示符输入：sudo gem install sass
