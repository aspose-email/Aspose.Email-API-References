---
title: SortConditions
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 370
url: /python-net/aspose.email.clients.imap/sortconditions/
---

## SortConditions class

Provides the search conditions for the SORT extension.<br/>            Compatibles with SORT IMAP extension described at<br/>            https://tools.ietf.org/html/rfc5256

The SortConditions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|SortConditions()|Initializes a new instance of the SortConditions class|
## Properties
| Name | Description |
| :- | :- |
|use_u_id|Gets or sets a value indicating whether<br/>            the search method returns sequence numbers or UIDs of messages.|
|charset|Gets or sets charset.<br/>            Indicates the charset of the strings that<br/>            appear in the searching criteria.|
|text|Gets or sets subject text.|
|since|Gets or sets the message date since<br/>            which the search criteria matches.|
|sort_by|Gets or sets sort criteria|
|reverse_by|Gets or sets reverse sort criteria <br/>            Followed by another sort criterion, has the effect of that criterion but in reverse(descending) order. <br/>            Note: <br/>            REVERSE only reverses a single criterion, and does not affect the implicit "sequence number" sort criterion if all other criteria are identical.<br/>            Consequently, a sort of REVERSE SUBJECT is not the same as a reverse ordering of a SUBJECT sort.<br/>            This can be avoided by use of additional criteria, e.g., SUBJECT DATE vs. REVERSE SUBJECT REVERSE DATE.  <br/>            In general, however, it's better (and faster, if the client has a "reverse current ordering" command) to reverse the results in the client instead of issuing a new SORT.|

### See Also

* namespace [aspose.email.clients.imap](/python-net/aspose.email.clients.imap/)
* assembly [Aspose.Email](/python-net/)

