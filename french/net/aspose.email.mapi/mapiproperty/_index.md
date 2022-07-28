---
title: MapiProperty
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente la propriété mapi.
type: docs
weight: 18560
url: /fr/net/aspose.email.mapi/mapiproperty/
---
## MapiProperty class

Représente la propriété mapi.

```csharp
public class MapiProperty
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [MapiProperty](mapiproperty#constructor_2)(long) | Initialise une nouvelle instance de la classe MapiProperty. |
| [MapiProperty](mapiproperty#constructor_3)(long, byte[]) | Initialise une nouvelle instance de la classe MapiProperty. |
| [MapiProperty](mapiproperty#constructor_5)(long, IList&lt;object&gt;) | Initialise une nouvelle instance du[`MapiProperty`](../mapiproperty) class. Cette surcharge est utilisée pour créer une propriété à valeurs multiples, PT_MV_*. |
| [MapiProperty](mapiproperty#constructor)(PidLidPropertyDescriptor, object) | Initialise une nouvelle instance de la classe MapiProperty. |
| [MapiProperty](mapiproperty#constructor_1)(PidTagPropertyDescriptor, object) | Initialise une nouvelle instance de la classe MapiProperty. |
| [MapiProperty](mapiproperty#constructor_4)(long, long, byte[]) | Initialise une nouvelle instance du[`MapiProperty`](../mapiproperty) classe. |
| [MapiProperty](mapiproperty#constructor_6)(string, long, long, byte[]) | Initialise une nouvelle instance de la classe MapiProperty. |

## Propriétés

| Nom | La description |
| --- | --- |
| virtual [Data](../../aspose.email.mapi/mapiproperty/data) { get; } | Obtient les données binaires. |
| virtual [DataType](../../aspose.email.mapi/mapiproperty/datatype) { get; } | Obtient le type de données. |
| [Descriptor](../../aspose.email.mapi/mapiproperty/descriptor) { get; } | Obtient le descripteur de la propriété MAPI |
| virtual [Identifier](../../aspose.email.mapi/mapiproperty/identifier) { get; } | Obtient l'indicateur. |
| [IsNamed](../../aspose.email.mapi/mapiproperty/isnamed) { get; } | Indique si la propriété est une propriété nommée. |
| virtual [IsSigned](../../aspose.email.mapi/mapiproperty/issigned) { get; set; } | Indique si les données binaires sont signées. |
| [MVEntries](../../aspose.email.mapi/mapiproperty/mventries) { get; } | Obtient la liste des entrées MV. |
| virtual [Name](../../aspose.email.mapi/mapiproperty/name) { get; } | Récupère le nom. |
| virtual [PropertyTagName](../../aspose.email.mapi/mapiproperty/propertytagname) { get; } | Obtient le PropertyName. |
| virtual [Tag](../../aspose.email.mapi/mapiproperty/tag) { get; } | Obtient la balise. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [CreateMapiPropertyFromBytes](../../aspose.email.mapi/mapiproperty/createmapipropertyfrombytes)(long, byte[]) | Crée la propriété mapi à partir de bytes. |
| static [CreateMapiPropertyFromDateTime](../../aspose.email.mapi/mapiproperty/createmapipropertyfromdatetime)(long, DateTime) | Crée la propriété mapi à partir de la date et de l'heure. |
| static [CreateMapiPropertyFromLong](../../aspose.email.mapi/mapiproperty/createmapipropertyfromlong#createmapipropertyfromlong)(long, long) | Crée la propriété mapi à partir de long. |
| static [CreateMapiPropertyFromLong](../../aspose.email.mapi/mapiproperty/createmapipropertyfromlong#createmapipropertyfromlong_1)(long, long, long) | Crée la propriété mapi à partir de long. |
| virtual [GetBoolean](../../aspose.email.mapi/mapiproperty/getboolean)() | Obtient les premiers octets des données binaires sous forme booléenne. |
| virtual [GetCurrency](../../aspose.email.mapi/mapiproperty/getcurrency)() | Obtient la devise sous forme de chaîne à l'aide de la page de code spécifiée. |
| virtual [GetDateTime](../../aspose.email.mapi/mapiproperty/getdatetime)() | Obtient les premiers octets des données binaires comme datetime. |
| virtual [GetDouble](../../aspose.email.mapi/mapiproperty/getdouble)() | Obtient les octets des données binaires en double. |
| virtual [GetFloat](../../aspose.email.mapi/mapiproperty/getfloat)() | Obtient les octets des données binaires en tant que float. |
| virtual [GetFloatingDate](../../aspose.email.mapi/mapiproperty/getfloatingdate)() | Obtient les octets des données binaires en tant que DateTime. |
| virtual [GetGuid](../../aspose.email.mapi/mapiproperty/getguid)() | Obtient les octets des données binaires en tant que Guid. |
| virtual [GetInt32](../../aspose.email.mapi/mapiproperty/getint32)() | Obtient les 4 premiers octets des données binaires sous la forme int32. |
| virtual [GetLong](../../aspose.email.mapi/mapiproperty/getlong)() | Obtient les 8 premiers octets des données binaires aussi longtemps. |
| virtual [GetShort](../../aspose.email.mapi/mapiproperty/getshort)() | Obtient les 2 premiers octets des données binaires sous forme courte. |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring#getstring)() | Obtient les données binaires sous forme de chaîne. |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring#getstring_1)(int) | Obtient les données binaires sous forme de chaîne à l'aide de la page de codes spécifiée. |
| [GetValue](../../aspose.email.mapi/mapiproperty/getvalue)() | Obtient la valeur en tant qu'objet |
| override [ToString](../../aspose.email.mapi/mapiproperty/tostring)() | Renvoie unString qui représente le courantObject . |

### Voir également

* espace de noms [Aspose.Email.Mapi](../../aspose.email.mapi)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
