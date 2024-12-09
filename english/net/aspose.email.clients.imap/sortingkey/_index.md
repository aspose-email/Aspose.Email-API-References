---
title: Enum SortingKey
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Imap.SortingKey enum. Sort criterias for SORT command See more https//tools.ietf.org/html/rfc5256
type: docs
weight: 16840
url: /net/aspose.email.clients.imap/sortingkey/
---
## SortingKey enumeration

Sort criterias for "SORT" command See more: https://tools.ietf.org/html/rfc5256

```csharp
[Flags]
public enum SortingKey
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Arrival | `1` | By internal date and time of the message. This differs from the ON criteria in SEARCH, which uses just the internal date. |
| Cc | `2` | By first "cc" address. |
| Date | `4` | By sent date and time. |
| From | `8` | By first "From" address. |
| Size | `10` | By size of the message in octets. |
| Subject | `20` | By subject |
| To | `40` | By first "To" address. |

### See Also

* namespace [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap/)
* assembly [Aspose.Email](../../)


