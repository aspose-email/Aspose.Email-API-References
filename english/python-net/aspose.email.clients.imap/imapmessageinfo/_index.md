---
title: ImapMessageInfo
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 170
url: /email/python-net/aspose.email.clients.imap/imapmessageinfo/
---

## ImapMessageInfo class

Represents a Imap message object.

The ImapMessageInfo type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|headers|Gets the Headers of the E-Mail message.|
|subject|Gets the Subject of the E-Mail message.|
|message_id|Gets the message ID.|
|to|Gets the receiptants of the E-Mail message.|
|cc|Gets CC of the E-Mail message.|
|bcc|Gets blind carbon copy of the E-Mail message.|
|reply_to|Gets the list of addresses that should receive replies to this message.|
|from_address|Gets the list of authors of this message.|
|sender|Gets the sender of this message.|
|size|Gets the size of the E-Mail message.|
|date|The origination date specifies the date and time at which the creator of the message indicated <br/>            that the message was complete and ready to enter the mail delivery system. <br/>            For instance, this might be the time that a user pushes the "send" or "submit" button in an application program.<br/>            In any case, it is specifically not intended to convey the time that the message is actually transported,<br/>            but rather the time at which the human or other creator of the message has put the message into its final form, <br/>            ready for transport.<br/>            (For example, a portable computer user who is not connected to a network might queue a message for delivery.<br/>            The origination date is intended to contain the date and time that the user queued the message, <br/>            not the time when the user connected to the network to send the message.)|
|list_unsubscribe|The List-Unsubscribe field describes the command (preferably using mail) to directly unsubscribe the user(removing them from the list).<br/>            For more details please see https://tools.ietf.org/html/rfc2369|
|properties|Gets a mapi properties.|
|parent_folder|Gets parent folder for message|
|internal_date|The internal date and time of the message on the server. <br/>            This is not the date and time in the [RFC-2822] header, but rather a date and time which reflects when the message was received.  <br/>            - In the case of messages delivered via [SMTP], this SHOULD be the date and time of final delivery of the message as defined by[SMTP].  <br/>            - In the case of messages delivered by the IMAP4rev1 COPY command, this SHOULD be the internal date and time of the source message.<br/>            - In the case of messages delivered by the IMAP4rev1 APPEND command, this SHOULD be the date and time as specified in the APPEND command description.<br/>            - All other cases are implementation defined.|
|modification_sequence|Gets the modification sequence of this message. <br/>            See more: https://tools.ietf.org/html/rfc7162|
|flags|Gets the message flags.|
|answered|Gets a value indicating whether <br/>            Flags property contains the Answered flag.|
|deleted|Gets a value indicating whether <br/>            Flags property contains the Deleted flag.|
|draft|Gets a value indicating whether <br/>            Flags property contains the Draft flag.|
|flagged|Gets a value indicating whether<br/>            Flags property contains the Flagged flag.|
|recent|Gets a value indicating whether<br/>            Flags property contains the Recent flag.|
|is_read|Gets a value indicating whether<br/>            Flags property contains the Read flag.|
|conversation_id|Gets a value indicating conversation id.|
|sequence_number|Gets the message sequence number.|
|unique_id|Gets the message unique ID.|
## Methods
| Name | Description |
| :- | :- |
|contains_keyword(flag)|  |

### See Also

* namespace [aspose.email.clients.imap](/email/python-net/aspose.email.clients.imap/)
* assembly [Aspose.Email](/slides/python-net/)

