---
title: Converter.ConvertToMht
second_title: Aspose.Email for .NET API Reference
description: Converter method. Converts an email message to MHT format
type: docs
weight: 60
url: /net/aspose.email.lowcode/converter/converttomht/
---
## Converter.ConvertToMht method

Converts an email message to MHT format.

```csharp
public static Task ConvertToMht(Stream input, string nameWithExtension, IOutputHandler handler)
```

| Parameter | Type | Description |
| --- | --- | --- |
| input | Stream | The email input stream. |
| nameWithExtension | String | Original file name. |
| handler | IOutputHandler | Output handler that will receive the .mht file. |

### Return Value

A completed task.

## Examples

```csharp
using var input = File.OpenRead("mail.eml");
var handler = new FolderOutputHandler("C:\\Out");
await Converter.ConvertToMht(input, "mail.eml", handler);
```

### See Also

* interface [IOutputHandler](../../ioutputhandler/)
* class [Converter](../)
* namespace [Aspose.Email.LowCode](../../converter/)
* assembly [Aspose.Email](../../../)


