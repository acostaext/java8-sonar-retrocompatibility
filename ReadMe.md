# Minumum Reproducible Sonar Plugin Example

To run the Sonar Server
```
docker-compose up -d
```

### For Gradle you can Run the sonarqube Task 
![img.png](java-maven/img.png)

### For Maven Add the Following Command to execute
![img_1.png](java-maven/img_1.png)
need to add the following command inside `Execute Maven Goal`
```mvn
mvn sonar:sonar -Dsonar.host.url=http://localhost:9000   -Dsonar.login=<Your Generated Token>
```
## Result :
![img_2.png](java-maven/img_2.png)