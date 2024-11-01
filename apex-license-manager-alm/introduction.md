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

# Introduction

<div align="left" data-full-width="false">

<figure><img src="../.gitbook/assets/LicenseManager.svg" alt="" width="113"><figcaption></figcaption></figure>

</div>

#### What is the ALM?

The APEX License Manager (ALM) is a utility that manages licensing for new APEX Turbine software applications. Formerly, the licensing was handled by each application individually.

The ALM must be installed for new APEX applications to be licensed. The ALM runs as a daemon in the background. Each APEX application will check on launch to see if the ALM is running. If not, the application will exit with a warning message.&#x20;

If the application finds the ALM, it will then send all license requests to the ALM. The ALM will send success/fail responses back to the application based on the license available.&#x20;

The ALM will also keep records of all licenses distributed to APEX applications.
