io.netty.util.concurrent 包下的事件调度
![图片来自互联网][1]
[1]: http://www.myexception.cn/img/2013/10/29/1041373.jpg

 1. 顶部五个接口来自JDK，但是5.x中 EventExecutorGroup没有再继承Iterable了（更精简的next()和children()方法来访问集合）。
