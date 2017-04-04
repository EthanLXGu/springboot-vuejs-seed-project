To run spring boot app with built code from the parent (root pom) run:
```
mvn install && mvn --projects backend spring-boot:run
```


To setup run with Intellij:

* Run > Edit Configurations... > hit the plus sign to add a new configuration > select maven 
* Name the new maven entry as ```spring-boot:run```
* Set Working Directory to ```/Users/<yourUserName>/IdeaProjects/app```
* Set Command Line to ```-projects backend spring-boot:run```
