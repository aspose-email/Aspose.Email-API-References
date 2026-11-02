---
title: Class PersonalStorageLoadOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Storage.Pst.PersonalStorageLoadOptions class. Options for opening a PST or OST file or stream
type: docs
weight: 19270
url: /net/aspose.email.storage.pst/personalstorageloadoptions/
---
## PersonalStorageLoadOptions class

Options for opening a PST or OST file or stream.

```csharp
public class PersonalStorageLoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PersonalStorageLoadOptions](personalstorageloadoptions/)() | Initializes a new instance of the `PersonalStorageLoadOptions` class with the default settings: read-only access, and the stream is closed when the storage is disposed. |

## Properties

| Name | Description |
| --- | --- |
| [LeaveStreamOpen](../../aspose.email.storage.pst/personalstorageloadoptions/leavestreamopen/) { get; set; } | Gets or sets whether to leave the stream open when the [`PersonalStorage`](../personalstorage/) is disposed. It must be `false` when opening a file with [`FromFile`](../personalstorage/fromfile/). The default is `false`. |
| [Writable](../../aspose.email.storage.pst/personalstorageloadoptions/writable/) { get; set; } | Gets or sets whether the PST is opened for writing. The default is `false`. |

### See Also

* namespace [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst/)
* assembly [Aspose.Email](../../)


