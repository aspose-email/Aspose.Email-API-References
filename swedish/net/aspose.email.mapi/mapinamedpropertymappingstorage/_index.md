---
title: MapiNamedPropertyMappingStorage
second_title: Aspose.Email för .NET API-referens
description: Representerar den namngivna egenskapsmapping
type: docs
weight: 18520
url: /sv/net/aspose.email.mapi/mapinamedpropertymappingstorage/
---
## MapiNamedPropertyMappingStorage class

Representerar den namngivna egenskapsmapping

```csharp
public sealed class MapiNamedPropertyMappingStorage : MapiPropertyContainer
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [MapiNamedPropertyMappingStorage](mapinamedpropertymappingstorage)() | Initierar en ny instans av[`MapiNamedPropertyMappingStorage`](../mapinamedpropertymappingstorage) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Hämtar teckentabellen. |
| [Content](../../aspose.email.mapi/mapinamedpropertymappingstorage/content) { get; } | Hämtar innehållet |
| [Name](../../aspose.email.mapi/mapinamedpropertymappingstorage/name) { get; } | Får namnet |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Hämtar samlingen av egenskaper. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddNamedPropertyMapping](../../aspose.email.mapi/mapinamedpropertymappingstorage/addnamedpropertymapping#addnamedpropertymapping)(MapiProperty, long, Guid) | Lägger till den namngivna egenskapsmappingen för numerisk namngiven egenskap. |
| [AddNamedPropertyMapping](../../aspose.email.mapi/mapinamedpropertymappingstorage/addnamedpropertymapping#addnamedpropertymapping_1)(MapiProperty, string, Guid) | Lägger till den namngivna egenskapsmappingen för strängen med namnet egenskap. |
| [GetNextAvailablePropertyId](../../aspose.email.mapi/mapinamedpropertymappingstorage/getnextavailablepropertyid)(MapiPropertyType) | Hämtar nästa tillgängliga egenskaps-id i postström baserat på egenskapsdatatyp. |
| virtual [GetProperty](../../aspose.email.mapi/mapipropertycontainer/getproperty)(PropertyDescriptor) | Hämtar MAPI-egenskap efter egenskapsbeskrivning. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Hämtar värdet för egenskapen som anges av taggen som boolesk typ. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Hämtar strängvärdet för egenskapen som anges av taggen. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Hämtar värdet för egenskapen specificerad av taggen som DateTime type. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Hämtar int32-värdet för egenskapen som anges av taggen. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Hämtar värdet för egenskapen specificerad av taggen som Long (int64) type. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Hämtar värdet för egenskapen som anges av taggen som Short type. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Hämtar strängvärdet för egenskapen som anges av taggen. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Hämtar strängvärdet för egenskapen som anges av taggen. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Bestämmer om strängegenskaper är Unicode-kodade eller inte. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | Anger egenskapen. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(PropertyDescriptor, object) | Ställer in MAPI-egenskapen. |
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
