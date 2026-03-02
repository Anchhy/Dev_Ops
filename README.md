# Dev_Ops - Java Setup

Minimal Java starter project using Maven and JDK 21.

## Prerequisites

- Java 21+
- Maven 3.8+

## Project Structure

src/
- main/java/com/example/App.java
- test/java/com/example/AppTest.java

## Getting Started

1. Open a terminal in the project root.
2. Build the project:

```bash
mvn clean package
```

## Run the Application

```bash
mvn exec:java
```

Expected output:

```text
Java setup complete ✅
```

## Run Tests

```bash
mvn test
```

## Notes

- Main class: `com.example.App`
- Java release level is set to 21 in `pom.xml`
