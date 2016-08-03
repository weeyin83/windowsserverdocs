---
title: Join the MultiPoint server to a domain (optional)
ms.custom: na
ms.date: 07/22/2016
ms.prod: windows-server-2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 623b7c21-dcbb-402e-8b5a-8e434cd225bd
author: evas
manager: scottman
---
# Join the MultiPoint Server computer to a domain (optional)
If you will access your MultiPoint server computer over an Active Directory domain, your next step is to add the computer to the domain.  
  
> [!IMPORTANT]  
> You must verify your time zone before you join the computer to a domain. For instructions, see [Set the date, time, and time zone](../../../compute/remote-desktop-services/multipoint-1/Set-the-date--time--and-time-zone.md).  
  
### To join the MultiPoint server computer to a domain  
  
1.  From the **Start** screen, open **Control Panel**. Click **System and Security**, and then click **System**.  
  
    \-Or\-  
  
    Open the computer properties in File Explorer. \(Right\-click **Computer**, and then click **Properties**.\)  
  
2.  Under **Computer name, domain, and workgroup settings**, click **Change settings**.  
  
3.  On the **Computer name** tab, click **Change**.  
  
4.  In the **Computer Name\/Domain Changes** dialog box, select **Domain**, enter the name of the domain, and click **OK**, and then follow the steps in the wizard to complete the process.  
  
5.  After the computer restarts, log on as Administrator and wait for MultiPoint Manager to open.  
  
> [!IMPORTANT]  
> To ensure that your MultiPoint server domain deployment works correctly, you will need to configure a couple of group policies and update the Registry. For information, see [Configure group policies for a domain deployment](../../../compute/remote-desktop-services/multipoint-1/Configure-group-policies-for-a-domain-deployment.md).  