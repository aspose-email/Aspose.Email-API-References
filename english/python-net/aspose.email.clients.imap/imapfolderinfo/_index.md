---
title: ImapFolderInfo
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 130
url: /python-net/aspose.email.clients.imap/imapfolderinfo/
---

## ImapFolderInfo class

Represents an IMAP folder.

The ImapFolderInfo type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|selectable|Gets a value indicating whether it is possible to select this folder.|
|marked|Gets a value indicating whether it is marked this folder.|
|has_children|Gets value indicating whether folder contains subfolders.<br/>            This option is accessible only in case if server supports  IMAP4 LIST Command Extensions (rfc5258)<br/>            See more: http://tools.ietf.org/html/rfc5258<br/>            If value is|
|folder_type|Gets information about folder purpose in case if it is used as special folder.<br/>            This option is accessible only in case if server supports IMAP LIST: Special-Use Mailboxes (rfc6154)<br/>            See more: http://tools.ietf.org/html/rfc6154|
|remote|Gets value indicating that a folder is a remote mailbox.<br/>            This option is accessible only in case if server supports  IMAP4 LIST Command Extensions (rfc5258)<br/>            See more: http://tools.ietf.org/html/rfc5258|
|subscribed|Gets value that indicates that a folder name is subscribed to.<br/>            See more: http://tools.ietf.org/html/rfc5258|
|non_existent|Gets value indicating whether a folder name is referred to an existing folder.<br/>            See more: http://tools.ietf.org/html/rfc5258|
|no_inferiors|Gets a value indicating whether this folder can have child levels. <br/>            If it is|
|name|Gets the name of the folder.|
|new_message_count|Gets the number of the new messages.|
|read_only|Gets a value indicating whether the folder is read-only.|
|recent_message_count|Gets the number of messages that arrived recently.|
|total_message_count|Gets the number of messages in the folder.|
|validity_id|Gets the validity ID of the mailbox.|
|uid_not_sticky|Gets value which indicates if mail store does not support persistent UIDs<br/>            This property works only if server supports UIDPLUS extension. Please, read more https://tools.ietf.org/html/rfc4315|
|no_mod_seq|Gets value which indicates if mailbox supports mod-sequences.<br/>            This property works only if server supports CONDSTORE extension. <br/>            Please, read more https://tools.ietf.org/html/rfc4551#section-3.1.2|
|highest_mod_sequence|Gets value of all messages in the mailbox.<br/>            See more: https://tools.ietf.org/html/rfc7162|
|uid_next|Gets the validity ID of the mailbox.|
|IN_BOX|Gets inbox name.|

### See Also

* namespace [aspose.email.clients.imap](/email/python-net/aspose.email.clients.imap/)
* assembly [Aspose.Email](/email/python-net/)

