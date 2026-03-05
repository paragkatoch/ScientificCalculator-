# Scientific Calculator

A simple **Java scientific calculator** with a **CI/CD pipeline using Jenkins, Docker, and Ansible**.

## Features
- Square root
- Factorial
- Natural log
- Power function
- Menu-driven CLI

## Tech Stack
Java • Maven • JUnit • Docker • Jenkins • Ansible

## Build
```bash
mvn clean package
```

## Run
```bash
java -jar target/calculator-1.0-SNAPSHOT.jar
```

## Docker
```bash
docker build -t calculator -f ./docker/dockerfile .
docker run -it calculator
```

## CI/CD Pipeline
GitHub → Jenkins → Build & Test → Docker Image → Docker Hub → Ansible Deploy
