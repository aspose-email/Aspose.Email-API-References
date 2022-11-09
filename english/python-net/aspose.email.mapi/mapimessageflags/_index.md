---
title: MapiMessageFlags
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 1060
url: /python-net/aspose.email.mapi/mapimessageflags/
---

## MapiMessageFlags enumeration

MapiMessageFlags.

## Members
| Member name | Description |
| :- | :- |
|ZERO||
|READ|The message is marked as having been read.|
|UNMODIFIED|The message has not been modified since it was first saved (if unsent) or it was delivered (if sent).|
|SUBMIT|The message is marked for sending as a result of a call to IMessage::SubmitMessage. <br/>            Message store providers set this flag; the client has read-only access.|
|UNSENT|The message is still being composed. It is saved, but has not been sent.|
|HASATTACH|The message has at least one attachment.|
|FROMME|The user receiving the message was also the user who sent the message.|
|ASSOCIATED|MSGFLAG_ASSOCIATED.|
|RESEND|The message includes a request for a resend operation with a non-delivery report.|
|NOTIFYREAD|The user who sent the message has requested notification when a recipient first reads it.|
|NOTIFYUNREAD|The user who sent the message has requested notification when a recipient deletes it before reading or the Message object expires.|
|EVERREAD|The message has been read at least once. This flag is set or cleared by the server whenever the|
|ORIGIN_X400|The incoming message arrived over an X.400 link.|
|ORIGIN_INTERNET|The incoming message arrived over the Internet.|
|ORIGIN_MISC_EXT|The incoming message arrived over an external link other than X.400 or the Internet.|

### See Also

* namespace [aspose.email.mapi](/python-net/aspose.email.mapi/)
* assembly [Aspose.Email](/python-net/)

