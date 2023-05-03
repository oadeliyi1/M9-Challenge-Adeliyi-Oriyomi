# M9-Challenge-Adeliyi-Oriyomi

## Issues and Source of Solutions:

I had to add a dependency and change the spring boot version to 2.6.7 to avoid a "java.security.PrivilegedActionException: null" error. 

This is the dependency I added: 
		<dependency>
			<groupId>com.sun.xml.messaging.saaj</groupId>
			<artifactId>saaj-impl</artifactId>
			<version>1.5.1</version>
		</dependency>

Courtesy to this answer thread in StackOverflow: https://stackoverflow.com/questions/72534992/java-security-privilegedactionexception-null
