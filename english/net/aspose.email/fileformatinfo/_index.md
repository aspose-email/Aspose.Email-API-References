---
title: Class FileFormatInfo
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.FileFormatInfo class. Contains data returned by FileFormatUtil file format detection methods
type: docs
weight: 17460
url: /net/aspose.email/fileformatinfo/
---
## FileFormatInfo class

Contains data returned by FileFormatUtil file format detection methods.

```csharp
public class FileFormatInfo
```

## Properties

| Name | Description |
| --- | --- |
| [FileFormatType](../../aspose.email/fileformatinfo/fileformattype/) { get; } | Gets file format type. |

## Examples

The following example shows how to detect File Formats of Email Message.

```csharp
[C#]

	// Detect file format and Gets the detected load format
	FileFormatInfo info = FileFormatUtil.DetectFileFormat("message.msg");
	Console.WriteLine("The message format is: " + info.FileFormatType);
```

```csharp
[VB.NET]

	' Detect file format and Gets the detected load format
	Dim info As FileFormatInfo = FileFormatUtil.DetectFileFormat("message.msg")
	Console.WriteLine("The message format is: " & info.FileFormatType)
```

### See Also

* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


