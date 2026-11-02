---
title: MapiNote.SaveAsync
second_title: Aspose.Email for .NET API Reference
description: MapiNote method. Saves this MapiNote to the given stream using specified format asynchronously. The supported save format is MSG
type: docs
weight: 110
url: /net/aspose.email.mapi/mapinote/saveasync/
---
## SaveAsync(Stream, NoteSaveFormat, CancellationToken) {#saveasync}

Saves this [`MapiNote`](../) to the given stream using specified format asynchronously. The supported save format is MSG.

```csharp
public Task SaveAsync(Stream stream, NoteSaveFormat saveFormat, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to save to. |
| saveFormat | NoteSaveFormat | A save format. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

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

## SaveAsync(string, NoteSaveFormat, CancellationToken) {#saveasync_1}

Saves this [`MapiNote`](../) into file using specified format asynchronously. The supported save format is MSG.

```csharp
public Task SaveAsync(string filePath, NoteSaveFormat saveFormat, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A file name. |
| saveFormat | NoteSaveFormat | A save format. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

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


