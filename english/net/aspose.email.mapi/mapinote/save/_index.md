---
title: MapiNote.Save
second_title: Aspose.Email for .NET API Reference
description: MapiNote method. Saves the note to a stream in the specified format. Only MSG is supported
type: docs
weight: 100
url: /net/aspose.email.mapi/mapinote/save/
---
## Save(Stream, NoteSaveFormat) {#save_1}

Saves the note to a stream in the specified format. Only MSG is supported.

```csharp
public void Save(Stream stream, NoteSaveFormat saveFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to write to. |
| saveFormat | NoteSaveFormat | The format. |

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

## Save(string, NoteSaveFormat) {#save_3}

Saves the note to a file in the specified format. Only MSG is supported.

```csharp
public void Save(string filePath, NoteSaveFormat saveFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path of the file to write. |
| saveFormat | NoteSaveFormat | The format. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty`. |
| NotSupportedException | *saveFormat* is not supported. |

### See Also

* enum [NoteSaveFormat](../../notesaveformat/)
* class [MapiNote](../)
* namespace [Aspose.Email.Mapi](../../mapinote/)
* assembly [Aspose.Email](../../../)

---

## Save(string) {#save_2}

Saves this [`MapiNote`](../) to the given file.

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

* class [MapiNote](../)
* namespace [Aspose.Email.Mapi](../../mapinote/)
* assembly [Aspose.Email](../../../)

---

## Save(Stream) {#save}

Saves this [`MapiNote`](../) to the given stream.

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

* class [MapiNote](../)
* namespace [Aspose.Email.Mapi](../../mapinote/)
* assembly [Aspose.Email](../../../)


