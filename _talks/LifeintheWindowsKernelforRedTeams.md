---
layout: talks
title: Life in the Windows Kernel for Red Teams
length: 45
keynote: false
scheduled: "11:00"
card: LifeintheWindowsKernelforRedTeams.png
speakers:
- name: Andre Lima
  image: AndreLima.jpg
  bio: |
    Andre is Red Teamer since 2011, who has worked in Portugal, Australia, and now at PwC Norway in Oslo. An avid researcher he tries to publish as often as possible on his Youtube channel (search "0x4ndr3"), and blog (current: https://medium.com/@0x4ndr3 & old blog: https://pentesterslife.blog/).
    
    His main areas of expertise are reverse engineering, exploit development, and malware development with AV bypass.

    Outside of cyber security, he enjoys spending it with his 2-year-old daughter, editing video and playing basketball or tennis.    

---
In this presentation, Andre will go through details of not only things to consider when developing in the kernel but, most importantly, things to consider when developing malware for the Windows kernel. He'll explain synchronization when the Operating System is not cooperating with you, memory type usage considerations, Direct Kernel Object Manipulation (DKOM), and finally show a demo on a rootkit he's constantly developing, doing the following:

 - Hide a process by PID
 - Hide a process by name (full name > 15 characters)
 - Hide a process by name whenever it's created
 - Hide a driver/rootkit
 - Elevate privileges from any process given their PID

Finally, he'll be giving tips on reverse engineering a malicious rootkit