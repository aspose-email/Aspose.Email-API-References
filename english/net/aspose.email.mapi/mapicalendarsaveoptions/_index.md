---
title: Class MapiCalendarSaveOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiCalendarSaveOptions class. The base class for the options of saving a MapiCalendar. The derived class selects the format
type: docs
weight: 16900
url: /net/aspose.email.mapi/mapicalendarsaveoptions/
---
## MapiCalendarSaveOptions class

The base class for the options of saving a [`MapiCalendar`](../mapicalendar/). The derived class selects the format.

```csharp
public abstract class MapiCalendarSaveOptions
```

## Properties

| Name | Description |
| --- | --- |
| [ProductIdentifier](../../aspose.email.mapi/mapicalendarsaveoptions/productidentifier/) { get; set; } | Gets or sets the identifier of the product that created the iCalendar file, written to its `PRODID` property. |
| [SaveFormat](../../aspose.email.mapi/mapicalendarsaveoptions/saveformat/) { get; } | Gets the format these options save to. |
| static [DefaultIcs](../../aspose.email.mapi/mapicalendarsaveoptions/defaultics/) { get; } | Gets new iCalendar save options with the default settings. |
| static [DefaultMsg](../../aspose.email.mapi/mapicalendarsaveoptions/defaultmsg/) { get; } | Gets new MSG save options with the default settings. |

## Methods

| Name | Description |
| --- | --- |
| static [FromSaveFormat](../../aspose.email.mapi/mapicalendarsaveoptions/fromsaveformat/)(AppointmentSaveFormat) | Gets the default save options for the specified format. |

## Remarks

Use [`MapiCalendarIcsSaveOptions`](../mapicalendaricssaveoptions/) for iCalendar and [`MapiCalendarMsgSaveOptions`](../mapicalendarmsgsaveoptions/) for MSG, or get the default options with [`DefaultIcs`](./defaultics/), [`DefaultMsg`](./defaultmsg/) or [`FromSaveFormat`](./fromsaveformat/).

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


