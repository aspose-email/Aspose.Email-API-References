---
title: Class ExchangeMessageInfo
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Exchange.ExchangeMessageInfo class. The ExchangeMessageInfo represents the EMail message info fetched from the Exchange Store
type: docs
weight: 3410
url: /net/aspose.email.clients.exchange/exchangemessageinfo/
---
## ExchangeMessageInfo class

The ExchangeMessageInfo represents the E-Mail message info fetched from the Exchange Store.

```csharp
public abstract class ExchangeMessageInfo : MessageInfoBase
```

## Properties

| Name | Description |
| --- | --- |
| virtual [Attachments](../../aspose.email.clients.exchange/exchangemessageinfo/attachments/) { get; } | Gets message attachments |
| virtual [Bcc](../../aspose.email.clients/messageinfobase/bcc/) { get; } | Gets blind carbon copy of the E-Mail message. |
| virtual [CC](../../aspose.email.clients/messageinfobase/cc/) { get; } | Gets CC of the E-Mail message. |
| virtual [Date](../../aspose.email.clients/messageinfobase/date/) { get; } | The origination date specifies the date and time at which the creator of the message indicated that the message was complete and ready to enter the mail delivery system. For instance, this might be the time that a user pushes the "send" or "submit" button in an application program. In any case, it is specifically not intended to convey the time that the message is actually transported, but rather the time at which the human or other creator of the message has put the message into its final form, ready for transport. (For example, a portable computer user who is not connected to a network might queue a message for delivery. The origination date is intended to contain the date and time that the user queued the message, not the time when the user connected to the network to send the message.) |
| [From](../../aspose.email.clients/messageinfobase/from/) { get; } | Gets the list of authors of this message. |
| virtual [HasAttachments](../../aspose.email.clients.exchange/exchangemessageinfo/hasattachments/) { get; } | Gets a value indicating whether the message contains at least one attachment. |
| [Headers](../../aspose.email.clients/messageinfobase/headers/) { get; } | Gets the Headers of the E-Mail message. |
| virtual [InternalDate](../../aspose.email.clients.exchange/exchangemessageinfo/internaldate/) { get; } | The internal date and time of the message on the server. This is not the date and time in the [RFC-2822] header, but rather a date and time which reflects when the message was received. - In the case of messages delivered via [SMTP], this SHOULD be the date and time of final delivery of the message as defined by[SMTP]. - In the case of messages delivered by the IMAP4rev1 COPY command, this SHOULD be the internal date and time of the source message. - In the case of messages delivered by the IMAP4rev1 APPEND command, this SHOULD be the date and time as specified in the APPEND command description. - All other cases are implementation defined. |
| virtual [IsRead](../../aspose.email.clients.exchange/exchangemessageinfo/isread/) { get; } | Gets a value indicating whether the message has been read |
| [ListUnsubscribe](../../aspose.email.clients/messageinfobase/listunsubscribe/) { get; } | The List-Unsubscribe field describes the command (preferably using mail) to directly unsubscribe the user(removing them from the list). For more details please see https://tools.ietf.org/html/rfc2369 |
| virtual [MessageClass](../../aspose.email.clients.exchange/exchangemessageinfo/messageclass/) { get; } | Gets a string representing the class for the message. The property corresponds to the PidTagMessageClass MAPI property. |
| [MessageId](../../aspose.email.clients/messageinfobase/messageid/) { get; } | Gets the message ID. |
| virtual [MessageInfoType](../../aspose.email.clients.exchange/exchangemessageinfo/messageinfotype/) { get; } | Gets the type of the message |
| virtual [Properties](../../aspose.email.clients/messageinfobase/properties/) { get; } | Gets a mapi properties. |
| [ReplyTo](../../aspose.email.clients/messageinfobase/replyto/) { get; } | Gets the list of addresses that should receive replies to this message. |
| [Sender](../../aspose.email.clients/messageinfobase/sender/) { get; } | Gets the sender of this message. |
| [Size](../../aspose.email.clients/messageinfobase/size/) { get; } | Gets the size of the E-Mail message. |
| [Subject](../../aspose.email.clients/messageinfobase/subject/) { get; } | Gets the Subject of the E-Mail message. |
| virtual [To](../../aspose.email.clients/messageinfobase/to/) { get; } | Gets the receiptants of the E-Mail message. |
| virtual [UniqueUri](../../aspose.email.clients.exchange/exchangemessageinfo/uniqueuri/) { get; } | Gets the unique URI of message. |

## Methods

| Name | Description |
| --- | --- |
| virtual [Dispose](../../aspose.email.clients/messageinfobase/dispose/)() | Performs tasks associated with freeing, releasing, or resetting unmanaged resources. |
| override [ToString](../../aspose.email.clients/messageinfobase/tostring/)() | A string that represents the current object. |

### See Also

* class [MessageInfoBase](../../aspose.email.clients/messageinfobase/)
* namespace [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange/)
* assembly [Aspose.Email](../../)


