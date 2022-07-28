---
title: IGraphClient
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta linterfaccia per il client REST di Exchange.
type: docs
weight: 15950
url: /it/net/aspose.email.clients.graph/igraphclient/
---
## IGraphClient interface

Rappresenta l'interfaccia per il client REST di Exchange.

```csharp
public interface IGraphClient : IDisposable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [MultipleServicesTokenProvider](../../aspose.email.clients.graph/igraphclient/multipleservicestokenprovider) { get; set; } | Ottiene o imposta un oggetto che consente di recuperare il token di accesso OAuth. |
| [Proxy](../../aspose.email.clients.graph/igraphclient/proxy) { get; set; } | Ottiene o imposta i dati per l'accesso tramite proxy al server Exchange. |
| [Resource](../../aspose.email.clients.graph/igraphclient/resource) { get; set; } | Ottiene o imposta il tipo di risorsa. |
| [ResourceId](../../aspose.email.clients.graph/igraphclient/resourceid) { get; set; } | Ottiene o imposta l'id della risorsa. Ad esempio per gli utenti può essere il nome dell'entità utente (UPN) o l'id utente |
| [TenantId](../../aspose.email.clients.graph/igraphclient/tenantid) { get; set; } | Ottiene o imposta l'identificatore del tenant |
| [Timeout](../../aspose.email.clients.graph/igraphclient/timeout) { get; set; } | Ottiene o imposta il numero di millisecondi di attesa prima del timeout dell'operazione. Il valore predefinito è 100.000 millisecondi (100 secondi). |
| [TokenProvider](../../aspose.email.clients.graph/igraphclient/tokenprovider) { get; set; } | Ottiene o imposta un oggetto che consente di recuperare il token di accesso OAuth. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CopyFolder](../../aspose.email.clients.graph/igraphclient/copyfolder)(string, string) | Copia una cartella di posta e il suo contenuto in un'altra cartella di posta. |
| [CopyMessage](../../aspose.email.clients.graph/igraphclient/copymessage)(string, string) | Copia un messaggio in un'altra cartella di posta. |
| [CopyNotebook](../../aspose.email.clients.graph/igraphclient/copynotebook)(string, string, string) | Copia un taccuino nella cartella Taccuini nella raccolta documenti di destinazione. La cartella viene creata se non esiste. Per le operazioni di copia, segui un modello di chiamata asincrono: chiama prima l'azione Copia, quindi esegui il polling dell'endpoint dell'operazione per il risultato. Permessi Per chiamare è necessaria una delle seguenti autorizzazioni questa API. Delegato (account aziendale o scolastico) Notes.Create, Notes.ReadWrite, Notes.ReadWrite.All Delegato (account Microsoft personale) Notes.Create, Notes.ReadWrite Application Notes.ReadWrite.All |
| [CreateAttachment](../../aspose.email.clients.graph/igraphclient/createattachment)(string, MapiAttachment) | Crea un nuovo allegato per l'elemento specificato |
| [CreateCategory](../../aspose.email.clients.graph/igraphclient/createcategory)(string, CategoryPreset) | Crea un[`OutlookCategory`](../outlookcategory) oggetto nell'elenco principale delle categorie dell'utente. |
| [CreateFolder](../../aspose.email.clients.graph/igraphclient/createfolder#createfolder)(string) | Crea nuova cartella. |
| [CreateFolder](../../aspose.email.clients.graph/igraphclient/createfolder#createfolder_1)(string, string) | Crea nuova cartella. |
| [CreateMessage](../../aspose.email.clients.graph/igraphclient/createmessage)(string, MapiMessage) | Crea il messaggio nella cartella specificata |
| [CreateNotebook](../../aspose.email.clients.graph/igraphclient/createnotebook)(Notebook) | Crea un nuovo blocco appunti di OneNote. Autorizzazioni Per chiamare questa API è necessaria una delle seguenti autorizzazioni. Delegato (account aziendale o dell'istituto di istruzione) Notes.Create, Notes.ReadWrite, Notes.ReadWrite.All Delegato (account Microsoft personale) Notes. Crea, Notes.ReadWrite Application Notes.ReadWrite.All |
| [CreateOrUpdateOverride](../../aspose.email.clients.graph/igraphclient/createorupdateoverride#createorupdateoverride)(ClassificationOverride) | Crea un override per un mittente identificato da un indirizzo SMTP. I messaggi futuri provenienti da quell'indirizzo SMTP verranno classificati in modo coerente come specificato nell'override. Nota: - Se esiste già un override con lo stesso indirizzo SMTP, i campi classifyAs e name di tale override vengono aggiornati con i valori forniti. - Il numero massimo di sostituzioni supportate per una cassetta postale è 1000, in base agli indirizzi SMTP del mittente univoci. Autorizzazioni: Delegato (account aziendale o scolastico) Mail.ReadWrite Delegato (account Microsoft personale) Mail.ReadWrite Applicazione Mail.ReadWrite |
| [CreateOrUpdateOverride](../../aspose.email.clients.graph/igraphclient/createorupdateoverride#createorupdateoverride_1)(MailAddress, ClassificationType) | Crea un override per un mittente identificato da un indirizzo SMTP. I messaggi futuri provenienti da quell'indirizzo SMTP verranno classificati in modo coerente come specificato nell'override. Nota: - Se esiste già un override con lo stesso indirizzo SMTP, i campi classifyAs e name di tale override vengono aggiornati con i valori forniti. - Il numero massimo di sostituzioni supportate per una cassetta postale è 1000, in base agli indirizzi SMTP del mittente univoci. Autorizzazioni: Delegato (account aziendale o scolastico) Mail.ReadWrite Delegato (account Microsoft personale) Mail.ReadWrite Applicazione Mail.ReadWrite |
| [CreateRule](../../aspose.email.clients.graph/igraphclient/createrule)(InboxRule) | Crea una regola per i messaggi specificando una serie di condizioni e azioni. Outlook esegue tali azioni se un messaggio in arrivo nella Posta in arrivo dell'utente soddisfa le condizioni specificate. Autorizzazioni: Per chiamare questa API è necessaria una delle seguenti autorizzazioni. per ulteriori informazioni, incluso come scegliere le autorizzazioni, vedere Autorizzazioni. Delegato (account aziendale o scolastico) MailboxSettings.ReadWrite Delegato (account Microsoft personale) MailboxSettings.ReadWrite Applicazione MailboxSettings.ReadWrite |
| [Delete](../../aspose.email.clients.graph/igraphclient/delete)(string) | Elimina oggetto. |
| [DeleteAttachment](../../aspose.email.clients.graph/igraphclient/deleteattachment)(string) | Rimuove l'allegato |
| [FetchAttachment](../../aspose.email.clients.graph/igraphclient/fetchattachment)(string) | Ottiene l'allegato per l'id specificato |
| [FetchCategory](../../aspose.email.clients.graph/igraphclient/fetchcategory)(string) | Ottieni le proprietà e le relazioni dell'oggetto outlookCategory specificato. |
| [FetchMessage](../../aspose.email.clients.graph/igraphclient/fetchmessage)(string) | Ottiene il messaggio nell'id specificato |
| [FetchNotebook](../../aspose.email.clients.graph/igraphclient/fetchnotebook)(string) | Recupera le proprietà e le relazioni di un oggetto notebook. Autorizzazioni Per chiamare questa API è necessaria una delle seguenti autorizzazioni. Delegato (account aziendale o dell'istituto di istruzione) Notes.Create, Notes.Read, Notes.ReadWrite, Notes.Read.All , Notes.ReadWrite.All Delegato (account Microsoft personale) Notes.Create, Notes.Read, Notes.ReadWrite Application Notes.Read.All, Notes.ReadWrite.All |
| [FetchRule](../../aspose.email.clients.graph/igraphclient/fetchrule)(string) | Ottieni le proprietà e le relazioni di un oggetto regola del messaggio. Autorizzazioni Una delle seguenti autorizzazioni è necessaria per chiamare questa API. Per ulteriori informazioni, incluso come scegliere le autorizzazioni, vedere Autorizzazioni. Delegato (account aziendale o dell'istituto di istruzione) MailboxSettings.Leggi Delegato (account Microsoft personale) MailboxSettings.Read Applicazione MailboxSettings.Read |
| [GetFolder](../../aspose.email.clients.graph/igraphclient/getfolder)(string) | Ottiene la cartella tramite un id. |
| [GetOneNoteOperationStatus](../../aspose.email.clients.graph/igraphclient/getonenoteoperationstatus)(string) | Ottieni lo stato di un'operazione di OneNote a esecuzione prolungata. Ciò si applica alle operazioni che restituiscono l'intestazione Operation-Location nella risposta, come CopyNotebook, CopyToNotebook, CopyToSectionGroup e CopyToSection. È possibile eseguire il polling dell'endpoint Operation-Location fino al la proprietà status restituisce completato o non riuscito. Se lo stato è completato, la proprietà ResourceLocation contiene l'URI dell'endpoint della risorsa. Se lo stato non è riuscito, le proprietà error e @api.diagnostics forniscono informazioni sull'errore. |
| [ListAttachments](../../aspose.email.clients.graph/igraphclient/listattachments)(string) | Elenca gli allegati dal messaggio principale. |
| [ListCategories](../../aspose.email.clients.graph/igraphclient/listcategories)() | Ottieni tutte le categorie che sono state definite per l'utente. |
| [ListFolders](../../aspose.email.clients.graph/igraphclient/listfolders#listfolders)() | Elenca le cartelle dalla cartella principale per le cartelle visualizzate nei normali client di posta, come la posta in arrivo. |
| [ListFolders](../../aspose.email.clients.graph/igraphclient/listfolders#listfolders_1)(string) | Elenca le cartelle dalla cartella principale per le cartelle visualizzate nei normali client di posta, come la posta in arrivo. |
| [ListMessages](../../aspose.email.clients.graph/igraphclient/listmessages#listmessages_1)(string) | Elenca MessageInfo dalla cartella principale. |
| [ListMessages](../../aspose.email.clients.graph/igraphclient/listmessages#listmessages)(string, PageInfo, MailQuery) | Elenca MessageInfo dalla cartella principale. |
| [ListNotebooks](../../aspose.email.clients.graph/igraphclient/listnotebooks)() | Recupera un elenco di oggetti notebook. Autorizzazioni Per chiamare questa API è necessaria una delle seguenti autorizzazioni. Delegato (account aziendale o dell'istituto di istruzione) Notes.Create, Notes.Read, Notes.ReadWrite, Notes.Read.All, Notes. ReadWrite.All Delegato (account Microsoft personale) Notes.Create, Notes.Read, Notes.ReadWrite Application Notes.Read.All, Notes.ReadWrite.All |
| [ListOverrides](../../aspose.email.clients.graph/igraphclient/listoverrides)() | Ottieni le sostituzioni impostate da un utente per classificare sempre i messaggi di determinati mittenti in modi specifici. Ogni sostituzione corrisponde a un indirizzo SMTP di un mittente. Inizialmente, un utente non dispone di sostituzioni. Autorizzazioni: Uno dei sono necessarie le seguenti autorizzazioni per chiamare questa API. Per ulteriori informazioni, incluso come scegliere le autorizzazioni, consulta Autorizzazioni. Delegato (account aziendale o dell'istituto di istruzione) Mail.Leggi Delegato (account Microsoft personale) Mail.Leggi Applicazione Mail.Leggi |
| [ListRules](../../aspose.email.clients.graph/igraphclient/listrules)() | Ottieni tutti gli oggetti messageRule definiti per la Posta in arrivo dell'utente. Permissions Per chiamare questa API è necessaria una delle seguenti autorizzazioni. Delegato (account Microsoft personale) MailboxSettings.Read Applicazione MailboxSettings.Read |
| [MoveFolder](../../aspose.email.clients.graph/igraphclient/movefolder)(string, string) | Sposta una cartella di posta e il suo contenuto in un'altra cartella di posta. |
| [MoveMessage](../../aspose.email.clients.graph/igraphclient/movemessage)(string, string) | Sposta un messaggio in un'altra cartella di posta. |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send)(MapiMessage) | Invia messaggio e-mail |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send_2)(string) | Invia un messaggio nella cartella delle bozze. La bozza del messaggio può essere una nuova bozza di messaggio, una bozza di risposta, una bozza di risposta a tutti o una bozza avanti. Il messaggio viene quindi salvato nella cartella Posta inviata. |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send_1)(MapiMessage, bool) | Invia messaggio e-mail |
| [SetRead](../../aspose.email.clients.graph/igraphclient/setread)(string) | Contrassegna il messaggio come letto |
| [UpdateCategory](../../aspose.email.clients.graph/igraphclient/updatecategory)(OutlookCategory) | Aggiorna la costante di colore preimpostata per la categoria specificata |
| [UpdateFolder](../../aspose.email.clients.graph/igraphclient/updatefolder)(FolderInfo) | Cartella Aggiornamenti. |
| [UpdateMessage](../../aspose.email.clients.graph/igraphclient/updatemessage#updatemessage)(MapiMessage) | Aggiorna il messaggio |
| [UpdateMessage](../../aspose.email.clients.graph/igraphclient/updatemessage#updatemessage_1)(MapiMessage, UpdateSettings) | Aggiorna il messaggio |
| [UpdateOverride](../../aspose.email.clients.graph/igraphclient/updateoverride)(ClassificationOverride) | Modifica il campo classifyAs di un override come specificato. Non è possibile utilizzare questo metodo per modificare altri campi in un'istanza ClassificationOverride. Se esiste un override per un mittente e il mittente modifica il proprio nome visualizzato, è possibile utilizzare CreateOrUpdateOverride per forzare un aggiornamento al campo del nome nell'override esistente. Se esiste un override per un mittente e il mittente modifica il proprio indirizzo SMTP, eliminare l'override esistente e crearne uno nuovo con il nuovo indirizzo SMTP è l'unico modo per "aggiorna" l'override per questo mittente. Autorizzazioni: Per chiamare questa API è richiesta una delle seguenti autorizzazioni. (account Microsoft personale) Mail.ReadWrite Applicazione Mail.ReadWrite |
| [UpdateRule](../../aspose.email.clients.graph/igraphclient/updaterule)(InboxRule) | Modifica le proprietà scrivibili su un oggetto messageRule e salva le modifiche. Autorizzazioni Per chiamare questa API è necessaria una delle seguenti autorizzazioni. ReadWrite Delegato (account Microsoft personale) MailboxSettings.ReadWrite Applicazione MailboxSettings.ReadWrite |

### Guarda anche

* spazio dei nomi [Aspose.Email.Clients.Graph](../../aspose.email.clients.graph)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
