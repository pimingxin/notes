<!-- 
**这是加粗的文字**
*这是倾斜的文字*`
***这是斜体加粗的文字***
~~这是加删除线的文字~~

>这是引用的内容
>>这是引用的内容
>>>这是引用的内容

分割线
---
***

```
  代码内容
```
超链接
[百度](http://baidu.com)

-->


# about vue

**vue中vdom渲染页面的过程：将<template>模板，通过render渲染函数（createElement()）得到虚拟的DOM树，通过diff算法进行新旧虚拟节点的比较，再通过patch更新到真实的dom上实现视图的更新。**


AST抽象语法树

VDOM

通过模拟JS转化成真实的DOM 

将真实DOM 转成vnode diff 比较变化 patch 将变化用打补丁的方式更新到真实DOM上

为什么要使用？ DOM 浪费性能 重排 重绘

