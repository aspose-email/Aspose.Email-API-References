---
title: DataContainer
second_title: Aspose.Email für .NET-API-Referenz
description: Enthält Daten für ein bestimmtes Objekt z. B. einen Kontakt eine E-Mail-Nachricht einen Kalendertermin oder ein Aufgabenelement. Der DataContainer kann verwendet werden um Elemente zu ändern Elemente hinzuzufügen oder Elemente auf dem Clientgerät oder Server abzurufen.
type: docs
weight: 1150
url: /de/net/aspose.email.clients.activesync.transportlayer/datacontainer/
---
## DataContainer class

Enthält Daten für ein bestimmtes Objekt, z. B. einen Kontakt, eine E-Mail-Nachricht, einen Kalendertermin oder ein Aufgabenelement. Der DataContainer kann verwendet werden, um Elemente zu ändern, Elemente hinzuzufügen oder Elemente auf dem Clientgerät oder Server abzurufen.

```csharp
public class DataContainer : IEnumerable
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [DataContainer](datacontainer#constructor)(string, Namespace) | Initialisiert eine neue Instanz der DataContainer-Klasse. |
| [DataContainer](datacontainer#constructor_1)(string, Namespace, DataContainer) | Initialisiert eine neue Instanz der DataContainer-Klasse. |
| [DataContainer](datacontainer#constructor_2)(string, Namespace, DataContainer, string) | Initialisiert eine neue Instanz der DataContainer-Klasse. |
| [DataContainer](datacontainer#constructor_3)(string, Namespace, DataContainer, string, bool) | Initialisiert eine neue Instanz der DataContainer-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BinaryData](../../aspose.email.clients.activesync.transportlayer/datacontainer/binarydata) { get; set; } | Gibt an, ob Daten binär sind. |
| [ElementName](../../aspose.email.clients.activesync.transportlayer/datacontainer/elementname) { get; } | Name des Elements, dessen Daten im Datencontainer enthalten sind. |
| [Item](../../aspose.email.clients.activesync.transportlayer/datacontainer/item) { get; } | Holt DataContainer für ausgewähltes Element Wenn die Anzahl der DataContainer größer als eins ist, steigt AsposeException. (15 indexers) |
| [Namespace](../../aspose.email.clients.activesync.transportlayer/datacontainer/namespace) { get; } | NameSpace des Elements, dessen Daten im Datencontainer enthalten sind. |
| [Parent](../../aspose.email.clients.activesync.transportlayer/datacontainer/parent) { get; } | Übergeordneter DataContainer |
| [Prefix](../../aspose.email.clients.activesync.transportlayer/datacontainer/prefix) { get; } | Präfix im XML-Knoten für das Element |
| [SubItems](../../aspose.email.clients.activesync.transportlayer/datacontainer/subitems) { get; } | Kopiert die Unterelemente der ApplicationData in eine neue Liste. |
| [Value](../../aspose.email.clients.activesync.transportlayer/datacontainer/value) { get; set; } | Wert des Elements |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_3)(string) | Fügt Daten des Elements im XML-Format zum DataContainer hinzu. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_4)(XmlNode) | Fügt Daten des Elements im XML-Format zum DataContainer hinzu. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add)(int, Namespace) | Fügt leeren DataContainer für Element hinzu. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_1)(int, string, Namespace) | Fügt Daten des Elements zum DataContainer hinzu. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_2)(int, string, bool, Namespace) | Fügt Daten des Elements zum DataContainer hinzu. |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist)(AirSync) | Ruft die Liste der DataContainer für das ausgewählte Element ab |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_1)(AirSyncBase) | Ruft die Liste der DataContainer für das ausgewählte Element ab |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_2)(Calendar) | Ruft die Liste der DataContainer für das ausgewählte Element ab |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_3)(Contacts) | Ruft die Liste der DataContainer für das ausgewählte Element ab |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_4)(Contacts2) | Ruft die Liste der DataContainer für das ausgewählte Element ab |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_5)(DocumentLibrary) | Ruft die Liste der DataContainer für das ausgewählte Element ab |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_6)(Email) | Ruft die Liste der DataContainer für das ausgewählte Element ab |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_7)(Email2) | Ruft die Liste der DataContainer für das ausgewählte Element ab |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_8)(GAL) | Ruft die Liste der DataContainer für das ausgewählte Element ab |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_9)(ItemOperations) | Ruft die Liste der DataContainer für das ausgewählte Element ab |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_10)(Notes) | Ruft die Liste der DataContainer für das ausgewählte Element ab |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_11)(RightsManagement) | Ruft die Liste der DataContainer für das ausgewählte Element ab |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_12)(Search) | Ruft die Liste der DataContainer für das ausgewählte Element ab |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_13)(Settings) | Ruft die Liste der DataContainer für das ausgewählte Element ab |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_14)(Tasks) | Ruft die Liste der DataContainer für das ausgewählte Element ab |
| [GetEnumerator](../../aspose.email.clients.activesync.transportlayer/datacontainer/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| override [ToString](../../aspose.email.clients.activesync.transportlayer/datacontainer/tostring)() | Gibt eine Zeichenfolge zurück, die das aktuelle Objekt darstellt. |

### Siehe auch

* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
