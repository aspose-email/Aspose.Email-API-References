---
title: Appointment.Load
second_title: Aspose.Email for .NET API Reference
description: Appointment method. Loads Appointment from the file. Supported file formats iCalendar
type: docs
weight: 20
url: /net/aspose.email.calendar/appointment/load/
---
## Load(string) {#load_3}

Loads [`Appointment`](../) from the file. Supported file formats: iCalendar

```csharp
public static Appointment Load(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A file path |

### Return Value

A read [`Appointment`](../)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty` |

### See Also

* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## Load(string, AppointmentLoadOptions) {#load_4}

Loads [`Appointment`](../) from the file. Supported file formats: iCalendar A file path.Represents appointment load options[`AppointmentLoadOptions`](../../appointmentloadoptions/).A read [`Appointment`](../).

```csharp
public static Appointment Load(string filePath, AppointmentLoadOptions options)
```

### See Also

* class [AppointmentLoadOptions](../../appointmentloadoptions/)
* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## Load(Stream) {#load}

Loads [`Appointment`](../) from the stream

```csharp
public static Appointment Load(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to load from |

### Return Value

A read [`Appointment`](../)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null` |
| NotSupportedException | *stream* does not support reading |

### See Also

* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## Load(Stream, bool) {#load_2}

Loads [`Appointment`](../) from the stream

```csharp
public static Appointment Load(Stream stream, bool applyLocalTimeZone)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to load from |
| applyLocalTimeZone | Boolean | Convert time to local timezone |

### Return Value

A read [`Appointment`](../)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null` |
| NotSupportedException | *stream* does not support reading |

### See Also

* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## Load(Stream, AppointmentLoadOptions) {#load_1}

Loads [`Appointment`](../) from the stream

```csharp
public static Appointment Load(Stream stream, AppointmentLoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to load from |
| options | AppointmentLoadOptions | Represents appointment load options |

### Return Value

A read [`Appointment`](../)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null` |
| NotSupportedException | *stream* does not support reading |

### See Also

* class [AppointmentLoadOptions](../../appointmentloadoptions/)
* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)


