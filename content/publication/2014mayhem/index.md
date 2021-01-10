---
title: "Mayhem in the push clouds: Understanding and mitigating security hazards in mobile push-messaging services"

authors:
- Tongxin Li
- Xiaoyong Zhou
- Luyi Xing
- Yeonjoon Lee
- Muhammad Naveed
- XiaoFeng Wang
- Xinhui Han


date: "2014-07-01T00:00:00Z"
publication_types: ["1"]
publication: Proceedings of the 2014 ACM SIGSAC Conference on Computer and Communications Security
publication_short: In *CCS*, 2014

abstract: Push messaging is among the most important mobile-cloud services, offering critical supports to a wide spectrum of mobile apps. This service needs to coordinate complicated interactions between developer servers and their apps in a large scale, making it error prone. With its importance, little has been done, however, to understand the security risks of the service. In this paper, we report the first security analysis on those push-messaging services, which reveals the pervasiveness of subtle yet significant security flaws in them, affecting billions of mobile users. Through even the most reputable services like Google Cloud Messaging (GCM) and Amazon Device Messaging (ADM), the adversary running carefullycrafted exploits can steal sensitive messages from a target device, stealthily install or uninstall any apps on it, remotely lock out its legitimate user or even completely wipe out her data. This is made possible by the vulnerabilities in those services-> protection of deviceto-cloud interactions and the communication between their clients and subscriber apps on the same devices. Our study further brings to light questionable practices in those services, including weak cloud-side access control and extensive use of PendingIntent, as well as the impacts of the problems, which cause popular apps or system services like Android Device Manager, Facebook, Google+, Skype, PayPal etc. to leak out sensitive user data or unwittingly act on the adversary->s command. To mitigate this threat, we developed a technique that helps the app developers establish end-to-end protection of the communication with their apps, over the vulnerable messaging services they use.

url_pdf: ''
---
