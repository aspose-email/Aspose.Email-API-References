---
title: PersonalStorage.SaveAs
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Saves the storage to another file in the specified format
type: docs
weight: 360
url: /net/aspose.email.storage.pst/personalstorage/saveas/
---
## SaveAs(string, FileFormat) {#saveas_1}

Saves the storage to another file in the specified format.

```csharp
public void SaveAs(string fileName, FileFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The path of the file to create. |
| format | FileFormat | The format to save in. |

## Remarks

Use it for a fast OST to PST conversion. It does not support OST files of Outlook 2013 and later; to convert such a file, create a new PST and call its [`MergeWith`](../mergewith/) method.

## Examples

This example converts an OST file to PST.

[C#]

```csharp
using (var ost = PersonalStorage.FromFile("mailbox.ost"))
{
    ost.SaveAs("mailbox.pst", FileFormat.Pst);
}
```

[Visual Basic]

```csharp
Using ost As PersonalStorage = PersonalStorage.FromFile("mailbox.ost")
    ost.SaveAs("mailbox.pst", FileFormat.Pst)
End Using
```

### See Also

* enum [FileFormat](../../fileformat/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## SaveAs(Stream, FileFormat) {#saveas}

Saves the storage to a stream in the specified format.

```csharp
public void SaveAs(Stream stream, FileFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to write to. |
| format | FileFormat | The format to save in. |

## Remarks

Use it for a fast OST to PST conversion. It does not support OST files of Outlook 2013 and later; to convert such a file, create a new PST and call its [`MergeWith`](../mergewith/) method.

### See Also

* enum [FileFormat](../../fileformat/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


