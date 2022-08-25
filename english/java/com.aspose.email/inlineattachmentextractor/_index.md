---
title: InlineAttachmentExtractor
second_title: Aspose.Email for Java API Reference
description:  Provides ability to extract files from MSO packages.
type: docs
weight: 334
url: /java/com.aspose.email/inlineattachmentextractor/
---
**Inheritance:**
java.lang.Object
```
public class InlineAttachmentExtractor
```

Provides ability to extract files from MSO packages. Can be used to process "oledata.mso" and similar files typically attached to messages created using Outlook.
## Constructors

| Constructor | Description |
| --- | --- |
| [InlineAttachmentExtractor()](#InlineAttachmentExtractor--) |  |
## Methods

| Method | Description |
| --- | --- |
| [enumerateMsoPackage(InputStream stream)](#enumerateMsoPackage-java.io.InputStream-) | Enumerates the MSO package and returns a dictionary containing files data. |
### InlineAttachmentExtractor() {#InlineAttachmentExtractor--}
```
public InlineAttachmentExtractor()
```


### enumerateMsoPackage(InputStream stream) {#enumerateMsoPackage-java.io.InputStream-}
```
public static System.Collections.Generic.IGenericDictionary<String,byte[]> enumerateMsoPackage(InputStream stream)
```


Enumerates the MSO package and returns a dictionary containing files data. The key is file identifier and value contains actual data.Files are usually referenced in message body using the identifiers provided.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to parse.

--------------------

While in evaluation mode only one file is extracted from given MSO stream. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,byte[]> - Dictionary with files data.
