---
title: Enum FileCompatibilityMode
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.FileCompatibilityMode enum. Defines conversions applied while a message is loaded or saved. The values can be combined
type: docs
weight: 16190
url: /net/aspose.email/filecompatibilitymode/
---
## FileCompatibilityMode enumeration

Defines conversions applied while a message is loaded or saved. The values can be combined.

```csharp
[Flags]
public enum FileCompatibilityMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | No conversions. |
| AllowCROnly | `1` | Line breaks that are a bare CR are replaced by CRLF. |
| PreserveTnefAttachments | `2` | Controls TNEF attachment saving behaviour. This option affects messages whose winmail.dat TNEF attachment (if present) was decoded at loading. If the option is set, the previously decoded and extracted TNEF will be encoded and packaged again into the winmail.dat attachment during message saving. By default the option isn't set. |

### See Also

* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


