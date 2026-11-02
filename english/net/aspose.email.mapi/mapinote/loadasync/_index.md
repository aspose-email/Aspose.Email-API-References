---
title: MapiNote.LoadAsync
second_title: Aspose.Email for .NET API Reference
description: MapiNote method. Loads a MapiNote from the specified file asynchronously
type: docs
weight: 120
url: /net/aspose.email.mapi/mapinote/loadasync/
---
## LoadAsync(string, CancellationToken) {#loadasync_1}

Loads a [`MapiNote`](../) from the specified file asynchronously.

```csharp
public static Task<MapiNote> LoadAsync(string filePath, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path to the file to be loaded. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Returns a [`MapiNote`](../) instance loaded from the specified file.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty`. |
| FileNotFoundException | The specified file does not exist. |
| InvalidOperationException | The file does not contain a note item. |

### See Also

* class [MapiNote](../)
* namespace [Aspose.Email.Mapi](../../mapinote/)
* assembly [Aspose.Email](../../../)

---

## LoadAsync(Stream, CancellationToken) {#loadasync}

Loads a [`MapiNote`](../) from the specified stream asynchronously.

```csharp
public static Task<MapiNote> LoadAsync(Stream stream, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to be loaded. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Returns a [`MapiNote`](../) instance loaded from the specified stream.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support reading. |
| InvalidOperationException | The stream does not contain a note item. |

### See Also

* class [MapiNote](../)
* namespace [Aspose.Email.Mapi](../../mapinote/)
* assembly [Aspose.Email](../../../)


