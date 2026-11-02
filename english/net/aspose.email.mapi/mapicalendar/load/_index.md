---
title: MapiCalendar.Load
second_title: Aspose.Email for .NET API Reference
description: MapiCalendar method. Loads a MapiCalendar from the specified file
type: docs
weight: 30
url: /net/aspose.email.mapi/mapicalendar/load/
---
## Load(string) {#load_1}

Loads a [`MapiCalendar`](../) from the specified file.

```csharp
public static MapiCalendar Load(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path to the file to be loaded. |

### Return Value

Returns a [`MapiCalendar`](../) instance loaded from the specified file.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty`. |
| FileNotFoundException | The specified file does not exist. |
| InvalidOperationException | The file holds neither a calendar item nor an iCalendar. |

## Remarks

Accepts both formats [`Save`](../save/) can produce: an Outlook MSG file holding a calendar item, and an iCalendar file (read as [`FromIcs`](../fromics/) would, with encoding detection). This makes `MapiCalendar.Load(path)` the inverse of `calendar.Save(path)`, which writes iCalendar by default.

### See Also

* class [MapiCalendar](../)
* namespace [Aspose.Email.Mapi](../../mapicalendar/)
* assembly [Aspose.Email](../../../)

---

## Load(Stream) {#load}

Loads a [`MapiCalendar`](../) from the specified stream.

```csharp
public static MapiCalendar Load(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to be loaded. |

### Return Value

Returns a [`MapiCalendar`](../) instance loaded from the specified stream.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support reading. |
| InvalidOperationException | The stream holds neither a calendar item nor an iCalendar. |

## Remarks

Accepts both formats [`Save`](../save/) can produce: an Outlook MSG file holding a calendar item, and an iCalendar file (read as [`FromIcs`](../fromics/) would, with encoding detection). This makes `MapiCalendar.Load(path)` the inverse of `calendar.Save(path)`, which writes iCalendar by default.

The stream is read from its beginning, whatever its current position.

### See Also

* class [MapiCalendar](../)
* namespace [Aspose.Email.Mapi](../../mapicalendar/)
* assembly [Aspose.Email](../../../)


