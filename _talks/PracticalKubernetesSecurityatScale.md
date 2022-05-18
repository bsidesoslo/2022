---
layout: talks
title: Practical Kubernetes Security at Scale
length: 45
keynote: false
scheduled: "13:40"
card: PracticalKubernetesSecurityatScale.png
speakers:
- name: Birgir Stefansson
  image: BirgirStefansson.jpg
  bio: |
    Birgir is a staff software engineer in Schibsted’s Developer Foundations team. 
- name: Stian Kristoffersen
  image: StianKristoffersen.png
  bio: |
    Stian is a staff security engineer in Schibsted’s Product & Application Security team. 
    
    In the past he has open sourced two security projects at Schibsted: Strongbox, a secrets manager, and Artishock, a tool to investigate dependency confusion.

    Stian also presented his talk on [Dependency Confusion Deep Dive](https://de2021.bsidesoslo.no/talks/Dependency_Confusion_Deep_Dive.html) at BSides Oslo Digital Edition 2021
---
Over the past few years Kubernetes (k8s) has been adopted widely across Schibsted. Currently Schibsted manages about 100 k8s clusters centrally and that number is growing as more as Schibsted brands adopt k8s. 

In this talk we will present what to consider and the trade-offs we made to improve security in those clusters. While most of the takeaways should be generally applicable, the examples will be from EKS clusters in AWS.

We will look at k8s and EKS hardening as well as open source and commercial security tools. Security in k8s is a large topic and our goal is to focus on the most important best practices, while keeping the user experience in mind.   
