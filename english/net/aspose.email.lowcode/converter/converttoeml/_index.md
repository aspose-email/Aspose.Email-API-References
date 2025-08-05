---
title: Converter.ConvertToEml
second_title: Aspose.Email for .NET API Reference
description: Converter method. Converts an email message to EML format
type: docs
weight: 40
url: /net/aspose.email.lowcode/converter/converttoeml/
---
## Converter.ConvertToEml method

Converts an email message to EML format.

```csharp
public static Task ConvertToEml(Stream input, string nameWithExtension, IOutputHandler handler)
```

| Parameter | Type | Description |
| --- | --- | --- |
| input | Stream | The email input stream. |
| nameWithExtension | String | Original file name. |
| handler | IOutputHandler | Output handler that will receive the .eml file. |

### Return Value

A completed task.

## Examples

```csharp
using var input = File.OpenRead("message.msg");
var handler = new FolderOutputHandler("C:\\Output");
await Converter.ConvertToEml(input, "message.msg", handler);
```

### See Also

* interface [IOutputHandler](../../ioutputhandler/)
* class [Converter](../)
* namespace [Aspose.Email.LowCode](../../converter/)
* assembly [Aspose.Email](../../../)


