---
title: ExtendedCalendar
second_title: Aspose.Email per riferimento all'API .NET
description: Un insieme di metadati estesi come i colori per un singolo calendario.
type: docs
weight: 15700
url: /it/net/aspose.email.clients.google/extendedcalendar/
---
## ExtendedCalendar class

Un insieme di metadati estesi, come i colori, per un singolo calendario.

```csharp
public class ExtendedCalendar : Calendar
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ExtendedCalendar](extendedcalendar#constructor)() | Inizializza una nuova istanza della classe ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_1)(string) | Inizializza una nuova istanza della classe ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_2)(string, string) | Inizializza una nuova istanza della classe ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_3)(string, string, string, string) | Inizializza una nuova istanza della classe ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_4)(string, string, string, string, string) | Inizializza una nuova istanza della classe ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_5)(string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) | Inizializza una nuova istanza della classe ExtendedCalendar. |
| [ExtendedCalendar](extendedcalendar#constructor_6)(string, string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) | Inizializza una nuova istanza della classe ExtendedCalendar. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [AccessRole](../../aspose.email.clients.google/extendedcalendar/accessrole) { get; } | Il ruolo di accesso effettivo che l'utente autenticato ha nel calendario. Sola lettura. I valori possibili sono: |
| virtual [BackgroundColor](../../aspose.email.clients.google/extendedcalendar/backgroundcolor) { get; set; } | Il colore principale del calendario nel formato '#0088aa'. Questa proprietà sostituisce la proprietà colorId basata sull'indice. |
| virtual [ColorId](../../aspose.email.clients.google/extendedcalendar/colorid) { get; set; } | Il colore del calendario. Questo è un ID che fa riferimento a una voce nella sezione "calendario" della definizione dei colori (vedi l'endpoint "colori"). |
| virtual [ConferenceProperties](../../aspose.email.clients.google/calendar/conferenceproperties) { get; } | Ottiene le proprietà della conferenza per questo calendario. |
| virtual [DefaultReminders](../../aspose.email.clients.google/extendedcalendar/defaultreminders) { get; set; } | I promemoria predefiniti che l'utente autenticato ha per questo calendario. |
| virtual [Description](../../aspose.email.clients.google/calendar/description) { get; set; } | Descrizione del calendario. |
| virtual [ETag](../../aspose.email.clients.google/basedataobject/etag) { get; set; } | Un ETag o un tag di entità è uno dei numerosi meccanismi forniti da HTTP per la convalida della cache Web e che consente a un client di effettuare richieste condizionali. Ciò consente alle cache di essere più efficienti e di risparmiare larghezza di banda, poiché un server Web non ha bisogno di inviare una risposta completa se il contenuto non è cambiato. Gli ETag possono essere utilizzati anche per il controllo ottimistico della concorrenza, come un modo per evitare che gli aggiornamenti simultanei di una risorsa si sovrascrivano a vicenda. |
| virtual [ForegroundColor](../../aspose.email.clients.google/extendedcalendar/foregroundcolor) { get; set; } | Il colore di primo piano del calendario nel formato '#ffffff'. Questa proprietà sostituisce la proprietà colorId basata sull'indice. |
| virtual [Hidden](../../aspose.email.clients.google/extendedcalendar/hidden) { get; set; } | Se il calendario è stato nascosto dall'elenco. Il valore predefinito è Falso. |
| virtual [Id](../../aspose.email.clients.google/basedataobject/id) { get; set; } | Identificatore della risorsa. |
| virtual [Kind](../../aspose.email.clients.google/basedataobject/kind) { get; } | Tipo di risorsa |
| virtual [Location](../../aspose.email.clients.google/calendar/location) { get; set; } | Posizione geografica del calendario come testo in formato libero. |
| virtual [NotificationSettings](../../aspose.email.clients.google/extendedcalendar/notificationsettings) { get; set; } | Le notifiche che l'utente autenticato sta ricevendo per questo calendario. |
| virtual [Primary](../../aspose.email.clients.google/extendedcalendar/primary) { get; set; } | Indica se il calendario è il calendario principale dell'utente autenticato. Sola lettura. Il valore predefinito è Falso. |
| virtual [Selected](../../aspose.email.clients.google/extendedcalendar/selected) { get; set; } | Se il contenuto del calendario viene visualizzato nell'interfaccia utente del calendario. Il valore predefinito è Falso. |
| virtual [Summary](../../aspose.email.clients.google/calendar/summary) { get; set; } | Titolo del calendario. |
| virtual [SummaryOverride](../../aspose.email.clients.google/extendedcalendar/summaryoverride) { get; set; } | Il riepilogo che l'utente autenticato ha impostato per questo calendario. |
| virtual [TimeZone](../../aspose.email.clients.google/calendar/timezone) { get; set; } | Il fuso orario del calendario. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [ToString](../../aspose.email.clients.google/extendedcalendar/tostring)() | Restituisce una stringa che rappresenta l'istanza dell'oggetto. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [ExtendedCalendarKind](../../aspose.email.clients.google/extendedcalendar/extendedcalendarkind) | Tipo di risorsa "calendar#calendarListEntry". |
| const [ListKind](../../aspose.email.clients.google/extendedcalendar/listkind) | Tipo di elenco risorse "calendar#calendarList". |

### Guarda anche

* class [Calendar](../calendar)
* spazio dei nomi [Aspose.Email.Clients.Google](../../aspose.email.clients.google)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
