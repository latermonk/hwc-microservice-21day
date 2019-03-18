注意！
1、打卡程序已开启，务必！务必！关注好打卡程序
https://sun.sharedaka.com/v2/habit/share_h5/visit?habitId=1947718&openId=ochvq0ImvAY-hi-iFk22uUhT3yTk&code=4ef723&byUserId=ochvq0ImvAY-hi-iFk22uUhT3yTk 
请按示例截图打卡，截图错误的可自行删除重新打卡；

2、技术问题请咨询@遥海时、@Dean、@李勇军
活动流程问题请咨询@9号助手或@应用服务小助手

-----------------------------

Day2 微服务入门之编写HelloWorld

课程资料下载【课堂入口】
https://education.huaweicloud.com:8443/courses/course-v1:HuaweiX+CBUCNXP012+Self-paced/courseware/da725ede26794694a621b8088a858743/d253080c3939499f8be47300655da3af/

【实践练习】
1、在provider服务中增加一个greeting方法，接受POST请求，请求参数为requestbody中传递的Person对象，包含name和gender两个字段。name为String类型；gender为枚举Gender类型，有MALE/FEMALE两个值。返回值为GreetingResponse类型，包含msg和timestamp两个字段，msg为根据gender不同生成的问候语Hello, Mr.xxx (MALE)/ Hello, Ms.xxx (FEMALE)，timestamp为java.util.Date类型的时间戳。

2、在consumer服务中增加一个greeting方法，接收外部请求的触发，以调用provider服务的greeting方法，并返回provider的应答消息。

【打卡任务】
1、调用provider服务的greeting方法成功，并截图
2、调用consumer服务的greeting方法成功，并截图
