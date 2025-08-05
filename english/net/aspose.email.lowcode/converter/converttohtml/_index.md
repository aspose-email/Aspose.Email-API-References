---
title: Converter.ConvertToHtml
second_title: Aspose.Email for .NET API Reference
description: Converter method. Converts an email message to HTML format
type: docs
weight: 50
url: /net/aspose.email.lowcode/converter/converttohtml/
---
## Converter.ConvertToHtml method

Converts an email message to HTML format.

```csharp
public static Task ConvertToHtml(Stream input, string nameWithExtension, IOutputHandler handler)
```

| Parameter | Type | Description |
| --- | --- | --- |
| input | Stream | The email input stream. |
| nameWithExtension | String | Original file name. |
| handler | IOutputHandler | Output handler that will receive the .html file. |

### Return Value

A completed task.

## Examples

```csharp
using var input = File.OpenRead("mail.msg");
var handler = new FolderOutputHandler("C:\\Out");
await Converter.ConvertToHtml(input, "mail.msg", handler);
```

### See Also

* interface [IOutputHandler](../../ioutputhandler/)
* class [Converter](../)
* namespace [Aspose.Email.LowCode](../../converter/)
* assembly [Aspose.Email](../../../)


