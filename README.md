# Continuous Integration with Jenkins

> **Module 2 of my EPAM Test Automation track.** Each module added one layer to the same Selenium framework.
> The complete, final version lives in **[selenium-framework-patterns](https://github.com/gomezLucila25/selenium-framework-patterns)**.

## What this module added

- The framework runs in **Jenkins** on a dedicated **agent node** (master/agent setup).
- Two jobs:
  - a basic build;
  - a **parameterized** job where you choose the browser, environment and suite at build time.
- Test results are shown in Jenkins, and screenshots and logs are archived as build artifacts.
- The `jenkins-screenshots/` folder has evidence of every step: nodes, job configs, builds and console output.

## Stack

Java · Selenium · TestNG · Maven · Jenkins

## Run

```bash
mvn clean test
```
