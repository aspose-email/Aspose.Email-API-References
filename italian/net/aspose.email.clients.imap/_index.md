---
title: Aspose.Email.Clients.Imap
second_title: Aspose.Email per riferimento all'API .NET
description: Il Aspose.Email.Client.Imap namespace fornisce classi per accedere a e manipolare i messaggi utilizzando lInternet Message Access Protocol IMAP.
type: docs
weight: 220
url: /it/net/aspose.email.clients.imap/
---
Il **Aspose.Email.Client.Imap** namespace fornisce classi per accedere a e manipolare i messaggi utilizzando l'Internet Message Access Protocol (IMAP).

## Classi

| Classe | Descrizione |
| --- | --- |
| [AppendMessagesResult](./appendmessagesresult) | Contiene il risultato dell'operazione con i messaggi |
| [BackupSettings](./backupsettings) | La classe contiene le opzioni per l'operazione di backup |
| [BaseSearchConditions](./basesearchconditions) | Fornisce la classe base per le condizioni di ricerca. |
| [ESearchOptions](./esearchoptions) | Opzioni risultato ESEARCH Questo metodo funziona solo se il server supporta l'estensione ESEARCH. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |
| [FetchTimeoutException](./fetchtimeoutexception) | Rappresenta l'eccezione generata quando non è possibile leggere un messaggio entro il tempo specificato. |
| [ImapAttachmentInfo](./imapattachmentinfo) | Rappresenta le informazioni di un allegato. |
| [ImapAttachmentInfoCollection](./imapattachmentinfocollection) | Rappresenta la raccolta di[`ImapAttachmentInfo`](../aspose.email.clients.imap/imapattachmentinfo) |
| [ImapClient](./imapclient) | Consente alle applicazioni di accedere e manipolare i messaggi utilizzando l'Internet Message Access Protocol (IMAP). |
| [ImapFolderInfo](./imapfolderinfo) | Rappresenta una cartella IMAP. |
| [ImapFolderInfoCollection](./imapfolderinfocollection) | Fornisce un contenitore per una raccolta di oggetti ImapFolderInfo. |
| [ImapIdentificationInfo](./imapidentificationinfo) | Rappresenta un contenitore di classe con informazioni di identificazione da scambiare tra client di posta e server. Per favore, leggi di più rfc2971 https://tools.ietf.org/html/rfc2971 |
| [ImapMailboxInfo](./imapmailboxinfo) | Contiene set di cassette postali per usi speciali |
| [ImapMessageFlags](./imapmessageflags) | Rappresenta i flag associati al messaggio. |
| [ImapMessageInfo](./imapmessageinfo) | Rappresenta un oggetto messaggio Imap. |
| [ImapMessageInfoCollection](./imapmessageinfocollection) | Fornisce un contenitore per una raccolta di[`ImapMessageInfo`](../aspose.email.clients.imap/imapmessageinfo) oggetti |
| [ImapMonitoringErrorEventArgs](./imapmonitoringerroreventargs) | La classe contiene i dati dell'evento di errore di monitoraggio. |
| [ImapMonitoringErrorEventHandler](./imapmonitoringerroreventhandler) | Rappresenta il metodo che gestirà un evento di errore di monitoraggio imap |
| [ImapMonitoringEventArgs](./imapmonitoringeventargs) | La classe contiene i dati degli eventi di monitoraggio. |
| [ImapMonitoringEventHandler](./imapmonitoringeventhandler) | Rappresenta il metodo che gestirà un evento di monitoraggio imap |
| [ImapNamespace](./imapnamespace) | Rappresenta lo spazio dei nomi IMAP Maggiori dettagli: https://tools.ietf.org/html/rfc2342 |
| [ImapPageInfo](./imappageinfo) | Contiene informazioni sulla pagina recuperata quando vengono utilizzati i metodi di paging. |
| [ImapQueryBuilder](./imapquerybuilder) | Rappresenta il builder dell'espressione di ricerca utilizzata dal protocollo IMAP. |
| [ImapQuota](./imapquota) | Contiene informazioni sulla quota per la risorsa della cassetta postale. |
| [ImapQuotaRoot](./imapquotaroot) | Contiene informazioni sulla radice della quota per la risorsa della cassetta postale. |
| [MessageThreadResult](./messagethreadresult) | Contiene il risultato per i metodi SORT ot THREAD Vedi altro: https://tools.ietf.org/html/rfc5256 |
| [ModificationSequenceField](./modificationsequencefield) | Definisce l'insieme di valori per il campo selezionato da cercare. |
| [PageSettings](./pagesettings) | Le impostazioni per il metodo ImapClient.ListMessagesByPage |
| [PageSettingsAsync](./pagesettingsasync) | Le impostazioni per il metodo asincrono ImapClient.BeginListMessagesByPage. |
| [RangeSeqSet](./rangeseqset) | Contenitore con intervallo di valori da cercare. |
| [ReadLinesTimeoutException](./readlinestimeoutexception) | Rappresenta l'eccezione generata quando non è possibile leggere una risposta dal server entro il tempo specificato. |
| [RestoreSettings](./restoresettings) | Le impostazioni per il metodo ImapClient.Restore |
| [RestoreSettingsAsync](./restoresettingsasync) | Le impostazioni per il metodo asincrono ImapClient.Restore. |
| [SequenceSetBaseValue](./sequencesetbasevalue) | Classe base per diversi contenitori per i valori da cercare. |
| [SequenceSetField](./sequencesetfield) | Definisce l'insieme di valori per il campo selezionato da cercare. |
| [SimpleSeqSet](./simpleseqset) | Contenitore semplice per il valore da cercare. |
| [SortConditions](./sortconditions) | Fornisce le condizioni di ricerca per l'estensione SORT. Compatibile con l'estensione SORT IMAP descritta in https://tools.ietf.org/html/rfc5256 |
| [ThreadSearchConditions](./threadsearchconditions) | Fornisce le condizioni di ricerca per recuperare il thread di posta elettronica. Compatibile con l'estensione THREAD IMAP descritta in https://tools.ietf.org/html/rfc5256 |
| [XGMThreadSearchConditions](./xgmthreadsearchconditions) | Fornisce le condizioni di ricerca per recuperare il thread di posta elettronica. Compatibile con l'estensione IMAP X-GM-EXT-1 descritta in https://developers.google.com/gmail/imap/imap-extensions#checking_for_the_presence_of_extensions. |
## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IAsyncImapClient](./iasyncimapclient) | Consente alle applicazioni di accedere e manipolare messaggi utilizzando l'Internet Message Access Protocol (IMAP). |
| [IImapMonitoringState](./iimapmonitoringstate) | Mantiene lo stato di monitoraggio della cartella. Questo può essere utilizzato per riprendere il monitoraggio della cartella da place dove è stato interrotto quando si è verificato un errore. Uso[`ResumeMonitoring`](../aspose.email.clients.imap/imapclient/resumemonitoring) metodo. |
## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [ImapCommandResult](./imapcommandresult) | Enumera i risultati del comando imap. |
| [ImapKnownAuthenticationType](./imapknownauthenticationtype) |  |
| [ImapListFields](./imaplistfields) | Campi che possono essere recuperati dal server |
| [ImapNamespaceType](./imapnamespacetype) | Rappresenta il tipo di spazio dei nomi IMAP Maggiori dettagli: https://tools.ietf.org/html/rfc2342 |
| [ImapSpecialFolderTypes](./imapspecialfoldertypes) | Rappresenta l'enumerazione delle cassette postali per usi speciali Maggiori dettagli si trovano in RFC6154 http://tools.ietf.org/html/rfc6154 |
| [ImapStatusCode](./imapstatuscode) | Rappresenta le risposte di stato. |
| [ListFoldersOptions](./listfoldersoptions) | Le opzioni di selezione dell'elenco delle cartelle Si prega di notare che queste opzioni sono supportate nel caso in cui il server supporti RFC 5258 "IMAP LIST Command Extensions" Vedere maggiori dettagli in https://tools.ietf.org/html/rfc5258 |
| [ListFoldersReturnOptions](./listfoldersreturnoptions) | Opzioni di ritorno per l'operazione ListFolders Si prega di notare che queste opzioni sono supportate nel caso in cui il server supporti RFC 5258 "IMAP LIST Command Extensions" Vedere maggiori dettagli in https://tools.ietf.org/html/rfc5258 |
| [SortingKey](./sortingkey) | Criteri di ordinamento per il comando "ORDINA" Vedi altro: https://tools.ietf.org/html/rfc5256 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
