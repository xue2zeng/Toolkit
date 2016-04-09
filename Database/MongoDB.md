###安装
* ####Linux(Fedora)

    1 配置MongoDB系统管理仓库文件

          [root@localhost ~]# touch /etc/yum.repos.d/mongodb-org.repo
    2 添加配置内容

          [mongodb-org-$version]
          name=MongoDB Repository
          baseurl=https://repo.mongodb.org/yum/redhat/$releasever/mongodb-org/$version/x86_64/
          gpgcheck=1
          enabled=1
          gpgkey=https://www.mongodb.org/static/pgp/server-$version.asc


          备注：
              $releasever：服务器版本号
              $version：mongodb版本号

    3 安装MongoDB

          [root@localhost ~]# sudo dnf -y install mongodb-org

    4 重启MongoDB

          [root@localhost ~]# systemctl restart mongod.service

    5 进入MongoDB
    
          [root@localhost ~]# mongo
