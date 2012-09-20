WebTiled
========

Web地图编辑器
-------------

HTML5 Canvas实现的网页版地图编辑器。

基本功能
--------

* 导入导出当前工程，及保存成json地图或图片。
* 图层分图块层、框域层两种。前者绘图块、后者绘区域。
* 工具栏主要提供图块层印刻、填充、连接三种绘制方式。
* 添加图块，可以将多个图片一起拖进图块显示域来添加。
* 导入工程文件也可拖进地图显示域，不过只会读取其中一个。
* 应用在本地即可跑，即file://路径。也没放服务器上试呢。

注意项
------

* 应用只在Chrome20+上跑过...
* 地图与选取的图块宽高不一致时，未多考虑。
* 图层建太大或过多，会有黑图层或直接崩溃T^T。
注：具体限制好像与PC性能相关。

第三方
------

* [jQuery](http://jquery.com/)
* [Bootstrap](http://twitter.github.com/bootstrap/)
* [工具栏图标](http://www.defaulticon.com/)

预览
----

[Click here!](http://join-wt.jit.su/)
