---
title: PersonalStorage.MergeWithAsync
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Asynchronously merges one or more other PST files into this PST
type: docs
weight: 340
url: /net/aspose.email.storage.pst/personalstorage/mergewithasync/
---
## MergeWithAsync(string[], CancellationToken) {#mergewithasync_1}

Asynchronously merges one or more other PST files into this PST.

```csharp
public Task MergeWithAsync(string[] sourceFileNames, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceFileNames | String[] | The paths of the PST files to merge. |
| token | CancellationToken | A token to cancel the operation. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *sourceFileNames* is `null`. |
| ArgumentException | An element of *sourceFileNames* is `null` or empty. |

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## MergeWithAsync(Stream[], CancellationToken) {#mergewithasync}

Asynchronously merges one or more other PST streams into this PST.

```csharp
public Task MergeWithAsync(Stream[] sourceStreams, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceStreams | Stream[] | The streams with the PST data to merge. |
| token | CancellationToken | A token to cancel the operation. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *sourceStreams* is `null`. |
| ArgumentException | An element of *sourceStreams* is `null`. |

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


