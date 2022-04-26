---
title: ImapFolderInfo
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 14730
url: /net/aspose.email.clients.imap/imapfolderinfo/
---
## ImapFolderInfo class

Represents an IMAP folder.

```csharp
public sealed class ImapFolderInfo
```

## Properties

| Name | Description |
| --- | --- |
| [FolderType](foldertype) { get; } | Gets information about folder purpose in case if it is used as special folder. This option is accessible only in case if server supports IMAP LIST: Special-Use Mailboxes (rfc6154) See more: http://tools.ietf.org/html/rfc6154 |
| [HasChildren](haschildren) { get; } | Gets value indicating whether folder contains subfolders. This option is accessible only in case if server supports IMAP4 LIST Command Extensions (rfc5258) See more: http://tools.ietf.org/html/rfc5258 If value is `true`, it indicates that the folder has child sub-folders that are accessible to the currently authenticated user, otherwise false. |
| [HighestModSequence](highestmodsequence) { get; } | Gets value of all messages in the mailbox. See more: https://tools.ietf.org/html/rfc7162 |
| [Marked](marked) { get; } | Gets a value indicating whether it is marked this folder. |
| [Name](name) { get; } | Gets the name of the folder. |
| [NewMessageCount](newmessagecount) { get; } | Gets the number of the new messages. |
| [NoInferiors](noinferiors) { get; } | Gets a value indicating whether this folder can have child levels. If it is `True`, then no child levels exist now and none can be created in the future |
| [NoModSeq](nomodseq) { get; } | Gets value which indicates if mailbox supports mod-sequences. This property works only if server supports CONDSTORE extension. Please, read more https://tools.ietf.org/html/rfc4551#section-3.1.2 |
| [NonExistent](nonexistent) { get; } | Gets value indicating whether a folder name is referred to an existing folder. See more: http://tools.ietf.org/html/rfc5258 |
| [ReadOnly](readonly) { get; } | Gets a value indicating whether the folder is read-only. |
| [RecentMessageCount](recentmessagecount) { get; } | Gets the number of messages that arrived recently. |
| [Remote](remote) { get; } | Gets value indicating that a folder is a remote mailbox. This option is accessible only in case if server supports IMAP4 LIST Command Extensions (rfc5258) See more: http://tools.ietf.org/html/rfc5258 |
| [Selectable](selectable) { get; } | Gets a value indicating whether it is possible to select this folder. |
| [Subscribed](subscribed) { get; } | Gets value that indicates that a folder name is subscribed to. See more: http://tools.ietf.org/html/rfc5258 |
| [TotalMessageCount](totalmessagecount) { get; } | Gets the number of messages in the folder. |
| [UIDNext](uidnext) { get; } | Gets the validity ID of the mailbox. |
| [UidNotSticky](uidnotsticky) { get; } | Gets value which indicates if mail store does not support persistent UIDs This property works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315 |
| [ValidityId](validityid) { get; } | Gets the validity ID of the mailbox. |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](tostring)() | Returns a string that represents the current object. |

## Other Members

| Name | Description |
| --- | --- |
| const [InBox](inbox) | Gets inbox name. |

### See Also

* namespace [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->