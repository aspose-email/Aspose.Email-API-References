---
title: MapiTask.Save
second_title: Aspose.Email for .NET API Reference
description: MapiTask method. Saves this MapiTask to the given stream using specified format
type: docs
weight: 230
url: /net/aspose.email.mapi/mapitask/save/
---
## Save(Stream, TaskSaveFormat) {#save}

Saves this [`MapiTask`](../) to the given stream using specified format.

```csharp
public void Save(Stream stream, TaskSaveFormat saveFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to save to. |
| saveFormat | TaskSaveFormat | A save format. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support writing. |
| NotSupportedException | The specified format is not supported. |

### See Also

* enum [TaskSaveFormat](../../tasksaveformat/)
* class [MapiTask](../)
* namespace [Aspose.Email.Mapi](../../mapitask/)
* assembly [Aspose.Email](../../../)

---

## Save(string, TaskSaveFormat) {#save_1}

Saves this [`MapiTask`](../) into file using specified format.

```csharp
public void Save(string filePath, TaskSaveFormat saveFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A file name. |
| saveFormat | TaskSaveFormat | A save format. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty`. |
| NotSupportedException | some save option is not supported |

### See Also

* enum [TaskSaveFormat](../../tasksaveformat/)
* class [MapiTask](../)
* namespace [Aspose.Email.Mapi](../../mapitask/)
* assembly [Aspose.Email](../../../)


