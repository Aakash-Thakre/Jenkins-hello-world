# Springboot Hello World App
This repository is used for Jenkins Learning Demo

### Build JAR
```
mvn clean package -DskipTests=true
```

### Unit Test Cases
```
mvn test
```
 
### Deploy/Run
```
java -jar target/hello-demo-*.jar 
```

### Integration Testing (Return 200 OK response)
```
curl -s http://localhost:6767/hello"
```
