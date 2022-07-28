---
title: MapiRecipient
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente les informations sur le destinataire dans le message Microsoft Outlook.
type: docs
weight: 18620
url: /fr/net/aspose.email.mapi/mapirecipient/
---
## MapiRecipient class

Représente les informations sur le destinataire dans le message Microsoft Outlook.

```csharp
public class MapiRecipient : MapiPropertyContainer
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AddressType](../../aspose.email.mapi/mapirecipient/addresstype) { get; } | Obtient le type d'adresse de le destinataire ou l'expéditeur du message. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Obtient la page de code. |
| [Content](../../aspose.email.mapi/mapirecipient/content) { get; } | Obtient le contenu. |
| [DisplayName](../../aspose.email.mapi/mapirecipient/displayname) { get; set; } | Obtient ou définit le nom d'affichage du destinataire ou de l'expéditeur du message . |
| [EmailAddress](../../aspose.email.mapi/mapirecipient/emailaddress) { get; set; } | Obtient ou définit l'adresse e-mail du destinataire ou de l'expéditeur du message . |
| [NamedProperties](../../aspose.email.mapi/mapirecipient/namedproperties) { get; } | Obtient les propriétés nommées du message. |
| [OrganizationEmailAddress](../../aspose.email.mapi/mapirecipient/organizationemailaddress) { get; } | Obtient l'adresse e-mail de l'organisation. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Obtient la collection de propriétés. |
| [PropertyStream](../../aspose.email.mapi/mapirecipient/propertystream) { get; } | Obtient le flux de propriété. |
| [RecipientClass](../../aspose.email.mapi/mapirecipient/recipientclass) { get; } | Obtient le type de destinataire. |
| [RecipientTrackStatus](../../aspose.email.mapi/mapirecipient/recipienttrackstatus) { get; set; } | État de la réponse du destinataire à une demande de réunion. |
| [RecipientType](../../aspose.email.mapi/mapirecipient/recipienttype) { get; } | Obtient le type du destinataire ou de l'expéditeur. |
| [SubStorages](../../aspose.email.mapi/mapirecipient/substorages) { get; } | Obtient les sous-stockages. |

## Méthodes

| Nom | La description |
| --- | --- |
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
