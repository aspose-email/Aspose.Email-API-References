---
title: Record
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 190
url: /python-net/aspose.email.clients.activity/record/
---

## Record class

Audit log record

The Record type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|Record()|Initializes a new instance of the Record class|
## Properties
| Name | Description |
| :- | :- |
|creation_time|Gets or sets date and time in Coordinated Universal Time (UTC) when the user performed the activity.<br/>            Mandatory: Yes|
|id|Gets or sets unique identifier of an audit record.<br/>            Mandatory: Yes|
|operation|Gets or sets name of the user or admin activity. <br/>            For a description of the most common operations/activities, see Search the audit log in the Office 365 Protection Center. <br/>            For Exchange admin activity, this property identifies the name of the cmdlet that was run. <br/>            For Dlp events, this can be "DlpRuleMatch", "DlpRuleUndo" or "DlpInfo", which are described under "DLP schema" below.<br/>            Mandatory: Yes|
|organization_id|Gets or sets GUID for your organization's Office 365 tenant. <br/>            This value will always be the same for your organization, regardless of the Office 365 service in which it occurs.<br/>            Mandatory: Yes|
|record_type|Gets or sets type of operation indicated by the record. <br/>            Mandatory: Yes|
|result_status|Gets or sets value which indicates whether the action (specified in the Operation property) was successful or not. <br/>            Mandatory: No|
|user_key|Gets or sets an alternative ID for the user identified in the UserId property. <br/>            For example, this property is populated with the passport unique ID (PUID) for events performed by users in SharePoint, OneDrive for Business, and Exchange. <br/>            This property may also specify the same value as the UserID property for events occurring in other services and events performed by system accounts.<br/>            Mandatory: Yes|
|user_type|Gets or sets type of user that performed the operation. <br/>            Mandatory: Yes|
|workload|Gets or sets Office 365 service where the activity occurred. <br/>            Mandatory: No|
|client_ip|Gets or sets IP address of the device that was used when the activity was logged. <br/>            The IP address is displayed in either an IPv4 or IPv6 address format.<br/>            Mandatory: Yes|
|object_id|Gets or sets object identifier.<br/>            For SharePoint and OneDrive for Business activity, the full path name of the file or folder accessed by the user. <br/>            For Exchange admin audit logging, the name of the object that was modified by the cmdlet.<br/>            Mandatory: No|
|user_id|Gets or sets UPN (User Principal Name) of the user who performed the action (specified in the Operation property) that resulted in the record being logged; <br/>            for example, my_name@my_domain_name. <br/>            Note that records for activity performed by system accounts (such as SHAREPOINT\system or NT AUTHORITY\SYSTEM) are also included.<br/>            Mandatory: Yes|
|azure_active_directory_event_type|Gets or sets type of Azure AD event.<br/>            Mandatory: Yes|
|extended_properties|Gets or sets list of extended properties for the setting being changed. Each property will have a Name and Value.<br/>            Mandatory: No|
|client|Gets or sets details about the client device, device OS, and device browser that was used for the of the account login event.<br/>            Mandatory: No|
|login_status|Gets or sets login status<br/>            Mandatory: Yes|
|user_domain|Gets or sets Tenant Identity Information (TII).<br/>            Mandatory: Yes|

### See Also

* namespace [aspose.email.clients.activity](/email/python-net/aspose.email.clients.activity/)
* assembly [Aspose.Email](/email/python-net/)

