---
title: MapiTask.LoadAsync
second_title: Aspose.Email for .NET API Reference
description: MapiTask method. Loads a MapiTask from the specified file asynchronously
type: docs
weight: 280
url: /net/aspose.email.mapi/mapitask/loadasync/
---
## LoadAsync(string, CancellationToken) {#loadasync_1}

Loads a [`MapiTask`](../) from the specified file asynchronously.

```csharp
public static Task<MapiTask> LoadAsync(string filePath, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path to the file to be loaded. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Returns a [`MapiTask`](../) instance loaded from the specified file.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty`. |
| FileNotFoundException | The specified file does not exist. |

### See Also

* class [MapiTask](../)
* namespace [Aspose.Email.Mapi](../../mapitask/)
* assembly [Aspose.Email](../../../)

---

## LoadAsync(Stream, CancellationToken) {#loadasync}

Loads a [`MapiTask`](../) from the specified stream asynchronously.

```csharp
public static Task<MapiTask> LoadAsync(Stream stream, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to be loaded. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Returns a [`MapiTask`](../) instance loaded from the specified stream.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support reading. |
| InvalidOperationException | The stream does not contain a task item. |

### See Also

* class [MapiTask](../)
* namespace [Aspose.Email.Mapi](../../mapitask/)
* assembly [Aspose.Email](../../../)


