---
# required metadata

title: Renew Apple MDM certificate
titleSuffix: Intune for Education
description: Learn how to renew expired certificates or tokens in the Intune for Education portal.
keywords:
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 07/23/2018
ms.topic: article
ms.prod:
ms.service: microsoft-intune
ms.subservice: education
ms.technology:
ms.assetid: c884df47-61a9-4799-a407-8cd311d376d1
searchScope:
 - IntuneEDU

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
#ms.reviewer: travisj
#ms.suite: ems
#ms.tgt_pltfrm:
#ms.custom: intune-education

---

# Renew iOS certificate and tokens
Apple MDM Push certificates, MDM server tokens, and VPP tokens expire 365 days after you create them. Intune for Education will alert you when a certificate or token is close to or past its expiration date. 

Make sure to renew them to maintain the connection between your Intune for Education account and Apple account.  

## Renew Apple MDM  certificate  
> [!IMPORTANT]
> If the Apple MDM certificate is deleted, you will need to reset and re-enroll devices with a new certificate.  

The MDM push certificate is associated with the Apple ID you used to create it. Renew the certificate with this same Apple ID.

1. From the Intune for Education dashboard, click **Tenant settings** > **iOS Device Management**.
2. Click the **MDM Push Certificate** tab.
3. Click **Renew certificate**.
4. Follow the instructions on the **MDM Push Certificate** page. You'll be required to visit the Apple Push Certificates portal to renew your MDM push Certificate. Remember, sign in to the Apple Push Certificates portal with the Apple ID you used to create your original certificate.
5. When you're in the Apple Push Certificates portal, click the option to renew the expiring certificate. 
6. Complete the steps in the Apple portal. When your certificate's status reads **Active** again, click to download and save it.
7. Return to the Intune for Education portal and enter the Apple ID you used to sign in to the Apple Push Certificates portal.
8. Upload the certificate you downloaded.
9. Click **Save**.

## Renew MDM server token

Renew the MDM server token annually to make sure that Intune for Education always has an updated list of your iOS devices.

The MDM server token is associated with the Apple ID you used to add the server. Renew the token with this same Apple ID. 

1. From the Intune for Education dashboard, click **Tenant settings** > **iOS Device Management**.
2. Click the **MDM Server Tokens** tab.
3. Select the token that you want to renew.
4. Click **Renew token**.
5. Follow the instructions on the **MDM Server Tokens** page. You'll be required to visit Apple School Manager to generate a new MDM Server Token. Remember, sign in to Apple School Manager with the Apple ID you used to get your original token.
6. After you download and save the new token from Apple School Manager, return to the Intune for Education portal. Type in the Apple ID used to create the original token.
7. Upload the token you downloaded.
8. Click **Save**.


## Renew VPP token
Renew your VPP tokens annually to make sure your VPP-purchased apps can be viewed and assigned from Intune for Education.  

The VPP token is associated with the Apple ID you used to create it. Renew the token with this same Apple ID.  

1. On the **iOS Device Management** page, click the **VPP Tokens** tab.
2. Select the token that you want to renew.
3. Under **VPP Token: Microsoft Intune**, click **Renew token**.
4. Follow the instructions on the **VPP Token** page. You'll be required to visit Apple School Manager to get a new token. Remember, sign in with the Apple ID you used to get your original token.
5. Follow the steps in Apple School Manager to create and download the token. Then save the token to your computer.
6. Return to the Intune for Education portal. Enter the Apple ID that you used to sign in to Apple School Manager.
7. Click the folder icon to browse your computer's files. Select the token file that you downloaded and saved earlier.
8. Choose the location of your school's devices.
9. If you don't want to enable automatic app updates, switch the setting to disable them. 
10. Click **Save**.

## Next steps
Now that your certificates and tokens are renewed, make sure [your group settings](edit-groups-intune-for-edu.md) are up-to-date. To see the current status of your groups in Intune, learn how to [view reports](what-are-reports.md).  

Read [What's new in Intune for Education](whats-new-in-edu.md) to find out about the latest updates and features.
