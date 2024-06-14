---
title: Enum CalendarRoleType
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Graph.CalendarRoleType enum. Represent sharing or delegating permission levels for the calendar
type: docs
weight: 15900
url: /net/aspose.email.clients.graph/calendarroletype/
---
## CalendarRoleType enumeration

Represent sharing or delegating permission levels for the calendar.

```csharp
public enum CalendarRoleType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | Calendar isn't shared with the user. |
| FreeBusyRead | `1` | User is a recipient who can view free/busy status of the owner on the calendar. |
| LimitedRead | `2` | User is a recipient who can view free/busy status, and titles and locations of the events on the calendar. |
| Read | `3` | User is a recipient who can view all the details of the events on the calendar, except for the owner's private events. |
| Write | `4` | User is a recipient who can view all the details (except for private events) and edit events on the calendar. |
| DelegateWithoutPrivateEventAccess | `5` | User is a delegate who has write access but can't view information of the owner's private events on the calendar. |
| DelegateWithPrivateEventAccess | `6` | User is a delegate who has write access and can view information of the owner's private events on the calendar. |
| Custom | `7` | User has custom permissions to the calendar. |

### See Also

* namespace [Aspose.Email.Clients.Graph](../../aspose.email.clients.graph/)
* assembly [Aspose.Email](../../)


