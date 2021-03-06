---
title: Microsoft Cloud App Security integration overview
description: 
keywords: 
search.product: eADQiWindows 10XVcnh
ms.prod: w10
ms.mktglfcycl: deploy
ms.sitesec: library
ms.pagetype: security
ms.author: macapara
author: mjcaparas
ms.localizationpriority: high
ms.date: 09/03/2018
---

# Microsoft Cloud App Security integration overview
**Applies to:**
- Windows Defender Advanced Threat Protection (Windows Defender ATP)

[!include[Prerelease information](prerelease.md)]

Microsoft Cloud App Security (Cloud App Security) is a comprehensive solution that gives visibility into cloud apps and services by allowing you to control and limit access to cloud apps, while enforcing compliance requirements on data stored in the cloud. For more information, see [Cloud App Security](https://docs.microsoft.com/cloud-app-security/what-is-cloud-app-security).

## Windows Defender ATP and Cloud App Security integration 

Cloud App Security discovery relies on cloud traffic logs being forwarded to it from enterprise firewall and proxy servers. Windows Defender ATP integrates with Cloud App Security by collecting and forwarding all cloud app networking activities, providing unparalleled visibility to cloud app usage. The monitoring functionality is built into the device, providing complete coverage of network activity.

The integration provides the following major improvements to the existing Cloud App Security discovery: 

- Available everywhere - Since the network activity is collected directly from the endpoint, it's available wherever the device is, on or off corporate network, as it's no longer depended on traffic routed through the enterprise firewall or proxy servers. 

- Works out of the box, no configuration required - Forwarding cloud traffic logs to Cloud App Security requires firewall and proxy server configuration. With the Windows Defender ATP and Cloud App Security integration, there's no configuration required. Just switch it on in Windows Defender Security Center settings and you're good to go. 

- Device context - Cloud traffic logs lack device context. Windows Defender ATP network activity is reported with the device context (which device accessed the cloud app), so you are able to understand exactly where (device) the network activity took place, in addition to who (user) performed it. 

For more information about cloud discovery, see [Working with discovered apps](https://docs.microsoft.com/en-us/cloud-app-security/discovered-apps).

## Related topic

- [Configure Microsoft Cloud App Security integration](microsoft-cloud-app-security-config.md)