---
title: SortConditions.ReverseBy
second_title: Aspose.Email for .NET API Reference
description: SortConditions property. Gets or sets reverse sort criteria Followed by another sort criterion has the effect of that criterion but in reversedescending order. Note REVERSE only reverses a single criterion and does not affect the implicit sequence number sort criterion if all other criteria are identical. Consequently a sort of REVERSE SUBJECT is not the same as a reverse ordering of a SUBJECT sort. This can be avoided by use of additional criteria e.g. SUBJECT DATE vs. REVERSE SUBJECT REVERSE DATE. In general however its better and faster if the client has a reverse current ordering command to reverse the results in the client instead of issuing a new SORT
type: docs
weight: 20
url: /net/aspose.email.clients.imap/sortconditions/reverseby/
---
## SortConditions.ReverseBy property

Gets or sets reverse sort criteria Followed by another sort criterion, has the effect of that criterion but in reverse(descending) order. Note: REVERSE only reverses a single criterion, and does not affect the implicit "sequence number" sort criterion if all other criteria are identical. Consequently, a sort of REVERSE SUBJECT is not the same as a reverse ordering of a SUBJECT sort. This can be avoided by use of additional criteria, e.g., SUBJECT DATE vs. REVERSE SUBJECT REVERSE DATE. In general, however, it's better (and faster, if the client has a "reverse current ordering" command) to reverse the results in the client instead of issuing a new SORT.

```csharp
public SortingKey ReverseBy { get; set; }
```

### See Also

* enum [SortingKey](../../sortingkey/)
* class [SortConditions](../)
* namespace [Aspose.Email.Clients.Imap](../../sortconditions/)
* assembly [Aspose.Email](../../../)


