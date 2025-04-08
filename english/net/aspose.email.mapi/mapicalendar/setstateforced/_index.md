---
title: MapiCalendar.SetStateForced
second_title: Aspose.Email for .NET API Reference
description: MapiCalendar method. Sets the state of the calendar object overriding any default behavior
type: docs
weight: 240
url: /net/aspose.email.mapi/mapicalendar/setstateforced/
---
## MapiCalendar.SetStateForced method

Sets the state of the calendar object, overriding any default behavior.

```csharp
public void SetStateForced(MapiCalendarState state)
```

| Parameter | Type | Description |
| --- | --- | --- |
| state | MapiCalendarState | The new state to apply to the calendar object. |

## Remarks

By default, when a meeting is created, its state is Meeting. When the meeting is received in a recipient's inbox, it changes to Received and its message class is set to "IPM.Schedule.Meeting.Request". Using this method to set the state to Received manually may prevent the item from being sent to other recipients correctly. However, it allows the organizer information to be visible in the saved MSG file.

### See Also

* enum [MapiCalendarState](../../mapicalendarstate/)
* class [MapiCalendar](../)
* namespace [Aspose.Email.Mapi](../../mapicalendar/)
* assembly [Aspose.Email](../../../)


