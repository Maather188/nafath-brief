Version: NAFATH-V4
Track: Cybersecurity

## Overview
A national service provider uses different IT fields to provide safe and reliable services. Software runs the systems, while artificial intelligence (AI) models analyze data and help people make decisions. Mobile apps allow users to access these services, and networks transfer data between users, systems, and servers. Cybersecurity protects these parts from unauthorized access and secret changes. Data analysis helps find unusual patterns that may show a security risk. These fields are closely connected because a problem in one field can affect the others. For example, hacked software can expose private information, changed AI models may give wrong results, and changed internet routes may send communications to the wrong place. Therefore, the provider must protect its software, AI models, data, and network connections. It is also important to understand how unauthorized changes to AI models can be detected before they affect national services.


## Software
According to the Twelve-Factor App methodology, configuration and secrets should be stored in environment variables, separate from the application code. They should not be stored in the code because configuration varies between deployments, while the code remains the same. Keeping secrets out of the code reduces the risk of exposing credentials in a code repository. Environment variables can also be changed without modifying the application code.

Resource: The Twelve-Factor App - III. Config - https://12factor.net/config

## AI
Adversarial attacks on machine learning systems can occur during training or deployment. Poisoning attacks occur during training when attackers modify training data, labels, model parameters or algorithms. Evasion attacks occur during deployment when attackers modify test samples to change the model’s predictions. Privacy attacks aim to infer sensitive information about training data or the model, including through membership inference and data reconstruction. These attacks differ in their timing, methods and objectives.

Resource: NIST - Adversarial Machine Learning: A Taxonomy and Terminology of Attacks and Mitigations - https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-2e2025.pdf

## Mobile
The OWASP Mobile Application Security Verification Standard (MASVS) is a security standard developed by OWASP to assess and improve mobile application security. It provides security controls that developers and testers use as a baseline to verify an app’s security, identify weaknesses and protect sensitive user data. Organizations can apply these controls throughout development and testing to reduce security risks and increase confidence in the application’s security.

Resource: OWASP - Mobile Application Security Verification Standard (MASVS) - https://mas.owasp.org/MASVS/

## Networking
BGP route hijacking occurs when an autonomous system (AS) announces an IP prefix it is not authorized to originate. If other networks accept the false announcement, they may redirect traffic to the hijacking AS instead of the legitimate destination. RPKI helps prevent this through Route Origin Authorizations (ROAs), which allow routers to check whether the originating AS is authorized. However, origin validation does not verify the complete AS path or prevent all path-manipulation attacks.

Resource: NIST - Resilient Interdomain Traffic Exchange: BGP Security and DDoS Mitigation - https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-189.pdf

## Cybersecurity
Log4Shell (CVE-2021-44228) was a remote code execution vulnerability in Apache Log4j 2, a widely used Java logging library. It was rated critical because attackers could exploit vulnerable systems remotely to execute malicious code and potentially take full control. The vulnerability was fixed by upgrading affected Log4j versions to patched releases. Organizations should also identify affected systems, apply updates, and investigate possible exploitation.

Resource: CISA - Mitigating Log4Shell and Other Log4j-Related Vulnerabilities - https://www.cisa.gov/news-events/cybersecurity-advisories/aa21-356a

## Data
An SBOM is a nested inventory, a list of ingredients that make up software applications and systems . It helps organizations identify vulnerabilities and manage software supply chain risks. According to the 2026 guidance, its minimum data fields include component name, producer, version, identifiers, dependencies, hash value and algorithm, license, SBOM author and signature, timestamp, data format and version, generation context, tool name and version, and SBOM version.

Resource: Australian Cyber Security Centre (ACSC) - 2026 Minimum Elements for a Software Bill of Materials (SBOM) - https://www.cyber.gov.au/publication/2026-minimum-elements-for-a-software-bill-of-materials-sbom


## Misconception in My Track

## Open Question
