# Limbo
[![Build Status](http://ci.loohpjames.com/job/Limbo/badge/icon)](http://ci.loohpjames.com/job/Limbo/)
## Standalone Limbo Minecraft Server (Currently 1.18.2)

### Starting the server
Use the following command lines to start the limbo server just like any other minecraft server
```
java -jar Limbo.jar --nogui
```

Put the world schem file in the same folder as the server jar file and configurate the `server.properties` file to your needs 
***
### Demo Limbo Server
```
IP: mc.loohpjames.com
```
![Server Banner](https://api.loohpjames.com/serverbanner.png?ip=mc.loohpjames.com&width=918&name=IP:%20mc.loohpjames.com)
***
### Downloads (1.17.1-1.18.2)
- [Jenkins](http://ci.loohpjames.com/job/Limbo/)
***
### Maven
```html
<repository>
  <id>loohp-repo</id>
  <url>https://repo.loohpjames.com/repository</url>
</repository>
```
```html
<dependency>
  <groupId>com.loohp</groupId>
  <artifactId>Limbo</artifactId>
  <version>VERSION</version>
  <scope>provided</scope>
</dependency>
```
Replace `VERSION` with the version.
