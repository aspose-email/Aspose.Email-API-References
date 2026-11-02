---
title: PersonalStorage.SplitIntoAsync
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Asynchronously splits the PST into files of about the specified size
type: docs
weight: 390
url: /net/aspose.email.storage.pst/personalstorage/splitintoasync/
---
## SplitIntoAsync(long, string, CancellationToken) {#splitintoasync_1}

Asynchronously splits the PST into files of about the specified size.

```csharp
public Task SplitIntoAsync(long chunkSize, string path, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| chunkSize | Int64 | The approximate size of each PST file, in bytes. It must be greater than 271,360 bytes. |
| path | String | The folder to create the PST files in. |
| token | CancellationToken | A token to cancel the operation. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *path* is `null` or empty. |
| ArgumentException | *chunkSize* is not greater than 271,360 bytes, the minimum size of a PST file. |
| InvalidOperationException | The library runs in evaluation mode and *chunkSize* is greater than 100,000,000 bytes. |

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## SplitIntoAsync(long, string, string, CancellationToken) {#splitintoasync}

Asynchronously splits the PST into files of about the specified size, named with a prefix.

```csharp
public Task SplitIntoAsync(long chunkSize, string partFileNamePrefix, string path, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| chunkSize | Int64 | The approximate size of each PST file, in bytes. It must be greater than 271,360 bytes. |
| partFileNamePrefix | String | The prefix of the file names. If it is `null` or empty, the files are named without a prefix. |
| path | String | The folder to create the PST files in. |
| token | CancellationToken | A token to cancel the operation. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *path* is `null` or empty. |
| ArgumentException | *chunkSize* is not greater than 271,360 bytes, the minimum size of a PST file. |
| InvalidOperationException | The library runs in evaluation mode and *chunkSize* is greater than 100,000,000 bytes. |

## Remarks

The files are named after the template `{prefix}_part{number}.pst`; without a prefix, the `{prefix}` part is left out. `StorageProcessed` is raised after each file is created.

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## SplitIntoAsync(IList&lt;MailQuery&gt;, string, CancellationToken) {#splitintoasync_3}

Asynchronously splits the PST into several files by search criteria.

```csharp
public Task SplitIntoAsync(IList<MailQuery> criteria, string path, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| criteria | IList`1 | The search criteria. A separate PST is created for the messages that match each [`MailQuery`](../../../aspose.email.tools.search/mailquery/). |
| path | String | The folder to create the PST files in. |
| token | CancellationToken | A token to cancel the operation. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *path* is `null` or empty. |

### See Also

* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## SplitIntoAsync(IList&lt;MailQuery&gt;, string, string, CancellationToken) {#splitintoasync_2}

Asynchronously splits the PST into several files by search criteria, named with a prefix.

```csharp
public Task SplitIntoAsync(IList<MailQuery> criteria, string partFileNamePrefix, string path, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| criteria | IList`1 | The search criteria. A separate PST is created for the messages that match each [`MailQuery`](../../../aspose.email.tools.search/mailquery/). |
| partFileNamePrefix | String | The prefix of the file names. If it is `null` or empty, the files are named without a prefix. |
| path | String | The folder to create the PST files in. |
| token | CancellationToken | A token to cancel the operation. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *path* is `null` or empty. |

## Remarks

The files are named after the template `{prefix}_part{number}.pst`; without a prefix, the `{prefix}` part is left out. `StorageProcessed` is raised after each file is created.

### See Also

* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


