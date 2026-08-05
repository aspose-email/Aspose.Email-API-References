---
title: "Aspose::Email::FileFormatInfo class"
linktitle: "FileFormatInfo"
articleTitle: "FileFormatInfo"
second_title: "Aspose.Email for C++"
description: "Contains data returned by FileFormatUtil file format detection methods."
type: docs
weight: 10
url: /cpp/aspose.email/fileformatinfo/
---

## FileFormatInfo class

Contains data returned by FileFormatUtil file format detection methods.

The following example shows how to detect File Formats of Email Message.

```csharp
// Detect file format and Gets the detected load format
FileFormatInfo info = FileFormatUtil.DetectFileFormat("message.msg");
Console.WriteLine("The message format is: " + info.FileFormatType);
```

```vb
' Detect file format and Gets the detected load format
Dim info As FileFormatInfo = FileFormatUtil.DetectFileFormat("message.msg")
Console.WriteLine("The message format is: " & info.FileFormatType)
```

## Constructors

| Name | Description |
| --- | --- |
| [FileFormatInfo](./fileformatinfo/) |  |

## Methods

| Name | Description |
| --- | --- |
| [get_FileFormatType](./get_fileformattype/) | Gets file format type. |

