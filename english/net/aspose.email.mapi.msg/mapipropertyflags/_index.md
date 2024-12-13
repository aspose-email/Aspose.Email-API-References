---
title: Enum MapiPropertyFlags
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.Msg.MapiPropertyFlags enum. Represents flags which can be set on a MAPI property
type: docs
weight: 18980
url: /net/aspose.email.mapi.msg/mapipropertyflags/
---
## MapiPropertyFlags enumeration

Represents flags which can be set on a MAPI property.

```csharp
[Flags]
public enum MapiPropertyFlags
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| PROPATTR_MANDATORY | `1` | If this flag is set for a property, that property MUST NOT be deleted from the .msg file (irrespective of which storage it is contained in) and implementations MUST return an error if any attempt is made to do so. This flag is set in circumstances where the implementation depends on that property always being present in the .msg file once it is written there. |
| PROPATTR_READABLE | `2` | If this flag is not set on a property, that property MUST not be read from the .msg file and implementations MUST return an error if any attempt is made to read it. This flag is set on all properties unless there is an implementation-specific reason to prevent a property from being read from the .msg file. |
| PROPATTR_WRITABLE | `4` | If this flag is not set on a property, that property MUST not be modified or deleted and implementations MUST return an error if any attempt is made to do so. This flag is set in circumstances where the implementation depends on the properties being writable. |

### See Also

* namespace [Aspose.Email.Mapi.Msg](../../aspose.email.mapi.msg/)
* assembly [Aspose.Email](../../)


