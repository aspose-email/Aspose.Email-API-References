---
title: ExtendedCalendar
second_title: Aspose.Email für .NET-API-Referenz
description: Initialisiert eine neue Instanz der ExtendedCalendar-Klasse.
type: docs
weight: 10
url: /de/net/aspose.email.clients.google/extendedcalendar/extendedcalendar/
---
## ExtendedCalendar() {#constructor}

Initialisiert eine neue Instanz der ExtendedCalendar-Klasse.

```csharp
public ExtendedCalendar()
```

### Siehe auch

* class [ExtendedCalendar](../../extendedcalendar)
* namensraum [Aspose.Email.Clients.Google](../../extendedcalendar)
* Montage [Aspose.Email](../../../)

---

## ExtendedCalendar(string) {#constructor_1}

Initialisiert eine neue Instanz der ExtendedCalendar-Klasse.

```csharp
public ExtendedCalendar(string summary)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| summary | String | Titel des Kalenders. |

### Siehe auch

* class [ExtendedCalendar](../../extendedcalendar)
* namensraum [Aspose.Email.Clients.Google](../../extendedcalendar)
* Montage [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string) {#constructor_2}

Initialisiert eine neue Instanz der ExtendedCalendar-Klasse.

```csharp
public ExtendedCalendar(string id, string summary)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | String | Kennung der Ressource. |
| summary | String | Titel des Kalenders. |

### Siehe auch

* class [ExtendedCalendar](../../extendedcalendar)
* namensraum [Aspose.Email.Clients.Google](../../extendedcalendar)
* Montage [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string) {#constructor_3}

Initialisiert eine neue Instanz der ExtendedCalendar-Klasse.

```csharp
public ExtendedCalendar(string summary, string description, string location, string timeZone)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| summary | String | Titel des Kalenders. |
| description | String | Beschreibung des Kalenders. |
| location | String | Geografischer Standort des Kalenders als Freitext. |
| timeZone | String | Die Zeitzone des Kalenders. |

### Siehe auch

* class [ExtendedCalendar](../../extendedcalendar)
* namensraum [Aspose.Email.Clients.Google](../../extendedcalendar)
* Montage [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string, string) {#constructor_4}

Initialisiert eine neue Instanz der ExtendedCalendar-Klasse.

```csharp
public ExtendedCalendar(string id, string summary, string description, string location, 
    string timeZone)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | String | Kennung der Ressource. |
| summary | String | Titel des Kalenders. |
| description | String | Beschreibung des Kalenders. |
| location | String | Geografischer Standort des Kalenders als Freitext. |
| timeZone | String | Die Zeitzone des Kalenders. |

### Siehe auch

* class [ExtendedCalendar](../../extendedcalendar)
* namensraum [Aspose.Email.Clients.Google](../../extendedcalendar)
* Montage [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) {#constructor_5}

Initialisiert eine neue Instanz der ExtendedCalendar-Klasse.

```csharp
public ExtendedCalendar(string id, string summary, string description, string location, 
    string timeZone, string summaryOverride, string colorId, string backgroundColor, 
    string foregroundColor, bool hidden, bool selected, AccessRole accessRole, 
    KeyValuePair<ReminderMethods, int>[] defaultReminders, bool primary)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | String | Kennung der Ressource. |
| summary | String | Titel des Kalenders. |
| description | String | Beschreibung des Kalenders. |
| location | String | Geografischer Standort des Kalenders als Freitext. |
| timeZone | String | Die Zeitzone des Kalenders. |
| summaryOverride | String | Die Zusammenfassung, die der authentifizierte Benutzer für diesen Kalender festgelegt hat. |
| colorId | String | Die Farbe des Kalenders. Dies ist eine ID, die auf einen Eintrag im Abschnitt "Kalender" der Farbdefinition verweist (siehe Endpunkt "Farben"). |
| backgroundColor | String | Die Hauptfarbe des Kalenders im Format '#0088aa'. Diese Eigenschaft ersetzt die indexbasierte colorId-Eigenschaft. |
| foregroundColor | String | Die Vordergrundfarbe des Kalenders im Format '#ffffff'. Diese Eigenschaft ersetzt die indexbasierte colorId-Eigenschaft. |
| hidden | Boolean | Ob der Kalender aus der Liste ausgeblendet wurde. Der Standardwert ist False. |
| selected | Boolean | Ob der Kalenderinhalt in der Kalender-Benutzeroberfläche angezeigt wird. Der Standardwert ist False. |
| accessRole | AccessRole | Die effektive Zugriffsrolle, die der authentifizierte Benutzer für den Kalender hat. Schreibgeschützt. Mögliche Werte sind: |
| defaultReminders | KeyValuePair`2[] | Die Standarderinnerungen, die der authentifizierte Benutzer für diesen Kalender hat. |
| primary | Boolean | Ob der Kalender der primäre Kalender des authentifizierten Benutzers ist. Schreibgeschützt. Der Standardwert ist False. |

### Siehe auch

* enum [AccessRole](../../accessrole)
* enum [ReminderMethods](../../remindermethods)
* class [ExtendedCalendar](../../extendedcalendar)
* namensraum [Aspose.Email.Clients.Google](../../extendedcalendar)
* Montage [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) {#constructor_6}

Initialisiert eine neue Instanz der ExtendedCalendar-Klasse.

```csharp
public ExtendedCalendar(string id, string eTag, string summary, string description, 
    string location, string timeZone, string summaryOverride, string colorId, 
    string backgroundColor, string foregroundColor, bool hidden, bool selected, 
    AccessRole accessRole, KeyValuePair<ReminderMethods, int>[] defaultReminders, bool primary)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | String | Kennung der Ressource. |
| eTag | String | Ein Entity-Tag |
| summary | String | Titel des Kalenders. |
| description | String | Beschreibung des Kalenders. |
| location | String | Geografischer Standort des Kalenders als Freitext. |
| timeZone | String | Die Zeitzone des Kalenders. |
| summaryOverride | String | Die Zusammenfassung, die der authentifizierte Benutzer für diesen Kalender festgelegt hat. |
| colorId | String | Die Farbe des Kalenders. Dies ist eine ID, die auf einen Eintrag im Abschnitt "Kalender" der Farbdefinition verweist (siehe Endpunkt "Farben"). |
| backgroundColor | String | Die Hauptfarbe des Kalenders im Format '#0088aa'. Diese Eigenschaft ersetzt die indexbasierte colorId-Eigenschaft. |
| foregroundColor | String | Die Vordergrundfarbe des Kalenders im Format '#ffffff'. Diese Eigenschaft ersetzt die indexbasierte colorId-Eigenschaft. |
| hidden | Boolean | Ob der Kalender aus der Liste ausgeblendet wurde. Der Standardwert ist False. |
| selected | Boolean | Ob der Kalenderinhalt in der Kalender-Benutzeroberfläche angezeigt wird. Der Standardwert ist False. |
| accessRole | AccessRole | Die effektive Zugriffsrolle, die der authentifizierte Benutzer für den Kalender hat. Schreibgeschützt. Mögliche Werte sind: |
| defaultReminders | KeyValuePair`2[] | Die Standarderinnerungen, die der authentifizierte Benutzer für diesen Kalender hat. |
| primary | Boolean | Ob der Kalender der primäre Kalender des authentifizierten Benutzers ist. Schreibgeschützt. Der Standardwert ist False. |

### Siehe auch

* enum [AccessRole](../../accessrole)
* enum [ReminderMethods](../../remindermethods)
* class [ExtendedCalendar](../../extendedcalendar)
* namensraum [Aspose.Email.Clients.Google](../../extendedcalendar)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
