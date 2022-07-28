---
title: PidTagPropertyDescriptor
second_title: Aspose.Email för .NET API-referens
description: Klassen innehåller egenskapsbeskrivningsinformation.
type: docs
weight: 18990
url: /sv/net/aspose.email.mapi/pidtagpropertydescriptor/
---
## PidTagPropertyDescriptor class

Klassen innehåller egenskapsbeskrivningsinformation.

```csharp
public class PidTagPropertyDescriptor : PropertyDescriptor
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_1)(long) | Initierar en ny instans av[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class En egenskap som definieras av ett 16-bitars egenskaps-ID och en 16-bitars egenskapstyp. Egenskaps-ID för en taggad egendom är i intervallet 0x001 � 0x7FFF. Egenskaps-ID:n i intervallet 0x8000 � 0x8FFF är reserverade för tilldelning till namngivna egenskaper |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor)(int, PropertyDataType) | Initierar en ny instans av[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class En egenskap som definieras av ett 16-bitars egenskaps-ID och en 16-bitars egenskapstyp. Egenskaps-ID för en taggad egendom är i intervallet 0x001 � 0x7FFF. Egenskaps-ID:n i intervallet 0x8000 � 0x8FFF är reserverade för tilldelning till namngivna egenskaper |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_2)(string, int, PropertyDataType) | Initierar en ny instans av[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class En egenskap som definieras av ett 16-bitars egenskaps-ID och en 16-bitars egenskapstyp. Egenskaps-ID för en taggad egendom är i intervallet 0x001 � 0x7FFF. Egenskaps-ID:n i intervallet 0x8000 � 0x8FFF är reserverade för tilldelning till namngivna egenskaper |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_4)(string, string, long) | Initierar en ny instans av[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class En egenskap som definieras av ett 16-bitars egenskaps-ID och en 16-bitars egenskapstyp. Egenskaps-ID för en taggad egendom är i intervallet 0x001 � 0x7FFF. Egenskaps-ID:n i intervallet 0x8000 � 0x8FFF är reserverade för tilldelning till namngivna egenskaper |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_3)(string, string, int, PropertyDataType) | Initierar en ny instans av[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class En egenskap som definieras av ett 16-bitars egenskaps-ID och en 16-bitars egenskapstyp. Egenskaps-ID för en taggad egendom är i intervallet 0x001 � 0x7FFF. Egenskaps-ID:n i intervallet 0x8000 � 0x8FFF är reserverade för tilldelning till namngivna egenskaper |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CanonicalName](../../aspose.email.mapi/propertydescriptor/canonicalname) { get; } | Namnet som används för att referera till egenskapen i dokumentationen. Prefixet för det kanoniska namnet identifierar de grundläggande egenskaperna hos en egenskap för implementeraren. Den kanoniska namnstrukturen använder tre kategorier som betecknas med följande prefix till det kanoniska egenskapsnamnet: * PidLid-prefix: Egenskaper identifierade av en osignerad 32-bitars kvantitet tillsammans med en egenskapsuppsättning. * PidName-prefix: Egenskaper identifierade med ett strängnamn tillsammans med en egenskapsuppsättning. * PidTag-prefix: Egenskaper identifierade av en osignerad 16-bitars kvantitet. |
| [DataType](../../aspose.email.mapi/propertydescriptor/datatype) { get; } | Egenskapsvärdetypen, som beskrivs i [MS-OXCDATA], som anger vilken typ av värden som är tillåtna för egenskapen. |
| [Id](../../aspose.email.mapi/pidtagpropertydescriptor/id) { get; } | Får en osignerad 16-bitars kvantitet som identifierar en taggad egenskap. Egenskaps-ID:n är inte nödvändigtvis unika. Med undantag för egenskaps-ID:n i intervallet från 0x6800 till 0x7BFF, är kombinationen av egenskaps-ID och datatyp unika. Egenskaps-ID:n i intervallet 0x6800 till 0x7BFF definieras av meddelandeklassen. |
| [MultipleValuesDataType](../../aspose.email.mapi/propertydescriptor/multiplevaluesdatatype) { get; } | Indikerar om datatypen innehåller flera värden |
| [Name](../../aspose.email.mapi/propertydescriptor/name) { get; } | Får en sträng som identifierar en egenskap. |
| [Tag](../../aspose.email.mapi/pidtagpropertydescriptor/tag) { get; } | En egenskapstagg är ett 32-bitars nummer som innehåller en unik egenskapsidentifierare i bitarna 16 till 31 och en egenskapstyp i bitarna 0 till 15. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.email.mapi/pidtagpropertydescriptor/equals#equals_1)(object) | Bestämmer om det angivna System.Object är lika med det aktuella System.Object. |
| override [Equals](../../aspose.email.mapi/pidtagpropertydescriptor/equals#equals)(PropertyDescriptor) | Indikerar om det aktuella objektet är lika med ett annat objekt av samma typ. |
| override [GetHashCode](../../aspose.email.mapi/pidtagpropertydescriptor/gethashcode)() | Fungerar som en hashfunktion för en typ. |
| override [ToString](../../aspose.email.mapi/pidtagpropertydescriptor/tostring)() | Returnerar en sträng som representerar egenskapsbeskrivningen. |
| [operator ==](../../aspose.email.mapi/pidtagpropertydescriptor/op_equality) | Bestämmer om de angivna objekten är lika med varandra. |
| [explicit operator](../../aspose.email.mapi/pidtagpropertydescriptor/op_explicit) | Konverterar taggvärde till taggad property |
| [operator !=](../../aspose.email.mapi/pidtagpropertydescriptor/op_inequality) | Bestämmer om de angivna objekten inte är lika med varandra. |

### Se även

* class [PropertyDescriptor](../propertydescriptor)
* namnutrymme [Aspose.Email.Mapi](../../aspose.email.mapi)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
