---
title: MboxStorageReader.SplitIntoAsync
second_title: Aspose.Email for .NET API Reference
description: MboxStorageReader method. Splits the mbox storage into less sized parts
type: docs
weight: 160
url: /net/aspose.email.storage.mbox/mboxstoragereader/splitintoasync/
---
## SplitIntoAsync(long, string, string, CancellationToken) {#splitintoasync}

Splits the mbox storage into less sized parts.

```csharp
public Task SplitIntoAsync(long chunkSize, string outputPath, string partFileNamePrefix, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| chunkSize | Int64 | The approximate size of a chunk in bytes. |
| outputPath | String | The folder path where chunks will be created. |
| partFileNamePrefix | String |  |
| token | CancellationToken | A CancellationToken that enables the possible cancellation of the operation. |

### Return Value

The Task object

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Throws when the path parameter is null or empty. |

### See Also

* class [MboxStorageReader](../)
* namespace [Aspose.Email.Storage.Mbox](../../mboxstoragereader/)
* assembly [Aspose.Email](../../../)

---

## SplitIntoAsync(long, string, CancellationToken) {#splitintoasync_1}

Splits the mbox storage into less sized parts.

```csharp
public Task SplitIntoAsync(long chunkSize, string outputPath, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| chunkSize | Int64 | The approximate size of a chunk in bytes. |
| outputPath | String | The folder path where chunks will be created. |
| token | CancellationToken | A CancellationToken that enables the possible cancellation of the operation. |

### Return Value

The Task object

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Throws when the path parameter is null or empty. |

### See Also

* class [MboxStorageReader](../)
* namespace [Aspose.Email.Storage.Mbox](../../mboxstoragereader/)
* assembly [Aspose.Email](../../../)


