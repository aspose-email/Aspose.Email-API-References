---
title: MapiContact
second_title: Aspose.Email för .NET API-referens
description: Representerar kontaktinformation för Outlook
type: docs
weight: 18190
url: /sv/net/aspose.email.mapi/mapicontact/
---
## MapiContact class

Representerar kontaktinformation för Outlook

```csharp
public sealed class MapiContact : MapiMessageItemBase
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [MapiContact](mapicontact#constructor)() | Initierar en ny instans av[`MapiContact`](../mapicontact) klass |
| [MapiContact](mapicontact#constructor_1)(string, string) | Initierar en ny instans av[`MapiContact`](../mapicontact) class. |
| [MapiContact](mapicontact#constructor_2)(string, string, string) | Initierar en ny instans av[`MapiContact`](../mapicontact) class. |
| [MapiContact](mapicontact#constructor_3)(string, string, string, string) | Initierar en ny instans av[`MapiContact`](../mapicontact) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapicontact/attachments) { get; } | Hämtar bilagorna i kontakten. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Innehåller faktureringsinformation som är kopplad till en artikel. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | Hämtar meddelandetexten. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Får[`BodyRtf`](../mapimessageitembase/bodyrtf) av meddelandet konverterat till HTML, om det finns, annars en tom sträng. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Hämtar eller ställer in den RTF-formaterade meddelandetexten. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Hämtar typen av kroppen. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Innehåller nyckelord eller kategorier för meddelandeobjektet. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Hämtar teckentabellen. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Innehåller namnen på de företag som är associerade med en vara. |
| [ElectronicAddresses](../../aspose.email.mapi/mapicontact/electronicaddresses) { get; set; } | Ange egenskaper för upp till tre olika e-postadresser och tre olika faxadresser |
| [Events](../../aspose.email.mapi/mapicontact/events) { get; set; } | Ange händelser associerade med en kontakt |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | Artikel-id, används med en server |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Får en skiftlägeskänslig sträng som identifierar den avsändardefinierade meddelandeklassen, till exempel IPM.Note. Meddelandeklassen anger typen, syftet eller innehållet för meddelandet. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Innehåller information om körsträcka som är associerad med en artikel. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Hämtar de namngivna egenskaperna för meddelandet. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Hämtar den namngivna egenskapsmappingen. |
| [NameInfo](../../aspose.email.mapi/mapicontact/nameinfo) { get; set; } | Egenskaperna används för att ange namnet på den person som representeras av kontakten |
| [OtherFields](../../aspose.email.mapi/mapicontact/otherfields) { get; set; } | Ange andra kontaktfält. |
| [PersonalInfo](../../aspose.email.mapi/mapicontact/personalinfo) { get; set; } | Ange annan ytterligare kontaktinformation |
| [Photo](../../aspose.email.mapi/mapicontact/photo) { get; set; } | Innehåller kontaktfoto[`MapiContactPhoto`](../mapicontactphoto) . |
| [PhysicalAddresses](../../aspose.email.mapi/mapicontact/physicaladdresses) { get; set; } | Ange tre fysiska adresser: Hemadress, Arbetsadress och Annan adress. En av adresserna kan markeras som Mailing Address |
| [ProfessionalInfo](../../aspose.email.mapi/mapicontact/professionalinfo) { get; set; } | Egenskaper används för att lagra professionella detaljer för den person som representeras av contact |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Hämtar samlingen av egenskaper. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Hämtar egenskapsströmmen. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Hämtar mottagarna av meddelandet. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Får känsligheten. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Hämtar eller ställer in ämnet för meddelandet. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Får ett ämnesprefix som vanligtvis indikerar någon åtgärd på ett meddelande, till exempel "FW: " för vidarebefordran. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Hämtar underlagringarna. |
| [Telephones](../../aspose.email.mapi/mapicontact/telephones) { get; set; } | Ange telefonnummer för kontakten |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard)(Stream) | Läser[`MapiContact`](../mapicontact) från den angivna strömmen som innehåller vCard. De vCard-versioner som stöds är 2.1 och 3.0 |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard_2)(string) | Läser[`MapiContact`](../mapicontact) från den angivna vCard-filen file De vCard-versioner som stöds är 2.1 och 3.0 |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard_1)(Stream, Encoding) | Läser[`MapiContact`](../mapicontact) från den angivna strömmen som innehåller vCard. De vCard-versioner som stöds är 2.1 och 3.0 |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard_3)(string, Encoding) | Läser[`MapiContact`](../mapicontact) från den angivna vCard-filen file De vCard-versioner som stöds är 2.1 och 3.0 |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose)() | Utför programdefinierade uppgifter associerade med att frigöra, frigöra eller återställa ohanterade resurser. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty)(PropertyDescriptor) | Hämtar MAPI-egenskap efter egenskapsbeskrivning. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Hämtar värdet för egenskapen som anges av taggen som boolesk typ. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Hämtar strängvärdet för egenskapen som anges av taggen. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Hämtar värdet för egenskapen specificerad av taggen som DateTime type. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Hämtar int32-värdet för egenskapen som anges av taggen. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Hämtar värdet för egenskapen specificerad av taggen som Long (int64) type. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Hämtar värdet för egenskapen som anges av taggen som Short type. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Hämtar strängvärdet för egenskapen som anges av taggen. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Hämtar strängvärdet för egenskapen som anges av taggen. |
| [GetUnderlyingMessage](../../aspose.email.mapi/mapicontact/getunderlyingmessage)() | Hämta MapiMessage som representerar kontakt. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Bestämmer om strängegenskaper är Unicode-kodade eller inte. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | Ger korrekt borttagning av egendom från alla samlingar. |
| [Save](../../aspose.email.mapi/mapicontact/save#save)(Stream) | Sparar detta[`MapiContact`](../mapicontact) in i den givna strömmen med vCard-format. Den vCard-version som stöds är 2.1 |
| [Save](../../aspose.email.mapi/mapicontact/save#save_3)(string) | Sparar detta[`MapiContact`](../mapicontact) till vCard-filen med ett standardalternativ. Den vCard-version som stöds är 2.1 |
| [Save](../../aspose.email.mapi/mapicontact/save#save_1)(Stream, ContactSaveFormat) | Sparar detta[`MapiContact`](../mapicontact) till den givna strömmen med ett format som använder standardalternativen. Det sparade formatet som stöds är vCard |
| [Save](../../aspose.email.mapi/mapicontact/save#save_2)(Stream, ContactSaveOptions) | Sparar detta[`MapiContact`](../mapicontact) till den givna strömmen med angivna sparalternativ. De sparade alternativen som stöds är[`VCardSaveOptions`](../../aspose.email.personalinfo.vcard/vcardsaveoptions) |
| [Save](../../aspose.email.mapi/mapicontact/save#save_4)(string, ContactSaveFormat) | Sparar detta[`MapiContact`](../mapicontact)till den angivna filen med ett format som använder standardalternativen. Det sparade formatet som stöds är vCard. |
| [Save](../../aspose.email.mapi/mapicontact/save#save_5)(string, ContactSaveOptions) | Sparar detta[`MapiContact`](../mapicontact) till fil med angivna sparaalternativ. De sparade alternativen som stöds är[`VCardSaveOptions`](../../aspose.email.personalinfo.vcard/vcardsaveoptions) |
| override [SetBodyContent](../../aspose.email.mapi/mapicontact/setbodycontent#setbodycontent)(string, BodyContentType) | Ställer in innehållet i brödtexten. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType, bool) | Ställer in innehållet i brödtexten. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf)(string, bool) | Hämtar eller ställer in den RTF-formaterade meddelandetexten. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags)(MapiMessageFlags) | Ställer in meddelandeflaggor. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | Anger egenskapen. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty)(PropertyDescriptor, object) | Ställer in MAPI-egenskapen. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | Försök att hämta egenskapsdata med angiven taggnyckel. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | Hämtar värdet för den angivna egenskapen som DateTime-typ. Ett returvärde anger om operationen lyckades. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | Hämtar värdet för den angivna egenskapen som Int32-typ. Ett returvärde anger om operationen lyckades. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | Hämtar värdet för den angivna egenskapen som lång typ. Ett returvärde anger om operationen lyckades. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | Försök att få en egenskapsdata som sträng med specificerad tagg. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | Försök att få en egenskapsdata som sträng med specificerad tagg och teckentabell. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | Hämtar värdet för den angivna egenskapen som strängtyp. Ett returvärde anger om operationen lyckades. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | Hämtar värdet för den angivna egenskapen som strängtyp. Ett returvärde anger om operationen lyckades. |

### Se även

* class [MapiMessageItemBase](../mapimessageitembase)
* namnutrymme [Aspose.Email.Mapi](../../aspose.email.mapi)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
