---
title: ExchangeMailboxAuditGroupActivity
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 100
url: /python-net/aspose.email.clients.activity/exchangemailboxauditgroupactivity/
---

## ExchangeMailboxAuditGroupActivity class



The ExchangeMailboxAuditGroupActivity type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|ExchangeMailboxAuditGroupActivity()|Initializes a new instance of the ExchangeMailboxAuditGroupActivity class|
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
|folder|The folder where a group of items is located.|
|cross_mailbox_operations|Indicates if the operation involved more than one mailbox.|
|dest_mailbox_id|Set only if the CrossMailboxOperations parameter is True. Specifies the target mailbox GUID.|
|dest_mailbox_owner_upn|Set only if the CrossMailboxOperations parameter is True. Specifies the UPN of the owner of the target mailbox.|
|dest_mailbox_owner_sid|Set only if the CrossMailboxOperations parameter is True. Specifies the SID of the target mailbox.|
|dest_mailbox_owner_master_account_sid|Set only if the CrossMailboxOperations parameter is True. Specifies the SID for the master account SID of the target mailbox owner.|
|dest_folder|The destination folder, for operations such as Move.|
|folders|Information about the source folders involved in an operation; for example, if folders are selected and then deleted.|
|affected_items|Information about each item in the group.|

### See Also

* namespace [aspose.email.clients.activity](/email/python-net/aspose.email.clients.activity/)
* assembly [Aspose.Email](/email/python-net/)

