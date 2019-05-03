Secure Spring REST API using OAuth2
===================================

 - http://websystique.com/spring-security/secure-spring-rest-api-using-oauth2/
 - [เรียนรู้เทคโนโลยี OAuth2](https://sysadmin.psu.ac.th/2017/04/23/what-is-oauth2/)
 - [Qeo Native Documentation : Implicit Grant](http://www.qeo.org/Doc/Implicit-Grant_21676147.html)

## Test

```
mvn clean package

java -jar target/dependency/jetty-runner.jar target/*.war
```

http://localhost:8080/oauth/token?grant_type=password&username=bill&password=abc123

## TODO
 - Implement with Spring Boot + Spring Security OAuth2
 - [Spring Boot REST API (4) - Security with OAuth2](https://gigsterous.github.io/engineering/2017/03/01/spring-boot-4.html)
