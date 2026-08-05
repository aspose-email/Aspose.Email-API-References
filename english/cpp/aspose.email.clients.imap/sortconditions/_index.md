---
title: "Aspose::Email::Clients::Imap::SortConditions class"
linktitle: "SortConditions"
articleTitle: "SortConditions"
second_title: "Aspose.Email for C++"
description: "Provides the search conditions for the SORT extension."
type: docs
weight: 10
url: /cpp/aspose.email.clients.imap/sortconditions/
---

## SortConditions class

**Inherits:** Aspose::Email::Clients::Imap::BaseSearchConditions

Provides the search conditions for the SORT extension. Compatibles with SORT IMAP extension described at https://tools.ietf.org/html/rfc5256

## Constructors

| Name | Description |
| --- | --- |
| [SortConditions](./sortconditions/) |  |

## Methods

| Name | Description |
| --- | --- |
| [get_ReverseBy](./get_reverseby/) | Gets reverse sort criteria Followed by another sort criterion, has the effect of that criterion but in reverse(descending) order. Note: REVERSE only reverses a single criterion, and does not affect the implicit "sequence number" sort criterion if all other criteria are identical. Consequently, a sort of REVERSE SUBJECT is not the same as a reverse ordering of a SUBJECT sort. This can be avoided by use of additional criteria, e.g., SUBJECT DATE vs. REVERSE SUBJECT REVERSE DATE. In general, however, it's better (and faster, if the client has a "reverse current ordering" command) to reverse the results in the client instead of issuing a new SORT. |
| [get_SortBy](./get_sortby/) | Gets sort criteria |
| [set_ReverseBy](./set_reverseby/) | Sets reverse sort criteria Followed by another sort criterion, has the effect of that criterion but in reverse(descending) order. Note: REVERSE only reverses a single criterion, and does not affect the implicit "sequence number" sort criterion if all other criteria are identical. Consequently, a sort of REVERSE SUBJECT is not the same as a reverse ordering of a SUBJECT sort. This can be avoided by use of additional criteria, e.g., SUBJECT DATE vs. REVERSE SUBJECT REVERSE DATE. In general, however, it's better (and faster, if the client has a "reverse current ordering" command) to reverse the results in the client instead of issuing a new SORT. |
| [set_SortBy](./set_sortby/) | Sets sort criteria |

