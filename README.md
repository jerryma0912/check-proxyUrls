URL Check Übersicht Widget
==========================
本插件利用[Ubersicht](http://tracesof.net/uebersicht/)软件，并在[check-urls.widget](http://tracesof.net/uebersicht-widgets/#check-urls)插件基础上进行修改，完成了一款用于mac端的，检测系统代理是否正常、并将结果显示于桌面上的插件。

基本原理
-------
通过bash脚本，向url发起请求，如果返回`200`,则认定连通。

环境要求
-------
1. 安装ubersicht软件
2. 安装代理软件

示例
-------
![Example!](screenshot.png)
To enable, place the `check-urls.widget` folder in your `Übersicht/widgets` directory.

Usage
-----
Just edit the file `test.list` and put in the urls you want to monitor.