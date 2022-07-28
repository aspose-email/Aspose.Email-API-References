---
title: MapiTask
second_title: Référence de l'API Aspose.Email pour .NET
description: Représente lobjet Tâche Outlook.
type: docs
weight: 18670
url: /fr/net/aspose.email.mapi/mapitask/
---
## MapiTask class

Représente l'objet Tâche Outlook.

```csharp
public class MapiTask : MapiMessageItemBase
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [MapiTask](mapitask#constructor)() | Initialise une nouvelle instance du[`MapiTask`](../mapitask) classe. |
| [MapiTask](mapitask#constructor_1)(string, string, DateTime, DateTime) | Initialise une nouvelle instance du[`MapiTask`](../mapitask) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AcceptanceState](../../aspose.email.mapi/mapitask/acceptancestate) { get; set; } | Obtient ou définit l'état d'acceptation de la tâche. |
| [ActualEffort](../../aspose.email.mapi/mapitask/actualeffort) { get; set; } | Obtient ou définit le nombre de minutes que l'utilisateur a réellement passées à travailler sur une tâche. |
| [Attachments](../../aspose.email.mapi/mapitask/attachments) { get; } | Obtient la collection de pièces jointes. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Contient les informations de facturation associées à un article. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | Obtient le texte du message. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Obtient le[`BodyRtf`](../mapimessageitembase/bodyrtf) du message converti en HTML, si présent, sinon une chaîne vide. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Obtient ou définit le texte du message au format RTF. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Obtient le type du corps. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Contient des mots-clés ou des catégories pour l'objet de message. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Obtient la page de code. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Contient les noms des sociétés associées à un article. |
| [DateCompleted](../../aspose.email.mapi/mapitask/datecompleted) { get; set; } | Obtient ou définit la date à laquelle l'utilisateur a terminé le travail sur la tâche. |
| [DueDate](../../aspose.email.mapi/mapitask/duedate) { get; set; } | Obtient ou définit la date à laquelle l'utilisateur s'attend à ce que le travail sur la tâche soit terminé. |
| [EstimatedEffort](../../aspose.email.mapi/mapitask/estimatedeffort) { get; set; } | Obtient ou définit le nombre de minutes pendant lesquelles l'utilisateur s'attend à travailler sur une tâche. |
| [Flags](../../aspose.email.mapi/mapitask/flags) { get; } | Obtient les drapeaux d'indication de l'objet Tâche. |
| [History](../../aspose.email.mapi/mapitask/history) { get; set; } | Obtient ou définit le type de modification qui a été apportée pour la dernière fois à l'objet Tâche. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | L'identifiant de l'élément, utilisé avec un serveur |
| [LastUpdate](../../aspose.email.mapi/mapitask/lastupdate) { get; set; } | Obtient ou définit la date et l'heure de la dernière modification apportée à l'objet Tâche. |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Obtient une chaîne sensible à la casse qui identifie la classe de message définie par l'expéditeur, telle que IPM.Note. La classe de message spécifie le type, l'objectif ou le contenu du message. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Contient les informations de kilométrage associées à un article. |
| [Mode](../../aspose.email.mapi/mapitask/mode) { get; set; } | Obtient ou définit l'état d'affectation de l'objet Task. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Obtient les propriétés nommées du message. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Obtient le mappage de propriété nommé. |
| [PercentComplete](../../aspose.email.mapi/mapitask/percentcomplete) { get; set; } | Obtient ou définit la progression de l'utilisateur sur une tâche. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Obtient la collection de propriétés. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Obtient le flux de propriété. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Obtient les destinataires du message. |
| [Recurrence](../../aspose.email.mapi/mapitask/recurrence) { get; set; } | Obtient ou définit les propriétés de récurrence. |
| [ReminderFileParameter](../../aspose.email.mapi/mapitask/reminderfileparameter) { get; set; } | Spécifie le chemin complet du son qu'un client DEVRAIT jouer lorsque le rappel devient en retard. |
| [ReminderSet](../../aspose.email.mapi/mapitask/reminderset) { get; set; } | Obtient ou définit une valeur indiquant si un rappel est défini sur l'objet |
| [ReminderTime](../../aspose.email.mapi/mapitask/remindertime) { get; set; } | Obtient ou définit l'heure du signal initial pour un rappel |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Obtient la sensibilité. |
| [StartDate](../../aspose.email.mapi/mapitask/startdate) { get; set; } | Obtient ou définit la date à laquelle l'utilisateur s'attend à ce que le travail sur la tâche commence. |
| [State](../../aspose.email.mapi/mapitask/state) { get; set; } | Obtient ou définit l'état actuel de l'affectation de l'objet Tâche. |
| [Status](../../aspose.email.mapi/mapitask/status) { get; set; } | Obtient ou définit l'état de la progression de l'utilisateur sur la tâche. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Obtient ou définit l'objet du message. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Obtient un préfixe d'objet qui indique généralement une action sur un message, tel que "FW : " pour le transfert. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Obtient les sous-stockages. |
| [Users](../../aspose.email.mapi/mapitask/users) { get; set; } | Obtient ou définit des informations sur les utilisateurs de la tâche. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo)(Stream) | Crée une instance de MapiTask à partir du flux spécifié. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo_2)(string) | Crée une instance de MapiTask à partir du fichier .ics spécifié. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo_1)(Stream, bool) | Crée une instance de MapiTask à partir du flux spécifié. |
| static [FromVTodo](../../aspose.email.mapi/mapitask/fromvtodo#fromvtodo_3)(string, bool) | Crée une instance de MapiTask à partir du fichier .ics spécifié. |
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
| [Save](../../aspose.email.mapi/mapitask/save#save)(Stream, TaskSaveFormat) | Enregistre ceci[`MapiTask`](../mapitask) au flux donné en utilisant le format spécifié. |
| [Save](../../aspose.email.mapi/mapitask/save#save_1)(string, TaskSaveFormat) | Enregistre ceci[`MapiTask`](../mapitask) dans le fichier en utilisant le format spécifié. |
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
