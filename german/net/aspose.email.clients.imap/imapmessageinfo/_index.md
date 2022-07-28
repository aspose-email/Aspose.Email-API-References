---
title: ImapMessageInfo
second_title: Aspose.Email für .NET-API-Referenz
description: Repräsentiert ein Imap-Nachrichtenobjekt.
type: docs
weight: 16370
url: /de/net/aspose.email.clients.imap/imapmessageinfo/
---
## ImapMessageInfo class

Repräsentiert ein Imap-Nachrichtenobjekt.

```csharp
public sealed class ImapMessageInfo : MessageInfoBase
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Answered](../../aspose.email.clients.imap/imapmessageinfo/answered) { get; } | Ruft einen Wert ab, der angibt, ob die Flags-Eigenschaft das Beantwortet-Flag enthält. |
| virtual [Bcc](../../aspose.email.clients/messageinfobase/bcc) { get; } | Ruft eine Blindkopie der E-Mail-Nachricht ab. |
| virtual [CC](../../aspose.email.clients/messageinfobase/cc) { get; } | Ruft CC der E-Mail-Nachricht ab. |
| [ConversationId](../../aspose.email.clients.imap/imapmessageinfo/conversationid) { get; } | Ruft einen Wert ab, der die Konversations-ID angibt. |
| virtual [Date](../../aspose.email.clients/messageinfobase/date) { get; } | Das Ursprungsdatum gibt das Datum und die Uhrzeit an, zu der der Ersteller der Nachricht anzeigte, dass die Nachricht vollständig und bereit war, in das Postzustellungssystem einzugeben. Dies kann beispielsweise der Zeitpunkt sein, zu dem ein Benutzer in einem Anwendungsprogramm auf die Schaltfläche „Senden“ oder „Senden“ drückt. In jedem Fall soll ausdrücklich nicht der Zeitpunkt übermittelt werden, zu dem die Nachricht tatsächlich transportiert wird, aber vielmehr der Zeitpunkt, zu dem der Mensch oder andere Ersteller der Nachricht die Nachricht in ihre endgültige Form gebracht hat, bereit für den Transport. (Zum Beispiel könnte ein Benutzer eines tragbaren Computers, der nicht mit einem Netzwerk verbunden ist, eine Nachricht für die Zustellung in die Warteschlange stellen. Das Ursprungsdatum soll das Datum und die Uhrzeit enthalten, zu der der Benutzer die Nachricht in die Warteschlange gestellt hat, nicht die Zeit, zu der sich der Benutzer mit dem Netzwerk verbunden hat, um die Nachricht zu senden.) |
| [Deleted](../../aspose.email.clients.imap/imapmessageinfo/deleted) { get; } | Ruft einen Wert ab, der angibt, ob die Flags-Eigenschaft das Gelöscht-Flag enthält. |
| [Draft](../../aspose.email.clients.imap/imapmessageinfo/draft) { get; } | Ruft einen Wert ab, der angibt, ob die Eigenschaft Flags das Entwurfsflag enthält. |
| [ExtraParameters](../../aspose.email.clients.imap/imapmessageinfo/extraparameters) { get; } | Ruft zusätzliche Parameter einer Nachricht ab. |
| [Flagged](../../aspose.email.clients.imap/imapmessageinfo/flagged) { get; } | Ruft einen Wert ab, der angibt, ob die Flags-Eigenschaft das Flagged-Flag enthält. |
| [Flags](../../aspose.email.clients.imap/imapmessageinfo/flags) { get; } | Ruft die Nachrichtenflags ab. |
| [From](../../aspose.email.clients/messageinfobase/from) { get; } | Ruft die Liste der Autoren dieser Nachricht ab. |
| [Headers](../../aspose.email.clients/messageinfobase/headers) { get; } | Ruft die Header der E-Mail-Nachricht ab. |
| [InternalDate](../../aspose.email.clients.imap/imapmessageinfo/internaldate) { get; } | Das interne Datum und die Uhrzeit der Nachricht auf dem Server. Dies ist nicht das Datum und die Uhrzeit im [RFC-2822]-Header, sondern eher ein Datum und eine Uhrzeit, die widerspiegeln, wann die Nachricht empfangen wurde. - Im Falle von Nachrichten, die über [SMTP] zugestellt werden, SOLLTEN dies das Datum und die Uhrzeit der endgültigen Zustellung der Nachricht sein, wie von [SMTP] definiert. – Bei Nachrichten, die mit dem Befehl IMAP4rev1 COPY zugestellt werden, SOLLTE dies das interne Datum und die Uhrzeit der Quellnachricht sein in der APPEND-Befehlsbeschreibung. - Alle anderen Fälle sind implementierungsdefiniert. |
| [IsRead](../../aspose.email.clients.imap/imapmessageinfo/isread) { get; } | Ruft einen Wert ab, der angibt, ob die Flags-Eigenschaft das Lese-Flag enthält. |
| [ListUnsubscribe](../../aspose.email.clients/messageinfobase/listunsubscribe) { get; } | Das List-Unsubscribe-Feld beschreibt den Befehl (vorzugsweise per E-Mail), um den Benutzer direkt abzumelden (um ihn aus der Liste zu entfernen). Weitere Einzelheiten finden Sie unter https://tools.ietf.org/html/rfc2369 |
| [MessageId](../../aspose.email.clients/messageinfobase/messageid) { get; } | Ruft die Nachrichten-ID ab. |
| [ModificationSequence](../../aspose.email.clients.imap/imapmessageinfo/modificationsequence) { get; } | Ruft die Änderungssequenz dieser Nachricht ab. Weitere Informationen: https://tools.ietf.org/html/rfc7162 |
| [ParentFolder](../../aspose.email.clients.imap/imapmessageinfo/parentfolder) { get; } | Ruft den übergeordneten Ordner für die Nachricht ab |
| virtual [Properties](../../aspose.email.clients/messageinfobase/properties) { get; } | Ruft Mapi-Eigenschaften ab. |
| [Recent](../../aspose.email.clients.imap/imapmessageinfo/recent) { get; } | Ruft einen Wert ab, der angibt, ob die Flags-Eigenschaft das Recent-Flag enthält. |
| [ReplyTo](../../aspose.email.clients/messageinfobase/replyto) { get; } | Ruft die Liste der Adressen ab, die Antworten auf diese Nachricht erhalten sollen. |
| [Sender](../../aspose.email.clients/messageinfobase/sender) { get; } | Ruft den Absender dieser Nachricht ab. |
| [SequenceNumber](../../aspose.email.clients.imap/imapmessageinfo/sequencenumber) { get; } | Ruft die Nachrichtenfolgenummer ab. |
| [Size](../../aspose.email.clients/messageinfobase/size) { get; } | Ermittelt die Größe der E-Mail-Nachricht. |
| [Subject](../../aspose.email.clients/messageinfobase/subject) { get; } | Ruft den Betreff der E-Mail-Nachricht ab. |
| virtual [To](../../aspose.email.clients/messageinfobase/to) { get; } | Ruft die Empfangsbestätigungen der E-Mail-Nachricht ab. |
| [UniqueId](../../aspose.email.clients.imap/imapmessageinfo/uniqueid) { get; } | Ruft die eindeutige ID der Nachricht ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ContainsKeyword](../../aspose.email.clients.imap/imapmessageinfo/containskeyword)(string) | Ruft einen Wert ab, der angibt, ob die Eigenschaft Flags das Keyword-Flag enthält. |
| virtual [Dispose](../../aspose.email.clients/messageinfobase/dispose)() | Führt Aufgaben im Zusammenhang mit dem Freigeben, Freigeben oder Zurücksetzen nicht verwalteter Ressourcen aus. |
| override [ToString](../../aspose.email.clients.imap/imapmessageinfo/tostring)() | Gibt eine Zeichenfolge zurück, die das aktuelle Objekt darstellt. |

### Siehe auch

* class [MessageInfoBase](../../aspose.email.clients/messageinfobase)
* namensraum [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
