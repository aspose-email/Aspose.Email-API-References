---
title: MapiProperty
second_title: Referencia de la API de Aspose.Email para .NET
description: Representa la propiedad mapi.
type: docs
weight: 18560
url: /es/net/aspose.email.mapi/mapiproperty/
---
## MapiProperty class

Representa la propiedad mapi.

```csharp
public class MapiProperty
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MapiProperty](mapiproperty#constructor_2)(long) | Inicializa una nueva instancia de la clase MapiProperty. |
| [MapiProperty](mapiproperty#constructor_3)(long, byte[]) | Inicializa una nueva instancia de la clase MapiProperty. |
| [MapiProperty](mapiproperty#constructor_5)(long, IList&lt;object&gt;) | Inicializa una nueva instancia del[`MapiProperty`](../mapiproperty) class. Esta sobrecarga se usa para crear una propiedad de valor múltiple, PT_MV_*. |
| [MapiProperty](mapiproperty#constructor)(PidLidPropertyDescriptor, object) | Inicializa una nueva instancia de la clase MapiProperty. |
| [MapiProperty](mapiproperty#constructor_1)(PidTagPropertyDescriptor, object) | Inicializa una nueva instancia de la clase MapiProperty. |
| [MapiProperty](mapiproperty#constructor_4)(long, long, byte[]) | Inicializa una nueva instancia del[`MapiProperty`](../mapiproperty) clase. |
| [MapiProperty](mapiproperty#constructor_6)(string, long, long, byte[]) | Inicializa una nueva instancia de la clase MapiProperty. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [Data](../../aspose.email.mapi/mapiproperty/data) { get; } | Obtiene los datos binarios. |
| virtual [DataType](../../aspose.email.mapi/mapiproperty/datatype) { get; } | Obtiene el tipo de dato. |
| [Descriptor](../../aspose.email.mapi/mapiproperty/descriptor) { get; } | Obtiene el descriptor de la propiedad MAPI |
| virtual [Identifier](../../aspose.email.mapi/mapiproperty/identifier) { get; } | Obtiene el identificador. |
| [IsNamed](../../aspose.email.mapi/mapiproperty/isnamed) { get; } | Indica si la propiedad es una propiedad con nombre. |
| virtual [IsSigned](../../aspose.email.mapi/mapiproperty/issigned) { get; set; } | Indica si los datos binarios están firmados. |
| [MVEntries](../../aspose.email.mapi/mapiproperty/mventries) { get; } | Obtiene la lista de entradas de MV. |
| virtual [Name](../../aspose.email.mapi/mapiproperty/name) { get; } | Obtiene el nombre. |
| virtual [PropertyTagName](../../aspose.email.mapi/mapiproperty/propertytagname) { get; } | Obtiene el PropertyName. |
| virtual [Tag](../../aspose.email.mapi/mapiproperty/tag) { get; } | Obtiene la etiqueta. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [CreateMapiPropertyFromBytes](../../aspose.email.mapi/mapiproperty/createmapipropertyfrombytes)(long, byte[]) | Crea la propiedad mapi a partir de bytes. |
| static [CreateMapiPropertyFromDateTime](../../aspose.email.mapi/mapiproperty/createmapipropertyfromdatetime)(long, DateTime) | Crea la propiedad mapi a partir de fecha y hora. |
| static [CreateMapiPropertyFromLong](../../aspose.email.mapi/mapiproperty/createmapipropertyfromlong#createmapipropertyfromlong)(long, long) | Crea la propiedad mapi a partir de long. |
| static [CreateMapiPropertyFromLong](../../aspose.email.mapi/mapiproperty/createmapipropertyfromlong#createmapipropertyfromlong_1)(long, long, long) | Crea la propiedad mapi a partir de long. |
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
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring#getstring)() | Obtiene los datos binarios como cadena. |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring#getstring_1)(int) | Obtiene los datos binarios como una cadena utilizando la página de códigos especificada. |
| [GetValue](../../aspose.email.mapi/mapiproperty/getvalue)() | Obtiene valor como object |
| override [ToString](../../aspose.email.mapi/mapiproperty/tostring)() | Devuelve unString que representa la corrienteObject . |

### Ver también

* espacio de nombres [Aspose.Email.Mapi](../../aspose.email.mapi)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
