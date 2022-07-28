---
title: DataContainer
second_title: Aspose.Email per riferimento all'API .NET
description: Contiene i dati per un oggetto particolare come un contatto un messaggio di posta elettronica un appuntamento del calendario o un elemento dellattività. Il DataContainer può essere utilizzato per modificare elementi aggiungere elementi o recuperare elementi sul dispositivo client o sul server.
type: docs
weight: 1150
url: /it/net/aspose.email.clients.activesync.transportlayer/datacontainer/
---
## DataContainer class

Contiene i dati per un oggetto particolare, come un contatto, un messaggio di posta elettronica, un appuntamento del calendario o un elemento dell'attività. Il DataContainer può essere utilizzato per modificare elementi, aggiungere elementi o recuperare elementi sul dispositivo client o sul server.

```csharp
public class DataContainer : IEnumerable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DataContainer](datacontainer#constructor)(string, Namespace) | Inizializza una nuova istanza della classe DataContainer. |
| [DataContainer](datacontainer#constructor_1)(string, Namespace, DataContainer) | Inizializza una nuova istanza della classe DataContainer. |
| [DataContainer](datacontainer#constructor_2)(string, Namespace, DataContainer, string) | Inizializza una nuova istanza della classe DataContainer. |
| [DataContainer](datacontainer#constructor_3)(string, Namespace, DataContainer, string, bool) | Inizializza una nuova istanza della classe DataContainer. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BinaryData](../../aspose.email.clients.activesync.transportlayer/datacontainer/binarydata) { get; set; } | Specifica se i dati sono binari. |
| [ElementName](../../aspose.email.clients.activesync.transportlayer/datacontainer/elementname) { get; } | Nome dell'elemento i cui dati sono contenuti nel contenitore dei dati. |
| [Item](../../aspose.email.clients.activesync.transportlayer/datacontainer/item) { get; } | Ottiene DataContainer per l'elemento selezionato Se la quantità di DataContainer è maggiore di uno, AsposeException aumenta. (15 indexers) |
| [Namespace](../../aspose.email.clients.activesync.transportlayer/datacontainer/namespace) { get; } | NameSpace dell'elemento, i cui dati sono contenuti nel contenitore dei dati. |
| [Parent](../../aspose.email.clients.activesync.transportlayer/datacontainer/parent) { get; } | Contenitore dati padre |
| [Prefix](../../aspose.email.clients.activesync.transportlayer/datacontainer/prefix) { get; } | Prefisso nel nodo xml per l'elemento |
| [SubItems](../../aspose.email.clients.activesync.transportlayer/datacontainer/subitems) { get; } | Copia i sottoelementi di ApplicationData in un nuovo List. |
| [Value](../../aspose.email.clients.activesync.transportlayer/datacontainer/value) { get; set; } | Valore dell'elemento |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_3)(string) | Aggiunge i dati dell'elemento in formato xml a DataContainer. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_4)(XmlNode) | Aggiunge i dati dell'elemento in formato xml a DataContainer. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add)(int, Namespace) | Aggiunge un DataContainer vuoto per l'elemento. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_1)(int, string, Namespace) | Aggiunge i dati dell'elemento a DataContainer. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_2)(int, string, bool, Namespace) | Aggiunge i dati dell'elemento a DataContainer. |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist)(AirSync) | Ottiene l'elenco dei DataContainer per l'elemento selezionato |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_1)(AirSyncBase) | Ottiene l'elenco dei DataContainer per l'elemento selezionato |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_2)(Calendar) | Ottiene l'elenco dei DataContainer per l'elemento selezionato |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_3)(Contacts) | Ottiene l'elenco dei DataContainer per l'elemento selezionato |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_4)(Contacts2) | Ottiene l'elenco dei DataContainer per l'elemento selezionato |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_5)(DocumentLibrary) | Ottiene l'elenco dei DataContainer per l'elemento selezionato |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_6)(Email) | Ottiene l'elenco dei DataContainer per l'elemento selezionato |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_7)(Email2) | Ottiene l'elenco dei DataContainer per l'elemento selezionato |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_8)(GAL) | Ottiene l'elenco dei DataContainer per l'elemento selezionato |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_9)(ItemOperations) | Ottiene l'elenco dei DataContainer per l'elemento selezionato |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_10)(Notes) | Ottiene l'elenco dei DataContainer per l'elemento selezionato |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_11)(RightsManagement) | Ottiene l'elenco dei DataContainer per l'elemento selezionato |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_12)(Search) | Ottiene l'elenco dei DataContainer per l'elemento selezionato |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_13)(Settings) | Ottiene l'elenco dei DataContainer per l'elemento selezionato |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_14)(Tasks) | Ottiene l'elenco dei DataContainer per l'elemento selezionato |
| [GetEnumerator](../../aspose.email.clients.activesync.transportlayer/datacontainer/getenumerator)() | Restituisce un enumeratore che scorre la raccolta. |
| override [ToString](../../aspose.email.clients.activesync.transportlayer/datacontainer/tostring)() | Restituisce una stringa che rappresenta l'oggetto corrente. |

### Guarda anche

* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
