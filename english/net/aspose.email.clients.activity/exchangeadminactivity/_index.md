---
title: Class ExchangeAdminActivity
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Activity.ExchangeAdminActivity class. Extends the Common schema with the properties specific to all Exchange admin audit data
type: docs
weight: 2480
url: /net/aspose.email.clients.activity/exchangeadminactivity/
---
## ExchangeAdminActivity class

Extends the Common schema with the properties specific to all Exchange admin audit data.

```csharp
public class ExchangeAdminActivity : Content
```

## Constructors

| Name | Description |
| --- | --- |
| [ExchangeAdminActivity](exchangeadminactivity/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ClientIP](../../aspose.email.clients.activity/content/clientip/) { get; set; } | The IP address of the device that was used when the activity was logged. The IP address is displayed in either an IPv4 or IPv6 address format. Mandatory: Yes |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime/) { get; set; } | The date and time in Coordinated Universal Time (UTC) when the user performed the activity. Mandatory: Yes |
| [ExternalAccess](../../aspose.email.clients.activity/exchangeadminactivity/externalaccess/) { get; set; } | Specifies whether the cmdlet was run by a user in your organization, by Microsoft datacenter personnel or a datacenter service account, or by a delegated administrator. The value False indicates that the cmdlet was run by someone in your organization. The value True indicates that the cmdlet was run by datacenter personnel, a datacenter service account, or a delegated administrator. |
| [Id](../../aspose.email.clients.activity/content/id/) { get; set; } | Unique identifier of an audit record. Mandatory: Yes |
| [ModifiedObjectResolvedName](../../aspose.email.clients.activity/exchangeadminactivity/modifiedobjectresolvedname/) { get; set; } | This is the user friendly name of the object that was modified by the cmdlet. This is logged only if the cmdlet modifies the object. |
| [ModifiedProperties](../../aspose.email.clients.activity/exchangeadminactivity/modifiedproperties/) { get; set; } | The property is included for admin events. The property includes the name of the property that was modified, the new value of the modified property, and the previous value of the modified object. |
| [ObjectId](../../aspose.email.clients.activity/content/objectid/) { get; set; } | For SharePoint and OneDrive for Business activity, the full path name of the file or folder accessed by the user. For Exchange admin audit logging, the name of the object that was modified by the cmdlet. Mandatory: No |
| [Operation](../../aspose.email.clients.activity/content/operation/) { get; set; } | The name of the user or admin activity. For a description of the most common operations/activities, see Search the audit log in the Office 365 Protection Center. For Exchange admin activity, this property identifies the name of the cmdlet that was run. For Dlp events, this can be "DlpRuleMatch", "DlpRuleUndo" or "DlpInfo", which are described under "DLP schema" below. Mandatory: Yes |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid/) { get; set; } | The GUID for your organization's Office 365 tenant. This value will always be the same for your organization, regardless of the Office 365 service in which it occurs. Mandatory: Yes |
| [OrganizationName](../../aspose.email.clients.activity/exchangeadminactivity/organizationname/) { get; set; } | The name of the tenant. |
| [OriginatingServer](../../aspose.email.clients.activity/exchangeadminactivity/originatingserver/) { get; set; } | The name of the server from which the cmdlet was executed. |
| [Parameters](../../aspose.email.clients.activity/exchangeadminactivity/parameters/) { get; set; } | The name and value for all parameters that were used with the cmdlet that is identified in the Operations property. |
| [RecordType](../../aspose.email.clients.activity/content/recordtype/) { get; set; } | The type of operation indicated by the record. Mandatory: Yes |
| [ResultStatus](../../aspose.email.clients.activity/content/resultstatus/) { get; set; } | Indicates whether the action (specified in the Operation property) was successful or not. Possible values are Succeeded, PartiallySucceded, or Failed. For Exchange admin activity, the value is either True or False. Mandatory: No |
| [Scope](../../aspose.email.clients.activity/content/scope/) { get; set; } | Was this event created by a hosted O365 service or an on-premises server? Possible values are online and onprem. Note that SharePoint is the only workload currently sending events from on-premises to O365. Mandatory: No |
| [UserId](../../aspose.email.clients.activity/content/userid/) { get; set; } | The UPN (User Principal Name) of the user who performed the action (specified in the Operation property) that resulted in the record being logged; for example, my_name@my_domain_name. Note that records for activity performed by system accounts (such as SHAREPOINT\system or NT AUTHORITY\SYSTEM) are also included. Mandatory: Yes |
| [UserKey](../../aspose.email.clients.activity/content/userkey/) { get; set; } | An alternative ID for the user identified in the UserId property. For example, this property is populated with the passport unique ID (PUID) for events performed by users in SharePoint, OneDrive for Business, and Exchange. This property may also specify the same value as the UserID property for events occurring in other services and events performed by system accounts. Mandatory: Yes |
| [UserType](../../aspose.email.clients.activity/content/usertype/) { get; set; } | The type of user that performed the operation. Mandatory: Yes |
| [Workload](../../aspose.email.clients.activity/content/workload/) { get; set; } | The Office 365 service where the activity occurred in the Workload string. The possible values for this property are: Exchange SharePoint OneDrive AzureActiveDirectory SecurityComplianceCenter Sway ThreatIntelligence Mandatory: No |

### See Also

* class [Content](../content/)
* namespace [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity/)
* assembly [Aspose.Email](../../)


