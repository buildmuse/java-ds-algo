# java-ds-algo

This repository has been initialized as a Maven Java project (minimal setup).

Build and run:

```bash
# show Maven version
mvn -v

# build (tests run by default)
mvn package

# run the application
mvn exec:java -Dexec.mainClass="com.buildmuse.App" || java -cp target/java-ds-algo-0.1.0-SNAPSHOT.jar com.buildmuse.App
```

Notes:
- Uses Java 17 by default in `pom.xml`. Change the `<maven.compiler.source>`/`target` if you need another Java version.
- There's a tiny JUnit 5 test in `src/test/java/com/buildmuse/AppTest.java`.