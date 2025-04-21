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

# Known Issues

<div align="left"><figure><img src="../.gitbook/assets/LicenseManager.svg" alt=""><figcaption></figcaption></figure></div>

**Last Updated:** April 21, 2025

## List of Known Issues for version 2025.15.6.0

1. License Type - switching the license type to License Server when one doesn't exist or the server is inaccessible can create a situation where the software becomes unresponsive / will not reliably restart.
   * **Impact:** Inconvenience
   * **Workaround:**&#x20;
     1. locate the environment variable file located at:
        * `C:\Users\<user>\AppData\Roaming\APEX\.env.apexlm`
     2. change the LIC\_TYPE value from LS back to NL
     3. save the file and restart ApexLM.exe

## List of Known Issues for version 2024.44

1. License server - possible crash during the 20 to 30 second interval between the license disconnecting and the heartbeat recognizing this. Only seems to occur when application attempts a checkout during this time period.
   * **Impact:** Minor Inconvenience
   * **Workaround:** Simply restart ALM and try again

## Notes

* Please report any new issues to Apex @ [https://users.apexturbine.com/](https://users.apexturbine.com/)
* Regular updates will be provided as issues are resolved.
