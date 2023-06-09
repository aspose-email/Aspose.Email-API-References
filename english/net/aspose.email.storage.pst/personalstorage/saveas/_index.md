---
title: PersonalStorage.SaveAs
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Saves the current object to a specified file format in a different file
type: docs
weight: 280
url: /net/aspose.email.storage.pst/personalstorage/saveas/
---
## SaveAs(string, FileFormat) {#saveas_1}

Saves the current object to a specified file format in a different file.

```csharp
public void SaveAs(string fileName, FileFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The name of the file to be saved. |
| format | FileFormat | The [`FileFormat`](../../fileformat/) is to be used when saving a file. |

## Remarks

It is used for the fast OST to PST conversion. The method doesn't support conversion of OST created by MS Office 2013 and later versions. To convert an OST of later version, create a new PST and use the [`MergeWith`](../mergewith/) method.

### See Also

* enum [FileFormat](../../fileformat/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## SaveAs(Stream, FileFormat) {#saveas}

Saves the current object to a specified file format in a stream.

```csharp
public void SaveAs(Stream stream, FileFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to be saved. |
| format | FileFormat | The [`FileFormat`](../../fileformat/) is to be used. |

## Remarks

It is used for the fast OST to PST conversion. The method doesn't support conversion of OST created by MS Office 2013 and later versions. To convert an OST of later version, create a new PST and use the [`MergeWith`](../mergewith/) method.

### See Also

* enum [FileFormat](../../fileformat/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


