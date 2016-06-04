#Cmder

###启动Cmder
1. 将Cmder添加至环境变量
2. 将Cmder添加至右键菜单，以管理员权限的终端执行以下语句即可：

        Cmder.exe /REGISTER ALL

###Aliases
Cmder目录下的config文件夹，里面的aliases文件

    ls=ls --show-control-chars --color=auto $*
    clear=cls

###快捷键
>Ctrl + `：全局快捷键，从任务栏唤起  
>Ctrl + number：切换tab显示  
>Ctrl + Alt + left/right: 切换tab位置  
>Win + Alt + p：偏好设置 ( 或者在标题栏鼠标右击 )  
>Ctrl + t: 新建tab ( 可以设置管理员账号运行)  
>Ctrl + w: 关闭当前tab  
>Alt+F4：关闭所有窗口  
>Shift + Alt + number: 快速新建tab  
>Alt + Enter：全屏
>Ctr +r：历史命令搜索  

###Chocolatey软件包管理
1. 安装Chocolatey，运行如下命令：  

        @powershell -NoProfile -ExecutionPolicy unrestricted -Command "iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin

2. 安装软件  

        命令：choco install softwareName, 短写是 cinst softwareName
    可安装的应用程序，参见其[package](https://chocolatey.org/packages)列表
