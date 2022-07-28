---
title: DataContainer
second_title: Référence de l'API Aspose.Email pour .NET
description: Contient des données pour un objet particulier tel quun contact un message électronique un rendez-vous de calendrier ou un élément de tâche. Le DataContainer peut être utilisé pour modifier des éléments ajouter des éléments ou récupérer des éléments sur le périphérique client ou le serveur.
type: docs
weight: 1150
url: /fr/net/aspose.email.clients.activesync.transportlayer/datacontainer/
---
## DataContainer class

Contient des données pour un objet particulier, tel qu'un contact, un message électronique, un rendez-vous de calendrier ou un élément de tâche. Le DataContainer peut être utilisé pour modifier des éléments, ajouter des éléments ou récupérer des éléments sur le périphérique client ou le serveur.

```csharp
public class DataContainer : IEnumerable
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [DataContainer](datacontainer#constructor)(string, Namespace) | Initialise une nouvelle instance de la classe DataContainer. |
| [DataContainer](datacontainer#constructor_1)(string, Namespace, DataContainer) | Initialise une nouvelle instance de la classe DataContainer. |
| [DataContainer](datacontainer#constructor_2)(string, Namespace, DataContainer, string) | Initialise une nouvelle instance de la classe DataContainer. |
| [DataContainer](datacontainer#constructor_3)(string, Namespace, DataContainer, string, bool) | Initialise une nouvelle instance de la classe DataContainer. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BinaryData](../../aspose.email.clients.activesync.transportlayer/datacontainer/binarydata) { get; set; } | Spécifie si les données sont binaires. |
| [ElementName](../../aspose.email.clients.activesync.transportlayer/datacontainer/elementname) { get; } | Nom de l'élément dont les données sont contenues dans le conteneur de données. |
| [Item](../../aspose.email.clients.activesync.transportlayer/datacontainer/item) { get; } | Obtient DataContainer pour l'élément sélectionné Si la quantité de DataContainers est supérieure à un, AsposeException augmente. (15 indexers) |
| [Namespace](../../aspose.email.clients.activesync.transportlayer/datacontainer/namespace) { get; } | NameSpace de l'élément, dont les données sont contenues dans le conteneur de données. |
| [Parent](../../aspose.email.clients.activesync.transportlayer/datacontainer/parent) { get; } | Parent DataContainer |
| [Prefix](../../aspose.email.clients.activesync.transportlayer/datacontainer/prefix) { get; } | Préfixe dans le nœud xml pour l'élément |
| [SubItems](../../aspose.email.clients.activesync.transportlayer/datacontainer/subitems) { get; } | Copie les sous-éléments de ApplicationData dans une nouvelle liste. |
| [Value](../../aspose.email.clients.activesync.transportlayer/datacontainer/value) { get; set; } | Valeur de l'élément |

## Méthodes

| Nom | La description |
| --- | --- |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_3)(string) | Ajoute les données de l'élément au format xml au DataContainer. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_4)(XmlNode) | Ajoute les données de l'élément au format xml au DataContainer. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add)(int, Namespace) | Ajoute un DataContainer vide pour l'élément. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_1)(int, string, Namespace) | Ajoute les données de l'élément au DataContainer. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_2)(int, string, bool, Namespace) | Ajoute les données de l'élément au DataContainer. |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist)(AirSync) | Obtient la liste des DataContainers pour l'élément sélectionné |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_1)(AirSyncBase) | Obtient la liste des DataContainers pour l'élément sélectionné |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_2)(Calendar) | Obtient la liste des DataContainers pour l'élément sélectionné |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_3)(Contacts) | Obtient la liste des DataContainers pour l'élément sélectionné |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_4)(Contacts2) | Obtient la liste des DataContainers pour l'élément sélectionné |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_5)(DocumentLibrary) | Obtient la liste des DataContainers pour l'élément sélectionné |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_6)(Email) | Obtient la liste des DataContainers pour l'élément sélectionné |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_7)(Email2) | Obtient la liste des DataContainers pour l'élément sélectionné |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_8)(GAL) | Obtient la liste des DataContainers pour l'élément sélectionné |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_9)(ItemOperations) | Obtient la liste des DataContainers pour l'élément sélectionné |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_10)(Notes) | Obtient la liste des DataContainers pour l'élément sélectionné |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_11)(RightsManagement) | Obtient la liste des DataContainers pour l'élément sélectionné |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_12)(Search) | Obtient la liste des DataContainers pour l'élément sélectionné |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_13)(Settings) | Obtient la liste des DataContainers pour l'élément sélectionné |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_14)(Tasks) | Obtient la liste des DataContainers pour l'élément sélectionné |
| [GetEnumerator](../../aspose.email.clients.activesync.transportlayer/datacontainer/getenumerator)() | Renvoie un énumérateur qui parcourt la collection. |
| override [ToString](../../aspose.email.clients.activesync.transportlayer/datacontainer/tostring)() | Renvoie une chaîne qui représente l'objet actuel. |

### Voir également

* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
