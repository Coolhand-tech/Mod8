# Mod8


Artemis Financial is a financial services company that handles sensitive data such as savings and investments through a RESTful web API. The client needed a comprehensive vulnerability assessment to secure their application against external threats, ensure compliance with regulations like GDPR for international transactions, and modernize their software by addressing outdated libraries and adopting secure web technologies.

Strengths in Identifying Vulnerabilities and Importance of Secure Coding:
I effectively identified vulnerabilities through manual code reviews and static testing with OWASP Dependency-Check, pinpointing issues like unvalidated inputs, hardcoded credentials, and outdated dependencies. Secure coding is critical to protect sensitive data, maintain customer trust, and avoid reputational and financial losses. For Artemis Financial, secure software ensures compliance, safeguards global transactions, and enhances overall business resilience by reducing breach risks.

Challenging or Helpful Aspects of the Vulnerability Assessment:
The manual review was challenging due to the need to thoroughly inspect code for subtle issues like incomplete implementations. However, the OWASP Dependency-Check tool was extremely helpful, as it automatically identified 175 vulnerabilities across 16 dependencies, providing clear CVE details and mitigation steps. This combination of manual and automated approaches gave a comprehensive view of the application’s security posture.

Increasing Layers of Security and Future Assessment Methods:
I increased security by implementing input validation, HTTPS enforcement, authentication with Spring Security, rate limiting, and secure credential management. In the future, I would use tools like OWASP ZAP for dynamic testing, Burp Suite for penetration testing, and Snyk for continuous dependency monitoring to assess vulnerabilities and prioritize mitigations based on severity and exploitability.

Ensuring Functionality and Security Post-Refactoring:
After refactoring, I ensured functionality by running unit tests and verifying API endpoints with Postman. To check for new vulnerabilities, I re-ran the OWASP Dependency-Check and performed manual reviews of modified code. Tools like SSL Labs confirmed secure configurations, ensuring no new issues were introduced while maintaining application functionality.

Helpful Resources, Tools, or Practices:
Tools like OWASP Dependency-Check, IntelliJ IDEA, and Postman were invaluable for identifying and testing vulnerabilities. Coding practices such as parameterized queries, secure authentication with JWT, and environment variable usage for credentials were effective. These tools and practices will be useful for future secure development tasks, especially in API security and dependency management.

Showcasing Work to Employers:
I would present the Artemis Financial Vulnerability Assessment Report to demonstrate my ability to conduct thorough security assessments, identify critical vulnerabilities, and propose actionable mitigation plans. This artifact highlights my skills in manual code reviews, static analysis, and secure coding practices, showcasing my expertise in building and securing software applications.
