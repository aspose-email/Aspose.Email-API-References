---
title: Class MapiCalendarSaveOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiCalendarSaveOptions class. Serves as the abstract base class for formatspecific options when saving MapiCalendar objects to various formats ICS MSG. This class provides common configuration properties such as save format and factory methods for creating formatspecific save options
type: docs
weight: 16900
url: /net/aspose.email.mapi/mapicalendarsaveoptions/
---
## MapiCalendarSaveOptions class

Serves as the abstract base class for format-specific options when saving [`MapiCalendar`](../mapicalendar/) objects to various formats (ICS, MSG). This class provides common configuration properties such as save format and factory methods for creating format-specific save options.

```csharp
public abstract class MapiCalendarSaveOptions
```

## Properties

| Name | Description |
| --- | --- |
| [ProductIdentifier](../../aspose.email.mapi/mapicalendarsaveoptions/productidentifier/) { get; set; } | Gets or sets the product identifier. |
| [SaveFormat](../../aspose.email.mapi/mapicalendarsaveoptions/saveformat/) { get; } | Gets a save format. |
| static [DefaultIcs](../../aspose.email.mapi/mapicalendarsaveoptions/defaultics/) { get; } | Gets the default Ics save options. |
| static [DefaultMsg](../../aspose.email.mapi/mapicalendarsaveoptions/defaultmsg/) { get; } | Gets the default Msg save options. |

## Methods

| Name | Description |
| --- | --- |
| static [FromSaveFormat](../../aspose.email.mapi/mapicalendarsaveoptions/fromsaveformat/)(AppointmentSaveFormat) | Gets the MapiCalendarSaveOptions from SaveFormat. |

## Remarks

This class is designed to be inherited by concrete format-specific classes like [`MapiCalendarIcsSaveOptions`](../mapicalendaricssaveoptions/) and [`MapiCalendarMsgSaveOptions`](../mapicalendarmsgsaveoptions/). Do not instantiate this class directly. Use the format-specific subclasses or the static factory methods like [`DefaultIcs`](./defaultics/), [`DefaultMsg`](./defaultmsg/), and [`FromSaveFormat`](./fromsaveformat/) to create appropriate save options for your target format.

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


