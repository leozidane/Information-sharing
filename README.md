# Information-sharing
### 本网站是一个类似知乎的一个资讯分享和问答小网站，用户注册后可以发布资讯和发布问题，也可以评论资讯或者对资讯进行点赞
主要包括以下模块：、资讯管理模块、评论管理模块、站内信模块、异步队列模块、文件上传下载模块等。 

技术细节：

1.后台开发框架采用spring boot + mybatis + redis，前端采用thymeleaf模板进行页面开发。

2.采用mysql数据库对实体信息进行存储，redis用在缓存、点赞和排名等相关方面。 

3.使用异步队列设计来完成对站内信。

 ![image](https://github.com/leozidane/Information-sharing/blob/master/toutiao-master/detial.PNG)

 ![image](https://github.com/leozidane/Information-sharing/blob/master/toutiao-master/home.PNG)

 ![image](https://github.com/leozidane/Information-sharing/blob/master/toutiao-master/messagedetail.PNG)

 ![image](https://github.com/leozidane/Information-sharing/blob/master/toutiao-master/messagelist.PNG)
