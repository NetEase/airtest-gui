airtest-gui
==================

This is a PyQt GUI for [airtest](http://git.mt.nie.netease.com/hzsunshx/airtest).

## 安装
首先需要安装pyqt。[点击下载](ftp://mt.nie.netease.com/airtest-gui/PyQt4-4.10.4-gpl-Py2.7-Qt4.8.6-x32.exe)

该pyqt依赖python2.7-32位版。并确保airtest已经安装。

## 使用
双击`start.bat`启动gui程序。

启动后的页面如下.

1. 需要选择连接设备的类型 <android|windows|ios>
2. 之后选择设备编号。 点击connect。 如果正常的话，下面的日志会出现连接成功的提示
3. 点击refresh可以将设备上的图像刷新到gui上。
4. 点击图像，就可以获取点击的坐标。
5. 在图形上拖拽，变可以截图。左键拖拽和右键拖拽分别会截取到不同的截图栏中。

右侧是代码生成框，列出了自动生成的命令。

![airtest-gui](http://doc.mt.nie.netease.com/lib/exe/fetch.php?cache=&media=pasted:20140827-111211.png)
