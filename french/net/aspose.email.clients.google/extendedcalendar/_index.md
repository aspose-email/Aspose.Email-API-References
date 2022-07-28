---
title: ExtendedCalendar
second_title: Référence de l'API Aspose.Email pour .NET
description: Un ensemble de métadonnées étendues telles que des couleurs pour un seul calendrier.
type: docs
weight: 15700
url: /fr/net/aspose.email.clients.google/extendedcalendar/
---
## ExtendedCalendar class

Un ensemble de métadonnées étendues, telles que des couleurs, pour un seul calendrier.

```csharp
public class ExtendedCalendar : Calendar
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ExtendedCalendar](extendedcalendar#constructor)() | Initialise une nouvelle instance de la classe ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_1)(string) | Initialise une nouvelle instance de la classe ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_2)(string, string) | Initialise une nouvelle instance de la classe ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_3)(string, string, string, string) | Initialise une nouvelle instance de la classe ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_4)(string, string, string, string, string) | Initialise une nouvelle instance de la classe ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_5)(string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) | Initialise une nouvelle instance de la classe ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_6)(string, string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) | Initialise une nouvelle instance de la classe ExtendedCalendar. |

## Propriétés

| Nom | La description |
| --- | --- |
| virtual [AccessRole](../../aspose.email.clients.google/extendedcalendar/accessrole) { get; } | Le rôle d'accès effectif que l'utilisateur authentifié a sur le calendrier. Lecture seulement. Les valeurs possibles sont : |
| virtual [BackgroundColor](../../aspose.email.clients.google/extendedcalendar/backgroundcolor) { get; set; } | La couleur principale du calendrier au format '#0088aa'. Cette propriété remplace la propriété colorId basée sur l'index. |
| virtual [ColorId](../../aspose.email.clients.google/extendedcalendar/colorid) { get; set; } | La couleur du calendrier. Il s'agit d'un ID faisant référence à une entrée dans la section "calendrier" de la définition des couleurs (voir le point de terminaison "couleurs"). |
| virtual [ConferenceProperties](../../aspose.email.clients.google/calendar/conferenceproperties) { get; } | Obtient les propriétés de conférence pour ce calendrier. |
| virtual [DefaultReminders](../../aspose.email.clients.google/extendedcalendar/defaultreminders) { get; set; } | Les rappels par défaut que l'utilisateur authentifié a pour ce calendrier. |
| virtual [Description](../../aspose.email.clients.google/calendar/description) { get; set; } | Description du calendrier. |
| virtual [ETag](../../aspose.email.clients.google/basedataobject/etag) { get; set; } | Un ETag ou une balise d'entité est l'un des nombreux mécanismes que HTTP fournit pour la validation du cache Web et qui permet à un client de faire des requêtes conditionnelles. Cela permet aux caches d'être plus efficaces et d'économiser de la bande passante, car un serveur Web n'a pas besoin d'envoyer une réponse complète si le contenu n'a pas changé. Les ETags peuvent également être utilisés pour un contrôle optimiste de la concurrence, afin d'éviter que les mises à jour simultanées d'une ressource ne s'écrasent mutuellement. |
| virtual [ForegroundColor](../../aspose.email.clients.google/extendedcalendar/foregroundcolor) { get; set; } | La couleur de premier plan du calendrier au format '#ffffff'. Cette propriété remplace la propriété colorId basée sur l'index. |
| virtual [Hidden](../../aspose.email.clients.google/extendedcalendar/hidden) { get; set; } | Indique si le calendrier a été masqué dans la liste. La valeur par défaut est Faux. |
| virtual [Id](../../aspose.email.clients.google/basedataobject/id) { get; set; } | Identifiant de la ressource. |
| virtual [Kind](../../aspose.email.clients.google/basedataobject/kind) { get; } | Type de ressource |
| virtual [Location](../../aspose.email.clients.google/calendar/location) { get; set; } | Emplacement géographique du calendrier sous forme de texte libre. |
| virtual [NotificationSettings](../../aspose.email.clients.google/extendedcalendar/notificationsettings) { get; set; } | Les notifications que l'utilisateur authentifié reçoit pour ce calendrier. |
| virtual [Primary](../../aspose.email.clients.google/extendedcalendar/primary) { get; set; } | Si le calendrier est le calendrier principal de l'utilisateur authentifié. Lecture seulement. La valeur par défaut est Faux. |
| virtual [Selected](../../aspose.email.clients.google/extendedcalendar/selected) { get; set; } | Indique si le contenu du calendrier s'affiche dans l'interface utilisateur du calendrier. La valeur par défaut est Faux. |
| virtual [Summary](../../aspose.email.clients.google/calendar/summary) { get; set; } | Titre du calendrier. |
| virtual [SummaryOverride](../../aspose.email.clients.google/extendedcalendar/summaryoverride) { get; set; } | Le résumé que l'utilisateur authentifié a défini pour ce calendrier. |
| virtual [TimeZone](../../aspose.email.clients.google/calendar/timezone) { get; set; } | Le fuseau horaire du calendrier. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [ToString](../../aspose.email.clients.google/extendedcalendar/tostring)() | Renvoie une chaîne qui représente l'instance de l'objet. |

## Des champs

| Nom | La description |
| --- | --- |
| const [ExtendedCalendarKind](../../aspose.email.clients.google/extendedcalendar/extendedcalendarkind) | Type de la ressource "calendar#calendarListEntry". |
| const [ListKind](../../aspose.email.clients.google/extendedcalendar/listkind) | Type de la liste de ressources "calendar#calendarList". |

### Voir également

* class [Calendar](../calendar)
* espace de noms [Aspose.Email.Clients.Google](../../aspose.email.clients.google)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
