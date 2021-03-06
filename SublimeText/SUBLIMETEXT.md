#Sublime Text
###个人偏好设置
```JSON
  "theme": "Seti_orig.sublime-theme", //使用Seti_UI主题
  "font_size": 10, // 设置字体大小：12
  "draw_white_space": "all", // 显示Tab,空格等空白字符
  "rulers": [80,100], // 行宽标尺
  "smart_indent": true,
  "tab_size": 2, // 设置tab键缩进为：2
  "translate_tabs_to_spaces": true, // 使用空格代替tab
  "trim_automatic_white_space": true, // 保存时自动去除行末空白
  "ensure_newline_at_eof_on_save": true, // 保存时自动增加文件末尾换行
  "caret_style": "phase", // 使光标闪动更加柔和
  "highlight_line": true, // 高亮当前行
  "highlight_modified_tabs": true, // 高亮有修改的标签
  "save_on_focus_lost": true, // 失去焦点自动保存
  "show_encoding": true // 显示当前文件编码
```

###插件

* #####Side​Bar​Enhancements

  >     增强文件夹中文件右键选项操作
  > 使用Seti_UI主题，左侧边栏默认为灰白色。
  >
  > 1.使其更加美观需要修改C:\Users\XXX\AppData\Roaming\Sublime Text 3\Packages\User\Default.sublime-theme文件，编辑如下四项：
  >
  > * "class": "sidebar_container" // 侧边栏与主文件区分割线内颜色
  > * "class": "sidebar_tree" // 侧边栏文件夹树形菜单背景色
  > * "class": "sidebar_label" // 侧边栏目录名以及文件名颜色
  > * "class": "sidebar_heading"
  >
  > __备注：__
  > 参考 [@stackoverflow](http://stackoverflow.com/questions/13580561/sublime-text-2-change-side-bar-color)
  > ，或[@个人设置](https://github.com/xue2zeng/Toolkit/blob/master/SublimeText/Default.sublime-theme)
  >
  > 2.使用[@SyncedSideBar](https://packagecontrol.io/packages/SyncedSideBar)插件

* #####AdvancedNewFile

  >     用于增强创建文件操作
  > 参考[@AdvancedNewFile](https://packagecontrol.io/packages/AdvancedNewFile)
  >
  > ######快捷键
  >
  >     Windows：ctrl+alt+n
  >     OS X and Linux：super+alt+n



###Fedora安装Sublime Text
```
[root@localhost ~]# wget https://gist.githubusercontent.com/simonewebdesign/8507139/raw/e1e7f6a302d44902dc0805eaf85344f1c4e84425/install_sublime_text.sh
[root@localhost ~]# chmod 774 install_sublime_text.sh
[root@localhost ~]# ./install_sublime_text.sh
```
参考[@simonewebdesign][1]
  [1]:https://gist.github.com/simonewebdesign/8507139 "@simonewebdesign"


