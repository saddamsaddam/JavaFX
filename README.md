path:   
--module-path "C:\Program Files\Java\javafx-sdk-19.0.2.1\lib" --add-modules=javafx.controls,javafx.fxml



pc javafx directory:
![image](https://github.com/saddamsaddam/JavaFX/assets/56682452/01f31de3-f3db-4677-b59d-8b94f074e222)


config project screenshot:
![image](https://github.com/saddamsaddam/JavaFX/assets/56682452/b480e0ad-412a-4ca2-9d15-b391b209734d)


config path screenshot:
![image](https://github.com/saddamsaddam/JavaFX/assets/56682452/a3b93e70-a8fe-4240-891d-46c0560771b5)

maven project:
pom.xml:
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
  xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
  <modelVersion>4.0.0</modelVersion>

  <groupId>Very</groupId>
  <artifactId>Vas</artifactId>
  <version>0.0.1-SNAPSHOT</version>
  <packaging>jar</packaging>

  <name>Vas</name>
  <url>http://maven.apache.org</url>

  <properties>
    <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
  </properties>

  <dependencies>
    <dependency>
      <groupId>junit</groupId>
      <artifactId>junit</artifactId>
      <version>3.8.1</version>
      <scope>test</scope>
    </dependency>
    <dependency>
        <groupId>org.openjfx</groupId>
        <artifactId>javafx-controls</artifactId>
        <version>19</version>
    </dependency>
    <dependency>
        <groupId>org.openjfx</groupId>
        <artifactId>javafx-fxml</artifactId>
        <version>19</version>
    </dependency>
    
    
  </dependencies>
  
  <build>
    <plugins>
        <plugin>
            <groupId>org.openjfx</groupId>
            <artifactId>javafx-maven-plugin</artifactId>
            <version>0.0.8</version>
            <configuration>
                <mainClass>Main</mainClass>
            </configuration>
        </plugin>
    </plugins>
</build>
</project>
