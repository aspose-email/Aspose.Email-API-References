---
title: HeaderType
second_title: Aspose.Email för .NET API-referens
description: Representerar internetstandarderna och RFCer definierar rubrikfält som kan förekomma på Internet Mail Messages .
type: docs
weight: 17510
url: /sv/net/aspose.email/headertype/
---
## HeaderType class

Representerar internetstandarderna och RFC:er definierar rubrikfält som kan förekomma på Internet Mail Messages .

```csharp
public sealed class HeaderType
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| static [ApparentlyTo](../../aspose.email/headertype/apparentlyto) { get; } | Infogas genom att skicka e-post när det inte finns någon "Till:"-mottagare i det ursprungliga meddelandet. Detta gör att mottagarna som kommer från kuvertet listas i meddelanderubriken. Det här beteendet är inte riktigt korrekt, MTA:er bör inte modifiera rubriker (förutom att infoga mottagna rader), och det kan i vissa fall göra att hemlig kopia-mottagare felaktigt avslöjas till icke-hemlig kopia-mottagare. Exempel: Apparently-To: someone@somedomain.com Icke-standardhuvud som inte används, nämnt i RFC1211. |
| static [ApprovedBy](../../aspose.email/headertype/approvedby) { get; } | Namn på moderatorn för e-postlistan som detta meddelande skickas till; nödvändigt på ett inlägg som skickas till en modererad e-postlista för att tillåta dess distribution till listmedlemmarna. Exempel: Godkänd-Av: någon@somedomain.com Ej standard för användning i e-post. Definierat i RFC1036. |
| static [Bcc](../../aspose.email/headertype/bcc) { get; } | En kopia av e-postmeddelandet som skickas till en eller flera mottagare utan att de primära mottagarna vet om det. Primära mottagare listas på raderna Till: och Kopia. Detta är användbart om du vill kopiera ett meddelande till många personer utan att var och en av dem ser vilka de andra mottagarna är. Om du ser denna rubrik på inkommande e-post är något fel eftersom det inte visas i rubrikerna. |
| static [CC](../../aspose.email/headertype/cc) { get; } | Denna rubrik kan betraktas som en förlängning av fältet "Till:" eftersom den används för att specificera ytterligare mottagare. I det här fallet har kopian av ett e-postmeddelande som skickas till en mottagare mottagarens adress som visas i meddelandet. Detta är användbart om du vill kopiera ett meddelande till många personer där var och en av dem ser vilka de andra mottagarna är; kontrast med Bcc ovan. Den här rubriken visas i inkommande e-post. Exempel: Kopia: gboyd@netcom.com |
| static [Comments](../../aspose.email/headertype/comments) { get; } | Detta är ett rubrikfält i fritt format definierat i RFC2822. Rubriken används för att placera förklarande text i rubrikdelen av ett e-postmeddelande. Fältet kan innehålla godtycklig text. Exempel: Kommentarer: Autentiserad avsändare är någon@somedonmain.com. |
| static [ContentTransferEncoding](../../aspose.email/headertype/contenttransferencoding) { get; } | Den tredje av de MIME-relaterade rubrikerna. Indikerar den kodningsmetod som används i ett MIME-meddelande. Det har ingen direkt relevans för leverans av e-post, men det påverkar hur MIME-kompatibla e-postprogram tolkar innehållet i meddelandet. Definierat i RFC2045. Content-Transfer-Encoding: 8bit Content-transfer-encoding: 7BIT Content-Transfer-Encoding: 7bit Content-Transfer-Encoding: base64 Encoding-Content-Transfer |
| static [ContentType](../../aspose.email/headertype/contenttype) { get; } | "Content-Type" definierar formatet på innehållet (teckenuppsättning etc.) Observera att värdena för denna rubrik definieras på olika sätt i RFC1049 och i MIME (RFC2045). Leta efter MIME-version: header för att förstå om Content-Type ska tolkas enligt RFC1049 eller enligt MIME (RFC2045). MIME-definitionen ska användas för att generera e-post. Historiskt har Content-Type-fältet föreslagits i RFC1049. I den särskiljde Content-Type inte typ och undertyp som RFC2045 gör. Exempel: Content-Type: text/plain; charset="us-ascii" Innehållstyp: text/plain; charset=US-ASCII Content-Type: text/plain; charset="iso-8859-1" Content-Type: text/plain; charset=koi8-r Content-Type: text/plain; charset=unknown-8bit |
| static [Date](../../aspose.email/headertype/date) { get; } | Denna rubrik anger ett datum (och tid), normalt datumet då meddelandet skrevs och skickades. I X.400 e-postsystem, tiden då ett meddelande skickades. Vissa e-postsystem på Internet använder också datumet då meddelandet skickades. Om denna rubrik utelämnas av avsändarens dator kan det tänkas läggas till av en e-postserver eller till och med av någon annan maskin längs rutten. Vad du kanske inte vet är att informationen i "Datum:"-raden tillhandahålls av tiden på avsändarens dator, som kanske är korrekt inställd eller inte. Rubriken "Datum:" anger normalt inte när meddelandet skickades, utan bara när det komponerades. Datumet är i form av 3 tecken veckodag (sön - lör), dagnummer (1-31) dd, 3-teckens månadsnamn, 4-siffrigt år åååå, följt av tid (24-timmar) hh :mm:ss och zon zzz-format. Tidszon (zzz) är antingen tidszonen med 3 tecken eller den lokala skillnaden i timmar och minuter som är förskjuten från UTC (Universal Time Coordinated - gammal Greenwich Mean Time). "-" indikerar väster och "+" indikerar öster om UTC. Det verkar inte finnas några standarddefinitioner för tidszon. Många UNIX-versioner förstår ett stort antal förkortningar, men den mest uttömmande listan jag hittade var GNU tar-manualen Timezone-objektet och dokumentation för Perl-datummanipuleringsmodulen TIMEZONES. Exempel: Datum: tis, 9 jan 2001 23:40:00 -0800 Datum: sön, 1 apr 2001 22:52:04 EDT 1 apr: 1 apr: 2002: 1 apr: 02:02: 01:02:02:02: 30 mars 2001 10:47:15 -0800 |
| static [DispositionNotificationTo](../../aspose.email/headertype/dispositionnotificationto) { get; } | När fältet DispositionNotificationTo är inställt görs en begäran om ett MDN (Message Delivery Notification). Mottagarens e-postprogram (Outlook, Eudora, etc.) kan ignorera begäran i tysthet, eller så kan den fråga användaren om tillåtelse att skicka MDN. Det finns ingen garanti för "retur-kvitto". Fältet DispositionNotificationTo är de facto standarden för att begära returkvitton (dvs. MDN eller meddelandeleveransaviseringar). |
| static [FollowupTo](../../aspose.email/headertype/followupto) { get; } | Används i Usenet News för att indikera att framtida diskussioner (=uppföljning) om en artikel bör gå till en annan uppsättning nyhetsgrupper än den besvarade artikeln. Den vanligaste användningen är när en artikel läggs upp i flera nyhetsgrupper, och ytterligare diskussioner ska äga rum i endast en av dem. Definierat i RFC 1036: 2.2.3, inte standardiserad för användning i e-post. |
| static [From](../../aspose.email/headertype/from) { get; } | Detta fält innehåller identiteten på den eller de personer som ville att detta meddelande skulle skickas. Processen för att skapa meddelanden bör som standard vara en enskild, autentiserad maskinadress, vilket anger AGENT (person, system eller process) som komponerar meddelandet. Om detta inte görs, MÅSTE fältet "Sender:" finnas. Om fältet "Från:" är standard på detta sätt är fältet "Avsändare:" valfritt och är överflödigt med fältet "Från:". Exempel: Från: "Mr. Some One" someone@somedomain.com |
| static [Importance](../../aspose.email/headertype/importance) { get; } | Får betydelsen. |
| static [InReplyTo](../../aspose.email/headertype/inreplyto) { get; } | Referens till meddelande som detta meddelande är ett svar på. |
| static [MessageID](../../aspose.email/headertype/messageid) { get; } | Unikt ID för detta meddelande. Definierat i RFC 822: 4.6.1 ,RFC 1036: 2.1.5. |
| static [MIMEVersion](../../aspose.email/headertype/mimeversion) { get; } | En indikator på att detta meddelande är formaterat enligt MIME-standarden och en indikation på vilken version av MIME som används. Definierat i RFC 2045 |
| static [Newsgroups](../../aspose.email/headertype/newsgroups) { get; } | I Usenet News: grupp(er) som denna artikel postades till. Vissa system tillhandahåller detta rubrikfält även i e-post även om det inte är standardiserat där. Tyvärr kan rubrikfältet visas i e-post med tre olika och motsägelsefulla betydelser: (a) Anger nyhetsgruppsmottagaren av en artikel/meddelande som skickats till både e-post- och Usenet News-mottagare. (b) I ett meddelande adresserat till viss e-post till nyhetsgateways, indikerar den eller vilka nyhetsgrupper som meddelandet ska skickas till. (c) I ett personligt adresserat svar på en artikel i en nyhetsgrupp, som anger i vilken nyhetsgrupp denna diskussion har sitt ursprung. Definierat i RFC 1036: 2.1.3, inte standardiserad och kontroversiell för användning i e-post. |
| static [Received](../../aspose.email/headertype/received) { get; } | Spår av MTA som ett meddelande har passerat. Definierat i RFC 822 |
| static [References](../../aspose.email/headertype/references) { get; } | Referens till andra relaterade meddelanden. |
| static [ReplyTo](../../aspose.email/headertype/replyto) { get; } | Detta rubrikfält är avsett att indikera vart avsändaren vill att svar ska hamna. Tyvärr är detta tvetydigt, eftersom det finns olika typer av svar, som avsändaren kan vilja gå till olika adresser. I synnerhet finns det personliga svar avsedda för endast en person, och gruppsvar, avsedda för hela gruppen personer som läser det besvarade meddelandet (ofta en e-postlista, ett nytt gruppnamn kan inte visas här på grund av olika syntax, se " Uppföljning till" .). |
| static [ReturnPath](../../aspose.email/headertype/returnpath) { get; } | Används för att förmedla informationen från attributet MAIL FROM envelope vid slutleverans, när meddelandet lämnar SMTP-miljön där "MAIL FROM" används. /// |
| static [ReturnReceiptTo](../../aspose.email/headertype/returnreceiptto) { get; } | En avsändare kan begära ett returkvitto genom att inkludera detta rubrikfält. Returkvittot skickas till retursökvägsadressen för e-postmeddelandet och inte till adressen som anges i fältet Returkvitto-till rubriken. Denna rubrik är icke-standard och stöds oftast inte. Använd Disposition-Notification-To istället. Även om det stöds finns det ingen garanti för att ett kvitto skickas. |
| static [Sender](../../aspose.email/headertype/sender) { get; } | Personen eller agenten som skickar meddelandet till nätverket, om något annat än visas i fältet Från:-huvud. Bör autentiseras, enligt RFC 822, men vilken typ av autentisering framgår inte. |
| static [Sensitivity](../../aspose.email/headertype/sensitivity) { get; } | Får känsligheten. |
| static [Subject](../../aspose.email/headertype/subject) { get; } | Titel, rubrik, ämne. Används ofta som trådindikator för meddelanden som svarar på eller kommenterar andra meddelanden. |
| static [To](../../aspose.email/headertype/to) { get; } | Primära mottagare. Exempel: Till: någon@somedomain.com |
| static [XConfirmReadingTo](../../aspose.email/headertype/xconfirmreadingto) { get; } | Den här rubriken begär ett automatiskt bekräftelsemeddelande när meddelandet tas emot eller läses. Det ignoreras vanligtvis; antagligen verkar någon programvara på den. |
| static [XMailer](../../aspose.email/headertype/xmailer) { get; } | Information om upphovsmannens klientprogramvara. Exempel: X-Mailer: Aspose.Email |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.email/headertype/equals)(object) | Returnerar ett booleskt värde som indikerar om det skickade objektet obj är lika med detta. |
| override [GetHashCode](../../aspose.email/headertype/gethashcode)() | Fungerar som en hashfunktion för en viss typ. |
| override [ToString](../../aspose.email/headertype/tostring)() | Returnerar enString som representerar strömmenObject . |
| [implicit operator](../../aspose.email/headertype/op_implicit) | Utför en implicit konvertering från[`HeaderType`](../headertype) tillString . |

### Se även

* namnutrymme [Aspose.Email](../../aspose.email)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
