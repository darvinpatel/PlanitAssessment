# PlanitAssessment

This repository contains automated tests for the Planit Jupiter Toys demo website, created using Selenium WebDriver. The project demonstrates a comprehensive suite of test cases for key e-commerce functionalities, including product browsing, cart management, and form submissions.

## Features

- **Automated UI Testing**: End-to-end tests covering essential workflows such as product selection, cart operations, and form validation.
- **Cross-browser Compatibility**: Tests executed across multiple browsers to ensure a consistent user experience.
- **Page Object Model (POM)**: Utilized to structure and maintain the codebase, improving readability and maintainability.
- **Assertions**: Implemented to validate expected behavior and verify the accuracy of test results.
- **Detailed Reporting**: Generates detailed test execution reports for easier debugging and test result analysis.

## Technology Stack

- **Selenium WebDriver**: For automating browser interactions.
- **Java**: Core language for writing test scripts.
- **JUnit/TestNG**: Test framework for organizing and running the tests.
- **Maven**: Build automation tool for managing dependencies and running tests.

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/darvinpatel/PlanitAssessment.git
   cd PlanitAssessment
   
2. **Install dependencies: Ensure you have Java and Maven installed. Run the following to install all dependencies:**
   ```bash
   mvn clean install
   
3. **Run the tests: Execute the test suite using Maven:**
   ```bash
   mvn test

## Test Scenarious

The project covers the following scenarios:

- Adding products to the cart.
- Removing items from the cart.
- Form submission with validation errors.
- Verifying product details and prices.

## Reporting
After test execution, a detailed test report will be generated. You can access the report in the target/surefire-reports directory.
