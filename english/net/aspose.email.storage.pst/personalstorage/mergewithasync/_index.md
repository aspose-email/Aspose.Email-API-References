---
title: PersonalStorage.MergeWithAsync
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Merges the pst storage with one or more other pst files. Thus the combined files are sources
type: docs
weight: 330
url: /net/aspose.email.storage.pst/personalstorage/mergewithasync/
---
## MergeWithAsync(string[], CancellationToken) {#mergewithasync_1}

Merges the pst storage with one or more other pst files. Thus, the combined files are sources.

```csharp
public Task MergeWithAsync(string[] sourceFileNames, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceFileNames | String[] | The source file names. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | "Throws when the filename collection is null." |
| ArgumentException | "Throws when the filename in collection is null or empty." |

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## MergeWithAsync(Stream[], CancellationToken) {#mergewithasync}

Merges the pst storage with one or more other pst streams. Thus, the combined stream are sources.

```csharp
public Task MergeWithAsync(Stream[] sourceStreams, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceStreams | Stream[] | The source streams. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | "Throws when the stream collection is null." |
| ArgumentException | "Throws when the stream in collection is null." |

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


