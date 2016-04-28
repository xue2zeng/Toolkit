# NPM
> * 访问官网下载NodeJS源码进行安装
>
>         [root@localhost ~]# cd $NODEJS_PATH/.configure
>         [root@localhost ~]# make
>         [root@localhost ~]# make install
>
> * 升级NPM管理包
>
>         npm -g install npm

#### NRM：快速切换NPM源
>     [root@localhost ~]# npm install -g nrm
> 参考 [NRM](https://github.com/Pana/nrm) 的Github

#### NVM：版本管理器
> 参考 [NVM](https://github.com/creationix/nvm) 的Github
>
> nvm默认从[http://nodejs.org/dist](http://nodejs.org/dist)下载，国外服务器非常慢，推荐从taobao的node dist镜像下载：
> 
>     [root@localhost ~]# NVM_NODEJS_ORG_MIRROR=https://npm.taobao.org/mirrors/node nvm install 6
>
> 避免每次输入环境变量NVM_NODEJS_ORG_MIRROR，建议加入到.bashrc文件中：
> 
>     # nvm
>     export NVM_NODEJS_ORG_MIRROR=https://npm.taobao.org/mirrors/node
>     source ~/git/nvm/nvm.sh
