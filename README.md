# spring-completed-tutorial

test steps:

1. `./gradlew build`
2. `java -jar build/libs/serving-web-content-0.0.1-SNAPSHOT.jar`
3. open localhost:8080, check that it is running
4. open localhost:8080/greeting:
<img width="100%" alt="Screenshot 2022-08-18 at 18 46 16" src="https://user-images.githubusercontent.com/1117405/185438196-0f3ddf08-33f3-4120-8e29-2bbd5df4d95e.png">
<img alt="Screenshot 2022-08-18 at 18 46 16" src="https://user-images.githubusercontent.com/1117405/185438206-96a0411a-358e-4014-8601-0d5b6cdcf92d.png">

## Requirements

Java - 11

Maven - 3.x.x

## Steps to Setup

**1. Clone the application**

**2. Build and run**
```bash
mvn package
java -jar target/...-SNAPSHOT.jar
```
OR
```bash
mvn spring-boot:run
```