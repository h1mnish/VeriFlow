# 🚀 VeriFlow – TestNG Automation Framework

**VeriFlow** is a Java-based UI Test Automation Framework designed to improve software quality through structured, maintainable, and scalable automated testing.

Built using **Java, Selenium WebDriver, TestNG, and Maven**, VeriFlow follows the **Page Object Model (POM)** design pattern and demonstrates practical software quality engineering concepts.

The framework is designed to support reusable test components, automated browser testing, test execution management, reporting, and continuous integration.

---

## 🎯 Project Objectives

- Automate web application testing.
- Improve test coverage and reliability.
- Reduce repetitive manual testing efforts.
- Implement maintainable automation architecture.
- Demonstrate industry-standard QA automation practices.
- Integrate automated testing into CI/CD workflows.

## ✨ Key Features

- Selenium WebDriver 4
- Java 17
- TestNG Testing Framework
- Maven Build Management
- Page Object Model (POM)
- Reusable Base Test Architecture
- WebDriver Factory
- Cross-Browser Testing
- Explicit Wait Mechanism
- Data-Driven Testing
- CSV and Excel Test Data Support
- Automated Test Reports
- Logging with Log4j2
- Screenshot Capture on Test Failure
- Retry Mechanism
- Parallel Test Execution
- GitHub Actions CI/CD Integration

*Features should be marked as implemented only after they are actually available in the repository.*

## 🛠 Technology Stack

| Technology | Purpose |
|---|---|
| Java 17 | Programming Language |
| Selenium WebDriver | Browser Automation |
| TestNG | Test Execution |
| Maven | Dependency Management |
| Apache POI | Excel Data Handling |
| Extent Reports | Test Reporting |
| Log4j2 | Logging |
| WebDriverManager | Browser Driver Management |
| Git & GitHub | Version Control |
| GitHub Actions | CI/CD |

## 📂 Project Structure

```text
VeriFlow/
│
├── .github/
│   └── workflows/
│       └── ci.yml
│
├── src/
│   └── test/
│       ├── java/
│       │   ├── base/
│       │   ├── pages/
│       │   ├── tests/
│       │   ├── listeners/
│       │   └── utils/
│       │
│       └── resources/
│           ├── config.properties
│           ├── log4j2.xml
│           └── testdata/
│
├── reports/
├── logs/
├── screenshots/
│
├── testng.xml
├── pom.xml
└── README.md
```

## 🏗 Framework Architecture

```text
             TestNG
                |
                ▼
             BaseTest
                |
                ▼
          DriverFactory
                |
                ▼
          WebDriver Setup
                |
                ▼
           Page Objects
                |
                ▼
           Test Classes
                |
                ▼
         Test Execution
                |
        ┌───────┼────────┐
        ▼       ▼        ▼
      Reports  Logs  Screenshots
```

## 🧪 Test Scenarios

The framework is designed around common e-commerce application workflows.

### Authentication Testing
- Valid User Login
- Invalid User Login
- Locked User Login
- Login Error Validation

### Product Testing
- Product Listing Verification
- Add Product to Cart
- Product Details Validation

### Cart Testing
- Verify Cart Contents
- Remove Product from Cart
- Validate Cart Information

### Checkout Testing
- Checkout Process
- Customer Information Validation
- Order Summary Verification
- Order Confirmation

## 🔄 Software Testing Practices

VeriFlow focuses on demonstrating:

- Functional Testing
- Regression Testing
- UI Automation Testing
- Data-Driven Testing
- Cross-Browser Testing
- Positive and Negative Test Scenarios
- Test Execution and Reporting

## ⚙️ Installation & Setup

### Prerequisites

Make sure the following are installed:

- Java JDK 17
- Apache Maven
- Git
- Chrome, Firefox, or Edge browser

### Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/VeriFlow.git
```

### Navigate to Project

```bash
cd VeriFlow
```

### Install Dependencies

```bash
mvn clean install
```

### Execute Automation Tests

```bash
mvn clean test
```

### Execute Through TestNG

Run the `testng.xml` suite configuration.

## 📊 Test Reports

Test execution reports can be generated to help analyze:

- Passed test cases
- Failed test cases
- Skipped test cases
- Execution duration
- Failure details

## 🔁 Continuous Integration

GitHub Actions can be configured to execute automated tests whenever code is pushed or a pull request is created.

Workflow location:

```text
.github/workflows/ci.yml
```

## 🔮 Future Enhancements

- REST Assured API Automation
- Database Testing using SQL
- Docker Integration
- Selenium Grid
- Jenkins Pipeline Integration
- Allure Reporting
- Cloud-Based Cross-Browser Testing

## 💡 Why VeriFlow?

VeriFlow represents a structured approach to software quality assurance.

The goal is not simply to automate test cases, but to build a maintainable testing system that improves confidence in software behavior, identifies defects early, and supports reliable software delivery.

---

## 👨‍💻 Author

**Himnish Tyagi**

Computer Science Engineering | Software Engineering

**Technical Interests:**
- Software Quality Assurance
- Test Automation
- Java & Selenium
- API Testing
- CI/CD
- Software Reliability

---

⭐ If you find VeriFlow useful, consider giving this repository a star.

**VeriFlow – Verify Better. Deliver with Confidence.**
