---
title: InlineAttachmentExtractor.EnumerateMsoPackage
second_title: Aspose.Email for .NET API Reference
description: InlineAttachmentExtractor method. Reads an MSO package and returns the files it contains
type: docs
weight: 10
url: /net/aspose.email.mapi/inlineattachmentextractor/enumeratemsopackage/
---
## InlineAttachmentExtractor.EnumerateMsoPackage method

Reads an MSO package and returns the files it contains.

```csharp
public static IDictionary<string, byte[]> EnumerateMsoPackage(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The content of the package, for example the `oledata.mso` attachment. |

### Return Value

The files of the package: the key is the identifier of the file, which the message body uses to refer to it, and the value is its content.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| InvalidDataException | *stream* does not contain a valid MSO package. |

## Remarks

In evaluation mode only the first file of the package is extracted.

### See Also

* class [InlineAttachmentExtractor](../)
* namespace [Aspose.Email.Mapi](../../inlineattachmentextractor/)
* assembly [Aspose.Email](../../../)


