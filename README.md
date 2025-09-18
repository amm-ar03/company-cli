# **Company CLI**

A small Java command-line interface (CLI) application using Picocli

---

## **Features**

- Print your company name.

## **Requirements**

- Java 8 or higher
- Maven (for building the project)

---

## **Installation**

1. Clone the repository:
```bash
git clone https://github.com/amm-ar03/company-cli.git
cd company-cli
```

2. Build JAR with dependencies
```bash
mvn clean package
```

3. Run CLI with the company name
```bash
java -jar target/company-cli-1.0.0-jar-with-dependencies.jar -c "<Company Name>"
```

4. You can also run with a custom message
```bash
java -jar target/company-cli-1.0.0-jar-with-dependencies.jar -c "<Company Name>" -m "Welcome to"



