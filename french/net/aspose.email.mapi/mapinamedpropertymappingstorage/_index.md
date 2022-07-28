---
title: MapiNamedPropertyMappingStorage
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente la propriété nommée mapping
type: docs
weight: 18520
url: /fr/net/aspose.email.mapi/mapinamedpropertymappingstorage/
---
## MapiNamedPropertyMappingStorage class

Représente la propriété nommée mapping

```csharp
public sealed class MapiNamedPropertyMappingStorage : MapiPropertyContainer
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [MapiNamedPropertyMappingStorage](mapinamedpropertymappingstorage)() | Initialise une nouvelle instance du[`MapiNamedPropertyMappingStorage`](../mapinamedpropertymappingstorage) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Obtient la page de code. |
| [Content](../../aspose.email.mapi/mapinamedpropertymappingstorage/content) { get; } | Obtient le contenu |
| [Name](../../aspose.email.mapi/mapinamedpropertymappingstorage/name) { get; } | Obtient le nom |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Obtient la collection de propriétés. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddNamedPropertyMapping](../../aspose.email.mapi/mapinamedpropertymappingstorage/addnamedpropertymapping#addnamedpropertymapping)(MapiProperty, long, Guid) | Ajoute le mappage de propriété nommée pour la propriété nommée numérique. |
| [AddNamedPropertyMapping](../../aspose.email.mapi/mapinamedpropertymappingstorage/addnamedpropertymapping#addnamedpropertymapping_1)(MapiProperty, string, Guid) | Ajoute le mappage de la propriété nommée pour la chaîne nommée propriété. |
| [GetNextAvailablePropertyId](../../aspose.email.mapi/mapinamedpropertymappingstorage/getnextavailablepropertyid)(MapiPropertyType) | Obtient le prochain identifiant de propriété disponible dans le flux d'entrées en fonction du type de données de la propriété. |
| virtual [GetProperty](../../aspose.email.mapi/mapipropertycontainer/getproperty)(PropertyDescriptor) | Obtient la propriété MAPI par descripteur de propriété. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Obtient la valeur de la propriété spécifiée par tag en tant que type booléen. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Obtient la valeur de chaîne de la propriété spécifiée par tag. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Obtient la valeur de la propriété spécifiée par tag en tant que type DateTime. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Obtient la valeur int32 de la propriété spécifiée par tag. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Obtient la valeur de la propriété spécifiée par la balise en tant que type Long (int64). |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Obtient la valeur de la propriété spécifiée par la balise en tant que type court. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Obtient la valeur de chaîne de la propriété spécifiée par tag. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Obtient la valeur de chaîne de la propriété spécifiée par tag. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Détermine si les propriétés de chaîne sont codées en Unicode ou non. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | Définit la propriété. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(PropertyDescriptor, object) | Définit la propriété MAPI. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | Essayez d'obtenir les données de propriété avec la clé de balise spécifiée. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | Obtient la valeur de la propriété spécifiée en tant que type DateTime. Une valeur de retour indique si l'opération a réussi. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | Obtient la valeur de la propriété spécifiée en tant que type Int32. Une valeur de retour indique si l'opération a réussi. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | Obtient la valeur de la propriété spécifiée en tant que type Long. Une valeur de retour indique si l'opération a réussi. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | Essayez d'obtenir une donnée de propriété sous forme de chaîne avec la balise spécifiée. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | Essayez d'obtenir une donnée de propriété sous forme de chaîne avec une balise et une page de code spécifiées. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | Obtient la valeur de la propriété spécifiée en tant que type String. Une valeur de retour indique si l'opération a réussi. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | Obtient la valeur de la propriété spécifiée en tant que type String. Une valeur de retour indique si l'opération a réussi. |

### Voir également

* class [MapiPropertyContainer](../mapipropertycontainer)
* espace de noms [Aspose.Email.Mapi](../../aspose.email.mapi)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
