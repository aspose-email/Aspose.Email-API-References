---
title: Class SortConditions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Imap.SortConditions class. Provides the search conditions for the SORT extension. Compatibles with SORT IMAP extension described at https//tools.ietf.org/html/rfc5256
type: docs
weight: 16820
url: /net/aspose.email.clients.imap/sortconditions/
---
## SortConditions class

Provides the search conditions for the SORT extension. Compatibles with SORT IMAP extension described at https://tools.ietf.org/html/rfc5256

```csharp
public sealed class SortConditions : BaseSearchConditions
```

## Constructors

| Name | Description |
| --- | --- |
| [SortConditions](sortconditions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Charset](../../aspose.email.clients.imap/basesearchconditions/charset/) { get; set; } | Gets or sets charset. Indicates the charset of the strings that appear in the searching criteria. |
| [ReverseBy](../../aspose.email.clients.imap/sortconditions/reverseby/) { get; set; } | Gets or sets reverse sort criteria Followed by another sort criterion, has the effect of that criterion but in reverse(descending) order. Note: REVERSE only reverses a single criterion, and does not affect the implicit "sequence number" sort criterion if all other criteria are identical. Consequently, a sort of REVERSE SUBJECT is not the same as a reverse ordering of a SUBJECT sort. This can be avoided by use of additional criteria, e.g., SUBJECT DATE vs. REVERSE SUBJECT REVERSE DATE. In general, however, it's better (and faster, if the client has a "reverse current ordering" command) to reverse the results in the client instead of issuing a new SORT. |
| [Since](../../aspose.email.clients.imap/basesearchconditions/since/) { get; set; } | Gets or sets the message date since which the search criteria matches. |
| [SortBy](../../aspose.email.clients.imap/sortconditions/sortby/) { get; set; } | Gets or sets sort criteria |
| [Text](../../aspose.email.clients.imap/basesearchconditions/text/) { get; set; } | Gets or sets subject text. |
| [UseUId](../../aspose.email.clients.imap/basesearchconditions/useuid/) { get; set; } | Gets or sets a value indicating whether the search method returns sequence numbers or UIDs of messages. |

### See Also

* class [BaseSearchConditions](../basesearchconditions/)
* namespace [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap/)
* assembly [Aspose.Email](../../)


