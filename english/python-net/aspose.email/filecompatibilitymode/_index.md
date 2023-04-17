---
title: FileCompatibilityMode
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 4930
url: /python-net/aspose.email/filecompatibilitymode/
---

## FileCompatibilityMode enumeration

Defines inner conversions, <br/>            that are necessarily to be done when loading <br/>            or saving a message. <br/>            By default CR is not replaces by CRLF, <br/>            Tnef-attachment is not saved.

## Members
| Member name | Description |
| :- | :- |
|NONE|No values are set.|
|ALLOW_CR_ONLY|Shows the necessity of the forced replace <br/>            of line separators by CRLF.|
|PRESERVE_TNEF_ATTACHMENTS|Controls TNEF attachment saving behaviour.<br/>            This option affects messages whose winmail.dat TNEF attachment (if present) was decoded at loading.<br/>            If the option is set, the previously decoded and extracted TNEF will be encoded and packaged again into the winmail.dat attachment during message saving.<br/>            By default the option isn't set.|

### See Also

* namespace [aspose.email](/email/python-net/aspose.email/)
* assembly [Aspose.Email](/email/python-net/)

