---
title: "ImapStatusCode Enum"
linktitle: "ImapStatusCode"
articleTitle: "ImapStatusCode"
second_title: "Aspose.Email for C++"
description: "Represents the status responses."
type: docs
weight: 10
url: /cpp/aspose.email.clients.imap/imapstatuscode/
---

## ImapStatusCode enumeration (18 values)

Represents the status responses.

| Value | Description |
| --- | --- |
| NotDefined | Not defined |
| Ok | The OK response indicates an information message from the server. When tagged, it indicates successful completion of the associated command. The human-readable text MAY be presented to the user as an information message. The untagged form indicates an information-only message; the nature of the information MAY be indicated by a response code. |
| No | The NO response indicates an operational error message from the server. When tagged, it indicates unsuccessful completion of the associated command. The untagged form indicates a warning; the command can still complete successfully. The human-readable text describes the condition. |
| Bad | The BAD response indicates an error message from the server. When tagged, it reports a protocol-level error in the client's command; the tag indicates the command that caused the error. The untagged form indicates a protocol-level error for which the associated command can not be determined; it can also indicate an internal server failure. The human-readable text describes the condition. |
| Preauth | The PREAUTH response is always untagged, and is one of three possible greetings at connection startup. It indicates that the connection has already been authenticated by external means and thus no LOGIN command is needed. |
| Bye | The BYE response is always untagged, and indicates that the server is about to close the connection. The human-readable text MAY be displayed to the user in a status report by the client. The difference between a BYE that occurs as part of a normal LOGOUT sequence (the first case) and a BYE that occurs because of a failure (the other three cases) is that the connection closes immediately in the failure case. |
| Alert | The human-readable text contains a special alert that MUST be presented to the user in a fashion that calls the user's attention to the message. |
| BadCharset | Optionally followed by a parenthesized list of charsets. A SEARCH failed because the given charset is not supported by this implementation. |
| Capability | Followed by a list of capabilities. |
| Parse | The human-readable text represents an error in parsing the [RFC-2822] header or [MIME-IMB] headers of a message in the mailbox. |
| PermanentFlags | Followed by a parenthesized list of flags, indicates which of the known flags the client can change permanently. |
| ReadOnly | The mailbox is selected read-only. |
| ReadWrite | The mailbox is selected read-write. |
| TryCreate | An APPEND or COPY attempt is failing because the target mailbox does not exist. |
| UIDNext | Indicates the next unique identifier value. |
| UIDValidity | Indicates the unique identifier validity value. |
| Unseen | Indicates the number of the first message without the \Seen flag set. |
| Unsolicited | Untagged status responses. |

