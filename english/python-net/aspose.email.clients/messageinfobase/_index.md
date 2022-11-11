---
title: MessageInfoBase
second_title: Aspose.Email for Python via .NET API Reference
description: 
type: docs
weight: 110
url: /python-net/aspose.email.clients/messageinfobase/
---

## MessageInfoBase class

The MessageInfo represents the E-Mail message info fetched from the mail server.

The MessageInfoBase type exposes the following members:
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

### See Also

* namespace [aspose.email.clients](/email/python-net/aspose.email.clients/)
* assembly [Aspose.Email](/email/python-net/)

