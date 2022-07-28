---
title: PidTagPropertyDescriptor
second_title: Référence de l'API Aspose.Email pour .NET
description: La classe contient des informations sur la description de la propriété.
type: docs
weight: 18990
url: /fr/net/aspose.email.mapi/pidtagpropertydescriptor/
---
## PidTagPropertyDescriptor class

La classe contient des informations sur la description de la propriété.

```csharp
public class PidTagPropertyDescriptor : PropertyDescriptor
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_1)(long) | Initialise une nouvelle instance du[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class Propriété définie par un ID de propriété 16 bits et un type de propriété 16 bits. L'ID de propriété d'une propriété balisée est comprise entre 0x001 et 0x7FFF. Les ID de propriété dans la plage 0x8000 � 0x8FFF sont réservés pour l'affectation aux propriétés nommées |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor)(int, PropertyDataType) | Initialise une nouvelle instance du[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class Propriété définie par un ID de propriété 16 bits et un type de propriété 16 bits. L'ID de propriété d'une propriété balisée est comprise entre 0x001 et 0x7FFF. Les ID de propriété dans la plage 0x8000 � 0x8FFF sont réservés pour l'affectation aux propriétés nommées |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_2)(string, int, PropertyDataType) | Initialise une nouvelle instance du[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class Propriété définie par un ID de propriété 16 bits et un type de propriété 16 bits. L'ID de propriété d'une propriété balisée est comprise entre 0x001 et 0x7FFF. Les ID de propriété dans la plage 0x8000 � 0x8FFF sont réservés pour l'affectation aux propriétés nommées |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_4)(string, string, long) | Initialise une nouvelle instance du[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class Propriété définie par un ID de propriété 16 bits et un type de propriété 16 bits. L'ID de propriété d'une propriété balisée est comprise entre 0x001 et 0x7FFF. Les ID de propriété dans la plage 0x8000 � 0x8FFF sont réservés pour l'affectation aux propriétés nommées |
| [PidTagPropertyDescriptor](pidtagpropertydescriptor#constructor_3)(string, string, int, PropertyDataType) | Initialise une nouvelle instance du[`PidTagPropertyDescriptor`](../pidtagpropertydescriptor) class Propriété définie par un ID de propriété 16 bits et un type de propriété 16 bits. L'ID de propriété d'une propriété balisée est comprise entre 0x001 et 0x7FFF. Les ID de propriété dans la plage 0x8000 � 0x8FFF sont réservés pour l'affectation aux propriétés nommées |

## Propriétés

| Nom | La description |
| --- | --- |
| [CanonicalName](../../aspose.email.mapi/propertydescriptor/canonicalname) { get; } | Le nom utilisé pour faire référence à la propriété dans la documentation. Le préfixe du nom canonique identifie les caractéristiques de base d'une propriété pour l'implémenteur. La structure de dénomination canonique utilise trois catégories désignées par les préfixes suivants pour le nom de propriété canonique : * Préfixe PidLid : propriétés identifiées par une quantité 32 bits non signée avec un jeu de propriétés. * Préfixe PidName : propriétés identifiées par un nom de chaîne avec un ensemble de propriétés. * Préfixe PidTag : propriétés identifiées par une quantité non signée de 16 bits. |
| [DataType](../../aspose.email.mapi/propertydescriptor/datatype) { get; } | Le type de valeur de propriété, tel que décrit dans [MS-OXCDATA], qui spécifie le type de valeurs autorisées pour la propriété. |
| [Id](../../aspose.email.mapi/pidtagpropertydescriptor/id) { get; } | Obtient une quantité 16 bits non signée qui identifie une propriété balisée. Les ID de propriété ne sont pas nécessairement uniques. À l'exception des ID de propriété compris entre 0x6800 et 0x7BFF, la combinaison de l'ID de propriété et du type de données est unique. Les ID de propriété compris entre 0x6800 et 0x7BFF sont définis par la classe de message. |
| [MultipleValuesDataType](../../aspose.email.mapi/propertydescriptor/multiplevaluesdatatype) { get; } | Indique si le type de données contient plusieurs valeurs |
| [Name](../../aspose.email.mapi/propertydescriptor/name) { get; } | Obtient une chaîne qui identifie une propriété. |
| [Tag](../../aspose.email.mapi/pidtagpropertydescriptor/tag) { get; } | Une balise de propriété est un nombre de 32 bits qui contient un identifiant de propriété unique dans les bits 16 à 31 et un type de propriété dans les bits 0 à 15. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Equals](../../aspose.email.mapi/pidtagpropertydescriptor/equals#equals_1)(object) | Détermine si le System.Object spécifié est égal au System.Object. actuel |
| override [Equals](../../aspose.email.mapi/pidtagpropertydescriptor/equals#equals)(PropertyDescriptor) | Indique si l'objet courant est égal à un autre objet du même type. |
| override [GetHashCode](../../aspose.email.mapi/pidtagpropertydescriptor/gethashcode)() | Sert de fonction de hachage pour un type. |
| override [ToString](../../aspose.email.mapi/pidtagpropertydescriptor/tostring)() | Renvoie une chaîne qui représente la description de la propriété. |
| [operator ==](../../aspose.email.mapi/pidtagpropertydescriptor/op_equality) | Détermine si les objets spécifiés sont égaux les uns aux autres. |
| [explicit operator](../../aspose.email.mapi/pidtagpropertydescriptor/op_explicit) | Convertit la valeur de la balise en propriété balisée |
| [operator !=](../../aspose.email.mapi/pidtagpropertydescriptor/op_inequality) | Détermine si les objets spécifiés ne sont pas égaux les uns aux autres. |

### Voir également

* class [PropertyDescriptor](../propertydescriptor)
* espace de noms [Aspose.Email.Mapi](../../aspose.email.mapi)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
