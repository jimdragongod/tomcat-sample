# tomcat-sample
Apache Tomcat's Sample App With Jakarta Servlet Support, Just for POC (Proof of Concept)

# IDE
IntelliJ IDEA Community Edition + Smart Tomcat Plugin

# Smart Tomcat Plugin Cofiguration
- Tomcat server: Apache Tomcat/10.0.20
global configuration: Settings -> Other Settings -> Tomcat Server
- Catalina base: tomcat-sample/target
OS platfrom specified directory
- Deployment directory: tomcat-sample/src/main/webapp
OS platfrom specified directory
- Use classpath of module：tomcat-sample
select current project name
- Context path: /sample
correspondence with offical sample
- Server port: 8080
default port
- Admin port: 8005
default port

# Maven Commands
- pacakge as war
```bash
mvn package
```

# WebApp URI
http://localhost:8080/sample/
