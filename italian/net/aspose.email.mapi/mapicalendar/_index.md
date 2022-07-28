---
title: MapiCalendar
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta loggetto calendario mapi
type: docs
weight: 17910
url: /it/net/aspose.email.mapi/mapicalendar/
---
## MapiCalendar class

Rappresenta l'oggetto calendario mapi

```csharp
public sealed class MapiCalendar : MapiMessageItemBase
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MapiCalendar](mapicalendar#constructor)() | Inizializza una nuova istanza di[`MapiCalendar`](../mapicalendar) classe |
| [MapiCalendar](mapicalendar#constructor_1)(string, string, string, DateTime, DateTime) | Inizializza una nuova istanza di[`MapiCalendar`](../mapicalendar) classe. |
| [MapiCalendar](mapicalendar#constructor_2)(string, string, string, DateTime, DateTime, MapiElectronicAddress, MapiRecipientCollection) | Inizializza una nuova istanza di[`MapiCalendar`](../mapicalendar) classe. |
| [MapiCalendar](mapicalendar#constructor_3)(string, string, string, DateTime, DateTime, string, MapiRecipientCollection) | Inizializza una nuova istanza di[`MapiCalendar`](../mapicalendar) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AppointmentCounterProposal](../../aspose.email.mapi/mapicalendar/appointmentcounterproposal) { get; set; } | Ottiene o imposta un valore che indica se un oggetto Meeting Response è una controproposta. |
| [Attachments](../../aspose.email.mapi/mapicalendar/attachments) { get; } | Ottiene la raccolta di allegati. |
| [Attendees](../../aspose.email.mapi/mapicalendar/attendees) { get; set; } | Ottiene o imposta i partecipanti |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Contiene le informazioni di fatturazione associate a un articolo. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body) { get; set; } | Ottiene il testo del messaggio. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Ottiene il[`BodyRtf`](../mapimessageitembase/bodyrtf) del messaggio convertito in HTML, se presente, altrimenti una stringa vuota. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Ottiene o imposta il testo del messaggio in formato RTF. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Ottiene il tipo del corpo. |
| [BusyStatus](../../aspose.email.mapi/mapicalendar/busystatus) { get; set; } | Ottiene o imposta lo stato occupato |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Contiene parole chiave o categorie per l'oggetto messaggio. |
| [ClientIntent](../../aspose.email.mapi/mapicalendar/clientintent) { get; set; } | Ottiene o imposta le azioni eseguite dall'utente su questo oggetto Meeting. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Ottiene la tabella codici. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Contiene i nomi delle aziende associate a un articolo. |
| [EndDate](../../aspose.email.mapi/mapicalendar/enddate) { get; set; } | Ottiene o imposta la data e l'ora di fine dell'evento. Se la data non è impostata, valore predefinito perDateTime viene restituito. |
| [EndDateTimeZone](../../aspose.email.mapi/mapicalendar/enddatetimezone) { get; set; } | Ottiene o imposta le informazioni sul fuso orario che indicano il fuso orario della proprietà EndDate |
| [IsAllDay](../../aspose.email.mapi/mapicalendar/isallday) { get; set; } | Ottiene o imposta un valore che indica se l'evento è un evento che dura tutto il giorno |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | L'ID elemento, utilizzato con un server |
| [KeyWords](../../aspose.email.mapi/mapicalendar/keywords) { get; set; } | Ottiene o imposta le categorie dell'oggetto calendario |
| [Location](../../aspose.email.mapi/mapicalendar/location) { get; set; } | Ottiene o imposta la posizione dell'evento |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Ottiene una stringa con distinzione tra maiuscole e minuscole che identifica la classe del messaggio definita dal mittente, ad esempio IPM.Note. La classe del messaggio specifica il tipo, lo scopo o il contenuto del messaggio. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Contiene le informazioni sul chilometraggio associate a un articolo. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Ottiene le proprietà denominate del messaggio. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Ottiene la mappatura della proprietà denominata. |
| [Organizer](../../aspose.email.mapi/mapicalendar/organizer) { get; set; } | Ottiene o imposta l'organizer. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Ottiene la raccolta di proprietà. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Ottiene il flusso di proprietà. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Ottiene i destinatari del messaggio. |
| [Recurrence](../../aspose.email.mapi/mapicalendar/recurrence) { get; set; } | Ottiene o imposta le proprietà di ricorrenza |
| [ReminderDelta](../../aspose.email.mapi/mapicalendar/reminderdelta) { get; set; } | Ottiene o imposta l'intervallo, in minuti, tra l'ora in cui il promemoria diventa scaduto per la prima volta e l'ora di inizio dell'oggetto Calendario |
| [ReminderFileParameter](../../aspose.email.mapi/mapicalendar/reminderfileparameter) { get; set; } | Specifica il percorso completo del suono che un client DOVREBBE riprodurre quando il promemoria è scaduto. |
| [ReminderSet](../../aspose.email.mapi/mapicalendar/reminderset) { get; set; } | Ottiene o imposta un valore che indica se un promemoria è impostato sull'oggetto |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Ottiene la sensibilità. |
| [Sequence](../../aspose.email.mapi/mapicalendar/sequence) { get; set; } | Ottiene o imposta il numero di sequenza |
| [StartDate](../../aspose.email.mapi/mapicalendar/startdate) { get; set; } | Ottiene o imposta la data e l'ora di inizio dell'evento. Se la data non è impostata, valore predefinito perDateTime viene restituito. |
| [StartDateTimeZone](../../aspose.email.mapi/mapicalendar/startdatetimezone) { get; set; } | Ottiene o imposta le informazioni sul fuso orario che indicano il fuso orario della proprietà StartDate |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Ottiene o imposta l'oggetto del messaggio. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Ottiene un prefisso dell'oggetto che in genere indica un'azione su un messaggio, ad esempio "FW: " per l'inoltro. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Ottiene i sottoarchivi. |
| [Uid](../../aspose.email.mapi/mapicalendar/uid) { get; set; } | Ottiene l'identificatore univoco |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Dispose](../../aspose.email.mapi/mapicalendar/dispose)() | Rilascia tutte le risorse. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty)(PropertyDescriptor) | Ottiene la proprietà MAPI in base al descrittore di proprietà. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Ottiene il valore della proprietà specificata dal tag come tipo booleano. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Ottiene il valore stringa della proprietà specificata da tag. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Ottiene il valore della proprietà specificata dal tag come tipo DateTime. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Ottiene il valore int32 della proprietà specificata dal tag. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Ottiene il valore della proprietà specificata dal tag come tipo Long (int64). |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Ottiene il valore della proprietà specificata dal tag come tipo Short. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Ottiene il valore stringa della proprietà specificata da tag. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Ottiene il valore stringa della proprietà specificata da tag. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Determina se le proprietà della stringa sono codificate in Unicode o meno. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | Fornisce la corretta rimozione della proprietà da tutte le raccolte. |
| [Save](../../aspose.email.mapi/mapicalendar/save#save)(Stream) | Salva l'oggetto calendario nel file con il formato iCalendar utilizzando le opzioni di salvataggio predefinite |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_3)(string) | Salva l'oggetto calendario nel file con il formato iCalendar utilizzando le opzioni di salvataggio predefinite |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_1)(Stream, AppointmentSaveFormat) | Salva l'oggetto calendario nello stream con il formato specificato utilizzando le opzioni di salvataggio predefinite |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_2)(Stream, MapiCalendarSaveOptions) | Salva il calendario nello stream con le opzioni di salvataggio specificate |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_4)(string, AppointmentSaveFormat) | Salva l'oggetto calendario nel file con il formato specificato utilizzando le opzioni di salvataggio predefinite |
| [Save](../../aspose.email.mapi/mapicalendar/save#save_5)(string, MapiCalendarSaveOptions) | Salva l'oggetto calendario nel file con il formato specificato utilizzando le opzioni di salvataggio predefinite |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType) | Imposta il contenuto del corpo. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType, bool) | Imposta il contenuto del corpo. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf)(string, bool) | Ottiene o imposta il testo del messaggio in formato RTF. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags)(MapiMessageFlags) | Imposta i flag dei messaggi. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | Imposta la proprietà. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty)(PropertyDescriptor, object) | Imposta la proprietà MAPI. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | Prova a ottenere i dati della proprietà con la chiave del tag specificata. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | Ottiene il valore della proprietà specificata come tipo DateTime. Un valore restituito indica se l'operazione è riuscita. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | Ottiene il valore della proprietà specificata come tipo Int32. Un valore restituito indica se l'operazione è riuscita. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | Ottiene il valore della proprietà specificata come tipo Long. Un valore restituito indica se l'operazione è riuscita. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | Prova a ottenere i dati di una proprietà come stringa con il tag specificato. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | Prova a ottenere i dati di una proprietà come stringa con tag e codepage specificati. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | Ottiene il valore della proprietà specificata come tipo String. Un valore restituito indica se l'operazione è riuscita. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | Ottiene il valore della proprietà specificata come tipo String. Un valore restituito indica se l'operazione è riuscita. |

### Guarda anche

* class [MapiMessageItemBase](../mapimessageitembase)
* spazio dei nomi [Aspose.Email.Mapi](../../aspose.email.mapi)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
