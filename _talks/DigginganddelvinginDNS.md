---
layout: talks
title: Digging and delving in DNS
length: 20
keynote: false
scheduled: "15:20"
card: DiggingAndDelvinginDNS.png
video: https://www.youtube.com/watch?v=4rbPPgi8gOg
speakers:
- name: Barry Irwin
  image: BarryIrwin.jpg
  bio: |
    Barry Irwin started off as a Systems and Network administrator at the dawn of the millennium and tripped and fell into the security field. Finding nothing on the market that met the operational needs, he led the development and deployment of an open-source derived firewalling system in the early 2000’s for a global telecoms operator. He returned to academia and has spent the last 19 years working in academia on research in the larger information security field, often returning to his first love of packets and network traffic analysis.
    He has significant experience in, and a passion for training the next generation of security professionals within academia and a cross section of public and private sector industry. 
    
    His current areas of research include network traffic analysis, data visualisation, web-based malware, botnet identification and anti-phishing tools. Prior to relocating to Norway in 2019, he developed and headed a very successful information security focussed postgraduate program at Rhodes University, South Africa. He has a love of military history especially as it relates to codes, ciphers and espionage, and is a somewhat dormant rhykenologist.
---
The domain name system, or DNS, is a critical component of the Internet ecosystem we use being a fundamental step of almost every transaction and connection. While the primary purpose in the eyes of the public is to mask the complexities of host addressing, it is used for a whole lot more -- the second most important component being its foundation for email delivery. 

In recent years we have seen the introduction and gradual adoption of several security measures rooted within the DNS protocol. These include DNSSEC, SPF, and more recently CAA. Despite the requirement for functional DNS, the deployment and operation of the servers and associated domain zones, are often neglected as 'too complex', mundane or unexciting in comparison to more exciting areas such as Threat Intelligence, Malware Analysis and ML/AI based security solutions. The irony is these all have a strong dependence on DNS!

This talk presents an overview of DNS operations and security as it related to the domains within the .no ccTLD. The research was undertaken using a list gathered from public sources of approximately 570 thousand .no domains. An evaluation of risk, particularly the dependency on key providers (about a third of .no domains surveyed are hosted by a single provider), as well as adherence to good practice is presented. The secondary part of the talk presents several short case studies of the adoption rate of security functionality within and offered by DNS for domains under the .no ccTLD. As appropriate these are compared with adoption rates in neighbouring ccTLDs.
