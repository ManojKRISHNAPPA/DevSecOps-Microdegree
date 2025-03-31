# DAST AND ITS TOOLS
**DAST** stands for **"Dynamic Application Security testing"** and is a method of testing the
security of an application or system by actively interacting with it and attempting to exploit vulnerabilities.

**Dynamic Application Security Testing (DAST)** is a type of security testing that analyzes a running application (often a web application) to identify vulnerabilities and security weaknesses. Unlike static analysis (which examines the source code of the application), DAST scans are performed during runtime and interact with the application in real-time, mimicking the behavior of an attacker trying to exploit vulnerabilities. This makes DAST useful for identifying issues such as:
-   Injection attacks (e.g., SQL injection)
-   Cross-site scripting (XSS)
-   Authentication issues 
-   Session management flaws
-   Security misconfigurations

## Key Characteristics of DAST:
**Runtime Testing:** DAST tests the application while it's running, without needing access to the source code.

**Black-Box Testing:** DAST typically operates in a "black-box" fashion, meaning it tests the application from an external perspective, with no prior knowledge of the underlying code.

**Automated Vulnerability Scanning:** DAST tools simulate attacks to detect vulnerabilities and provide reports with remediation advice.

DAST can be an effective way to identify and address vulnerabilities in an application or system, but it is
important to note that it is not a substitute for other types of security testing such as static analysis or
penetration testing. It is often used in combination with these other techniques as part of a
comprehensive security testing strategy.

### Commercial DAST Tools:
#### OWASP ZAP (Zed Attack Proxy)

Description: An open-source tool that can also be used commercially, ZAP is widely known and provides automated scanners for detecting vulnerabilities in web applications. ZAP is often used for penetration testing and integrates well with CI/CD workflows.

Features: Automated scanning, manual testing capabilities, support for a wide range of vulnerabilities, and a large plugin ecosystem.

Website: https://www.zaproxy.org

#### Burp Suite Professional

Description: Burp Suite is a popular commercial tool used for web application security testing. Its professional version includes an advanced DAST scanner that can identify a wide range of vulnerabilities, including SQL injections, XSS, and more.

Features: Advanced scanning capabilities, intercepting proxy, fuzzing tools, extensive reporting, and integration options with CI/CD pipelines.

Website: https://portswigger.net/burp

#### Acunetix

Description: Acunetix is a commercial web vulnerability scanner designed for dynamic application security testing. It scans websites and web applications for vulnerabilities like SQL injection, XSS, and other common security issues.

Features: Automated scans, multi-level reporting, CI/CD integration, and support for modern web technologies such as HTML5, JavaScript, and Angular.

Website: https://www.acunetix.com

#### Nessus

Description: While primarily a vulnerability scanner, Nessus includes dynamic application security testing features for web applications and network-based security testing.

Features: Comprehensive vulnerability scanning, ease of use, and reporting, with integration into DevOps pipelines.

Website: https://www.tenable.com/products/nessus

#### Checkmarx (CxSAST + CxIAST)

Description: Checkmarx is a comprehensive application security solution that combines both static and dynamic testing. It provides a DAST solution through its CxIAST tool, which integrates runtime security testing into the development lifecycle.

Features: Automated vulnerability detection, detailed reporting, DevSecOps integration, and support for both on-premises and cloud environments.

Website: https://www.checkmarx.com

### Open-Source DAST Tools:
#### OWASP ZAP (Zed Attack Proxy)

As mentioned, OWASP ZAP is an open-source DAST tool that is free to use and actively supported by the OWASP community. It's one of the most popular open-source tools for dynamic security testing.

Features: Automated vulnerability scanning, manual testing, penetration testing features, and extensive plugin support.

Website: https://www.zaproxy.org

#### Wapiti

Description: Wapiti is an open-source web application vulnerability scanner that performs dynamic security testing. It supports both black-box and grey-box testing and focuses on common web application vulnerabilities.

Features: Scans for a wide range of vulnerabilities like SQL injection, XSS, and file inclusion. It can be run via command line or integrated into CI/CD pipelines.

Website: https://wapiti.sourceforge.io

#### Nikto

Description: Nikto is a free and open-source web server scanner that detects various security issues. It scans web servers for vulnerabilities, outdated software, and configuration issues.

Features: Detects known vulnerabilities, outdated web server software, and potential misconfigurations. It is extensible and supports multiple protocols.

Website: https://cirt.net/Nikto2

#### Arachni

Description: Arachni is an open-source DAST tool designed for security testing of modern web applications. It is suitable for penetration testers and security auditors.

Features: Automated scanning, extensive vulnerability detection capabilities, and robust reporting tools.

Website: https://www.arachni-scanner.com

#### Vega

Description: Vega is an open-source web application scanner that performs DAST and can help identify vulnerabilities like SQL injections, XSS, and others.

Features: Provides an intuitive GUI, supports both automated and manual testing, and includes features for vulnerability analysis and exploitation.

Website: https://subgraph.com/vega/

## Summary:
DAST focuses on identifying vulnerabilities in a running application by simulating external attacks during runtime.

Commercial DAST tools such as Burp Suite, Acunetix, and Checkmarx offer advanced vulnerability scanning, detailed reporting, and integration with CI/CD pipelines.

Open-source DAST tools like OWASP ZAP, Nikto, Wapiti, and Arachni provide cost-effective alternatives for dynamic security testing, although they may require more manual configuration and setup.

Both commercial and open-source tools are essential for identifying runtime vulnerabilities and securing applications against various attack vectors.