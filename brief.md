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

## Cybersecurity

## Data

## Misconception in My Track

## Open Question
