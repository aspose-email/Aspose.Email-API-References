---
title: Class ImapMessageInfo
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Imap.ImapMessageInfo class. Represents a Imap message object
type: docs
weight: 16530
url: /net/aspose.email.clients.imap/imapmessageinfo/
---
## ImapMessageInfo class

Represents a Imap message object.

```csharp
public sealed class ImapMessageInfo : MessageInfoBase
```

## Properties

| Name | Description |
| --- | --- |
| [Answered](../../aspose.email.clients.imap/imapmessageinfo/answered/) { get; } | Gets a value indicating whether Flags property contains the Answered flag. |
| virtual [Bcc](../../aspose.email.clients/messageinfobase/bcc/) { get; } | Gets blind carbon copy of the E-Mail message. |
| virtual [CC](../../aspose.email.clients/messageinfobase/cc/) { get; } | Gets CC of the E-Mail message. |
| [ConversationId](../../aspose.email.clients.imap/imapmessageinfo/conversationid/) { get; } | Gets a value indicating conversation id. |
| virtual [Date](../../aspose.email.clients/messageinfobase/date/) { get; } | The origination date specifies the date and time at which the creator of the message indicated that the message was complete and ready to enter the mail delivery system. For instance, this might be the time that a user pushes the "send" or "submit" button in an application program. In any case, it is specifically not intended to convey the time that the message is actually transported, but rather the time at which the human or other creator of the message has put the message into its final form, ready for transport. (For example, a portable computer user who is not connected to a network might queue a message for delivery. The origination date is intended to contain the date and time that the user queued the message, not the time when the user connected to the network to send the message.) |
| [Deleted](../../aspose.email.clients.imap/imapmessageinfo/deleted/) { get; } | Gets a value indicating whether Flags property contains the Deleted flag. |
| [Draft](../../aspose.email.clients.imap/imapmessageinfo/draft/) { get; } | Gets a value indicating whether Flags property contains the Draft flag. |
| [ExtraParameters](../../aspose.email.clients.imap/imapmessageinfo/extraparameters/) { get; } | Gets extra parameters of a message. |
| [Flagged](../../aspose.email.clients.imap/imapmessageinfo/flagged/) { get; } | Gets a value indicating whether Flags property contains the Flagged flag. |
| [Flags](../../aspose.email.clients.imap/imapmessageinfo/flags/) { get; } | Gets the message flags. |
| [From](../../aspose.email.clients/messageinfobase/from/) { get; } | Gets the list of authors of this message. |
| [Headers](../../aspose.email.clients/messageinfobase/headers/) { get; } | Gets the Headers of the E-Mail message. |
| [InternalDate](../../aspose.email.clients.imap/imapmessageinfo/internaldate/) { get; } | The internal date and time of the message on the server. This is not the date and time in the [RFC-2822] header, but rather a date and time which reflects when the message was received. - In the case of messages delivered via [SMTP], this SHOULD be the date and time of final delivery of the message as defined by[SMTP]. - In the case of messages delivered by the IMAP4rev1 COPY command, this SHOULD be the internal date and time of the source message. - In the case of messages delivered by the IMAP4rev1 APPEND command, this SHOULD be the date and time as specified in the APPEND command description. - All other cases are implementation defined. |
| [IsRead](../../aspose.email.clients.imap/imapmessageinfo/isread/) { get; } | Gets a value indicating whether Flags property contains the Read flag. |
| [ListUnsubscribe](../../aspose.email.clients/messageinfobase/listunsubscribe/) { get; } | The List-Unsubscribe field describes the command (preferably using mail) to directly unsubscribe the user(removing them from the list). For more details please see https://tools.ietf.org/html/rfc2369 |
| [MessageId](../../aspose.email.clients/messageinfobase/messageid/) { get; } | Gets the message ID. |
| [ModificationSequence](../../aspose.email.clients.imap/imapmessageinfo/modificationsequence/) { get; } | Gets the modification sequence of this message. See more: https://tools.ietf.org/html/rfc7162 |
| [ParentFolder](../../aspose.email.clients.imap/imapmessageinfo/parentfolder/) { get; } | Gets parent folder for message |
| virtual [Properties](../../aspose.email.clients/messageinfobase/properties/) { get; } | Gets a mapi properties. |
| [Recent](../../aspose.email.clients.imap/imapmessageinfo/recent/) { get; } | Gets a value indicating whether Flags property contains the Recent flag. |
| [ReplyTo](../../aspose.email.clients/messageinfobase/replyto/) { get; } | Gets the list of addresses that should receive replies to this message. |
| [Sender](../../aspose.email.clients/messageinfobase/sender/) { get; } | Gets the sender of this message. |
| [SequenceNumber](../../aspose.email.clients.imap/imapmessageinfo/sequencenumber/) { get; } | Gets the message sequence number. |
| [Size](../../aspose.email.clients/messageinfobase/size/) { get; } | Gets the size of the E-Mail message. |
| [Subject](../../aspose.email.clients/messageinfobase/subject/) { get; } | Gets the Subject of the E-Mail message. |
| virtual [To](../../aspose.email.clients/messageinfobase/to/) { get; } | Gets the receiptants of the E-Mail message. |
| [UniqueId](../../aspose.email.clients.imap/imapmessageinfo/uniqueid/) { get; } | Gets the message unique ID. |

## Methods

| Name | Description |
| --- | --- |
| [ContainsKeyword](../../aspose.email.clients.imap/imapmessageinfo/containskeyword/)(string) | Gets a value indicating whether Flags property contains the Keyword flag. |
| virtual [Dispose](../../aspose.email.clients/messageinfobase/dispose/)() | Performs tasks associated with freeing, releasing, or resetting unmanaged resources. |
| override [ToString](../../aspose.email.clients.imap/imapmessageinfo/tostring/)() | Returns a string that represents the current object. |

### See Also

* class [MessageInfoBase](../../aspose.email.clients/messageinfobase/)
* namespace [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap/)
* assembly [Aspose.Email](../../)


