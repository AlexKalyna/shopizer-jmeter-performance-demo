
# JMeter Performance Testing Demo Project

This repository contains a demo JMeter test plan for performance testing.

## 📌 Project Structure
/jmeter-performance-test 
├── .github/workflows/ 
# GitHub Actions workflow for automation
├── config/ 
# Config files (CSV, properties, etc.) 
├── results/ 
# Test results
├── gitignore 
# Ignored files (logs, results, etc.)
├── LICENSE 
# Project license
├── README.md 
# Project documentation 
└── test-plan-shopizer.jmx 
# JMeter test plan 

## 🚀 Getting Started

### Prerequisites
- [Apache JMeter](https://jmeter.apache.org/download_jmeter.cgi) installed
- Java (required for JMeter)

### Running Tests Locally

1. Clone the repository:
```shell
    git clone https://github.com/your-username/jmeter-performance-test.git
```

2. Run the JMeter test:

```shell
    jmeter -n -t test-plan-shopizer.jmx -l results/test-results.jtl
```

### GitHub Actions Workflow

This repository includes a GitHub Actions workflow that:

- Runs JMeter tests automatically on push or PR.
- Uploads test results as artifacts.
- Check the workflow file at .github/workflows/jmeter-test.yml.

### License

This project is licensed under the [MIT License](./LICENSE).
