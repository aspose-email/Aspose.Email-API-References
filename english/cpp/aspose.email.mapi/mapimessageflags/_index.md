---
title: "MapiMessageFlags Enum"
linktitle: "MapiMessageFlags"
articleTitle: "MapiMessageFlags"
second_title: "Aspose.Email for C++"
description: "MapiMessageFlags."
type: docs
weight: 10
url: /cpp/aspose.email.mapi/mapimessageflags/
---

## MapiMessageFlags enumeration (15 values)

MapiMessageFlags.

| Value | Description |
| --- | --- |
| MSGFLAG_ZERO |  |
| MSGFLAG_READ | The message is marked as having been read. |
| MSGFLAG_UNMODIFIED | The message has not been modified since it was first saved (if unsent) or it was delivered (if sent). |
| MSGFLAG_SUBMIT | The message is marked for sending as a result of a call to IMessage::SubmitMessage. Message store providers set this flag; the client has read-only access. |
| MSGFLAG_UNSENT | The message is still being composed. It is saved, but has not been sent. |
| MSGFLAG_HASATTACH | The message has at least one attachment. |
| MSGFLAG_FROMME | The user receiving the message was also the user who sent the message. |
| MSGFLAG_ASSOCIATED | MSGFLAG_ASSOCIATED. |
| MSGFLAG_RESEND | The message includes a request for a resend operation with a non-delivery report. |
| MSGFLAG_NOTIFYREAD | The user who sent the message has requested notification when a recipient first reads it. |
| MSGFLAG_NOTIFYUNREAD | The user who sent the message has requested notification when a recipient deletes it before reading or the Message object expires. |
| MSGFLAG_EVERREAD | The message has been read at least once. This flag is set or cleared by the server whenever the MSGFLAG_READ flag is set or cleared. |
| MSGFLAG_ORIGIN_X400 | The incoming message arrived over an X.400 link. |
| MSGFLAG_ORIGIN_INTERNET | The incoming message arrived over the Internet. |
| MSGFLAG_ORIGIN_MISC_EXT | The incoming message arrived over an external link other than X.400 or the Internet. |

