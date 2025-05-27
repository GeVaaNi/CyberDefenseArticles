# Lumma Stealer Takedown Reveals Sprawling Operation

How "the world's most popular malware" was disrupted.



## What is Lumma Stealer

The Lumma Stealer is an information stealer written in C that was made available as MaaS (Malware-as-a-Service) since August 2022. The malware is said to be created by "Shamel" based in Russia. The main target of the Lumma Stealer are cryptocurrency wallets and 2FA browser extensions achieving the ultimate goal of stealing sensitive information. This data is then exfiltrated to a C2 server via HTTP POST requests using the user agent "TeslaBrowser/5.5". Data exfiltrated typically includes stolen credentials, financial data, and personal information or PII. 

According to ESET, the stealer malware is a very active service with 74 new domains emerging every week to host new parts of its infrastructure. Last year alone the authors deployed 3,353 unique command-and-control domains. According to the US Department of Justice, Lumma Stealer is not just in demand but is actually the most popular infostealer service available in Dark Web markets, responsible for 1.7 million known attacks against victims.



## A Coordinated response across the world

The disruption operation was a joined effort from entities around the world. Europol acted as the central point in Europe for the intelligence sharing and coordination. While in America, enterprises such as Microsoft, ESET, BitSight, Lumen Technologies, Cloudflare, CleanDNS, and GMO Registry, aided the FBI in the takedown. In the operation also participated Japan's Cybercrime Control Center (JC3). The takedown was led by Microsoft.

Via a court order granted in the United States District Court of the Northern District of Georgia, Microsoft’s DCU seized and facilitated the takedown, suspension, and blocking of approximately 2,300 malicious domains that formed the backbone of Lumma’s infrastructure. The [Department of Justice](https://www.justice.gov/opa/pr/justice-department-seizes-domains-behind-major-information-stealing-malware-operation) (DOJ) simultaneously seized the central command structure for Lumma and disrupted the marketplaces where the tool was sold to other cybercriminals. [Europol’s European Cybercrime Center](https://www.europol.europa.eu/media-press/newsroom/news/europol-and-microsoft-disrupt-world’s-largest-infostealer-lumma) (EC3) and Japan’s [Cybercrime Control Center](https://www.jc3.or.jp/) (JC3) facilitated the suspension of locally based Lumma infrastructure. 

Microsoft also identified over 394,000 Windows computers globally infected by Lumma Stealer. Together with law enforcement and industry partners, they have severed communications between the malicious tool and the victims. Moreover, more than 1,300 domains seized by or transferred to Microsoft, including 300 domains actioned by law enforcement with the support of Europol, will be redirected to Microsoft sinkholes. Sinkholing these domains to Microsoft's backend provides substantial visibility into active infections and will enhance the security of hundreds of thousands of compromised devices. 

This joined action is designed to slow the speed at which these threat actors can launch their attacks, minimize the effectiveness of their campaigns, and hinder their illicit profits by cutting a major revenue stream.



**https://blogs.microsoft.com/on-the-issues/2025/05/21/microsoft-leads-global-action-against-favored-cybercrime-tool/**

**https://www.darkreading.com/cybersecurity-operations/lumma-stealer-takedown-sprawling-operation**

**https://malpedia.caad.fkie.fraunhofer.de/details/win.lumma**

**https://www.europol.europa.eu/media-press/newsroom/news/europol-and-microsoft-disrupt-world%E2%80%99s-largest-infostealer-lumma**

**https://www.cybersecuritydive.com/news/microsoft-takedown-lumma-stealer/748727/**

**https://www.microsoft.com/en-us/security/blog/2025/05/21/lumma-stealer-breaking-down-the-delivery-techniques-and-capabilities-of-a-prolific-infostealer/**



### IoCs

| User-Agent| TeslaBrowser/5.5