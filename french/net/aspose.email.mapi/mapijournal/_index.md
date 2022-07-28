---
title: MapiJournal
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente lobjet Journal Outlook.
type: docs
weight: 18420
url: /fr/net/aspose.email.mapi/mapijournal/
---
## MapiJournal class

Représente l'objet Journal Outlook.

```csharp
public sealed class MapiJournal : MapiMessageItemBase
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [MapiJournal](mapijournal#constructor)() | Initialise une nouvelle instance du[`MapiJournal`](../mapijournal) classe. |
| [MapiJournal](mapijournal#constructor_1)(string, string, string, string) | Initialise une nouvelle instance du[`MapiJournal`](../mapijournal) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapimessageitembase/attachments) { get; } | Obtient les pièces jointes dans le message. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Contient les informations de facturation associées à un article. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | Obtient le texte du message. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Obtient le[`BodyRtf`](../mapimessageitembase/bodyrtf) du message converti en HTML, si présent, sinon une chaîne vide. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Obtient ou définit le texte du message au format RTF. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Obtient le type du corps. |
| [BriefDescription](../../aspose.email.mapi/mapijournal/briefdescription) { get; set; } | Obtient ou définit la brève description de l'activité en cours d'enregistrement. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Contient des mots-clés ou des catégories pour l'objet de message. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Obtient la page de code. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Contient les noms des sociétés associées à un article. |
| [Description](../../aspose.email.mapi/mapijournal/description) { get; set; } | Obtient ou définit la description de l'activité en cours d'enregistrement. |
| [DocumentStatus](../../aspose.email.mapi/mapijournal/documentstatus) { get; set; } | Obtient ou définit l'état du document. |
| [Duration](../../aspose.email.mapi/mapijournal/duration) { get; } | Obtient la durée de l'activité. |
| [EndTime](../../aspose.email.mapi/mapijournal/endtime) { get; set; } | Obtient ou définit l'heure à laquelle l'activité s'est terminée. |
| [Flags](../../aspose.email.mapi/mapijournal/flags) { get; set; } | Obtient ou définit un indicateur contenant des métadonnées sur l'objet Journal. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | L'identifiant de l'élément, utilisé avec un serveur |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Obtient une chaîne sensible à la casse qui identifie la classe de message définie par l'expéditeur, telle que IPM.Note. La classe de message spécifie le type, l'objectif ou le contenu du message. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Contient les informations de kilométrage associées à un article. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Obtient les propriétés nommées du message. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Obtient le mappage de propriété nommé. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Obtient la collection de propriétés. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Obtient le flux de propriété. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Obtient les destinataires du message. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Obtient la sensibilité. |
| [StartTime](../../aspose.email.mapi/mapijournal/starttime) { get; set; } | Obtient ou définit l'heure à laquelle l'activité a commencé. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Obtient ou définit l'objet du message. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Obtient un préfixe d'objet qui indique généralement une action sur un message, tel que "FW : " pour le transfert. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Obtient les sous-stockages. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose)() | Effectue des tâches définies par l'application associées à la libération, à la libération ou à la réinitialisation des ressources non gérées. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty)(PropertyDescriptor) | Obtient la propriété MAPI par descripteur de propriété. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Obtient la valeur de la propriété spécifiée par tag en tant que type booléen. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Obtient la valeur de chaîne de la propriété spécifiée par tag. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Obtient la valeur de la propriété spécifiée par tag en tant que type DateTime. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Obtient la valeur int32 de la propriété spécifiée par tag. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Obtient la valeur de la propriété spécifiée par la balise en tant que type Long (int64). |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Obtient la valeur de la propriété spécifiée par la balise en tant que type court. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Obtient la valeur de chaîne de la propriété spécifiée par tag. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Obtient la valeur de chaîne de la propriété spécifiée par tag. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Détermine si les propriétés de chaîne sont codées en Unicode ou non. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | Fournit la suppression correcte de la propriété de toutes les collections. |
| [Save](../../aspose.email.mapi/mapijournal/save#save)(Stream) | Enregistre le flux spécifié. |
| [Save](../../aspose.email.mapi/mapijournal/save#save_1)(string) | Enregistre le nom de fichier spécifié. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType) | Définit le contenu du corps. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType, bool) | Définit le contenu du corps. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf)(string, bool) | Obtient ou définit le texte du message au format RTF. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags)(MapiMessageFlags) | Définit les indicateurs de message. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | Définit la propriété. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty)(PropertyDescriptor, object) | Définit la propriété MAPI. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | Essayez d'obtenir les données de propriété avec la clé de balise spécifiée. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | Obtient la valeur de la propriété spécifiée en tant que type DateTime. Une valeur de retour indique si l'opération a réussi. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | Obtient la valeur de la propriété spécifiée en tant que type Int32. Une valeur de retour indique si l'opération a réussi. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | Obtient la valeur de la propriété spécifiée en tant que type Long. Une valeur de retour indique si l'opération a réussi. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | Essayez d'obtenir une donnée de propriété sous forme de chaîne avec la balise spécifiée. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | Essayez d'obtenir une donnée de propriété sous forme de chaîne avec une balise et une page de code spécifiées. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | Obtient la valeur de la propriété spécifiée en tant que type String. Une valeur de retour indique si l'opération a réussi. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | Obtient la valeur de la propriété spécifiée en tant que type String. Une valeur de retour indique si l'opération a réussi. |

### Voir également

* class [MapiMessageItemBase](../mapimessageitembase)
* espace de noms [Aspose.Email.Mapi](../../aspose.email.mapi)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
