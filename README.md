﻿###暂不支持

不支持for in循环

不支持is和as关键字

不支持delete关键字

不支持undefined关键字

不支持case后用引用（只能是数字或者字符串）

不支持默认参数

不支持Vector类型

不支持重写get/set

不支持use namespace关键字

支持顺序按优先级来

----------------------------------------------------------------------------------------------------------------------

###注意事项

int、Number、Boolean默认值是null

js对象的方法都用了 bind(this) 来绑定上下文

api命名比较乱，因为是用本人另一个C#版本的as3解释器的核心库翻译过来的，C#版本支持运行as3代码，不支持导出js，地址：http://git.oschina.net/jianyumofa/ActionScriptForUnity/

暂时不支持runtime，不能运行时解释as3代码，后续会支持

此库是as3版本，可以利用此库编译成js版本

暂时只支持导出js，后续会支持ts、c#、java

最终是as3可以导出大部分语言、也可以直接运行在cocos、unity3d、egret等引擎上

生成的js文件需要先导入how.js库才能运行

可以调用任何H5引擎的api

----------------------------------------------------------------------------------------------------------------------

附：ActionScriptForUnity地址：http://git.oschina.net/jianyumofa/ActionScriptForUnity/