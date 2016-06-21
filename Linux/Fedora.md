###Fedaora升级
1. 升级软件

        sudo dnf upgrade

2. 安装dnf插件

        sudo dnf install dnf-plugin-system-upgrade

3. 升级到指定版本

        sudo dnf system-upgrade download --releasever=23 --best //–best：表示如果有依赖问题解决不了，那么取消这次升级。
        sudo dnf system-upgrade download --releasever=23 --allowerasing

4. 重启系统

        sudo dnf system-upgrade reboot

###Fedora安装后优化配置
添加中文社区源

    dnf config-manager --add-repo=http://repo.fdzh.org/FZUG/FZUG.repo

1. 配置RPMFusion仓库

    >     sudo rpm -Uvh http://download1.rpmfusion.org/free/fedora/rpmfusion-free-release-stable.noarch.rpm
    >     sudo rpm -Uvh http://download1.rpmfusion.org/nonfree/fedora/rpmfusion-nonfree-release-stable.noarch.rpm

2. 安装Gnome调整工具

    >     sudo dnf install gnome-tweak-tool

3. 安装鼠标右键"在终端中打开"

    >     sudo dnf install nautilus-open-terminal

4. yum图形界面工具

    >     sudo dnf install yumex
    >     sudo dnf install yumex-dnf

5. 安装Guake多命令行终端

    >     sudo dnf install guake
