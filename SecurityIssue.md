**OWASP Top 10** - Open Web Application Security Project is a non-profit organization for Application. Mobile & API security requirement.
Below are the 10 common things to look into
1. **Broken Access Control** - If an unahorized party can access some functionality, data, perform some action. ex - user can access an admin page
2. **Cryptographic failure** - This is data encryption part and choosing idustry statndard algorithm and storing the key for encryption securely in a key store
3. **injection** - This cover where a attacker can insert some input in a form or user input field and the same damage the application or genuine user. Definition - injection attack is a type of security exploit where an attacker injects malicious data or code into a computer program, typically with the intention of compromising the integrity or security of the target system. Injection attacks can occur in various types of software, such as web applications, databases, and operating systems". Ex - a user injected SQL queries to read unauthroised data from database or user inserted a javascript to read another user cookie details.
4. **Insecure Design** - issue at desgin level only like no otp or email verification on change password
5. **Security Misconfiguration** - Any secure confgiration issue at server level or cloud 
6. **Vulnerable & outdated components** - Like discussed on last blog, issue on OSS and known CVE.
7. **Identity & Authentication failure** - Seurity issue for login/authentication. ex - No projected for trying password again again if I know a username.
8. **Software & data Integrity failure** - Checking integrity of code & data corrcuption due to any security issues etc.
9. **Security Logging & monitoring failure** - Improper log for traceback
10. **Server side request Forgery** - It is a security vulnerability that occurs when an attacker is able to make requests from a server to other internal resources or external entities, typically in a way that the server does not intend. In SSRF attacks, the attacker can manipulate the server to perform requests on its behalf, potentially leading to unauthorized access to internal systems, data exposure . One ex - let's assume an attcker don't have access to internal system. He/she found SSRF issue in an application. Now using this application, the attcker can access internal system

------------
These top 10 list is important and many people ask in interview.
