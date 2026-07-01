---
title: Class MapiCalendarIcsSaveOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiCalendarIcsSaveOptions class. Provides options for controlling how MapiCalendar instances are saved to iCalendar ICS format. This class extends MapiCalendarSaveOptions and adds iCalendarspecific configuration options for date/time handling and product identification
type: docs
weight: 16790
url: /net/aspose.email.mapi/mapicalendaricssaveoptions/
---
## MapiCalendarIcsSaveOptions class

Provides options for controlling how [`MapiCalendar`](../mapicalendar/) instances are saved to iCalendar (ICS) format. This class extends [`MapiCalendarSaveOptions`](../mapicalendarsaveoptions/) and adds iCalendar-specific configuration options for date/time handling and product identification.

```csharp
public class MapiCalendarIcsSaveOptions : MapiCalendarSaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiCalendarIcsSaveOptions](mapicalendaricssaveoptions/)() | Initializes a new instance of the [`MapiCalendarSaveOptions`](../mapicalendarsaveoptions/) class |

## Properties

| Name | Description |
| --- | --- |
| [KeepOriginalDateTimeStamp](../../aspose.email.mapi/mapicalendaricssaveoptions/keeporiginaldatetimestamp/) { get; set; } | Gets or sets a value indicating whether to keep the original date and time stamps when saving to iCalendar format. When set to true, the original timestamp information is preserved in the output ICS file. |
| [ProductIdentifier](../../aspose.email.mapi/mapicalendarsaveoptions/productidentifier/) { get; set; } | Gets or sets the product identifier. |
| [SaveFormat](../../aspose.email.mapi/mapicalendarsaveoptions/saveformat/) { get; } | Gets a save format. |

## Remarks

Use this class with [`Save`](../mapicalendar/save/) to save calendar items in iCalendar format. The [`KeepOriginalDateTimeStamp`](./keeporiginaldatetimestamp/) property controls whether original date/time stamps are preserved, and !:ProductIdentifier allows you to specify the product identifier for the generated iCalendar object.

### See Also

* class [MapiCalendarSaveOptions](../mapicalendarsaveoptions/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


