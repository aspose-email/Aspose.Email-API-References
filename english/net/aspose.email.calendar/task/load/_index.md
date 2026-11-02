---
title: Task.Load
second_title: Aspose.Email for .NET API Reference
description: Task method. Loads a task from an iCalendar ICS file
type: docs
weight: 20
url: /net/aspose.email.calendar/task/load/
---
## Load(string) {#load_1}

Loads a task from an iCalendar (ICS) file.

```csharp
public static Task Load(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path of the ICS file. |

### Return Value

The task read from the file.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or empty. |
| FileNotFoundException | The file specified by *filePath* does not exist. |

### See Also

* class [Task](../)
* namespace [Aspose.Email.Calendar](../../task/)
* assembly [Aspose.Email](../../../)

---

## Load(Stream) {#load}

Loads a task from a stream of iCalendar (ICS) data.

```csharp
public static Task Load(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to read from. |

### Return Value

The task read from the stream.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null` |
| NotSupportedException | *stream* does not support reading |

### See Also

* class [Task](../)
* namespace [Aspose.Email.Calendar](../../task/)
* assembly [Aspose.Email](../../../)


