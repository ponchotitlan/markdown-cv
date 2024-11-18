---
layout: cv
title: Alfonso Sandoval Rosas
---
# Alfonso Sandoval Rosas
B.Sc.Eng. Telematics. Network Automation and Orchestration. DevOps. Public Speaking. Developer Advocacy.

<div id="webaddress">
<a href="asandovalros@gmail.com">My email</a>
| <a href="https://github.com/ponchotitlan">My Github</a>
| <a href="https://www.linkedin.com/in/asandovalros/">My LinkedIn</a>
</div>


### Experienced in

Automated provisioning/orchestration/reconciliation of networking services

DevOps & NetDevOps design and tooling

Software development lifecycle with Agile methodologies

Software projects leadership, performing requirements gathering, systems design, code reviews, quality coding enforcement, SCM management

Technical Presentation for customer & academic contexts

Developer Advocacy in public events




## Professional experience

`2021 - now`
__Cisco Systems__, Lisbon
Software Consulting Engineer - SAO (Software & Orchestration)

Relevant projects:

_1) Firewall-Automation-as-a-Service platform_

Creation of a full-stack platform for the automated provisioning of security policies in the customer's Data Center. The firewalls within were from multiple vendors (Fortinet, Juniper, PaloAlto, Cisco). I fulfilled the role of Developer Lead for the southbound interface (devices configurations check, commit and rollback), including setup of development environment, DevOps pipeline for automated testing and artefact generation, code reviews, PR managing, pair troubleshooting and Day2 support. Our customer was able to drastically reduce the time for manual configuration of security policies in their brownfield network, as well as to mitigate human errors and discrepancies; everything while performing persona-based, end-to-end management of the requests. 

_Technologies used:_ Python, NETCONF and RESTCONF protocols, Robot Framework for testing, Jenkins for pipeline, Docker for staging environments, Redis and PostgreSQL databases, Github SCM.


_2) Network services reconciliation platform_

Creation of a CLI-based platform for the reconciliation of network services (ACLs, BGP, VRFs, etc) for a Service Provider. The platform would query the desired state configurations from an API and calculate the configuration deltas for each of the network routers involved. The user could determine wether to enforce the reconciliation of these deltas or not. I fulfilled the role of Developer Lead for the integral testing and delivery of this solution. Our customer was able to perform the reconciliation process in a quick and automated manner, complying with a tight schedule of maintenance windows for their production network.

_Technologies used:_ Python, requests module for API querying, NETCONF and RESTCONF protocols, Robot Framework for testing, Gitlab Runner for pipeline, Docker for staging environments, Gitlab SCM.


_3) Network status dashboard on-the-go_

Creation of a multi-container application for visualization of network devices status - Memory usage, vendor information, software version, historical benchmarks on specific features. The information is queried via a Cisco RADKit agent integrated into a web server container. This container pushes historical data into a database one. Finally, a visualisation container queries both containers for the population of charts and graphs. I fulfilled the role of solo Developer of this application, working side by side with a Network Engineer to fulfill all the visualisation and query needs for multiple customers. Several customers are using this solution and adapting it to their needs.

_Technologies used:_ Python, FastAPI, InfluxDB, Grafana, Docker, Docker-Compose, Cisco RADKit, Gitlab SCM.



`2016 - 2021`
__Cisco Systems__, Mexico City
Collaboration Consulting Engineer - VoIP and Video

Relevant projects:

_1) Contact Center Conversational Experiences integration framework_

Creation of a middleware server for the integration of Cisco Contact Center workflows with Google DialogFlow conversational agents. The developer would be able to code small plugins in NodeJS to incorporate into this middleware. These plugins would allow the querying of existing Google DialogFlow agents using the pre-trained conversations and available locales for voice. The calling user would be able to interact with their voice during the call. I fulfilled the role of Developer Lead for the design and implementation of the middleware, as well as the training of the Google DialogFlow agents and Cisco Contact Center workflow design. Our customer bosted the productivity of their contact center by applying this solution on specific Use Cases which could be easily addressed with serf-service, releasing human agents for more critical calls.

_Technologies used:_ NodeJS, Cisco Contact Center Express, Google DialogFlow ES


_2) Contact Center Multi-Channel Dunning platform_

Creation of a contact center agent portal for the dunning of customers through different integrated channels. The agent would be able to send alerts to a specific user via SMS texts, email and robo-calls. Additionally, the administrator would be able to setup policies and templates for these messages to be triggered under specific criteria (Ex. client in debt template email after X amount of days with a payment overdue). I fulfilled the role of solo developer for the design and implementation of the solution, working side by side with a Contact Center engineer to create the integration of both systems. Our customer was able to release their agents from these tasks so they could focus on more critical activities.

_Technologies used:_ NodeJS, Cisco Contact Center Express



## Education

