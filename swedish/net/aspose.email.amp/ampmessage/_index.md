---
title: AmpMessage
second_title: Aspose.Email för .NET API-referens
description: Meddelande som tillåter avsändare att inkludera AMP-komponenter i e-postmeddelanden.
type: docs
weight: 140
url: /sv/net/aspose.email.amp/ampmessage/
---
## AmpMessage class

Meddelande som tillåter avsändare att inkludera AMP-komponenter i e-postmeddelanden.

```csharp
public class AmpMessage : MailMessage
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [AmpMessage](ampmessage)() | Initierar en ny instans av[`MailMessage`](../../aspose.email/mailmessage) klass |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [AlternateViews](../../aspose.email/mailmessage/alternateviews) { get; } | Får samlingen av alternativa vyer av message |
| virtual [AmpHtmlBody](../../aspose.email.amp/ampmessage/amphtmlbody) { get; set; } | Hämtar AmpHtml-representationen av meddelandetexten. |
| virtual [Attachments](../../aspose.email/mailmessage/attachments) { get; } | Får samlingen av bilagor av meddelande |
| virtual [Bcc](../../aspose.email/mailmessage/bcc) { get; set; } | Hämtar eller ställer in adresssamlingen som innehåller BCC-mottagarna för message |
| virtual [Body](../../aspose.email/mailmessage/body) { get; set; } | Hämtar eller ställer in ren textrepresentation av meddelandets brödtext. Om texten/den vanliga delen finns i ett meddelande, returnerar egenskapen dess textdata. Annars returnerar egenskapen textinnehållet i HtmlBody-egenskapen utan html-uppmärkning. |
| virtual [BodyEncoding](../../aspose.email/mailmessage/bodyencoding) { get; set; } | Hämtar eller ställer in kodning av body |
| [BodyType](../../aspose.email/mailmessage/bodytype) { get; } | Hämtar typen av kroppen. |
| virtual [CC](../../aspose.email/mailmessage/cc) { get; set; } | Hämtar eller ställer in adresssamlingen som innehåller CC recipients |
| virtual [Date](../../aspose.email/mailmessage/date) { get; set; } | Hämtar eller ställer in datumet för meddelandet |
| virtual [DeliveryNotificationOptions](../../aspose.email/mailmessage/deliverynotificationoptions) { get; set; } | Hämtar eller ställer in leveransaviseringar |
| [Epilogue](../../aspose.email/mailmessage/epilogue) { get; set; } | Hämtar eller ställer in en epilogtext. Den är placerad efter den sista gränsen. |
| virtual [From](../../aspose.email/mailmessage/from) { get; set; } | Hämtar eller ställer in från adressen |
| virtual [Headers](../../aspose.email/mailmessage/headers) { get; } | Får rubriksamling av meddelande |
| virtual [HtmlBody](../../aspose.email/mailmessage/htmlbody) { get; set; } | Hämtar eller ställer in html body |
| virtual [IsBodyHtml](../../aspose.email/mailmessage/isbodyhtml) { get; set; } | Hämtar eller ställer in ett värde som anger om meddelandetexten är i Html |
| virtual [IsDraft](../../aspose.email/mailmessage/isdraft) { get; set; } | Hämtar eller ställer in värde som indikerar om ett meddelande har skickats eller inte. |
| virtual [IsEncrypted](../../aspose.email/mailmessage/isencrypted) { get; } | Får ett värde som indikerar om meddelandet är krypterat. |
| virtual [IsReadOnly](../../aspose.email/mailmessage/isreadonly) { get; } | Får ett värde som indikerar om meddelandet är skrivskyddat |
| virtual [IsSigned](../../aspose.email/mailmessage/issigned) { get; } | Får ett värde som indikerar om meddelandet är signerat. |
| virtual [LinkedResources](../../aspose.email/mailmessage/linkedresources) { get; } | Hämtar samlingen av länkade resurser för message |
| virtual [MessageId](../../aspose.email/mailmessage/messageid) { get; set; } | Hämtar eller ställer in meddelandet id |
| virtual [OriginalIsTnef](../../aspose.email/mailmessage/originalistnef) { get; } | Får ett värde som indikerar om det ursprungliga EML-meddelandet är i TNEF-format. |
| [Preamble](../../aspose.email/mailmessage/preamble) { get; set; } | Hämtar eller ställer in en inledningstext. Den är placerad före den första gränsen och innehåller vanligtvis en förklarande anmärkning till läsare som inte uppfyller MIME. |
| [PreferredTextEncoding](../../aspose.email/mailmessage/preferredtextencoding) { get; set; } | Hämtar eller ställer in föredragen kodning för alla textegenskaper |
| virtual [Priority](../../aspose.email/mailmessage/priority) { get; set; } | Hämtar eller ställer in prioriteten för message |
| [ReadReceiptTo](../../aspose.email/mailmessage/readreceiptto) { get; set; } | Hämtar eller ställer in läskvittoadressen. |
| virtual [ReplyToList](../../aspose.email/mailmessage/replytolist) { get; set; } | Hämtar eller ställer in listan med adresser att svara på för e-postmeddelandet |
| virtual [ReversePath](../../aspose.email/mailmessage/reversepath) { get; set; } | Hämtar eller ställer in ReversePath address |
| virtual [Sender](../../aspose.email/mailmessage/sender) { get; set; } | Hämtar eller ställer in avsändaradress |
| virtual [Sensitivity](../../aspose.email/mailmessage/sensitivity) { get; set; } | Hämtar eller ställer in känsligheten för meddelande |
| virtual [Subject](../../aspose.email/mailmessage/subject) { get; set; } | Hämtar eller ställer in ämnesraden |
| virtual [SubjectEncoding](../../aspose.email/mailmessage/subjectencoding) { get; set; } | Hämtar eller ställer in kodningen för subject |
| [TimeZoneOffset](../../aspose.email/mailmessage/timezoneoffset) { get; set; } | Hämtar eller ställer in Coordinated Universal Time (UTC) offset för meddelandedatum. Den här egenskapen definierar tidszonsskillnaden, mellan lokal tid och UTC. |
| virtual [To](../../aspose.email/mailmessage/to) { get; set; } | Hämtar eller ställer in adresssamlingen som innehåller mottagarna av meddelande |
| virtual [XMailer](../../aspose.email/mailmessage/xmailer) { get; set; } | Hämtar eller ställer in X-Mailer programvaran som skapade e-postmeddelandet |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [AddAlternateView](../../aspose.email/mailmessage/addalternateview)(AlternateView) | Lägg till en alternativ vy till message |
| [AddAmpComponent](../../aspose.email.amp/ampmessage/addampcomponent)(AmpComponent) | Lägg till Amp-komponent i detta meddelande. |
| virtual [AddAttachment](../../aspose.email/mailmessage/addattachment)(Attachment) | Lägg till en bilaga till meddelande |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature)(CmsSigner) | Skapar ett signerat meddelande. Skapar en skrivskyddad kopia av det angivna MailMessage och lägger till en digital signatur till det. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature)(X509Certificate2) | Skapar ett signerat meddelande. Skapar en skrivskyddad kopia av det angivna MailMessage och lägger till en digital signatur till det. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature)(CmsSigner, bool) | Skapar ett signerat meddelande. Skapar en skrivskyddad kopia av det angivna MailMessage och lägger till en digital signatur till det. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature)(X509Certificate2, bool) | Skapar ett signerat meddelande. Skapar en skrivskyddad kopia av det angivna MailMessage och lägger till en digital signatur till det. |
| virtual [CheckBounced](../../aspose.email/mailmessage/checkbounced)() | Kontrollerar om detta meddelande kan behandlas som ett avvisningsmeddelande. |
| virtual [CheckSignature](../../aspose.email/mailmessage/checksignature)() | Kontrollerar befintlig signatur för MailMessage. |
| virtual [Clone](../../aspose.email/mailmessage/clone)() | Klonar denna instans |
| [CreateReadReceipt](../../aspose.email/mailmessage/createreadreceipt)(string, string) | Skapar läskvittot. |
| virtual [Decrypt](../../aspose.email/mailmessage/decrypt)() | Dekrypterar detta meddelande |
| virtual [Decrypt](../../aspose.email/mailmessage/decrypt)(X509Certificate2) | Dekrypterar detta meddelande |
| [Dispose](../../aspose.email/mailmessage/dispose)() | Frigör alla resurser som används av MailMessage |
| virtual [DKIMSign](../../aspose.email/mailmessage/dkimsign)(RSACryptoServiceProvider, DKIMSignatureInfo) | Signerar detta meddelande med DKIM-signatur (DomainKeys Identified Mail). |
| virtual [Encrypt](../../aspose.email/mailmessage/encrypt)(X509Certificate2) | Krypterar detta meddelande |
| virtual [Encrypt](../../aspose.email/mailmessage/encrypt)(X509Certificate2[]) | Krypterar detta meddelande |
| override [Equals](../../aspose.email/mailmessage/equals)(object) | Bestämmer om det angivna objektet är lika med det aktuella objektet. |
| [GetEnumerator](../../aspose.email/mailmessage/getenumerator)() | Returnerar en uppräkning som itererar genom en samling. |
| override [GetHashCode](../../aspose.email/mailmessage/gethashcode)() | Returnerar en hash-kod för objekt |
| virtual [GetHtmlBodyText](../../aspose.email/mailmessage/gethtmlbodytext)(bool) | Hämtar meddelandets html text som vanlig text. Den här metoden analyserar egenskapen HtmlBody och returnerar oformaterad text som ignorerar html-markeringen. |
| virtual [GetHtmlBodyText](../../aspose.email/mailmessage/gethtmlbodytext)(HyperlinkRenderingCallback) | Hämtar meddelandet htmlbody som vanlig text. |
| virtual [GetObjectData](../../aspose.email/mailmessage/getobjectdata)(SerializationInfo, StreamingContext) | Fyller i enSerializationInfo med de data som behövs för att serialisera målobjektet. |
| virtual [Import](../../aspose.email/mailmessage/import)(Stream) | Importerar meddelande från stream |
| [RecomposeTnefContent](../../aspose.email/mailmessage/recomposetnefcontent)() | Komponerar TNEF-innehållet. Observera att tnef-bilaga skapas om ett meddelande från början innehöll TNEF och laddades utan FileCompatibilityMode.PreserveTnefAttachments-flaggan, Det är den här metoden som inte skapar tx0 det vanliga meddelandet._0 |
| virtual [RemoveSignature](../../aspose.email/mailmessage/removesignature)() | Ta bort signatur |
| virtual [Save](../../aspose.email/mailmessage/save)(Stream) | Spara meddelande som en stream |
| virtual [Save](../../aspose.email/mailmessage/save)(string) | Spara meddelande som en fil |
| override [Save](../../aspose.email.amp/ampmessage/save#save_1)(Stream, SaveOptions) | Spara meddelande som en stream |
| virtual [Save](../../aspose.email/mailmessage/save)(string, SaveOptions) | Spara meddelande som en fil med ytterligare alternativ. |
| virtual [SetHtmlBody](../../aspose.email/mailmessage/sethtmlbody)(string, bool) | Ställer in HTML-text. |
| override [ToString](../../aspose.email/mailmessage/tostring)() | Returnerar en sträng som representerar det aktuella objektet. |

### Se även

* class [MailMessage](../../aspose.email/mailmessage)
* namnutrymme [Aspose.Email.Amp](../../aspose.email.amp)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
