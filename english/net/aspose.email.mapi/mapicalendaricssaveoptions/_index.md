---
title: Class MapiCalendarIcsSaveOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiCalendarIcsSaveOptions class. Options for saving a MapiCalendar to iCalendar .ics format
type: docs
weight: 16790
url: /net/aspose.email.mapi/mapicalendaricssaveoptions/
---
## MapiCalendarIcsSaveOptions class

Options for saving a [`MapiCalendar`](../mapicalendar/) to iCalendar (.ics) format.

```csharp
public class MapiCalendarIcsSaveOptions : MapiCalendarSaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiCalendarIcsSaveOptions](mapicalendaricssaveoptions/)() | Initializes a new instance of the `MapiCalendarIcsSaveOptions` class. |

## Properties

| Name | Description |
| --- | --- |
| [KeepOriginalDateTimeStamp](../../aspose.email.mapi/mapicalendaricssaveoptions/keeporiginaldatetimestamp/) { get; set; } | Gets or sets a value indicating whether the original date and time stamp (`DTSTAMP`) of the item is written instead of the time of saving. |
| [ProductIdentifier](../../aspose.email.mapi/mapicalendarsaveoptions/productidentifier/) { get; set; } | Gets or sets the identifier of the product that created the iCalendar file, written to its `PRODID` property. |
| [SaveFormat](../../aspose.email.mapi/mapicalendarsaveoptions/saveformat/) { get; } | Gets the format these options save to. |

## Remarks

Pass an instance to [`Save`](../mapicalendar/save/). [`KeepOriginalDateTimeStamp`](./keeporiginaldatetimestamp/) keeps the `DTSTAMP` of the item, and the inherited [`ProductIdentifier`](../mapicalendarsaveoptions/productidentifier/) sets the `PRODID` of the file.

### See Also

* class [MapiCalendarSaveOptions](../mapicalendarsaveoptions/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


