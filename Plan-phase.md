**Threat Modeling**
1. In the Plan phase of SDOL, we talked about Threat Modelling. Now let's explore the same with more details.
2. Threat modeling is the process of figuring out how a hacker/attacker might try to attack, and then making a plan to stop them.
3. Definition - "Threat modeling is a structured approach to identifying, assessing, and mitigating potential security threats in a system or application. It is a proactive process that helps organizations understand and address potential vulnerabilities before they can be exploited by attackers".
--------------------------------
Let's Understand what is difference between Threat & risk from a real word scenario.
1. Threat is Tsunami
2. Vulnerability (weakness) - Poor Infrastucture
3. Risk - costal flooding and property damage
   
So, if we see this risk before hand than we can plan for warning systems, evacuation plans, and building structures to protect the Vulnerability (weakness) being exploited.

In Software world, let's take the below example

1. Threat - Virus infection for a Bank server
2. Vulnerability (weakness) - Running outdated windows system
3. Risk - Unauthroized access & Data theft

Here, if we have control like antivirus software the issue would authomatically get handled

Another example - Let' say there is an application where there are 2 kind of user role. 1 is **admin** who has privilege to perform any kind of task like password reset or view personal data like mobile number or address of other users. Another role is **normal user** who has privile to only accces it's own data.

1. Threat - Privilege Escalation (the attempt to gain higher-level access)
2. Vulnerability - poorly configured access control or weak authentication (login) mechanism
3. Risk: Unauthorized Access to Sensitive personal Data (the potential harm or consequence of the threat)

To mitigate the risk of privilege escalation, the developers should implement proper access controls and authentication mechanisms. This includes assigning minimal necessary privileges to each user role, regularly reviewing and updating user privileges, and conducting security audits to identify and address any vulnerabilities that could be exploited for privilege escalation. Additionally, implementing multi-factor authentication (OTP verifiction for login)

-----------------------------
To Summarize, In Threat Modeling we perform below task. This is a group activity and partcipant are mostly Developer, Product Manager, Secuirty Professionals, Architect etc. Steps are as below

1. Asset Identification: Identify the assets that need protection, such as sensitive data, hardware (server), software, and other things.
2. Identifying Threats
3. Vulnerability Analysis: Evaluate the weaknesses and vulnerabilities in the system that could be exploited by potential threats
4. Risk Assessment: Now analyze the risk if crticality is high, medium, low based on impact and prioritize fix based on that
5. Mitigation Strategy


