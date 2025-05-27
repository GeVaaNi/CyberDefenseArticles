# Employees Searching Payroll Portals on Google Tricked Into Sending Paychecks to Hackers

A new SEO (Seach Engine Optimization) poisoning technique has been exposed by Threat Hunters from ReliaQuest. This technique was seen targetting employee mobile devices and facilitate payroll fraud.

### SEO poisoning

The technique uses a fake login page impersonating the organization's login page to access the employee payroll portal and redirects paychecks into accounts under the threat actor's control. The attacker infrastructure uses compromised home office routers and mobile networks to mask the traffic. Using the stolen credentials, the attacker gains access to the payroll portal and changes direct deposit information.



### Attack chain

It all starts with a phishing campaign leading to a fake wordpress page mimicking a Microsoft login portal when visited from a mobile device. The credentials are then sent to and attacker-controlled website, while also establishing a two-way WebSocket connection in order to alert the threat actor of new stolen passwords.

Attacking mobile devices gives another advantage as they lack enterprise-grade security measures effectively reducing visibility and hampering investigation efforts.

The malicious login attempts was seen originating from home office routers and other residential IP addresses. Once again showing the increasing concern of exploitable weaknesses in these network devices which are also often infected with malware to enlist them into proxy botnets. These residential IP address are harder to detect as malicious unlike VPNs that are often flagged because of previous misuse. On top of that, using proxy networks allows the attacker to originate its malicious traffic from the same geolocation as the targeted organization.



### Detection

The detection comes from uncovering a phishing campaign using the W3LL phishing kit. This again shows the importance of good phishing detection capabilities and awareness.

