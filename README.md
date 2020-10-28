# PyMiner 开发者指南

### 概述

官方网站：[www.py2cn.com](http://py2cn.com/)

PyMiner是一个开源的数据处理、分析、建模、评估软件.

### 技术说明：

PyMiner项目开发环境基于Window 10 X64，使用Python3.8+PyQt5.15+Pycharm进行技术开发， 同时，此项目支持跨平台，这意味着即使是Linux、Mac也可以直接使用或开发此软件！

### 如何安装：

1.  下载项目源码.
2.  安装python并打开命令行工具，使用 pip install -r requirements.txt 导入python包，如果你的python依赖包下载太慢，我建议使用：pip install -i [https://mirrors.cloud.tencent.com/pypi/simple](https://mirrors.cloud.tencent.com/pypi/simple) -r requirements.txt
3.  调用python 执行目录下pyminer.py，例如python安装在C盘根目录下，可以在cmd命令行中执行：C:\python\python.exe C:\PyMiner\pyminer.py
4.  此外，你也可以使用pyinstaller进行编译后使用，编译语句：pyinstaller -i logo.ico -w pyminer.py