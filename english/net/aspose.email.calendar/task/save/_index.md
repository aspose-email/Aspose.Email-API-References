---
title: Task.Save
second_title: Aspose.Email for .NET API Reference
description: Task method. Saves the task to a stream in iCalendar ICS format
type: docs
weight: 210
url: /net/aspose.email.calendar/task/save/
---
## Save(Stream) {#save}

Saves the task to a stream in iCalendar (ICS) format.

```csharp
public virtual void Save(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to write to. |

### See Also

* class [Task](../)
* namespace [Aspose.Email.Calendar](../../task/)
* assembly [Aspose.Email](../../../)

---

## Save(string) {#save_3}

Saves the task to an iCalendar (ICS) file.

```csharp
public virtual void Save(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path of the file to create. An existing file is overwritten. |

### See Also

* class [Task](../)
* namespace [Aspose.Email.Calendar](../../task/)
* assembly [Aspose.Email](../../../)

---

## Save(string, TaskSaveOptions) {#save_4}

Saves the task to a file with the specified options.

```csharp
public virtual void Save(string filePath, TaskSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path of the file to create. An existing file is overwritten. |
| saveOptions | TaskSaveOptions | The save options. Their type, [`TaskIcsSaveOptions`](../../taskicssaveoptions/) or [`TaskMsgSaveOptions`](../../taskmsgsaveoptions/), selects the format; `null` saves in iCalendar format. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or empty. |

### See Also

* class [TaskSaveOptions](../../tasksaveoptions/)
* class [Task](../)
* namespace [Aspose.Email.Calendar](../../task/)
* assembly [Aspose.Email](../../../)

---

## Save(Stream, TaskSaveOptions) {#save_1}

Saves the task to a stream with the specified options.

```csharp
public virtual void Save(Stream stream, TaskSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to write to. |
| saveOptions | TaskSaveOptions | The save options. Their type, [`TaskIcsSaveOptions`](../../taskicssaveoptions/) or [`TaskMsgSaveOptions`](../../taskmsgsaveoptions/), selects the format; `null` saves in iCalendar format. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |

### See Also

* class [TaskSaveOptions](../../tasksaveoptions/)
* class [Task](../)
* namespace [Aspose.Email.Calendar](../../task/)
* assembly [Aspose.Email](../../../)


