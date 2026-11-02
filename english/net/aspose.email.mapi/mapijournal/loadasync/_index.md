---
title: MapiJournal.LoadAsync
second_title: Aspose.Email for .NET API Reference
description: MapiJournal method. Loads a MapiJournal from the specified file asynchronously
type: docs
weight: 130
url: /net/aspose.email.mapi/mapijournal/loadasync/
---
## LoadAsync(string, CancellationToken) {#loadasync_1}

Loads a [`MapiJournal`](../) from the specified file asynchronously.

```csharp
public static Task<MapiJournal> LoadAsync(string filePath, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path to the file to be loaded. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Returns a [`MapiJournal`](../) instance loaded from the specified file.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty`. |
| FileNotFoundException | The specified file does not exist. |
| InvalidOperationException | The file does not contain a journal item. |

### See Also

* class [MapiJournal](../)
* namespace [Aspose.Email.Mapi](../../mapijournal/)
* assembly [Aspose.Email](../../../)

---

## LoadAsync(Stream, CancellationToken) {#loadasync}

Loads a [`MapiJournal`](../) from the specified stream asynchronously.

```csharp
public static Task<MapiJournal> LoadAsync(Stream stream, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to be loaded. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Returns a [`MapiJournal`](../) instance loaded from the specified stream.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support reading. |
| InvalidOperationException | The stream does not contain a journal item. |

### See Also

* class [MapiJournal](../)
* namespace [Aspose.Email.Mapi](../../mapijournal/)
* assembly [Aspose.Email](../../../)


