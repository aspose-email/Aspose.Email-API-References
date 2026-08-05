---
title: "FileCompatibilityMode Enum"
linktitle: "FileCompatibilityMode"
articleTitle: "FileCompatibilityMode"
second_title: "Aspose.Email for C++"
description: "Defines inner conversions, that are necessarily to be done when loading or saving a message."
type: docs
weight: 10
url: /cpp/aspose.email/filecompatibilitymode/
---

## FileCompatibilityMode enumeration (3 values)

Defines inner conversions, that are necessarily to be done when loading or saving a message. By default CR is not replaces by CRLF, Tnef-attachment is not saved.

| Value | Description |
| --- | --- |
| None | No values are set. |
| AllowCROnly | Shows the necessity of the forced replace of line separators by CRLF. |
| PreserveTnefAttachments | Controls TNEF attachment saving behaviour. This option affects messages whose winmail.dat TNEF attachment (if present) was decoded at loading. If the option is set, the previously decoded and extracted TNEF will be encoded and packaged again into the winmail.dat attachment during message saving. By default the option isn't set. |

