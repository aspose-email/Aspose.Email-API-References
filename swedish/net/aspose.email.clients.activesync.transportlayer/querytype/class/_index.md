---
title: Class
second_title: Aspose.Email för .NET API-referens
description: Identifierar klassen för objektet. De giltiga airsyncClass-elementvärdena är - Tasks - Email - Calendar - Contacts - Notes 0 är SMS 0-versionen av sökning e-post e-post e-post 1- och e-post Kontakter uppgifter. SMS- och Notes-klasserna är endast tillgängliga om protokollversionen är 14.0 eller 14.1. Sökbegäran kan inkludera ett eller flera klasselement i begäran för att begränsa typen av data som ingår i söksvaret. Om ett eller flera klasselement inte ingår i sökbegäran kommer servern att returnera alla klasser som stöds. Om klassen ingår som ett underordnat element till något annat än elementet And svarar servern med ett statusvärde på 8 SearchTooComplex.
type: docs
weight: 20
url: /sv/net/aspose.email.clients.activesync.transportlayer/querytype/class/
---
## QueryType.Class property

Identifierar klassen för objektet. De giltiga airsync:Class-elementvärdena är: - Tasks - Email - Calendar - Contacts - Notes 0 är SMS 0-versionen av sökning, e-post, e-post, e-post, 1- och e-post: Kontakter, uppgifter. SMS- och Notes-klasserna är endast tillgängliga om protokollversionen är 14.0 eller 14.1. Sökbegäran kan inkludera ett eller flera klasselement i begäran för att begränsa typen av data som ingår i söksvaret. Om ett eller flera klasselement inte ingår i sökbegäran kommer servern att returnera alla klasser som stöds. Om klassen ingår som ett underordnat element till något annat än elementet And, svarar servern med ett statusvärde på 8 (SearchTooComplex).

```csharp
public List<AirsyncClass> Class { get; }
```

### Se även

* enum [AirsyncClass](../../airsyncclass)
* class [QueryType](../../querytype)
* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../querytype)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->