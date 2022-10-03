---
title: ImapSpecialFolderTypes
second_title: Aspose.Email for Java API Reference
description: Represents enumeration of special-use mailboxes More details see in RFC6154  http//tools.ietf.org/html/rfc6154
type: docs
weight: 330
url: /java/com.aspose.email/imapspecialfoldertypes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ImapSpecialFolderTypes extends System.Enum
```

Represents enumeration of special-use mailboxes More details see in RFC6154 http://tools.ietf.org/html/rfc6154
## Fields

| Field | Description |
| --- | --- |
| [NotSpecified](#NotSpecified) | If IMAP LIST Extension for Special-Use Mailboxes (RFC6154) is supported, this means that mailbox is regular and does not used for special purposes. |
| [All](#All) | This mailbox presents all messages in the user's message store. |
| [Archive](#Archive) | This mailbox is used to archive messages. |
| [Drafts](#Drafts) | This mailbox is used to hold draft messages typically, messages that are being composed but have not yet been sent. |
| [Flagged](#Flagged) | This mailbox presents all messages marked in some way as "important". |
| [Junk](#Junk) | This mailbox is where messages deemed to be junk mail are held. |
| [Sent](#Sent) | This mailbox is used to hold copies of messages that have been sent. |
| [Trash](#Trash) | This mailbox is used to hold messages that have been deleted or marked for deletion. |
| [Important](#Important) | This mailbox is used to hold messages that have been marked as important. |
### NotSpecified {#NotSpecified}
```
public static final int NotSpecified
```


If IMAP LIST Extension for Special-Use Mailboxes (RFC6154) is supported, this means that mailbox is regular and does not used for special purposes.

### All {#All}
```
public static final int All
```


This mailbox presents all messages in the user's message store. Implementations MAY omit some messages, such as, perhaps, those in \\Trash and \\Junk. When this special use is supported, it is almost certain to represent a virtual mailbox.

### Archive {#Archive}
```
public static final int Archive
```


This mailbox is used to archive messages. The meaning of an "archival" mailbox is server-dependent; typically, it will be used to get messages out of the inbox, or otherwise keep them out of the user's way, while still making them accessible.

### Drafts {#Drafts}
```
public static final int Drafts
```


This mailbox is used to hold draft messages typically, messages that are being composed but have not yet been sent. In some server implementations, this might be a virtual mailbox, containing messages from other mailboxes that are marked with the "\\Draft" message flag. Alternatively, this might just be advice that a client put drafts here.

### Flagged {#Flagged}
```
public static final int Flagged
```


This mailbox presents all messages marked in some way as "important". When this special use is supported, it is likely to represent a virtual mailbox collecting messages (from other mailboxes) that are marked with the "\\Flagged" message flag.

### Junk {#Junk}
```
public static final int Junk
```


This mailbox is where messages deemed to be junk mail are held. Some server implementations might put messages here automatically. Alternatively, this might just be advice to a client-side spam filter.

### Sent {#Sent}
```
public static final int Sent
```


This mailbox is used to hold copies of messages that have been sent. Some server implementations might put messages here automatically. Alternatively, this might just be advice that a client save sent messages here.

### Trash {#Trash}
```
public static final int Trash
```


This mailbox is used to hold messages that have been deleted or marked for deletion. In some server implementations, this might be a virtual mailbox, containing messages from other mailboxes that are marked with the "\\Deleted" message flag. Alternatively, this might just be advice that a client that chooses not to use the IMAP "\\Deleted" model should use this as its trash location. In server implementations that strictly expect the IMAP "\\Deleted" model, this special use is likely not to be supported.

### Important {#Important}
```
public static final int Important
```


This mailbox is used to hold messages that have been marked as important. The "\\Important" mailbox attribute is a signal that the mailbox contains messages that are likely important to the user. In an implementation that also supports the "$Important" keyword, this special use is likely to represent a virtual mailbox collecting messages (from other mailboxes) that are marked with the "$Important" keyword. In other implementations, the system might automatically put messages there based on the same sorts of heuristics that are noted for the "$Important" keyword. The distinctions between "\\Important" and "\\Flagged" for mailboxes are similar to those between "$Important" and "\\Flagged" for messages. https://tools.ietf.org/html/rfc8457

