---
title: ExchangeMessageInfo
second_title: Aspose.Email für .NET-API-Referenz
description: Die ExchangeMessageInfo stellt die E-Mail-Nachrichteninformationen dar die aus dem Exchange Store abgerufen wurden.
type: docs
weight: 3400
url: /de/net/aspose.email.clients.exchange/exchangemessageinfo/
---
## ExchangeMessageInfo class

Die ExchangeMessageInfo stellt die E-Mail-Nachrichteninformationen dar, die aus dem Exchange Store abgerufen wurden.

```csharp
public abstract class ExchangeMessageInfo : MessageInfoBase
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [Attachments](../../aspose.email.clients.exchange/exchangemessageinfo/attachments) { get; } | Ruft Nachrichtenanhänge ab |
| virtual [Bcc](../../aspose.email.clients/messageinfobase/bcc) { get; } | Ruft eine Blindkopie der E-Mail-Nachricht ab. |
| virtual [CC](../../aspose.email.clients/messageinfobase/cc) { get; } | Ruft CC der E-Mail-Nachricht ab. |
| virtual [Date](../../aspose.email.clients/messageinfobase/date) { get; } | Das Ursprungsdatum gibt das Datum und die Uhrzeit an, zu der der Ersteller der Nachricht anzeigte, dass die Nachricht vollständig und bereit war, in das Postzustellungssystem einzugeben. Dies kann beispielsweise der Zeitpunkt sein, zu dem ein Benutzer in einem Anwendungsprogramm auf die Schaltfläche „Senden“ oder „Senden“ drückt. In jedem Fall soll ausdrücklich nicht der Zeitpunkt übermittelt werden, zu dem die Nachricht tatsächlich transportiert wird, aber vielmehr der Zeitpunkt, zu dem der Mensch oder andere Ersteller der Nachricht die Nachricht in ihre endgültige Form gebracht hat, bereit für den Transport. (Zum Beispiel könnte ein Benutzer eines tragbaren Computers, der nicht mit einem Netzwerk verbunden ist, eine Nachricht für die Zustellung in die Warteschlange stellen. Das Ursprungsdatum soll das Datum und die Uhrzeit enthalten, zu der der Benutzer die Nachricht in die Warteschlange gestellt hat, nicht die Zeit, zu der sich der Benutzer mit dem Netzwerk verbunden hat, um die Nachricht zu senden.) |
| [From](../../aspose.email.clients/messageinfobase/from) { get; } | Ruft die Liste der Autoren dieser Nachricht ab. |
| virtual [HasAttachments](../../aspose.email.clients.exchange/exchangemessageinfo/hasattachments) { get; } | Ruft einen Wert ab, der angibt, ob die Nachricht mindestens einen Anhang enthält. |
| [Headers](../../aspose.email.clients/messageinfobase/headers) { get; } | Ruft die Header der E-Mail-Nachricht ab. |
| virtual [InternalDate](../../aspose.email.clients.exchange/exchangemessageinfo/internaldate) { get; } | Das interne Datum und die Uhrzeit der Nachricht auf dem Server. Dies ist nicht das Datum und die Uhrzeit im [RFC-2822]-Header, sondern eher ein Datum und eine Uhrzeit, die widerspiegeln, wann die Nachricht empfangen wurde. - Im Falle von Nachrichten, die über [SMTP] zugestellt werden, SOLLTEN dies das Datum und die Uhrzeit der endgültigen Zustellung der Nachricht sein, wie von [SMTP] definiert. – Bei Nachrichten, die mit dem Befehl IMAP4rev1 COPY zugestellt werden, SOLLTE dies das interne Datum und die Uhrzeit der Quellnachricht sein in der APPEND-Befehlsbeschreibung. - Alle anderen Fälle sind implementierungsdefiniert. |
| virtual [IsRead](../../aspose.email.clients.exchange/exchangemessageinfo/isread) { get; } | Ruft einen Wert ab, der angibt, ob die Nachricht gelesen wurde |
| [ListUnsubscribe](../../aspose.email.clients/messageinfobase/listunsubscribe) { get; } | Das List-Unsubscribe-Feld beschreibt den Befehl (vorzugsweise per E-Mail), um den Benutzer direkt abzumelden (um ihn aus der Liste zu entfernen). Weitere Einzelheiten finden Sie unter https://tools.ietf.org/html/rfc2369 |
| virtual [MessageClass](../../aspose.email.clients.exchange/exchangemessageinfo/messageclass) { get; } | Ruft eine Zeichenfolge ab, die die Klasse für die Nachricht darstellt. Die Eigenschaft entspricht der MAPI-Eigenschaft PidTagMessageClass. |
| [MessageId](../../aspose.email.clients/messageinfobase/messageid) { get; } | Ruft die Nachrichten-ID ab. |
| virtual [MessageInfoType](../../aspose.email.clients.exchange/exchangemessageinfo/messageinfotype) { get; } | Ruft den Typ der Nachricht ab |
| virtual [Properties](../../aspose.email.clients/messageinfobase/properties) { get; } | Ruft Mapi-Eigenschaften ab. |
| [ReplyTo](../../aspose.email.clients/messageinfobase/replyto) { get; } | Ruft die Liste der Adressen ab, die Antworten auf diese Nachricht erhalten sollen. |
| [Sender](../../aspose.email.clients/messageinfobase/sender) { get; } | Ruft den Absender dieser Nachricht ab. |
| [Size](../../aspose.email.clients/messageinfobase/size) { get; } | Ermittelt die Größe der E-Mail-Nachricht. |
| [Subject](../../aspose.email.clients/messageinfobase/subject) { get; } | Ruft den Betreff der E-Mail-Nachricht ab. |
| virtual [To](../../aspose.email.clients/messageinfobase/to) { get; } | Ruft die Empfangsbestätigungen der E-Mail-Nachricht ab. |
| virtual [UniqueUri](../../aspose.email.clients.exchange/exchangemessageinfo/uniqueuri) { get; } | Ruft den eindeutigen URI der Nachricht ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Dispose](../../aspose.email.clients/messageinfobase/dispose)() | Führt Aufgaben im Zusammenhang mit dem Freigeben, Freigeben oder Zurücksetzen nicht verwalteter Ressourcen aus. |
| override [ToString](../../aspose.email.clients/messageinfobase/tostring)() | Eine Zeichenfolge, die das aktuelle Objekt darstellt. |

### Siehe auch

* class [MessageInfoBase](../../aspose.email.clients/messageinfobase)
* namensraum [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
