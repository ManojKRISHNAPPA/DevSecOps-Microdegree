## A05:2021 – Security Misconfiguration
Moving up from #6 in the previous edition, 90% of applications were tested for some form of misconfiguration, with an average incidence rate of 4.%, and over 208k occurrences of a Common Weakness Enumeration (CWE) in this risk category. With more shifts into highly configurable software, it's not surprising to see this category move up. Notable CWEs included are CWE-16 Configuration and CWE-611 Improper Restriction of XML External Entity Reference.

Description
1.  The application might be vulnerable if the application is:

2.  Missing appropriate security hardening across any part of the application stack or improperly configured permissions on cloud services.

3.  Unnecessary features are enabled or installed (e.g., unnecessary ports, services, pages, accounts, or privileges).

4.  Default accounts and their passwords are still enabled and unchanged.

5.  Error handling reveals stack traces or other overly informative error messages to users.

6.  For upgraded systems, the latest security features are disabled or not configured securely.

7.  The security settings in the application servers, application frameworks (e.g., Struts, Spring, ASP.NET), libraries, databases, etc., are not set to secure values.

8.  The server does not send security headers or directives, or they are not set to secure values.

9.  The software is out of date or vulnerable (see A06:2021-Vulnerable and Outdated Components).

## How to Prevent
### Secure installation processes should be implemented, including:

1.  A repeatable hardening process makes it fast and easy to deploy another environment that is appropriately locked down. Development, QA, and production environments should all be configured identically, with different credentials used in each environment. This process should be automated to minimize the effort required to set up a new secure environment.

2.  A minimal platform without any unnecessary features, components, documentation, and samples. Remove or do not install unused features and frameworks.

3.  A task to review and update the configurations appropriate to all security notes, updates, and patches as part of the patch management process (see A06:2021-Vulnerable and Outdated Components). Review cloud storage permissions (e.g., S3 bucket permissions).

   4. A segmented application architecture provides effective and secure separation between components or tenants, with segmentation, containerization, or cloud security groups (ACLs).

5.  Sending security directives to clients, e.g., Security Headers.

6. An automated process to verify the effectiveness of the configurations and settings in all environments.