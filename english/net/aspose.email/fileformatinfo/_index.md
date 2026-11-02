---
title: Class FileFormatInfo
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.FileFormatInfo class. Information about the format of a file as detected by FileFormatUtil.DetectFileFormat
type: docs
weight: 16210
url: /net/aspose.email/fileformatinfo/
---
## FileFormatInfo class

Information about the format of a file, as detected by `FileFormatUtil.DetectFileFormat`.

```csharp
public class FileFormatInfo
```

## Properties

| Name | Description |
| --- | --- |
| [FileFormatType](../../aspose.email/fileformatinfo/fileformattype/) { get; } | Gets the detected file format. |

## Examples

The following example shows how to detect File Formats of Email Message.

[C#]

```csharp
// Detect file format and Gets the detected load format
FileFormatInfo info = FileFormatUtil.DetectFileFormat("message.msg");
Console.WriteLine("The message format is: " + info.FileFormatType);
```

[Visual Basic]

```csharp
' Detect file format and Gets the detected load format
Dim info As FileFormatInfo = FileFormatUtil.DetectFileFormat("message.msg")
Console.WriteLine("The message format is: " & info.FileFormatType)
```

### See Also

* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


