---
title: ExchangeQueryBuilder
second_title: Aspose.Email für .NET-API-Referenz
description: Stellt den Generator des Suchausdrucks basierend auf Suchfiltern dar die vom Exchange-Protokoll verwendet werden.
type: docs
weight: 3440
url: /de/net/aspose.email.clients.exchange/exchangequerybuilder/
---
## ExchangeQueryBuilder class

Stellt den Generator des Suchausdrucks basierend auf Suchfiltern dar, die vom Exchange-Protokoll verwendet werden.

```csharp
public sealed class ExchangeQueryBuilder : MailQueryBuilder
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ExchangeQueryBuilder](exchangequerybuilder)() | Initialisiert eine neue Instanz von[`ExchangeQueryBuilder`](../exchangequerybuilder) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Appointment](../../aspose.email.clients.exchange/exchangequerybuilder/appointment) { get; } | Ruft Objekt mit Termineigenschaften ab, um Abfrage zu erstellen |
| [Bcc](../../aspose.email.tools.search/mailquerybuilder/bcc) { get; } | Ruft das Feld ab, mit dem Nachrichten gefunden werden können, die die angegebene Zeichenfolge im BCC-Feld der Umschlagstruktur enthalten. |
| [Body](../../aspose.email.tools.search/mailquerybuilder/body) { get; } | Ruft das Feld ab, mit dem Nachrichten gefunden werden können, die die angegebene Zeichenfolge im Nachrichtentext enthalten. |
| [Cc](../../aspose.email.tools.search/mailquerybuilder/cc) { get; } | Ruft das Feld ab, mit dem Nachrichten gefunden werden können, die die angegebene Zeichenfolge im CC-Feld der Umschlagstruktur enthalten. |
| [Contact](../../aspose.email.clients.exchange/exchangequerybuilder/contact) { get; } | Ruft ein Objekt mit Kontakteigenschaften ab, um eine Abfrage zu erstellen |
| [ContentClass](../../aspose.email.clients.exchange/exchangequerybuilder/contentclass) { get; } | Ruft Elemente mit einer angegebenen Inhaltsklasse ab. |
| [DefaultEncoding](../../aspose.email.tools.search/mailquerybuilder/defaultencoding) { get; } | Ruft die Standardcodierung (Zeichensatz) für den Abfragegenerator ab |
| [ExtendedProperties](../../aspose.email.clients.exchange/exchangequerybuilder/extendedproperties) { get; } | Ruft ein Wörterbuch mit Paaren von Eigenschaftsdeskriptoren und einem Vergleichsfeld ab, um nach erweiterten Eigenschaften zu suchen. |
| [From](../../aspose.email.tools.search/mailquerybuilder/from) { get; } | Ruft das Feld ab, mit dem Nachrichten gefunden werden können, die die angegebene Zeichenfolge im FROM-Feld der Umschlagstruktur enthalten. |
| [InternalDate](../../aspose.email.tools.search/mailquerybuilder/internaldate) { get; } | Ruft das Feld ab, mit dem Nachrichten nach internem Datum gefunden werden können. |
| [ItemSize](../../aspose.email.clients.exchange/exchangequerybuilder/itemsize) { get; } | Ruft das Feld ab, mit dem Elemente mit einer bestimmten Größe gefunden werden können. |
| [MessageId](../../aspose.email.clients.exchange/exchangequerybuilder/messageid) { get; } | Ruft das Feld ab, mit dem Nachrichten gefunden werden können, die die angegebene Zeichenfolge im MessageId-Feld der Envelope-Struktur enthalten. |
| [SentDate](../../aspose.email.tools.search/mailquerybuilder/sentdate) { get; } | Ruft das Feld ab, mit dem Nachrichten nach Sendedatum gesucht werden können. |
| [Subject](../../aspose.email.tools.search/mailquerybuilder/subject) { get; } | Ruft das Feld ab, mit dem Nachrichten gefunden werden können, die die angegebene Zeichenfolge im Feld SUBJECT der Umschlagstruktur enthalten. |
| [TaskStatus](../../aspose.email.clients.exchange/exchangequerybuilder/taskstatus) { get; } | Ruft das Feld ab, mit dem Aufgaben gefunden werden können, die den angegebenen Status enthalten. Serverkompatibilität: Exchange 2010 und höher |
| [Text](../../aspose.email.tools.search/mailquerybuilder/text) { get; } | Ruft das Feld ab, mit dem die Nachrichten gefunden werden können, die die angegebene Zeichenfolge in den Kopfzeilen (Betreff, von, an, cc) und im Nachrichtentext enthalten. |
| [To](../../aspose.email.tools.search/mailquerybuilder/to) { get; } | Ruft das Feld ab, mit dem Nachrichten gefunden werden können, die die angegebene Zeichenfolge im TO-Feld der Envelope-Struktur enthalten. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetQuery](../../aspose.email.tools.search/mailquerybuilder/getquery)() | Ruft die Abfrage ab. |
| [HasFlags](../../aspose.email.clients.exchange/exchangequerybuilder/hasflags)(ExchangeMessageFlag) | Nachrichten mit den angegebenen Flags suchen. |
| [HasNoFlags](../../aspose.email.clients.exchange/exchangequerybuilder/hasnoflags)(ExchangeMessageFlag) | Nachrichten mit den nicht angegebenen Flags suchen. |
| [Or](../../aspose.email.tools.search/mailquerybuilder/or)(MailQuery, MailQuery) | Nachrichten suchen, die mit einem der Suchschlüssel übereinstimmen. Bietet Disjunktion zwischen zwei Ausdrücken (OR). |

### Siehe auch

* class [MailQueryBuilder](../../aspose.email.tools.search/mailquerybuilder)
* namensraum [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
