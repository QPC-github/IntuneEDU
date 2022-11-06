---
# required metadata

title: Remote assistance for managed devices - Intune for Education
description: There are four different options to remotely help students and teachers with their mobile devices when you can't be there in person.
keywords:
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 04/14/2020
ms.topic: conceptual
ms.service: microsoft-intune
ms.subservice: education
ms.localizationpriority: high
ms.technology:
ms.assetid: 

# optional metadata 

#ROBOTS:
#audience:
ms.suite: ems
search.appverid: MET150
#ms.tgt_pltfrm:
ms.custom: intune-education 

---

# Remote assistance for devices managed by Intune for Education  

There are four options available to help you remotely help students and teachers with their managed devices.  

- [Microsoft Teams](https://products.office.com/microsoft-teams/) is the hub for teamwork where you can chat, meet, and collaborate no matter where you are.
- [Quick Assist](https://support.microsoft.com/help/4027243/windows-10-solve-pc-problems-with-quick-assist) is a Windows 10 application that lets two people share a device over a remote connection.
- [TeamViewer](https://www.teamviewer.com/) is a third-party program that you purchase separately. It provides a comprehensive set of remote access and support capabilities. The Intune and [TeamViewer integration](https://docs.microsoft.com/mem/intune/remote-actions/teamviewer-support) enables remote support using TeamViewer, and the connector is managed directly in Intune.
- [Remote control](https://docs.microsoft.com/configmgr/core/clients/manage/remote-control/introduction-to-remote-control) is included in Microsoft Endpoint Configuration Manager. It's used to remotely administer, provide assistance, or view any workgroup computer and domain-joined computer. 

| Features, platforms, licensing | **Teams** | Quick Assist | TeamViewer (Intune) | Remote control (ConfigMgr) |
|:---:|:---:|:---:|:---:|:---:|
| Remote view and control |![Checkmark](./media/checkmark.png)|![Checkmark](./media/checkmark.png)|![Checkmark](./media/checkmark.png)|![Checkmark](./media/checkmark.png)|
| Chat |![Checkmark](./media/checkmark.png)||![Checkmark](./media/checkmark.png)||
| File transfer |![Checkmark](./media/checkmark.png)|![Checkmark](./media/checkmark.png)|![Checkmark](./media/checkmark.png)|![Checkmark](./media/checkmark.png)|
| Elevated admin access |||![Checkmark](./media/checkmark.png)|![Checkmark](./media/checkmark.png)|
| Unattended access |||![Checkmark](./media/checkmark.png)|![Checkmark](./media/checkmark.png)|
| Simultaneous remote control |![Checkmark](./media/checkmark.png)|![Checkmark](./media/checkmark.png)|||
| Multi-user support |||![Checkmark](./media/checkmark.png)|![Checkmark](./media/checkmark.png)|
| Remote actions ||![Checkmark](./media/checkmark.png)|![Checkmark](./media/checkmark.png)|![Checkmark](./media/checkmark.png)|
| Over-the-internet support |![Checkmark](./media/checkmark.png)|![Checkmark](./media/checkmark.png)|![Checkmark](./media/checkmark.png)||
| Audit reporting |![Checkmark](./media/checkmark.png)||![Checkmark](./media/checkmark.png)|![Checkmark](./media/checkmark.png)|
| Support for all platforms (Windows, iOS, Android, macOS) |![Checkmark](./media/checkmark.png)||![Checkmark](./media/checkmark.png)||
| Requires device to be co-managed by Configuration Manager and Intune ||||![Checkmark](./media/checkmark.png)|
| Requires additional licensing\* |![Checkmark](./media/checkmark.png)||![Checkmark](./media/checkmark.png)|![Checkmark](./media/checkmark.png)|

\* Teams requires Office 365 or Microsoft 365 licensing. Use of TeamViewer and Intune requires licensing from both TeamViewer and Intune. Remote control is a feature of Configuration Manager and requires Configuration Manager licensing.  
