---
title: InternalDate
second_title: Aspose.Email für .NET-API-Referenz
description: Das interne Datum und die Uhrzeit der Nachricht auf dem Server. Dies ist nicht das Datum und die Uhrzeit im RFC-2822-Header sondern eher ein Datum und eine Uhrzeit die widerspiegeln wann die Nachricht empfangen wurde. - Im Falle von Nachrichten die über SMTP zugestellt werden SOLLTEN dies das Datum und die Uhrzeit der endgültigen Zustellung der Nachricht sein wie von SMTP definiert.  Bei Nachrichten die mit dem Befehl IMAP4rev1 COPY zugestellt werden SOLLTE dies das interne Datum und die Uhrzeit der Quellnachricht sein in der APPEND-Befehlsbeschreibung. - Alle anderen Fälle sind implementierungsdefiniert.
type: docs
weight: 30
url: /de/net/aspose.email.clients.exchange/exchangemessageinfo/internaldate/
---
## ExchangeMessageInfo.InternalDate property

Das interne Datum und die Uhrzeit der Nachricht auf dem Server. Dies ist nicht das Datum und die Uhrzeit im [RFC-2822]-Header, sondern eher ein Datum und eine Uhrzeit, die widerspiegeln, wann die Nachricht empfangen wurde. - Im Falle von Nachrichten, die über [SMTP] zugestellt werden, SOLLTEN dies das Datum und die Uhrzeit der endgültigen Zustellung der Nachricht sein, wie von [SMTP] definiert. – Bei Nachrichten, die mit dem Befehl IMAP4rev1 COPY zugestellt werden, SOLLTE dies das interne Datum und die Uhrzeit der Quellnachricht sein in der APPEND-Befehlsbeschreibung. - Alle anderen Fälle sind implementierungsdefiniert.

```csharp
public virtual DateTime InternalDate { get; }
```

### Siehe auch

* class [ExchangeMessageInfo](../../exchangemessageinfo)
* namensraum [Aspose.Email.Clients.Exchange](../../exchangemessageinfo)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->