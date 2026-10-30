---
title: CalendarWriter.CalendarWriter
second_title: Aspose.Email for .NET API Reference
description: CalendarWriter constructor. Initializes a new instance of the CalendarWriter class that creates the specified file with the default options
type: docs
weight: 10
url: /net/aspose.email.calendar/calendarwriter/calendarwriter/
---
## CalendarWriter(string) {#constructor_2}

Initializes a new instance of the [`CalendarWriter`](../) class that creates the specified file with the default options.

```csharp
public CalendarWriter(string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The path of the ICS file to create. An existing file is overwritten. |

### See Also

* class [CalendarWriter](../)
* namespace [Aspose.Email.Calendar](../../calendarwriter/)
* assembly [Aspose.Email](../../../)

---

## CalendarWriter(Stream) {#constructor}

Initializes a new instance of the [`CalendarWriter`](../) class that writes to the specified stream with the default options.

```csharp
public CalendarWriter(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to write to. It must be empty. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| InvalidOperationException | `CreateNew` is `true` and *stream* is not empty. |

### See Also

* class [CalendarWriter](../)
* namespace [Aspose.Email.Calendar](../../calendarwriter/)
* assembly [Aspose.Email](../../../)

---

## CalendarWriter(string, AppointmentIcsSaveOptions) {#constructor_3}

Initializes a new instance of the [`CalendarWriter`](../) class that writes to the specified file with the specified options.

```csharp
public CalendarWriter(string path, AppointmentIcsSaveOptions icsSaveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The path of the ICS file. When `CreateNew` is `false`, the file must exist and the events are added to it. |
| icsSaveOptions | AppointmentIcsSaveOptions | The save options, or `null` to use the defaults. |

### See Also

* class [AppointmentIcsSaveOptions](../../appointmenticssaveoptions/)
* class [CalendarWriter](../)
* namespace [Aspose.Email.Calendar](../../calendarwriter/)
* assembly [Aspose.Email](../../../)

---

## CalendarWriter(Stream, AppointmentIcsSaveOptions) {#constructor_1}

Initializes a new instance of the [`CalendarWriter`](../) class that writes to the specified stream with the specified options.

```csharp
public CalendarWriter(Stream stream, AppointmentIcsSaveOptions icsSaveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to write to. When `CreateNew` is `true`, the default, it must be empty. |
| icsSaveOptions | AppointmentIcsSaveOptions | The save options, or `null` to use the defaults. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| InvalidOperationException | `CreateNew` is `true` and *stream* is not empty. |

### See Also

* class [AppointmentIcsSaveOptions](../../appointmenticssaveoptions/)
* class [CalendarWriter](../)
* namespace [Aspose.Email.Calendar](../../calendarwriter/)
* assembly [Aspose.Email](../../../)


