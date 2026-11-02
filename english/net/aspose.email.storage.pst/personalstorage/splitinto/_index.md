---
title: PersonalStorage.SplitInto
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Splits the PST into several files by search criteria
type: docs
weight: 380
url: /net/aspose.email.storage.pst/personalstorage/splitinto/
---
## SplitInto(IList&lt;MailQuery&gt;, string) {#splitinto_2}

Splits the PST into several files by search criteria.

```csharp
public void SplitInto(IList<MailQuery> criteria, string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| criteria | IList`1 | The search criteria. A separate PST is created for the messages that match each [`MailQuery`](../../../aspose.email.tools.search/mailquery/). |
| path | String | The folder to create the PST files in. |

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

## SplitInto(long, string, string) {#splitinto_1}

Splits the PST into files of about the specified size, named with a prefix.

```csharp
public void SplitInto(long chunkSize, string partFileNamePrefix, string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| chunkSize | Int64 | The approximate size of each PST file, in bytes. It must be greater than 271,360 bytes. |
| path | String | The folder to create the PST files in. |
| partFileNamePrefix | String | The prefix of the file names. If it is `null` or empty, the files are named without a prefix. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *path* is `null` or empty. |
| ArgumentException | *chunkSize* is not greater than 271,360 bytes, the minimum size of a PST file. |
| InvalidOperationException | The library runs in evaluation mode and *chunkSize* is greater than 100,000,000 bytes. |

## Remarks

The files are named after the template `{prefix}_part{number}.pst`; without a prefix, the `{prefix}` part is left out. `StorageProcessed` is raised after each file is created.

## Examples

This example splits a PST into files of about 50 MB and reports each new file.

[C#]

```csharp
using (var pst = PersonalStorage.FromFile("archive.pst"))
{
    pst.StorageProcessed += (sender, e) => Console.WriteLine($"Created {e.FileName}");

    // Files of about 50 MB, named archive_part{number}.pst
    pst.SplitInto(50 * 1024 * 1024, "archive", @"C:\Split");
}
```

[Visual Basic]

```csharp
Using pst As PersonalStorage = PersonalStorage.FromFile("archive.pst")
    AddHandler pst.StorageProcessed, Sub(sender, e) Console.WriteLine($"Created {e.FileName}")

    ' Files of about 50 MB, named archive_part{number}.pst
    pst.SplitInto(50 * 1024 * 1024, "archive", "C:\Split")
End Using
```

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## SplitInto(IList&lt;MailQuery&gt;, string, string) {#splitinto_3}

Splits the PST into several files by search criteria, named with a prefix.

```csharp
public void SplitInto(IList<MailQuery> criteria, string partFileNamePrefix, string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| criteria | IList`1 | The search criteria. A separate PST is created for the messages that match each [`MailQuery`](../../../aspose.email.tools.search/mailquery/). |
| path | String | The folder to create the PST files in. |
| partFileNamePrefix | String | The prefix of the file names. If it is `null` or empty, the files are named without a prefix. |

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

---

## SplitInto(long, string) {#splitinto}

Splits the PST into files of about the specified size.

```csharp
public void SplitInto(long chunkSize, string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| chunkSize | Int64 | The approximate size of each PST file, in bytes. It must be greater than 271,360 bytes. |
| path | String | The folder to create the PST files in. |

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


