---
title: ExtendedCalendar
second_title: Référence de l'API Aspose.Email pour .NET
description: Initialise une nouvelle instance de la classe ExtendedCalendar.
type: docs
weight: 10
url: /fr/net/aspose.email.clients.google/extendedcalendar/extendedcalendar/
---
## ExtendedCalendar() {#constructor}

Initialise une nouvelle instance de la classe ExtendedCalendar.

```csharp
public ExtendedCalendar()
```

### Voir également

* class [ExtendedCalendar](../../extendedcalendar)
* espace de noms [Aspose.Email.Clients.Google](../../extendedcalendar)
* Assemblée [Aspose.Email](../../../)

---

## ExtendedCalendar(string) {#constructor_1}

Initialise une nouvelle instance de la classe ExtendedCalendar.

```csharp
public ExtendedCalendar(string summary)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| summary | String | Titre du calendrier. |

### Voir également

* class [ExtendedCalendar](../../extendedcalendar)
* espace de noms [Aspose.Email.Clients.Google](../../extendedcalendar)
* Assemblée [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string) {#constructor_2}

Initialise une nouvelle instance de la classe ExtendedCalendar.

```csharp
public ExtendedCalendar(string id, string summary)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| id | String | Identifiant de la ressource. |
| summary | String | Titre du calendrier. |

### Voir également

* class [ExtendedCalendar](../../extendedcalendar)
* espace de noms [Aspose.Email.Clients.Google](../../extendedcalendar)
* Assemblée [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string) {#constructor_3}

Initialise une nouvelle instance de la classe ExtendedCalendar.

```csharp
public ExtendedCalendar(string summary, string description, string location, string timeZone)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| summary | String | Titre du calendrier. |
| description | String | Description du calendrier. |
| location | String | Emplacement géographique du calendrier sous forme de texte libre. |
| timeZone | String | Le fuseau horaire du calendrier. |

### Voir également

* class [ExtendedCalendar](../../extendedcalendar)
* espace de noms [Aspose.Email.Clients.Google](../../extendedcalendar)
* Assemblée [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string, string) {#constructor_4}

Initialise une nouvelle instance de la classe ExtendedCalendar.

```csharp
public ExtendedCalendar(string id, string summary, string description, string location, 
    string timeZone)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| id | String | Identifiant de la ressource. |
| summary | String | Titre du calendrier. |
| description | String | Description du calendrier. |
| location | String | Emplacement géographique du calendrier sous forme de texte libre. |
| timeZone | String | Le fuseau horaire du calendrier. |

### Voir également

* class [ExtendedCalendar](../../extendedcalendar)
* espace de noms [Aspose.Email.Clients.Google](../../extendedcalendar)
* Assemblée [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) {#constructor_5}

Initialise une nouvelle instance de la classe ExtendedCalendar.

```csharp
public ExtendedCalendar(string id, string summary, string description, string location, 
    string timeZone, string summaryOverride, string colorId, string backgroundColor, 
    string foregroundColor, bool hidden, bool selected, AccessRole accessRole, 
    KeyValuePair<ReminderMethods, int>[] defaultReminders, bool primary)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| id | String | Identifiant de la ressource. |
| summary | String | Titre du calendrier. |
| description | String | Description du calendrier. |
| location | String | Emplacement géographique du calendrier sous forme de texte libre. |
| timeZone | String | Le fuseau horaire du calendrier. |
| summaryOverride | String | Le résumé que l'utilisateur authentifié a défini pour ce calendrier. |
| colorId | String | La couleur du calendrier. Il s'agit d'un ID faisant référence à une entrée dans la section "calendrier" de la définition des couleurs (voir le point de terminaison "couleurs"). |
| backgroundColor | String | La couleur principale du calendrier au format '#0088aa'. Cette propriété remplace la propriété colorId basée sur l'index. |
| foregroundColor | String | La couleur de premier plan du calendrier au format '#ffffff'. Cette propriété remplace la propriété colorId basée sur l'index. |
| hidden | Boolean | Indique si le calendrier a été masqué dans la liste. Le défaut est faux. |
| selected | Boolean | Indique si le contenu du calendrier s'affiche dans l'interface utilisateur du calendrier. Le défaut est faux. |
| accessRole | AccessRole | Le rôle d'accès effectif dont dispose l'utilisateur authentifié sur le calendrier. Lecture seulement. Les valeurs possibles sont : |
| defaultReminders | KeyValuePair`2[] | Les rappels par défaut que l'utilisateur authentifié a pour ce calendrier. |
| primary | Boolean | Si le calendrier est le calendrier principal de l'utilisateur authentifié. Lecture seulement. Le défaut est faux. |

### Voir également

* enum [AccessRole](../../accessrole)
* enum [ReminderMethods](../../remindermethods)
* class [ExtendedCalendar](../../extendedcalendar)
* espace de noms [Aspose.Email.Clients.Google](../../extendedcalendar)
* Assemblée [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) {#constructor_6}

Initialise une nouvelle instance de la classe ExtendedCalendar.

```csharp
public ExtendedCalendar(string id, string eTag, string summary, string description, 
    string location, string timeZone, string summaryOverride, string colorId, 
    string backgroundColor, string foregroundColor, bool hidden, bool selected, 
    AccessRole accessRole, KeyValuePair<ReminderMethods, int>[] defaultReminders, bool primary)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| id | String | Identifiant de la ressource. |
| eTag | String | Une balise d'entité |
| summary | String | Titre du calendrier. |
| description | String | Description du calendrier. |
| location | String | Emplacement géographique du calendrier sous forme de texte libre. |
| timeZone | String | Le fuseau horaire du calendrier. |
| summaryOverride | String | Le résumé que l'utilisateur authentifié a défini pour ce calendrier. |
| colorId | String | La couleur du calendrier. Il s'agit d'un ID faisant référence à une entrée dans la section "calendrier" de la définition des couleurs (voir le point de terminaison "couleurs"). |
| backgroundColor | String | La couleur principale du calendrier au format '#0088aa'. Cette propriété remplace la propriété colorId basée sur l'index. |
| foregroundColor | String | La couleur de premier plan du calendrier au format '#ffffff'. Cette propriété remplace la propriété colorId basée sur l'index. |
| hidden | Boolean | Indique si le calendrier a été masqué dans la liste. Le défaut est faux. |
| selected | Boolean | Indique si le contenu du calendrier s'affiche dans l'interface utilisateur du calendrier. Le défaut est faux. |
| accessRole | AccessRole | Le rôle d'accès effectif dont dispose l'utilisateur authentifié sur le calendrier. Lecture seulement. Les valeurs possibles sont : |
| defaultReminders | KeyValuePair`2[] | Les rappels par défaut que l'utilisateur authentifié a pour ce calendrier. |
| primary | Boolean | Si le calendrier est le calendrier principal de l'utilisateur authentifié. Lecture seulement. Le défaut est faux. |

### Voir également

* enum [AccessRole](../../accessrole)
* enum [ReminderMethods](../../remindermethods)
* class [ExtendedCalendar](../../extendedcalendar)
* espace de noms [Aspose.Email.Clients.Google](../../extendedcalendar)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
