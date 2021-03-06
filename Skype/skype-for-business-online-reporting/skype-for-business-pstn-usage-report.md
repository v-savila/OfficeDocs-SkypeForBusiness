---
title: "Skype for Business PSTN usage report"
ms.author: tonysmit
author: tonysmit
ms.date: 11/24/2017
ms.audience: Admin
ms.topic: article
ms.prod: office-online-server
localization_priority: Normal
ms.collection: Adm_Skype4B_Online
ms.custom: Adm_O365_FullSet
ms.assetid: 74eda791-c41f-4fd9-ae0b-913342e7ab04
description: "The new Skype for Business Admin Center Reports area shows you calling and audio conferencing activity in your organization. It enables you to drill into reports to give you more granular insight about the activities of each user. For example, you can use the Skype for Business PSTN usage details report to see the number of minutes spent in inbound/outbound calls and cost for these calls. You can view Audio Conferencing PSTN usage details including the cost of the call so that you can understand your usage and call billing details to determine usage within your organization."
---

# Skype for Business PSTN usage report

The new Skype for Business Admin Center **Reports** area shows you calling and audio conferencing activity in your organization. It enables you to drill into reports to give you more granular insight about the activities of each user. For example, you can use the **Skype for Business PSTN usage details** report to see the number of minutes spent in inbound/outbound calls and cost for these calls. You can view Audio Conferencing PSTN usage details including the cost of the call so that you can understand your usage and call billing details to determine usage within your organization.
  
Check out [Activity Reports in the Office 365 admin center](http://technet.microsoft.com/library/0d6dfb17-8582-4172-a9a9-aed798150263%28Office.14%29.aspx) for more reports that are available.
  
This report along with the other Skype for Business reports give you details on activity including calling usage across your organization. These details are very helpful when you investigating, planning, and making other business decisions for your organization and for setting up [What are Communications Credits?](../skype-for-business-and-microsoft-teams-add-on-licensing/what-are-communications-credits.md).
  
> [!NOTE]
> You can see all of the Skype for Business reports when you log on as an administrator to the Office 365 admin center. 
  
## How to get to the Skype for Business PSTN usage details report

- Go to the **Office 365 admin center** > **Admin centers** > **Skype for Business admin center** > **Reports** > **PSTN usage details**.
    
    > [!NOTE]
    > Depending on the Office 365 subscription you have, you might not see all the products and reports that are shown here. 
  
## Interpret the Skype for Business PSTN usage report

You can get a view into your user's Skype for Business PSTN usage by looking at each of the columns that are displayed.
  
This is what the report looks like.
  
![Skype for Business PSTN usage report](../images/79d7aadf-c69e-4d6a-8179-ab69dbbb2472.png)
  
## 

|||
|:-----|:-----|
|**1** <br/> | The table shows you a breakdown of the all PSTN usage per user. This shows all users that have Skype for Business assigned to them and their PSTN usage. You can add/remove columns to the table. <br/> **Call ID** is the call ID for a call. It is a unique identifier for the call that is used when calling Microsoft service support. <br/> **User ID** is the user's sign in name. <br/> **Phone number** is the Skype for Business phone number that received the call for inbound calls or the number dialed for outbound calls. <br/> **User location** is the country/region where the user is located. <br/> **Caller ID** is caller's telephone number (Caller ID) for inbound calls, the number from which the call originated or the Skype for Business number from which the call originated for outbound calls. <br/> **Call type** is whether the call was a PSTN outgoing or incoming call and the type of call such as a call placed by a user or an audio conference. The call types you may see are: <br/> **Calling Plan Call Types** <br/> **user_in** (the user received an inbound PSTN call) <br/> **﻿user_out** (the user placed an outbound PSTN call) <br/> **﻿user_out_conf** (the user added 2 or more PSTN participants to the call such as a 3-way conference call) <br/> **﻿user_out_transfer** (the user transferred the call to a PSTN number) <br/> **user_out_forwarding** (the user forwarded the call to a PSTN number) <br/> **Audio Conferencing Call Types** <br/> **﻿conf_in** (an inbound call to the Audio Conferencing bridge) <br/> **﻿conf_out** (an outbound call from the Audio Conferencing bridge usually to add a PSTN number to the conference) <br/>  ﻿Unified Communication Applications (UCAP) <br/> **﻿ucap_in** (an inbound call to the UC application such as auto attendant or call queue) <br/> **﻿ucap_out** (an outbound call ﻿from the UC application such as auto attendant or call queue) <br/> **Domestic/International** tells you whether the call that was placed was considered domestic (within a country/region) or international (outside of a country/region) based on the user's location. <br/> **Destination dialed** is the name of the country/region destination that is dialed such as France, Germany, or the United States (U.S.). <br/> **Number type** is the type of phone number that is from a user's phone number, a service or toll-free number. <br/> **Start Time (UTC)** is the time that the call was started or placed. <br/> **Duration** is how long the call was connected. <br/> **ConfID** is the conference ID of the audio conference. <br/> **Charge** is the amount of money or cost of the call that is being charged to your account. <br/> **Currency** is the type of currency that is used to calculate the cost of the call. <br/> **Capability** is the license used for the call. The license types you may see are: <br/> **MCOPSTNPP** - Communications Credits <br/> **MCOPSTN1** - Domestic Calling Plan (3000 min US / 1200 min EU plans) <br/> **MCOPSTN2** - International Calling Plan <br/> **MCOPSTN5** - Domestic Calling Plan (120 min calling plan) <br/> **MCOMEETADD** - Audio Conferencing <br/> **MCOMEETACPEA** - Pay Per Minute Audio Conferencing <br/> |
|**2** <br/> |Click to drag a column to **To group by a particular column, drag and drop the column header here** if you want to create a view that groups all of the data in one or more columns. <br/> |
|**3** <br/> |You can also export the report data into an Excel .csv file, by clicking or tapping the **Export to Excel** button. <br/> This exports data of all users and enables you to do simple sorting and filtering for further analysis. If you have less than 2000 users, you can sort and filter within the table in the report itself. If you have more than 2000 users, in order to filter and sort, you will need to export the data.  <br/> |
   
## Want to see other Skype for Business reports?

- [Skype for Business activity report](skype-for-business-activity-report.md) You can see how much your users are using peer-to-peer, organized, and participated in conferencing sessions.
    
- [Skype for Business device usage report](skype-for-business-device-usage-report.md) You can to see the devices including Windows-based operating systems and mobile devices that have the Skype for Business app installed and are using it for IM and meetings.
    
- [Skype for Business conference organizer activity report](skype-for-business-conference-organizer-activity-report.md) You can see how much your users are organizing conferences that use IM, audio/video, application sharing, Web, /dial out - 3rd party, and /dial out - Microsoft.
    
- [Skype for Business conference participant activity report](skype-for-business-conference-participant-activity-report.md) You can see how many IM, audio/video, application sharing, Web and dial out audio conferences are being participated in.
    
- [Skype for Business peer-to-peer activity report](skype-for-business-peer-to-peer-activity-report.md) You can see how much your users are using IM, audio/video, application sharing and transferring files.
    
- [Skype for Business users blocked report](skype-for-business-users-blocked-report.md) You can see the users in your organization that have been blocked from making PSTN calls.
    
- [Skype for Business users blocked report](skype-for-business-users-blocked-report.md) You can see details about the type of media being used, duration of the session, the client used and the conferencing URL.
    
## Related Topics

[Activity Reports in the Office 365 admin center](http://technet.microsoft.com/library/0d6dfb17-8582-4172-a9a9-aed798150263%28Office.14%29.aspx)
  

