# Information-sharing
### 本网站是一个类似知乎的一个资讯分享和问答小网站，用户注册后可以发布资讯和发布问题，也可以评论资讯或者对资讯进行点赞
主要包括以下模块：、资讯管理模块、评论管理模块、站内信模块、异步队列模块、文件上传下载模块等。 

技术细节：

1.后台开发框架采用spring boot + mybatis + redis，前端采用thymeleaf模板进行页面开发。

2.采用mysql数据库对实体信息进行存储，redis用在缓存、点赞和排名等相关方面。 

3.使用异步队列设计来完成对站内信、登录异常、关注问题等事件的处理，提升系统的用户交互体验，采用邮件发送技术对用户关心的资讯或问题进行邮件通知。

4.采用七牛云对象存储，通过提供的SDK进行对资讯中的图片、用户分享的文件进行云上传、下载。
(https://github.com/leozidane/Information-sharing/blob/master/toutiao-master/detial.PNG)

(https://github.com/leozidane/Information-sharing/blob/master/toutiao-master/home.PNG)

(https://github.com/leozidane/Information-sharing/blob/master/toutiao-master/messagedetail.PNG)

(https://github.com/leozidane/Information-sharing/blob/master/toutiao-master/messagelist.PNG)
