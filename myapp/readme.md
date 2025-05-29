# Maven Test Project

This is a simple Java project created using Maven archetype `maven-archetype-quickstart`.

## 📁 Project Info

- **Group ID**: com.example  
- **Artifact ID**: myapp  
- **Archetype Version**: 1.4  
- **Java version**: 8 or above  
- **Build tool**: Apache Maven  

## 📦 How to Build

Make sure you have **Java** and **Maven** installed.

```bash
mvn clean install

▶️ How to Run
After building, run the application with:

```bash
java -cp target/myapp-1.0-SNAPSHOT.jar com.example.App

**Make sure the App.java file has a main() method.**
🧪 How to Run Tests
```bash
mvn test

This runs the JUnit tests inside the src/test/java folder.

If you are going with new folder then run:
```bash
mvn archetype:generate -DgroupId=com.example -DartifactId=myapp -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false
