###Fedora安装后优化配置
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
