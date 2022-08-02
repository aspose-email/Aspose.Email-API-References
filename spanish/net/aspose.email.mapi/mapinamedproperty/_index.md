---
title: MapiNamedProperty
second_title: Referencia de la API de Aspose.Email para .NET
description: Representa el tipo de datos de Propiedad con nombre.
type: docs
weight: 18510
url: /es/net/aspose.email.mapi/mapinamedproperty/
---
## MapiNamedProperty class

Representa el tipo de datos de Propiedad con nombre.

```csharp
public sealed class MapiNamedProperty : MapiProperty
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MapiNamedProperty](mapinamedproperty#constructor)() | Inicializa una nueva instancia del[`MapiNamedProperty`](../mapinamedproperty) clase. |
| [MapiNamedProperty](mapinamedproperty#constructor_1)(INamedPropertyTagProvider, PidLidPropertyDescriptor, object) | Inicializa una nueva instancia del[`MapiNamedProperty`](../mapinamedproperty) clase. |
| [MapiNamedProperty](mapinamedproperty#constructor_2)(INamedPropertyTagProvider, PidNamePropertyDescriptor, object) | Inicializa una nueva instancia del[`MapiNamedProperty`](../mapinamedproperty) clase. |
| [MapiNamedProperty](mapinamedproperty#constructor_3)(long, long, Guid, byte[]) | Inicializa una nueva instancia del[`MapiNamedProperty`](../mapinamedproperty) clase. |
| [MapiNamedProperty](mapinamedproperty#constructor_4)(long, string, Guid, byte[]) | Inicializa una nueva instancia del[`MapiNamedProperty`](../mapinamedproperty) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [Data](../../aspose.email.mapi/mapiproperty/data) { get; } | Obtiene los datos binarios. |
| virtual [DataType](../../aspose.email.mapi/mapiproperty/datatype) { get; } | Obtiene el tipo de dato. |
| [Descriptor](../../aspose.email.mapi/mapiproperty/descriptor) { get; } | Obtiene el descriptor de la propiedad MAPI |
| [Guid](../../aspose.email.mapi/mapinamedproperty/guid) { get; } | obtiene el nombre de propiedad GUID |
| virtual [Identifier](../../aspose.email.mapi/mapiproperty/identifier) { get; } | Obtiene el identificador. |
| [IsNamed](../../aspose.email.mapi/mapiproperty/isnamed) { get; } | Indica si la propiedad es una propiedad con nombre. |
| virtual [IsSigned](../../aspose.email.mapi/mapiproperty/issigned) { get; set; } | Indica si los datos binarios están firmados. |
| [Kind](../../aspose.email.mapi/mapinamedproperty/kind) { get; } | obtiene el nombre de propiedad kind |
| [MVEntries](../../aspose.email.mapi/mapiproperty/mventries) { get; } | Obtiene la lista de entradas de MV. |
| virtual [Name](../../aspose.email.mapi/mapiproperty/name) { get; } | Obtiene el nombre. |
| [NameId](../../aspose.email.mapi/mapinamedproperty/nameid) { get; } | obtiene el nombre de propiedad ID |
| [Oom](../../aspose.email.mapi/mapinamedproperty/oom) { get; } | obtiene el valor OOM |
| virtual [PropertyTagName](../../aspose.email.mapi/mapiproperty/propertytagname) { get; } | Obtiene el PropertyName. |
| virtual [Tag](../../aspose.email.mapi/mapiproperty/tag) { get; } | Obtiene la etiqueta. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [GetBoolean](../../aspose.email.mapi/mapiproperty/getboolean)() | Obtiene los primeros bytes de los datos binarios como booleanos. |
| virtual [GetCurrency](../../aspose.email.mapi/mapiproperty/getcurrency)() | Obtiene la moneda como cadena utilizando la página de códigos especificada. |
| virtual [GetDateTime](../../aspose.email.mapi/mapiproperty/getdatetime)() | Obtiene los primeros bytes de los datos binarios como datetime. |
| virtual [GetDouble](../../aspose.email.mapi/mapiproperty/getdouble)() | Obtiene los bytes de los datos binarios como double. |
| virtual [GetFloat](../../aspose.email.mapi/mapiproperty/getfloat)() | Obtiene los bytes de los datos binarios como float. |
| virtual [GetFloatingDate](../../aspose.email.mapi/mapiproperty/getfloatingdate)() | Obtiene los bytes de los datos binarios como DateTime. |
| virtual [GetGuid](../../aspose.email.mapi/mapiproperty/getguid)() | Obtiene los bytes de los datos binarios como Guid. |
| virtual [GetInt32](../../aspose.email.mapi/mapiproperty/getint32)() | Obtiene los primeros 4 bytes de los datos binarios como int32. |
| virtual [GetLong](../../aspose.email.mapi/mapiproperty/getlong)() | Obtiene los primeros 8 bytes de los datos binarios tan largos. |
| virtual [GetShort](../../aspose.email.mapi/mapiproperty/getshort)() | Obtiene los primeros 2 bytes de los datos binarios como short. |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring)() | Obtiene los datos binarios como cadena. |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring)(int) | Obtiene los datos binarios como una cadena utilizando la página de códigos especificada. |
| [GetValue](../../aspose.email.mapi/mapiproperty/getvalue)() | Obtiene valor como object |
| override [ToString](../../aspose.email.mapi/mapiproperty/tostring)() | Devuelve unString que representa la corrienteObject . |

### Ver también

* class [MapiProperty](../mapiproperty)
* espacio de nombres [Aspose.Email.Mapi](../../aspose.email.mapi)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
