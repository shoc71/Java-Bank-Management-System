# Java-Bank-Management-System
Making java bank application from srctach

Creating the app from scratch: 
```
mvn archetype:generate   
    -DgroupId=dev.bank.app   
    -DartifactId=banking-app   
    -DarchetypeArtifactId=maven-archetype-quickstart   
    -DinteractiveMode=false
```

How to run this Program (via Maven):

1. Install Maven

2. ```cd banking-app``` (be in the directory)

3. Copy paste this command into the terminal
```
mvn exec:java  -Dexec.mainClass="dev.bank.app.Login" -Dexec.classpathScope=compile -Dexec.classpath=/Java-Bank-Management/banking-app/src/main/java/dev/bank/app
```