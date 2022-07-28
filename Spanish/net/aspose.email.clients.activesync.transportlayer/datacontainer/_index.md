---
title: DataContainer
second_title: Referencia de la API de Aspose.Email para .NET
description: Contiene datos para un objeto en particular como un contacto mensaje de correo electrónico cita de calendario o elemento de tarea. El DataContainer se puede usar para cambiar elementos agregar elementos o recuperar elementos en el servidor o dispositivo cliente.
type: docs
weight: 1150
url: /es/net/aspose.email.clients.activesync.transportlayer/datacontainer/
---
## DataContainer class

Contiene datos para un objeto en particular, como un contacto, mensaje de correo electrónico, cita de calendario o elemento de tarea. El DataContainer se puede usar para cambiar elementos, agregar elementos o recuperar elementos en el servidor o dispositivo cliente.

```csharp
public class DataContainer : IEnumerable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DataContainer](datacontainer#constructor)(string, Namespace) | Inicializa una nueva instancia de la clase DataContainer. |
| [DataContainer](datacontainer#constructor_1)(string, Namespace, DataContainer) | Inicializa una nueva instancia de la clase DataContainer. |
| [DataContainer](datacontainer#constructor_2)(string, Namespace, DataContainer, string) | Inicializa una nueva instancia de la clase DataContainer. |
| [DataContainer](datacontainer#constructor_3)(string, Namespace, DataContainer, string, bool) | Inicializa una nueva instancia de la clase DataContainer. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BinaryData](../../aspose.email.clients.activesync.transportlayer/datacontainer/binarydata) { get; set; } | Especifica si los datos son binarios. |
| [ElementName](../../aspose.email.clients.activesync.transportlayer/datacontainer/elementname) { get; } | Nombre del elemento, cuyos datos están contenidos en el contenedor de datos. |
| [Item](../../aspose.email.clients.activesync.transportlayer/datacontainer/item) { get; } | Obtiene DataContainer para el elemento seleccionado Si la cantidad de DataContainers es más de uno, AsposeException aumenta. (15 indexers) |
| [Namespace](../../aspose.email.clients.activesync.transportlayer/datacontainer/namespace) { get; } | NameSpace del elemento, cuyos datos están contenidos en el contenedor de datos. |
| [Parent](../../aspose.email.clients.activesync.transportlayer/datacontainer/parent) { get; } | Contenedor de datos principal |
| [Prefix](../../aspose.email.clients.activesync.transportlayer/datacontainer/prefix) { get; } | Prefijo en el nodo xml para el elemento |
| [SubItems](../../aspose.email.clients.activesync.transportlayer/datacontainer/subitems) { get; } | Copia los subelementos de ApplicationData a una nueva Lista. |
| [Value](../../aspose.email.clients.activesync.transportlayer/datacontainer/value) { get; set; } | Valor del elemento |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_3)(string) | Agrega datos del elemento en formato xml al DataContainer. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_4)(XmlNode) | Agrega datos del elemento en formato xml al DataContainer. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add)(int, Namespace) | Agrega un contenedor de datos vacío para el elemento. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_1)(int, string, Namespace) | Agrega datos del elemento al DataContainer. |
| [Add](../../aspose.email.clients.activesync.transportlayer/datacontainer/add#add_2)(int, string, bool, Namespace) | Agrega datos del elemento al DataContainer. |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist)(AirSync) | Obtiene una lista de contenedores de datos para el elemento seleccionado |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_1)(AirSyncBase) | Obtiene una lista de contenedores de datos para el elemento seleccionado |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_2)(Calendar) | Obtiene una lista de contenedores de datos para el elemento seleccionado |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_3)(Contacts) | Obtiene una lista de contenedores de datos para el elemento seleccionado |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_4)(Contacts2) | Obtiene una lista de contenedores de datos para el elemento seleccionado |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_5)(DocumentLibrary) | Obtiene una lista de contenedores de datos para el elemento seleccionado |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_6)(Email) | Obtiene una lista de contenedores de datos para el elemento seleccionado |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_7)(Email2) | Obtiene una lista de contenedores de datos para el elemento seleccionado |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_8)(GAL) | Obtiene una lista de contenedores de datos para el elemento seleccionado |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_9)(ItemOperations) | Obtiene una lista de contenedores de datos para el elemento seleccionado |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_10)(Notes) | Obtiene una lista de contenedores de datos para el elemento seleccionado |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_11)(RightsManagement) | Obtiene una lista de contenedores de datos para el elemento seleccionado |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_12)(Search) | Obtiene una lista de contenedores de datos para el elemento seleccionado |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_13)(Settings) | Obtiene una lista de contenedores de datos para el elemento seleccionado |
| [GetApplicationDataList](../../aspose.email.clients.activesync.transportlayer/datacontainer/getapplicationdatalist#getapplicationdatalist_14)(Tasks) | Obtiene una lista de contenedores de datos para el elemento seleccionado |
| [GetEnumerator](../../aspose.email.clients.activesync.transportlayer/datacontainer/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| override [ToString](../../aspose.email.clients.activesync.transportlayer/datacontainer/tostring)() | Devuelve una cadena que representa el objeto actual. |

### Ver también

* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
