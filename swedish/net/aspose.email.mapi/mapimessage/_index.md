---
title: MapiMessage
second_title: Aspose.Email för .NET API-referens
description: Representerar ett dokument i Outlook-meddelandeformat som kan tolkas.
type: docs
weight: 18450
url: /sv/net/aspose.email.mapi/mapimessage/
---
## MapiMessage class

Representerar ett dokument i Outlook-meddelandeformat som kan tolkas.

```csharp
public sealed class MapiMessage : MapiMessageItemBase
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [MapiMessage](mapimessage#constructor)() | Initierar en ny instans av[`MapiMessage`](../mapimessage) class. |
| [MapiMessage](mapimessage#constructor_1)(OutlookMessageFormat) | Initierar en ny instans av[`MapiMessage`](../mapimessage) class. |
| [MapiMessage](mapimessage#constructor_2)(string, string, string, string) | Initierar en ny instans av[`MapiMessage`](../mapimessage) class. |
| [MapiMessage](mapimessage#constructor_3)(string, string, string, string, OutlookMessageFormat) | Initierar en ny instans av[`MapiMessage`](../mapimessage) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapimessageitembase/attachments) { get; } | Hämtar bilagorna i meddelandet. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Innehåller faktureringsinformation som är kopplad till en artikel. |
| [Body](../../aspose.email.mapi/mapimessage/body) { get; set; } | Hämtar meddelandetexten. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Får[`BodyRtf`](../mapimessageitembase/bodyrtf) av meddelandet konverterat till HTML, om det finns, annars en tom sträng. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Hämtar eller ställer in den RTF-formaterade meddelandetexten. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Hämtar typen av kroppen. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Innehåller nyckelord eller kategorier för meddelandeobjektet. |
| [ClientSubmitTime](../../aspose.email.mapi/mapimessage/clientsubmittime) { get; set; } | Hämtar eller ställer in datum och tid meddelandeavsändaren skickade ett meddelande. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Hämtar teckentabellen. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Innehåller namnen på de företag som är associerade med en vara. |
| [ConversationTopic](../../aspose.email.mapi/mapimessage/conversationtopic) { get; } | Hämtar ämnet för det första meddelandet i en konversationstråd. |
| [DeliveryTime](../../aspose.email.mapi/mapimessage/deliverytime) { get; set; } | Hämtar eller ställer in datum och tid ett meddelande levererades. |
| [DisplayBcc](../../aspose.email.mapi/mapimessage/displaybcc) { get; } | Hämtar en lista över visningsnamnen för alla mottagare av BCC-meddelanden, separerade med semikolon (;). |
| [DisplayCc](../../aspose.email.mapi/mapimessage/displaycc) { get; } | Hämtar en lista över visningsnamnen för alla mottagare av CC-meddelanden, separerade med semikolon (;). |
| [DisplayName](../../aspose.email.mapi/mapimessage/displayname) { get; } | Hämtar visningsnamnet för meddelandet. |
| [DisplayNamePrefix](../../aspose.email.mapi/mapimessage/displaynameprefix) { get; } | Får ett prefix för visningsnamnet. |
| [DisplayTo](../../aspose.email.mapi/mapimessage/displayto) { get; } | Hämtar en lista över visningsnamnen för de primära (Till) meddelandemottagarna, separerade med semikolon (;). |
| [Flags](../../aspose.email.mapi/mapimessage/flags) { get; } | Hämtar meddelandeflaggor. |
| [Headers](../../aspose.email.mapi/mapimessage/headers) { get; set; } | Hämtar transportmeddelandet headers |
| [InternetMessageId](../../aspose.email.mapi/mapimessage/internetmessageid) { get; } | Hämtar meddelandets meddelande-id. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | Artikel-id, används med en server |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Får en skiftlägeskänslig sträng som identifierar den avsändardefinierade meddelandeklassen, till exempel IPM.Note. Meddelandeklassen anger typen, syftet eller innehållet för meddelandet. |
| [MessageFormat](../../aspose.email.mapi/mapimessage/messageformat) { get; } | Hämtar Outlook-meddelandeformatet. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Innehåller information om körsträcka som är associerad med en artikel. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Hämtar de namngivna egenskaperna för meddelandet. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Hämtar den namngivna egenskapsmappingen. |
| [NormalizedSubject](../../aspose.email.mapi/mapimessage/normalizedsubject) { get; } | Får normaliserat ämne för meddelandet. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Hämtar samlingen av egenskaper. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Hämtar egenskapsströmmen. |
| [ReadReceiptRequested](../../aspose.email.mapi/mapimessage/readreceiptrequested) { get; set; } | Hämtar eller ställer in ett värde som anger om läskvittot efterfrågas. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Hämtar mottagarna av meddelandet. |
| [ReplyTo](../../aspose.email.mapi/mapimessage/replyto) { get; set; } | Hämtar eller ställer in svaret på namn. |
| [SenderAddressType](../../aspose.email.mapi/mapimessage/senderaddresstype) { get; } | Hämtar meddelandeavsändarens e-postadresstyp. |
| [SenderEmailAddress](../../aspose.email.mapi/mapimessage/senderemailaddress) { get; set; } | Hämtar eller ställer in meddelandeavsändarens e-postadress. |
| [SenderName](../../aspose.email.mapi/mapimessage/sendername) { get; set; } | Hämtar eller ställer in meddelandeavsändarens visningsnamn. |
| [SenderSmtpAddress](../../aspose.email.mapi/mapimessage/sendersmtpaddress) { get; set; } | Hämtar eller ställer in meddelandeavsändarens e-postadress. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Får känsligheten. |
| [SentRepresentingAddressType](../../aspose.email.mapi/mapimessage/sentrepresentingaddresstype) { get; } | Hämtar adresstypen för meddelandeanvändaren som representeras av avsändaren. |
| [SentRepresentingEmailAddress](../../aspose.email.mapi/mapimessage/sentrepresentingemailaddress) { get; set; } | Hämtar eller ställer in e-postadressen för meddelandeanvändaren som representeras av avsändaren. |
| [SentRepresentingName](../../aspose.email.mapi/mapimessage/sentrepresentingname) { get; set; } | Hämtar eller ställer in visningsnamnet för meddelandeanvändaren som representeras av avsändaren. |
| [SentRepresentingSmtpAddress](../../aspose.email.mapi/mapimessage/sentrepresentingsmtpaddress) { get; } | Hämtar eller ställer in e-postadressen för meddelandeanvändaren som representeras av avsändaren. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Hämtar eller ställer in ämnet för meddelandet. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Får ett ämnesprefix som vanligtvis indikerar någon åtgärd på ett meddelande, till exempel "FW: " för vidarebefordran. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Hämtar underlagringarna. |
| [TransportMessageHeaders](../../aspose.email.mapi/mapimessage/transportmessageheaders) { get; } | Hämtar den transportspecifika meddelandekuvertinformationen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage)(MailMessage) | Skapar en instans av MapiMessage från MailMessage. |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage_2)(string) | Skapar en instans av MapiMessage från MailMessage. |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage_1)(MailMessage, MapiConversionOptions) | Skapar en instans av MapiMessage från MailMessage. |
| static [FromProperties](../../aspose.email.mapi/mapimessage/fromproperties)(MapiPropertyCollection) | Skapar en instans av MapiMessage från en samling av Mapi-egenskaper. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load)(Stream) | Laddar meddelande från stream. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_2)(string) | Laddar meddelande från fil. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_1)(Stream, LoadOptions) | Laddar meddelande från ström med ytterligare alternativ. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_3)(string, LoadOptions) | Laddar meddelande från fil med ytterligare alternativ. |
| static [LoadFromTnef](../../aspose.email.mapi/mapimessage/loadfromtnef#loadfromtnef)(Stream) | Laddar meddelande från Transport Neutral Encapsulation Format (TNEF) datastruktur |
| static [LoadFromTnef](../../aspose.email.mapi/mapimessage/loadfromtnef#loadfromtnef_1)(string) | Laddar meddelande från Transport Neutral Encapsulation Format (TNEF) datastruktur |
| [AddCustomProperty](../../aspose.email.mapi/mapimessage/addcustomproperty#addcustomproperty)(MapiProperty, string) | Lägger till den anpassade egenskapen. |
| [AddCustomProperty](../../aspose.email.mapi/mapimessage/addcustomproperty#addcustomproperty_1)(MapiPropertyType, byte[], string) | Lägger till den anpassade egenskapen. |
| [CheckBounced](../../aspose.email.mapi/mapimessage/checkbounced)() | Kontrollerar om detta meddelande kan behandlas som ett avvisningsmeddelande. |
| [Clone](../../aspose.email.mapi/mapimessage/clone)() | Skapar ett nytt objekt som är en kopia av den aktuella instansen. |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose)() | Utför programdefinierade uppgifter associerade med att frigöra, frigöra eller återställa ohanterade resurser. |
| [GetCustomProperties](../../aspose.email.mapi/mapimessage/getcustomproperties)() | Får en samling anpassade MapiProperties. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty)(PropertyDescriptor) | Hämtar MAPI-egenskap efter egenskapsbeskrivning. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Hämtar värdet för egenskapen som anges av taggen som boolesk typ. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Hämtar strängvärdet för egenskapen som anges av taggen. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Hämtar värdet för egenskapen specificerad av taggen som DateTime type. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Hämtar int32-värdet för egenskapen som anges av taggen. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Hämtar värdet för egenskapen specificerad av taggen som Long (int64) type. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Hämtar värdet för egenskapen som anges av taggen som Short type. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Hämtar strängvärdet för egenskapen som anges av taggen. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Hämtar strängvärdet för egenskapen som anges av taggen. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Bestämmer om strängegenskaper är Unicode-kodade eller inte. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | Ger korrekt borttagning av egendom från alla samlingar. |
| [Save](../../aspose.email.mapi/mapimessage/save#save)(Stream) | Sparar till den angivna strömmen som Msg. |
| [Save](../../aspose.email.mapi/mapimessage/save#save_2)(string) | Sparar till den angivna filen som Msg. |
| [Save](../../aspose.email.mapi/mapimessage/save#save_1)(Stream, SaveOptions) | Sparar meddelandet som en ström med ytterligare alternativ. |
| [Save](../../aspose.email.mapi/mapimessage/save#save_3)(string, SaveOptions) | Sparar meddelandet som en fil med ytterligare alternativ. |
| [SaveAsTemplate](../../aspose.email.mapi/mapimessage/saveastemplate#saveastemplate)(Stream) | Sparar till den angivna strömmen som Outlook-filmall (OFT-format). |
| [SaveAsTemplate](../../aspose.email.mapi/mapimessage/saveastemplate#saveastemplate_1)(string) | Sparar till den angivna filen som Outlook-filmall (OFT-format). |
| [SaveAsTnef](../../aspose.email.mapi/mapimessage/saveastnef#saveastnef)(Stream) | Spara meddelande i TNEF-format. |
| [SaveAsTnef](../../aspose.email.mapi/mapimessage/saveastnef#saveastnef_1)(string) | Spara meddelande i TNEF-format. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType) | Ställer in innehållet i brödtexten. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType, bool) | Ställer in innehållet i brödtexten. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf)(string, bool) | Hämtar eller ställer in den RTF-formaterade meddelandetexten. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags)(MapiMessageFlags) | Ställer in meddelandeflaggor. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | Anger egenskapen. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty)(PropertyDescriptor, object) | Ställer in MAPI-egenskapen. |
| [SetStringPropertyValue](../../aspose.email.mapi/mapimessage/setstringpropertyvalue)(long, string) | Anger strängegenskapsvärdet. |
| [ToMailMessage](../../aspose.email.mapi/mapimessage/tomailmessage)(MailConversionOptions) | Skapar en instans av MailMessage från denna MapiMessage. |
| [ToMapiMessageItem](../../aspose.email.mapi/mapimessage/tomapimessageitem)() | Konvertera MapiMessage till IMapiMessageItem object i beroende av MessageClass. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | Försök att hämta egenskapsdata med angiven taggnyckel. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | Hämtar värdet för den angivna egenskapen som DateTime-typ. Ett returvärde anger om operationen lyckades. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | Hämtar värdet för den angivna egenskapen som Int32-typ. Ett returvärde anger om operationen lyckades. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | Hämtar värdet för den angivna egenskapen som lång typ. Ett returvärde anger om operationen lyckades. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | Försök att få en egenskapsdata som sträng med specificerad tagg. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | Försök att få en egenskapsdata som sträng med specificerad tagg och teckentabell. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | Hämtar värdet för den angivna egenskapen som strängtyp. Ett returvärde anger om operationen lyckades. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | Hämtar värdet för den angivna egenskapen som strängtyp. Ett returvärde anger om operationen lyckades. |
| static [DestroyAttachments](../../aspose.email.mapi/mapimessage/destroyattachments)(string) | Förstör bilagorna i de angivna Outlook-meddelandefilerna. DestroyAttachments kommer att ignorera bifogad analys. |
| static [IsMsgFormat](../../aspose.email.mapi/mapimessage/ismsgformat#ismsgformat)(Stream) | Avgör om den angivna strömmen har ett MSG-format. |
| static [IsMsgFormat](../../aspose.email.mapi/mapimessage/ismsgformat#ismsgformat_1)(string) | Avgör om den angivna filen har ett MSG-format. |
| static [RemoveAttachments](../../aspose.email.mapi/mapimessage/removeattachments)(string) | Tar bort alla bilagor från de angivna Outlook-meddelandefilerna. |

### Anmärkningar

Instanser av MapiMessage-klassen används för att representera Microsoft Outlook Message-dokumentfiler som tolkas av MapiMessageReader-klassen. För att komma åt avsändaren, mottagaren och innehållet i ett e-postmeddelande, använd de tillhörande egenskaperna för MapiMessage-klassen.

### Exempel

Följande exempel visar hur man läser Outlook-meddelandefiler.

[C#]

[Visual Basic]

```csharp
//Öppna Outlook Message-filer
MapiMessage msg = MapiMessage.FromFile(@"c:\outlookmessage.msg");

/läs ämne
onsole.WriteLine("Subject:" + msg.Subject);

/avsändarens namn
onsole.WriteLine("From:" + msg.SenderName);

/meddelandetext
onsole.WriteLine("Body:" + msg.Body);

/Bilagor
oreach(MapiAttachment att in msg.Attachments)

   Console.WriteLine("Attachment Name:"+att.FileName);
   att.Save(att.FileName);
    
```

```csharp
'Öppna Outlook-meddelandefiler 
Dim msg As MapiMessage = MapiMessage.FromFile("c:\outlookmessage.msg") 

'läst ämne 
Console.WriteLine("Subject:" + msg.Subject) 

'avsändarens namn 
Console.WriteLine("From:" + msg.SenderName) 

'meddelandetext 
Console.WriteLine("Body:" + msg.Body) 

'Bilagor 
For Each att As MapiAttachment In msg.Attachments 
    Console.WriteLine("Attachment Name:" + att.FileName) 
    att.Save(att.FileName) 
Next
```

### Se även

* class [MapiMessageItemBase](../mapimessageitembase)
* namnutrymme [Aspose.Email.Mapi](../../aspose.email.mapi)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
