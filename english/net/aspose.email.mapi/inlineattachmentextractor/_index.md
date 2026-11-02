---
title: Class InlineAttachmentExtractor
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.InlineAttachmentExtractor class. Extracts the files packed into an MSO package such as the oledata.mso attachment that Outlook adds to messages with embedded images or objects
type: docs
weight: 16630
url: /net/aspose.email.mapi/inlineattachmentextractor/
---
## InlineAttachmentExtractor class

Extracts the files packed into an MSO package, such as the `oledata.mso` attachment that Outlook adds to messages with embedded images or objects.

```csharp
public static class InlineAttachmentExtractor
```

## Methods

| Name | Description |
| --- | --- |
| static [EnumerateMsoPackage](../../aspose.email.mapi/inlineattachmentextractor/enumeratemsopackage/)(Stream) | Reads an MSO package and returns the files it contains. |

## Examples

This example finds the `oledata.mso` attachment of a message and saves every file it contains.

[C#]

```csharp
var msg = MapiMessage.Load("message.msg");

foreach (var attachment in msg.Attachments)
{
    if (attachment.LongFileName != "oledata.mso")
        continue;

    using (Stream package = attachment.OpenRead())
    {
        IDictionary<string, byte[]> files = InlineAttachmentExtractor.EnumerateMsoPackage(package);
        foreach (var file in files)
        {
            // the key is the identifier the message body uses to refer to the file
            File.WriteAllBytes(Path.Combine("output", file.Key), file.Value);
        }
    }
}
```

[Visual Basic]

```csharp
Dim msg = MapiMessage.Load("message.msg")

For Each attachment In msg.Attachments
    If attachment.LongFileName <> "oledata.mso" Then Continue For

    Using package As Stream = attachment.OpenRead()
        Dim files As IDictionary(Of String, Byte()) = InlineAttachmentExtractor.EnumerateMsoPackage(package)
        For Each file In files
            ' the key is the identifier the message body uses to refer to the file
            System.IO.File.WriteAllBytes(Path.Combine("output", file.Key), file.Value)
        Next
    End Using
Next
```

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


