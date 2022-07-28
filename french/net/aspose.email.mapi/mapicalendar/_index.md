---
title: MapiCalendar
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente lobjet calendrier mapi
type: docs
weight: 17910
url: /fr/net/aspose.email.mapi/mapicalendar/
---
## MapiCalendar class

Représente l'objet calendrier mapi

```csharp
public sealed class MapiCalendar : MapiMessageItemBase
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [MapiCalendar](mapicalendar#constructor)() | Initialise une nouvelle instance du[`MapiCalendar`](../mapicalendar) classe |
| [MapiCalendar](mapicalendar#constructor_1)(string, string, string, DateTime, DateTime) | Initialise une nouvelle instance du[`MapiCalendar`](../mapicalendar) classe. |
| [MapiCalendar](mapicalendar#constructor_2)(string, string, string, DateTime, DateTime, MapiElectronicAddress, MapiRecipientCollection) | Initialise une nouvelle instance du[`MapiCalendar`](../mapicalendar) classe. |
| [MapiCalendar](mapicalendar#constructor_3)(string, string, string, DateTime, DateTime, string, MapiRecipientCollection) | Initialise une nouvelle instance du[`MapiCalendar`](../mapicalendar) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AppointmentCounterProposal](../../aspose.email.mapi/mapicalendar/appointmentcounterproposal) { get; set; } | Obtient ou définit une valeur indiquant si un objet de réponse de réunion est une contre-proposition. |
| [Attachments](../../aspose.email.mapi/mapicalendar/attachments) { get; } | Obtient la collection de pièces jointes. |
| [Attendees](../../aspose.email.mapi/mapicalendar/attendees) { get; set; } | Obtient ou définit les participants |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Contient les informations de facturation associées à un article. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | Obtient le texte du message. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Obtient le[`BodyRtf`](../mapimessageitembase/bodyrtf) du message converti en HTML, si présent, sinon une chaîne vide. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Obtient ou définit le texte du message au format RTF. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Obtient le type du corps. |
| [BusyStatus](../../aspose.email.mapi/mapicalendar/busystatus) { get; set; } | Obtient ou définit le statut occupé |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Contient des mots-clés ou des catégories pour l'objet de message. |
| [ClientIntent](../../aspose.email.mapi/mapicalendar/clientintent) { get; set; } | Obtient ou définit les actions que l'utilisateur a effectuées sur cet objet Meeting. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Obtient la page de code. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Contient les noms des sociétés associées à un article. |
| [EndDate](../../aspose.email.mapi/mapicalendar/enddate) { get; set; } | Obtient ou définit la date et l'heure de fin de l'événement. Si la date n'est pas définie, la valeur par défaut pourDateTime est renvoyé. |
| [EndDateTimeZone](../../aspose.email.mapi/mapicalendar/enddatetimezone) { get; set; } | Obtient ou définit les informations de fuseau horaire qui indiquent le fuseau horaire de la propriété EndDate |
| [IsAllDay](../../aspose.email.mapi/mapicalendar/isallday) { get; set; } | Obtient ou définit une valeur indiquant si l'événement est un événement d'une journée entière |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | L'identifiant de l'élément, utilisé avec un serveur |
| [KeyWords](../../aspose.email.mapi/mapicalendar/keywords) { get; set; } | Obtient ou définit les catégories de l'objet calendrier |
| [Location](../../aspose.email.mapi/mapicalendar/location) { get; set; } | Obtient ou définit l'emplacement de l'événement |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Obtient une chaîne sensible à la casse qui identifie la classe de message définie par l'expéditeur, telle que IPM.Note. La classe de message spécifie le type, l'objectif ou le contenu du message. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Contient les informations de kilométrage associées à un article. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Obtient les propriétés nommées du message. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Obtient le mappage de propriété nommé. |
| [Organizer](../../aspose.email.mapi/mapicalendar/organizer) { get; set; } | Obtient ou définit l'organisateur. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Obtient la collection de propriétés. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Obtient le flux de propriété. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Obtient les destinataires du message. |
| [Recurrence](../../aspose.email.mapi/mapicalendar/recurrence) { get; set; } | Obtient ou définit les propriétés de récurrence |
| [ReminderDelta](../../aspose.email.mapi/mapicalendar/reminderdelta) { get; set; } | Obtient ou définit l'intervalle, en minutes, entre l'heure à laquelle le rappel devient pour la première fois en retard et l'heure de début de l'objet Calendrier |
| [ReminderFileParameter](../../aspose.email.mapi/mapicalendar/reminderfileparameter) { get; set; } | Spécifie le chemin complet du son qu'un client DEVRAIT jouer lorsque le rappel devient en retard. |
| [ReminderSet](../../aspose.email.mapi/mapicalendar/reminderset) { get; set; } | Obtient ou définit une valeur indiquant si un rappel est défini sur l'objet |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Obtient la sensibilité. |
| [Sequence](../../aspose.email.mapi/mapicalendar/sequence) { get; set; } | Obtient ou définit le numéro de séquence |
| [StartDate](../../aspose.email.mapi/mapicalendar/startdate) { get; set; } | Obtient ou définit la date et l'heure de début de l'événement. Si la date n'est pas définie, la valeur par défaut pourDateTime est renvoyé. |
| [StartDateTimeZone](../../aspose.email.mapi/mapicalendar/startdatetimezone) { get; set; } | Obtient ou définit les informations de fuseau horaire qui indiquent le fuseau horaire de la propriété StartDate |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Obtient ou définit l'objet du message. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Obtient un préfixe d'objet qui indique généralement une action sur un message, tel que "FW : " pour le transfert. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Obtient les sous-stockages. |
| [Uid](../../aspose.email.mapi/mapicalendar/uid) { get; set; } | Obtient l'identifiant unique |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Dispose](../../aspose.email.mapi/mapicalendar/dispose)() | Libère toutes les ressources. |
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
| [Save](../../aspose.email.mapi/mapicalendar/save#save)(Stream) | Enregistre l'objet calendrier dans le fichier au format iCalendar en utilisant les options d'enregistrement par défaut |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_3)(string) | Enregistre l'objet calendrier dans le fichier au format iCalendar en utilisant les options d'enregistrement par défaut |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_1)(Stream, AppointmentSaveFormat) | Enregistre l'objet de calendrier dans le flux avec le format spécifié à l'aide des options d'enregistrement par défaut |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_2)(Stream, MapiCalendarSaveOptions) | Enregistre le calendrier dans le flux avec les options d'enregistrement spécifiées |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_4)(string, AppointmentSaveFormat) | Enregistre l'objet de calendrier dans le fichier au format spécifié à l'aide des options d'enregistrement par défaut |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_5)(string, MapiCalendarSaveOptions) | Enregistre l'objet de calendrier dans le fichier au format spécifié à l'aide des options d'enregistrement par défaut |
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
