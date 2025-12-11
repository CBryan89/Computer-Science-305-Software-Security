# Computer-Science-305-Software-Security
SNHU Computer Science 305 Software Security

1. Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a financial planning and consulting company that develops personalized savings, investment, retirement, and insurance strategies for its clients. They wanted to modernize their software systems and improve their security posture. Specifically, they needed a vulnerability assessment of their existing web application and guidance on implementing secure coding practices, including adding encrypted communications and a secure file-verification mechanism.

2. What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

I performed a structured vulnerability assessment using industry-standard tools and identified several areas where the application could be strengthened—such as outdated dependencies, insecure configurations, and missing encryption practices. I provided detailed recommendations and implemented secure hashing and HTTPS configuration to address these issues. Secure coding is essential because it protects sensitive customer information, reduces legal and financial risks, and builds trust with users. Strong security practices directly support a company’s stability, brand reputation, and long-term success.

3. Which part of the vulnerability assessment was challenging or helpful to you?

The most challenging part was analyzing the dependency vulnerabilities and determining which issues were inherited from outdated libraries versus which might be caused by new code changes. However, this was also one of the most helpful components because it gave me hands-on experience reviewing CVEs, evaluating severity levels, and understanding how third-party dependencies impact the overall security of an application.

4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased security by implementing HTTPS using a self-signed certificate, adding SHA-256 checksum functionality, enforcing secure communication channels, and ensuring the application followed secure coding principles. In future assessments, I would continue using tools like OWASP Dependency-Check, static analyzers, penetration testing frameworks, and NIST guidelines to prioritize vulnerabilities and choose the most effective mitigation techniques.

5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

I validated functionality by running the refactored Spring Boot application and manually testing the secure /hash endpoint over HTTPS. I also performed functional testing through the Eclipse console to confirm successful startup with no runtime errors. To ensure security, I re-ran OWASP Dependency-Check after refactoring to verify that no new vulnerabilities were introduced. The results confirmed that any existing CVEs originated from the original project dependencies, not from my newly added code.

6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

I used the Java Cryptography Architecture (JCA), the keytool utility, Spring Boot security configurations, SHA-256 hashing, HTTPS configuration, and the OWASP Dependency-Check plugin. These tools and practices are highly transferable to real-world software development and will be valuable for securing APIs, performing vulnerability testing, and implementing encryption in future projects.

7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would show future employers both the Vulnerability Assessment Report and the Secure Software Practices Report. These documents demonstrate my ability to review, identify, and mitigate security vulnerabilities; configure secure communication protocols; implement cryptographic hashing; and follow industry security standards. The completed Spring Boot project and GitHub repository also showcase my ability to refactor code, document findings, use secure coding techniques, and work with modern development tools.
