---
title: O365URLTimeOfClickActivity
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 170
url: /email/python-net/aspose.email.clients.activity/o365urltimeofclickactivity/
---

## O365URLTimeOfClickActivity class

Extends the Common schema with the properties specific to Office 365 Advanced Threat Protection and Threat Intelligence data.<br/>            Office 365 Advanced Threat Protection (ATP) and Threat Intelligence events are available for Office 365 customers who have an ATP, Threat Intelligence, or E5 subscription. <br/>            Each event in the ATP and Threat Intelligence feed corresponds to the <br/>            URLs clicked by a user in the organization that were detected as malicious at time-of-click based on Office 365 ATP Safe Links protection.

The O365URLTimeOfClickActivity type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|O365URLTimeOfClickActivity()|Initializes a new instance of the O365URLTimeOfClickActivity class|
## Properties
| Name | Description |
| :- | :- |
|id|Unique identifier of an audit record.<br/>            Mandatory: Yes|
|record_type|The type of operation indicated by the record. <br/>            Mandatory: Yes|
|creation_time|The date and time in Coordinated Universal Time (UTC) when the user performed the activity.<br/>            Mandatory: Yes|
|operation|The name of the user or admin activity. <br/>            For a description of the most common operations/activities, see Search the audit log in the Office 365 Protection Center. <br/>            For Exchange admin activity, this property identifies the name of the cmdlet that was run. <br/>            For Dlp events, this can be "DlpRuleMatch", "DlpRuleUndo" or "DlpInfo", which are described under "DLP schema" below.<br/>            Mandatory: Yes|
|organization_id|The GUID for your organization's Office 365 tenant. <br/>            This value will always be the same for your organization, regardless of the Office 365 service in which it occurs.<br/>            Mandatory: Yes|
|user_type|The type of user that performed the operation. <br/>            Mandatory: Yes|
|user_key|An alternative ID for the user identified in the UserId property. <br/>            For example, this property is populated with the passport unique ID (PUID) for events performed by users in SharePoint, OneDrive for Business, and Exchange. <br/>            This property may also specify the same value as the UserID property for events occurring in other services and events performed by system accounts.<br/>            Mandatory: Yes|
|workload|The Office 365 service where the activity occurred in the Workload string. The possible values for this property are:<br/>                Exchange<br/>                SharePoint<br/>                OneDrive<br/>                AzureActiveDirectory<br/>                SecurityComplianceCenter<br/>                Sway<br/>                ThreatIntelligence<br/>            Mandatory: No|
|result_status|Indicates whether the action (specified in the Operation property) was successful or not. <br/>            Possible values are Succeeded, PartiallySucceded, or Failed. <br/>            For Exchange admin activity, the value is either True or False.<br/>            Mandatory: No|
|object_id|For SharePoint and OneDrive for Business activity, the full path name of the file or folder accessed by the user. <br/>            For Exchange admin audit logging, the name of the object that was modified by the cmdlet.<br/>            Mandatory: No|
|user_id|The UPN (User Principal Name) of the user who performed the action (specified in the Operation property) that resulted in the record being logged; <br/>            for example, my_name@my_domain_name. <br/>            Note that records for activity performed by system accounts (such as SHAREPOINT\system or NT AUTHORITY\SYSTEM) are also included.<br/>            Mandatory: Yes|
|client_ip|The IP address of the device that was used when the activity was logged. <br/>            The IP address is displayed in either an IPv4 or IPv6 address format.<br/>            Mandatory: Yes|
|scope|Was this event created by a hosted O365 service or an on-premises server? <br/>            Possible values are online and onprem. Note that SharePoint is the only workload currently sending events from on-premises to O365.<br/>            Mandatory: No|
|app_name|Office 365 service from which the URL was clicked (e.g. Mail).<br/>            Mandatory: Yes|
|blocked|This is true if the URL click is blocked by Office 365 ATP Safe Links protection.<br/>            Mandatory: Yes|
|clicked_through|This is true if the URL block is clicked through (overridden) by the user based on the organization's policies <br/>            for Office 365 ATP Safe Links protection.<br/>            Mandatory: Yes|
|source_id|Identifier for the Office 365 service from which the URL was clicked (e.g. for Mail, this is the Exchange Online Network Message Id).<br/>            Mandatory: Yes|
|time_of_click|The date and time in Coordinated Universal Time (UTC) when the user clicked the URL.<br/>            Mandatory: Yes|
|url|URL clicked by the user.<br/>            Mandatory: Yes|
|user_ip|The IP address for the user who clicked the URL. The IP address is displayed in either an IPv4 or IPv6 address format.<br/>            Mandatory: Yes|

### See Also

* namespace [aspose.email.clients.activity](/email/python-net/aspose.email.clients.activity/)
* assembly [Aspose.Email](/slides/python-net/)

