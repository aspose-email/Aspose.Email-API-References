---
title: CalendarInfo
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 30
url: /python-net/aspose.email.clients.graph/calendarinfo/
---

## CalendarInfo class

Represents information about calendar.

The CalendarInfo type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|properties|Gets the mapi properties.|
|name|Gets or sets the name of Calendar.|
|item_id|Gets string representation of entry ID.|
|can_edit|true if the user can write to the calendar, false otherwise.|
|can_share|true if the user has the permission to share the calendar, false otherwise. Only the user who created the calendar can share it.|
|can_view_private_items|true if the user can read calendar items that have been marked private, false otherwise.|
|color|Specifies the color theme to distinguish the calendar from other calendars in a UI. The property values are: auto, lightBlue, lightGreen, lightOrange, lightGray, lightYellow, lightTeal, lightPink, lightBrown, lightRed, maxColor.|
|default_online_meeting_provider|The default online meeting provider for meetings sent from this calendar. Possible values are: unknown, skypeForBusiness, skypeForConsumer, teamsForBusiness.|
|is_default_calendar|true if this is the default calendar where new events are created by default, false otherwise.|
|is_removable|Indicates whether this user calendar can be deleted from the user mailbox.|
|is_tallying_responses|Indicates whether this user calendar supports tracking of meeting responses. Only meeting invites sent from users' primary calendars support tracking of meeting responses.|
|owner|If set, this represents the user who created or added the calendar. For a calendar that the user created or added, the owner property is set to the user. For a calendar shared with the user, the owner property is set to the person who shared that calendar with the user.|

### See Also

* namespace [aspose.email.clients.graph](/email/python-net/aspose.email.clients.graph/)
* assembly [Aspose.Email](/email/python-net/)

