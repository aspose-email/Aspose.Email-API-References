---
title: Class CalendarInfo
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Graph.CalendarInfo class. Represents information about calendar
type: docs
weight: 15940
url: /net/aspose.email.clients.graph/calendarinfo/
---
## CalendarInfo class

Represents information about calendar.

```csharp
public class CalendarInfo : BaseRestObject
```

## Properties

| Name | Description |
| --- | --- |
| [CanEdit](../../aspose.email.clients.graph/calendarinfo/canedit/) { get; set; } | true if the user can write to the calendar, false otherwise. |
| [CanShare](../../aspose.email.clients.graph/calendarinfo/canshare/) { get; set; } | true if the user has the permission to share the calendar, false otherwise. Only the user who created the calendar can share it. |
| [CanViewPrivateItems](../../aspose.email.clients.graph/calendarinfo/canviewprivateitems/) { get; set; } | true if the user can read calendar items that have been marked private, false otherwise. |
| [Color](../../aspose.email.clients.graph/calendarinfo/color/) { get; set; } | Specifies the color theme to distinguish the calendar from other calendars in a UI. The property values are: auto, lightBlue, lightGreen, lightOrange, lightGray, lightYellow, lightTeal, lightPink, lightBrown, lightRed, maxColor. |
| [DefaultOnlineMeetingProvider](../../aspose.email.clients.graph/calendarinfo/defaultonlinemeetingprovider/) { get; set; } | The default online meeting provider for meetings sent from this calendar. Possible values are: unknown, skypeForBusiness, skypeForConsumer, teamsForBusiness. |
| [IsDefaultCalendar](../../aspose.email.clients.graph/calendarinfo/isdefaultcalendar/) { get; set; } | true if this is the default calendar where new events are created by default, false otherwise. |
| [IsRemovable](../../aspose.email.clients.graph/calendarinfo/isremovable/) { get; set; } | Indicates whether this user calendar can be deleted from the user mailbox. |
| [IsTallyingResponses](../../aspose.email.clients.graph/calendarinfo/istallyingresponses/) { get; set; } | Indicates whether this user calendar supports tracking of meeting responses. Only meeting invites sent from users' primary calendars support tracking of meeting responses. |
| virtual [ItemId](../../aspose.email.clients.graph/calendarinfo/itemid/) { get; } | Gets string representation of entry ID. |
| virtual [Name](../../aspose.email.clients.graph/calendarinfo/name/) { get; set; } | Gets or sets the name of Calendar. |
| [Owner](../../aspose.email.clients.graph/calendarinfo/owner/) { get; set; } | If set, this represents the user who created or added the calendar. For a calendar that the user created or added, the owner property is set to the user. For a calendar shared with the user, the owner property is set to the person who shared that calendar with the user. |
| virtual [Properties](../../aspose.email.clients.graph/baserestobject/properties/) { get; } | Gets the mapi properties. |

### See Also

* class [BaseRestObject](../baserestobject/)
* namespace [Aspose.Email.Clients.Graph](../../aspose.email.clients.graph/)
* assembly [Aspose.Email](../../)


