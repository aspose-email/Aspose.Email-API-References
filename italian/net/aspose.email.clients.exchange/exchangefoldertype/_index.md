---
title: ExchangeFolderType
second_title: Aspose.Email per riferimento all'API .NET
description: Enumera i tipi di cartelle distinti. Questi valori sono contenuti anche nella proprietà PidTagContainerClass.
type: docs
weight: 3340
url: /it/net/aspose.email.clients.exchange/exchangefoldertype/
---
## ExchangeFolderType enumeration

Enumera i tipi di cartelle distinti. Questi valori sono contenuti anche nella proprietà PidTagContainerClass.

```csharp
public enum ExchangeFolderType
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Undefined | `0` | Il tipo di cartella non è impostato. Il valore viene utilizzato con le seguenti cartelle note: Root: la cartella di livello superiore della gerarchia dell'archivio messaggi, che contiene tutti gli altri oggetti cartella in quell'archivio messaggi. Finder: contiene le cartelle di ricerca predefinite. Dati FreeBusy: contiene i dati sulla disponibilità del proprietario della casella di posta. Top of Personal Folders: la cartella principale della gerarchia dei messaggi interpersonali, che contiene le cartelle dei dati dell'utente, comprese le cartelle più speciali come la cartella Posta in arrivo. Visualizzazioni comuni: contiene i dati per le visualizzazioni predefinite che sono standard per l'archivio messaggi e che possono essere utilizzati da qualsiasi utente di un client che accede all'archivio messaggi. Visualizzazioni personali: contiene i dati per le visualizzazioni definite da un determinato utente. Azione differita: contiene eventuali differiti Messaggio di azione (DAM) o messaggio di errore differito (DEM) risultante dall'esecuzione di regole lato client. |
| Note | `1` | Questo valore rappresenta il tipo di cartella dei messaggi di posta elettronica ("IPF.Note"). Il valore viene utilizzato con le seguenti cartelle note: Posta eliminata - La posizione predefinita per gli oggetti che sono stati eliminati. Posta in uscita - Posta in uscita Gli oggetti del messaggio vengono inseriti in questa cartella quando l'oggetto del messaggio viene inviato. Posta inviata: il percorso predefinito in cui vengono collocate le copie degli oggetti del messaggio di posta elettronica dopo che sono state inviate (inviate). Posta in arrivo: il percorso predefinito per i messaggi in arrivo ( ricevuto) e-mail Oggetti messaggio. Bozze: posizione predefinita per la posta elettronica composta Oggetti messaggio che sono stati salvati ma non inviati. Posta indesiderata: posizione predefinita per la posta elettronica Oggetti messaggio determinati come posta indesiderata da una regola di posta indesiderata. Problemi di sincronizzazione: contiene cartelle che contengono messaggi che indicano problemi particolari riscontrati durante la sincronizzazione tra client e server. Questa è la cartella principale delle cartelle Conflitti, Errori locali e Errori server. Conflitti: contiene oggetti messaggio che indicano conflitti di sincronizzazione tra client e server. Errori locali: contiene messaggi che indicano errori di sincronizzazione lato client. Errori server - Contiene messaggi che indicano errori di sincronizzazione lato server. Elaborazione posta tracciata - Cartella di ricerca che contiene oggetti contrassegnati. Coda spooler - Contiene oggetti e-mail che sono stati inviati o ricevuti. |
| RSSFeeds | `2` | Questo valore rappresenta il tipo di cartella dei messaggi RSS ("IPF.Note.OutlookHomepage"). Il valore viene utilizzato con le seguenti cartelle note: Feed RSS - Contiene messaggi di feed RSS (Really Simple Syndication). |
| Appointment | `3` | Questo valore rappresenta il tipo di cartella "appuntamento" ("IPF.Appuntamento"). Il valore viene utilizzato con le seguenti cartelle ben note: Calendario: contiene oggetti Calendario, ad esempio appuntamenti. |
| Contact | `4` | Questo valore rappresenta il tipo di cartella "contatti" ("IPF.Contact"). Il valore viene utilizzato con le seguenti cartelle note: Contatti - Contiene oggetti Contatto. Contatti consigliati - Contiene oggetti Contatto creati quando un destinatario non è in una rubrica. Ricerca contatti - Cartella di ricerca che visualizza un elenco di contatti che soddisfano i criteri di ricerca. |
| QuickContacts | `5` | Questo valore rappresenta il tipo di cartella per i contatti preferiti ("IPF.Contact.MOC.QuickContacts"). Il valore viene utilizzato con le seguenti cartelle ben note: Contatti rapidi - Contiene oggetti Contatto per i contatti preferiti dell'utente e i contatti di messaggistica istantanea. |
| ImContactsList | `6` | Questo valore rappresenta il tipo di cartella per i contatti di messaggistica istantanea ("IPF.Contact.MOC.ImContactList"). Il valore viene utilizzato con le seguenti cartelle note: Elenco contatti IM - Contiene gli oggetti dell'elenco di distribuzione personale dei contatti preferiti e dei contatti di messaggistica istantanea . |
| DocumentLibraries | `7` | Questo valore rappresenta il tipo di cartella "documenti" ("IPF.ShortcutFolder"). Il valore viene utilizzato con le seguenti cartelle note: Librerie di documenti: contiene i documenti da caricare in una posizione condivisa. |
| Journal | `8` | Questo valore rappresenta il tipo di cartella 'Journal' ("IPF.Journal"). Il valore viene utilizzato con le seguenti cartelle ben note: Journal - Contiene oggetti Journal. |
| StickyNote | `9` | Questo valore rappresenta il tipo di cartella "note" ("IPF.StickyNote"). Il valore viene utilizzato con le seguenti cartelle note: Note - Contiene oggetti Nota. |
| Task | `10` | Questo valore rappresenta il tipo di cartella "Attività" ("IPF.Task"). Il valore viene utilizzato con le seguenti cartelle note: Da fare: cartella di ricerca utilizzata per tenere traccia degli oggetti attività. Attività: contiene oggetti attività. |
| Imap | `11` | Questo valore rappresenta il tipo di cartella 'imap' ("IPF.IMAP"). Utilizzato per migrare dal profilo IMAP a Exchange. |
| Unknown | `12` | Il tipo di cartella è sconosciuto. |

### Guarda anche

* spazio dei nomi [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
