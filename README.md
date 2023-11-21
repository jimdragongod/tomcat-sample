# tomcat-sample
Apache Tomcat's Sample App With Jakarta Servlet Support, Just for POC (Proof of Concept)

# IDE
IntelliJ IDEA Community Edition + Smart Tomcat Plugin

# Smart Tomcat Plugin Configuration
- Tomcat server: Apache Tomcat/10.0.20 <br/>
global configuration: Settings -> Other Settings -> Tomcat Server

- Catalina base: tomcat-sample/target <br/>
OS platform specified directory

- Deployment directory: tomcat-sample/src/main/webapp <br/>
OS platform specified directory

- Use classpath of module：tomcat-sample <br/>
select current project name

- Context path: /sample <br/>
correspondence with official sample

- Server port: 8080 <br/>
default port

- Admin port: 8005 <br/>
default port

# Maven Commands
- create war package
```bash
mvn clean package
```

# WebApp URI
http://localhost:8080/sample/