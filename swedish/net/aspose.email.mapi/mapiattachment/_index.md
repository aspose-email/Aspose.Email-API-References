---
title: MapiAttachment
second_title: Aspose.Email för .NET API-referens
description: Representerar bilagan i e-postmeddelandet.
type: docs
weight: 17880
url: /sv/net/aspose.email.mapi/mapiattachment/
---
## MapiAttachment class

Representerar bilagan i e-postmeddelandet.

```csharp
public class MapiAttachment : MapiPropertyContainer
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BinaryData](../../aspose.email.mapi/mapiattachment/binarydata) { get; set; } | Hämtar eller ställer in binära bifogade data. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Hämtar teckentabellen. |
| [Content](../../aspose.email.mapi/mapiattachment/content) { get; } | Hämtar innehållet. |
| [DisplayName](../../aspose.email.mapi/mapiattachment/displayname) { get; } | Hämtar visningsnamnet på ole-objektet i en bilaga. |
| [Extension](../../aspose.email.mapi/mapiattachment/extension) { get; } | Får ett filnamnstillägg som anger dokumenttypen för en bilaga. |
| [FileName](../../aspose.email.mapi/mapiattachment/filename) { get; } | Hämtar en bilagas basfilnamn och filtillägg, exklusive sökväg. |
| virtual [ItemId](../../aspose.email.mapi/mapiattachment/itemid) { get; } | Artikel-id, används med en server |
| [LongFileName](../../aspose.email.mapi/mapiattachment/longfilename) { get; } | Får en bilagas långa filnamn och filtillägg, exklusive sökväg. |
| [MimeTag](../../aspose.email.mapi/mapiattachment/mimetag) { get; } | Får formateringsinformation om en Multipurpose Internet Mail Extensions (MIME)-bilaga. |
| [NamedProperties](../../aspose.email.mapi/mapiattachment/namedproperties) { get; } | Hämtar de namngivna egenskaperna för meddelandet. |
| [ObjectData](../../aspose.email.mapi/mapiattachment/objectdata) { get; } | Får ett bifogat objekt som vanligtvis nås via OLE IStorage-gränssnittet. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Hämtar samlingen av egenskaper. |
| [PropertyStream](../../aspose.email.mapi/mapiattachment/propertystream) { get; } | Hämtar egenskapsströmmen. |
| [SubStorages](../../aspose.email.mapi/mapiattachment/substorages) { get; } | Hämtar underlagringarna. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [GetProperty](../../aspose.email.mapi/mapiattachment/getproperty)(PropertyDescriptor) | Hämtar MAPI-egenskap efter egenskapsbeskrivning. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Hämtar värdet för egenskapen som anges av taggen som boolesk typ. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Hämtar strängvärdet för egenskapen som anges av taggen. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Hämtar värdet för egenskapen specificerad av taggen som DateTime type. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Hämtar int32-värdet för egenskapen som anges av taggen. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Hämtar värdet för egenskapen specificerad av taggen som Long (int64) type. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Hämtar värdet för egenskapen som anges av taggen som Short type. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Hämtar strängvärdet för egenskapen som anges av taggen. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Hämtar strängvärdet för egenskapen som anges av taggen. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Bestämmer om strängegenskaper är Unicode-kodade eller inte. |
| [RemoveProperty](../../aspose.email.mapi/mapiattachment/removeproperty)(long) | Ger korrekt borttagning av egendom från alla samlingar. |
| [Save](../../aspose.email.mapi/mapiattachment/save#save)(Stream) | Spara bilagans innehåll. |
| [Save](../../aspose.email.mapi/mapiattachment/save#save_1)(string) | Spara bilagans innehåll. |
| override [SetProperty](../../aspose.email.mapi/mapiattachment/setproperty#setproperty)(MapiProperty) | Anger egenskapen. |
| override [SetProperty](../../aspose.email.mapi/mapiattachment/setproperty#setproperty_1)(PropertyDescriptor, object) | Ställer in MAPI-egenskapen. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | Försök att hämta egenskapsdata med angiven taggnyckel. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | Hämtar värdet för den angivna egenskapen som DateTime-typ. Ett returvärde anger om operationen lyckades. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | Hämtar värdet för den angivna egenskapen som Int32-typ. Ett returvärde anger om operationen lyckades. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | Hämtar värdet för den angivna egenskapen som lång typ. Ett returvärde anger om operationen lyckades. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | Försök att få en egenskapsdata som sträng med specificerad tagg. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | Försök att få en egenskapsdata som sträng med specificerad tagg och teckentabell. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | Hämtar värdet för den angivna egenskapen som strängtyp. Ett returvärde anger om operationen lyckades. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | Hämtar värdet för den angivna egenskapen som strängtyp. Ett returvärde anger om operationen lyckades. |

### Se även

* class [MapiPropertyContainer](../mapipropertycontainer)
* namnutrymme [Aspose.Email.Mapi](../../aspose.email.mapi)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
