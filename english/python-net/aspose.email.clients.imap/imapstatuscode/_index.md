---
title: ImapStatusCode
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 510
url: /python-net/aspose.email.clients.imap/imapstatuscode/
---

## ImapStatusCode enumeration

Represents the status responses.

## Members
| Member name | Description |
| :- | :- |
|NOT_DEFINED|Not defined|
|OK|The OK response indicates an information message from the server. <br/>            When tagged, it indicates successful completion of the associated command.  <br/>            The human-readable text MAY be presented to the user as an information message.  <br/>            The untagged form indicates an information-only message; the nature of the information MAY be indicated by a response code.|
|NO|The NO response indicates an operational error message from the server.  <br/>            When tagged, it indicates unsuccessful completion of the associated command.  <br/>            The untagged form indicates a warning; the command can still complete successfully.  <br/>            The human-readable text describes the condition.|
|BAD|The BAD response indicates an error message from the server.  <br/>            When tagged, it reports a protocol-level error in the client's command; <br/>            the tag indicates the command that caused the error.  <br/>            The untagged form indicates a protocol-level error for which the associated command can not be determined; <br/>            it can also indicate an internal server failure.  <br/>            The human-readable text describes the condition.|
|PREAUTH|The PREAUTH response is always untagged, and is one of three possible greetings at connection startup.  <br/>            It indicates that the connection has already been authenticated by external means and thus no LOGIN command is needed.|
|BYE|The BYE response is always untagged, and indicates that the server is about to close the connection.  <br/>            The human-readable text MAY be displayed to the user in a status report by the client.  <br/>            The difference between a BYE that occurs as part of a normal LOGOUT sequence (the first case) and a BYE <br/>            that occurs because of a failure (the other three cases) is that the connection closes immediately in the failure case.|
|ALERT|The human-readable text contains a special alert that MUST be presented to the user <br/>            in a fashion that calls the user's attention to the message.|
|BAD_CHARSET|Optionally followed by a parenthesized list of charsets. <br/>            A SEARCH failed because the given charset is not supported by this implementation.|
|CAPABILITY|Followed by a list of capabilities.|
|PARSE|The human-readable text represents an error in parsing the<br/>            [RFC-2822] header or [MIME-IMB] headers of a message in the<br/>            mailbox.|
|PERMANENT_FLAGS|Followed by a parenthesized list of flags, indicates which of<br/>            the known flags the client can change permanently.|
|READ_ONLY|The mailbox is selected read-only.|
|READ_WRITE|The mailbox is selected read-write.|
|TRY_CREATE|An APPEND or COPY attempt is failing <br/>            because the target mailbox does not exist.|
|UID_NEXT|Indicates the next unique identifier value.|
|UID_VALIDITY|Indicates the unique identifier validity value.|
|UNSEEN|Indicates the number of the first message without the \Seen flag set.|
|UNSOLICITED|Untagged status responses.|

### See Also

* namespace [aspose.email.clients.imap](/email/python-net/aspose.email.clients.imap/)
* assembly [Aspose.Email](/email/python-net/)

