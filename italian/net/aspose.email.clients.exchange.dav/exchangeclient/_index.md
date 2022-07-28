---
title: ExchangeClient
second_title: Aspose.Email per riferimento all'API .NET
description: La classe ExchangeClient consente alle applicazioni di gestire la casella di posta elettronica in Microsoft Exchange Server utilizzando il protocollo WebDav Exchange Store.
type: docs
weight: 3150
url: /it/net/aspose.email.clients.exchange.dav/exchangeclient/
---
## ExchangeClient class

La classe ExchangeClient consente alle applicazioni di gestire la casella di posta elettronica in Microsoft Exchange Server utilizzando il protocollo WebDav Exchange Store.

```csharp
public sealed class ExchangeClient : ExchangeClientBase
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ExchangeClient](exchangeclient#constructor)(string, ICredentials) | Inizializza una nuova istanza della classe[`Cliente di scambio`](../exchangeclient) |
| [ExchangeClient](exchangeclient#constructor_1)(string, string, string) | Inizializza una nuova istanza della classe[`Cliente di scambio`](../exchangeclient) |
| [ExchangeClient](exchangeclient#constructor_2)(string, string, string, string) | Inizializza una nuova istanza della classe[`Cliente di scambio`](../exchangeclient) |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ClientCertificate](../../aspose.email.clients.exchange.dav/exchangeclient/clientcertificate) { get; set; } | Ottiene o imposta il certificato client. |
| [CookieContainer](../../aspose.email.clients.exchange.dav/exchangeclient/cookiecontainer) { get; set; } | Ottiene o imposta il contenitore dei cookie. |
| virtual [Credentials](../../aspose.email.clients.exchange/exchangeclientbase/credentials) { get; set; } | Ottiene o imposta le credenziali |
| [Encoding](../../aspose.email.clients.exchange.dav/exchangeclient/encoding) { get; set; } | Ottiene o imposta la codifica. |
| [KeepAlive](../../aspose.email.clients.exchange.dav/exchangeclient/keepalive) { get; set; } | Indica se mantenersi in vita. |
| [LogFileName](../../aspose.email.clients.exchange/exchangeclientbase/logfilename) { get; set; } | Ottiene o imposta il nome del file di registro |
| [MailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/mailboxinfo) { get; } | Ottiene le informazioni sulla casella di posta. |
| virtual [MailboxUri](../../aspose.email.clients.exchange/exchangeclientbase/mailboxuri) { get; set; } | Ottiene o imposta la casella di posta uri |
| [PreAuthenticate](../../aspose.email.clients.exchange.dav/exchangeclient/preauthenticate) { get; set; } | Indica se eseguire la preautenticazione. |
| virtual [Proxy](../../aspose.email.clients.exchange/exchangeclientbase/proxy) { get; set; } | Ottiene o imposta il proxy. |
| [SendChunked](../../aspose.email.clients.exchange.dav/exchangeclient/sendchunked) { get; set; } | Ottiene o imposta un valore che indica se [send chunked]. |
| virtual [Timeout](../../aspose.email.clients.exchange/exchangeclientbase/timeout) { get; set; } | Ottiene o imposta il numero di millisecondi di attesa prima del timeout dell'operazione. Il valore predefinito è 100.000 millisecondi (100 secondi). |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/exchangeclientbase/usedateinlogfilename) { get; set; } | Ottiene o imposta un valore che indica se la data deve essere utilizzata nel nome del file di registro. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AppendMessage](../../aspose.email.clients.exchange.dav/exchangeclient/appendmessage#appendmessage)(string, MailMessage) | Carica il messaggio di posta nella cartella specificata |
| [AppendMessage](../../aspose.email.clients.exchange.dav/exchangeclient/appendmessage#appendmessage_1)(string, MailMessage, bool) | Carica il messaggio di posta nella cartella specificata |
| [Backup](../../aspose.email.clients.exchange.dav/exchangeclient/backup#backup)(ExchangeFolderInfoCollection, Stream, BackupOptions) | Esegue il backup del contenuto delle cartelle specificate |
| [Backup](../../aspose.email.clients.exchange.dav/exchangeclient/backup#backup_1)(ExchangeFolderInfoCollection, string, BackupOptions) | Esegue il backup del contenuto delle cartelle specificate |
| [CreateContact](../../aspose.email.clients.exchange.dav/exchangeclient/createcontact)(Contact) | Crea un elemento di contatto nell'archivio di Exchange. |
| [CreateFolder](../../aspose.email.clients.exchange.dav/exchangeclient/createfolder)(string, string) | Crea la nuova cartella con il nome specificato nella cartella principale specificata. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact_1)(Contact) | Elimina il contatto. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact)(MapiContact) | Elimina il contatto. |
| [DeleteContact](../../aspose.email.clients.exchange.dav/exchangeclient/deletecontact#deletecontact_2)(string) | Elimina il contatto. |
| [DeleteFolder](../../aspose.email.clients.exchange.dav/exchangeclient/deletefolder)(string) | Elimina la cartella |
| [DeleteMessage](../../aspose.email.clients.exchange.dav/exchangeclient/deletemessage#deletemessage)(string) | Elimina il messaggio di posta. |
| [DeleteMessage](../../aspose.email.clients.exchange.dav/exchangeclient/deletemessage#deletemessage_1)(string, bool) | Elimina il messaggio di posta. |
| [Dispose](../../aspose.email.clients.exchange/exchangeclientbase/dispose)() | Esegue attività definite dall'applicazione associate alla liberazione, al rilascio o al ripristino di risorse non gestite. |
| [FetchAttachment](../../aspose.email.clients.exchange.dav/exchangeclient/fetchattachment)(string) | Recupera l'allegato |
| [FetchMapiMessage](../../aspose.email.clients.exchange.dav/exchangeclient/fetchmapimessage)(string) | Recupera il messaggio mapi con uri specificato. |
| [FetchMessage](../../aspose.email.clients.exchange.dav/exchangeclient/fetchmessage)(string) | Recupera il messaggio di posta con uri specificato. |
| [FolderExists](../../aspose.email.clients.exchange.dav/exchangeclient/folderexists#folderexists)(string, string) | Verifica se la cartella specificata esiste. |
| [FolderExists](../../aspose.email.clients.exchange.dav/exchangeclient/folderexists#folderexists_1)(string, string, out ExchangeFolderInfo) | Verifica se la cartella specificata esiste. |
| [GetContacts](../../aspose.email.clients.exchange.dav/exchangeclient/getcontacts)(string) | Elenca i contatti che si trovano nella cartella specificata sul server |
| [GetFolderInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getfolderinfo)(string) | Ottiene le informazioni sulla cartella. |
| [GetMailboxes](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxes)() | Elenca le cassette postali nell'elenco indirizzi globale. |
| [GetMailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxinfo#getmailboxinfo)() | Ottieni le informazioni della casella di posta |
| [GetMailboxInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxinfo#getmailboxinfo_1)(string) | Ottiene le informazioni sulla casella di posta |
| [GetMailboxSize](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxsize#getmailboxsize)() | Ottieni la dimensione della cassetta postale |
| [GetMailboxSize](../../aspose.email.clients.exchange.dav/exchangeclient/getmailboxsize#getmailboxsize_1)(string) | Ottieni la dimensione della cassetta postale |
| [GetVersionInfo](../../aspose.email.clients.exchange.dav/exchangeclient/getversioninfo)() | Restituisce la versione del server di scambio info |
| [ListContacts](../../aspose.email.clients.exchange.dav/exchangeclient/listcontacts)(string) | Elenca i contatti che si trovano nella cartella specificata sul server |
| [ListMailboxes](../../aspose.email.clients.exchange.dav/exchangeclient/listmailboxes)() | Elenca le cassette postali nell'elenco indirizzi globale. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages)(string) | Elenca i messaggi. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_3)(string, bool) | Elenca i messaggi nella cartella specificata |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_1)(string, ExchangeListMessagesOptions) | Elenca il messaggio di posta nella cartella specificata. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_4)(string, int) | Elenca i messaggi. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_6)(string, string) | Elenca i messaggi. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_5)(string, int, ExchangeListMessagesOptions) | Elenca i messaggi nella cartella specificata |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_2)(string, MailQuery, bool) | Elenca i messaggi. |
| [ListMessages](../../aspose.email.clients.exchange.dav/exchangeclient/listmessages#listmessages_7)(string, string, bool) | Elenca i messaggi. |
| [ListMessagesById](../../aspose.email.clients.exchange.dav/exchangeclient/listmessagesbyid)(string, string) | Elenca i messaggi per id. |
| [ListPublicFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listpublicfolders)() | Ottiene la raccolta di cartelle pubbliche dalla cartella pubblica principale |
| [ListSubFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listsubfolders#listsubfolders)(ExchangeFolderInfo) | Ottiene la raccolta di cartelle pubbliche figlie da genitore |
| [ListSubFolders](../../aspose.email.clients.exchange.dav/exchangeclient/listsubfolders#listsubfolders_1)(string) | Ottiene la raccolta di cartelle figlie da genitore |
| [MoveItems](../../aspose.email.clients.exchange.dav/exchangeclient/moveitems#moveitems_1)(string, params string[]) | Sposta gli elementi. |
| [MoveItems](../../aspose.email.clients.exchange.dav/exchangeclient/moveitems#moveitems)(string, bool, params string[]) | Sposta gli elementi. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage)(ExchangeMessageInfo, string) | Sposta il messaggio. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_3)(string, string) | Sposta il messaggio. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_1)(ExchangeMessageInfo, string, bool) | Sposta il messaggio. |
| [MoveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/movemessage#movemessage_2)(string, bool, string) | Sposta il messaggio. |
| [ResolveContacts](../../aspose.email.clients.exchange.dav/exchangeclient/resolvecontacts)(string) | Risolve i nomi visualizzati delle cassette postali ambigui. Nota: il numero massimo di contatti restituiti è 100. Questa è una restrizione del comando di scambio utilizzato. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_1)(PersonalStorage, RestoreOptions) | Ripristina le cartelle di scambio dalla memoria personale specificata. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_3)(Stream, RestoreOptions) | Ripristina le cartelle di scambio dalla memoria personale specificata. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_5)(string, RestoreOptions) | Ripristina le cartelle di scambio dal file di archiviazione personale specificato. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore)(PersonalStorage, ExchangeFolderInfoCollection, RestoreOptions) | Ripristina le cartelle di scambio specificate dalla memoria personale specificata. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_2)(Stream, ExchangeFolderInfoCollection, RestoreOptions) | Ripristina le cartelle di scambio specificate dalla memoria personale specificata. |
| [Restore](../../aspose.email.clients.exchange.dav/exchangeclient/restore#restore_4)(string, ExchangeFolderInfoCollection, RestoreOptions) | Ripristina le cartelle di scambio specificate dal file di archiviazione personale specificato. |
| [SaveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/savemessage#savemessage)(string, Stream) | Salva il messaggio. |
| [SaveMessage](../../aspose.email.clients.exchange.dav/exchangeclient/savemessage#savemessage_1)(string, string) | Salva il messaggio di posta specificato dall'uri nel file system locale. Il file del messaggio di posta è in formato conforme a RFC 822 (EML).  se vuoi analizzare i file dei messaggi di posta, usa[`MailMessage`](../../aspose.email/mailmessage). |
| [Send](../../aspose.email.clients.exchange.dav/exchangeclient/send)(MailMessage) | Invia il messaggio di posta elettronica. |
| [SetReadFlag](../../aspose.email.clients.exchange.dav/exchangeclient/setreadflag#setreadflag)(string) | Contrassegna il messaggio specifico come letto. |
| [SetReadFlag](../../aspose.email.clients.exchange.dav/exchangeclient/setreadflag#setreadflag_1)(string, bool) | Contrassegna il messaggio specifico come letto. |

### Guarda anche

* class [ExchangeClientBase](../../aspose.email.clients.exchange/exchangeclientbase)
* spazio dei nomi [Aspose.Email.Clients.Exchange.Dav](../../aspose.email.clients.exchange.dav)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
