---
title: ExtendedCalendar
second_title: Aspose.Email per riferimento all'API .NET
description: Inizializza una nuova istanza della classe ExtendedCalendar.
type: docs
weight: 10
url: /it/net/aspose.email.clients.google/extendedcalendar/extendedcalendar/
---
## ExtendedCalendar() {#constructor}

Inizializza una nuova istanza della classe ExtendedCalendar.

```csharp
public ExtendedCalendar()
```

### Guarda anche

* class [ExtendedCalendar](../../extendedcalendar)
* spazio dei nomi [Aspose.Email.Clients.Google](../../extendedcalendar)
* assemblea [Aspose.Email](../../../)

---

## ExtendedCalendar(string) {#constructor_1}

Inizializza una nuova istanza della classe ExtendedCalendar.

```csharp
public ExtendedCalendar(string summary)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| summary | String | Titolo del calendario. |

### Guarda anche

* class [ExtendedCalendar](../../extendedcalendar)
* spazio dei nomi [Aspose.Email.Clients.Google](../../extendedcalendar)
* assemblea [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string) {#constructor_2}

Inizializza una nuova istanza della classe ExtendedCalendar.

```csharp
public ExtendedCalendar(string id, string summary)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | String | Identificatore della risorsa. |
| summary | String | Titolo del calendario. |

### Guarda anche

* class [ExtendedCalendar](../../extendedcalendar)
* spazio dei nomi [Aspose.Email.Clients.Google](../../extendedcalendar)
* assemblea [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string) {#constructor_3}

Inizializza una nuova istanza della classe ExtendedCalendar.

```csharp
public ExtendedCalendar(string summary, string description, string location, string timeZone)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| summary | String | Titolo del calendario. |
| description | String | Descrizione del calendario. |
| location | String | Posizione geografica del calendario come testo in formato libero. |
| timeZone | String | Il fuso orario del calendario. |

### Guarda anche

* class [ExtendedCalendar](../../extendedcalendar)
* spazio dei nomi [Aspose.Email.Clients.Google](../../extendedcalendar)
* assemblea [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string, string) {#constructor_4}

Inizializza una nuova istanza della classe ExtendedCalendar.

```csharp
public ExtendedCalendar(string id, string summary, string description, string location, 
    string timeZone)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | String | Identificatore della risorsa. |
| summary | String | Titolo del calendario. |
| description | String | Descrizione del calendario. |
| location | String | Posizione geografica del calendario come testo in formato libero. |
| timeZone | String | Il fuso orario del calendario. |

### Guarda anche

* class [ExtendedCalendar](../../extendedcalendar)
* spazio dei nomi [Aspose.Email.Clients.Google](../../extendedcalendar)
* assemblea [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) {#constructor_5}

Inizializza una nuova istanza della classe ExtendedCalendar.

```csharp
public ExtendedCalendar(string id, string summary, string description, string location, 
    string timeZone, string summaryOverride, string colorId, string backgroundColor, 
    string foregroundColor, bool hidden, bool selected, AccessRole accessRole, 
    KeyValuePair<ReminderMethods, int>[] defaultReminders, bool primary)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | String | Identificatore della risorsa. |
| summary | String | Titolo del calendario. |
| description | String | Descrizione del calendario. |
| location | String | Posizione geografica del calendario come testo in formato libero. |
| timeZone | String | Il fuso orario del calendario. |
| summaryOverride | String | Il riepilogo che l'utente autenticato ha impostato per questo calendario. |
| colorId | String | Il colore del calendario. Questo è un ID che fa riferimento a una voce nella sezione "calendario" della definizione dei colori (vedi l'endpoint "colori"). |
| backgroundColor | String | Il colore principale del calendario nel formato '#0088aa'. Questa proprietà sostituisce la proprietà colorId basata sull'indice. |
| foregroundColor | String | Il colore di primo piano del calendario nel formato '#ffffff'. Questa proprietà sostituisce la proprietà colorId basata sull'indice. |
| hidden | Boolean | Se il calendario è stato nascosto dall'elenco. L'impostazione predefinita è Falso. |
| selected | Boolean | Se il contenuto del calendario viene visualizzato nell'interfaccia utente del calendario. L'impostazione predefinita è Falso. |
| accessRole | AccessRole | Il ruolo di accesso effettivo che l'utente autenticato ha nel calendario. Sola lettura. I valori possibili sono: |
| defaultReminders | KeyValuePair`2[] | I promemoria predefiniti che l'utente autenticato ha per questo calendario. |
| primary | Boolean | Indica se il calendario è il calendario principale dell'utente autenticato. Sola lettura. L'impostazione predefinita è Falso. |

### Guarda anche

* enum [AccessRole](../../accessrole)
* enum [ReminderMethods](../../remindermethods)
* class [ExtendedCalendar](../../extendedcalendar)
* spazio dei nomi [Aspose.Email.Clients.Google](../../extendedcalendar)
* assemblea [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) {#constructor_6}

Inizializza una nuova istanza della classe ExtendedCalendar.

```csharp
public ExtendedCalendar(string id, string eTag, string summary, string description, 
    string location, string timeZone, string summaryOverride, string colorId, 
    string backgroundColor, string foregroundColor, bool hidden, bool selected, 
    AccessRole accessRole, KeyValuePair<ReminderMethods, int>[] defaultReminders, bool primary)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | String | Identificatore della risorsa. |
| eTag | String | Un tag di entità |
| summary | String | Titolo del calendario. |
| description | String | Descrizione del calendario. |
| location | String | Posizione geografica del calendario come testo in formato libero. |
| timeZone | String | Il fuso orario del calendario. |
| summaryOverride | String | Il riepilogo che l'utente autenticato ha impostato per questo calendario. |
| colorId | String | Il colore del calendario. Questo è un ID che fa riferimento a una voce nella sezione "calendario" della definizione dei colori (vedi l'endpoint "colori"). |
| backgroundColor | String | Il colore principale del calendario nel formato '#0088aa'. Questa proprietà sostituisce la proprietà colorId basata sull'indice. |
| foregroundColor | String | Il colore di primo piano del calendario nel formato '#ffffff'. Questa proprietà sostituisce la proprietà colorId basata sull'indice. |
| hidden | Boolean | Se il calendario è stato nascosto dall'elenco. L'impostazione predefinita è Falso. |
| selected | Boolean | Se il contenuto del calendario viene visualizzato nell'interfaccia utente del calendario. L'impostazione predefinita è Falso. |
| accessRole | AccessRole | Il ruolo di accesso effettivo che l'utente autenticato ha nel calendario. Sola lettura. I valori possibili sono: |
| defaultReminders | KeyValuePair`2[] | I promemoria predefiniti che l'utente autenticato ha per questo calendario. |
| primary | Boolean | Indica se il calendario è il calendario principale dell'utente autenticato. Sola lettura. L'impostazione predefinita è Falso. |

### Guarda anche

* enum [AccessRole](../../accessrole)
* enum [ReminderMethods](../../remindermethods)
* class [ExtendedCalendar](../../extendedcalendar)
* spazio dei nomi [Aspose.Email.Clients.Google](../../extendedcalendar)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
