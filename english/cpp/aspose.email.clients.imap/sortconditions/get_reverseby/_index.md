---
title: "Aspose::Email::Clients::Imap::SortConditions::get_ReverseBy method"
linktitle: "get_ReverseBy"
articleTitle: "get_ReverseBy"
second_title: "Aspose.Email for C++"
description: "Gets reverse sort criteria Followed by another sort criterion, has the effect of that criterion but in reverse(descending) order."
type: docs
weight: 10
url: /cpp/aspose.email.clients.imap/sortconditions/get_reverseby/
---

## get_ReverseBy {#get_reverseby}

Gets reverse sort criteria Followed by another sort criterion, has the effect of that criterion but in reverse(descending) order. Note: REVERSE only reverses a single criterion, and does not affect the implicit "sequence number" sort criterion if all other criteria are identical. Consequently, a sort of REVERSE SUBJECT is not the same as a reverse ordering of a SUBJECT sort. This can be avoided by use of additional criteria, e.g., SUBJECT DATE vs. REVERSE SUBJECT REVERSE DATE. In general, however, it's better (and faster, if the client has a "reverse current ordering" command) to reverse the results in the client instead of issuing a new SORT.

**Returns:** SortingKey Aspose::Email::Clients::Imap::

```cpp
get_ReverseBy()
```

