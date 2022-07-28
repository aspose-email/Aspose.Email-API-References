---
title: Aspose.Email.Clients.ActiveSync.TransportLayer
second_title: Aspose.Email per riferimento all'API .NET
description: 
type: docs
weight: 80
url: /it/net/aspose.email.clients.activesync.transportlayer/
---


## Classi

| Classe | Descrizione |
| --- | --- |
| [AccountInformation](./accountinformation) | Contiene le informazioni sull'account dell'utente. |
| [ActiveSyncTLClient](./activesynctlclient) | Classe di base per implementazioni client ActiveSync |
| [AutodiscoverResult](./autodiscoverresult) | Risultato dell'operazione di individuazione automatica |
| [Body](./body) | Specifica un campo dati in formato libero ea lunghezza variabile associato a un elemento memorizzato sul server. |
| [BodyPart](./bodypart) | Specifica i dettagli sulla parte del messaggio di un messaggio di posta elettronica in una risposta. L'elemento BodyPart DEVE essere incluso in una risposta al comando quando BodyPartPreference è specificato in una richiesta. |
| [BodyPreference](./bodypreference) | Contiene informazioni sulle preferenze relative al tipo e alla dimensione delle informazioni restituite dalla ricerca, sincronizzazione o recupero. |
| [CertificateStatuses](./certificatestatuses) | Indica se il certificato è stato convalidato correttamente. |
| [DataContainer](./datacontainer) | Contiene i dati per un oggetto particolare, come un contatto, un messaggio di posta elettronica, un appuntamento del calendario o un elemento dell'attività. Il DataContainer può essere utilizzato per modificare elementi, aggiungere elementi o recuperare elementi sul dispositivo client o sul server. |
| [DeviceInformation](./deviceinformation) | Richiesta utilizzata per inviare le proprietà del dispositivo client al server. |
| [DevicePasswordRequest](./devicepasswordrequest) | Specifica la richiesta di impostare la password di ripristino del dispositivo client da parte del server. Per cancellare una password di ripristino esistente, il client DEVE inviare una Password vuota. |
| [EASProvisionDoc](./easprovisiondoc) | Specifica la raccolta delle impostazioni di sicurezza per il provisioning del dispositivo. |
| [EmptyFolderContentsRequest](./emptyfoldercontentsrequest) | Contiene la richiesta sull'eliminazione del contenuto di una cartella. EmptyFolderContents supporta un singolo elemento figlio dell'elemento Options, DeleteSubFolders, che determina se le sottocartelle contenute nella cartella vengono eliminate. Se l'opzione DeleteSubFolders non è inclusa nella richiesta, le sottocartelle del CollectionId specificato non vengono eliminate. |
| [FolderInfo](./folderinfo) | La classe FolderInfo contiene informazioni sulla cartella |
| [FolderSyncResult](./foldersyncresult) | Contiene le modifiche alla gerarchia delle cartelle. |
| [ItemEstimate](./itemestimate) | Contiene una valutazione nella cartella richiesta |
| [ItemEstimateOptions](./itemestimateoptions) | Contiene elementi che filtrano i risultati dell'operazione GetItemEstimate. |
| [ItemEstimateRequest](./itemestimaterequest) | Contiene i parametri della richiesta ItemEstimate |
| [ItemOperationsEmptFldrCntntsResponce](./itemoperationsemptfldrcntntsresponce) | Identifica il corpo della risposta come contenente l'operazione che elimina il contenuto di una cartella. |
| [ItemOperationsFetchProperties](./itemoperationsfetchproperties) | Contiene le proprietà restituite per gli elementi nella risposta. |
| [ItemOperationsFetchRequest](./itemoperationsfetchrequest) | Contiene la richiesta sul recupero di un elemento dal server. |
| [ItemOperationsFetchResponce](./itemoperationsfetchresponce) | Contiene la risposta sul recupero di un elemento dal server. |
| [ItemOperationsMoveRequest](./itemoperationsmoverequest) | Contiene la richiesta di spostare una conversazione in una cartella specifica. |
| [ItemOperationsMoveResponce](./itemoperationsmoveresponce) | Identifica il corpo della risposta come contenente l'operazione che sposta una determinata conversazione. |
| [ItemOperationsRequest](./itemoperationsrequest) | Contiene la richiesta ItemOperations. |
| [ItemOperationsResponse](./itemoperationsresponse) | Contiene la risposta ItemOperations. |
| [ItOpEmpFldCntOptions](./itopempfldcntoptions) | Contiene le opzioni per l'operazione ItemOperations.EmptyFolderContents |
| [ItOpFetchOptions](./itopfetchoptions) | Contiene le opzioni per l'operazione ItemOperations.Fetch. |
| [ItOpMoveOptions](./itopmoveoptions) | Contiene le opzioni per l'operazione ItemOperations.Move. |
| [MeetingResponseRequest](./meetingresponserequest) | Specifica la convocazione di riunione a cui si sta rispondendo, la risposta a tale richiesta di riunione e la cartella sul server in cui si trova la convocazione di riunione. |
| [MeetingResponseResult](./meetingresponseresult) | Risultato della risposta alla riunione oggetto |
| [MoveItemData](./moveitemdata) | Contiene informazioni sullo spostamento di oggetti |
| [MoveItemResponse](./moveitemresponse) | Contiene informazioni che descrivono gli elementi spostati. |
| [OOFMessage](./oofmessage) | Specifica il messaggio fuori sede per un determinato pubblico. Exchange 2007, Exchange 2010 ed Exchange 2013 richiedono che il messaggio di risposta per i destinatari esterni sconosciuti ed esterni noti sia lo stesso. La proprietà supporta i seguenti tre segmenti di pubblico per un messaggio fuori sede: Interno: un utente che fa parte della stessa organizzazione dell'utente mittente. Esterno noto: un utente che è esterno all'organizzazione dell'utente mittente, ma è rappresentato nei contatti dell'utente mittente. Esterno sconosciuto: un utente che è al di fuori dell'organizzazione dell'utente mittente. organizzazione e non è rappresentato nei contatti dell'utente mittente. |
| [OOFReqParametrs](./oofreqparametrs) | Ottiene le impostazioni delle informazioni fuori sede dal server. |
| [OOFRequest](./oofrequest) | Specifica una classe per il recupero e l'impostazione delle informazioni Fuori sede (OOF). |
| [OOFResponse](./oofresponse) | Specifica una classe per il recupero e l'impostazione delle informazioni Fuori sede (OOF). |
| [OOFSettings](./oofsettings) | Impostazioni informazioni fuori sede. |
| [PictureRequest](./picturerequest) | Indica che il client sta richiedendo che le foto vengano restituite nella risposta del server. L'immagine non è supportata quando la versione del protocollo è 12.1 o 14.0. Contiene i dati relativi alla richiesta di foto. |
| [PictureRespose](./picturerespose) | Contiene i dati relativi alle foto dei contatti. L'immagine non è supportata quando la versione del protocollo è 12.1 o 14.0. |
| [PingParameter](./pingparameter) | Contiene il comando ping parameters |
| [ProvisionPolicy](./provisionpolicy) | Specifica una politica di sicurezza. |
| [ProvisionPolicyData](./provisionpolicydata) | Specifica le impostazioni per un criterio. |
| [ProvisionRequest](./provisionrequest) | Contiene informazioni sulla richiesta per il provisioning command |
| [ProvisionResponse](./provisionresponse) | Contiene informazioni sulla risposta per il comando di provisioning |
| [QueryType](./querytype) | Specifica le parole chiave da utilizzare per la corrispondenza delle voci nell'archivio in cui viene eseguita la ricerca. Il valore della query viene utilizzato come modello di corrispondenza della stringa di prefisso e restituisce le voci che corrispondono all'inizio della stringa. Ad esempio, la ricerca di "John" corrisponderebbe a "John Frum" o "Barry Johnson", ma non corrisponderebbe a "James Littlejohn". Tutte le proprietà di testo non vuote nel GAL indicizzate tramite ANR vengono confrontate con l'elemento Query valore. I confronti di ricerca vengono eseguiti utilizzando la corrispondenza senza distinzione tra maiuscole e minuscole. Per una ricerca nella raccolta documenti di Windows SharePoint Services, questo protocollo supporta le query nel formato seguente: LinkId == valore, dove valore specifica l'URL dell'elemento o della cartella e LinkId indica che il valore deve essere confrontato con la proprietà dell'ID collegamento. Per la ricerca nella casella di posta, la sintassi della query è la seguente: - Le cartelle possono essere specificate nei seguenti modi: ID specificato Cartella e sottocartelle specificate Tutte le cartelle di posta elettronica, inclusa Bozza, Posta in arrivo e sottocartelle, Posta in uscita e Posta inviata - La query della parola chiave di base può essere composta da quanto segue: L'operatore di base: And (sezione 2.2.3.10) Un filtro dateTime specificato utilizzando GreaterThan (sezione 2.2.3.78) e LessThan elementi (sezione 2.2.3.87) Elementi FreeText (sezione 2.2.3.73) che contengono parole chiave La query di base per parole chiave viene eseguita su tutte le proprietà indicizzate. |
| [Recipient](./recipient) | Rappresenta un singolo destinatario che è stato risolto. |
| [ResolveRecipientsAvailabilityRequest](./resolverecipientsavailabilityrequest) | Indica al server che i dati sulla disponibilità sono richiesti dal client e identifica l'ora di inizio e l'ora di fine dei dati sulla disponibilità da recuperare. La disponibilità non è supportata quando la versione del protocollo è 12.1. |
| [ResolveRecipientsAvailabilityResponse](./resolverecipientsavailabilityresponse) | Identifica lo stato e i dati sulla disponibilità degli utenti o liste di distribuzione identificati nella richiesta per il tempo identificato da StartTime ed EndTime. Quando la disponibilità è inclusa in una richiesta ResolveRecipients, il server recupera le informazioni sulla disponibilità per gli utenti identificati negli elementi A inclusi nella richiesta e restituisce le informazioni sulla disponibilità in MergedFreeBusy nella risposta. Quando il server analizza la richiesta, il server risolve prima i destinatari identificati dagli elementi A, quindi determina le informazioni sulla disponibilità degli utenti per l'intervallo di tempo specificato, prima di restituire i dati sulla disponibilità in MergedFreeBusy. |
| [ResolveRecipientsCertificates](./resolverecipientscertificates) | Contiene informazioni sui certificati per un destinatario. |
| [ResolveRecipientsOptions](./resolverecipientsoptions) | Contiene le opzioni per la risoluzione dell'elenco dei destinatari. |
| [ResolveRecipientsRequest](./resolverecipientsrequest) | Contiene informazioni per risolvere i destinatari. |
| [ResolveRecipientsResponse](./resolverecipientsresponse) | Contiene informazioni sull'eventuale risoluzione del destinatario. Se il destinatario è stato risolto, contiene anche il tipo di destinatario, l'indirizzo e-mail a cui il destinatario ha risolto e, facoltativamente, il certificato S/MIME per il destinatario. |
| [RightsManagementInformationResponce](./rightsmanagementinformationresponce) | Contiene le impostazioni delle informazioni sulla gestione dei diritti recuperate dal server. |
| [RightsManagementLicense](./rightsmanagementlicense) | Contiene le impostazioni del modello di politica dei diritti per il modello applicato al messaggio di posta elettronica in fase di sincronizzazione. |
| [RightsManagementTemplate](./rightsmanagementtemplate) | Contiene l'identificatore del modello, il nome e la descrizione di un modello di politica dei diritti disponibile sul client. |
| [SearchCondition](./searchcondition) | Specifica una condizione per le richieste di ricerca |
| [SearchOptions](./searchoptions) | Contiene le opzioni di ricerca. UserName e Password possono essere inviati nella richiesta solo dopo aver ricevuto un valore di Stato pari a 14. Il server richiede queste credenziali per accedere alle risorse richieste. Il client DEVE inviare questi solo su una connessione sicura o affidabile e solo in risposta a un valore di stato di 14. Le opzioni supportate variano a seconda del negozio che viene cercato. La tabella seguente elenca le opzioni valide per ciascun negozio. GAL: Intervallo, Nome utente, Password, Immagine Cassetta postale: Intervallo, DeepTraversal, RebuildResults, BodyPreference, BodyPartPreference, RightsManagementSupport DocumentLibrary: Range, UserName, Password La BodyPartPreference è valida solo nella ricerca richieste di comando che includono un ConversationId. |
| [SearchQuery](./searchquery) | Specifica le parole chiave da utilizzare per la corrispondenza delle voci nell'archivio in cui viene eseguita la ricerca. Il valore della query viene utilizzato come modello di corrispondenza della stringa di prefisso e restituisce le voci che corrispondono all'inizio della stringa. Ad esempio, la ricerca di "John" corrisponderebbe a "John Frum" o "Barry Johnson", ma non corrisponderebbe a "James Littlejohn". Tutte le proprietà di testo non vuote nel GAL indicizzate tramite ANR vengono confrontate con l'elemento Query valore. I confronti di ricerca vengono eseguiti utilizzando la corrispondenza senza distinzione tra maiuscole e minuscole. Per una ricerca nella raccolta documenti di Windows SharePoint Services, questo protocollo supporta query del formato seguente: LinkId == valore, dove valore specifica l'URL dell'elemento o della cartella e LinkId indica che il valore deve essere confrontato con la proprietà dell'ID collegamento. Per la ricerca nella casella di posta, la sintassi della query è la seguente: - Le cartelle possono essere specificate nei seguenti modi: ID specificato Cartella e sottocartelle specificate Tutte le cartelle di posta elettronica, inclusa Bozza, Posta in arrivo e sottocartelle, Posta in uscita e Posta inviata - La query della parola chiave di base può essere composta da quanto segue: L'operatore di base: And (sezione 2.2.3.10) Un filtro dateTime specificato utilizzando GreaterThan (sezione 2.2.3.78) e LessThan elementi (sezione 2.2.3.87) Elementi FreeText (sezione 2.2.3.73) che contengono parole chiave La query di base per parole chiave viene eseguita su tutte le proprietà indicizzate. |
| [SearchRequest](./searchrequest) | Contiene informazioni sulla richiesta di ricerca |
| [SearchRequestStore](./searchrequeststore) | Specificare il nome, la query e le opzioni per la ricerca. |
| [SearchResponse](./searchresponse) | Contiene informazioni sulla risposta alla ricerca |
| [SearchResponseStore](./searchresponsestore) | Contiene gli elementi Stato, Risultato, Intervallo e Totale per le voci della cassetta postale restituite. |
| [SearchResult](./searchresult) | Contenitore per un singolo elemento della cassetta postale corrispondente. Quando l'archivio in cui viene eseguita la ricerca è la cassetta postale: - Esiste un elemento Risultato per ogni corrispondenza trovata nella cassetta postale. Se non vengono trovate corrispondenze, è presente un elemento Result vuoto nell'elemento Contenitore Store dell'XML di risposta. - All'interno dell'elemento Result, l'elemento Properties contiene un elenco di proprietà richieste per l'elemento della casella di posta. Quando l'archivio è la ricerca è nella raccolta documenti: - Il primo risultato restituito nella risposta di ricerca sono i metadati per la cartella principale o l'elemento a cui punta il valore LinkId. Il client può scegliere di ignorare questa voce se non la richiede. - Se il valore dell'elemento documentlibrary:LinkId nella richiesta punta a una cartella, le proprietà dei metadati della cartella vengono restituite come primo elemento e il contenuto di la cartella viene restituita come risultati successivi. L'intervallo si applica a questi risultati senza alcuna differenza; ad esempio, l'indice 0 sarebbe sempre per l'elemento radice a cui punta il collegamento. - Se il valore dell'elemento documentlibrary:LinkId nella richiesta punta a un elemento, viene restituito un solo risultato: i metadati per l'elemento. - All'interno dell'elemento Risultato, l'elemento Proprietà contiene un elenco di proprietà richieste per l'elemento della casella di posta. |
| [SearchResultProperties](./searchresultproperties) | La risposta del comando Cerca Proprietà è un contenitore di proprietà che si applicano a una singola voce che corrisponde alla stringa di ricerca dell'elemento Query. Ad esempio, l'elemento Properties contiene un elemento per ogni proprietà GAL con valore di testo non vuota collegata alla voce GAL corrispondente. Vengono restituite solo le proprietà allegate alla voce GAL specifica; pertanto è possibile restituire diversi insiemi di proprietà nell'XML di risposta per diverse voci GAL corrispondenti. Ciascun elemento nel contenitore Proprietà ha come ambito lo spazio dei nomi appropriato specificato nell'elemento Cerca di livello superiore. |
| [ServerInfo](./serverinfo) | Impostazioni del server nell'operazione di individuazione automatica |
| [SettingsRequest](./settingsrequest) | Il comando Impostazioni supporta le operazioni di recupero e impostazione sulle proprietà globali e le impostazioni Fuori sede (OOF) per l'utente. Il comando Impostazioni invia anche le informazioni sul dispositivo al server, implementa il ripristino della password del dispositivo/numero di identificazione personale (PIN) e recupera un elenco di indirizzi e-mail dell'utente. |
| [SettingsResponse](./settingsresponse) | Specifica una risposta con le impostazioni Fuori sede (OOF) e l'elenco degli account dell'utente. |
| [SmartRequest](./smartrequest) | Contiene informazioni sulla richiesta intelligente |
| [SmartRequestSource](./smartrequestsource) | Contiene informazioni sul messaggio di origine. |
| [Status](./status) | Indica il risultato di un'operazione. |
| [SyncAddClientOperation](./syncaddclientoperation) | Crea un nuovo oggetto in una raccolta sul client. |
| [SyncAddResponse](./syncaddresponse) | Serve per indicare che è necessario creare un nuovo oggetto in una collezione. |
| [SyncAddServerOperation](./syncaddserveroperation) | Crea un nuovo oggetto in una raccolta sul server. |
| [SyncChangeClientOperation](./syncchangeclientoperation) | Contiene le proprietà di un oggetto esistente sul dispositivo client che sono state modificate. L'oggetto modificato è identificato dal suo elemento ServerId. |
| [SyncChangeResponse](./syncchangeresponse) | Serve per indicare che un oggetto è stato modificato. |
| [SyncChangeServerOperation](./syncchangeserveroperation) | Contiene le proprietà di un oggetto esistente sul server che sono state modificate. L'oggetto modificato è identificato dal suo elemento ServerId. |
| [SyncCollectionRequest](./synccollectionrequest) | La classe contiene comandi e opzioni che si applicano a una particolare raccolta. |
| [SyncCollectionResponse](./synccollectionresponse) | La classe contiene comandi e opzioni che si applicano a una risposta di sincronizzazione. |
| [SyncCommandsRequest](./synccommandsrequest) | Contiene le operazioni che si applicano a una raccolta. Le operazioni disponibili sono Aggiungi, Elimina, Modifica, Recupera e SoftDelete. |
| [SyncCommandsResponse](./synccommandsresponse) | Contiene le operazioni che si applicano a una raccolta. Le operazioni disponibili sono Aggiungi, Elimina, Modifica, Recupera e SoftDelete. |
| [SyncDeleteClientOperation](./syncdeleteclientoperation) | Elimina un oggetto sul dispositivo client o sul server. L'oggetto è identificato dal suo ServerId. |
| [SyncFetchResponse](./syncfetchresponse) | Richiede i dati dell'applicazione di un elemento che è stato troncato in una risposta di sincronizzazione dal server. |
| [SyncOperationResponse](./syncoperationresponse) | Classe astratta di base per le risposte all'operazione di sincronizzazione |
| [SyncOperationsResponse](./syncoperationsresponse) | Contiene le risposte alle operazioni come Aggiungi, Recupera, Modifica che vengono elaborate dal server. La risposta contiene un codice di stato e altre informazioni, a seconda dell'operazione. |
| [SyncOptions](./syncoptions) | Specifica le opzioni che controllano determinati aspetti di come viene eseguita la sincronizzazione. |
| [SyncRequest](./syncrequest) | Contiene i parametri della richiesta di sincronizzazione |
| [UserInformationResponse](./userinformationresponse) | Contiene lo stato della richiesta e un elenco delle informazioni sull'account di un utente (indirizzi e-mail). |
| [ValueConverter](./valueconverter) | La classe converte la versione del protocollo ActiveSync dalla rappresentazione di stringa in enum e viceversa. |
## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IActiveSyncTLClient](./iactivesynctlclient) | Interfaccia client ActiveSync |
| [IBaseActiveSyncTLClient](./ibaseactivesynctlclient) | Interfaccia client ActiveSync di base |
## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [ActiveSyncAuthenticationType](./activesyncauthenticationtype) | Enum specifica il tipo di autenticazione |
| [AirSync](./airsync) | Spazio dei nomi AirSync del protocollo ActiveSync |
| [AirSyncBase](./airsyncbase) | Spazio dei nomi AirSyncBase del protocollo ActiveSync |
| [AirsyncClass](./airsyncclass) | Identifica la classe dell'elemento. Le seguenti classi sono supportate per le ricerche nella casella di posta quando la versione del protocollo è 12.1: - Email - Calendar - Contacts - Tasks Le classi SMS e Notes sono disponibili solo se la versione del protocollo è 14.0 o 14.1. |
| [AirsyncFilterType](./airsyncfiltertype) | Specifica una finestra temporale facoltativa per gli oggetti |
| [AllowBluetooth](./allowbluetooth) | Specifica l'uso del Bluetooth sul dispositivo. |
| [ASProtocolVersions](./asprotocolversions) | ASProtocolVersions indica le versioni del protocollo ActiveSync. |
| [BehaviorReplacement](./behaviorreplacement) | Specifica come risolvere il conflitto che si verifica quando un oggetto è stato modificato sia sul client che sul server. Il valore specifica quale oggetto, l'oggetto client o l'oggetto server, da conservare in caso di conflitto. |
| [BodyType](./bodytype) | Specifica il tipo di formato del contenuto del corpo dell'elemento. |
| [Calendar](./calendar) | Spazio dei nomi del calendario del protocollo ActiveSync |
| [CertificateRetrieval](./certificateretrieval) | Specifica se i certificati S/MIME DEVONO essere restituiti dal server per ogni destinatario risolto. |
| [CommandCodes](./commandcodes) | La tabella seguente fornisce i codici numerici che corrispondono ai comandi ActiveSync. Il codice numerico viene utilizzato nel campo Codice comando dell'URI con codifica base64 per specificare il comando. |
| [CommandParameters](./commandparameters) | Parametri di comando. |
| [ComposeMail](./composemail) | Spazio dei nomi ComposeMail del protocollo ActiveSync |
| [Contacts](./contacts) | Spazio dei nomi dei contatti del protocollo ActiveSync |
| [Contacts2](./contacts2) | Spazio dei nomi Contacts2 del protocollo ActiveSync |
| [DocumentLibrary](./documentlibrary) | Spazio dei nomi DocumentLibrary del protocollo ActiveSync |
| [Email](./email) | Spazio dei nomi e-mail del protocollo ActiveSync |
| [Email2](./email2) | Spazio dei nomi Email2 del protocollo ActiveSync |
| [EncryptionSMIMEAlgorithm](./encryptionsmimealgorithm) | Specifica l'algoritmo utilizzato durante la crittografia dei messaggi S/MIME. |
| [FolderClass](./folderclass) | Specifica la classe di contenuto della cartella da monitorare. |
| [FolderHierarchy](./folderhierarchy) | Spazio dei nomi FolderHierarchy del protocollo ActiveSync |
| [FolderTypes](./foldertypes) | Specifica il tipo di cartella che è stata aggiornata (rinominata o spostata) o aggiunta al server. |
| [GAL](./gal) | Spazio dei nomi GAL del protocollo ActiveSync |
| [GetItemEstimate](./getitemestimate) | GetItemEstimate spazio dei nomi del protocollo ActiveSync |
| [ItemOperations](./itemoperations) | Spazio dei nomi ItemOperations del protocollo ActiveSync |
| [MaxAgeFilter](./maxagefilter) | Specifica il numero massimo di giorni di calendario che possono essere sincronizzati. |
| [MeetingResponse](./meetingresponse) | Spazio dei nomi MeetingResponse del protocollo ActiveSync |
| [MergedFreeBusy](./mergedfreebusy) | Specifica le informazioni sulla disponibilità per gli utenti o la lista di distribuzione. |
| [MIMESupport](./mimesupport) | Abilita il supporto MIME per gli elementi di posta elettronica inviati dal server al client. |
| [MIMETruncation](./mimetruncation) | Specifica se i dati MIME dell'elemento e-mail DEVONO essere troncati quando viene inviato dal server al client. |
| [MinDevicePasswordComplexCharacters](./mindevicepasswordcomplexcharacters) | Specifica il livello di complessità richiesto della password del client. Ad esempio: Se il valore di MinDevicePasswordComplexCharacters è 2, sarebbe sufficiente una password con caratteri alfabetici sia maiuscoli che minuscoli, come sarebbe una password con caratteri alfabetici minuscoli e numeri. |
| [Move](./move) | Sposta lo spazio dei nomi del protocollo ActiveSync |
| [Namespace](./namespace) | Pagine codici ActiveSync |
| [Notes](./notes) | Spazio dei nomi delle note del protocollo ActiveSync |
| [OofState](./oofstate) | Specifica la disponibilità della proprietà Oof. |
| [Ping](./ping) | Spazio dei nomi ping del protocollo ActiveSync |
| [Provision](./provision) | Fornitura dello spazio dei nomi del protocollo ActiveSync |
| [ProvisionPolicyStatuses](./provisionpolicystatuses) | Il valore indica l'esito positivo o negativo dell'applicazione da parte del client delle impostazioni dei criteri recuperate dal server. |
| [ProvisionRemoteWipeStatuses](./provisionremotewipestatuses) | Il valore indica l'esito positivo o negativo di un'operazione di cancellazione remota sul client. |
| [RecipientType](./recipienttype) | Indica il tipo di destinatario. |
| [ResolveRecipients](./resolverecipients) | Spazio dei nomi ResolveRecipients del protocollo ActiveSync |
| [RightsManagement](./rightsmanagement) | Spazio dei nomi RightsManagement del protocollo ActiveSync |
| [Search](./search) | Cerca lo spazio dei nomi del protocollo ActiveSync |
| [ServerType](./servertype) | Specifica il tipo di server |
| [Settings](./settings) | Impostazioni spazio dei nomi del protocollo ActiveSync |
| [SignedSMIMEAlgorithm](./signedsmimealgorithm) | Specifica l'algoritmo utilizzato durante la firma dei messaggi S/MIME. |
| [SMIMEEncryptionAlgorithmNegotiation](./smimeencryptionalgorithmnegotiation) | Controlla la negoziazione dell'algoritmo di crittografia. |
| [StoreType](./storetype) | Contiene l'infarmation che specifica la posizione, per le operazioni. |
| [Tasks](./tasks) | Spazio dei nomi delle attività del protocollo ActiveSync |
| [UserCreatedFolderTypes](./usercreatedfoldertypes) | Specifica il tipo di cartella da creare. |
| [UserResponse](./userresponse) | Indica se la riunione viene accettata, accettata provvisoriamente o rifiutata. |
| [ValidateCert](./validatecert) | Spazio dei nomi ValidateCert del protocollo ActiveSync |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
