---
title: DataContainer
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 1150
url: /net/aspose.email.clients.activesync.transportlayer/datacontainer/
---
## DataContainer class

Contains data for a particular object, such as a contact, email message, calendar appointment, or task item. The DataContainer can be used to change items, add items, or fetch items on the client device or server.

```csharp
public class DataContainer : IEnumerable
```

## Constructors

| Name | Description |
| --- | --- |
| [DataContainer](datacontainer)(string, Namespace) | Initializes a new instance of the DataContainer class. |
| [DataContainer](datacontainer)(string, Namespace, DataContainer) | Initializes a new instance of the DataContainer class. |
| [DataContainer](datacontainer)(string, Namespace, DataContainer, string) | Initializes a new instance of the DataContainer class. |
| [DataContainer](datacontainer)(string, Namespace, DataContainer, string, bool) | Initializes a new instance of the DataContainer class. |

## Properties

| Name | Description |
| --- | --- |
| [BinaryData](../../aspose.email.clients.activesync.transportlayer/datacontainer/binarydata) { get; set; } | Specifies if data is binary. |
| [ElementName](../../aspose.email.clients.activesync.transportlayer/datacontainer/elementname) { get; } | Name of the element, whose data are contained in the data container. |
| [Item](../../aspose.email.clients.activesync.transportlayer/datacontainer/item) { get; } | Gets DataContainer for selected element If quantity of DataContainers more then one, AsposeException rises. (15 indexers) |
| [Namespace](../../aspose.email.clients.activesync.transportlayer/datacontainer/namespace) { get; } | NameSpace of the element, whose data are contained in the data container. |
| [Parent](../../aspose.email.clients.activesync.transportlayer/datacontainer/parent) { get; } | Parent DataContainer |
| [Prefix](../../aspose.email.clients.activesync.transportlayer/datacontainer/prefix) { get; } | Prefix in xml node for the element |
| [SubItems](../../aspose.email.clients.activesync.transportlayer/datacontainer/subitems) { get; } | Copies the sub-elements of the ApplicationData to a new List. |
| [Value](../../aspose.email.clients.activesync.transportlayer/datacontainer/value) { get; set; } | Value of the element |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add)(string) | Adds data of element in xml format to the DataContainer. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add)(XmlNode) | Adds data of element in xml format to the DataContainer. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add)(int, Namespace) | Adds empty DataContainer for element. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add)(int, string, Namespace) | Adds data of element to the DataContainer. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add)(int, string, bool, Namespace) | Adds data of element to the DataContainer. |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist)(AirSync) | Gets list of DataContainers for selected element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist)(AirSyncBase) | Gets list of DataContainers for selected element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist)(Calendar) | Gets list of DataContainers for selected element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist)(Contacts) | Gets list of DataContainers for selected element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist)(Contacts2) | Gets list of DataContainers for selected element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist)(DocumentLibrary) | Gets list of DataContainers for selected element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist)(Email) | Gets list of DataContainers for selected element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist)(Email2) | Gets list of DataContainers for selected element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist)(GAL) | Gets list of DataContainers for selected element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist)(ItemOperations) | Gets list of DataContainers for selected element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist)(Notes) | Gets list of DataContainers for selected element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist)(RightsManagement) | Gets list of DataContainers for selected element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist)(Search) | Gets list of DataContainers for selected element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist)(Settings) | Gets list of DataContainers for selected element |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist)(Tasks) | Gets list of DataContainers for selected element |
| [GetEnumerator](../../aspose.email.clients.activesync.transportlayer/datacontainer/getenumerator)() | Returns an enumerator that iterates through the collection. |
| override [ToString](../../aspose.email.clients.activesync.transportlayer/datacontainer/tostring)() | Returns a string that represents the current object. |

### See Also

* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
