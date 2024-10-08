# SmuggleSheild
***Beta Version***

[![CodeQL Advanced](https://github.com/RootUp/SmuggleSheild/actions/workflows/codeql.yml/badge.svg)](https://github.com/RootUp/SmuggleSheild/actions/workflows/codeql.yml)

SmuggleSheild is an experimental browser extension that aims to prevent **basic** HTML smuggling attacks by detecting common patterns. While this is not a comprehensive or bulletproof solution, it is an attempt to provide an additional layer of security during browsing. **The project is still in the testing phase!**

The extension is compatible both on Chrome and Edge for Mac and Windows OS. Enable developer mode under extension settings and click on "Load unpacked" in the "SumggleSheild" folder. The extension would be up and running. Blocked URLs are stored in extension cache up to 10 days with blocked pattern, URL, and timestamp, which can be reviewed by clicking on extension then "Export Blocked Content Logs.". 

[Watch on Youtube](https://youtu.be/6x0Fe_63qxA)

![SmuggleSheild_POC](https://github.com/user-attachments/assets/c8602882-cd1b-48fb-9512-642993aadf88)

I have taken multiple code references from StackOverflow/Github and file smuggling samples from delivr[dot]to. Hence, special thanks to them!

## **Privacy Policy**
- [Privacy Policy for SmuggleSheild](https://www.inputzero.io/p/smuggelsheild.html)

## **SmuggleSheild could have prevented**

- [Quakbot- 14072022](https://github.com/0xToxin/Malware-IOCs/blob/main/Quakbot/Quakbot-%2014072022)
- [Pikabot | TA577 | 1.1.15-ghost](https://github.com/pr0xylife/Pikabot/blob/main/Pikabot_01.11.2023.txt)
- [HTML smuggling is delivering DCRat malware, bypassing traditional security controls by embedding malicious payloads in HTML files. This advanced technique poses a global threat to unsuspecting users](https://x.com/RandomDhiraj/status/1839717748970021027).
