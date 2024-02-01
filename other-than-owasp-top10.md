There are few more security issue mostly checked other than owasp top 10 as mentioned earlier.
1. Protect against file upload & download - check for virus in uploaded file, check if the uploaded file is allowed & not corrupted. check extesnion & content-type.
2. provide encrypted communication - use TLS (The HTTPS you see while browsing) - without that all your internet traffic can be seen by an attcker.
3. protcet from CSRF attack - CSRF, which stands for Cross-Site Request Forgery, is a type of security vulnerability that exploits the trust a web application has in a user's browser. In a CSRF attack, an attacker tricks a user's browser into making an unintended and unauthorized request on a web application where the user is authenticated. ex- u will receieve an email link and on click the link might send some money to attacker from your bank account. how to protect- include a random csrf token for each request
4. 
