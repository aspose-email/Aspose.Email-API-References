---
title: O365EmailMessageActivity
second_title: Aspose.Email per riferimento all'API .NET
description: Estende lo schema comune con le proprietà specifiche dei dati di Office 365 Advanced Threat Protection e Threat Intelligence. Gli eventi di Office 365 Advanced Threat Protection ATP e Threat Intelligence sono disponibili per i clienti di Office 365 che hanno un abbonamento ATP Threat Intelligence o E5 . Ogni evento nel feed ATP e Threat Intelligence corrisponde a Un messaggio di posta elettronica inviato o ricevuto da un utente nellorganizzazione con rilevamenti viene eseguito sui messaggi al momento della consegna e dalleliminazione automatica dellora zero.
type: docs
weight: 2660
url: /it/net/aspose.email.clients.activity/o365emailmessageactivity/
---
## O365EmailMessageActivity class

Estende lo schema comune con le proprietà specifiche dei dati di Office 365 Advanced Threat Protection e Threat Intelligence. Gli eventi di Office 365 Advanced Threat Protection (ATP) e Threat Intelligence sono disponibili per i clienti di Office 365 che hanno un abbonamento ATP, Threat Intelligence o E5 . Ogni evento nel feed ATP e Threat Intelligence corrisponde a Un messaggio di posta elettronica inviato o ricevuto da un utente nell'organizzazione con rilevamenti viene eseguito sui messaggi al momento della consegna e dall'eliminazione automatica dell'ora zero.

```csharp
public class O365EmailMessageActivity : Content
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [O365EmailMessageActivity](o365emailmessageactivity)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AttachmentData](../../aspose.email.clients.activity/o365emailmessageactivity/attachmentdata) { get; set; } | Dati sugli allegati nel messaggio e-mail che ha attivato l'evento. Obbligatorio: No |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | L'indirizzo IP del dispositivo utilizzato quando l'attività è stata registrata. L'indirizzo IP viene visualizzato in un formato di indirizzo IPv4 o IPv6. Obbligatorio: Sì |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | La data e l'ora in UTC (Coordinated Universal Time) in cui l'utente ha eseguito l'attività. Obbligatorio: Sì |
| [DetectionMethod](../../aspose.email.clients.activity/o365emailmessageactivity/detectionmethod) { get; set; } | Il metodo o la tecnologia utilizzata da Office 365 ATP per il rilevamento. Obbligatorio: Sì |
| [DetectionType](../../aspose.email.clients.activity/o365emailmessageactivity/detectiontype) { get; set; } | Il tipo di rilevamento. Obbligatorio: Sì |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | Identificatore univoco di un record di audit. Obbligatorio: Sì |
| [InternetMessageId](../../aspose.email.clients.activity/o365emailmessageactivity/internetmessageid) { get; set; } | L'ID messaggio Internet Obbligatorio: Sì |
| [NetworkMessageId](../../aspose.email.clients.activity/o365emailmessageactivity/networkmessageid) { get; set; } | ID messaggio di rete di Exchange Online Obbligatorio: Sì |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | Per le attività di SharePoint e OneDrive for Business, il percorso completo del file o della cartella a cui l'utente ha eseguito l'accesso. Per la registrazione di controllo dell'amministratore di Exchange, il nome dell'oggetto che è stato modificato dal cmdlet. Obbligatorio: No |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | Il nome dell'utente o dell'attività dell'amministratore. Per una descrizione delle operazioni/attività più comuni, vedere Cerca nel registro di controllo in Office 365 Protection Center. Per l'attività di amministrazione di Exchange, questa proprietà identifica il nome del cmdlet eseguito. Per gli eventi Dlp, può essere "DlpRuleMatch", "DlpRuleUndo" o "DlpInfo", descritti in "Schema DLP" di seguito. Obbligatorio: Sì |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | Il GUID per il tenant di Office 365 dell'organizzazione. Questo valore sarà sempre lo stesso per l'organizzazione, indipendentemente dal servizio di Office 365 in cui si trova. Obbligatorio: Sì |
| [P1Sender](../../aspose.email.clients.activity/o365emailmessageactivity/p1sender) { get; set; } | Il percorso di ritorno del mittente del messaggio e-mail. Obbligatorio: Sì |
| [P2Sender](../../aspose.email.clients.activity/o365emailmessageactivity/p2sender) { get; set; } | Il mittente del messaggio e-mail. Obbligatorio: Sì |
| [Recipients](../../aspose.email.clients.activity/o365emailmessageactivity/recipients) { get; set; } | Un array di destinatari del messaggio e-mail. Obbligatorio: Sì |
| [RecordType](../../aspose.email.clients.activity/content/recordtype) { get; set; } | Il tipo di operazione indicato dal record. Obbligatorio: Sì |
| [ResultStatus](../../aspose.email.clients.activity/content/resultstatus) { get; set; } | Indica se l'azione (specificata nella proprietà Operazione) è riuscita o meno. I valori possibili sono Succeeded, PartiallySucceded o Failed. Per l'attività di amministrazione di Exchange, il valore è True o False. Obbligatorio: No |
| [Scope](../../aspose.email.clients.activity/content/scope) { get; set; } | Questo evento è stato creato da un servizio O365 ospitato o da un server locale? I valori possibili sono online e onprem. Tieni presente che SharePoint è l'unico carico di lavoro che attualmente invia eventi da locale a O365. Obbligatorio: No |
| [SenderIp](../../aspose.email.clients.activity/o365emailmessageactivity/senderip) { get; set; } | L'indirizzo IP che ha inviato l'e-mail di Office 365. L'indirizzo IP viene visualizzato in un formato di indirizzo IPv4 o IPv6. Obbligatorio: Sì |
| [Subject](../../aspose.email.clients.activity/o365emailmessageactivity/subject) { get; set; } | La riga dell'oggetto del messaggio. Obbligatorio: Sì |
| [UserId](../../aspose.email.clients.activity/content/userid) { get; set; } | L'UPN (User Principal Name) dell'utente che ha eseguito l'azione (specificata nella proprietà Operation) che ha portato alla registrazione del record; ad esempio, mio_nome@mio_nome_dominio. Si noti che sono inclusi anche i record per le attività eseguite dagli account di sistema (come SHAREPOINT\system o NT AUTHORITY\SYSTEM). Obbligatorio: Sì |
| [UserKey](../../aspose.email.clients.activity/content/userkey) { get; set; } | Un ID alternativo per l'utente identificato nella proprietà UserId. Ad esempio, questa proprietà viene popolata con l'ID univoco (PUID) del passaporto per gli eventi eseguiti dagli utenti in SharePoint, OneDrive for Business ed Exchange. Questa proprietà può anche specificare lo stesso valore della proprietà UserID per eventi che si verificano in altri servizi ed eventi eseguiti da account di sistema. Obbligatorio: Sì |
| [UserType](../../aspose.email.clients.activity/content/usertype) { get; set; } | Il tipo di utente che ha eseguito l'operazione. Obbligatorio: Sì |
| [Verdict](../../aspose.email.clients.activity/o365emailmessageactivity/verdict) { get; set; } | Il verdetto del messaggio. Obbligatorio: Sì |
| [Workload](../../aspose.email.clients.activity/content/workload) { get; set; } | Il servizio di Office 365 in cui si è verificata l'attività nella stringa del carico di lavoro. I valori possibili per questa proprietà sono: Exchange SharePoint OneDrive AzureActiveDirectory SecurityComplianceCenter Sway ThreatIntelligence Obbligatorio: No |

### Guarda anche

* class [Content](../content)
* spazio dei nomi [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
