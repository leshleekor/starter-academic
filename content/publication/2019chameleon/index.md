---

title: "Understanding Illicit UI in iOS apps Through Hidden UI Analysis"

authors:
- Yeonjoon Lee
- Xueqiang Wang
- Xiaojing Liao
- XiaoFeng Wang

date: "2019-10-01T00:00:00Z"
publication_types: ["1"]
publication: IEEE Transactions on Dependable and Secure Computing (TDSC)

abstract: In Chameleon apps, benign UIs are displayed during Apple App vetting while their hidden potentially-harmful illicit UIs (PHI-UI) are revealed once they reached App Store. In this paper, we report the first systematic study on iOS Chameleon apps, which sheds light on a largely overlooked threat that the illicit activities are launched solely based on UI. Our research employed CHAMELEON-HUNTER, a new static analysis approach that determines the suspiciousness of a PHI-UI leveraging the semantic features generated from iOS app UI and metadata. The approach is based on the observation that PHI-UI not only is structurally hidden but also has notable semantic inconsistency with the benign UI. Our evaluation shows that CHAMELEON-HUNTER is highly effective, achieving 92.6% precision and 94.7% recall. From 28K Apple App Store apps, we found 142 new Chameleon apps, which were confirmed and promptly removed by Apple. Our work reveals that Chameleon apps can easily bypass the App store vetting and conduct a set of suspicious activities including collecting users private information, swindling money with fake monetary services, and leading the user to a pirated app store.
---
