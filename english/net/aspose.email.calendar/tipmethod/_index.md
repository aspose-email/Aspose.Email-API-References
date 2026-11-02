---
title: Enum TIPMethod
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Calendar.TIPMethod enum. Defines the iTIP iCalendar TransportIndependent Interoperability Protocol methods associated with an object
type: docs
weight: 870
url: /net/aspose.email.calendar/tipmethod/
---
## TIPMethod enumeration

Defines the iTIP (iCalendar Transport-Independent Interoperability Protocol) methods associated with an object.

```csharp
public enum TIPMethod
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | The method is not set. |
| Publish | `1` | Publishes an object to share it, without assigning it to anyone. |
| Request | `2` | Assigns an object to one or more calendar users, or updates an existing one. Clients that cannot handle a request may treat it as a publication. |
| Reply | `3` | Replies to a request, for example to accept or decline it. |
| Add | `4` | Adds one or more instances to an existing object. |
| Cancel | `5` | Cancels one or more instances of an existing object. |
| Refresh | `6` | Sent to the organizer to ask for the latest version of an object. |
| Counter | `7` | Proposes a change to a request. |
| DeclineCounter | `8` | Sent by the organizer to decline a proposed change. |

### See Also

* namespace [Aspose.Email.Calendar](../../aspose.email.calendar/)
* assembly [Aspose.Email](../../)


