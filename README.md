# CS-305-Portfolio
CS 305 Software Security Portfolio

Artemis Financial – Secure Software Practices

Project Overview

For this project, I worked with Artemis Financial, a financial services company that needed to improve the security of its software application. The main goal was to protect sensitive information, improve secure communication, and identify possible security weaknesses.

Reflection

1. What did I do well, and why is secure coding important?

I think I did well with adding security improvements to the application and testing them afterward. I implemented SHA-256 checksum verification and configured HTTPS to help protect communication. Secure coding is important because companies need to protect customer information and prevent security problems that could affect their customers and reputation.

2. What was challenging or helpful about the vulnerability assessment?

One of the more challenging parts was working with the dependency-check tools and understanding the scan results. The report identified potential vulnerabilities in the application’s dependencies, which helped me understand that even when a program runs correctly, it can still have security issues that need attention.

3. How did I increase the layers of security?

I added SHA-256 hashing for data integrity, generated a self-signed certificate, and configured HTTPS for encrypted communication. In the future, I would continue using dependency scans, review outdated libraries, and follow current security recommendations when deciding how to address vulnerabilities.

4. How did I make sure the application was functional and secure?

After making changes, I ran the application to check that it still worked. I confirmed that the server started using HTTPS on port 8443 and completed an OWASP Dependency-Check scan. The scan identified potential vulnerabilities that would need further review, so I learned that successful testing does not automatically mean an application is free of security risks.

5. What tools and resources did I use?

I worked with Java, Eclipse, Maven, SSL certificates, and OWASP Dependency-Check. I also practiced using SHA-256 hashing and testing secure communication. These are tools and skills I can use again in future software development projects.

6. What could I show future employers?

I could show employers my completed Artemis Financial secure software report as an example of my experience improving application security. It demonstrates my ability to implement security features, test an application, review vulnerability findings, and document my work.

What I Learned

This project helped me understand that software security involves more than just making a program work. Developers also need to protect information, check for vulnerabilities, and continue testing their applications as technology and security risks change.
