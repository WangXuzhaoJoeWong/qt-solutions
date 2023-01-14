# qt-solutions
使用qtwinmigrate开源库，正常情况下，qt的界面库必须是qt的主程序调用才行，但是qtwinmigrate库在内部解决了qt主程问题。我们只需要使用即可。
使用qtwinmigrate开源库
正常情况下，qt的界面库必须是qt的主程序调用才行，但是qtwinmigrate库在内部解决了qt主程问题。我们只需要使用即可.
qtwinmigrate 库的下载地址 https://github.com/qtproject/qt-solutions.git
使用步骤
新建一个C++的dll，将qtwinmigrate库的三个类(qwinhost、qmfcapp、qwinwidget三个类对应的头文件和cpp文件)文件拷贝到自己的工程目录下，并加入到工程中
在dll入口函数dllmain 中加入如下代码
————————————————
版权声明：本文为CSDN博主「揽月凡尘」的原创文章，遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/qq_33377547/article/details/106867245
