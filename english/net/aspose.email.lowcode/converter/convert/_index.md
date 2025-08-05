---
title: Converter.Convert
second_title: Aspose.Email for .NET API Reference
description: Converter method. Detects the email file type based on its extension and delegates to the appropriate converter
type: docs
weight: 20
url: /net/aspose.email.lowcode/converter/convert/
---
## Converter.Convert method

Detects the email file type based on its extension and delegates to the appropriate converter.

```csharp
public static Task Convert(Stream input, string nameWithExtension, IOutputHandler handler, 
    string outputType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| input | Stream | The input stream representing the email file. |
| nameWithExtension | String | The original name of the file with its extension. |
| handler | IOutputHandler | The output handler responsible for writing the converted file. |
| outputType | String | The desired output format (e.g., "eml", "msg", "html"). |

### Return Value

A task that represents the asynchronous conversion operation.

## Examples

```csharp
using var input = File.OpenRead("email.msg");
var outputHandler = new FolderOutputHandler("C:\\Output");
await Converter.Convert(input, "email.msg", outputHandler, "eml");
```

### See Also

* interface [IOutputHandler](../../ioutputhandler/)
* class [Converter](../)
* namespace [Aspose.Email.LowCode](../../converter/)
* assembly [Aspose.Email](../../../)


