---
title: "Using Sonar for Liveness Detection to Protect Smart Speakers Against Remote Attackers"

authors:
- Yeonjoon Lee
- Yue Zhao
- Jiutian Zeng
- Kwangwuk Lee
- Nan Zhang
- Faysal Hossain Shezan
- Yuan Tian
- Kai Chen
- XiaoFeng Wang

date: "2020-01-01T00:00:00Z"
publication_types: ["1"]
publication: ACM UbiComp 2020 / Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (IMWUT)

abstract: Smart speakers, which wait for voice commands and complete tasks for users, are becoming part of common households. While voice commands came with basic functionalities in the earlier days, as the market grew, various commands with critical functionalities were developed; e.g., access banking services, send money, open front door. Such voice commands can cause serious consequences once smart speakers are attacked. Recent research shows that smart speakers are vulnerable to malicious voice commands sent from other speakers (e.g., TV, baby monitor, radio) in the same area. In this work, we propose the SPEAKER-SONAR, a sonar-based liveness detection system for smart speakers. Our approach aims to protect the smart speakers from remote attackers that leverage network-connected speakers to send malicious commands. The key idea of our approach is to make sure that the voice command is indeed coming from the user. For this purpose, the SPEAKER-SONAR emits an inaudible sound and tracks the user’s direction to compare it with the direction of the received voice command. The SPEAKER-SONAR does not require additional action from the user and works through an automatic consistency check. We built the SPEAKER-SONAR on a raspberry pi 3b, a circular microphone array, and a commodity speaker by imitating the Amazon Echo. Our evaluation shows that the SPEAKER-SONAR can reject remote voice attacks with an average accuracy of 95.5% in 2 meters, which significantly raises the bar for remote attackers. To the best of our knowledge, our defense is able to defend against known remote voice attack techniques.

---
