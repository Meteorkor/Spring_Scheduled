Spring_Scheduled
================

Spring_Scheduled

=====================
##.xml
xmlns:task="http://www.springframework.org/schema/task"

xsi:schemaLocation="
http://www.springframework.org/schema/task 
http://www.springframework.org/schema/task/spring-task.xsd
"
	
	<context:component-scan base-package="com.meteor.controller" />
	<task:annotation-driven/>
	
	
===================
##JAVA
@Scheduled(fixedDelay=3000)
	public void Scheduled(){
	
=======================
