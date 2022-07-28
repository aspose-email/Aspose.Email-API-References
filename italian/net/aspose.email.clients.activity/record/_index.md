---
title: Record
second_title: Aspose.Email per riferimento all'API .NET
description: Record registro di controllo
type: docs
weight: 2720
url: /it/net/aspose.email.clients.activity/record/
---
## Record class

Record registro di controllo

```csharp
public class Record
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Record](record)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AzureActiveDirectoryEventType](../../aspose.email.clients.activity/record/azureactivedirectoryeventtype) { get; set; } | Ottiene o imposta il tipo di evento di Azure AD. Obbligatorio: Sì |
| [Client](../../aspose.email.clients.activity/record/client) { get; set; } | Ottiene o imposta i dettagli sul dispositivo client, sul sistema operativo del dispositivo e sul browser del dispositivo utilizzati per l'evento di accesso dell'account. Obbligatorio: No |
| [ClientIP](../../aspose.email.clients.activity/record/clientip) { get; set; } | Ottiene o imposta l'indirizzo IP del dispositivo utilizzato quando l'attività è stata registrata. L'indirizzo IP viene visualizzato in un formato di indirizzo IPv4 o IPv6. Obbligatorio: Sì |
| [CreationTime](../../aspose.email.clients.activity/record/creationtime) { get; set; } | Ottiene o imposta la data e l'ora in Coordinated Universal Time (UTC) quando l'utente ha eseguito l'attività. Obbligatorio: Sì |
| [ExtendedProperties](../../aspose.email.clients.activity/record/extendedproperties) { get; set; } | Ottiene o imposta l'elenco delle proprietà estese per l'impostazione modificata. Ogni proprietà avrà un Nome e un Valore. Obbligatorio: No |
| [Id](../../aspose.email.clients.activity/record/id) { get; set; } | Ottiene o imposta l'identificatore univoco di un record di controllo. Obbligatorio: Sì |
| [LoginStatus](../../aspose.email.clients.activity/record/loginstatus) { get; set; } | Ottiene o imposta lo stato di accesso Obbligatorio: Sì |
| [ObjectId](../../aspose.email.clients.activity/record/objectid) { get; set; } | Ottiene o imposta l'identificatore oggetto. Per le attività di SharePoint e OneDrive for Business, il percorso completo del file o della cartella a cui accede l'utente. Per la registrazione di controllo dell'amministratore di Exchange, il nome dell'oggetto che è stato modificato dal cmdlet. Obbligatorio: No |
| [Operation](../../aspose.email.clients.activity/record/operation) { get; set; } | Ottiene o imposta il nome dell'utente o dell'attività dell'amministratore. Per una descrizione delle operazioni/attività più comuni, vedere Cerca nel registro di controllo in Office 365 Protection Center. Per l'attività di amministrazione di Exchange, questa proprietà identifica il nome del cmdlet eseguito. Per gli eventi Dlp, può essere "DlpRuleMatch", "DlpRuleUndo" o "DlpInfo", descritti in "Schema DLP" di seguito. Obbligatorio: Sì |
| [OrganizationId](../../aspose.email.clients.activity/record/organizationid) { get; set; } | Ottiene o imposta il GUID per il tenant di Office 365 dell'organizzazione. Questo valore sarà sempre lo stesso per l'organizzazione, indipendentemente dal servizio di Office 365 in cui si trova. Obbligatorio: Sì |
| [RecordType](../../aspose.email.clients.activity/record/recordtype) { get; set; } | Ottiene o imposta il tipo di operazione indicata dal record. Obbligatorio: Sì |
| [ResultStatus](../../aspose.email.clients.activity/record/resultstatus) { get; set; } | Ottiene o imposta un valore che indica se l'azione (specificata nella proprietà Operation) è riuscita o meno. Obbligatorio: No |
| [UserDomain](../../aspose.email.clients.activity/record/userdomain) { get; set; } | Ottiene o imposta le informazioni sull'identità del tenant (TII). Obbligatorio: Sì |
| [UserId](../../aspose.email.clients.activity/record/userid) { get; set; } | Ottiene o imposta l'UPN (User Principal Name) dell'utente che ha eseguito l'azione (specificata nella proprietà Operation) che ha determinato la registrazione del record; ad esempio, mio_nome@mio_nome_dominio. Si noti che sono inclusi anche i record per le attività eseguite dagli account di sistema (come SHAREPOINT\system o NT AUTHORITY\SYSTEM). Obbligatorio: Sì |
| [UserKey](../../aspose.email.clients.activity/record/userkey) { get; set; } | Ottiene o imposta un ID alternativo per l'utente identificato nella proprietà UserId. Ad esempio, questa proprietà viene popolata con l'ID univoco (PUID) del passaporto per gli eventi eseguiti dagli utenti in SharePoint, OneDrive for Business ed Exchange. Questa proprietà può anche specificare lo stesso valore della proprietà UserID per eventi che si verificano in altri servizi ed eventi eseguiti da account di sistema. Obbligatorio: Sì |
| [UserType](../../aspose.email.clients.activity/record/usertype) { get; set; } | Ottiene o imposta il tipo di utente che ha eseguito l'operazione. Obbligatorio: Sì |
| [Workload](../../aspose.email.clients.activity/record/workload) { get; set; } | Ottiene o imposta il servizio Office 365 in cui si è verificata l'attività. Obbligatorio: No |

### Guarda anche

* spazio dei nomi [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
