# Introduction
---
This repository is use to hold the manifest for BlackBeagleBone.The description of manifest is below:
+ **example.xml**:a example of manifest.xml
+ **BlackBeagleBone.xml**:the manifest of project BlackBeagleBone.uboot:2014.04;kernel:3.8.13

The method to get the source code of project:

**Step1:**initialize the project‘s repository by repo
`repo init -u https://github.com/harryyue/manifests -m BlackBeagleBone.xml -b BlackBeagleBone`

**Step2:**download the source code by repo
`repo sync`
