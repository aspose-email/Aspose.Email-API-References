---
title: ImapMessageInfo
second_title: Aspose.Email för .NET API-referens
description: Representerar ett Imap-meddelandeobjekt.
type: docs
weight: 16370
url: /sv/net/aspose.email.clients.imap/imapmessageinfo/
---
## ImapMessageInfo class

Representerar ett Imap-meddelandeobjekt.

```csharp
public sealed class ImapMessageInfo : MessageInfoBase
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Answered](../../aspose.email.clients.imap/imapmessageinfo/answered) { get; } | Får ett värde som indikerar om egenskapen Flags innehåller flaggan Besvarade. |
| virtual [Bcc](../../aspose.email.clients/messageinfobase/bcc) { get; } | Får en blind kopia av e-postmeddelandet. |
| virtual [CC](../../aspose.email.clients/messageinfobase/cc) { get; } | Får CC på e-postmeddelandet. |
| [ConversationId](../../aspose.email.clients.imap/imapmessageinfo/conversationid) { get; } | Får ett värde som indikerar konversations-id. |
| virtual [Date](../../aspose.email.clients/messageinfobase/date) { get; } | Ursprungsdatumet anger datumet och tiden då skaparen av meddelandet angav att meddelandet var komplett och redo att gå in i postleveranssystemet. Detta kan till exempel vara den tid som en användare trycker på knappen "skicka" eller "skicka" i ett applikationsprogram. I vilket fall som helst är det specifikt inte avsett att förmedla tiden då meddelandet faktiskt transporteras, men snarare tidpunkten då människan eller annan skapare av meddelandet har satt meddelandet i sin slutliga form, redo för transport. (Till exempel kan en bärbar datoranvändare som inte är ansluten till ett nätverk ställa ett meddelande i kö för leverans. Ursprungsdatumet är avsett att innehålla datumet och tiden då användaren köade meddelandet, inte tiden då användaren anslöt sig till nätverket för att skicka meddelandet.) |
| [Deleted](../../aspose.email.clients.imap/imapmessageinfo/deleted) { get; } | Får ett värde som indikerar om egenskapen Flags innehåller den borttagna flaggan. |
| [Draft](../../aspose.email.clients.imap/imapmessageinfo/draft) { get; } | Får ett värde som indikerar om egenskapen Flags innehåller flaggan Draft. |
| [ExtraParameters](../../aspose.email.clients.imap/imapmessageinfo/extraparameters) { get; } | Får extra parametrar för ett meddelande. |
| [Flagged](../../aspose.email.clients.imap/imapmessageinfo/flagged) { get; } | Får ett värde som indikerar om Flags-egenskapen innehåller den Flaggade flaggan. |
| [Flags](../../aspose.email.clients.imap/imapmessageinfo/flags) { get; } | Hämtar meddelandeflaggor. |
| [From](../../aspose.email.clients/messageinfobase/from) { get; } | Hämtar listan över författare till detta meddelande. |
| [Headers](../../aspose.email.clients/messageinfobase/headers) { get; } | Hämtar rubrikerna för e-postmeddelandet. |
| [InternalDate](../../aspose.email.clients.imap/imapmessageinfo/internaldate) { get; } | Det interna datumet och tiden för meddelandet på servern. Detta är inte datum och tid i [RFC-2822]-huvudet, utan snarare ett datum och en tid som återspeglar när meddelandet togs emot. - I fallet med meddelanden som levereras via [SMTP], SKA detta vara datumet och tiden för slutleveransen av meddelandet enligt definitionen av [SMTP]. - I fallet med meddelanden som levereras av kommandot IMAP4rev1 COPY, SKA detta vara det interna datumet och klockslaget för källmeddelandet. - I fallet med meddelanden som levereras av kommandot IMAP4rev1 APPEND, SKA detta vara datumet och tiden som specificerats i kommandobeskrivningen APPEND. - Alla andra fall är implementeringsdefinierade. |
| [IsRead](../../aspose.email.clients.imap/imapmessageinfo/isread) { get; } | Får ett värde som indikerar om Flags-egenskapen innehåller Read-flaggan. |
| [ListUnsubscribe](../../aspose.email.clients/messageinfobase/listunsubscribe) { get; } | Fältet List-Unsubscribe beskriver kommandot (helst med e-post) för att direkt avbryta prenumerationen av användaren (ta bort dem från listan). För mer information se https://tools.ietf.org/html/rfc2369 |
| [MessageId](../../aspose.email.clients/messageinfobase/messageid) { get; } | Hämtar meddelande-ID. |
| [ModificationSequence](../../aspose.email.clients.imap/imapmessageinfo/modificationsequence) { get; } | Hämtar ändringssekvensen för detta meddelande. Se mer: https://tools.ietf.org/html/rfc7162 |
| [ParentFolder](../../aspose.email.clients.imap/imapmessageinfo/parentfolder) { get; } | Hämtar överordnad mapp för message |
| virtual [Properties](../../aspose.email.clients/messageinfobase/properties) { get; } | Får en mapi-egenskaper. |
| [Recent](../../aspose.email.clients.imap/imapmessageinfo/recent) { get; } | Får ett värde som anger om Flags-egenskapen innehåller flaggan Senaste. |
| [ReplyTo](../../aspose.email.clients/messageinfobase/replyto) { get; } | Hämtar listan över adresser som ska få svar på detta meddelande. |
| [Sender](../../aspose.email.clients/messageinfobase/sender) { get; } | Hämtar avsändaren av detta meddelande. |
| [SequenceNumber](../../aspose.email.clients.imap/imapmessageinfo/sequencenumber) { get; } | Hämtar meddelandesekvensnumret. |
| [Size](../../aspose.email.clients/messageinfobase/size) { get; } | Hämtar storleken på e-postmeddelandet. |
| [Subject](../../aspose.email.clients/messageinfobase/subject) { get; } | Hämtar ämnet för e-postmeddelandet. |
| virtual [To](../../aspose.email.clients/messageinfobase/to) { get; } | Hämtar mottagarna av e-postmeddelandet. |
| [UniqueId](../../aspose.email.clients.imap/imapmessageinfo/uniqueid) { get; } | Får meddelandets unika ID. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [ContainsKeyword](../../aspose.email.clients.imap/imapmessageinfo/containskeyword)(string) | Får ett värde som indikerar om egenskapen Flags innehåller nyckelordsflaggan. |
| virtual [Dispose](../../aspose.email.clients/messageinfobase/dispose)() | Utför uppgifter associerade med att frigöra, frigöra eller återställa ohanterade resurser. |
| override [ToString](../../aspose.email.clients.imap/imapmessageinfo/tostring)() | Returnerar en sträng som representerar det aktuella objektet. |

### Se även

* class [MessageInfoBase](../../aspose.email.clients/messageinfobase)
* namnutrymme [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
