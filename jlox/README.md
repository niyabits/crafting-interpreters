## Maven

The project uses Maven. <br />
[Maven in five minutes Guide to get started.](https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html)

#### quickly run:

```
mvn package
java -cp target/jlox-1.0-SNAPSHOT.jar com.craftinginterpreters.lox.App
```

### Build the project

```
mvn package
```

### Running the project

```
java -cp target/jlox-1.0-SNAPSHOT.jar com.craftinginterpreters.lox.App
```

### Creating this Project

Following command was used:

```bash
mvn archetype:generate -DgroupId=com.craftinginterpreters.lox -DartifactId=jlox -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false
```
