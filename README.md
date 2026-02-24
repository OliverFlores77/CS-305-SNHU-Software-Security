# CS-305 Software Security Portfolio Artifact



Artifact Included: Artemis Financial Vulnerability Assessment Report

1. Client Overview and Software Requirements

Artemis Financial is a financial services company that required a security assessment of its web-based REST application. The application processes financial information and operates in a client-server environment, which makes security a critical requirement. Because the system handles sensitive customer and account data, it must ensure confidentiality, integrity, and secure communication.

The main software requirement was to perform a vulnerability assessment of the application. This included reviewing the source code, identifying security weaknesses, analyzing third-party dependencies, and recommending mitigation strategies to improve the overall security posture of the system.

2. What I Did Well

One area I performed well in during this project was conducting a structured and detailed vulnerability assessment. I carefully reviewed the application’s source code and identified weaknesses related to input validation, authentication, authorization, cryptography, and secure configuration. I made sure to connect each identified issue to a specific security domain and explain why it was relevant to Artemis Financial’s application.

I also successfully used OWASP Dependency-Check to analyze third-party libraries and identify known vulnerabilities in outdated dependencies. This strengthened the overall assessment and demonstrated the importance of managing external components securely.

3. Importance of Secure Coding

Secure coding is especially important for financial applications because they handle sensitive customer and account information. If vulnerabilities exist, attackers could exploit them to gain unauthorized access, manipulate financial data, or expose confidential information. This could result in financial loss, legal consequences, and damage to a company’s reputation.

By implementing secure coding practices such as proper input validation, encryption, access control, and secure configuration, organizations can reduce risk and build trust with their customers. Security adds value to a company by protecting its systems, data, and long-term stability.

4. Challenges and How I Overcame Them

One of the most challenging parts of this project was accurately mapping application components to the correct security domains and supporting each finding with actual code references. It required careful review of controller classes, configuration files, and dependency reports to ensure that each vulnerability was properly documented and justified.

I overcame this challenge by taking a systematic approach to reviewing the source code and cross-referencing findings with the vulnerability assessment process flow diagram. This helped me clearly connect technical issues to the appropriate security areas and improve the overall quality of the report.

5. Layers of Security Implemented

To improve the application’s security, I focused on strengthening multiple layers within the system. I evaluated how the application handled user input and identified areas where additional validation would reduce risk. I examined the lack of authentication and authorization controls on REST endpoints and explained why proper access control mechanisms are necessary in a financial application. I also addressed cryptography by recognizing the need for secure transmission of sensitive data. In addition, I reviewed secure configuration practices, including dependency management, and identified outdated libraries that introduced known vulnerabilities. Applying multiple layers of security helps ensure that if one control fails, other protections are still in place to reduce overall risk.

6. Verifying Security After Refactoring

After identifying vulnerabilities, I reviewed the code to ensure that recommended improvements would not negatively affect application functionality. I also used static analysis tools, including OWASP Dependency-Check, to verify dependency-related vulnerabilities. This process helped confirm that security improvements could be implemented while maintaining stable system performance and functionality.

7. Tools and Resources Used

The primary tool used during this project was OWASP Dependency-Check, which allowed me to scan third-party libraries and identify known vulnerabilities in outdated components. I also relied on Java secure coding principles, course materials on vulnerability assessment, and best practices for secure software development. These resources helped me analyze both code-level and configuration-level security risks within the application.

8. What I Would Show a Future Employer

If presenting this project to a future employer, I would highlight my ability to conduct a structured vulnerability assessment of a Java-based web application. I would demonstrate how I identified security weaknesses in source code, analyzed dependency vulnerabilities using industry tools, mapped findings to specific security domains, and recommended realistic mitigation strategies. This project shows that I understand secure software development concepts and can apply them to protect applications that handle sensitive financial data.
