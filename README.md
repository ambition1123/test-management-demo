# Test Management Demo

This is a Java Maven project demonstrating unit testing with JUnit 5.

## Project Structure

- `pom.xml`: Maven configuration file
- `src/main/java/com/example/demo/Calculator.java`: Main calculator class
- `src/test/java/com/example/demo/CalculatorTest.java`: Unit tests for the calculator

## Building and Testing

To build the project and run tests:

```bash
mvn clean package
```

To run only tests:

```bash
mvn test
```

## Running the Application

After building, you can run the JAR:

```bash
java -jar target/test-management-demo-1.0-SNAPSHOT.jar
```