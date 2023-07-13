---
title: MapiNote.Save
second_title: Aspose.Email for .NET API Reference
description: MapiNote method. Saves this MapiNote to the given stream using specified format
type: docs
weight: 90
url: /net/aspose.email.mapi/mapinote/save/
---
## Save(Stream, NoteSaveFormat) {#save}

Saves this [`MapiNote`](../) to the given stream using specified format.

```csharp
public void Save(Stream stream, NoteSaveFormat saveFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to save to. |
| saveFormat | NoteSaveFormat | A save format. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support writing. |
| NotSupportedException | The specified format is not supported. |

### See Also

* enum [NoteSaveFormat](../../notesaveformat/)
* class [MapiNote](../)
* namespace [Aspose.Email.Mapi](../../mapinote/)
* assembly [Aspose.Email](../../../)

---

## Save(string, NoteSaveFormat) {#save_1}

Saves this [`MapiNote`](../) into file using specified format.

```csharp
public void Save(string filePath, NoteSaveFormat saveFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A file name. |
| saveFormat | NoteSaveFormat | A save format. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty`. |
| NotSupportedException | some save option is not supported |

### See Also

* enum [NoteSaveFormat](../../notesaveformat/)
* class [MapiNote](../)
* namespace [Aspose.Email.Mapi](../../mapinote/)
* assembly [Aspose.Email](../../../)


