---
title: Converter.ConvertToMhtml
second_title: Aspose.Email for .NET API Reference
description: Converter method. Converts an email message to MHTML format
type: docs
weight: 70
url: /net/aspose.email.lowcode/converter/converttomhtml/
---
## Converter.ConvertToMhtml method

Converts an email message to MHTML format.

```csharp
public static Task ConvertToMhtml(Stream input, string nameWithExtension, IOutputHandler handler)
```

| Parameter | Type | Description |
| --- | --- | --- |
| input | Stream | The email input stream. |
| nameWithExtension | String | Original file name. |
| handler | IOutputHandler | Output handler that will receive the .mhtml file. |

### Return Value

A completed task.

## Examples

```csharp
using var input = File.OpenRead("mail.msg");
var handler = new FolderOutputHandler("C:\\Out");
await Converter.ConvertToMhtml(input, "mail.msg", handler);
```

### See Also

* interface [IOutputHandler](../../ioutputhandler/)
* class [Converter](../)
* namespace [Aspose.Email.LowCode](../../converter/)
* assembly [Aspose.Email](../../../)


