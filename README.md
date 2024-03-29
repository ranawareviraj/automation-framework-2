# Test Automation Framework

## Overview

This repository contains a draft of test automation framework built with Java, Selenium, Cucumber, and Spring Boot. The framework is designed to support end-to-end testing of web applications using behavior-driven development (BDD) principles.

## Features

- **Java:** Core programming language.
- **Selenium:** Web browser automation.
- **Cucumber:** BDD framework for test scenarios.
- **Spring Boot:** Provides a structured and modular approach to building test framework.

## Prerequisites

Ensure you have the following installed on your machine:

- Java (version 17)
- Maven (3.2.0)
- Your target web application running locally or accessible.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/ranawareviraj/automation-framework.git
   ```
2. Navigate to the project directory:
   ```bash
    cd automation-framework
   ```
3. Build the project:
   ```bash
   mvn clean install
   ```  

## Configuration

- Customize test configuration in src/test/resources/application.properties.
- Update feature files in src/test/resources/features with your scenarios.


## Reporting
View test execution reports in reports/cucumber-html-report.html after running the tests.




