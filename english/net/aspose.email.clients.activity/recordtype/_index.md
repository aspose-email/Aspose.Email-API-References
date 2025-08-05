---
title: Enum RecordType
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Activity.RecordType enum. Audit record types
type: docs
weight: 1280
url: /net/aspose.email.clients.activity/recordtype/
---
## RecordType enumeration

Audit record types

```csharp
public enum RecordType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| ExchangeAdmin | `1` | Events from the Exchange admin audit log. |
| ExchangeItem | `2` | Events from an Exchange mailbox audit log for actions that are performed on a single item, such as creating or receiving an email message. |
| ExchangeItemGroup | `3` | Events from an Exchange mailbox audit log for actions that can be performed on multiple items, such as moving or deleted one or more email messages. |
| SharePoint | `4` | SharePoint events. |
| SharePointFileOperation | `6` | SharePoint file operation events. |
| AzureActiveDirectory | `8` | Azure Active Directory events. |
| AzureActiveDirectoryAccountLogon | `9` | Azure Active Directory OrgId logon events (deprecating). |
| DataCenterSecurityCmdlet | `10` | Data Center security cmdlet events. |
| ComplianceDLPSharePoint | `11` | Data loss protection (DLP) events in SharePoint and OneDrive for Business. |
| Sway | `12` | Events from the Sway service and clients. |
| ComplianceDLPExchange | `13` | Data loss protection (DLP) events in Exchange, when configured via Unified DLP Policy. DLP events based on Exchange Transport Rules are not supported. |
| SharePointSharingOperation | `14` | SharePoint sharing events. |
| AzureActiveDirectoryStsLogon | `15` | Secure Token Service (STS) logon events in Azure Active Directory. |
| SecurityComplianceCenterEOPCmdlet | `18` |  |
| PowerBIAudit | `20` | Power BI events. |
| CRM | `21` | Microsoft CRM events. |
| Yammer | `22` | Yammer events. |
| SkypeForBusinessCmdlets | `23` | Skype for Business events. |
| Discovery | `24` |  |
| MicrosoftTeams | `25` | Events from Microsoft Teams. |
| MicrosoftTeamsAddOns | `26` | Events from Microsoft Teams Add-ons. |
| MicrosoftTeamsSettingsOperation | `27` | Settings changes from Microsoft Teams. |
| ThreatIntelligence | `28` | Phishing and malware events from Exchange Online Protection and Office 365 Advanced Threat Protection. |
| MicrosoftFlow | `30` | Microsoft Flow events. |
| MicrosoftStream | `32` | Microsoft Stream events. |
| Project | `35` | Microsoft Project events. |
| SharepointListOperation | `36` | Sharepoint List events. |
| SecurityComplianceAlerts | `40` | Security and compliance alert signals. |
| ThreatIntelligenceUrl | `41` | Safe links time-of-block and block override events from Office 365 Advanced Threat Protection. |
| ThreatIntelligenceAtpContent | `47` | Phishing and malware events for files in SharePoint, OneDrive for Business, and Microsoft Teams from Office 365 Advanced Threat Protection. |

### See Also

* namespace [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity/)
* assembly [Aspose.Email](../../)


