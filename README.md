# Introduction
---
This repository is use to hold the manifest for tiny4412.The description of manifest is below:  
+ **example.xml**:a example of manifest.xml  
+ **Tiny4412_171201.xml**:the manifest of project tiny4412.uboot:2010.12;kernel:3.15;busybox:1.72  

The method to get the source code of project:

**Step1**:initialize the project‘s repository by repo

`repo init -u https://github.com/harryyue/manifests -m Tiny4412_171201.xml -b Tiny4412`

**Step2**:download the source code by repo

`repo sync`
