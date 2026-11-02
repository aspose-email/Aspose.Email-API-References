---
title: PersonalStorage.MergeWith
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Merges one or more other PST files into this PST
type: docs
weight: 330
url: /net/aspose.email.storage.pst/personalstorage/mergewith/
---
## MergeWith(string[]) {#mergewith_1}

Merges one or more other PST files into this PST.

```csharp
public void MergeWith(string[] sourceFileNames)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceFileNames | String[] | The paths of the PST files to merge. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *sourceFileNames* is `null`. |
| ArgumentException | An element of *sourceFileNames* is `null` or empty. |

## Remarks

`StorageProcessing` is raised before each source is merged, and `StorageProcessed` after it.

## Examples

This example merges two PST files into a third one and reports each file as it is merged.

[C#]

```csharp
using (var pst = PersonalStorage.FromFile("merged.pst"))
{
    pst.StorageProcessing += (sender, e) => Console.WriteLine($"Merging {e.FileName}");

    // Add the contents of the other files to merged.pst
    pst.MergeWith(new[] { "2024.pst", "2025.pst" });
}
```

[Visual Basic]

```csharp
Using pst As PersonalStorage = PersonalStorage.FromFile("merged.pst")
    AddHandler pst.StorageProcessing, Sub(sender, e) Console.WriteLine($"Merging {e.FileName}")

    ' Add the contents of the other files to merged.pst
    pst.MergeWith(New String() {"2024.pst", "2025.pst"})
End Using
```

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## MergeWith(Stream[]) {#mergewith}

Merges one or more other PST streams into this PST.

```csharp
public void MergeWith(Stream[] sourceStreams)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourceStreams | Stream[] | The streams with the PST data to merge. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *sourceStreams* is `null`. |
| ArgumentException | An element of *sourceStreams* is `null`. |

## Remarks

`StorageProcessing` is raised before each source is merged, and `StorageProcessed` after it.

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


