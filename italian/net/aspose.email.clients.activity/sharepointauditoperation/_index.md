---
title: SharePointAuditOperation
second_title: Aspose.Email per riferimento all'API .NET
description: Operazioni di controllo di SharePoint
type: docs
weight: 2760
url: /it/net/aspose.email.clients.activity/sharepointauditoperation/
---
## SharePointAuditOperation enumeration

Operazioni di controllo di SharePoint

```csharp
public enum SharePointAuditOperation
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| AccessInvitationAccepted | `0` | Questa operazione è in Anteprima. Il destinatario di un invito a visualizzare o modificare un file (o una cartella) condiviso ha effettuato l'accesso al file condiviso facendo clic sul collegamento nell'invito. |
| AccessInvitationCreated | `1` | Questa operazione è in Anteprima. L'utente invia un invito a un'altra persona (all'interno o all'esterno dell'organizzazione) per visualizzare o modificare un file o una cartella condivisa in un sito di SharePoint o OneDrive for Business. I dettagli della voce dell'evento identificano il nome del file che è stato condiviso, l'utente a cui è stato inviato l'invito, e il tipo di autorizzazione di condivisione selezionato dalla persona che ha inviato l'invito. |
| AccessInvitationExpired | `2` | Questa operazione è in Anteprima. Un invito inviato a un utente esterno scade. Per impostazione predefinita, un invito inviato a un utente esterno alla tua organizzazione scade dopo 7 giorni se l'invito non viene accettato. |
| AccessInvitationRevoked | `3` | Questa operazione è in Anteprima. L'amministratore del sito o il proprietario di un sito o di un documento in SharePoint o OneDrive for Business ritira un invito inviato a un utente esterno all'organizzazione. Un invito può essere ritirato solo prima di essere accettato. |
| AccessInvitationUpdated | `4` | Questa operazione è in Anteprima. L'utente che ha creato e inviato un invito a un'altra persona per visualizzare o modificare un file (o una cartella) condiviso su un sito di SharePoint o OneDrive for Business invia nuovamente l'invito. |
| AccessRequestApproved | `5` | L'amministratore del sito o il proprietario di un sito o di un documento in SharePoint o OneDrive for Business approva una richiesta dell'utente di accedere al sito o al documento. |
| AccessRequestCreated | `6` | L'utente richiede l'accesso a un sito o un documento in SharePoint o OneDrive for Business a cui non dispone dell'autorizzazione per accedere. |
| AccessRequestRejected | `7` | Questa operazione è in Anteprima. L'amministratore del sito o il proprietario di un sito o di un documento in SharePoint rifiuta una richiesta dell'utente di accedere al sito o al documento. |
| ActivationEnabled | `8` | Questa operazione è in Anteprima. Gli utenti possono abilitare al browser modelli di modulo che non contengono codice modulo, richiedono l'attendibilità totale, abilitare il rendering su un dispositivo mobile o utilizzare una connessione dati gestita da un amministratore del server. |
| AdministratorAddedToTermStore | `9` | Questa operazione è in Anteprima. Aggiunto amministratore archivio termini. |
| AdministratorDeletedFromTermStore | `10` | Questa operazione è in Anteprima. Amministratore archivio termini eliminato. |
| AllowGroupCreationSet | `11` | Questa operazione è in Anteprima. L'amministratore o il proprietario del sito aggiunge un livello di autorizzazione a un sito di SharePoint o OneDrive for Business che consente a un utente a cui è stata assegnata tale autorizzazione di creare un gruppo per quel sito. |
| AppCatalogCreated | `12` | Questa operazione è in Anteprima. Catalogo app creato per rendere disponibili app aziendali personalizzate per il tuo ambiente SharePoint. |
| AuditPolicyRemoved | `13` | Questa operazione è in Anteprima. Il criterio del ciclo di vita del documento è stato rimosso per una raccolta siti. |
| AuditPolicyUpdate | `14` | Questa operazione è in Anteprima. La policy del ciclo di vita del documento è stata aggiornata per una raccolta siti. |
| AzureStreamingEnabledSet | `15` | Questa operazione è in Anteprima. Il proprietario di un portale video ha consentito lo streaming video da Azure. |
| CollaborationTypeModified | `16` | Questa operazione è in Anteprima. Il tipo di collaborazione consentito sui siti (ad esempio, intranet, extranet o pubblico) è stato modificato. |
| ConnectedSiteSettingModified | `17` | L'utente ha creato, modificato o eliminato il collegamento tra un progetto e un sito del progetto oppure l'utente modifica l'impostazione di sincronizzazione sul collegamento in Project Web App. |
| CreateSSOApplication | `18` | Questa operazione è in Anteprima. Applicazione di destinazione creata nel servizio di archiviazione sicura. |
| CustomFieldOrLookupTableCreated | `19` | L'utente ha creato un frield personalizzato o una tabella/elemento di ricerca in Project Web App. |
| CustomFieldOrLookupTableDeleted | `20` | L'utente ha eliminato un campo personalizzato o una tabella/elemento di ricerca in Project Web App. |
| CustomFieldOrLookupTableModified | `21` | L'utente ha modificato un campo personalizzato o una tabella/elemento di ricerca in Project Web App. |
| CustomizeExemptUsers | `22` | Questa operazione è in Anteprima. L'amministratore globale ha personalizzato l'elenco degli agenti utente esenti nell'interfaccia di amministrazione di SharePoint. È possibile specificare quali programmi utente esentare dalla ricezione di un'intera pagina Web da indicizzare. Ciò significa che quando un programma utente che hai specificato come esente incontra un modulo InfoPath, il modulo verrà restituito come file XML anziché come un'intera pagina Web. Ciò rende più veloce l'indicizzazione dei moduli di InfoPath. |
| DefaultLanguageChangedInTermStore | `23` | Questa operazione è in Anteprima. Impostazione della lingua modificata nell'archivio terminologico. |
| DelegateModified | `24` | L'utente ha creato o modificato un delegato di sicurezza in Project Web App. |
| DelegateRemoved | `25` | L'utente ha eliminato un delegato di sicurezza in Project Web App. |
| DeleteSSOApplication | `26` | Questa operazione è in Anteprima. Un'applicazione SSO è stata eliminata. |
| eDiscoveryHoldApplied | `27` | Questa operazione è in Anteprima. È stata applicata una sospensione sul posto su un'origine di contenuto. I blocchi sul posto vengono gestiti tramite una raccolta siti eDiscovery (ad esempio eDiscovery Center) in SharePoint. |
| eDiscoveryHoldRemoved | `28` | Questa operazione è in Anteprima. Un blocco sul posto è stato rimosso da un'origine contenuto. I blocchi sul posto vengono gestiti tramite una raccolta siti eDiscovery (ad esempio eDiscovery Center) in SharePoint. |
| eDiscoverySearchPerformed | `29` | Questa operazione è in Anteprima. È stata eseguita una ricerca eDiscovery utilizzando una raccolta siti eDiscovery in SharePoint. |
| EngagementAccepted | `30` | L'utente accetta un impegno di risorse in Project Web App. |
| EngagementModified | `31` | L'utente modifica un impegno di risorse in Project Web App. |
| EngagementRejected | `32` | L'utente rifiuta un impegno di risorse in Project Web App. |
| EnterpriseCalendarModified | `33` | L'utente copia, modifica o elimina un calendario aziendale in Project Web App. |
| EntityDeleted | `34` | L'utente elimina una scheda attività in Project Web App. |
| EntityForceCheckedIn | `35` | L'utente forza un check-in su un calendario, un campo personalizzato o una tabella di ricerca in Project Web App. |
| ExemptUserAgentSet | `36` | Questa operazione è in Anteprima. L'amministratore globale aggiunge un agente utente all'elenco degli agenti utente esenti nell'interfaccia di amministrazione di SharePoint. |
| FileAccessed | `37` | L'account utente o di sistema accede a un file in un sito di SharePoint o OneDrive for Business. Gli account di sistema possono anche generare eventi FileAccessed. |
| FileCheckOutDiscarded | `38` | Questa operazione è in Anteprima. L'utente elimina (o annulla) un file estratto. Ciò significa che tutte le modifiche apportate al file al momento dell'estrazione vengono eliminate e non salvate nella versione del documento nella raccolta documenti. |
| FileCheckedIn | `39` | Questa operazione è in Anteprima. L'utente archivia un documento che ha estratto da una raccolta documenti di SharePoint o OneDrive for Business. |
| FileCheckedOut | `40` | Questa operazione è in Anteprima. L'utente estrae un documento che si trova in una raccolta documenti di SharePoint o OneDrive for Business. Gli utenti possono controllare e apportare modifiche ai documenti che sono stati condivisi con loro. |
| FileCopied | `41` | L'utente copia un documento da un sito di SharePoint o OneDrive for Business. Il file copiato può essere salvato in un'altra cartella del sito. |
| FileDeleted | `42` | L'utente elimina un documento da un sito di SharePoint o OneDrive for Business. |
| FileDeletedFirstStageRecycleBin | `43` | L'utente elimina un file dal cestino in un sito di SharePoint o OneDrive for Business. |
| FileDeletedSecondStageRecycleBin | `44` | L'utente elimina un file dal cestino della seconda fase in un sito di SharePoint o OneDrive for Business. |
| FileDownloaded | `45` | L'utente scarica un documento da un sito di SharePoint o OneDrive for Business. |
| FileFetched | `46` | Questo evento è stato sostituito dall'evento FileAccessed ed è stato deprecato. |
| FileModified | `47` | L'account utente o di sistema modifica il contenuto o le proprietà di un documento che si trova in un sito di SharePoint o OneDrive for Business. |
| FileMoved | `48` | L'utente sposta un documento dalla posizione corrente su un sito di SharePoint o OneDrive for Business a una nuova posizione. |
| FilePreviewed | `49` | L'utente visualizza in anteprima un documento su un sito di SharePoint o OneDrive for Business. |
| FileRenamed | `50` | L'utente rinomina un documento su un sito di SharePoint o OneDrive for Business. |
| FileRestored | `51` | L'utente ripristina un documento dal cestino di un sito di SharePoint o OneDrive for Business. |
| FileSyncDownloadedFull | `52` | L'utente stabilisce una relazione di sincronizzazione e scarica correttamente i file per la prima volta sul proprio computer da una raccolta documenti di SharePoint o OneDrive for Business. |
| FileSyncDownloadedPartial | `53` | L'utente scarica correttamente le modifiche ai file dalla raccolta documenti di SharePoint o OneDrive for Business. Questo evento indica che tutte le modifiche apportate ai file nella raccolta documenti sono state scaricate nel computer dell'utente. Sono state scaricate solo le modifiche perché la raccolta documenti è stata precedentemente scaricata dall'utente (come indicato dall'evento FileSyncDownloadedFull). |
| FileSyncUploadedFull | `54` | Questa operazione è in Anteprima. L'utente stabilisce una relazione di sincronizzazione e carica correttamente i file per la prima volta dal proprio computer a una raccolta documenti di SharePoint o OneDrive for Business. |
| FileSyncUploadedPartial | `55` | Questa operazione è in Anteprima. L'utente carica correttamente le modifiche ai file in una raccolta documenti di SharePoint o OneDrive for Business. Questo evento indica che tutte le modifiche apportate alla versione locale di un file da una raccolta documenti sono state caricate correttamente nella raccolta documenti. Vengono scaricate solo le modifiche perché quei file sono stati caricati in precedenza dall'utente (come indicato dall'evento FileSyncUploadedFull). |
| FileUploaded | `56` | L'utente carica un documento in una cartella in un sito di SharePoint o OneDrive for Business. |
| FileViewed | `57` | Questo evento è stato sostituito dall'evento FileAccessed ed è stato deprecato. |
| FolderCopied | `58` | L'utente copia una cartella da un sito di SharePoint o OneDrive for Business in un'altra posizione in SharePoint o OneDrive for Business. |
| FolderCreated | `59` | L'utente crea una cartella in un sito di SharePoint o OneDrive for Business. |
| FolderDeleted | `60` | L'utente elimina una cartella da un sito di SharePoint o OneDrive for Business. |
| FolderDeletedFirstStageRecycleBin | `61` | L'utente elimina una cartella dal cestino in un sito di SharePoint o OneDrive for Business . |
| FolderDeletedSecondStageRecycleBin | `62` | L'utente elimina una cartella dal cestino della seconda fase in un sito di SharePoint o OneDrive for Business. |
| FolderModified | `63` | L'utente modifica una cartella in un sito di SharePoint o OneDrive for Business. Questo evento include modifiche ai metadati delle cartelle, come tag e proprietà. |
| FolderMoved | `64` | L'utente sposta una cartella da un sito di SharePoint o OneDrive for Business. |
| FolderRenamed | `65` | L'utente rinomina una cartella in un sito di SharePoint o OneDrive for Business. |
| FolderRestored | `66` | L'utente ripristina una cartella dal Cestino in un sito di SharePoint o OneDrive for Business. |
| GroupAdded | `67` | Questa operazione è in Anteprima. L'amministratore o il proprietario del sito crea un gruppo per un sito di SharePoint o OneDrive for Business oppure esegue un'attività che comporta la creazione di un gruppo. Ad esempio, la prima volta che un utente crea un collegamento per condividere un file, un gruppo di sistema viene aggiunto al sito OneDrive for Business dell'utente. Questo evento può anche essere il risultato di un utente che crea un collegamento con autorizzazioni di modifica a un file condiviso. |
| GroupRemoved | `68` | Questa operazione è in Anteprima. L'utente elimina un gruppo da un sito di SharePoint o OneDrive for Business. |
| GroupUpdated | `69` | Questa operazione è in Anteprima. L'amministratore o il proprietario del sito modifica le impostazioni di un gruppo per un sito di SharePoint o OneDrive for Business. Ciò può includere la modifica del nome del gruppo, chi può visualizzare o modificare l'appartenenza al gruppo e come vengono gestite le richieste di appartenenza. |
| LanguageAddedToTermStore | `70` | Questa operazione è in Anteprima. Lingua aggiunta all'archivio terminologico. |
| LanguageRemovedFromTermStore | `71` | Questa operazione è in Anteprima. Lingua rimossa dall'archivio terminologico. |
| LegacyWorkflowEnabledSet | `72` | Questa operazione è in Anteprima. L'amministratore o il proprietario del sito aggiunge il tipo di contenuto Attività flusso di lavoro SharePoint al sito. Gli amministratori globali possono anche abilitare i flussi di lavoro per l'intera organizzazione nell'interfaccia di amministrazione di SharePoint. |
| LookAndFeelModified | `73` | L'utente modifica un avvio rapido, formati di diagramma di Gantt o formati di gruppo. Oppure l'utente crea, modifica o elimina una vista in Project Web App. |
| ManagedSyncClientAllowed | `74` | L'utente stabilisce correttamente una relazione di sincronizzazione con un sito di SharePoint o OneDrive for Business. La relazione di sincronizzazione è riuscita perché il computer dell'utente è un membro di un dominio che è stato aggiunto all'elenco di domini (denominato elenco di destinatari sicuri) che possono accedere alle raccolte documenti nell'organizzazione. Per ulteriori informazioni su questa funzionalità, vedere Usare i cmdlet di Windows PowerShell per abilitare la sincronizzazione di OneDrive per i domini che si trovano nell'elenco dei destinatari sicuri. |
| MaxQuotaModified | `75` | Questa operazione è in Anteprima. La quota massima per un sito è stata modificata. |
| MaxResourceUsageModified | `76` | Questa operazione è in Anteprima. L'utilizzo massimo consentito delle risorse per un sito è stato modificato. |
| MySitePublicEnabledSet | `77` | Questa operazione è in Anteprima. Il flag che consente agli utenti di avere siti personali pubblici è stato impostato dall'amministratore di SharePoint. |
| NewsFeedEnabledSet | `78` | Questa operazione è in Anteprima. L'amministratore o il proprietario del sito abilita i feed RSS per un sito di SharePoint o OneDrive for Business. Gli amministratori globali possono abilitare i feed RSS per l'intera organizzazione nell'interfaccia di amministrazione di SharePoint. |
| ODBNextUXSettings | `79` | Questa operazione è in Anteprima. È stata abilitata la nuova interfaccia utente per OneDrive for Business. |
| OfficeOnDemandSet | `80` | Questa operazione è in Anteprima. L'amministratore del sito abilita Office on Demand, che consente agli utenti di accedere alla versione più recente delle applicazioni desktop di Office. Office on Demand è abilitato nell'interfaccia di amministrazione di SharePoint e richiede un abbonamento a Office 365 che includa applicazioni di Office complete e installate. |
| PageViewed | `81` | L'utente visualizza una pagina in un sito di SharePoint o in un sito di OneDrive for Business. Ciò non include la visualizzazione dei file della raccolta documenti da un sito di SharePoint o da un sito di One Drive for Business su un browser. |
| PeopleResultsScopeSet | `82` | Questa operazione è in Anteprima. L'amministratore del sito crea o modifica l'origine dei risultati per le ricerche di utenti per un sito di SharePoint. |
| PermissionSyncSettingModified | `83` | L'utente modifica le impostazioni di sincronizzazione delle autorizzazioni del progetto in Project Web App. |
| PermissionTemplateModified | `84` | L'utente crea, modifica o elimina un modello di autorizzazioni in Project Web App. |
| PortfolioDataAccessed | `85` | L'utente accede al contenuto del portfolio (libreria dei driver, prioritizzazione dei driver, analisi del portfolio) in Project Web App. |
| PortfolioDataModified | `86` | L'utente crea, modifica o elimina i dati del portfolio (libreria del driver, prioritizzazione del driver, analisi del portfolio) in Project Web App. |
| PreviewModeEnabledSet | `87` | Questa operazione è in Anteprima. L'amministratore del sito abilita l'anteprima del documento per un sito di SharePoint. |
| ProjectAccessed | `88` | L'utente accede al contenuto del progetto in Project Web App. |
| ProjectCheckedIn | `89` | L'utente effettua il check-in di un progetto che ha estratto da un'app Project Web. |
| ProjectCheckedOut | `90` | L'utente estrae un progetto che si trova in un'app Project Web. Gli utenti possono controllare e apportare modifiche ai progetti per i quali hanno il permesso di aprire. |
| ProjectCreated | `91` | L'utente crea un progetto in Project Web App. |
| ProjectDeleted | `92` | L'utente elimina un progetto in Project Web App. |
| ProjectForceCheckedIn | `93` | L'utente forza un check-in su un progetto in Project Web App. |
| ProjectModified | `94` | L'utente modifica un progetto in Project Web App. |
| ProjectPublished | `95` | L'utente pubblica un progetto in Project Web App. |
| ProjectWorkflowRestarted | `96` | L'utente riavvia un flusso di lavoro in Project Web App. |
| PWASettingsAccessed | `97` | L'utente accede alle impostazioni di Project Web App tramite CSOM. |
| PWASettingsModified | `98` | L'utente modifica la configurazione di Project Web App. |
| QueueJobStateModified | `99` | L'utente annulla o riavvia un processo in coda in Project Web App. |
| QuotaWarningEnabledModified | `100` | Questa operazione è in Anteprima. Avviso quota di archiviazione modificato. |
| RenderingEnabled | `101` | Questa operazione è in Anteprima. I modelli di modulo abilitati per il browser verranno visualizzati dai servizi di moduli di InfoPath. |
| ReportingAccessed | `102` | L'utente ha eseguito l'accesso all'endpoint di reporting in Project Web App. |
| ReportingSettingModified | `103` | L'utente modifica la configurazione dei rapporti in Project Web App. |
| ResourceAccessed | `104` | L'utente accede al contenuto di una risorsa aziendale in Project Web App. |
| ResourceCheckedIn | `105` | L'utente esegue il check-in di una risorsa aziendale che ha estratto da Project Web App. |
| ResourceCheckedOut | `106` | L'utente estrae una risorsa aziendale situata in Project Web App. |
| ResourceCreated | `107` | L'utente crea una risorsa aziendale in Project Web App. |
| ResourceDeleted | `108` | L'utente elimina una risorsa aziendale in Project Web App. |
| ResourceForceCheckedIn | `109` | L'utente forza il check-in di una risorsa aziendale in Project Web App. |
| ResourceModified | `110` | L'utente modifica una risorsa aziendale in Project Web App. |
| ResourcePlanCheckedInOrOut | `111` | L'utente effettua il check-in o il check-out di un piano delle risorse in Project Web App. |
| ResourcePlanModified | `112` | L'utente modifica un piano delle risorse in Project Web App. |
| ResourcePlanPublished | `113` | L'utente pubblica un piano delle risorse in Project Web App. |
| ResourceRedacted | `114` | L'utente redige una risorsa aziendale rimuovendo tutte le informazioni personali in Project Web App. |
| ResourceWarningEnabledModified | `115` | Questa operazione è in Anteprima. Avviso quota risorse modificato. |
| SSOGroupCredentialsSet | `116` | Questa operazione è in Anteprima. Credenziali del gruppo impostate nel servizio di archiviazione sicura. |
| SSOUserCredentialsSet | `117` | Questa operazione è in Anteprima. Credenziali utente impostate nel servizio di archiviazione sicura. |
| SearchCenterUrlSet | `118` | Questa operazione è in Anteprima. URL del centro di ricerca impostato. |
| SecondaryMySiteOwnerSet | `119` | Questa operazione è in Anteprima. Un utente ha aggiunto un proprietario secondario al proprio MySite. |
| SecurityCategoryModified | `120` | L'utente crea, modifica o elimina una categoria di sicurezza in Project Web App. |
| SecurityGroupModified | `121` | L'utente crea, modifica o elimina un gruppo di sicurezza in Project Web App. |
| SendToConnectionAdded | `122` | Questa operazione è in Anteprima. L'amministratore globale crea una nuova connessione Invia a nella pagina Gestione record nell'interfaccia di amministrazione di SharePoint. Una connessione Invia a specifica le impostazioni per un repository di documenti o un centro record. Quando crei una connessione Invia a, Content Organizer può inviare documenti nella posizione specificata. |
| SendToConnectionRemoved | `123` | Questa operazione è in Anteprima. L'amministratore globale elimina una connessione Invia a nella pagina Gestione record nell'interfaccia di amministrazione di SharePoint. |
| SharedLinkCreated | `124` | L'utente crea un collegamento a un file condiviso in SharePoint o OneDrive for Business. Questo collegamento può essere inviato ad altre persone per consentire loro l'accesso al file. Un utente può creare due tipi di collegamenti: un collegamento che consente a un utente di visualizzare e modificare il file condiviso o un collegamento che consente all'utente di visualizzare semplicemente il file. |
| SharedLinkDisabled | `125` | Questa operazione è in Anteprima. L'utente disabilita (permanentemente) un collegamento creato per condividere un file. |
| SharingInvitationAccepted | `126` | Questa operazione è in Anteprima. L'utente accetta un invito a condividere un file o una cartella. Questo evento viene registrato quando un utente condivide un file con altri utenti. |
| SharingRevoked | `127` | Questa operazione è in Anteprima. L'utente annulla la condivisione di un file o di una cartella precedentemente condivisa con altri utenti. Questo evento viene registrato quando un utente interrompe la condivisione di un file con altri utenti. |
| SharingSet | `128` | L'utente condivide un file o una cartella che si trova in SharePoint o OneDrive for Business con un altro utente all'interno della propria organizzazione. |
| SiteAdminChangeRequest | `129` | Questa operazione è in Anteprima. L'utente richiede di essere aggiunto come amministratore della raccolta siti per una raccolta siti di SharePoint. Gli amministratori della raccolta siti dispongono delle autorizzazioni di controllo completo per la raccolta siti e tutti i siti secondari. |
| SiteCollectionAdminAdded | `130` | Questa operazione è in Anteprima. L'amministratore o il proprietario della raccolta siti aggiunge una persona come amministratore della raccolta siti per un sito di SharePoint o OneDrive for Business. Gli amministratori della raccolta siti dispongono delle autorizzazioni di controllo completo per la raccolta siti e tutti i siti secondari. |
| SiteCollectionCreated | `131` | Questa operazione è in Anteprima. L'amministratore globale crea una nuova raccolta siti nell'organizzazione di SharePoint. |
| SiteRenamed | `132` | Questa operazione è in Anteprima. L'amministratore o il proprietario del sito rinomina un sito di SharePoint o OneDrive for Business |
| StatusReportModified | `133` | L'utente crea, modifica o elimina un rapporto di stato in Project Web App. |
| SyncGetChanges | `134` | Questa operazione è in Anteprima. L'utente fa clic su Sincronizza nella barra delle azioni in SharePoint o OneDrive for Business per sincronizzare eventuali modifiche al file in una raccolta documenti sul proprio computer. |
| TaskStatusAccessed | `135` | L'utente accede allo stato di una o più attività in Project Web App. |
| TaskStatusApproved | `136` | L'utente approva un aggiornamento dello stato di una o più attività in Project Web App. |
| TaskStatusRejected | `137` | L'utente rifiuta un aggiornamento dello stato di una o più attività in Project Web App. |
| TaskStatusSaved | `138` | L'utente salva un aggiornamento dello stato di una o più attività in Project Web App. |
| TaskStatusSubmitted | `139` | L'utente invia un aggiornamento dello stato di una o più attività in Project Web App. |
| TimesheetAccessed | `140` | L'utente accede a una scheda attività in Project Web App. |
| TimesheetApproved | `141` | L'utente approva la scheda attività in Project Web App. |
| TimesheetRejected | `142` | L'utente rifiuta una scheda attività in Project Web App. |
| TimesheetSaved | `143` | L'utente salva una scheda attività in Project Web App. |
| TimesheetSubmitted | `144` | L'utente invia una scheda attività di stato in Project Web App. |
| UnmanagedSyncClientBlocked | `145` | L'utente tenta di stabilire una relazione di sincronizzazione con un sito SharePoint o OneDrive for Business da un computer che non è membro del dominio dell'organizzazione o è membro di un dominio che non è stato aggiunto all'elenco dei domini ( chiamato l'elenco dei destinatari sicuri) che possono accedere alle raccolte documenti nell'organizzazione. La relazione di sincronizzazione non è consentita e al computer dell'utente viene impedito di sincronizzare, scaricare o caricare file in una raccolta documenti. Per informazioni su questa funzionalità, vedere Usare i cmdlet di Windows PowerShell per abilitare la sincronizzazione di OneDrive per i domini che si trovano nell'elenco dei destinatari sicuri. |
| UpdateSSOApplication | `146` | Questa operazione è in Anteprima. Applicazione di destinazione aggiornata nel servizio di archiviazione sicura. |
| UserAddedToGroup | `147` | Questa operazione è in Anteprima. L'amministratore o il proprietario del sito aggiunge una persona a un gruppo in un sito di SharePoint o OneDrive for Business. L'aggiunta di una persona a un gruppo concede all'utente le autorizzazioni che sono state assegnate al gruppo. |
| UserRemovedFromGroup | `148` | Questa operazione è in Anteprima. L'amministratore o il proprietario del sito rimuove una persona da un gruppo in un sito di SharePoint o OneDrive for Business. Dopo che la persona è stata rimossa, non vengono più concesse le autorizzazioni assegnate al gruppo. |
| WorkflowModified | `149` | L'utente crea, modifica o elimina un tipo di progetto aziendale o fasi o fasi del flusso di lavoro in Project Web App. |

### Guarda anche

* spazio dei nomi [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
