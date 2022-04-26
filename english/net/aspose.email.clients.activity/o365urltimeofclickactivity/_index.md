---
title: O365URLTimeOfClickActivity
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 1220
url: /net/aspose.email.clients.activity/o365urltimeofclickactivity/
---
## O365URLTimeOfClickActivity class

Extends the Common schema with the properties specific to Office 365 Advanced Threat Protection and Threat Intelligence data. Office 365 Advanced Threat Protection (ATP) and Threat Intelligence events are available for Office 365 customers who have an ATP, Threat Intelligence, or E5 subscription. Each event in the ATP and Threat Intelligence feed corresponds to the URLs clicked by a user in the organization that were detected as malicious at time-of-click based on Office 365 ATP Safe Links protection.

```csharp
public class O365URLTimeOfClickActivity : Content
```

## Constructors

| Name | Description |
| --- | --- |
| [O365URLTimeOfClickActivity](o365urltimeofclickactivity)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AppName](appname) { get; set; } | Office 365 service from which the URL was clicked (e.g. Mail). Mandatory: Yes |
| [Blocked](blocked) { get; set; } | This is true if the URL click is blocked by Office 365 ATP Safe Links protection. Mandatory: Yes |
| [ClickedThrough](clickedthrough) { get; set; } | This is true if the URL block is clicked through (overridden) by the user based on the organization's policies for Office 365 ATP Safe Links protection. Mandatory: Yes |
| [SourceId](sourceid) { get; set; } | Identifier for the Office 365 service from which the URL was clicked (e.g. for Mail, this is the Exchange Online Network Message Id). Mandatory: Yes |
| [TimeOfClick](timeofclick) { get; set; } | The date and time in Coordinated Universal Time (UTC) when the user clicked the URL. Mandatory: Yes |
| [URL](url) { get; set; } | URL clicked by the user. Mandatory: Yes |
| [UserIp](userip) { get; set; } | The IP address for the user who clicked the URL. The IP address is displayed in either an IPv4 or IPv6 address format. Mandatory: Yes |

### See Also

* class [Content](../content)
* namespace [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->