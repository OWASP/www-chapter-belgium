---
title: meetings
displaytext: Chapter Meetings
layout: null
tab: true
order: 2
tags: belgium
---
# Upcoming OWASP Belgium Chapter Meetings
## June 2nd, 2026 @KU Leuven (Heverlee)
Hosted by [DistriNet Research Group (KU Leuven)](https://distrinet.cs.kuleuven.be/)

Jim is faculty of the [Secure Application Development (SecAppDev) course ](https://www.secappdev.org/) held in Leuven from 2026-06-21 to 2026-06-05.

### Location
KU Leuven Dept. Computer Science (Auditorium A.00.225)
Celestijnenlaan 200A
3001 Heverlee


### Agenda

* 17:45 - 18:30 : Welcome (drinks + sandwiches)
* 18:30 - 18:40 : **OWASP update**
* 18:40 - 19:40 : **Secure Coding with AI: Building Safer Software with Claude Code and Codex** (by Jim Manico, Manicode Security)
* 19:40 - 19:50 : break
* 19:50 - 20:50 : **The Vulnpocalypse is hitting the physical realm: Reverse-engineering IoT devices with open source tooling and LLMs** (by Georges Bolssens, Toreon)

### Registration
Our chapter meetings are open for everyone, and attendance is free of charge. We ask you to [register via the OWASP Belgium Meetup group](https://www.meetup.com/belgium-owasp-meetup-group/) in order to provide you with last-minute updates, if needed.

RSVP chapter meeting: <https://www.meetup.com/belgium-owasp-meetup-group/events/314842473/>

### Secure Coding with AI: Building Safer Software with Claude Code and Codex
***Abstract:***
AI coding assistants are rapidly changing how software is built, but they also introduce new security risks when used without proper controls and guidance. In this practical, demo-driven session, Jim Manico will demonstrate how to use modern AI coding tools securely and effectively. The talk covers setting up a secure Claude Code environment, applying secure coding prompts based on OWASP guidance, and using Claude Code and Codex together for development, review, and testing workflows. Attendees will learn practical techniques for improving software security while accelerating development with AI-assisted coding.

***About Jim:***
Jim Manico is the founder of Manicode Security and a longtime application security educator with more than 25 years of software development and security experience. Jim is a frequent international speaker on secure software practices, a former member of the OWASP Global Board of Directors, and a contributor to several OWASP projects including the AISVS and Cheat Sheet Series. He is the author of Iron-Clad Java: Building Secure Web Applications and has trained developers at Fortune 500 companies, financial institutions, and government organizations worldwide.

### The Vulnpocalypse is hitting the physical realm: Reverse-engineering IoT devices with open source tooling and LLMs 
***Abstract:*** Skeptical at first, I started looking into how well an LLM would do in reverse-engineering the firmware of cheap IoT hardware, gating slop-submissions by having a hard rule on "PoC||GTFO". The case study running through the talk is a coordinated-disclosure project against a €30 WiFi extender, with the end result (much to my own surprise) being an automatable set of 0-days that ultimately led to the manufacturer issuing 4 CVEs. Chained together, they lead to interception of all internet traffic for all downstream users. The scary part is that all I had to do was chat to Claude, reboot the device when asked, and validate the PoCs: in other words, I was the QA-reviewer for a pentester that never sleeps.

We will be discussing the technicalities and lessons-learned so attendees can build this kind of setup themselves, but also open the discussion of how this new paradigm democratizes penetration testing. It also looks at how device manufacturers are going to have to deal with this looming tsunami of incoming bug reports and how new EU legislation will squeeze them from the other end into forced rapid response. 


***About Georges:*** Georges' lifelong curiosity about 'how stuff works' culminated in a Master’s degree in Electro-Mechanical Engineering. With over 15 years of experience in technical and managerial roles within the biotech industry, he developed a deep proficiency in programming and a passion for cybersecurity.

This unique combination of engineering logic and coding expertise makes Georges an ideal Application Security expert; he relates to the daily challenges of software developers while fully understanding the adversarial mindset of hackers. Since transitioning to AppSec in 2017, he has consulted for a wide variety of business contexts.

Georges joined Toreon in 2021, where he currently serves as the Product Owner for Threat Modeling Consulting. He is also the Lead Trainer for Toreon’s globally recognized 'Whiteboard Hacking' training. Leveraging his background in electronics, Georges is a key member of the hardware penetration testing team, with specific expertise in threat modeling for embedded medical and non-medical devices.


# Past OWASP Belgium Chapter Meetings
## April 29th, 2026 @KdG (Antwerp)

Karel de Grote Hogeschool in Antwerp has kindly invited us to host a chapter meeting at their Groenplaats campus again this year, and we're happy to accept their invitation.

This chapter meeting will have a pentest theme, with renowned penetration testers Louis Nyffenegger (Pentesterlabs) and Robbe Van Roey (Toreon) joining us to share their experience.

### Location:
KDG Campus Groenplaats
GR-217 (second floor)
Nationalestraat 5
2000 ANTWERPEN

Note: Another event will take place at the same evening (Girls in ICT), 
while you are free to attend that one too, we're hosting the OWASP meetup in GR-217 on the second floor.

### Agenda

* 17:30 - 18:00 : Welcome (drinks + sandwiches)
* 18:00 - 18:10 : **OWASP update**
* 18:10 - 19:00 : **I don't like this code!** (by Louis Nyffenegger , pentesterlabs)
* 19:00 - 19:10 : break
* 19:10 - 20:00 : **Hacking Browsers: The Easy Way** (by Robbe Van Roey, Toreon)
* 20:00 - 20:30 : Refreshments

### I don't like this code!
***Abstract:*** You have probably seen plenty of talks about amazing vulnerabilities where the code is either horrendous, or it feels like the presenter dug deep into the perfect rabbit hole. The secret behind many of these stories is simple: once you have read enough code, you know exactly what to investigate. Your spidey sense starts tingling.

In this session, we turn that feeling into a game! We will walk through a series of real-world inspired code snippets and give you one minute to tell us why we do not like this code. Then we will break down, point by point, what feels wrong, what is risky, and how it could fail in practice. By the end, you will leave with a reusable mental checklist for "I don't like this code" moments and a more systematic approach to security code review.

***About Louis:*** Louis Nyffenegger is an experienced speaker who has delivered talks and training at major security events worldwide. His sessions focus on web application security, vulnerability research, and advanced code review techniques.

![Profile picture of Louis](assets/images/Speaker%20pictures/profilepicture_LouisNyffenegger.jpeg)

### Hacking Browsers: The Easy Way
***Abstract:*** When you think of hacking browsers, you perhaps think of V8 heap exploitation, deep-dive fuzzing, crazy sandbox escapes, and so on. But what if I told you that you can still find vulnerabilities in major browsers that don’t require any technical knowledge? Bugs you can even run into by accident!
In this talk, I’ll take you through my journey of how I “accidentally“ found a vulnerability in Google Chrome. And how that led me to find more vulnerabilities in Chrome as well as some vulnerabilities in Mozilla Firefox and many more bugs in other products.
So if you’re keen to find out how I could, with minimal user-interaction, steal your private GitHub repositories, then this talk is for you!

***About Robbe:*** Hi! I’m Robbe Van Roey 👋
I’m a hacker. I like breaking stuff. I’m a penetration tester at Toreon, I’ve worked for a bug bounty company, and I’ve found 35+ CVEs. I love hacking web apps, mobile applications, AI systems, and Active Directory.
I’m also a teacher. I teach developers about secure coding, I teach beginners about Red Teaming for Hack The Box and I’ve created a bunch of YouTube videos on my channel.
In the online realm, you may know me as PinkDraconian. Come up to me and say hi!
My life motto is “Hacking you so you don’t get hacked“ and I’d like to show you part of that ideology during my talk. See you there!

![Profile picture of Robbe](assets/images/Speaker%20pictures/profilepicture_RobbeVanRoey.png)
