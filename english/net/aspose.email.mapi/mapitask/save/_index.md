---
title: MapiTask.Save
second_title: Aspose.Email for .NET API Reference
description: MapiTask method. Saves the task to a stream in the specified format. Only MSG is supported
type: docs
weight: 250
url: /net/aspose.email.mapi/mapitask/save/
---
## Save(Stream, TaskSaveFormat) {#save_1}

Saves the task to a stream in the specified format. Only MSG is supported.

```csharp
public void Save(Stream stream, TaskSaveFormat saveFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to write to. |
| saveFormat | TaskSaveFormat | The format. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support writing. |
| NotSupportedException | *saveFormat* is not `Msg`. |

### See Also

* enum [TaskSaveFormat](../../tasksaveformat/)
* class [MapiTask](../)
* namespace [Aspose.Email.Mapi](../../mapitask/)
* assembly [Aspose.Email](../../../)

---

## Save(string, TaskSaveFormat) {#save_3}

Saves the task to a file in the specified format. Only MSG is supported.

```csharp
public void Save(string filePath, TaskSaveFormat saveFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path of the file to write. |
| saveFormat | TaskSaveFormat | The format. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty`. |
| NotSupportedException | *saveFormat* is not `Msg`. |

### See Also

* enum [TaskSaveFormat](../../tasksaveformat/)
* class [MapiTask](../)
* namespace [Aspose.Email.Mapi](../../mapitask/)
* assembly [Aspose.Email](../../../)

---

## Save(string) {#save_2}

Saves this [`MapiTask`](../) to the given file.

```csharp
public void Save(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A file name. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty`. |

### See Also

* class [MapiTask](../)
* namespace [Aspose.Email.Mapi](../../mapitask/)
* assembly [Aspose.Email](../../../)

---

## Save(Stream) {#save}

Saves this [`MapiTask`](../) to the given stream.

```csharp
public void Save(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to save to. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support writing. |

### See Also

* class [MapiTask](../)
* namespace [Aspose.Email.Mapi](../../mapitask/)
* assembly [Aspose.Email](../../../)


