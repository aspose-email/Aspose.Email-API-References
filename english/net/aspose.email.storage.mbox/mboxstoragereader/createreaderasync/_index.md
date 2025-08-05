---
title: MboxStorageReader.CreateReaderAsync
second_title: Aspose.Email for .NET API Reference
description: MboxStorageReader method. Creates the instance of reader
type: docs
weight: 170
url: /net/aspose.email.storage.mbox/mboxstoragereader/createreaderasync/
---
## CreateReaderAsync(string, MboxLoadOptions, CancellationToken) {#createreaderasync_1}

Creates the instance of reader.

```csharp
public static Task<MboxStorageReader> CreateReaderAsync(string fileName, MboxLoadOptions options, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The full name of the file. |
| options | MboxLoadOptions | additional options when loading a Mbox storage[`MboxLoadOptions`](../../mboxloadoptions/). |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException |  |

### See Also

* class [MboxLoadOptions](../../mboxloadoptions/)
* class [MboxStorageReader](../)
* namespace [Aspose.Email.Storage.Mbox](../../mboxstoragereader/)
* assembly [Aspose.Email](../../../)

---

## CreateReaderAsync(Stream, MboxLoadOptions, CancellationToken) {#createreaderasync}

Creates the instance of reader.

```csharp
public static Task<MboxStorageReader> CreateReaderAsync(Stream stream, MboxLoadOptions options, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream. |
| options | MboxLoadOptions | additional options when loading a Mbox storage[`MboxLoadOptions`](../../mboxloadoptions/). |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

A read [`MboxStorageReader`](../)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException |  |

### See Also

* class [MboxLoadOptions](../../mboxloadoptions/)
* class [MboxStorageReader](../)
* namespace [Aspose.Email.Storage.Mbox](../../mboxstoragereader/)
* assembly [Aspose.Email](../../../)


