---
title: MapiContact
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente les informations de contact Outlook
type: docs
weight: 18190
url: /fr/net/aspose.email.mapi/mapicontact/
---
## MapiContact class

Représente les informations de contact Outlook

```csharp
public sealed class MapiContact : MapiMessageItemBase
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [MapiContact](mapicontact#constructor)() | Initialise une nouvelle instance du[`MapiContact`](../mapicontact) classe |
| [MapiContact](mapicontact#constructor_1)(string, string) | Initialise une nouvelle instance du[`MapiContact`](../mapicontact) classe. |
| [MapiContact](mapicontact#constructor_2)(string, string, string) | Initialise une nouvelle instance du[`MapiContact`](../mapicontact) classe. |
| [MapiContact](mapicontact#constructor_3)(string, string, string, string) | Initialise une nouvelle instance du[`MapiContact`](../mapicontact) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapicontact/attachments) { get; } | Obtient les pièces jointes dans le contact. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Contient les informations de facturation associées à un article. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | Obtient le texte du message. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Obtient le[`BodyRtf`](../mapimessageitembase/bodyrtf) du message converti en HTML, si présent, sinon une chaîne vide. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Obtient ou définit le texte du message au format RTF. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Obtient le type du corps. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Contient des mots-clés ou des catégories pour l'objet de message. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Obtient la page de code. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Contient les noms des sociétés associées à un article. |
| [ElectronicAddresses](../../aspose.email.mapi/mapicontact/electronicaddresses) { get; set; } | Spécifiez les propriétés pour jusqu'à trois adresses e-mail différentes et trois adresses de fax différentes |
| [Events](../../aspose.email.mapi/mapicontact/events) { get; set; } | Spécifier les événements associés à un contact |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | L'identifiant de l'élément, utilisé avec un serveur |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Obtient une chaîne sensible à la casse qui identifie la classe de message définie par l'expéditeur, telle que IPM.Note. La classe de message spécifie le type, l'objectif ou le contenu du message. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Contient les informations de kilométrage associées à un article. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Obtient les propriétés nommées du message. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Obtient le mappage de propriété nommé. |
| [NameInfo](../../aspose.email.mapi/mapicontact/nameinfo) { get; set; } | Les propriétés permettent de spécifier le nom de la personne représentée par le contact |
| [OtherFields](../../aspose.email.mapi/mapicontact/otherfields) { get; set; } | Spécifiez d'autres champs de contact. |
| [PersonalInfo](../../aspose.email.mapi/mapicontact/personalinfo) { get; set; } | Spécifiez d'autres informations de contact supplémentaires |
| [Photo](../../aspose.email.mapi/mapicontact/photo) { get; set; } | Contient une photo de contact[`MapiContactPhoto`](../mapicontactphoto) . |
| [PhysicalAddresses](../../aspose.email.mapi/mapicontact/physicaladdresses) { get; set; } | Spécifiez trois adresses physiques : Adresse personnelle, Adresse professionnelle et Autre adresse. L'une des adresses peut être marquée comme Adresse postale |
| [ProfessionalInfo](../../aspose.email.mapi/mapicontact/professionalinfo) { get; set; } | Les propriétés sont utilisées pour stocker les détails professionnels de la personne représentée par le contact |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Obtient la collection de propriétés. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Obtient le flux de propriété. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Obtient les destinataires du message. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Obtient la sensibilité. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Obtient ou définit l'objet du message. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Obtient un préfixe d'objet qui indique généralement une action sur un message, tel que "FW : " pour le transfert. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Obtient les sous-stockages. |
| [Telephones](../../aspose.email.mapi/mapicontact/telephones) { get; set; } | Spécifiez les numéros de téléphone pour le contact |

## Méthodes

| Nom | La description |
| --- | --- |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard)(Stream) | Lectures[`MapiContact`](../mapicontact) à partir du flux spécifié contenant vCard. Les versions de vCard prises en charge sont 2.1 et 3.0 |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard_2)(string) | Lectures[`MapiContact`](../mapicontact) à partir du fichier vCard spécifié Les versions de vCard prises en charge sont 2.1 et 3.0 |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard_1)(Stream, Encoding) | Lectures[`MapiContact`](../mapicontact) à partir du flux spécifié contenant vCard. Les versions de vCard prises en charge sont 2.1 et 3.0 |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard#fromvcard_3)(string, Encoding) | Lectures[`MapiContact`](../mapicontact) à partir du fichier vCard spécifié Les versions de vCard prises en charge sont 2.1 et 3.0 |
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
| [GetUnderlyingMessage](../../aspose.email.mapi/mapicontact/getunderlyingmessage)() | Obtenez le MapiMessage qui représente le contact. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Détermine si les propriétés de chaîne sont codées en Unicode ou non. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | Fournit la suppression correcte de la propriété de toutes les collections. |
| [Save](../../aspose.email.mapi/mapicontact/save#save)(Stream) | Enregistre ceci[`MapiContact`](../mapicontact) dans le flux donné au format vCard. La version vCard prise en charge est 2.1 |
| [Save](../../aspose.email.mapi/mapicontact/save#save_3)(string) | Enregistre ceci[`MapiContact`](../mapicontact) au fichier vCard avec une option par défaut. La version vCard prise en charge est 2.1 |
| [Save](../../aspose.email.mapi/mapicontact/save#save_1)(Stream, ContactSaveFormat) | Enregistre ceci[`MapiContact`](../mapicontact) au flux donné avec un format utilisant les options par défaut. Le format de sauvegarde pris en charge est vCard |
| [Save](../../aspose.email.mapi/mapicontact/save#save_2)(Stream, ContactSaveOptions) | Enregistre ceci[`MapiContact`](../mapicontact) au flux donné en utilisant les options de sauvegarde spécifiées. Les options de sauvegarde prises en charge sont[`VCardSaveOptions`](../../aspose.email.personalinfo.vcard/vcardsaveoptions) |
| [Save](../../aspose.email.mapi/mapicontact/save#save_4)(string, ContactSaveFormat) | Enregistre ceci[`MapiContact`](../mapicontact)au fichier spécifié avec un format utilisant les options par défaut. Le format de sauvegarde pris en charge est vCard. |
| [Save](../../aspose.email.mapi/mapicontact/save#save_5)(string, ContactSaveOptions) | Enregistre ceci[`MapiContact`](../mapicontact) dans le fichier à l'aide des options d'enregistrement spécifiées. Les options d'enregistrement prises en charge sont[`VCardSaveOptions`](../../aspose.email.personalinfo.vcard/vcardsaveoptions) |
| override [SetBodyContent](../../aspose.email.mapi/mapicontact/setbodycontent#setbodycontent)(string, BodyContentType) | Définit le contenu du corps. |
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
