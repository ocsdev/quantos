
# Welcome
欢迎使用quantOS。

# Introduction
本是一个开源的量化研究平台，旨在为用户提供全链路的量化研究解决方案，在这里，你将可以完成：

- 使用数据API，轻松获取研究数据
- 使用信号研究工具，进行交易信号的快速定义、研究、回测
- 根据策略模板，编写自己的量化策略
- 使用回测框架，对策略进行回测和验证

未来，我们还计划推出在线验证环境，进行策略仿真交易。


# Dependencies

	Python = 2.7 or 3+
	pandas >= 1.8
	

# Installation

目前可以在如下操作系统上安装

-  GNU/Linux 64-bit
-  Windows 64-bit
-  Mac OS

安装方式主要有以下几种：

1、使用``pip``进行安装
-----------------------
    $ pip install quantos

2、通过源代码安装
--------
clone quantOS的源代码，进入到源文件目录，执行安装命令：
	
	$ python setup.py install
或者通过pypi地址https://pypi.python.org/quantOS-Org/quantos/下载,并执行上面安装命令。

3、代码升级
--------

	$ python install quantos --upgrade

# Quickstart

参见 [user guide](doc/user_guide.md "user guide")


更多的示例保存在 ``quantos/examples`` 

Questions?
==========

如果您发现任何问题，请到[这里](https://github.com/quantOSorg/quantos/issues/new)提交。


Change Logs
=========

0.2.0 2017/10/16
----
1、发布第一个版本

