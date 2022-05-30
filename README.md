# Taxi Service
<p align = "center">
<img alt="Taxi picture" height="417" src="src/main/resources/images/taxi.jpg">
</p>

# About project:
Taxi service is a web application that can be used to keep a record of taxi drivers and cars. You need to log in first, then you can:

- Add/Delete/DisplayAll driver
- Add/Delete/DisplayAll manufacturer
- Add/Delete/DisplayAll car
- Add driver to car

# Technologies used:

- Java 11
- Apache Maven
- Apache Tomcat 9
- Injector
- Java Servlets
- JDBC
- MySQL

# If you want to run this project, you need:
1. Install MySQL
2. Clone this project
3. Create DB using `init_db.sql` file from `src/main/resources` directory
4. Configure `src/main/java/taxi/util/ConnectionUtil.java` class to create connection to db:
```java
public class ConnectionUtil {
    private static final String URL = "YOUR_MySQL_URL";
    private static final String USERNAME = "YOUR_MySQL_USERNAME";
    private static final String PASSWORD = "YOUR_MySQL_PASSWORD";
}
```
5.Install and configure Apache Tomcat(or another servlet container). Use `/` as application context path
