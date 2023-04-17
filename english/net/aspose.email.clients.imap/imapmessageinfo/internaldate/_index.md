---
title: ImapMessageInfo.InternalDate
second_title: Aspose.Email for .NET API Reference
description: ImapMessageInfo property. The internal date and time of the message on the server. This is not the date and time in the RFC2822 header but rather a date and time which reflects when the message was received.  In the case of messages delivered via SMTP this SHOULD be the date and time of final delivery of the message as defined bySMTP.  In the case of messages delivered by the IMAP4rev1 COPY command this SHOULD be the internal date and time of the source message.  In the case of messages delivered by the IMAP4rev1 APPEND command this SHOULD be the date and time as specified in the APPEND command description.  All other cases are implementation defined
type: docs
weight: 80
url: /net/aspose.email.clients.imap/imapmessageinfo/internaldate/
---
## ImapMessageInfo.InternalDate property

The internal date and time of the message on the server. This is not the date and time in the [RFC-2822] header, but rather a date and time which reflects when the message was received. - In the case of messages delivered via [SMTP], this SHOULD be the date and time of final delivery of the message as defined by[SMTP]. - In the case of messages delivered by the IMAP4rev1 COPY command, this SHOULD be the internal date and time of the source message. - In the case of messages delivered by the IMAP4rev1 APPEND command, this SHOULD be the date and time as specified in the APPEND command description. - All other cases are implementation defined.

```csharp
public DateTime InternalDate { get; }
```

### See Also

* class [ImapMessageInfo](../)
* namespace [Aspose.Email.Clients.Imap](../../imapmessageinfo/)
* assembly [Aspose.Email](../../../)


