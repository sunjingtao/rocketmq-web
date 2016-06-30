1，必须使用jdk 1.6.038及以上版本，jdk1.7未测试过，建议先用jdk1.6系列的
2，tomcat 使用　apache-tomcat-7.0.50
3，将　D:\消息中间件\RocketMQ\rocketmq-console-master控制台\rocketmq-console-master\target\rocketmq-console-SNAPSHOT-1.0.war　包放到tomcat下的webapp文件夹下，启动tomcat后，自解压安装
4，将tomcat下自安装好的　webapps\rocketmq-console-SNAPSHOT-1.0\WEB-INF下的　index.html文件，放到上一级目录中
5，修改\WEB-INF\classes\config.properties文件，设置好对应的nameserver地址
			rocketmq.namesrv.addr=192.168.44.129:9876
6，修改\WEB-INF\classes\log4j.properties  设置日志路径：
		log4j.appender.file.File=D:\log\rocketmq\rocketmq-console.log
7, 启动tomcat,浏览器登录　http://localhost:8080/rocketmq-console-SNAPSHOT-1.0/index.html　则登录上控制台。