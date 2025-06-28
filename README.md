# Secure Software Report Reflection

## 1. Who is Artemis Financial and what issue did they want addressed?
Artemis Financial is a client that provides financial services to customers. They needed help securing a Java-based software application used in their operations. The main issue they wanted addressed was the lack of strong security practices in their existing software. My job was to improve the application’s security by identifying vulnerabilities and applying secure coding practices.

## 2. What did you do well when identifying security vulnerabilities, and why is secure coding important?
I was able to identify weaknesses such as missing HTTPS configuration, lack of certificate validation, and no integrity checks for file transfers. Secure coding is important because it protects sensitive data, prevents unauthorized access, and reduces the risk of breaches that could damage a company’s reputation and operations. Software security helps ensure the system remains trustworthy and compliant with industry standards.

## 3. What part of the assessment was challenging or helpful?
The most challenging part was configuring the Java keystore and setting up HTTPS correctly in the development environment. It was helpful to work through each stage step by step and verify that the application behaved as expected after changes were applied. Performing functional and static testing gave me confidence in the final version.

## 4. How did you increase layers of security? What tools or methods would you use in the future?
I increased security by generating a self-signed SSL certificate, enabling HTTPS in the application, and implementing SHA-256 checksum verification for file integrity. I also used the OWASP dependency check to scan for known vulnerabilities. In the future, I would use similar tools along with static code analysis, penetration testing utilities, and updated cipher suites for better security.

## 5. How did you ensure the refactored code remained secure and functional?
After each major change, I tested the application’s functionality to make sure it still worked correctly. I also ran dependency checks and re-verified the SSL configuration and checksum functionality. I watched for errors in the logs and confirmed that no new vulnerabilities were introduced by the changes.

## 6. What resources or practices will you use again in future projects?
I will continue to use OWASP tools for vulnerability checks, implement secure file transfer techniques like checksums, and ensure all communication is encrypted with HTTPS. I also found it helpful to clearly document each change, which helped me track progress and troubleshoot issues.

## 7. What might you show future employers from this assignment?
I can show future employers my secure software report and the refactored code as proof of my ability to identify software vulnerabilities, improve security through encryption and integrity checks, and follow best practices for secure development. This project shows that I can take ownership of a security-focused assignment and deliver a complete, working solution.
