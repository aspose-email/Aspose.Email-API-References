---
title: ExchangeMessageInfo
second_title: Aspose.Email för .NET API-referens
description: ExchangeMessageInfo representerar informationen om e-postmeddelandet som hämtats från Exchange Store.
type: docs
weight: 3400
url: /sv/net/aspose.email.clients.exchange/exchangemessageinfo/
---
## ExchangeMessageInfo class

ExchangeMessageInfo representerar informationen om e-postmeddelandet som hämtats från Exchange Store.

```csharp
public abstract class ExchangeMessageInfo : MessageInfoBase
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [Attachments](../../aspose.email.clients.exchange/exchangemessageinfo/attachments) { get; } | Får meddelandebilagor |
| virtual [Bcc](../../aspose.email.clients/messageinfobase/bcc) { get; } | Får en blind kopia av e-postmeddelandet. |
| virtual [CC](../../aspose.email.clients/messageinfobase/cc) { get; } | Får CC på e-postmeddelandet. |
| virtual [Date](../../aspose.email.clients/messageinfobase/date) { get; } | Ursprungsdatumet anger datumet och tiden då skaparen av meddelandet angav att meddelandet var komplett och redo att gå in i postleveranssystemet. Detta kan till exempel vara den tid som en användare trycker på knappen "skicka" eller "skicka" i ett applikationsprogram. I vilket fall som helst är det specifikt inte avsett att förmedla tiden då meddelandet faktiskt transporteras, men snarare tidpunkten då människan eller annan skapare av meddelandet har satt meddelandet i sin slutliga form, redo för transport. (Till exempel kan en bärbar datoranvändare som inte är ansluten till ett nätverk ställa ett meddelande i kö för leverans. Ursprungsdatumet är avsett att innehålla datumet och tiden då användaren köade meddelandet, inte tiden då användaren anslöt sig till nätverket för att skicka meddelandet.) |
| [From](../../aspose.email.clients/messageinfobase/from) { get; } | Hämtar listan över författare till detta meddelande. |
| virtual [HasAttachments](../../aspose.email.clients.exchange/exchangemessageinfo/hasattachments) { get; } | Får ett värde som anger om meddelandet innehåller minst en bilaga. |
| [Headers](../../aspose.email.clients/messageinfobase/headers) { get; } | Hämtar rubrikerna för e-postmeddelandet. |
| virtual [InternalDate](../../aspose.email.clients.exchange/exchangemessageinfo/internaldate) { get; } | Det interna datumet och tiden för meddelandet på servern. Detta är inte datum och tid i [RFC-2822]-huvudet, utan snarare ett datum och en tid som återspeglar när meddelandet togs emot. - I fallet med meddelanden som levereras via [SMTP], SKA detta vara datumet och tiden för slutleveransen av meddelandet enligt definitionen av [SMTP]. - I fallet med meddelanden som levereras av kommandot IMAP4rev1 COPY, SKA detta vara det interna datumet och klockslaget för källmeddelandet. - I fallet med meddelanden som levereras av kommandot IMAP4rev1 APPEND, SKA detta vara datumet och tiden som specificerats i kommandobeskrivningen APPEND. - Alla andra fall är implementeringsdefinierade. |
| virtual [IsRead](../../aspose.email.clients.exchange/exchangemessageinfo/isread) { get; } | Får ett värde som indikerar om meddelandet har lästs |
| [ListUnsubscribe](../../aspose.email.clients/messageinfobase/listunsubscribe) { get; } | Fältet List-Unsubscribe beskriver kommandot (helst med e-post) för att direkt avbryta prenumerationen av användaren (ta bort dem från listan). För mer information se https://tools.ietf.org/html/rfc2369 |
| virtual [MessageClass](../../aspose.email.clients.exchange/exchangemessageinfo/messageclass) { get; } | Får en sträng som representerar klassen för meddelandet. Egenskapen motsvarar egenskapen PidTagMessageClass MAPI. |
| [MessageId](../../aspose.email.clients/messageinfobase/messageid) { get; } | Hämtar meddelande-ID. |
| virtual [MessageInfoType](../../aspose.email.clients.exchange/exchangemessageinfo/messageinfotype) { get; } | Hämtar typen av meddelandet |
| virtual [Properties](../../aspose.email.clients/messageinfobase/properties) { get; } | Får en mapi-egenskaper. |
| [ReplyTo](../../aspose.email.clients/messageinfobase/replyto) { get; } | Hämtar listan över adresser som ska få svar på detta meddelande. |
| [Sender](../../aspose.email.clients/messageinfobase/sender) { get; } | Hämtar avsändaren av detta meddelande. |
| [Size](../../aspose.email.clients/messageinfobase/size) { get; } | Hämtar storleken på e-postmeddelandet. |
| [Subject](../../aspose.email.clients/messageinfobase/subject) { get; } | Hämtar ämnet för e-postmeddelandet. |
| virtual [To](../../aspose.email.clients/messageinfobase/to) { get; } | Hämtar mottagarna av e-postmeddelandet. |
| virtual [UniqueUri](../../aspose.email.clients.exchange/exchangemessageinfo/uniqueuri) { get; } | Får meddelandets unika URI. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [Dispose](../../aspose.email.clients/messageinfobase/dispose)() | Utför uppgifter associerade med att frigöra, frigöra eller återställa ohanterade resurser. |
| override [ToString](../../aspose.email.clients/messageinfobase/tostring)() | En sträng som representerar det aktuella objektet. |

### Se även

* class [MessageInfoBase](../../aspose.email.clients/messageinfobase)
* namnutrymme [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
