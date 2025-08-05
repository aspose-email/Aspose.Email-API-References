---
title: Converter.ConvertToMsg
second_title: Aspose.Email for .NET API Reference
description: Converter method. Converts an email message to MSG format
type: docs
weight: 80
url: /net/aspose.email.lowcode/converter/converttomsg/
---
## Converter.ConvertToMsg method

Converts an email message to MSG format.

```csharp
public static Task ConvertToMsg(Stream input, string nameWithExtension, IOutputHandler handler)
```

| Parameter | Type | Description |
| --- | --- | --- |
| input | Stream | The email input stream. |
| nameWithExtension | String | Original file name. |
| handler | IOutputHandler | Output handler that will receive the .msg file. |

### Return Value

A completed task.

## Examples

```csharp
using var input = File.OpenRead("message.eml");
var handler = new FolderOutputHandler("C:\\Output");
await Converter.ConvertToMsg(input, "message.eml", handler);
```

### See Also

* interface [IOutputHandler](../../ioutputhandler/)
* class [Converter](../)
* namespace [Aspose.Email.LowCode](../../converter/)
* assembly [Aspose.Email](../../../)


