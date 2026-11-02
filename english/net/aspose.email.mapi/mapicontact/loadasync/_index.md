---
title: MapiContact.LoadAsync
second_title: Aspose.Email for .NET API Reference
description: MapiContact method. Loads a MapiContact from the specified file asynchronously
type: docs
weight: 200
url: /net/aspose.email.mapi/mapicontact/loadasync/
---
## LoadAsync(string, CancellationToken) {#loadasync_1}

Loads a [`MapiContact`](../) from the specified file asynchronously.

```csharp
public static Task<MapiContact> LoadAsync(string filePath, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path to the file to be loaded. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Returns a [`MapiContact`](../) instance loaded from the specified file.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty`. |
| FileNotFoundException | The specified file does not exist. |

### See Also

* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)

---

## LoadAsync(Stream, CancellationToken) {#loadasync}

Loads a [`MapiContact`](../) from the specified stream asynchronously.

```csharp
public static Task<MapiContact> LoadAsync(Stream stream, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to be loaded. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Returns a [`MapiContact`](../) instance loaded from the specified stream.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support reading. |
| InvalidOperationException | The stream does not contain a contact item. |

### See Also

* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)


