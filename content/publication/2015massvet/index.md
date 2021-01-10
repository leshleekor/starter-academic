---
title: "Finding Unknown Malice in 10 Seconds: Mass Vetting for New Threats at the Google-Play Scale"

authors:
- Kai Chen
- Peng Wang
- Yeonjoon Lee
- XiaoFeng Wang
- Nan Zhang
- Heqing Huang
- Wei Zou
- Peng Liu

date: "2015-07-01T00:00:00Z"
publication_types: ["1"]
publication: 24th USENIX Security Symposium
publication_short: In *USENIX Security*, 2015

abstract: An app market->s vetting process is expected to be scalableand effective. However, today->s vetting mechanismsare slow and less capable of catching new threats. Inour research, we found that a more powerful solutioncan be found by exploiting the way Android malware isconstructed and disseminated, which is typically throughrepackaging legitimate apps with similar malicious components.As a result, such attack payloads often stand outfrom those of the same repackaging origin and also showup in the apps not supposed to relate to each other.Based upon this observation, we developed a newtechnique, called MassVet, for vetting apps at a massivescale, without knowing what malware looks likeand how it behaves. Unlike existing detection mechanisms,which often utilize heavyweight program analysistechniques, our approach simply compares a submittedapp with all those already on a market, focusing onthe difference between those sharing a similar UI structure(indicating a possible repackaging relation), and thecommonality among those seemingly unrelated. Oncepublic libraries and other legitimate code reuse are removed,such diff/common program components becomehighly suspicious. In our research, we built this ->DiffCom->analysis on top of an efficient similarity comparisonalgorithm, which maps the salient features of anapp->s UI structure or a method->s control-flow graph toa value for a fast comparison. We implemented MassVetover a stream processing engine and evaluated it nearly1.2 million apps from 33 app markets around the world,the scale of Google Play. Our study shows that the techniquecan vet an app within 10 seconds at a low falsedetection rate. Also, it outperformed all 54 scanners inVirusTotal (NOD32, Symantec, McAfee, etc.) in termsof detection coverage, capturing over a hundred thousandmalicious apps, including over 20 likely zero-daymalware and those installed millions of times. A closelook at these apps brings to light intriguing new observations:e.g., Google->s detection strategy and malwareauthors-> countermoves that cause the mysterious disappearanceand reappearance of some Google Play apps.

url_pdf: ''
---
