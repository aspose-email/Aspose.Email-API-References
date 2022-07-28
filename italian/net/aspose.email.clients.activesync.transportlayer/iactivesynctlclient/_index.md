---
title: IActiveSyncTLClient
second_title: Aspose.Email per riferimento all'API .NET
description: Interfaccia client ActiveSync
type: docs
weight: 1310
url: /it/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/
---
## IActiveSyncTLClient interface

Interfaccia client ActiveSync

```csharp
public interface IActiveSyncTLClient : IBaseActiveSyncTLClient
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AirSyncKeys](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/airsynckeys) { get; } | Contiene un valore utilizzato dal server per contrassegnare lo stato di sincronizzazione di ogni raccolta sincronizzata. Dove la chiave del dizionario è l'ID del server e il valore del dizionario è SyncKey. Per i comandi GetItemEstimate e Sync. |
| [FoldersSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderssynckey) { get; } | Utilizzato dal server per tenere traccia dello stato corrente del client. Solo per operazioni con cartelle |
| [HeartbeatInterval](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/heartbeatinterval) { get; set; } | L'elemento HeartbeatInterval è un elemento figlio dell'elemento Ping nelle richieste e risposte dei comandi Ping. Nelle richieste di comando Ping, specifica il periodo di tempo, in secondi, che il server DOVREBBE attendere prima di inviare una risposta se non vengono aggiunti nuovi elementi al set di cartelle specificato, come specificato nella sezione 3.1.5.6. Anche l'elemento HeartbeatInterval viene restituito dal server con un codice di stato 5 e specifica l'intervallo minimo o massimo consentito quando il client ha richiesto un intervallo di heartbeat al di fuori dell'intervallo accettabile. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [FolderCreate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldercreate)(string, string, UserCreatedFolderTypes) | FolderCreate crea una nuova cartella come cartella figlio della cartella principale specificata. |
| [FolderDelete](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderdelete)(string) | Elimina la raccolta con l'identificatore corrispondente. |
| [FolderSync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldersync#foldersync)() | FolderSync sincronizza la gerarchia delle raccolte ma non sincronizza gli elementi nelle raccolte stesse. |
| [FolderSync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/foldersync#foldersync_1)(bool) | FolderSync sincronizza la gerarchia delle raccolte ma non sincronizza gli elementi nelle raccolte stesse. |
| [FolderUpdate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderupdate#folderupdate)(FolderInfo) | Il comando FolderUpdate sposta una cartella da una posizione all'altra sul server. Il comando serve anche per rinominare una cartella. |
| [FolderUpdate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/folderupdate#folderupdate_1)(string, string, string) | Il comando FolderUpdate sposta una cartella da una posizione all'altra sul server. Il comando serve anche per rinominare una cartella. |
| [GetAttachment](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getattachment)(string) | GetAttachment recupera un allegato e-mail dal server. GetAttachment non è supportato quando la versione del protocollo è 14.0 o 14.1. Utilizzare invece l'elemento Fetch del comando ItemOperations. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate_2)(IEnumerable&lt;ItemEstimateRequest&gt;) | Il comando GetItemEstimate ottiene una stima del numero di elementi in una raccolta o cartella sul server che devono essere sincronizzati. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate)(ItemEstimateRequest) | Il comando GetItemEstimate ottiene una stima del numero di elementi in una raccolta o cartella sul server che devono essere sincronizzati. |
| [GetItemEstimate](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/getitemestimate#getitemestimate_1)(params ItemEstimateRequest[]) | Il comando GetItemEstimate ottiene una stima del numero di elementi in una raccolta o cartella sul server che devono essere sincronizzati. |
| [ItemOperations](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/itemoperations)(ItemOperationsRequest) | ItemOperations fornisce la gestione online in batch delle operazioni Recupero, EmptyFolderContents e Sposta. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_3)(IEnumerable&lt;MeetingResponseRequest&gt;) | Accetta, accetta provvisoriamente o rifiuta una convocazione di riunione nella cartella Posta in arrivo o nella cartella Calendario dell'utente. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_2)(params MeetingResponseRequest[]) | Accetta, accetta provvisoriamente o rifiuta una convocazione di riunione nella cartella Posta in arrivo o nella cartella Calendario dell'utente. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse)(UserResponse, string, string) | Accetta, accetta provvisoriamente o rifiuta una convocazione di riunione nella cartella Posta in arrivo o nella cartella Calendario dell'utente. |
| [MeetingResponse](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse#meetingresponse_1)(UserResponse, string, string, string, string) | Accetta, accetta provvisoriamente o rifiuta una convocazione di riunione nella cartella Posta in arrivo o nella cartella Calendario dell'utente. |
| [MoveItem](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitem)(string, string, string) | Il comando MoveItems sposta uno o più elementi da una cartella del server a un'altra. |
| [MoveItems](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitems#moveitems_1)(IEnumerable&lt;MoveItemData&gt;) | Il comando MoveItems sposta uno o più elementi da una cartella del server a un'altra. |
| [MoveItems](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/moveitems#moveitems)(params MoveItemData[]) | Il comando MoveItems sposta uno o più elementi da una cartella del server a un'altra. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_4)(IEnumerable&lt;PingParameter&gt;) | Il comando Ping viene utilizzato per richiedere al server di monitorare le cartelle specificate per le modifiche che richiederebbero la risincronizzazione del client. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping)(params PingParameter[]) | Il comando Ping viene utilizzato per richiedere al server di monitorare le cartelle specificate per le modifiche che richiederebbero la risincronizzazione del client. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_2)(int, IEnumerable&lt;PingParameter&gt;) | Il comando Ping viene utilizzato per richiedere al server di monitorare le cartelle specificate per le modifiche che richiederebbero la risincronizzazione del client. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_1)(int, params PingParameter[]) | Il comando Ping viene utilizzato per richiedere al server di monitorare le cartelle specificate per le modifiche che richiederebbero la risincronizzazione del client. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_5)(string, FolderClass) | Il comando Ping viene utilizzato per richiedere al server di monitorare le cartelle specificate per le modifiche che richiederebbero la risincronizzazione del client. |
| [Ping](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping#ping_3)(int, string, FolderClass) | Il comando Ping viene utilizzato per richiedere al server di monitorare le cartelle specificate per le modifiche che richiederebbero la risincronizzazione del client. |
| [Provision](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/provision)(ProvisionRequest) | Il comando Provision consente ai dispositivi client di richiedere al server le impostazioni dei criteri di sicurezza impostate dall'amministratore, come il requisito di lunghezza della password PIN (Personal Identification Number) minimo. |
| [ResetAirSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetairsynckey#resetairsynckey)() | Reimposta chiavi di sincronizzazione per GetItemEstimate e operazioni di sincronizzazione per tutte le raccolte. |
| [ResetAirSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetairsynckey#resetairsynckey_1)(string) | Reimposta SyncKey per GetItemEstimate e operazioni di sincronizzazione per la raccolta definita. |
| [ResetFoldersSyncKey](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resetfolderssynckey)() | Reimposta SyncKey per operazioni con cartelle |
| [ResolveRecipients](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/resolverecipients)(ResolveRecipientsRequest) | ResolveRecipients viene utilizzato per risolvere un elenco di destinatari forniti, per recuperare le loro informazioni sulla disponibilità e, facoltativamente, per recuperare i loro certificati S/MIME in modo che i client possano inviare messaggi di posta elettronica S/MIME crittografati. Recupero delle informazioni sulla disponibilità l'utilizzo dell'elemento Availability nel comando ResolveRecipients non è supportato quando la versione del protocollo è 12.1. |
| [Search](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/search)(SearchRequest) | La ricerca viene utilizzata per trovare voci in una rubrica, una cassetta postale o una raccolta documenti (UNC o Windows SharePoint Services). |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail)(string) | SendMail viene utilizzato dai client per inviare messaggi di posta elettronica in formato MIME al server. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_1)(string, bool) | SendMail viene utilizzato dai client per inviare messaggi di posta elettronica in formato MIME al server. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_2)(string, bool, string) | SendMail viene utilizzato dai client per inviare messaggi di posta elettronica in formato MIME al server. |
| [SendMail](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sendmail#sendmail_3)(string, bool, string, string) | SendMail viene utilizzato dai client per inviare messaggi di posta elettronica in formato MIME al server. |
| [Settings](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/settings)(SettingsRequest) | Le impostazioni supportano le operazioni di recupero e impostazione sulle proprietà globali e le impostazioni Fuori sede (OOF) per l'utente. Le Impostazioni inviano anche le informazioni sul dispositivo al server, implementano il ripristino della password del dispositivo/numero di identificazione personale (PIN) e recuperano un elenco di indirizzi e-mail dell'utente. |
| [SmartForward](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/smartforward)(SmartRequest) | Il comando SmartForward viene utilizzato dai client per inoltrare i messaggi senza recuperare il messaggio originale completo dal server. |
| [SmartReply](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/smartreply)(SmartRequest) | Il comando SmartReply viene utilizzato dai client per rispondere ai messaggi senza recuperare il messaggio originale completo dal server. |
| [Sync](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/sync)(SyncRequest) | La sincronizzazione sincronizza le modifiche in una raccolta tra il client e il server. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert)(IEnumerable&lt;X509Certificate&gt;) | ValidateCert viene utilizzato dal client per convalidare un certificato che è stato ricevuto tramite una mail S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_4)(X509Certificate) | Il comando ValidateCert viene utilizzato dal client per convalidare un certificato ricevuto tramite e-mail S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_1)(IEnumerable&lt;X509Certificate&gt;, bool) | ValidateCert viene utilizzato dal client per convalidare un certificato che è stato ricevuto tramite una mail S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_2)(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;) | ValidateCert viene utilizzato dal client per convalidare un certificato che è stato ricevuto tramite una mail S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_5)(X509Certificate, bool) | ValidateCert viene utilizzato dal client per convalidare un certificato che è stato ricevuto tramite una mail S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_6)(X509Certificate, IEnumerable&lt;X509Certificate&gt;) | ValidateCert viene utilizzato dal client per convalidare un certificato che è stato ricevuto tramite una mail S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_3)(IEnumerable&lt;X509Certificate&gt;, IEnumerable&lt;X509Certificate&gt;, bool) | ValidateCert viene utilizzato dal client per convalidare un certificato che è stato ricevuto tramite una mail S/MIME. |
| [ValidateCert](../../aspose.email.clients.activesync.transportlayer/iactivesynctlclient/validatecert#validatecert_7)(X509Certificate, IEnumerable&lt;X509Certificate&gt;, bool) | ValidateCert viene utilizzato dal client per convalidare un certificato che è stato ricevuto tramite una mail S/MIME. |

### Guarda anche

* interface [IBaseActiveSyncTLClient](../ibaseactivesynctlclient)
* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
