---
title: ImapSpecialFolderTypes
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 500
url: /email/python-net/aspose.email.clients.imap/imapspecialfoldertypes/
---

## ImapSpecialFolderTypes enumeration

Represents enumeration of special-use mailboxes<br/>            More details see in RFC6154 <br/>            http://tools.ietf.org/html/rfc6154

## Members
| Member name | Description |
| :- | :- |
|NOT_SPECIFIED|If IMAP LIST Extension for Special-Use Mailboxes (RFC6154) is supported, this means that mailbox is regular and does not used for special purposes.|
|ALL|This mailbox presents all messages in the user's message store. <br/>            Implementations MAY omit some messages, such as, perhaps, those in \Trash and \Junk.  <br/>            When this special use is supported, it is almost certain to represent a virtual mailbox.|
|ARCHIVE|This mailbox is used to archive messages.<br/>            The meaning of an "archival" mailbox is server-dependent; typically, it will be used to get messages out of the inbox, <br/>            or otherwise keep them out of the user's way, while still making them accessible.|
|DRAFTS|This mailbox is used to hold draft messages typically, messages that are being composed but have not yet been sent.<br/>            In some server implementations, this might be a virtual mailbox, containing messages from other mailboxes that are marked with the "\Draft" message flag.  <br/>            Alternatively, this might just be advice that a client put drafts here.|
|FLAGGED|This mailbox presents all messages marked in some way as "important".<br/>            When this special use is supported, it is likely to represent a virtual mailbox collecting messages (from other mailboxes) that are marked with the "\Flagged" message flag.|
|JUNK|This mailbox is where messages deemed to be junk mail are held.<br/>            Some server implementations might put messages here automatically.  <br/>            Alternatively, this might just be advice to a client-side spam filter.|
|SENT|This mailbox is used to hold copies of messages that have been sent.<br/>            Some server implementations might put messages here automatically.  <br/>            Alternatively, this might just be advice that a client save sent messages here.|
|TRASH|This mailbox is used to hold messages that have been deleted or marked for deletion.<br/>            In some server implementations, this might be a virtual mailbox, containing messages from other mailboxes that are marked with the "\Deleted" message flag. <br/>            Alternatively, this might just be advice that a client that chooses not to use the IMAP "\Deleted" model should use this as its trash location.  <br/>            In server implementations that strictly expect the IMAP "\Deleted" model, this special use is likely not to be supported.|
|IMPORTANT|This mailbox is used to hold messages that have been marked as important.<br/>            The "\Important" mailbox attribute is a signal that the mailbox contains messages that are likely important to the user.<br/>            In an implementation that also supports the "$Important" keyword, this special use is likely to represent a virtual mailbox collecting messages (from other mailboxes) that are marked with the "$Important" keyword. <br/>            In other implementations, the system might automatically put messages there based on the same sorts of heuristics that are noted for the "$Important" keyword.  <br/>            The distinctions between "\Important" and "\Flagged" for mailboxes are similar to those between "$Important" and "\Flagged" for messages.<br/>            https://tools.ietf.org/html/rfc8457|

### See Also

* namespace [aspose.email.clients.imap](/email/python-net/aspose.email.clients.imap/)
* assembly [Aspose.Email](/slides/python-net/)

