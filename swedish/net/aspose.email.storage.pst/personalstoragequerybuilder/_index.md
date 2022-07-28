---
title: PersonalStorageQueryBuilder
second_title: Aspose.Email för .NET API-referens
description: Representerar byggaren av sökuttryck som används av pst.
type: docs
weight: 20310
url: /sv/net/aspose.email.storage.pst/personalstoragequerybuilder/
---
## PersonalStorageQueryBuilder class

Representerar byggaren av sökuttryck som används av pst.

```csharp
public sealed class PersonalStorageQueryBuilder : MailQueryBuilder
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PersonalStorageQueryBuilder](personalstoragequerybuilder)() | Initierar en ny instans av[`PersonalStorageQueryBuilder`](../personalstoragequerybuilder) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Bcc](../../aspose.email.tools.search/mailquerybuilder/bcc) { get; } | Hämtar fältet som gör det möjligt att hitta meddelanden som innehåller den angivna strängen i kuvertstrukturens BCC-fält. |
| [Body](../../aspose.email.tools.search/mailquerybuilder/body) { get; } | Hämtar fältet som gör det möjligt att hitta meddelanden som innehåller den angivna strängen i meddelandets brödtext. |
| [Cc](../../aspose.email.tools.search/mailquerybuilder/cc) { get; } | Hämtar fältet som gör det möjligt att hitta meddelanden som innehåller den angivna strängen i kuvertstrukturens CC-fält. |
| [ContainerClass](../../aspose.email.storage.pst/personalstoragequerybuilder/containerclass) { get; } | Hämtar mappar med en angiven meddelandeklass. |
| [ContentsCount](../../aspose.email.storage.pst/personalstoragequerybuilder/contentscount) { get; } | Sök i mappar med ett specificerat innehåll. |
| [DefaultEncoding](../../aspose.email.tools.search/mailquerybuilder/defaultencoding) { get; } | Får standardkodning (teckenuppsättning) för query builder |
| [FolderName](../../aspose.email.storage.pst/personalstoragequerybuilder/foldername) { get; } | Sök i mappar med ett angivet visningsnamn. |
| [From](../../aspose.email.tools.search/mailquerybuilder/from) { get; } | Hämtar fältet som gör det möjligt att hitta meddelanden som innehåller den angivna strängen i kuvertstrukturens FRÅN-fält. |
| [Importance](../../aspose.email.storage.pst/personalstoragequerybuilder/importance) { get; } | Sök efter meddelanden med en viss betydelse. |
| [InternalDate](../../aspose.email.tools.search/mailquerybuilder/internaldate) { get; } | Hämtar fältet som gör det möjligt att hitta meddelanden efter internt datum. |
| [MessageClass](../../aspose.email.storage.pst/personalstoragequerybuilder/messageclass) { get; } | Får meddelanden med en angiven meddelandeklass. |
| [MessageId](../../aspose.email.storage.pst/personalstoragequerybuilder/messageid) { get; } | Hämtar fältet som gör det möjligt att hitta meddelanden som innehåller den angivna strängen i kuvertstrukturens MessageId-fält. |
| [MessageSize](../../aspose.email.storage.pst/personalstoragequerybuilder/messagesize) { get; } | Sök efter meddelanden med en angiven storlek. |
| [OnlyFoldersCreatedByUser](../../aspose.email.storage.pst/personalstoragequerybuilder/onlyfolderscreatedbyuser) { get; } | Hämtar mappar som skapats av användaren, dvs exkluderar alla standard IPM-mappar. |
| [SentDate](../../aspose.email.tools.search/mailquerybuilder/sentdate) { get; } | Hämtar fältet som gör det möjligt att hitta meddelanden efter skickat datum. |
| [Subject](../../aspose.email.tools.search/mailquerybuilder/subject) { get; } | Hämtar fältet som gör det möjligt att hitta meddelanden som innehåller den angivna strängen i kuvertstrukturens SUBJECT-fält. |
| [Text](../../aspose.email.tools.search/mailquerybuilder/text) { get; } | Hämtar fältet som gör det möjligt att hitta de meddelanden som innehåller den angivna strängen i rubrikerna (ämne, från, till, cc) och brödtexten i meddelandet. |
| [To](../../aspose.email.tools.search/mailquerybuilder/to) { get; } | Hämtar fältet som gör det möjligt att hitta meddelanden som innehåller den angivna strängen i kuvertstrukturens TO-fält. |
| [UnreadContentsCount](../../aspose.email.storage.pst/personalstoragequerybuilder/unreadcontentscount) { get; } | Sök i mappar med ett specificerat oläst innehåll. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [FindConversationThread](../../aspose.email.storage.pst/personalstoragequerybuilder/findconversationthread)(MessageInfo) | Hittar konversationstråden. |
| [GetQuery](../../aspose.email.tools.search/mailquerybuilder/getquery)() | Hämtar frågan. |
| [HasFlags](../../aspose.email.storage.pst/personalstoragequerybuilder/hasflags)(MapiMessageFlags) | Sök efter meddelanden med de angivna flaggorna. |
| [HasNoFlags](../../aspose.email.storage.pst/personalstoragequerybuilder/hasnoflags)(MapiMessageFlags) | Sök efter meddelanden med de ospecificerade flaggorna. |
| [HasNoSubfolders](../../aspose.email.storage.pst/personalstoragequerybuilder/hasnosubfolders)() | Sök i mappar som inte innehåller undermappar. |
| [HasSubfolders](../../aspose.email.storage.pst/personalstoragequerybuilder/hassubfolders)() | Sök i mappar som innehåller undermappar. |
| [Or](../../aspose.email.tools.search/mailquerybuilder/or)(MailQuery, MailQuery) | Sök efter meddelanden som matchar någon av söknycklarna. Ger disjunktion mellan två uttryck (OR). |

### Se även

* class [MailQueryBuilder](../../aspose.email.tools.search/mailquerybuilder)
* namnutrymme [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
