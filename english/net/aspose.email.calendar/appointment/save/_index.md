---
title: Appointment.Save
second_title: Aspose.Email for .NET API Reference
description: Appointment method. Saves appointment to the stream with specified save options
type: docs
weight: 350
url: /net/aspose.email.calendar/appointment/save/
---
## Save(Stream, AppointmentSaveOptions) {#save_2}

Saves appointment to the stream with specified save options

```csharp
public void Save(Stream stream, AppointmentSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to save to |
| saveOptions | AppointmentSaveOptions | A save options |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *saveOptions* or *stream* is `null` |
| NotSupportedException | the specified save options are not supported |
| NotSupportedException | stream does not support writing |

### See Also

* class [AppointmentSaveOptions](../../appointmentsaveoptions/)
* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## Save(string) {#save_3}

Saves appointment to the file with iCalendar format using te default save options

```csharp
public void Save(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A file path |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *filePath* is `null` or `empty` |

### See Also

* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## Save(string, AppointmentSaveFormat) {#save_4}

Saves appointment to the file with specified format using te default save options

```csharp
public void Save(string filePath, AppointmentSaveFormat saveFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A file path |
| saveFormat | AppointmentSaveFormat | A save format |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *filePath* is `null` or `empty` |
| NotSupportedException | The specified save options are not supported |

### See Also

* enum [AppointmentSaveFormat](../../appointmentsaveformat/)
* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## Save(string, AppointmentSaveOptions) {#save_5}

Saves appointment to the file with specified save options

```csharp
public void Save(string filePath, AppointmentSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A file path |
| saveOptions | AppointmentSaveOptions | A save options |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *filePath* is `null` or `empty` |
| ArgumentNullException | *saveOptions* is `null` |
| NotSupportedException | The specified save options are not supported |

### See Also

* class [AppointmentSaveOptions](../../appointmentsaveoptions/)
* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## Save(Stream) {#save}

Saves appointment to the file with iCalendar format using te default save options

```csharp
public void Save(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to save to |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null` |
| NotSupportedException | stream does not support writing |

### See Also

* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## Save(Stream, AppointmentSaveFormat) {#save_1}

Saves appointment to the stream with specified format using te default save options

```csharp
public void Save(Stream stream, AppointmentSaveFormat saveFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to save to |
| saveFormat | AppointmentSaveFormat | A save format |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null` |
| NotSupportedException | The specified save options are not supported |
| NotSupportedException | stream does not support writing |

### See Also

* enum [AppointmentSaveFormat](../../appointmentsaveformat/)
* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)


