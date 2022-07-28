---
title: ExchangeAdminActivity
second_title: Aspose.Email per riferimento all'API .NET
description: Estende lo schema comune con le proprietà specifiche di tutti i dati di controllo dellamministratore di Exchange.
type: docs
weight: 2480
url: /it/net/aspose.email.clients.activity/exchangeadminactivity/
---
## ExchangeAdminActivity class

Estende lo schema comune con le proprietà specifiche di tutti i dati di controllo dell'amministratore di Exchange.

```csharp
public class ExchangeAdminActivity : Content
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ExchangeAdminActivity](exchangeadminactivity)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | L'indirizzo IP del dispositivo utilizzato quando l'attività è stata registrata. L'indirizzo IP viene visualizzato in un formato di indirizzo IPv4 o IPv6. Obbligatorio: Sì |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | La data e l'ora in UTC (Coordinated Universal Time) in cui l'utente ha eseguito l'attività. Obbligatorio: Sì |
| [ExternalAccess](../../aspose.email.clients.activity/exchangeadminactivity/externalaccess) { get; set; } | Specifica se il cmdlet è stato eseguito da un utente dell'organizzazione, dal personale del centro dati Microsoft o da un account del servizio del centro dati oppure da un amministratore delegato. Il valore False indica che il cmdlet è stato eseguito da un utente dell'organizzazione. Il valore True indica che il cmdlet è stato eseguito dal personale del centro dati, da un account del servizio del centro dati o da un amministratore delegato. |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | Identificatore univoco di un record di audit. Obbligatorio: Sì |
| [ModifiedObjectResolvedName](../../aspose.email.clients.activity/exchangeadminactivity/modifiedobjectresolvedname) { get; set; } | Questo è il nome descrittivo dell'oggetto che è stato modificato dal cmdlet. Viene registrato solo se il cmdlet modifica l'oggetto. |
| [ModifiedProperties](../../aspose.email.clients.activity/exchangeadminactivity/modifiedproperties) { get; set; } | La proprietà è inclusa per gli eventi di amministrazione. La proprietà include il nome della proprietà che è stata modificata, il nuovo valore della proprietà modificata e il valore precedente dell'oggetto modificato. |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | Per le attività di SharePoint e OneDrive for Business, il percorso completo del file o della cartella a cui l'utente ha eseguito l'accesso. Per la registrazione di controllo dell'amministratore di Exchange, il nome dell'oggetto che è stato modificato dal cmdlet. Obbligatorio: No |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | Il nome dell'utente o dell'attività dell'amministratore. Per una descrizione delle operazioni/attività più comuni, vedere Cerca nel registro di controllo in Office 365 Protection Center. Per l'attività di amministrazione di Exchange, questa proprietà identifica il nome del cmdlet eseguito. Per gli eventi Dlp, può essere "DlpRuleMatch", "DlpRuleUndo" o "DlpInfo", descritti in "Schema DLP" di seguito. Obbligatorio: Sì |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | Il GUID per il tenant di Office 365 dell'organizzazione. Questo valore sarà sempre lo stesso per l'organizzazione, indipendentemente dal servizio di Office 365 in cui si trova. Obbligatorio: Sì |
| [OrganizationName](../../aspose.email.clients.activity/exchangeadminactivity/organizationname) { get; set; } | Il nome del tenant. |
| [OriginatingServer](../../aspose.email.clients.activity/exchangeadminactivity/originatingserver) { get; set; } | Il nome del server da cui è stato eseguito il cmdlet. |
| [Parameters](../../aspose.email.clients.activity/exchangeadminactivity/parameters) { get; set; } | Il nome e il valore di tutti i parametri utilizzati con il cmdlet identificato nella proprietà Operations. |
| [RecordType](../../aspose.email.clients.activity/content/recordtype) { get; set; } | Il tipo di operazione indicato dal record. Obbligatorio: Sì |
| [ResultStatus](../../aspose.email.clients.activity/content/resultstatus) { get; set; } | Indica se l'azione (specificata nella proprietà Operazione) è riuscita o meno. I valori possibili sono Succeeded, PartiallySucceded o Failed. Per l'attività di amministrazione di Exchange, il valore è True o False. Obbligatorio: No |
| [Scope](../../aspose.email.clients.activity/content/scope) { get; set; } | Questo evento è stato creato da un servizio O365 ospitato o da un server locale? I valori possibili sono online e onprem. Tieni presente che SharePoint è l'unico carico di lavoro che attualmente invia eventi da locale a O365. Obbligatorio: No |
| [UserId](../../aspose.email.clients.activity/content/userid) { get; set; } | L'UPN (User Principal Name) dell'utente che ha eseguito l'azione (specificata nella proprietà Operation) che ha portato alla registrazione del record; ad esempio, mio_nome@mio_nome_dominio. Si noti che sono inclusi anche i record per le attività eseguite dagli account di sistema (come SHAREPOINT\system o NT AUTHORITY\SYSTEM). Obbligatorio: Sì |
| [UserKey](../../aspose.email.clients.activity/content/userkey) { get; set; } | Un ID alternativo per l'utente identificato nella proprietà UserId. Ad esempio, questa proprietà viene popolata con l'ID univoco (PUID) del passaporto per gli eventi eseguiti dagli utenti in SharePoint, OneDrive for Business ed Exchange. Questa proprietà può anche specificare lo stesso valore della proprietà UserID per eventi che si verificano in altri servizi ed eventi eseguiti da account di sistema. Obbligatorio: Sì |
| [UserType](../../aspose.email.clients.activity/content/usertype) { get; set; } | Il tipo di utente che ha eseguito l'operazione. Obbligatorio: Sì |
| [Workload](../../aspose.email.clients.activity/content/workload) { get; set; } | Il servizio di Office 365 in cui si è verificata l'attività nella stringa del carico di lavoro. I valori possibili per questa proprietà sono: Exchange SharePoint OneDrive AzureActiveDirectory SecurityComplianceCenter Sway ThreatIntelligence Obbligatorio: No |

### Guarda anche

* class [Content](../content)
* spazio dei nomi [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