`2010-2015`
__Instituto Politécnico Nacional, Mexico__
B.Sc.Eng. Telematics.

Thesis project: ["Videoconference System Based on WebRTC With Access to the PSTN (ES)"](https://www.slideshare.net/slideshow/sistema-de-videoconferencia-basado-en-webrtc-con-acceso-a-la-pstn-56562444/56562444)

`2014`
__Universidad Politécnica de Madrid, Spain__
ERASMUS.



## Skills

### Spoken languages (CEFR scale)

**Spanish.** Native

**English.** C2 Proficiency on all skills

**Portuguese.** C1 Proficiency on all skills

**French.** B2 Proficiency on all skills


### Computing

Network Automation and Orchestration - NETCONF, RESTCONF protocols. YANG modelling language

DevOps design and tooling - Jenkins, Gitlab Runners, Github Actions, jFrog

NetDevOps - Cisco NSO (Network Services Orchestrator), Ansible

Programming languages - Python, Java, JS

Databases - SQL, Document, Key-value, Time series. MySQL, PostgreSQL, MongoDB, InfluxDB, Redis engines

Containerised applications with Docker

Software testing - Robot framework

Web development - MEAN stack

Data visualization - TIG stack


### Certifications

Cisco Certified DevNet Specialist - DevOps

AWS Certified Cloud Practicioner

ITIL4 Foundation CPD



## Speaker sessions in Technical Events

**[WITCOM 2024 - Puerto Vallarta (ES)](https://github.com/ponchotitlan/witcom-2024-code-is-the-new-cli)**:

"Code is the new CLI. Network Programmability and beyond"


**[Open Source Summit Europe 2024](https://www.youtube.com/watch?v=qcl2sYVTo8M&list=PLbzoR-pLrL6rC7SpO7MJCZm22Qp5ns3p-&index=49&ab_channel=TheLinuxFoundation)**: 

"Data Networks Neutrality with OpenConfig: Unveiling Challenges and Practical Insights"


**[DevOps Pro Europe 2024](https://devopspro.lt/devops-pro-europe-2024/)**:

"Taming your Data Networks with the power of NetDevOps"


**[Cisco Live Amsterdam 2024](https://www.ciscolive.com/on-demand/on-demand-library.html?search=%22Alfonso%20Sandoval%20Rosas%22#/session/1707505612413001pTAA)**:

"Embracing DevOps for my NSO Use Cases lifecycle"


**[Developer Days Automation 2023](https://www.youtube.com/watch?v=nnjzu57vI3g&t=634s&ab_channel=CiscoNSODeveloperHub)**:

"The quest for DevOps utopia in NSO Land - Tips & tricks for the ideal strategy"


**[Cisco Live Las Vegas 2022](https://www.ciscolive.com/on-demand/on-demand-library.html?search=alfonso#/session/1675722411262001tQK7)**:

"“Hello! How can I help you today?” Conversational Experiences in our Contact Center with Google DialogFlow and the Power of Code"


**[Developer Days Automation 2022](https://www.youtube.com/watch?v=0bWm1q6V0qM&ab_channel=CiscoNSODeveloperHub)**:

"Enhanced Compliance Reporting: A development journey"


**[Cisco Community Talks (ES)](https://community.cisco.com/t5/eventos-general/devnet-en-acci%C3%B3n-tips-temas-claves-y-mejores-pr%C3%A1cticas-cl-evento/ba-p/4310121?utm_campaign=cl-sp-devent-comienzo-mar2021&utm_medium=referral&utm_source=sm)**:

"DevNet en acción: Tips, temas claves y mejores prácticas"


**[Cisco DevNet Create 2020](https://www.youtube.com/watch?v=zHOUyR3kKrE&ab_channel=CiscoDevNet)**:

"Cisco Multi-Channel Campaign Manager: Innovating Our Customer Contact for Potential Markets"




## Volunteering

**[NOVA Universidade de Lisboa - Faculdade de Engenharia (PT)](https://github.com/ponchotitlan/NOVA_code_is_the_new_CLI):** 

"Code is the new CLI" masterclass for the students of Computer Science & Telecom degrees


**[IST - Instituto Técnico Superior de Lisboa (PT)](https://github.com/ponchotitlan/NOVA_code_is_the_new_CLI):** 

"Code is the new CLI" masterclass for the students of Computer Science & Telecom degrees


**DevNet Programming Club (Admin, Mentor and Trainer)**

The DevNet Programming Club was a initiative with the purpose of empowering the community to bring their digital ideas to life with the power of code. The Club delivered well-defined live sessions on specific coding topics, as well as close mentoring and an open space for support on coding-related questions




## Publications

**[Electronic Notes in Theoretical Computer Science](https://www.sciencedirect.com/science/article/pii/S1571066116301141):**

"Videoconference System Based on WebRTC With Access to the PSTN"




<!-- ### Footer

Last updated: November 2024 -->
