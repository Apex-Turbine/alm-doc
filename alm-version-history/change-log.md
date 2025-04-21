---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Change Log

<div align="left"><figure><img src="../.gitbook/assets/LicenseManager.svg" alt=""><figcaption></figcaption></figure></div>

## Versions

***

## 2025.15.6.0 (released 2025-04-15)

* Introduced three modes of operation:
  * ApexLM.exe (daemon that runs in background, default)
  * ApexLM\_GUI.exe (graphical user interface)
  * ApexLM\_CLI.exe (command line interface)
* The GUI application has a redesigned appearance to more effectively display license information, status, and counts
* The CLI application provides functionality for users that are not able (or do not wish to) use a graphical interface
* Added "RETRIES" key to Environment Variable File
* OpenCode is not supported in this version

## 2024.44

* Log now updates every 5 seconds and provides more granular token information, e.g.:\
  \[10-31-2024 11:10:50] Success: checked out feature ANALYSIS: count = 8 Spectral: 3, Peak: 5,

## 2024.38 (released 2024-09-30)

* Initial release of ApexLM
