---
title: Class Record
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Activity.Record class. Audit log record
type: docs
weight: 2720
url: /net/aspose.email.clients.activity/record/
---
## Record class

Audit log record

```csharp
public class Record
```

## Constructors

| Name | Description |
| --- | --- |
| [Record](record/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AzureActiveDirectoryEventType](../../aspose.email.clients.activity/record/azureactivedirectoryeventtype/) { get; set; } | Gets or sets type of Azure AD event. Mandatory: Yes |
| [Client](../../aspose.email.clients.activity/record/client/) { get; set; } | Gets or sets details about the client device, device OS, and device browser that was used for the of the account login event. Mandatory: No |
| [ClientIP](../../aspose.email.clients.activity/record/clientip/) { get; set; } | Gets or sets IP address of the device that was used when the activity was logged. The IP address is displayed in either an IPv4 or IPv6 address format. Mandatory: Yes |
| [CreationTime](../../aspose.email.clients.activity/record/creationtime/) { get; set; } | Gets or sets date and time in Coordinated Universal Time (UTC) when the user performed the activity. Mandatory: Yes |
| [ExtendedProperties](../../aspose.email.clients.activity/record/extendedproperties/) { get; set; } | Gets or sets list of extended properties for the setting being changed. Each property will have a Name and Value. Mandatory: No |
| [Id](../../aspose.email.clients.activity/record/id/) { get; set; } | Gets or sets unique identifier of an audit record. Mandatory: Yes |
| [LoginStatus](../../aspose.email.clients.activity/record/loginstatus/) { get; set; } | Gets or sets login status Mandatory: Yes |
| [ObjectId](../../aspose.email.clients.activity/record/objectid/) { get; set; } | Gets or sets object identifier. For SharePoint and OneDrive for Business activity, the full path name of the file or folder accessed by the user. For Exchange admin audit logging, the name of the object that was modified by the cmdlet. Mandatory: No |
| [Operation](../../aspose.email.clients.activity/record/operation/) { get; set; } | Gets or sets name of the user or admin activity. For a description of the most common operations/activities, see Search the audit log in the Office 365 Protection Center. For Exchange admin activity, this property identifies the name of the cmdlet that was run. For Dlp events, this can be "DlpRuleMatch", "DlpRuleUndo" or "DlpInfo", which are described under "DLP schema" below. Mandatory: Yes |
| [OrganizationId](../../aspose.email.clients.activity/record/organizationid/) { get; set; } | Gets or sets GUID for your organization's Office 365 tenant. This value will always be the same for your organization, regardless of the Office 365 service in which it occurs. Mandatory: Yes |
| [RecordType](../../aspose.email.clients.activity/record/recordtype/) { get; set; } | Gets or sets type of operation indicated by the record. Mandatory: Yes |
| [ResultStatus](../../aspose.email.clients.activity/record/resultstatus/) { get; set; } | Gets or sets value which indicates whether the action (specified in the Operation property) was successful or not. Mandatory: No |
| [UserDomain](../../aspose.email.clients.activity/record/userdomain/) { get; set; } | Gets or sets Tenant Identity Information (TII). Mandatory: Yes |
| [UserId](../../aspose.email.clients.activity/record/userid/) { get; set; } | Gets or sets UPN (User Principal Name) of the user who performed the action (specified in the Operation property) that resulted in the record being logged; for example, my_name@my_domain_name. Note that records for activity performed by system accounts (such as SHAREPOINT\system or NT AUTHORITY\SYSTEM) are also included. Mandatory: Yes |
| [UserKey](../../aspose.email.clients.activity/record/userkey/) { get; set; } | Gets or sets an alternative ID for the user identified in the UserId property. For example, this property is populated with the passport unique ID (PUID) for events performed by users in SharePoint, OneDrive for Business, and Exchange. This property may also specify the same value as the UserID property for events occurring in other services and events performed by system accounts. Mandatory: Yes |
| [UserType](../../aspose.email.clients.activity/record/usertype/) { get; set; } | Gets or sets type of user that performed the operation. Mandatory: Yes |
| [Workload](../../aspose.email.clients.activity/record/workload/) { get; set; } | Gets or sets Office 365 service where the activity occurred. Mandatory: No |

### See Also

* namespace [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity/)
* assembly [Aspose.Email](../../)


