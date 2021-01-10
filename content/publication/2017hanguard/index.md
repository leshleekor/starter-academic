---
title: "HanGuard: SDN-driven protection of smart home WiFi devices from malicious mobile apps"

authors:
- Soteris Demetriou
- Nan Zhang
- Yeonjoon Lee
- XiaoFeng Wang
- Carl A Gunter
- Xiaoyong Zhou
- Michael Grace


date: "2017-07-01T00:00:00Z"
publication_types: ["1"]
publication: Proceedings of the 10th ACM Conference on Security and Privacy in Wireless and Mobile Networks
publication_short: In *WISEC*, 2017

abstract: A new development of smart-home systems is to use mobile appsto control IoT devices across a Home Area Network (HAN). As veri!edin our study, those systems tend to rely on the Wi-Fi router toauthenticate other devices. This treatment exposes them to the attackfrom malicious apps, particularly those running on authorizedphones, which the router does not have information to control. Mitigatingthis threat cannot solely rely on IoT manufacturers, whichmay need to change the hardware on the devices to support encryption,increasing the cost of the device, or software developers whowe need to trust to implement security correctly. In this work, wepresent a new technique to control the communication between theIoT devices and their apps in a unified, backward-compatible way.Our approach, called HanGuard, does not require any changes to theIoT devices themselves, the IoT apps or the OS of the participatingphones. HanGuard uses an SDN-like approach to o$er fine-grainedprotection; each phone runs a non-system userspace Monitor appto identify the party that a%empts to access the protected IoT deviceand inform the router through a control plane of its accessdecision; the router enforces the decision on the data plane afterverifying whether the phone should be allowed to talk to the device.We implemented our design over both Android and iOS (> 95% ofmobile OS market share) and a popular router. Our study showsthat HanGuard is both e&cient and effective in practice.

url_pdf: ''
---
