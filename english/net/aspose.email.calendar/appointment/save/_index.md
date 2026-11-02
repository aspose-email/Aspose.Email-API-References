---
title: Appointment.Save
second_title: Aspose.Email for .NET API Reference
description: Appointment method. Saves the appointment to an iCalendar ICS file
type: docs
weight: 380
url: /net/aspose.email.calendar/appointment/save/
---
## Save(string) {#save_3}

Saves the appointment to an iCalendar (ICS) file.

```csharp
public void Save(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path of the file to create. An existing file is overwritten. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or empty. |

### See Also

* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## Save(string, AppointmentSaveFormat) {#save_4}

Saves the appointment to a file in the specified format, with default options.

```csharp
public void Save(string filePath, AppointmentSaveFormat saveFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path of the file to create. An existing file is overwritten. |
| saveFormat | AppointmentSaveFormat | The format to save in. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or empty. |
| NotSupportedException | *saveFormat* is not a supported format. |

### See Also

* enum [AppointmentSaveFormat](../../appointmentsaveformat/)
* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## Save(string, AppointmentSaveOptions) {#save_5}

Saves the appointment to a file with the specified options.

```csharp
public void Save(string filePath, AppointmentSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path of the file to create. An existing file is overwritten. |
| saveOptions | AppointmentSaveOptions | The save options. Their type, [`AppointmentIcsSaveOptions`](../../appointmenticssaveoptions/) or [`AppointmentMsgSaveOptions`](../../appointmentmsgsaveoptions/), selects the format. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or empty. |
| ArgumentNullException | *saveOptions* is `null`. |
| NotSupportedException | The type of *saveOptions* is not supported. |

### See Also

* class [AppointmentSaveOptions](../../appointmentsaveoptions/)
* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## Save(Stream) {#save}

Saves the appointment to a stream in iCalendar (ICS) format.

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

* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## Save(Stream, AppointmentSaveFormat) {#save_1}

Saves the appointment to a stream in the specified format, with default options.

```csharp
public void Save(Stream stream, AppointmentSaveFormat saveFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to write to. |
| saveFormat | AppointmentSaveFormat | The format to save in. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *saveFormat* is not a supported format. |
| NotSupportedException | *stream* does not support writing. |

### See Also

* enum [AppointmentSaveFormat](../../appointmentsaveformat/)
* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## Save(Stream, AppointmentSaveOptions) {#save_2}

Saves the appointment to a stream with the specified options.

```csharp
public void Save(Stream stream, AppointmentSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to write to. |
| saveOptions | AppointmentSaveOptions | The save options. Their type, [`AppointmentIcsSaveOptions`](../../appointmenticssaveoptions/) or [`AppointmentMsgSaveOptions`](../../appointmentmsgsaveoptions/), selects the format. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* or *saveOptions* is `null`. |
| NotSupportedException | The type of *saveOptions* is not supported. |
| NotSupportedException | *stream* does not support writing. |

### See Also

* class [AppointmentSaveOptions](../../appointmentsaveoptions/)
* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)


