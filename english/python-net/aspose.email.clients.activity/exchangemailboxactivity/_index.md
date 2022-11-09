---
title: ExchangeMailboxActivity
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 80
url: /python-net/aspose.email.clients.activity/exchangemailboxactivity/
---

## ExchangeMailboxActivity class

Extends the Common schema with the properties specific to all Exchange mailbox audit data.

The ExchangeMailboxActivity type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|ExchangeMailboxActivity()|Initializes a new instance of the ExchangeMailboxActivity class|
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
|logon_type|Indicates the type of user who accessed the mailbox and performed the operation that was logged.|
|internal_logon_type|Reserved for internal use.|
|mailbox_guid|The Exchange GUID of the mailbox that was accessed.|
|mailbox_owner_upn|The email address of the person who owns the mailbox that was accessed.|
|mailbox_owner_sid|The SID of the mailbox owner.|
|mailbox_owner_master_account_sid|Mailbox owner account's master account SID.|
|logon_user_sid|The SID of the user who performed the operation.|
|logon_user_display_name|The user-friendly name of the user who performed the operation.|
|external_access|This is true if the logon user's domain is different from the mailbox owner's domain.|
|originating_server|This is from where the operation originated.|
|organization_name|The name of the tenant.|
|client_info_string|Information about the email client that was used to perform the operation, such as a browser version, Outlook version, and mobile device information.|
|client_ip_address|The IP address of the device that was used when the operation was logged. The IP address is displayed in either an IPv4 or IPv6 address format.|
|client_machine_name|The machine name that hosts the Outlook client.|
|client_process_name|The email client that was used to access the mailbox.|
|client_version|The version of the email client.|

### See Also

* namespace [aspose.email.clients.activity](/python-net/aspose.email.clients.activity/)
* assembly [Aspose.Email](/python-net/)

