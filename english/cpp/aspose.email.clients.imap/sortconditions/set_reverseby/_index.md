---
title: "Aspose::Email::Clients::Imap::SortConditions::set_ReverseBy method"
linktitle: "set_ReverseBy"
articleTitle: "set_ReverseBy"
second_title: "Aspose.Email for C++"
description: "Sets reverse sort criteria Followed by another sort criterion, has the effect of that criterion but in reverse(descending) order."
type: docs
weight: 30
url: /cpp/aspose.email.clients.imap/sortconditions/set_reverseby/
---

## set_ReverseBy {#set_reverseby}

Sets reverse sort criteria Followed by another sort criterion, has the effect of that criterion but in reverse(descending) order. Note: REVERSE only reverses a single criterion, and does not affect the implicit "sequence number" sort criterion if all other criteria are identical. Consequently, a sort of REVERSE SUBJECT is not the same as a reverse ordering of a SUBJECT sort. This can be avoided by use of additional criteria, e.g., SUBJECT DATE vs. REVERSE SUBJECT REVERSE DATE. In general, however, it's better (and faster, if the client has a "reverse current ordering" command) to reverse the results in the client instead of issuing a new SORT.

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
set_ReverseBy(SortingKey value)
```

| Parameter | Description |
| --- | --- |
| value |  |

