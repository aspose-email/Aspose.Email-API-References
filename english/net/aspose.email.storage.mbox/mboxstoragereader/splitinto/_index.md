---
title: MboxStorageReader.SplitInto
second_title: Aspose.Email for .NET API Reference
description: MboxStorageReader method. Splits the mbox storage into less sized parts
type: docs
weight: 150
url: /net/aspose.email.storage.mbox/mboxstoragereader/splitinto/
---
## SplitInto(long, string) {#splitinto_2}

Splits the mbox storage into less sized parts.

```csharp
public void SplitInto(long chunkSize, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| chunkSize | Int64 | The approximate size of a chunk in bytes. |
| outputPath | String | The folder path where chunks will be created. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Throws when the path parameter is null or empty. |

### See Also

* class [MboxStorageReader](../)
* namespace [Aspose.Email.Storage.Mbox](../../mboxstoragereader/)
* assembly [Aspose.Email](../../../)

---

## SplitInto(long, string, string) {#splitinto_3}

```csharp
public void SplitInto(long chunkSize, string outputPath, string partFileNamePrefix)
```

### See Also

* class [MboxStorageReader](../)
* namespace [Aspose.Email.Storage.Mbox](../../mboxstoragereader/)
* assembly [Aspose.Email](../../../)


