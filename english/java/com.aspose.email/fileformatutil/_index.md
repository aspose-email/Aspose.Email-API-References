---
title: FileFormatUtil
second_title: Aspose.Email for Java API Reference
description:  Provides utility methods to detect file type.
type: docs
weight: 250
url: /java/com.aspose.email/fileformatutil/
---
**Inheritance:**
java.lang.Object
```
public class FileFormatUtil
```

Provides utility methods to detect file type.
## Constructors

| Constructor | Description |
| --- | --- |
| [FileFormatUtil()](#FileFormatUtil--) |  |
## Methods

| Method | Description |
| --- | --- |
| [detectFileFormat(InputStream stream)](#detectFileFormat-java.io.InputStream-) | Detects and returns the information about a format of a file stored in a stream. |
| [detectFileFormat(String filePath)](#detectFileFormat-java.lang.String-) | Detects and returns the information about a format of a file. |
### FileFormatUtil() {#FileFormatUtil--}
```
public FileFormatUtil()
```


### detectFileFormat(InputStream stream) {#detectFileFormat-java.io.InputStream-}
```
public static FileFormatInfo detectFileFormat(InputStream stream)
```


Detects and returns the information about a format of a file stored in a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Source stream. |

**Returns:**
[FileFormatInfo](../../com.aspose.email/fileformatinfo) - The result [FileFormatInfo](../../com.aspose.email/fileformatinfo)
### detectFileFormat(String filePath) {#detectFileFormat-java.lang.String-}
```
public static FileFormatInfo detectFileFormat(String filePath)
```


Detects and returns the information about a format of a file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Path to the source file. |

**Returns:**
[FileFormatInfo](../../com.aspose.email/fileformatinfo) - The result [FileFormatInfo](../../com.aspose.email/fileformatinfo)
