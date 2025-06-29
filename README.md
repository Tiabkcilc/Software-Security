# Software-Security
<h3>Client Summary</h3>
<p>
Artemis Financial is a consulting company that creates customized financial plans, including savings, investment, and insurance services. The company needed to improve the security of its web application to protect sensitive client data. Specifically, they requested the addition of a file verification feature and secure communication using HTTPS.
</p>

<h3>Approach and Value</h3>
<p>
I identified and addressed potential software vulnerabilities by implementing a checksum verification using the SHA-256 hashing algorithm and enabling HTTPS with a self-signed certificate. Secure coding is essential to prevent data breaches, maintain user trust, and comply with industry regulations. These updates add significant value to the company’s overall security posture and client confidence.
</p>

<h3>Challenges and Insights</h3>
<p>
One challenging but helpful aspect was ensuring the secure configuration of HTTPS using a self-signed certificate. It required careful setup of the keystore and properties file but provided valuable experience in securing web traffic.
</p>

<h3>Security Enhancements and Future Practices</h3>
<p>
I added layers of security through HTTPS, data integrity checks, and dependency scanning. In the future, I would continue using static analysis tools like OWASP Dependency-Check and implement automated security testing in CI/CD pipelines to identify and mitigate risks more efficiently.
</p>

<h3>Verification and Testing</h3>
<p>
After refactoring, I verified the application’s functionality by running the secure endpoint and checking output manually. I also used static analysis to confirm no new vulnerabilities were introduced during development.
</p>

<h3>Tools and Best Practices</h3>
<p>
I used Java Keytool, SHA-256 hashing with <code>MessageDigest</code>, and OWASP Dependency-Check. I followed secure coding practices such as avoiding deprecated cryptographic algorithms and limiting exposed functionality.
</p>

<h3>Future Portfolio Use</h3>
<p>
This project demonstrates my ability to secure a Java-based web application, perform vulnerability assessments, and apply encryption best practices. I would share this artifact with future employers as evidence of my knowledge in secure software development and real-world application of cybersecurity concepts.
</p>
