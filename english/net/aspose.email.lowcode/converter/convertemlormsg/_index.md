---
title: Converter.ConvertEmlOrMsg
second_title: Aspose.Email for .NET API Reference
description: Converter method. Converts an email file to a specific format if its not already in that format
type: docs
weight: 30
url: /net/aspose.email.lowcode/converter/convertemlormsg/
---
## Converter.ConvertEmlOrMsg method

Converts an email file to a specific format if it's not already in that format.

```csharp
public static Task ConvertEmlOrMsg(Stream input, string nameWithExtension, IOutputHandler handler, 
    string outputType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| input | Stream | The email input stream. |
| nameWithExtension | String | The file name with extension. |
| handler | IOutputHandler | The output handler for writing the result. |
| outputType | String | Target format (e.g., "eml", "msg", "html", "mht", "mhtml"). |

### Return Value

A task that represents the asynchronous operation.

## Examples

```csharp
using var input = File.OpenRead("email.eml");
var outputHandler = new FolderOutputHandler("C:\\Converted");
await Converter.ConvertEmlOrMsg(input, "email.eml", outputHandler, "html");
```

### See Also

* interface [IOutputHandler](../../ioutputhandler/)
* class [Converter](../)
* namespace [Aspose.Email.LowCode](../../converter/)
* assembly [Aspose.Email](../../../)


