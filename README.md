airtest-gui 注：已经不再维护
==================

This is a PyQt GUI for [airtest](http://git.mt.nie.netease.com/hzsunshx/airtest).

## 安装
首先需要安装pyqt。[点击下载](ftp://mt.nie.netease.com/airtest-gui/PyQt4-4.10.4-gpl-Py2.7-Qt4.8.6-x32.exe)

该pyqt依赖python2.7-32位版。并确保airtest已经安装。

[点击下载gui代码](http://git.mt.nie.netease.com/hzsunshx/airtest-gui/archive/master.zip)
解压后，双击`start.bat`启动gui程序。

## 使用
启动后的页面如下.
![airtest-gui](http://doc.mt.nie.netease.com/lib/exe/fetch.php?cache=&media=pasted:20140827-111211.png)

### 步骤
1. 需要选择连接设备的类型 <android|windows|ios>
2. 之后选择设备编号。 点击connect。 如果正常的话，下面的日志会出现连接成功的提示
3. 点击refresh可以将设备上的图像刷新到gui上。
4. 单击图像，会生成点击坐标位置的命令。
5. 在图形上拖拽，便可以截图，保存到相应的文件夹下。并且文本框里会填充点击截图的指令。

右侧比较大的那部分，`Commands Generated`是命令生成框。可以直接编辑。

* 点击运行代码按钮后，命令会直接附加到命令生成框里去。![commands-generated](http://doc.mt.nie.netease.com/lib/exe/fetch.php?cache=&media=pasted:20140827-130015.png)
* 右侧是代码生成框，列出了自动生成的命令。

左键拖拽和右键拖拽分别会截取到不同的截图栏中。右键拖拽截图的方式主要是用于生成drag命令。
![截图](http://doc.mt.nie.netease.com/lib/exe/fetch.php?cache=&media=pasted:20140827-130346.png)


