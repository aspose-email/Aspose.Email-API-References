---
title: DataContainer
second_title: Aspose.Email för .NET API-referens
description: Innehåller data för ett visst objekt till exempel en kontakt e-postmeddelande kalendermöte eller uppgiftsobjekt. DataContainern kan användas för att ändra objekt lägga till objekt eller hämta objekt på klientenheten eller servern.
type: docs
weight: 1150
url: /sv/net/aspose.email.clients.activesync.transportlayer/datacontainer/
---
## DataContainer class

Innehåller data för ett visst objekt, till exempel en kontakt, e-postmeddelande, kalendermöte eller uppgiftsobjekt. DataContainern kan användas för att ändra objekt, lägga till objekt eller hämta objekt på klientenheten eller servern.

```csharp
public class DataContainer : IEnumerable
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [DataContainer](datacontainer#constructor)(string, Namespace) | Initierar en ny instans av DataContainer-klassen. |
| [DataContainer](datacontainer#constructor_1)(string, Namespace, DataContainer) | Initierar en ny instans av DataContainer-klassen. |
| [DataContainer](datacontainer#constructor_2)(string, Namespace, DataContainer, string) | Initierar en ny instans av DataContainer-klassen. |
| [DataContainer](datacontainer#constructor_3)(string, Namespace, DataContainer, string, bool) | Initierar en ny instans av DataContainer-klassen. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BinaryData](../../aspose.email.clients.activesync.transportlayer/datacontainer/binarydata) { get; set; } | Anger om data är binär. |
| [ElementName](../../aspose.email.clients.activesync.transportlayer/datacontainer/elementname) { get; } | Namnet på elementet vars data finns i databehållaren. |
| [Item](../../aspose.email.clients.activesync.transportlayer/datacontainer/item) { get; } | Hämtar DataContainer för valt element Om mängden DataContainers mer än en, ökar AsposeException. (15 indexers) |
| [Namespace](../../aspose.email.clients.activesync.transportlayer/datacontainer/namespace) { get; } | Namnutrymme för elementet, vars data finns i databehållaren. |
| [Parent](../../aspose.email.clients.activesync.transportlayer/datacontainer/parent) { get; } | Parent DataContainer |
| [Prefix](../../aspose.email.clients.activesync.transportlayer/datacontainer/prefix) { get; } | Prefix i xml-noden för elementet |
| [SubItems](../../aspose.email.clients.activesync.transportlayer/datacontainer/subitems) { get; } | Kopierar underelementen i ApplicationData till en ny lista. |
| [Value](../../aspose.email.clients.activesync.transportlayer/datacontainer/value) { get; set; } | Värdet för elementet |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_3)(string) | Lägger till data för element i xml-format till DataContainer. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_4)(XmlNode) | Lägger till data för element i xml-format till DataContainer. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add)(int, Namespace) | Lägger till tom DataContainer för element. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_1)(int, string, Namespace) | Lägger till data från element till DataContainer. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_2)(int, string, bool, Namespace) | Lägger till data från element till DataContainer. |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist)(AirSync) | Hämtar lista över databehållare för valt element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_1)(AirSyncBase) | Hämtar lista över databehållare för valt element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_2)(Calendar) | Hämtar lista över databehållare för valt element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_3)(Contacts) | Hämtar lista över databehållare för valt element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_4)(Contacts2) | Hämtar lista över databehållare för valt element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_5)(DocumentLibrary) | Hämtar lista över databehållare för valt element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_6)(Email) | Hämtar lista över databehållare för valt element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_7)(Email2) | Hämtar lista över databehållare för valt element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_8)(GAL) | Hämtar lista över databehållare för valt element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_9)(ItemOperations) | Hämtar lista över databehållare för valt element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_10)(Notes) | Hämtar lista över databehållare för valt element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_11)(RightsManagement) | Hämtar lista över databehållare för valt element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_12)(Search) | Hämtar lista över databehållare för valt element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_13)(Settings) | Hämtar lista över databehållare för valt element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_14)(Tasks) | Hämtar lista över databehållare för valt element |
| [GetEnumerator](../../aspose.email.clients.activesync.transportlayer/datacontainer/getenumerator)() | Returnerar en uppräkning som itererar genom samlingen. |
| override [ToString](../../aspose.email.clients.activesync.transportlayer/datacontainer/tostring)() | Returnerar en sträng som representerar det aktuella objektet. |

### Se även

* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
