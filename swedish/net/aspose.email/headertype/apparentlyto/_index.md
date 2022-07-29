---
title: ApparentlyTo
second_title: Aspose.Email för .NET API-referens
description: Infogas genom att skicka e-post när det inte finns någon Till-mottagare i det ursprungliga meddelandet. Detta gör att mottagarna som kommer från kuvertet listas i meddelanderubriken. Det här beteendet är inte riktigt korrekt MTAer bör inte modifiera rubriker förutom att infoga mottagna rader och det kan i vissa fall göra att hemlig kopia-mottagare felaktigt avslöjas till icke-hemlig kopia-mottagare. Exempel Apparently-To someonesomedomain.com Icke-standardhuvud som inte används nämnt i RFC1211.
type: docs
weight: 10
url: /sv/net/aspose.email/headertype/apparentlyto/
---
## HeaderType.ApparentlyTo property

Infogas genom att skicka e-post när det inte finns någon "Till:"-mottagare i det ursprungliga meddelandet. Detta gör att mottagarna som kommer från kuvertet listas i meddelanderubriken. Det här beteendet är inte riktigt korrekt, MTA:er bör inte modifiera rubriker (förutom att infoga mottagna rader), och det kan i vissa fall göra att hemlig kopia-mottagare felaktigt avslöjas till icke-hemlig kopia-mottagare. Exempel: Apparently-To: someone@somedomain.com Icke-standardhuvud som inte används, nämnt i RFC1211.

```csharp
public static HeaderType ApparentlyTo { get; }
```

### Se även

* class [HeaderType](../../headertype)
* namnutrymme [Aspose.Email](../../headertype)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->