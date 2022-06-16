---
title: ResolveRecipientsRequest
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 1860
url: /net/aspose.email.clients.activesync.transportlayer/resolverecipientsrequest/
---
## ResolveRecipientsRequest class

Contains information to resolve recipients.

```csharp
public class ResolveRecipientsRequest
```

## Constructors

| Name | Description |
| --- | --- |
| [ResolveRecipientsRequest](resolverecipientsrequest)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Options](../../aspose.email.clients.activesync.transportlayer/resolverecipientsrequest/options) { get; set; } | Contains the options for resolving the list of recipients. |
| [To](../../aspose.email.clients.activesync.transportlayer/resolverecipientsrequest/to) { get; } | Specifies one or more recipients to be resolved. Value can be up to 256 characters in length. The result of including more than 1000 To elements in the request is undefined. The server MAY return a protocol status error in response to such a command request. If the ResolveRecipients command request includes the Availability, a maximum of 100 To elements containing SMTP addresses can be included in the request. If more than 100 SMTP addresses are included in the request, Status value 160 is returned in the response. If the ResolveRecipients command request includes the Availability and includes a To element for an ambiguous user, the response does not include a MergedFreeBusy element for that user. Only users or distribution lists specified with valid SMTP addresses or a uniquely identifiable string in the request message To element have MergedFreeBusy elements included in the response. If the ResolveRecipients command request includes the Availability and the To element specifies a distribution group, then the availability data is returned as a single string that merges the data for the individual members of the distribution group. If the distribution group contains more than 20 members, a Status element value of 161 is returned in the response indicating that the merged free busy information of such a large distribution group is not useful. |

### See Also

* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->