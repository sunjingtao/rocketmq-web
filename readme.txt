1������ʹ��jdk 1.6.038�����ϰ汾��jdk1.7δ���Թ�����������jdk1.6ϵ�е�
2��tomcat ʹ�á�apache-tomcat-7.0.50
3������D:\��Ϣ�м��\RocketMQ\rocketmq-console-master����̨\rocketmq-console-master\target\rocketmq-console-SNAPSHOT-1.0.war�����ŵ�tomcat�µ�webapp�ļ����£�����tomcat���Խ�ѹ��װ
4����tomcat���԰�װ�õġ�webapps\rocketmq-console-SNAPSHOT-1.0\WEB-INF�µġ�index.html�ļ����ŵ���һ��Ŀ¼��
5���޸�\WEB-INF\classes\config.properties�ļ������úö�Ӧ��nameserver��ַ
			rocketmq.namesrv.addr=192.168.44.129:9876
6���޸�\WEB-INF\classes\log4j.properties  ������־·����
		log4j.appender.file.File=D:\log\rocketmq\rocketmq-console.log
7, ����tomcat,�������¼��http://localhost:8080/rocketmq-console-SNAPSHOT-1.0/index.html�����¼�Ͽ���̨��