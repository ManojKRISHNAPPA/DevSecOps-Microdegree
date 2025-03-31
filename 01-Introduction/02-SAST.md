# SAST:- Static Application Security Testing

### What is Static Application Security Testing (SAST)?
-   **Static Application Security Testing (SAST)** is a security testing methodology that analyzes an application's source code, bytecode, or binaries to identify potential vulnerabilities without executing the program. It’s typically performed early in the development cycle, ideally during the coding phase.

    The goal of SAST is to find security flaws such as SQL injection, cross-site scripting (XSS), buffer overflows, and other vulnerabilities within the code before it is run in a production environment. SAST tools examine the entire codebase to detect weaknesses, offering developers feedback to improve the security of the software.

### Key Features of SAST:
-   **Source Code Analysis:** SAST tools analyze the raw code or binaries to detect vulnerabilities.

-   **Early Detection:** Since SAST is integrated into the development process, it enables early identification of security flaws.

-   **Comprehensive Coverage:** It scans the entire codebase for potential security issues.

-   **Automated:** Tools can automatically perform scans on the code during development or in CI/CD pipelines.

### Commercial and Open-Source Tools for SAST:
#### Commercial SAST Tools:
- **SonarQube (Commercial Version)**
A widely used static code analysis tool that identifies bugs, vulnerabilities, and code smells in the code. The commercial version includes advanced features like security vulnerability detection and deep integration with CI/CD pipelines.

- **Checkmarx**
A comprehensive SAST solution that scans source code for security vulnerabilities, supports a variety of languages, and provides detailed insights into the root causes of vulnerabilities.

- **Veracode**
Veracode offers a cloud-based static analysis platform that identifies vulnerabilities and enforces secure coding standards. It can be integrated into the development pipeline.

- **Fortify Static Code Analyzer (SCA)**
Fortify SCA provides deep analysis of source code for security vulnerabilities. It supports a wide range of programming languages and frameworks and integrates into CI/CD workflows.

#### Open-Source SAST Tools:
- **SonarLint**
An open-source IDE plugin that provides real-time static code analysis for developers to detect bugs, security vulnerabilities, and code quality issues while they are coding.

- **Brakeman**
A static analysis tool specifically for Ruby on Rails applications that scans the application’s source code for security vulnerabilities.

- **SpotBugs (with Find Security Bugs plugin)**
SpotBugs is an open-source static code analysis tool for Java, and when combined with the Find Security Bugs plugin, it detects security vulnerabilities.

- **OWASP Dependency-Check**
This open-source tool checks for known vulnerabilities in libraries and dependencies within the codebase, focusing on both security and license issues.

- **PMD**
An open-source static code analyzer for Java, JavaScript, and other languages that detects issues like empty catch blocks, unused variables, and potential security vulnerabilities.

- **CodeQL**
An open-source semantic code analysis tool developed by GitHub that allows you to write queries to find security vulnerabilities in your code.

- **Infer**
A static analysis tool developed by Facebook to detect issues like null pointer dereferencing and memory leaks, and also finds security vulnerabilities in the code.

## Summary of SAST Tools:
- **Commercial Tools:** These tools often come with enterprise-level features, support, and integration capabilities. Examples include SonarQube, Checkmarx, and Veracode.

- **Open-Source Tools:** These are typically free, community-supported tools, such as SonarLint, Brakeman, and SpotBugs, which can be used to scan and secure code in smaller or less resource-intensive environments.

Both commercial and open-source tools can be integrated into a Continuous Integration/Continuous Deployment (CI/CD) pipeline to automate the detection of vulnerabilities and enforce secure coding practices.
