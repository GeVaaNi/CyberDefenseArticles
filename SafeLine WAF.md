# SafeLine WAF

Open Source Web Application firewall with Zero-Day detection and Bot protection

With an increasing demand for high quality and user-friendly WAF solutions, SafeLine is an excellent choice. It is a self-hosted web application firewall that acts as a reverse proxy, filtering and monitoring HTTP/HTTPS traffic to block malicious requests before they reach your backend web applications. It provides the following key features:

#### Comprehensive Attack Prevention

Effectively blocking a wide range of common and advanced web attacks including but not limited to:

- XSS
- SQLi
- Directory traversal
- XXE
- CRLF



#### Zero-Day Detection via Semantic Analysis

SafeLine uses a patented semantic analysis engine that deeply parses HTTP traffic semantics with an industry-leading detection rate of 99.45% and an ultra-low false positive rate of 0.07%.



#### Robut Bot Protection

The rise of bot attacks results in a growing of attack vectors such as credential stuffing, malicious scraping, vulnerability scanning, ... SafeLine includes a multi-layered defense against these attacks:

- CAPTCHA challenges to distinguish humans from bots
- Dynamic protection by randomly obfuscating frontend code before delivering to the client
- Anti-Replay Mechanism detecting and blocking the reuse of tokens, headers, or payloads in scripted attacks.



#### HTTP Flood DDoS mitigation

It uses **rate limiting** to cap request frequency and mitigate abuse. For sudden traffic spikes, SafeLine provides a **virtual waiting room** that ensures service availability by queuing excess users and releasing them gradually. These measures are highly configurable.



#### Authentication Challenges

Designed with the Zero-Trust principle --never trust, always verify-- SafeLine offers configurable visitor authentication as a built-in identity gateway supporting modern authentication protocols such as OIDC and integrating with popular identity providers. On top of that, SSO is supported all for free.