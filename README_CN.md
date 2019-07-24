Proxy Check Übersicht Widget
==========================

简介
-------
1. 本插件是一款用于mac端的、检测系统代理是否正常、并将结果显示于桌面上的软件。
2. 本插件在[check-urls.widget](http://tracesof.net/uebersicht-widgets/#check-urls)插件的基础上进行修改.
3. 本插件的使用需要安装[Ubersicht](http://tracesof.net/uebersicht/)软件。

检测原理
-------
通过bash脚本，向url发起请求，如果返回`200`,则认定连通。

环境要求
-------
1. 安装ubersicht软件
2. 安装代理软件(ssr,easyConnect...)

安装方式
-------
1. 打开Ubersicht Widget文件夹
2. 在该目录下新建文件夹`check-urls.widget`
3. `git clone`本仓库，并将代码移动至上述文件夹中

如何使用
-------
- 将需要在`本地网络`环境下检测的网址添加至`locallist.list`文件中。
- 将需要在`代理网络`环境下检测的网址添加至`proxylist.list`文件中。

示例
-------
![Example!](screenshot.png)

English manual please click [here](./README.md).