---
title: Class FreebusyQuery
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Google.FreebusyQuery class. Request free/busy information for a set of calendars
type: docs
weight: 15770
url: /net/aspose.email.clients.google/freebusyquery/
---
## FreebusyQuery class

Request free/busy information for a set of calendars.

```csharp
public class FreebusyQuery
```

## Constructors

| Name | Description |
| --- | --- |
| [FreebusyQuery](freebusyquery/#constructor)() | Initializes a new instance of the FreebusyQuery class. |
| [FreebusyQuery](freebusyquery/#constructor_1)(DateTime, DateTime, IEnumerable&lt;string&gt;) | Initializes a new instance of the FreebusyQuery class. |
| [FreebusyQuery](freebusyquery/#constructor_6)(DateTime, DateTime, params string[]) | Initializes a new instance of the FreebusyQuery class. |
| [FreebusyQuery](freebusyquery/#constructor_2)(DateTime, DateTime, string, IEnumerable&lt;string&gt;) | Initializes a new instance of the FreebusyQuery class. |
| [FreebusyQuery](freebusyquery/#constructor_5)(DateTime, DateTime, string, params string[]) | Initializes a new instance of the FreebusyQuery class. |
| [FreebusyQuery](freebusyquery/#constructor_3)(DateTime, DateTime, string, int?, int?, IEnumerable&lt;string&gt;) | Initializes a new instance of the FreebusyQuery class. |
| [FreebusyQuery](freebusyquery/#constructor_4)(DateTime, DateTime, string, int?, int?, params string[]) | Initializes a new instance of the FreebusyQuery class. |

## Properties

| Name | Description |
| --- | --- |
| [CalendarExpansionMax](../../aspose.email.clients.google/freebusyquery/calendarexpansionmax/) { get; set; } | Maximal number of calendars for which FreeBusy information is to be provided. Optional. |
| [GroupExpansionMax](../../aspose.email.clients.google/freebusyquery/groupexpansionmax/) { get; set; } | Maximal number of calendar identifiers to be provided for a single group. Optional. An error will be returned for a group with more members than this value. |
| [Items](../../aspose.email.clients.google/freebusyquery/items/) { get; } | List of calendars and/or groups to query. Contains identifiers of a calendar or a group. |
| [TimeMax](../../aspose.email.clients.google/freebusyquery/timemax/) { get; set; } | The end of the interval for the query. |
| [TimeMin](../../aspose.email.clients.google/freebusyquery/timemin/) { get; set; } | The start of the interval for the query. |
| [TimeZone](../../aspose.email.clients.google/freebusyquery/timezone/) { get; set; } | Time zone used in the response. Optional. The default is UTC. |

### See Also

* namespace [Aspose.Email.Clients.Google](../../aspose.email.clients.google/)
* assembly [Aspose.Email](../../)


