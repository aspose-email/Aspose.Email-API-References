---
title: MapiPropertyFlags
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 120
url: /python-net/aspose.email.mapi.msg/mapipropertyflags/
---

## MapiPropertyFlags enumeration

Represents flags which can be set on a MAPI property.

## Members
| Member name | Description |
| :- | :- |
|MANDATORY|If this flag is set for a property, that property MUST NOT be deleted from the .msg file (irrespective of which storage it is contained in) and implementations MUST return an error if any attempt is made to do so. This flag is set in circumstances where the implementation depends on that property always being present in the .msg file once it is written there.|
|READABLE|If this flag is not set on a property, that property MUST not be read from the .msg file and implementations MUST return an error if any attempt is made to read it. This flag is set on all properties unless there is an implementation-specific reason to prevent a property from being read from the .msg file.|
|WRITABLE|If this flag is not set on a property, that property MUST not be modified or deleted and implementations MUST return an error if any attempt is made to do so. This flag is set in circumstances where the implementation depends on the properties being writable.|

### See Also

* namespace [aspose.email.mapi.msg](/python-net/aspose.email.mapi.msg/)
* assembly [Aspose.Email](/python-net/)

