# heritrix
heritrix 爬虫的简单学习，就是一些基本的配置，并没有太大的深入，过几天，再深入点 


## 配置Heritrix
这个东西虽说是配置 很简单的，但是有时候老是出现一些莫名其妙的错误，我们可以参考

这个地址的文章去慢慢的自己搭建，我这个是已经做好的项目
https://www.ibm.com/developerworks/cn/opensource/os-cn-heritrix/


##扩展Heritrix

###URL的过滤操作
可以参考这个，通过复写org.archive.crawler.postprocessor.FrontierScheduler 类中的schedule 的方法来完成url的过滤
http://blog.csdn.net/waltertan1988/article/details/45290741

###内容的处理
这个是将我们的数据都处理到数据库中，设定获取页面的解析工作
http://www.chepoo.com/heritrix3-crawled-data-is-written-directly-to-the-mysql.html
