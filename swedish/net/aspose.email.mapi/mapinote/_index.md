---
title: MapiNote
second_title: Aspose.Email för .NET API-referens
description: Representerar outlook Note-objekt sticky note
type: docs
weight: 18530
url: /sv/net/aspose.email.mapi/mapinote/
---
## MapiNote class

Representerar outlook Note-objekt ("sticky note")

```csharp
public sealed class MapiNote : MapiMessageItemBase
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [MapiNote](mapinote#constructor)() | Initierar en ny instans av[`MapiNote`](../mapinote) class. |
| [MapiNote](mapinote#constructor_1)(string, string) | Initierar en ny instans av[`MapiNote`](../mapinote) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapimessageitembase/attachments) { get; } | Hämtar bilagorna i meddelandet. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Innehåller faktureringsinformation som är kopplad till en artikel. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | Hämtar meddelandetexten. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Får[`BodyRtf`](../mapimessageitembase/bodyrtf) av meddelandet konverterat till HTML, om det finns, annars en tom sträng. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Hämtar eller ställer in den RTF-formaterade meddelandetexten. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Hämtar typen av kroppen. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Innehåller nyckelord eller kategorier för meddelandeobjektet. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Hämtar teckentabellen. |
| [Color](../../aspose.email.mapi/mapinote/color) { get; set; } | Hämtar eller ställer in den föreslagna bakgrundsfärgen för Note-objektet |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Innehåller namnen på de företag som är associerade med en vara. |
| [CreationDate](../../aspose.email.mapi/mapinote/creationdate) { get; set; } | Hämtar eller ställer in datum för skapande av not |
| [Height](../../aspose.email.mapi/mapinote/height) { get; set; } | Hämtar eller ställer in höjden på det synliga meddelandefönstret i pixels |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | Artikel-id, används med en server |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Får en skiftlägeskänslig sträng som identifierar den avsändardefinierade meddelandeklassen, till exempel IPM.Note. Meddelandeklassen anger typen, syftet eller innehållet för meddelandet. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Innehåller information om körsträcka som är associerad med en artikel. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Hämtar de namngivna egenskaperna för meddelandet. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Hämtar den namngivna egenskapsmappingen. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Hämtar samlingen av egenskaper. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Hämtar egenskapsströmmen. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Hämtar mottagarna av meddelandet. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Får känsligheten. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Hämtar eller ställer in ämnet för meddelandet. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Får ett ämnesprefix som vanligtvis indikerar någon åtgärd på ett meddelande, till exempel "FW: " för vidarebefordran. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Hämtar underlagringarna. |
| [Width](../../aspose.email.mapi/mapinote/width) { get; set; } | Hämtar eller ställer in bredden på det synliga meddelandefönstret i pixels |
| [XPosition](../../aspose.email.mapi/mapinote/xposition) { get; set; } | Hämtar eller ställer in avståndet, i pixlar, från den vänstra kanten av skärmen som ett användargränssnitt visar ett Note-objekt |
| [YPosition](../../aspose.email.mapi/mapinote/yposition) { get; set; } | Hämtar eller ställer in avståndet, i pixlar, från den övre kanten av skärmen som ett användargränssnitt visar ett Note-objekt |

## Metoder

| namn | Beskrivning |
| --- | --- |
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
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Bestämmer om strängegenskaper är Unicode-kodade eller inte. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | Ger korrekt borttagning av egendom från alla samlingar. |
| [Save](../../aspose.email.mapi/mapinote/save#save)(Stream, NoteSaveFormat) | Sparar detta[`MapiNote`](../mapinote) till den givna strömmen med angivet format. |
| [Save](../../aspose.email.mapi/mapinote/save#save_1)(string, NoteSaveFormat) | Sparar detta[`MapiNote`](../mapinote) till fil med angivet format. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType) | Ställer in innehållet i brödtexten. |
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
