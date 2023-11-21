# tomcat-sample
Apache Tomcat's Sample App With Jakarta Servlet Support, Just for POC (Proof of Concept)

# IDE
IntelliJ IDEA Community Edition + Smart Tomcat Plugin

# Smart Tomcat Plugin Configuration
- Tomcat server: Apache Tomcat/10.0.20 
global configuration: Settings -> Other Settings -> Tomcat Server

- Catalina base: tomcat-sample/target
OS platform specified directory

- Deployment directory: tomcat-sample/src/main/webapp
OS platform specified directory

- Use classpath of module：tomcat-sample
select current project name

- Context path: /sample
correspondence with official sample

- Server port: 8080
default port

- Admin port: 8005
default port

# Maven Commands
- package as war
```bash
mvn package
```

# WebApp URI
http://localhost:8080/sample/
