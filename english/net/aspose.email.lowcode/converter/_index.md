---
title: Class Converter
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.LowCode.Converter class. Provides functionality to convert email messages between various formats such as EML MSG HTML MHT and MHTML
type: docs
weight: 16330
url: /net/aspose.email.lowcode/converter/
---
## Converter class

Provides functionality to convert email messages between various formats, such as EML, MSG, HTML, MHT, and MHTML.

```csharp
public class Converter
```

## Constructors

| Name | Description |
| --- | --- |
| [Converter](converter/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| static [Convert](../../aspose.email.lowcode/converter/convert/)(Stream, string, IOutputHandler, string) | Detects the email file type based on its extension and delegates to the appropriate converter. |
| static [ConvertEmlOrMsg](../../aspose.email.lowcode/converter/convertemlormsg/)(Stream, string, IOutputHandler, string) | Converts an email file to a specific format if it's not already in that format. |
| static [ConvertToEml](../../aspose.email.lowcode/converter/converttoeml/)(Stream, string, IOutputHandler) | Converts an email message to EML format. |
| static [ConvertToHtml](../../aspose.email.lowcode/converter/converttohtml/)(Stream, string, IOutputHandler) | Converts an email message to HTML format. |
| static [ConvertToMht](../../aspose.email.lowcode/converter/converttomht/)(Stream, string, IOutputHandler) | Converts an email message to MHT format. |
| static [ConvertToMhtml](../../aspose.email.lowcode/converter/converttomhtml/)(Stream, string, IOutputHandler) | Converts an email message to MHTML format. |
| static [ConvertToMsg](../../aspose.email.lowcode/converter/converttomsg/)(Stream, string, IOutputHandler) | Converts an email message to MSG format. |

## Remarks

This class uses a pluggable [`IOutputHandler`](../ioutputhandler/) interface to support flexible output destinations, such as writing files to disk, memory, or cloud storage. Supported input formats: - .eml - .msg Supported output formats: - eml - msg - html - mht - mhtml

## Examples

```csharp
using var input = File.OpenRead("inbox/email.eml");
var outputHandler = new FolderOutputHandler("C:\\ConvertedEmails");
await Converter.Convert(input, "email.eml", outputHandler, "html");
```

### See Also

* namespace [Aspose.Email.LowCode](../../aspose.email.lowcode/)
* assembly [Aspose.Email](../../)


