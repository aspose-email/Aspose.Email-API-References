---
title: MapiNamedPropertyMappingStorage
second_title: Referencia de la API de Aspose.Email para .NET
description: Representa la propiedad nombrada mapping
type: docs
weight: 18520
url: /es/net/aspose.email.mapi/mapinamedpropertymappingstorage/
---
## MapiNamedPropertyMappingStorage class

Representa la propiedad nombrada mapping

```csharp
public sealed class MapiNamedPropertyMappingStorage : MapiPropertyContainer
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MapiNamedPropertyMappingStorage](mapinamedpropertymappingstorage)() | Inicializa una nueva instancia del[`MapiNamedPropertyMappingStorage`](../mapinamedpropertymappingstorage) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Obtiene la página de códigos. |
| [Content](../../aspose.email.mapi/mapinamedpropertymappingstorage/content) { get; } | Obtiene el contenido |
| [Name](../../aspose.email.mapi/mapinamedpropertymappingstorage/name) { get; } | Obtiene el nombre |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Obtiene la colección de propiedades. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddNamedPropertyMapping](../../aspose.email.mapi/mapinamedpropertymappingstorage/addnamedpropertymapping#addnamedpropertymapping)(MapiProperty, long, Guid) | Agrega la asignación de propiedad con nombre para la propiedad con nombre numérico. |
| [AddNamedPropertyMapping](../../aspose.email.mapi/mapinamedpropertymappingstorage/addnamedpropertymapping#addnamedpropertymapping_1)(MapiProperty, string, Guid) | Agrega la asignación de propiedades con nombre para la propiedad con nombre de cadena. |
| [GetNextAvailablePropertyId](../../aspose.email.mapi/mapinamedpropertymappingstorage/getnextavailablepropertyid)(MapiPropertyType) | Obtiene el siguiente ID de propiedad disponible en el flujo de entradas según el tipo de datos de la propiedad. |
| virtual [GetProperty](../../aspose.email.mapi/mapipropertycontainer/getproperty)(PropertyDescriptor) | Obtiene la propiedad MAPI por descriptor de propiedad. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Obtiene el valor de la propiedad especificada por la etiqueta como tipo booleano. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Obtiene el valor de cadena de la propiedad especificada por la etiqueta. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Obtiene el valor de la propiedad especificada por la etiqueta como tipo DateTime. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Obtiene el valor int32 de la propiedad especificada por tag. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Obtiene el valor de la propiedad especificada por la etiqueta como tipo Long (int64). |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Obtiene el valor de la propiedad especificada por etiqueta como Tipo corto. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Obtiene el valor de cadena de la propiedad especificada por la etiqueta. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Obtiene el valor de cadena de la propiedad especificada por la etiqueta. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Determina si las propiedades de la cadena están codificadas en Unicode o no. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | Establece la propiedad. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(PropertyDescriptor, object) | Establece la propiedad MAPI. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | Intente obtener los datos de la propiedad con la clave de etiqueta especificada. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | Obtiene el valor de la propiedad especificada como tipo DateTime. Un valor devuelto indica si la operación tuvo éxito. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | Obtiene el valor de la propiedad especificada como tipo Int32. Un valor devuelto indica si la operación tuvo éxito. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | Obtiene el valor de la propiedad especificada como tipo Long. Un valor devuelto indica si la operación tuvo éxito. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | Intente obtener los datos de una propiedad como una cadena con la etiqueta especificada. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | Intente obtener los datos de una propiedad como una cadena con la etiqueta y la página de códigos especificadas. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | Obtiene el valor de la propiedad especificada como tipo String. Un valor devuelto indica si la operación tuvo éxito. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | Obtiene el valor de la propiedad especificada como tipo String. Un valor devuelto indica si la operación tuvo éxito. |

### Ver también

* class [MapiPropertyContainer](../mapipropertycontainer)
* espacio de nombres [Aspose.Email.Mapi](../../aspose.email.mapi)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
