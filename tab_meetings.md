---
title: meetings
displaytext: Chapter Meetings
layout: null
tab: true
order: 2
tags: belgium
---
## OWASP Belgium Chapter Meeting 2023

## October 17th:
We are please to welcome Asuman Senol and Georges Bolssens. 
This meeting is co-located with the [CyberSecurity event "Strategic Rsearch and Industry Impact"](https://cybersecurity-bites.be/cybersecurity-strategic-research-industry-impact-2nd-edition/)

### Agenda:
* 18h15-19h00: Welcome and refreshments
* 19h00-19h10: **OWASP Update**
* 19h10-19h50: **Leaky Forms: A Study of Email and Password Exfiltration Before Form Submission** by Asuman Senol (Privacy Researcher at COSIC, KU Leuven BE)
* 19h50-20h30: **Cyber breaches and how to prevent them** by Georges Bolssens (Principal Consultant at Toreon) 

### Leaky Forms: A Study of Email and Password Exfiltration Before Form Submission 
Web users enter their email addresses into online forms for a variety of reasons, including signing in or signing up for a service or subscribing to a newsletter. While enabling such functionality, email addresses typed into forms can also be collected by third-party scripts even when users change their minds and leave the site without submitting the form. Email addresses—or identifiers derived from them—are known to be used by data brokers and advertisers for cross-site, cross-platform, and persistent identification of potentially unsuspecting individuals. In order to find out whether access to online forms is misused by online trackers, we present a measurement of email and password collection that occurs before the form submission on the top 100,000 websites. We evaluate the effect of user location, browser configuration, and interaction with consent dialogs by comparing results across two vantage points (EU/US), two browser configurations (desktop/mobile), and three consent modes. Our crawler finds and fills email and password fields, monitors the network traffic for leaks, and intercepts script access to filled input fields. Our analyses show that users’ email addresses are exfiltrated to tracking, marketing and analytics domains before form submission and without giving consent on 1,844 websites in the EU crawl and 2,950 websites in the US crawl. While the majority of email addresses are sent to known tracking domains, we further identify 41 tracker domains that are not listed by any of the popular blocklists. Furthermore, we find incidental password collection on 52 websites by third-party session replay scripts. 

### Asuman Senol
Asuman Senol is a last year PhD student at COSIC under the supervision of Assistant Prof. Gunes Acar and Prof. Claudia Diaz. She works on online tracking and web privacy. Her research involves conducting large-scale web measurement studies to investigate privacy and security issues on the Web. Before starting her doctoral studies, she worked as a full-stack web developer for 5 years. She contributes to various open source software projects thanks to her background in the industry and current academic interests in privacy and security.

### Cyber breaches and how to prevent them
 This talk explains the common threats for software applications from an attacker point of view, by using real-world data breaches and what the attacked companies could have done to prevent it.

We have selected breaches of which technical details are well understood, so we can use them as case studies, which we will approach using the following questions:
* What happened?
* Why did this happen?
* What were the consequences?
* How can you prevent it?

### Georges Bolssens
Georges Bolssens embarked on his coding journey in the early 1990s and delved into the realm of application security in 2017. With an inherent passion for teaching, Georges is not only a seasoned developer but also an adept communicator. His unique talent lies in simplifying intricate subjects through relatable analogies, making him an engaging and effective speaker.

Having undertaken numerous consulting assignments, Georges has assumed the role of a cybersecurity educator for a diverse spectrum of professionals. His guidance has illuminated the path for individuals ranging from legal experts at renowned "Big 4" consulting firms to ethical hackers and all those in between.

In his capacity as an Application Security Consultant at Toreon, Georges has been instrumental in assisting numerous clients in constructing comprehensive threat models for their digital assets. His expertise and commitment led to his appointment as a co-instructor for Toreon's distinguished "Advanced Whiteboard Hacking – a.k.a. Hands-on Threat Modeling" course. Notably, he co-taught this course at the esteemed "BlackHat USA" conference in 2023.


## OWASP BeNeLux Days 2023 (November 23-24)
We are proud to announce the next edition of OWASP BeNeLux Days! The event will take place on 23 and 24 November 2023, in Hasselt (BE)

The OWASP BeNeLux Days 2023 consist of 2 days. On Thursday November 23th, we have a full day conference program with a list of renowned speakers. On Friday November 24th, you can join 1 of the free trainings.

For further info and registration, we kindly refer you to: <https://owaspbenelux.eu>.


# OWASP Belgium Chapter Meeting 2022

## November 24-25th, 2022, Tilburg (NL)
Join us in Tilburg for the 2022 version of [Owasp BeNeLux days](https://owaspbenelux.eu).


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
Victor Le Pochat is a PhD researcher in the area of web security and privacy at the imec-DistriNet research group at KU Leuven in Belgium. His interests lie in the exploration of web ecosystems through large-scale measurements, and in web security and privacy research methodology, both analyzing and improving current research practices. Follow [@VictorLePochat](https://twitter.com/VictorLePochat) on Twitter.


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
