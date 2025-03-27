## Run Locally

2. #### Ensure you have the following installed:

Check for Prerequisites
```bash
    java -version
```

Java Development Kit (JDK):
Version compatible with the project (usually JDK 21 or higher):
```bash
    java -version
```

Maven:
```bash
    mvn -version
```

3. #### Import the Project into Your IDE
Use an IDE like IntelliJ IDEA(Suggested), Eclipse, or VS Code.
Open the project directory in your IDE to manage and run it more effectively.

4. #### Install Dependencies
Run the following command to download all dependencies specified in pom.xml (for Maven):
```bash
    mvn clean install 
```

5. #### Configure Application Properties
Check the application.yml file in the `src/main/resources` directory.
Update configurations like `database URLs`, `credentials`, or `API keys`.

6. #### Run the Application
To start the Spring Boot application:
```bash
    mvn spring-boot:run
```
or just use the run button in the IDE you're using.

