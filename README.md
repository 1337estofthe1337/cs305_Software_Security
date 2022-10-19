# cs305_Software_Security


# Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
  # Artemis Financial has a web-based application which needs to be secured with best software security practices. They wanted us to address their web applications vulnerabilities.
# What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
  # I was able to find many vulnerabilities within the client's web-based software application. Most of these vulnerabilities were due to old versions being used. Older versions have more vulnerabilities and often the newer versions have updated security. It's important to code securely because insecure code can become vulnerable to attack which could have the potential to jeopardize financial and personally identifiable information such as SSN's, passwords, emails, etc. Software security adds a layer of trust between the company and their clients. When news stories hit about credit card numbers being leaked out, it's damaging to the company. This may lead to fewer clients in the future.
# What part of the vulnerability assessment was challenging or helpful to you?
  # Assessing which CVE's were false positives and which were not was hard to clarify at first. It helped to read the descriptions of the vulnerabilities to better assess whether they were relevant or not. However, this was exhaustive since there was so many CVE's to check.
# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
  # I updated many of the packages. Later I also suppressed false positives in order to better tackle the issues that were more concerning.
# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
  # I refactored the code for the software application. I ran the application to ensure that the code was functional. I did OWASP dependency checks to check which issues were still prevalent.
# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
  #I used OWASP dependency check and tried to code with good comments. I'll continue to comment and I will use OWASP dependency check when I think it's necessary on future projects.
# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
  # I will show them how I used information from the OWASP dependency check to analyze vulnerabilities and fix them.
