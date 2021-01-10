---
title: "The peril of fragmentation: Security hazards in android device driver customizations"

authors:
- Xiaoyong Zhou
- Yeonjoon Lee
- Nan Zhang
- Muhammad Naveed
- XiaoFeng Wang

date: "2014-07-01T00:00:00Z"
publication_types: ["1"]
publication: Security and Privacy (SP), 2014 IEEE Symposium on
publication_short: In *S&P*, 2014

abstract: Android phone manufacturers are under the perpetualpressure to move quickly on their new models, continuouslycustomizing Android to fit their hardware. However, thesecurity implications of this practice are less known, particularlywhen it comes to the changes made to Androids Linux devicedrivers, e.g., those for camera, GPS, NFC etc. In this paper, wereport the first study aimed at a better understanding of thesecurity risks in this customization process. Our study is basedon ADDICTED, a new tool we built for automatically detectingsome types of flaws in customized driver protection. Specifically,on a customized phone, ADDICTED performs dynamic analysisto correlate the operations on a security-sensitive device to itsrelated Linux files, and then determines whether those files areunder-protected on the Linux layer by comparing them withtheir counterparts on an official Android OS. In this way, wecan detect a set of likely security flaws on the phone. Using thetool, we analyzed three popular phones from Samsung, identifiedtheir likely flaws and built end-to-end attacks that allow anunprivileged app to take pictures and screenshots, and even logthe keys the user enters through touchscreen. Some of thoseflaws are found to exist on over a hundred phone models andaffect millions of users. We reported the flaws and helped themanufacturers fix those problems. We further studied the securitysettings of device files on 2423 factory images from major phonemanufacturers, discovered over 1,000 vulnerable images and alsogained insights about how they are distributed across differentAndroid versions, carriers and countries.

url_pdf: ''
---
