# CS-305-Software-Security

This repo was the major assignment for my CS 305: Software Security class at Southern New Hampshire University during the completion of my Bachelors of Computer Science degree.

**Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?**

Artemis Financial is a financial services company that required a security assessment of its existing software infrastructure. The company faced vulnerabilities related to data protection, access control, and secure authentication. The goal was to identify and mitigate security risks to protect sensitive financial data and ensure compliance with industry standards.

**Which part of the vulnerability assessment was challenging or helpful to you?**

The most challenging part of the vulnerability assessment was manually analyzing the code for vulnerabilities and determining which security risks posed the most significant threat.

**How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**

To strengthen security, I implemented improved input validation, performed OWSAP dependency vulnerability assessments, implemented secure checksum validation, refactored a RESTful server to use HTTPS for all requests and responses, and performed manual code inspection. 

**How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**

After refactoring the code, I reran the OWSAP dependency vulnerability assessment to ensure any new libraries being implemented were secure, and performed static manual testing to ensure system information is not passed to the user with any exceptions at runtime. 

**Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?**

This project showcases my ability to conduct security assessments, refactor code securely, and implement best practices for software protection. A future employer would see my experience in identifying vulnerabilities, applying secure coding principles, and ensuring software reliability in a financial environment.





