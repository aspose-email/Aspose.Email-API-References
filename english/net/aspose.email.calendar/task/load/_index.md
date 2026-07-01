---
title: Task.Load
second_title: Aspose.Email for .NET API Reference
description: Task method. Loads Task from the file. Supported file formats iCalendar A file path.A read Appointment
type: docs
weight: 20
url: /net/aspose.email.calendar/task/load/
---
## Load(string) {#load_1}

Loads [`Task`](../) from the file. Supported file formats: iCalendar A file path.A read [`Appointment`](../../appointment/).

```csharp
public static Task Load(string filePath)
```

### See Also

* class [Task](../)
* namespace [Aspose.Email.Calendar](../../task/)
* assembly [Aspose.Email](../../../)

---

## Load(Stream) {#load}

Loads [`Task`](../) from the stream

```csharp
public static Task Load(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to load from |

### Return Value

A read [`Task`](../)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null` |
| NotSupportedException | *stream* does not support reading |

### See Also

* class [Task](../)
* namespace [Aspose.Email.Calendar](../../task/)
* assembly [Aspose.Email](../../../)


