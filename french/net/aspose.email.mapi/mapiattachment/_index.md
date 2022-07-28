---
title: MapiAttachment
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente la pièce jointe dans le message électronique.
type: docs
weight: 17880
url: /fr/net/aspose.email.mapi/mapiattachment/
---
## MapiAttachment class

Représente la pièce jointe dans le message électronique.

```csharp
public class MapiAttachment : MapiPropertyContainer
```

## Propriétés

| Nom | La description |
| --- | --- |
| [BinaryData](../../aspose.email.mapi/mapiattachment/binarydata) { get; set; } | Obtient ou définit des données de pièces jointes binaires. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Obtient la page de code. |
| [Content](../../aspose.email.mapi/mapiattachment/content) { get; } | Obtient le contenu. |
| [DisplayName](../../aspose.email.mapi/mapiattachment/displayname) { get; } | Obtient le nom d'affichage de l'objet ole dans une pièce jointe. |
| [Extension](../../aspose.email.mapi/mapiattachment/extension) { get; } | Obtient une extension de nom de fichier qui indique le type de document d'une pièce jointe. |
| [FileName](../../aspose.email.mapi/mapiattachment/filename) { get; } | Obtient le nom de fichier de base et l'extension d'une pièce jointe, à l'exclusion du chemin. |
| virtual [ItemId](../../aspose.email.mapi/mapiattachment/itemid) { get; } | L'identifiant de l'élément, utilisé avec un serveur |
| [LongFileName](../../aspose.email.mapi/mapiattachment/longfilename) { get; } | Obtient le nom de fichier long et l'extension d'une pièce jointe, à l'exclusion du chemin. |
| [MimeTag](../../aspose.email.mapi/mapiattachment/mimetag) { get; } | Obtient des informations de formatage sur une pièce jointe Multipurpose Internet Mail Extensions (MIME). |
| [NamedProperties](../../aspose.email.mapi/mapiattachment/namedproperties) { get; } | Obtient les propriétés nommées du message. |
| [ObjectData](../../aspose.email.mapi/mapiattachment/objectdata) { get; } | Obtient un objet de pièce jointe généralement accessible via l'interface OLE IStorage. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Obtient la collection de propriétés. |
| [PropertyStream](../../aspose.email.mapi/mapiattachment/propertystream) { get; } | Obtient le flux de propriété. |
| [SubStorages](../../aspose.email.mapi/mapiattachment/substorages) { get; } | Obtient les sous-stockages. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [GetProperty](../../aspose.email.mapi/mapiattachment/getproperty)(PropertyDescriptor) | Obtient la propriété MAPI par descripteur de propriété. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Obtient la valeur de la propriété spécifiée par tag en tant que type booléen. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Obtient la valeur de chaîne de la propriété spécifiée par tag. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Obtient la valeur de la propriété spécifiée par tag en tant que type DateTime. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Obtient la valeur int32 de la propriété spécifiée par tag. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Obtient la valeur de la propriété spécifiée par la balise en tant que type Long (int64). |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Obtient la valeur de la propriété spécifiée par la balise en tant que type court. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Obtient la valeur de chaîne de la propriété spécifiée par tag. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Obtient la valeur de chaîne de la propriété spécifiée par tag. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Détermine si les propriétés de chaîne sont codées en Unicode ou non. |
| [RemoveProperty](../../aspose.email.mapi/mapiattachment/removeproperty)(long) | Fournit la suppression correcte de la propriété de toutes les collections. |
| [Save](../../aspose.email.mapi/mapiattachment/save#save)(Stream) | Enregistrer le contenu de la pièce jointe. |
| [Save](../../aspose.email.mapi/mapiattachment/save#save_1)(string) | Enregistrer le contenu de la pièce jointe. |
| override [SetProperty](../../aspose.email.mapi/mapiattachment/setproperty#setproperty)(MapiProperty) | Définit la propriété. |
| override [SetProperty](../../aspose.email.mapi/mapiattachment/setproperty#setproperty_1)(PropertyDescriptor, object) | Définit la propriété MAPI. |
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
