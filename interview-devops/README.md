# Correvate's Devops engineer test

Support files for Correvate's Devops engineer test

Solutions

1. List of commands executed
java -jar target/my-api-1.0.0.1591234567.jar
lsof -i :8080\n
 1099  mvn spring-boot:run\n
 1100  java -jar \n
 1101  mvn spring-boot:run\n
 1102  mvn spring-boot:run -Dspring-boot.run.arguments=--debug\n
 1103  java -jar my-api-1.0.0.1591234567.jar --debug\n
 1104  java -jar my-api-1.0.0.1591234567.jar --debug\n
 1105  ls
 1106  cd target
 1107  ls
 1108  java -jar my-api-1.0.0.1591234567.jar --debug\n
 1109  java -jar target/my-api-1.0.0.1591234567.jar
 1110  java -jar target/my-api-1.0.0.1591234567.jar
 1111  cd ..
 1112  java -jar target/my-api-1.0.0.1591234567.jar
 1113  java -jar target/my-api-1.0.0.1591234567.jar

2. Full output log for each of the commands


  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::        (v2.3.1.RELEASE)

01:58:02.165 [main] INFO  u.c.c.hr.devops.DevopsTestApp - Starting DevopsTestApp on MacBooks-MacBook-Air.local with PID 29592 (/Users/macbook/Downloads/consentemailforthedevopsengineerrolewhichisremoteb/interview-devops/my-api/target/my-api-1.0.0.1591234567.jar started by macbook in /Users/macbook/Downloads/consentemailforthedevopsengineerrolewhichisremoteb/interview-devops/my-api)
01:58:02.169 [main] INFO  u.c.c.hr.devops.DevopsTestApp - No active profile set, falling back to default profiles: default
01:58:05.015 [main] INFO  o.s.b.w.e.tomcat.TomcatWebServer - Tomcat initialized with port(s): 8080 (http)
01:58:05.043 [main] INFO  o.a.coyote.http11.Http11NioProtocol - Initializing ProtocolHandler ["http-nio-8080"]
01:58:05.043 [main] INFO  o.a.catalina.core.StandardService - Starting service [Tomcat]
01:58:05.044 [main] INFO  o.a.catalina.core.StandardEngine - Starting Servlet engine: [Apache Tomcat/9.0.36]
01:58:05.199 [main] INFO  o.a.c.c.C.[Tomcat].[localhost].[/] - Initializing Spring embedded WebApplicationContext
01:58:05.199 [main] INFO  o.s.b.w.s.c.ServletWebServerApplicationContext - Root WebApplicationContext: initialization completed in 2915 ms
01:58:05.585 [main] INFO  u.c.c.hr.devops.DevopsTestApp - Starting awesome application uk.co.correvate.hr.devops:my-api:1.0.0.1591234567 ...
01:58:05.813 [main] INFO  o.s.s.c.ThreadPoolTaskExecutor - Initializing ExecutorService 'applicationTaskExecutor'
01:58:06.423 [main] INFO  o.s.b.a.e.web.EndpointLinksResolver - Exposing 2 endpoint(s) beneath base path '/actuator'
01:58:06.462 [main] INFO  o.a.coyote.http11.Http11NioProtocol - Starting ProtocolHandler ["http-nio-8080"]
01:58:06.517 [main] WARN  o.s.b.w.s.c.AnnotationConfigServletWebServerApplicationContext - Exception encountered during context initialization - cancelling refresh attempt: org.springframework.context.ApplicationContextException: Failed to start bean 'webServerStartStop'; nested exception is org.springframework.boot.web.server.PortInUseException: Port 8080 is already in use
01:58:06.517 [main] WARN  o.s.b.f.s.DisposableBeanAdapter - Invocation of destroy method failed on bean with name 'tomcatMetricsBinder': java.lang.NullPointerException
01:58:06.518 [main] INFO  o.s.s.c.ThreadPoolTaskExecutor - Shutting down ExecutorService 'applicationTaskExecutor'
01:58:06.531 [main] INFO  o.a.coyote.http11.Http11NioProtocol - Pausing ProtocolHandler ["http-nio-8080"]
01:58:06.531 [main] INFO  o.a.catalina.core.StandardService - Stopping service [Tomcat]
01:58:06.541 [main] INFO  o.a.coyote.http11.Http11NioProtocol - Stopping ProtocolHandler ["http-nio-8080"]
01:58:06.542 [main] INFO  o.a.coyote.http11.Http11NioProtocol - Destroying ProtocolHandler ["http-nio-8080"]
01:58:06.560 [main] INFO  o.s.b.a.l.ConditionEvaluationReportLoggingListener - 

Error starting ApplicationContext. To display the conditions report re-run your application with 'debug' enabled.
01:58:06.563 [main] ERROR o.s.b.d.LoggingFailureAnalysisReporter - 

***************************
APPLICATION FAILED TO START
***************************

Description:

Web server failed to start. Port 8080 was already in use.

Action:

Identify and stop the process that's listening on port 8080 or configure this application to listen on another port.

