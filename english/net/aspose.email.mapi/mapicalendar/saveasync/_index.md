---
title: MapiCalendar.SaveAsync
second_title: Aspose.Email for .NET API Reference
description: MapiCalendar method. Saves calendar to the file with specified save options asynchronously
type: docs
weight: 270
url: /net/aspose.email.mapi/mapicalendar/saveasync/
---
## SaveAsync(string, MapiCalendarSaveOptions, CancellationToken) {#saveasync_4}

Saves calendar to the file with specified save options asynchronously.

```csharp
public Task SaveAsync(string filePath, MapiCalendarSaveOptions saveOptions, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A file path |
| saveOptions | MapiCalendarSaveOptions | A save options |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty` |
| NotSupportedException | the specified save options are not supported |

### See Also

* class [MapiCalendarSaveOptions](../../mapicalendarsaveoptions/)
* class [MapiCalendar](../)
* namespace [Aspose.Email.Mapi](../../mapicalendar/)
* assembly [Aspose.Email](../../../)

---

## SaveAsync(Stream, MapiCalendarSaveOptions, CancellationToken) {#saveasync_1}

Saves calendar to the stream with specified save options asynchronously.

```csharp
public Task SaveAsync(Stream stream, MapiCalendarSaveOptions saveOptions, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to save to |
| saveOptions | MapiCalendarSaveOptions | A save options |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *saveOptions* or *stream* is `null` |
| NotSupportedException | the specified save options are not supported |
| NotSupportedException | stream does not support writing |

### See Also

* class [MapiCalendarSaveOptions](../../mapicalendarsaveoptions/)
* class [MapiCalendar](../)
* namespace [Aspose.Email.Mapi](../../mapicalendar/)
* assembly [Aspose.Email](../../../)

---

## SaveAsync(string, CancellationToken) {#saveasync_5}

Saves calendar object to the file with iCalendar format using the default save options asynchronously.

```csharp
public Task SaveAsync(string filePath, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A file path |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty` |

### See Also

* class [MapiCalendar](../)
* namespace [Aspose.Email.Mapi](../../mapicalendar/)
* assembly [Aspose.Email](../../../)

---

## SaveAsync(string, AppointmentSaveFormat, CancellationToken) {#saveasync_3}

Saves calendar object to the file with specified format using the default save options asynchronously.

```csharp
public Task SaveAsync(string filePath, AppointmentSaveFormat saveFormat, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A file path |
| saveFormat | AppointmentSaveFormat | A save format |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty` |
| NotSupportedException | The specified *saveFormat* is not supported |

### See Also

* enum [AppointmentSaveFormat](../../../aspose.email.calendar/appointmentsaveformat/)
* class [MapiCalendar](../)
* namespace [Aspose.Email.Mapi](../../mapicalendar/)
* assembly [Aspose.Email](../../../)

---

## SaveAsync(Stream, CancellationToken) {#saveasync_2}

Saves calendar object to the file with iCalendar format using the default save options asynchronously.

```csharp
public Task SaveAsync(Stream stream, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to save to |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null` |
| NotSupportedException | stream does not support writing |

### See Also

* class [MapiCalendar](../)
* namespace [Aspose.Email.Mapi](../../mapicalendar/)
* assembly [Aspose.Email](../../../)

---

## SaveAsync(Stream, AppointmentSaveFormat, CancellationToken) {#saveasync}

Saves calendar object to the stream with specified format using the default save options asynchronously.

```csharp
public Task SaveAsync(Stream stream, AppointmentSaveFormat saveFormat, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to save to |
| saveFormat | AppointmentSaveFormat | A save format |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null` |
| NotSupportedException | The specified *saveFormat* is not supported |
| NotSupportedException | stream does not support writing |

### See Also

* enum [AppointmentSaveFormat](../../../aspose.email.calendar/appointmentsaveformat/)
* class [MapiCalendar](../)
* namespace [Aspose.Email.Mapi](../../mapicalendar/)
* assembly [Aspose.Email](../../../)


