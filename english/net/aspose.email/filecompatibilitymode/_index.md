---
title: Enum FileCompatibilityMode
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.FileCompatibilityMode enum. Defines inner conversions that are necessarily to be done when loading or saving a message. By default CR is not replaces by CRLF Tnefattachment is not saved
type: docs
weight: 17490
url: /net/aspose.email/filecompatibilitymode/
---
## FileCompatibilityMode enumeration

Defines inner conversions, that are necessarily to be done when loading or saving a message. By default CR is not replaces by CRLF, Tnef-attachment is not saved.

```csharp
[Flags]
public enum FileCompatibilityMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | No values are set. |
| AllowCROnly | `1` | Shows the necessity of the forced replace of line separators by CRLF. |
| PreserveTnefAttachments | `2` | Controls TNEF attachment saving behaviour. This option affects messages whose winmail.dat TNEF attachment (if present) was decoded at loading. If the option is set, the previously decoded and extracted TNEF will be encoded and packaged again into the winmail.dat attachment during message saving. By default the option isn't set. |

### See Also

* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


