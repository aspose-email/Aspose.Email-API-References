---
title: MapiCalendar.Save
second_title: Aspose.Email for .NET API Reference
description: MapiCalendar method. Saves the calendar item to a file with the specified options
type: docs
weight: 260
url: /net/aspose.email.mapi/mapicalendar/save/
---
## Save(string, MapiCalendarSaveOptions) {#save_5}

Saves the calendar item to a file with the specified options.

```csharp
public void Save(string filePath, MapiCalendarSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path of the file to write. |
| saveOptions | MapiCalendarSaveOptions | The options; they also select the format: [`MapiCalendarIcsSaveOptions`](../../mapicalendaricssaveoptions/) for iCalendar, [`MapiCalendarMsgSaveOptions`](../../mapicalendarmsgsaveoptions/) for MSG. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or empty. |
| NotSupportedException | The format of *saveOptions* is not supported. |

### See Also

* class [MapiCalendarSaveOptions](../../mapicalendarsaveoptions/)
* class [MapiCalendar](../)
* namespace [Aspose.Email.Mapi](../../mapicalendar/)
* assembly [Aspose.Email](../../../)

---

## Save(Stream, MapiCalendarSaveOptions) {#save_2}

Saves the calendar item to a stream with the specified options.

```csharp
public void Save(Stream stream, MapiCalendarSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to write to. |
| saveOptions | MapiCalendarSaveOptions | The options; they also select the format: [`MapiCalendarIcsSaveOptions`](../../mapicalendaricssaveoptions/) for iCalendar, [`MapiCalendarMsgSaveOptions`](../../mapicalendarmsgsaveoptions/) for MSG. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* or *saveOptions* is `null`. |
| NotSupportedException | The format of *saveOptions* is not supported. |
| NotSupportedException | *stream* does not support writing. |

### See Also

* class [MapiCalendarSaveOptions](../../mapicalendarsaveoptions/)
* class [MapiCalendar](../)
* namespace [Aspose.Email.Mapi](../../mapicalendar/)
* assembly [Aspose.Email](../../../)

---

## Save(string) {#save_3}

Saves the calendar item to an iCalendar (.ics) file with the default options.

```csharp
public void Save(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path of the file to write. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or empty. |

### See Also

* class [MapiCalendar](../)
* namespace [Aspose.Email.Mapi](../../mapicalendar/)
* assembly [Aspose.Email](../../../)

---

## Save(string, AppointmentSaveFormat) {#save_4}

Saves the calendar item to a file in the specified format with the default options.

```csharp
public void Save(string filePath, AppointmentSaveFormat saveFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path of the file to write. |
| saveFormat | AppointmentSaveFormat | The format: ICS or MSG. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or empty. |
| NotSupportedException | *saveFormat* is not supported. |

### See Also

* enum [AppointmentSaveFormat](../../../aspose.email.calendar/appointmentsaveformat/)
* class [MapiCalendar](../)
* namespace [Aspose.Email.Mapi](../../mapicalendar/)
* assembly [Aspose.Email](../../../)

---

## Save(Stream) {#save}

Saves the calendar item to a stream in iCalendar format with the default options.

```csharp
public void Save(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to write to. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support writing. |

### See Also

* class [MapiCalendar](../)
* namespace [Aspose.Email.Mapi](../../mapicalendar/)
* assembly [Aspose.Email](../../../)

---

## Save(Stream, AppointmentSaveFormat) {#save_1}

Saves the calendar item to a stream in the specified format with the default options.

```csharp
public void Save(Stream stream, AppointmentSaveFormat saveFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to write to. |
| saveFormat | AppointmentSaveFormat | The format: ICS or MSG. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *saveFormat* is not supported. |
| NotSupportedException | *stream* does not support writing. |

### See Also

* enum [AppointmentSaveFormat](../../../aspose.email.calendar/appointmentsaveformat/)
* class [MapiCalendar](../)
* namespace [Aspose.Email.Mapi](../../mapicalendar/)
* assembly [Aspose.Email](../../../)


