---
title: PidTagPropertyDescriptor
second_title: Referencia de la API de Aspose.Email para .NET
description: La clase contiene información de descripción de la propiedad.
type: docs
weight: 18990
url: /es/net/aspose.email.mapi/pidtagpropertydescriptor/
---
## PidTagPropertyDescriptor class

La clase contiene información de descripción de la propiedad.

```csharp
public class PidTagPropertyDescriptor : PropertyDescriptor
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_1)(long) | Inicializa una nueva instancia del[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class Una propiedad definida por un ID de propiedad de 16 bits y un tipo de propiedad de 16 bits. El ID de propiedad para una propiedad etiquetada está en el rango 0x001 � 0x7FFF. Los ID de propiedad en el rango 0x8000 � 0x8FFF están reservados para la asignación a propiedades con nombre |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor)(int, PropertyDataType) | Inicializa una nueva instancia del[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class Una propiedad definida por un ID de propiedad de 16 bits y un tipo de propiedad de 16 bits. El ID de propiedad para una propiedad etiquetada está en el rango 0x001 � 0x7FFF. Los ID de propiedad en el rango 0x8000 � 0x8FFF están reservados para la asignación a propiedades con nombre |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_2)(string, int, PropertyDataType) | Inicializa una nueva instancia del[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class Una propiedad definida por un ID de propiedad de 16 bits y un tipo de propiedad de 16 bits. El ID de propiedad para una propiedad etiquetada está en el rango 0x001 � 0x7FFF. Los ID de propiedad en el rango 0x8000 � 0x8FFF están reservados para la asignación a propiedades con nombre |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_4)(string, string, long) | Inicializa una nueva instancia del[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class Una propiedad definida por un ID de propiedad de 16 bits y un tipo de propiedad de 16 bits. El ID de propiedad para una propiedad etiquetada está en el rango 0x001 � 0x7FFF. Los ID de propiedad en el rango 0x8000 � 0x8FFF están reservados para la asignación a propiedades con nombre |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_3)(string, string, int, PropertyDataType) | Inicializa una nueva instancia del[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class Una propiedad definida por un ID de propiedad de 16 bits y un tipo de propiedad de 16 bits. El ID de propiedad para una propiedad etiquetada está en el rango 0x001 � 0x7FFF. Los ID de propiedad en el rango 0x8000 � 0x8FFF están reservados para la asignación a propiedades con nombre |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CanonicalName](../../aspose.email.mapi/propertydescriptor/canonicalname) { get; } | El nombre utilizado para referirse a la propiedad en la documentación. El prefijo del nombre canónico identifica las características básicas de una propiedad para el implementador. La estructura de nomenclatura canónica utiliza tres categorías que se indican mediante los siguientes prefijos al nombre de propiedad canónica: * Prefijo PidLid: propiedades identificadas por una cantidad de 32 bits sin firmar junto con un conjunto de propiedades. * Prefijo PidName: propiedades identificadas por un nombre de cadena junto con un conjunto de propiedades. * Prefijo PidTag: propiedades identificadas por una cantidad de 16 bits sin signo. |
| [DataType](../../aspose.email.mapi/propertydescriptor/datatype) { get; } | El tipo de valor de propiedad, como se describe en [MS-OXCDATA], que especifica el tipo de valores permitidos para la propiedad. |
| [Id](../../aspose.email.mapi/pidtagpropertydescriptor/id) { get; } | Obtiene una cantidad de 16 bits sin firmar que identifica una propiedad etiquetada. Los ID de propiedad no son necesariamente únicos. Con la excepción de los ID de propiedad en el rango de 0x6800 a 0x7BFF, la combinación de ID de propiedad y tipo de datos es única. Los ID de propiedad en el rango de 0x6800 a 0x7BFF están definidos por la clase de mensaje. |
| [MultipleValuesDataType](../../aspose.email.mapi/propertydescriptor/multiplevaluesdatatype) { get; } | Indica si el tipo de datos contiene varios valores |
| [Name](../../aspose.email.mapi/propertydescriptor/name) { get; } | Obtiene una cadena que identifica una propiedad. |
| [Tag](../../aspose.email.mapi/pidtagpropertydescriptor/tag) { get; } | Una etiqueta de propiedad es un número de 32 bits que contiene un identificador de propiedad único en los bits 16 a 31 y un tipo de propiedad en los bits 0 a 15. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.email.mapi/pidtagpropertydescriptor/equals#equals_1)(object) | Determina si el System.Object especificado es igual al System.Object. actual |
| override [Equals](../../aspose.email.mapi/pidtagpropertydescriptor/equals#equals)(PropertyDescriptor) | Indica si el objeto actual es igual a otro objeto del mismo tipo. |
| override [GetHashCode](../../aspose.email.mapi/pidtagpropertydescriptor/gethashcode)() | Sirve como función hash para un tipo. |
| override [ToString](../../aspose.email.mapi/pidtagpropertydescriptor/tostring)() | Devuelve una cadena que representa la descripción de la propiedad. |
| [operator ==](../../aspose.email.mapi/pidtagpropertydescriptor/op_equality) | Determina si los objetos especificados son iguales entre sí. |
| [explicit operator](../../aspose.email.mapi/pidtagpropertydescriptor/op_explicit) | Convierte el valor de la etiqueta en una propiedad etiquetada |
| [operator !=](../../aspose.email.mapi/pidtagpropertydescriptor/op_inequality) | Determina si los objetos especificados no son iguales entre sí. |

### Ver también

* class [PropertyDescriptor](../propertydescriptor)
* espacio de nombres [Aspose.Email.Mapi](../../aspose.email.mapi)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
