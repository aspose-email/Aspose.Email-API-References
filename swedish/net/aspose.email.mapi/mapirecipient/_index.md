---
title: MapiRecipient
second_title: Aspose.Email för .NET API-referens
description: Representerar mottagarens information i Microsoft Outlook-meddelandet.
type: docs
weight: 18620
url: /sv/net/aspose.email.mapi/mapirecipient/
---
## MapiRecipient class

Representerar mottagarens information i Microsoft Outlook-meddelandet.

```csharp
public class MapiRecipient : MapiPropertyContainer
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AddressType](../../aspose.email.mapi/mapirecipient/addresstype) { get; } | Hämtar typen av adress till meddelandemottagaren eller avsändaren. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Hämtar teckentabellen. |
| [Content](../../aspose.email.mapi/mapirecipient/content) { get; } | Hämtar innehållet. |
| [DisplayName](../../aspose.email.mapi/mapirecipient/displayname) { get; set; } | Hämtar eller ställer in visningsnamnet för meddelandet mottagare eller avsändare. |
| [EmailAddress](../../aspose.email.mapi/mapirecipient/emailaddress) { get; set; } | Hämtar eller ställer in e-postadressen till meddelandemottagaren eller avsändaren. |
| [NamedProperties](../../aspose.email.mapi/mapirecipient/namedproperties) { get; } | Hämtar de namngivna egenskaperna för meddelandet. |
| [OrganizationEmailAddress](../../aspose.email.mapi/mapirecipient/organizationemailaddress) { get; } | Hämtar organisationens e-postadress. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Hämtar samlingen av egenskaper. |
| [PropertyStream](../../aspose.email.mapi/mapirecipient/propertystream) { get; } | Hämtar egenskapsströmmen. |
| [RecipientClass](../../aspose.email.mapi/mapirecipient/recipientclass) { get; } | Hämtar typen av recept. |
| [RecipientTrackStatus](../../aspose.email.mapi/mapirecipient/recipienttrackstatus) { get; set; } | Status för mottagarens svar på en mötesförfrågan. |
| [RecipientType](../../aspose.email.mapi/mapirecipient/recipienttype) { get; } | Hämtar typen av mottagare eller avsändare. |
| [SubStorages](../../aspose.email.mapi/mapirecipient/substorages) { get; } | Hämtar underlagringarna. |

## Metoder

| namn | Beskrivning |
| --- | --- |
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
