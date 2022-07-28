---
title: PersonalStorageQueryBuilder
second_title: Aspose.Email für .NET-API-Referenz
description: Stellt den Builder des Suchausdrucks dar der von pst verwendet wird.
type: docs
weight: 20310
url: /de/net/aspose.email.storage.pst/personalstoragequerybuilder/
---
## PersonalStorageQueryBuilder class

Stellt den Builder des Suchausdrucks dar, der von pst verwendet wird.

```csharp
public sealed class PersonalStorageQueryBuilder : MailQueryBuilder
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PersonalStorageQueryBuilder](personalstoragequerybuilder)() | Initialisiert eine neue Instanz von[`PersonalStorageQueryBuilder`](../personalstoragequerybuilder) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Bcc](../../aspose.email.tools.search/mailquerybuilder/bcc) { get; } | Ruft das Feld ab, mit dem Nachrichten gefunden werden können, die die angegebene Zeichenfolge im BCC-Feld der Umschlagstruktur enthalten. |
| [Body](../../aspose.email.tools.search/mailquerybuilder/body) { get; } | Ruft das Feld ab, mit dem Nachrichten gefunden werden können, die die angegebene Zeichenfolge im Nachrichtentext enthalten. |
| [Cc](../../aspose.email.tools.search/mailquerybuilder/cc) { get; } | Ruft das Feld ab, mit dem Nachrichten gefunden werden können, die die angegebene Zeichenfolge im CC-Feld der Umschlagstruktur enthalten. |
| [ContainerClass](../../aspose.email.storage.pst/personalstoragequerybuilder/containerclass) { get; } | Ruft Ordner mit einer angegebenen Nachrichtenklasse ab. |
| [ContentsCount](../../aspose.email.storage.pst/personalstoragequerybuilder/contentscount) { get; } | Durchsucht Ordner mit einer bestimmten Inhaltsanzahl. |
| [DefaultEncoding](../../aspose.email.tools.search/mailquerybuilder/defaultencoding) { get; } | Ruft die Standardcodierung (Zeichensatz) für den Abfragegenerator ab |
| [FolderName](../../aspose.email.storage.pst/personalstoragequerybuilder/foldername) { get; } | Durchsucht Ordner mit einem bestimmten Anzeigenamen. |
| [From](../../aspose.email.tools.search/mailquerybuilder/from) { get; } | Ruft das Feld ab, mit dem Nachrichten gefunden werden können, die die angegebene Zeichenfolge im FROM-Feld der Umschlagstruktur enthalten. |
| [Importance](../../aspose.email.storage.pst/personalstoragequerybuilder/importance) { get; } | Nachrichten mit einer bestimmten Wichtigkeit suchen. |
| [InternalDate](../../aspose.email.tools.search/mailquerybuilder/internaldate) { get; } | Ruft das Feld ab, mit dem Nachrichten nach internem Datum gefunden werden können. |
| [MessageClass](../../aspose.email.storage.pst/personalstoragequerybuilder/messageclass) { get; } | Ruft Nachrichten mit einer angegebenen Nachrichtenklasse ab. |
| [MessageId](../../aspose.email.storage.pst/personalstoragequerybuilder/messageid) { get; } | Ruft das Feld ab, mit dem Nachrichten gefunden werden können, die die angegebene Zeichenfolge im MessageId-Feld der Envelope-Struktur enthalten. |
| [MessageSize](../../aspose.email.storage.pst/personalstoragequerybuilder/messagesize) { get; } | Nachrichten mit einer bestimmten Größe suchen. |
| [OnlyFoldersCreatedByUser](../../aspose.email.storage.pst/personalstoragequerybuilder/onlyfolderscreatedbyuser) { get; } | Ruft vom Benutzer erstellte Ordner ab, dh schließt alle Standard-IPM-Ordner aus. |
| [SentDate](../../aspose.email.tools.search/mailquerybuilder/sentdate) { get; } | Ruft das Feld ab, mit dem Nachrichten nach Sendedatum gesucht werden können. |
| [Subject](../../aspose.email.tools.search/mailquerybuilder/subject) { get; } | Ruft das Feld ab, mit dem Nachrichten gefunden werden können, die die angegebene Zeichenfolge im Feld SUBJECT der Umschlagstruktur enthalten. |
| [Text](../../aspose.email.tools.search/mailquerybuilder/text) { get; } | Ruft das Feld ab, mit dem die Nachrichten gefunden werden können, die die angegebene Zeichenfolge in den Kopfzeilen (Betreff, von, an, cc) und im Nachrichtentext enthalten. |
| [To](../../aspose.email.tools.search/mailquerybuilder/to) { get; } | Ruft das Feld ab, mit dem Nachrichten gefunden werden können, die die angegebene Zeichenfolge im TO-Feld der Envelope-Struktur enthalten. |
| [UnreadContentsCount](../../aspose.email.storage.pst/personalstoragequerybuilder/unreadcontentscount) { get; } | Durchsucht Ordner mit einer bestimmten Anzahl ungelesener Inhalte. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindConversationThread](../../aspose.email.storage.pst/personalstoragequerybuilder/findconversationthread)(MessageInfo) | Findet den Konversationsthread. |
| [GetQuery](../../aspose.email.tools.search/mailquerybuilder/getquery)() | Ruft die Abfrage ab. |
| [HasFlags](../../aspose.email.storage.pst/personalstoragequerybuilder/hasflags)(MapiMessageFlags) | Nachrichten mit den angegebenen Flags suchen. |
| [HasNoFlags](../../aspose.email.storage.pst/personalstoragequerybuilder/hasnoflags)(MapiMessageFlags) | Nachrichten mit den nicht angegebenen Flags suchen. |
| [HasNoSubfolders](../../aspose.email.storage.pst/personalstoragequerybuilder/hasnosubfolders)() | Durchsucht Ordner, die keine Unterordner enthalten. |
| [HasSubfolders](../../aspose.email.storage.pst/personalstoragequerybuilder/hassubfolders)() | Ordner durchsuchen, die Unterordner enthalten. |
| [Or](../../aspose.email.tools.search/mailquerybuilder/or)(MailQuery, MailQuery) | Nachrichten suchen, die mit einem der Suchschlüssel übereinstimmen. Bietet Disjunktion zwischen zwei Ausdrücken (OR). |

### Siehe auch

* class [MailQueryBuilder](../../aspose.email.tools.search/mailquerybuilder)
* namensraum [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
