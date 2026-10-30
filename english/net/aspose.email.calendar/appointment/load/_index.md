---
title: Appointment.Load
second_title: Aspose.Email for .NET API Reference
description: Appointment method. Loads an appointment from an iCalendar ICS file
type: docs
weight: 20
url: /net/aspose.email.calendar/appointment/load/
---
## Load(string) {#load_3}

Loads an appointment from an iCalendar (ICS) file.

```csharp
public static Appointment Load(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path of the ICS file. |

### Return Value

The appointment read from the file.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or empty. |
| FileNotFoundException | The file specified by *filePath* does not exist. |
| [AsposeInvalidOperationException](../../../aspose.email/asposeinvalidoperationexception/) | The file contains no events, or none at the index set in the options. |

## Remarks

If there are several events, the first one is loaded. Use [`CalendarReader`](../../calendarreader/) to read all of them, or set `AppointmentLoadOptions.EventIndex` to pick another one.

### See Also

* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## Load(string, AppointmentLoadOptions) {#load_4}

Loads an appointment from an iCalendar (ICS) file with the specified options.

```csharp
public static Appointment Load(string filePath, AppointmentLoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path of the ICS file. |
| options | AppointmentLoadOptions | Options that control loading, such as which event of the file to read. |

### Return Value

The appointment read from the file.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or empty. |
| FileNotFoundException | The file specified by *filePath* does not exist. |
| [AsposeInvalidOperationException](../../../aspose.email/asposeinvalidoperationexception/) | The file contains no events, or none at the index set in the options. |

### See Also

* class [AppointmentLoadOptions](../../appointmentloadoptions/)
* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## Load(Stream) {#load}

Loads an appointment from a stream of iCalendar (ICS) data.

```csharp
public static Appointment Load(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to read from. |

### Return Value

The appointment read from the stream.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support reading. |
| [AsposeInvalidOperationException](../../../aspose.email/asposeinvalidoperationexception/) | The data contains no events, or none at the index set in the options. |

## Remarks

If there are several events, the first one is loaded. Use [`CalendarReader`](../../calendarreader/) to read all of them, or set `AppointmentLoadOptions.EventIndex` to pick another one.

### See Also

* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## Load(Stream, bool) {#load_2}

Loads an appointment from a stream of iCalendar (ICS) data, optionally converting its times to the local time zone.

```csharp
public static Appointment Load(Stream stream, bool applyLocalTimeZone)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to read from. |
| applyLocalTimeZone | Boolean | `true` to convert the start and end times to the local time zone of the computer. |

### Return Value

The appointment read from the stream.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support reading. |
| [AsposeInvalidOperationException](../../../aspose.email/asposeinvalidoperationexception/) | The data contains no events, or none at the index set in the options. |

### See Also

* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)

---

## Load(Stream, AppointmentLoadOptions) {#load_1}

Loads an appointment from a stream of iCalendar (ICS) data with the specified options.

```csharp
public static Appointment Load(Stream stream, AppointmentLoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to read from. |
| options | AppointmentLoadOptions | Options that control loading, or `null` to use the defaults. |

### Return Value

The appointment read from the stream.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support reading. |
| [AsposeInvalidOperationException](../../../aspose.email/asposeinvalidoperationexception/) | The data contains no events, or none at the index set in the options. |

### See Also

* class [AppointmentLoadOptions](../../appointmentloadoptions/)
* class [Appointment](../)
* namespace [Aspose.Email.Calendar](../../appointment/)
* assembly [Aspose.Email](../../../)


