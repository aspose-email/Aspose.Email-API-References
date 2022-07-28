---
title: MapiAttachment
second_title: Referencia de la API de Aspose.Email para .NET
description: Representa el archivo adjunto en el mensaje de correo electrónico.
type: docs
weight: 17880
url: /es/net/aspose.email.mapi/mapiattachment/
---
## MapiAttachment class

Representa el archivo adjunto en el mensaje de correo electrónico.

```csharp
public class MapiAttachment : MapiPropertyContainer
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BinaryData](../../aspose.email.mapi/mapiattachment/binarydata) { get; set; } | Obtiene o establece datos adjuntos binarios. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Obtiene la página de códigos. |
| [Content](../../aspose.email.mapi/mapiattachment/content) { get; } | Obtiene el contenido. |
| [DisplayName](../../aspose.email.mapi/mapiattachment/displayname) { get; } | Obtiene el nombre para mostrar del objeto ole en un adjunto. |
| [Extension](../../aspose.email.mapi/mapiattachment/extension) { get; } | Obtiene una extensión de nombre de archivo que indica el tipo de documento de un adjunto. |
| [FileName](../../aspose.email.mapi/mapiattachment/filename) { get; } | Obtiene el nombre de archivo base y la extensión de un adjunto, excluyendo la ruta. |
| virtual [ItemId](../../aspose.email.mapi/mapiattachment/itemid) { get; } | El id del artículo, se usa con un servidor |
| [LongFileName](../../aspose.email.mapi/mapiattachment/longfilename) { get; } | Obtiene el nombre de archivo largo y la extensión de un adjunto, excluyendo la ruta. |
| [MimeTag](../../aspose.email.mapi/mapiattachment/mimetag) { get; } | Obtiene información de formato sobre un archivo adjunto Extensiones de correo de Internet multipropósito (MIME). |
| [NamedProperties](../../aspose.email.mapi/mapiattachment/namedproperties) { get; } | Obtiene las propiedades con nombre del mensaje. |
| [ObjectData](../../aspose.email.mapi/mapiattachment/objectdata) { get; } | Obtiene un objeto adjunto al que normalmente se accede a través de la interfaz OLE IStorage. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Obtiene la colección de propiedades. |
| [PropertyStream](../../aspose.email.mapi/mapiattachment/propertystream) { get; } | Obtiene el flujo de propiedad. |
| [SubStorages](../../aspose.email.mapi/mapiattachment/substorages) { get; } | Obtiene los subalmacenamientos. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [GetProperty](../../aspose.email.mapi/mapiattachment/getproperty)(PropertyDescriptor) | Obtiene la propiedad MAPI por descriptor de propiedad. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Obtiene el valor de la propiedad especificada por la etiqueta como tipo booleano. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Obtiene el valor de cadena de la propiedad especificada por la etiqueta. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Obtiene el valor de la propiedad especificada por la etiqueta como tipo DateTime. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Obtiene el valor int32 de la propiedad especificada por tag. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Obtiene el valor de la propiedad especificada por la etiqueta como tipo Long (int64). |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Obtiene el valor de la propiedad especificada por etiqueta como Tipo corto. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Obtiene el valor de cadena de la propiedad especificada por la etiqueta. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Obtiene el valor de cadena de la propiedad especificada por la etiqueta. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Determina si las propiedades de la cadena están codificadas en Unicode o no. |
| [RemoveProperty](../../aspose.email.mapi/mapiattachment/removeproperty)(long) | Proporciona la eliminación correcta de propiedades de todas las colecciones. |
| [Save](../../aspose.email.mapi/mapiattachment/save#save)(Stream) | Guardar contenido adjunto. |
| [Save](../../aspose.email.mapi/mapiattachment/save#save_1)(string) | Guardar contenido adjunto. |
| override [SetProperty](../../aspose.email.mapi/mapiattachment/setproperty#setproperty)(MapiProperty) | Establece la propiedad. |
| override [SetProperty](../../aspose.email.mapi/mapiattachment/setproperty#setproperty_1)(PropertyDescriptor, object) | Establece la propiedad MAPI. |
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
