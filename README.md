# SNHU-CS-305
Portfolio project for the SNHU course CS 305: Software Security

### Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a financial services company. It is developing a website that needs to be secured against attackers.

### What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

There were a few issues in the client's software that needed addressing. Notably, the way the system accepted user input was susceptible to injection attacks. Security is especially important to financial service companies, because the data pertains to real money. Hackers gaining access could mean bankruptcy, or at minimum, the loss of customer confidence. In addition, these types of companies have regulations to comply with, and stiff penalties for failure to do so.

### Which part of the vulnerability assessment was challenging or helpful to you?

I got stuck trying to get the server to run, and to verify the algorithm cipher was working.

### How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

One such way that I might have implemented, given the time, was to sanitize user data of things like escape characters, and to parameterize. User input should not be trusted, by default.

### How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

Using the Maven dependency checker, I was able to identify known vulnerabilities and potential mitigations.

### What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

In addition to Maven, we also used a checksum to verify the algorithm cipher.

### Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I think an employer were like to know about my experience using the Maven dependency checker and my implementation of an algorithm cipher.
