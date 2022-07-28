---
title: MapiNamedProperty
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente le type de données de la propriété nommée.
type: docs
weight: 18510
url: /fr/net/aspose.email.mapi/mapinamedproperty/
---
## MapiNamedProperty class

Représente le type de données de la propriété nommée.

```csharp
public sealed class MapiNamedProperty : MapiProperty
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [MapiNamedProperty](mapinamedproperty#constructor)() | Initialise une nouvelle instance du[`MapiNamedProperty`](../mapinamedproperty) classe. |
| [MapiNamedProperty](mapinamedproperty#constructor_1)(INamedPropertyTagProvider, PidLidPropertyDescriptor, object) | Initialise une nouvelle instance du[`MapiNamedProperty`](../mapinamedproperty) classe. |
| [MapiNamedProperty](mapinamedproperty#constructor_2)(INamedPropertyTagProvider, PidNamePropertyDescriptor, object) | Initialise une nouvelle instance du[`MapiNamedProperty`](../mapinamedproperty) classe. |
| [MapiNamedProperty](mapinamedproperty#constructor_3)(long, long, Guid, byte[]) | Initialise une nouvelle instance du[`MapiNamedProperty`](../mapinamedproperty) classe. |
| [MapiNamedProperty](mapinamedproperty#constructor_4)(long, string, Guid, byte[]) | Initialise une nouvelle instance du[`MapiNamedProperty`](../mapinamedproperty) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| virtual [Data](../../aspose.email.mapi/mapiproperty/data) { get; } | Obtient les données binaires. |
| virtual [DataType](../../aspose.email.mapi/mapiproperty/datatype) { get; } | Obtient le type de données. |
| [Descriptor](../../aspose.email.mapi/mapiproperty/descriptor) { get; } | Obtient le descripteur de la propriété MAPI |
| [Guid](../../aspose.email.mapi/mapinamedproperty/guid) { get; } | obtient la propriété nommée GUID |
| virtual [Identifier](../../aspose.email.mapi/mapiproperty/identifier) { get; } | Obtient l'indicateur. |
| [IsNamed](../../aspose.email.mapi/mapiproperty/isnamed) { get; } | Indique si la propriété est une propriété nommée. |
| virtual [IsSigned](../../aspose.email.mapi/mapiproperty/issigned) { get; set; } | Indique si les données binaires sont signées. |
| [Kind](../../aspose.email.mapi/mapinamedproperty/kind) { get; } | obtient la propriété nommée kind |
| [MVEntries](../../aspose.email.mapi/mapiproperty/mventries) { get; } | Obtient la liste des entrées MV. |
| virtual [Name](../../aspose.email.mapi/mapiproperty/name) { get; } | Récupère le nom. |
| [NameId](../../aspose.email.mapi/mapinamedproperty/nameid) { get; } | obtient la propriété nommée ID |
| [Oom](../../aspose.email.mapi/mapinamedproperty/oom) { get; } | obtient la valeur OOM |
| virtual [PropertyTagName](../../aspose.email.mapi/mapiproperty/propertytagname) { get; } | Obtient le PropertyName. |
| virtual [Tag](../../aspose.email.mapi/mapiproperty/tag) { get; } | Obtient la balise. |

## Méthodes

| Nom | La description |
| --- | --- |
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
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring)() | Obtient les données binaires sous forme de chaîne. |
| virtual [GetString](../../aspose.email.mapi/mapiproperty/getstring)(int) | Obtient les données binaires sous forme de chaîne à l'aide de la page de codes spécifiée. |
| [GetValue](../../aspose.email.mapi/mapiproperty/getvalue)() | Obtient la valeur en tant qu'objet |
| override [ToString](../../aspose.email.mapi/mapiproperty/tostring)() | Renvoie unString qui représente le courantObject . |

### Voir également

* class [MapiProperty](../mapiproperty)
* espace de noms [Aspose.Email.Mapi](../../aspose.email.mapi)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
