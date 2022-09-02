---
title: meetings
displaytext: Chapter Meetings
layout: null
tab: true
order: 2
tags: belgium
---
## OWASP Belgium Chapter Meeting 2022

## September 13th:
We are please to welcome Victor Le Pochat and Philippe Bogaerts.
This meeting is co-located with the [CyberSecurity event "Strategic Rsearch and Industry Impact"](https://cybersecurity-bites.be/cybersecurity-van-onderzoek-tot-industrie-impact/)

### Agenda:
* 18h15-19h00: Welcome and refreshments
* 19h00-19h10: **OWASP Update**
* 19h10-20h00: [A hacker’s view on #containers and #K8S by Philippe Bogaerts](#a-hackers-view-on-containers-and-k8s)
* 20h00-20h10: ***Break***
* 20h10-21h00: [An Audit of Facebook's Political Ad Policy Enforcement by Victor Le Pochat](#an-audit-of-facebooks-political-ad-policy-enforcement)

### A hacker’s view on #containers and #K8S
Kubernetes and the eco-systems around are fundamentally complex systems with lots of different potential attack vectors aimed at data theft, currency mining and other threats.  The attack surface is immense.\
Current legacy security controls do not offer an acceptable level of protection anymore. By looking at the problem from different angles, we’ll discuss the key concepts of container and Kubernetes security to better and reliably protect our applications, workloads and clusters.

### Philippe Bogaerts
Philippe brings more than 20+ years of experience in security. Starting out as a trainer specializing in advanced TCP/IP protocols, networking and security, Philippe quickly became known by colleagues as “Philippe hacks to learn”.\
Being a pioneer in network firewall, reverse proxy and load-balancing, Philippe later on specialized in web application security with a focus on penetration testing and web application firewalling.\
About 6 years ago, containers and orchestration grabbed his attention and started researching (mostly as a hobby), the architecture and security aspects of these new emerging technologies.\
Today, Philippe contributes mostly by writing [blog posts](https://xxradar.medium.com), talking at meetups as well as co-organizing a [renowned security conference](https://brucon.org).\
During daytime, Philippe is a solution architect focusing on AWS, Kubernetes and cloud protection.

### An Audit of Facebook's Political Ad Policy Enforcement
Major technology companies strive to protect the integrity of political advertising on their platforms by implementing and enforcing self-regulatory policies that impose transparency requirements on political ads. In this paper, we quantify whether Facebook’s current enforcement correctly identifies political ads and ensures compliance by advertisers. In a comprehensive, large-scale analysis of 4.2 million political and 29.6 million non-political ads from 215,030 advertisers, we identify ads correctly detected as political (true positives), ads incorrectly detected (false positives), and ads missed by detection (false negatives).\
Facebook’s current enforcement appears imprecise: 61% more ads are missed than are detected worldwide, and 55% of U.S. detected ads are in fact non-political. Detection performance is uneven across countries, with some having up to 53 times higher false negative rates among clearly political pages than in the U.S. Moreover, enforcement appears inadequate for preventing systematic violations of political advertising policies: for example, advertisers were able to continue running political ads without disclosing them while they were temporarily prohibited in the U.S. We attribute these flaws to five gaps in Facebook’s current enforcement and transparency implementation, and close with recommendations to improve the security of the online political ad ecosystem.

### Victor Le Pochat
Victor Le Pochat is a PhD researcher in the area of web security and privacy at the imec-DistriNet research group at KU Leuven in Belgium. His interests lie in the exploration of web ecosystems through large-scale measurements, and in web security and privacy research methodology, both analyzing and improving current research practices. [@VictorLePochat on Twitter](https://twitter.com/VictorLePochat)


## June 14th:
For this ON-SITE chapter meeting, we have scheduled Isabelle Mauny and Abhay Bhargav.

Both speakers are faculty of the [Secure Application Development (SecAppDev 2022)](https://secappdev.org/) course held in Leuven from 2022-06-13 to 2022-06-17.

### Agenda:

* 18h15-19h00: Welcome and refreshments
* 19h00-19h10: **OWASP Update**
* 19h10-20h00: [Top 5 of recent API Breaches - What can we learn from them? by Isabelle Mauny](#top-5-of-recent-api-breaches---what-can-we-learn-from-them)  - [Check out the PDF](assets/2022/2022-06-14/OWASP-Belgium-APISecurity.pdf)
* 20h00-20h10: ***Break***
* 20h10-21h00: [The Call is coming from inside: Post-exploitation Scenarios with Kubernetes Webhooks by Abhay Bhargav](#the-call-is-coming-from-inside-post-exploitation-scenarios-with-kubernetes-webhooks)

### Top 5 of recent API Breaches - What can we learn from them?
We will outline the root causes of some recent API vulnerabilities making the news.
* A detailed look at the underlying OWASP API security Top 10 flaws.
* Explain of how the vulnerability occurred and what we could have done to prevent it.

#### Isabelle Mauny's bio (Field CTO, 42Crunch)
 I have been spending the last 15 years helping people integrate their applications internally and externally. I introduced IBM DataPower in Europe in 2005 and worked with numerous enterprises customers deploying what were the first API Gateways. I have stayed in that field since then, with a stronger focus on security in the past 5 years with 42Crunch.

### The Call is coming from inside: Post-Exploitation Scenarios with Kubernetes Webhooks
Admission Controllers are an integral part of Kubernetes Security. Specifically, Access Control. These take the form of mutating and validating web-hooks. Kubernetes clusters use these webhooks to enforce/mutate security policy checks.\
Everything from security context to memory limits can be enforced through the use of these webhooks. However, attackers can leverage custom-built webhooks as a way of maintaining persistence in an exploited Kubernetes cluster.\
 In this talk, I will detail the admission controller implementation in Kubernetes. I will build and deploy both mutating and validating, malicious webhooks to a cluster to demonstrate a bevy of post-exploit persistence approaches that one can leverage, entirely using Kubernetes webhooks.

#### Abhay Bhargav's bio (CEO, AppSecEngineer)
Abhay Bhargav is the Founder of we45 and AppSecEngineer. He has created some pioneering works in the area of DevSecOps and AppSec Automation, including the world’s first hands-on training program on DevSecOps. In addition to this, Abhay is active in his research of new technologies and their impact on Application Security.\
Abhay is a speaker and trainer at major industry events including DEF CON, BlackHat, OWASP AppSecUSA, EU and AppSecCali. His trainings have been sold-out events at conferences like AppSecUSA, AppSecDay Melbourne, CodeBlue, BlackHat and so on.



## May 17th 2022:
### Securing a World of Physically Capable Computers by Bruce Schneier
#### Abstract:
Computer security is no longer about data; it’s about life and property. This change makes an enormous difference, and will shake up our industry in many ways.\
First, data authentication and integrity will become more important than confidentiality. And second, our largely regulation-free Internet will become a thing of the past. Soon we will no longer have a choice between government regulation and no government regulation. Our choice is between smart government regulation and stupid government regulation.\
Given this future, it’s vital that we look back at what we’ve learned from past attempts to secure these systems, and forward at what technologies, laws, regulations, economic incentives, and social norms we need to secure them in the future.

#### Bio:
Bruce Schneier is an internationally renowned security technologist, called a “security guru” by the Economist. He is the New York Times best-selling author of 14 books – including * Click Here to Kill Everybody* – as well as hundreds of articles, essays, and academic papers.\
His influential newsletter Crypto-Gram and blog Schneier on Security are read by over 250,000 people. Schneier is a fellow at the Berkman-Klein Center for Internet and Society at Harvard University, a Lecturer in Public Policy at the Harvard Kennedy School, a board member of the Electronic Frontier Foundation and AccessNow, and an advisory board member of EPIC and VerifiedVoting.org.\
He is the Chief of Security Architecture at Inrupt, Inc.
