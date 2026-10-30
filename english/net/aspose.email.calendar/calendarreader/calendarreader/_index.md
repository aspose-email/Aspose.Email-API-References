---
title: CalendarReader.CalendarReader
second_title: Aspose.Email for .NET API Reference
description: CalendarReader constructor. Initializes a new instance of the CalendarReader class that reads the specified file with the default options
type: docs
weight: 10
url: /net/aspose.email.calendar/calendarreader/calendarreader/
---
## CalendarReader(string) {#constructor_2}

Initializes a new instance of the [`CalendarReader`](../) class that reads the specified file with the default options.

```csharp
public CalendarReader(string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The path of the ICS file. |

### Exceptions

| exception | condition |
| --- | --- |
| FileNotFoundException | The file specified by *path* does not exist. |
| InvalidOperationException | `AppointmentLoadOptions.EventIndex` is beyond the last event. |

### See Also

* class [CalendarReader](../)
* namespace [Aspose.Email.Calendar](../../calendarreader/)
* assembly [Aspose.Email](../../../)

---

## CalendarReader(string, AppointmentLoadOptions) {#constructor_3}

Initializes a new instance of the [`CalendarReader`](../) class that reads the specified file with the specified options.

```csharp
public CalendarReader(string path, AppointmentLoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The path of the ICS file. |
| options | AppointmentLoadOptions | Options that control loading, or `null` to use the defaults. |

### Exceptions

| exception | condition |
| --- | --- |
| FileNotFoundException | The file specified by *path* does not exist. |
| InvalidOperationException | `AppointmentLoadOptions.EventIndex` is beyond the last event. |

### See Also

* class [AppointmentLoadOptions](../../appointmentloadoptions/)
* class [CalendarReader](../)
* namespace [Aspose.Email.Calendar](../../calendarreader/)
* assembly [Aspose.Email](../../../)

---

## CalendarReader(Stream) {#constructor}

Initializes a new instance of the [`CalendarReader`](../) class that reads the specified stream with the default options.

```csharp
public CalendarReader(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream of iCalendar data. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support reading. |
| InvalidOperationException | `AppointmentLoadOptions.EventIndex` is beyond the last event. |

### See Also

* class [CalendarReader](../)
* namespace [Aspose.Email.Calendar](../../calendarreader/)
* assembly [Aspose.Email](../../../)

---

## CalendarReader(Stream, AppointmentLoadOptions) {#constructor_1}

Initializes a new instance of the [`CalendarReader`](../) class that reads the specified stream with the specified options.

```csharp
public CalendarReader(Stream stream, AppointmentLoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream of iCalendar data. |
| options | AppointmentLoadOptions | Options that control loading, or `null` to use the defaults. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support reading. |
| InvalidOperationException | `AppointmentLoadOptions.EventIndex` is beyond the last event. |

### See Also

* class [AppointmentLoadOptions](../../appointmentloadoptions/)
* class [CalendarReader](../)
* namespace [Aspose.Email.Calendar](../../calendarreader/)
* assembly [Aspose.Email](../../../)


