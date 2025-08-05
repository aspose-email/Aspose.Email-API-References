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
| None | `0` | Method is not defined. |
| Publish | `1` | Post notification of an object. Used primarily as a method of advertising the existence of an object. |
| Request | `2` | Assign an object. This is an explicit assignment to one or more Calendar Users. The REQUEST method is also used to update or change an existing object. Clients that cannot handle REQUEST MAY degrade the method to treat it as a PUBLISH. |
| Reply | `3` | Reply to an object request. |
| Add | `4` | Add one or more instances to an existing object. |
| Cancel | `5` | Cancel one or more instances of an existing object. |
| Refresh | `6` | A request sent to an object Organizer asking for the latest version of an object. |
| Counter | `7` | Counter a REQUEST with an alternative proposal. |
| DeclineCounter | `8` | Decline a counter proposal by an Attendee. |

### See Also

* namespace [Aspose.Email.Calendar](../../aspose.email.calendar/)
* assembly [Aspose.Email](../../)


