---
title: QueryType
second_title: Aspose.Email för .NET API-referens
description: Anger nyckelorden som ska användas för att matcha posterna i butiken som söks efter. Värdet på frågan används som ett prefix-strängmatchningsmönster och returnerar poster som matchar början av strängen. Till exempel sökning efter John skulle matcha John Frum eller Barry Johnson men skulle inte matcha James Littlejohn. Alla icke-tomma textegenskaper i GAL som indexeras med hjälp av ANR jämförs med Query-elementet värde. Sökjämförelser utförs genom att använda skiftlägesokänslig matchning. För en Windows SharePoint Services-dokumentbibliotekssökning stöder detta protokoll frågor i följande form LinkId  värde där värdet anger webbadressen till objektet eller mappen och LinkId indikerar att värdet ska jämföras med länk-ID-egenskapen. För postlådesökning är frågesyntaxen följande - Mappar kan anges på följande sätt Specificerad ID Specificerad mapp och undermappar Alla e-postmappar inklusive utkast Inkorg och undermappar Utkorg och Skickade objekt - Den grundläggande sökordsfrågan kan bestå av följande Grundoperatorn Och avsnitt 2.2.3.10 Ett dateTime-filter som specificeras med hjälp av GreaterThan avsnitt 2.2.3.Than och Less. element avsnitt 2.2.3.87 Fritextelement avsnitt 2.2.3.73 som innehåller nyckelord Den grundläggande sökordsfrågan körs mot alla indexerade egenskaper.
type: docs
weight: 1780
url: /sv/net/aspose.email.clients.activesync.transportlayer/querytype/
---
## QueryType class

Anger nyckelorden som ska användas för att matcha posterna i butiken som söks efter. Värdet på frågan används som ett prefix-strängmatchningsmönster och returnerar poster som matchar början av strängen. Till exempel, sökning efter "John" skulle matcha "John Frum" eller "Barry Johnson", men skulle inte matcha "James Littlejohn". Alla icke-tomma textegenskaper i GAL som indexeras med hjälp av ANR jämförs med Query-elementet värde. Sökjämförelser utförs genom att använda skiftlägesokänslig matchning. För en Windows SharePoint Services-dokumentbibliotekssökning stöder detta protokoll frågor i följande form: LinkId == värde, där värdet anger webbadressen till objektet eller mappen och LinkId indikerar att värdet ska jämföras med länk-ID-egenskapen. För postlådesökning är frågesyntaxen följande: - Mappar kan anges på följande sätt: Specificerad ID Specificerad mapp och undermappar Alla e-postmappar, inklusive utkast, Inkorg och undermappar, Utkorg och Skickade objekt - Den grundläggande sökordsfrågan kan bestå av följande: Grundoperatorn: Och (avsnitt 2.2.3.10) Ett dateTime-filter som specificeras med hjälp av GreaterThan (avsnitt 2.2.3.Than) och Less. element (avsnitt 2.2.3.87) Fritextelement (avsnitt 2.2.3.73) som innehåller nyckelord Den grundläggande sökordsfrågan körs mot alla indexerade egenskaper.

```csharp
public class QueryType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [QueryType](querytype)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Class](../../aspose.email.clients.activesync.transportlayer/querytype/class) { get; } | Identifierar klassen för objektet. De giltiga airsync:Class-elementvärdena är: - Tasks - Email - Calendar - Contacts - Notes 0 är SMS 0-versionen av sökning, e-post, e-post, e-post, 1- och e-post: Kontakter, uppgifter. SMS- och Notes-klasserna är endast tillgängliga om protokollversionen är 14.0 eller 14.1. Sökbegäran kan inkludera ett eller flera klasselement i begäran för att begränsa typen av data som ingår i söksvaret. Om ett eller flera klasselement inte ingår i sökbegäran kommer servern att returnera alla klasser som stöds. Om klassen ingår som ett underordnat element till något annat än elementet And, svarar servern med ett statusvärde på 8 (SearchTooComplex). |
| [CollectionId](../../aspose.email.clients.activesync.transportlayer/querytype/collectionid) { get; } | Anger i vilken mapp det ska sökas. Om DeepTraversal finns, gäller det alla mappar under varje CollectionId. Om CollectionId ingår som ett underordnat element än And, svarar servern med ett statusvärde på 8 (SearchTooComplex). |
| [ConversationId](../../aspose.email.clients.activesync.transportlayer/querytype/conversationid) { get; set; } | Anger konversationen som ska sökas efter. Värdet är ett GUID. ConversationId stöds inte när protokollversionen är 12.1. Om ConversationId ingår som ett underordnat element till något annat element än And-elementet, svarar servern med ett statusvärde på 8 (SearchTooComplex). |
| [FreeText](../../aspose.email.clients.activesync.transportlayer/querytype/freetext) { get; set; } | Anger ett strängvärde som det ska sökas efter. Om FreeText-egenskapen är inställd på annat sätt än egenskapen And, svarar servern med ett statusvärde på 8 (SearchTooComplex). |
| [GreaterThan](../../aspose.email.clients.activesync.transportlayer/querytype/greaterthan) { get; set; } | Anger en egenskap och ett värde som jämförs för ett "Större än"-villkor under en sökning. |
| [LessThan](../../aspose.email.clients.activesync.transportlayer/querytype/lessthan) { get; set; } | Anger en egenskap och ett värde som jämförs för ett "Mindre än"-villkor under en sökning. |

### Se även

* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
