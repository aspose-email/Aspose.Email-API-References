---
title: Aspose.Email.Clients.ActiveSync.TransportLayer
second_title: Référence de l'API Aspose.Email pour .NET
description: 
type: docs
weight: 80
url: /fr/net/aspose.email.clients.activesync.transportlayer/
---


## Des classes

| Classer | La description |
| --- | --- |
| [AccountInformation](./accountinformation) | Contient les informations de compte de l'utilisateur. |
| [ActiveSyncTLClient](./activesynctlclient) | Classe de base pour les implémentations de client ActiveSync |
| [AutodiscoverResult](./autodiscoverresult) | Résultat de l'opération de découverte automatique |
| [Body](./body) | Spécifie un champ de données de forme libre et de longueur variable associé à un élément stocké sur le serveur. |
| [BodyPart](./bodypart) | Spécifie des détails sur la partie message d'un e-mail dans une réponse. L'élément BodyPart DOIT être inclus dans une réponse de commande lorsque BodyPartPreference est spécifié dans une requête. |
| [BodyPreference](./bodypreference) | Contient des informations de préférence liées au type et à la taille des informations renvoyées par la recherche, la synchronisation ou la récupération. |
| [CertificateStatuses](./certificatestatuses) | Indique si le certificat a été validé avec succès. |
| [DataContainer](./datacontainer) | Contient des données pour un objet particulier, tel qu'un contact, un message électronique, un rendez-vous de calendrier ou un élément de tâche. Le DataContainer peut être utilisé pour modifier des éléments, ajouter des éléments ou récupérer des éléments sur le périphérique client ou le serveur. |
| [DeviceInformation](./deviceinformation) | Requête utilisée pour envoyer les propriétés de l'appareil client au serveur. |
| [DevicePasswordRequest](./devicepasswordrequest) | Spécifie la demande de définition du mot de passe de récupération du périphérique client par le serveur. Pour effacer un mot de passe de récupération existant, le client DOIT envoyer un mot de passe vide. |
| [EASProvisionDoc](./easprovisiondoc) | Spécifie la collection de paramètres de sécurité pour le provisionnement des appareils. |
| [EmptyFolderContentsRequest](./emptyfoldercontentsrequest) | Contient une demande de suppression du contenu d'un dossier. EmptyFolderContents prend en charge un seul élément enfant de l'élément Options, DeleteSubFolders, qui détermine si les sous-dossiers contenus dans le dossier sont supprimés. Si l'option DeleteSubFolders n'est pas incluse dans la requête, les sous-dossiers du CollectionId spécifié ne sont pas supprimés. |
| [FolderInfo](./folderinfo) | La classe FolderInfo contient des informations sur le dossier |
| [FolderSyncResult](./foldersyncresult) | Contient les modifications apportées à la hiérarchie des dossiers. |
| [ItemEstimate](./itemestimate) | Contient une évaluation sur le dossier demandé |
| [ItemEstimateOptions](./itemestimateoptions) | Contient des éléments qui filtrent les résultats de l'opération GetItemEstimate. |
| [ItemEstimateRequest](./itemestimaterequest) | Contient les paramètres de requête ItemEstimate |
| [ItemOperationsEmptFldrCntntsResponce](./itemoperationsemptfldrcntntsresponce) | Identifie le corps de la réponse comme contenant l'opération qui supprime le contenu d'un dossier. |
| [ItemOperationsFetchProperties](./itemoperationsfetchproperties) | Contient les propriétés renvoyées pour les éléments de la réponse. |
| [ItemOperationsFetchRequest](./itemoperationsfetchrequest) | Contient une requête sur la récupération d'un élément du serveur. |
| [ItemOperationsFetchResponce](./itemoperationsfetchresponce) | Contient une réponse sur la récupération d'un élément du serveur. |
| [ItemOperationsMoveRequest](./itemoperationsmoverequest) | Contient une demande concernant le déplacement d'une conversation vers un dossier spécifique. |
| [ItemOperationsMoveResponce](./itemoperationsmoveresponce) | Identifie le corps de la réponse comme contenant l'opération qui déplace une conversation donnée. |
| [ItemOperationsRequest](./itemoperationsrequest) | Contient la requête ItemOperations. |
| [ItemOperationsResponse](./itemoperationsresponse) | Contient la réponse ItemOperations. |
| [ItOpEmpFldCntOptions](./itopempfldcntoptions) | Contient les options pour l'opération ItemOperations.EmptyFolderContents |
| [ItOpFetchOptions](./itopfetchoptions) | Contient les options de l'opération ItemOperations.Fetch. |
| [ItOpMoveOptions](./itopmoveoptions) | Contient les options de l'opération ItemOperations.Move. |
| [MeetingResponseRequest](./meetingresponserequest) | Spécifie la demande de réunion à laquelle on répond, la réponse à cette demande de réunion et le dossier sur le serveur dans lequel se trouve la demande de réunion. |
| [MeetingResponseResult](./meetingresponseresult) | Objet de résultat de réponse de réunion |
| [MoveItemData](./moveitemdata) | Contient des informations sur le déplacement d'éléments |
| [MoveItemResponse](./moveitemresponse) | Contient des informations décrivant les éléments déplacés. |
| [OOFMessage](./oofmessage) | Spécifie le message OOF pour une audience particulière. Exchange 2007, Exchange 2010 et Exchange 2013 exigent que le message de réponse pour les audiences externes inconnues et connues soit le même. La propriété prend en charge les trois audiences suivantes pour un message OOF : Interne — Un utilisateur qui est dans la même organisation que l'utilisateur expéditeur. Connu externe — Un utilisateur qui est en dehors de l'organisation de l'utilisateur expéditeur, mais qui est représenté dans les contacts de l'utilisateur expéditeur. Inconnu externe — Un utilisateur qui est en dehors de l'utilisateur expéditeur organisation et n'est pas représenté dans les contacts de l'utilisateur expéditeur. |
| [OOFReqParametrs](./oofreqparametrs) | Obtient les paramètres d'informations OOF du serveur. |
| [OOFRequest](./oofrequest) | Spécifie une classe pour récupérer et définir les informations d'absence du bureau (OOF). |
| [OOFResponse](./oofresponse) | Spécifie une classe pour récupérer et définir les informations d'absence du bureau (OOF). |
| [OOFSettings](./oofsettings) | Paramètres d'informations OOF. |
| [PictureRequest](./picturerequest) | Indique que le client demande que les photos soient renvoyées dans la réponse du serveur. L'image n'est pas prise en charge lorsque la version du protocole est 12.1 ou 14.0. Contient les données relatives à la demande de photos. |
| [PictureRespose](./picturerespose) | Contient les données relatives aux photos de contact. L'image n'est pas prise en charge lorsque la version du protocole est 12.1 ou 14.0. |
| [PingParameter](./pingparameter) | Contient les paramètres de la commande ping |
| [ProvisionPolicy](./provisionpolicy) | Spécifie une politique de sécurité. |
| [ProvisionPolicyData](./provisionpolicydata) | Spécifie les paramètres d'une stratégie. |
| [ProvisionRequest](./provisionrequest) | Contient les informations de demande pour la provision command |
| [ProvisionResponse](./provisionresponse) | Contient les informations de réponse pour la commande de provisionnement |
| [QueryType](./querytype) | Spécifie les mots-clés à utiliser pour faire correspondre les entrées du magasin recherché. La valeur de la requête est utilisée comme modèle de correspondance de chaîne de préfixe et renvoie les entrées qui correspondent au début de la chaîne. Par exemple, la recherche de "John" correspondrait à "John Frum" ou "Barry Johnson", mais ne correspondrait pas à "James Littlejohn". Toutes les propriétés de texte non vides dans la GAL qui sont indexées à l'aide de l'ANR sont comparées à l'élément Query évaluer. Les comparaisons de recherche sont effectuées à l'aide d'une correspondance insensible à la casse. Pour une recherche dans la bibliothèque de documents Windows SharePoint Services, ce protocole prend en charge les requêtes de la forme suivante : LinkId == valeur, où valeur spécifie l'URL de l'élément ou du dossier et LinkId indique que la valeur doit être comparée à la propriété d'ID de lien. Pour la recherche de boîte aux lettres, la syntaxe de la requête est la suivante : - Les dossiers peuvent être spécifiés des manières suivantes : ID spécifié Dossier et sous-dossiers spécifiés Tous les dossiers de messagerie, y compris les brouillons, Boîte de réception et sous-dossiers, Boîte d'envoi et Éléments envoyés - La requête de mot-clé de base peut être composée des éléments suivants : L'opérateur de base : Et (section 2.2.3.10) Un filtre dateTime spécifié à l'aide de GreaterThan (section 2.2.3.78) et LessThan éléments (section 2.2.3.87) éléments FreeText (section 2.2.3.73) qui contiennent des mots-clés La requête de mot-clé de base est exécutée sur toutes les propriétés indexées. |
| [Recipient](./recipient) | Représente un seul destinataire qui a été résolu. |
| [ResolveRecipientsAvailabilityRequest](./resolverecipientsavailabilityrequest) | Indique au serveur que des données de disponibilité sont demandées par le client et identifie l'heure de début et l'heure de fin des données de disponibilité à récupérer. La disponibilité n'est pas prise en charge lorsque la version du protocole est 12.1. |
| [ResolveRecipientsAvailabilityResponse](./resolverecipientsavailabilityresponse) | Identifie l'état et les données de disponibilité des utilisateurs ou des listes de distribution identifiés dans la demande pour l'heure identifiée par StartTime et EndTime. Lorsque la disponibilité est incluse dans une demande ResolveRecipients, le serveur récupère les informations de disponibilité pour les utilisateurs identifiés dans les éléments To inclus dans la demande et renvoie les informations de disponibilité dans MergedFreeBusy dans la réponse. Lorsque le serveur analyse la demande, le serveur résout d'abord les destinataires identifiés par les éléments À, puis détermine les informations de disponibilité des utilisateurs pour la période spécifiée, avant de renvoyer les données de disponibilité dans MergedFreeBusy. |
| [ResolveRecipientsCertificates](./resolverecipientscertificates) | Contient des informations sur les certificats d'un destinataire. |
| [ResolveRecipientsOptions](./resolverecipientsoptions) | Contient les options de résolution de la liste des destinataires. |
| [ResolveRecipientsRequest](./resolverecipientsrequest) | Contient des informations pour résoudre les destinataires. |
| [ResolveRecipientsResponse](./resolverecipientsresponse) | Contient des informations indiquant si le destinataire a été résolu. Si le destinataire a été résolu, il contient également le type de destinataire, l'adresse e-mail à laquelle le destinataire a résolu et, éventuellement, le certificat S/MIME du destinataire. |
| [RightsManagementInformationResponce](./rightsmanagementinformationresponce) | Contient les paramètres d'informations de gestion des droits extraits du serveur. |
| [RightsManagementLicense](./rightsmanagementlicense) | Contient les paramètres de modèle de stratégie de droits pour le modèle appliqué au message électronique en cours de synchronisation. |
| [RightsManagementTemplate](./rightsmanagementtemplate) | Contient l'identifiant du modèle, le nom et la description d'un modèle de stratégie de droits disponible sur le client. |
| [SearchCondition](./searchcondition) | Spécifie une condition pour les demandes de recherche |
| [SearchOptions](./searchoptions) | Contient les options de recherche. Le nom d'utilisateur et le mot de passe ne peuvent être envoyés dans la demande qu'après avoir reçu une valeur de statut de 14. Le serveur a besoin de ces informations d'identification pour accéder aux ressources demandées. Le client DOIT les envoyer uniquement via une connexion sécurisée ou approuvée, et uniquement en réponse à une valeur de statut de 14. Les options prises en charge varient en fonction du magasin recherché. Le tableau suivant répertorie les options valides pour chaque magasin. GAL : Range, UserName, Password, Picture Mailbox : Range, DeepTraversal, RebuildResults, BodyPreference, BodyPartPreference, RightsManagementSupport DocumentLibrary : Range, UserName, Password La BodyPartPreference n'est valide que dans la recherche demandes de commande qui incluent un ConversationId. |
| [SearchQuery](./searchquery) | Spécifie les mots-clés à utiliser pour faire correspondre les entrées du magasin recherché. La valeur de la requête est utilisée comme modèle de correspondance de chaîne de préfixe et renvoie les entrées qui correspondent au début de la chaîne. Par exemple, la recherche de "John" correspondrait à "John Frum" ou "Barry Johnson", mais ne correspondrait pas à "James Littlejohn". Toutes les propriétés de texte non vides dans la GAL qui sont indexées à l'aide de l'ANR sont comparées à l'élément Query évaluer. Les comparaisons de recherche sont effectuées à l'aide d'une correspondance insensible à la casse. Pour une recherche dans la bibliothèque de documents Windows SharePoint Services, ce protocole prend en charge les requêtes de la forme suivante : LinkId == valeur, où la valeur spécifie l'URL de l'élément ou du dossier et LinkId indique que la valeur doit être comparée à la propriété d'ID de lien. Pour la recherche de boîte aux lettres, la syntaxe de la requête est la suivante : - Les dossiers peuvent être spécifiés des manières suivantes : ID spécifié Dossier et sous-dossiers spécifiés Tous les dossiers de messagerie, y compris les brouillons, Boîte de réception et sous-dossiers, Boîte d'envoi et Éléments envoyés - La requête de mot-clé de base peut être composée des éléments suivants : L'opérateur de base : Et (section 2.2.3.10) Un filtre dateTime spécifié à l'aide de GreaterThan (section 2.2.3.78) et LessThan éléments (section 2.2.3.87) éléments FreeText (section 2.2.3.73) qui contiennent des mots-clés La requête de mot-clé de base est exécutée sur toutes les propriétés indexées. |
| [SearchRequest](./searchrequest) | Contient des informations sur la demande de recherche |
| [SearchRequestStore](./searchrequeststore) | Spécifiez le nom, la requête et les options de recherche. |
| [SearchResponse](./searchresponse) | Contient des informations de réponse de recherche |
| [SearchResponseStore](./searchresponsestore) | Contient les éléments État, Résultat, Plage et Total des entrées de boîte aux lettres renvoyées. |
| [SearchResult](./searchresult) | Conteneur pour un élément de boîte aux lettres correspondant individuel. Lorsque le magasin recherché est la boîte aux lettres : - Il existe un élément de résultat pour chaque correspondance trouvée dans la boîte aux lettres. Si aucune correspondance n'est trouvée, un élément Result vide est présent dans l'élément Conteneur Store du XML de réponse. - Dans l'élément Result, l'élément Properties contient une liste des propriétés demandées pour l'élément de boîte aux lettres. Lorsque le magasin qui est faisant l'objet de la recherche est la bibliothèque de documents : - Le premier résultat renvoyé dans la réponse de recherche correspond aux métadonnées du dossier racine ou de l'élément vers lequel la valeur LinkId pointe. Le client peut choisir d'ignorer cette entrée s'il ne l'exige pas. - Si la valeur de l'élément documentlibrary:LinkId dans la requête pointe vers un dossier, les propriétés de métadonnées du dossier sont renvoyées en tant que premier élément, et le contenu de le dossier sont renvoyés en tant que résultats ultérieurs. La plage s'applique à ces résultats sans différence ; par exemple, l'index 0 serait toujours pour l'élément racine vers lequel le lien pointe. - Si la valeur de l'élément documentlibrary:LinkId dans la requête pointe vers un élément, un seul résultat est renvoyé : les métadonnées de l'élément. - À l'intérieur de l'élément Result, l'élément Properties contient une liste des propriétés demandées pour l'élément de boîte aux lettres. |
| [SearchResultProperties](./searchresultproperties) | Les propriétés de réponse de la commande de recherche sont un conteneur pour les propriétés qui s'appliquent à une entrée individuelle qui correspond à la chaîne de recherche de l'élément Query. Par exemple, l'élément Propriétés contient un élément pour chaque propriété GAL à valeur texte non vide qui est attachée à l'entrée GAL correspondante. Seules les propriétés associées à l'entrée GAL spécifique sont renvoyées ; par conséquent, différents ensembles de propriétés peuvent être renvoyés dans la réponse XML pour différentes entrées GAL correspondantes. Chaque élément du conteneur Propriétés est limité à l'espace de noms approprié qui est spécifié dans l'élément de recherche de niveau supérieur. |
| [ServerInfo](./serverinfo) | Paramètres du serveur dans l'opération de découverte automatique |
| [SettingsRequest](./settingsrequest) | La commande Paramètres prend en charge les opérations d'obtention et de définition sur les propriétés globales et les paramètres d'absence du bureau (OOF) pour l'utilisateur. La commande Paramètres envoie également des informations sur l'appareil au serveur, implémente la récupération du mot de passe/numéro d'identification personnel (PIN) de l'appareil et récupère une liste des adresses e-mail de l'utilisateur. |
| [SettingsResponse](./settingsresponse) | Spécifie une réponse avec les paramètres d'absence du bureau (OOF) et la liste des comptes de l'utilisateur. |
| [SmartRequest](./smartrequest) | Contient des informations de requête intelligente |
| [SmartRequestSource](./smartrequestsource) | Contient des informations sur le message source. |
| [Status](./status) | Indique le résultat d'une opération. |
| [SyncAddClientOperation](./syncaddclientoperation) | Crée un nouvel objet dans une collection sur le client. |
| [SyncAddResponse](./syncaddresponse) | Sert à indiquer qu'un nouvel objet doit être créé dans une collection. |
| [SyncAddServerOperation](./syncaddserveroperation) | Crée un nouvel objet dans une collection sur le serveur. |
| [SyncChangeClientOperation](./syncchangeclientoperation) | Contient les propriétés d'un objet existant sur le périphérique client qui ont été modifiées. L'objet modifié est identifié par son élément ServerId. |
| [SyncChangeResponse](./syncchangeresponse) | Sert à indiquer qu'un objet a été modifié. |
| [SyncChangeServerOperation](./syncchangeserveroperation) | Contient les propriétés d'un objet existant sur le serveur qui ont été modifiées. L'objet modifié est identifié par son élément ServerId. |
| [SyncCollectionRequest](./synccollectionrequest) | La classe contient des commandes et des options qui s'appliquent à une collection particulière. |
| [SyncCollectionResponse](./synccollectionresponse) | La classe contient des commandes et des options qui s'appliquent à une réponse Sync. |
| [SyncCommandsRequest](./synccommandsrequest) | Contient les opérations qui s'appliquent à une collection. Les opérations disponibles sont Add, Delete, Change, Fetch et SoftDelete. |
| [SyncCommandsResponse](./synccommandsresponse) | Contient les opérations qui s'appliquent à une collection. Les opérations disponibles sont Add, Delete, Change, Fetch et SoftDelete. |
| [SyncDeleteClientOperation](./syncdeleteclientoperation) | Supprime un objet sur l'appareil client ou le serveur. L'objet est identifié par son ServerId. |
| [SyncFetchResponse](./syncfetchresponse) | Demande les données d'application d'un élément qui a été tronqué dans une réponse de synchronisation du serveur. |
| [SyncOperationResponse](./syncoperationresponse) | Classe abstraite de base pour les réponses d'opération de synchronisation |
| [SyncOperationsResponse](./syncoperationsresponse) | Contient les réponses aux opérations telles que Add, Fetch, Change qui sont traitées par le serveur. La réponse contient un code d'état et d'autres informations, selon l'opération. |
| [SyncOptions](./syncoptions) | Spécifie les options qui contrôlent certains aspects de la façon dont la synchronisation est effectuée. |
| [SyncRequest](./syncrequest) | Contient les paramètres de requête de synchronisation |
| [UserInformationResponse](./userinformationresponse) | Contient l'état de la demande et une liste des informations de compte d'un utilisateur (adresses e-mail). |
| [ValueConverter](./valueconverter) | La classe convertit la version du protocole ActiveSync de la représentation sous forme de chaîne en énumération et inversement. |
## Interfaces

| Interface | La description |
| --- | --- |
| [IActiveSyncTLClient](./iactivesynctlclient) | interface client ActiveSync |
| [IBaseActiveSyncTLClient](./ibaseactivesynctlclient) | Interface client ActiveSync de base |
## Énumération

| Énumération | La description |
| --- | --- |
| [ActiveSyncAuthenticationType](./activesyncauthenticationtype) | Enum spécifie le type d'authentification |
| [AirSync](./airsync) | Espace de noms AirSync du protocole ActiveSync |
| [AirSyncBase](./airsyncbase) | Espace de noms AirSyncBase du protocole ActiveSync |
| [AirsyncClass](./airsyncclass) | Identifie la classe de l'élément. Les classes suivantes sont prises en charge pour les recherches de boîtes aux lettres lorsque la version du protocole est 12.1 : - Email - Calendrier - Contacts - Tâches Les classes SMS et Notes ne sont disponibles que si la version du protocole est 14.0 ou 14.1. |
| [AirsyncFilterType](./airsyncfiltertype) | Spécifie une fenêtre de temps facultative pour les objets |
| [AllowBluetooth](./allowbluetooth) | Spécifie l'utilisation de Bluetooth sur l'appareil. |
| [ASProtocolVersions](./asprotocolversions) | ASProtocolVersions indique les versions du protocole ActiveSync. |
| [BehaviorReplacement](./behaviorreplacement) | Spécifie comment résoudre le conflit qui se produit lorsqu'un objet a été modifié à la fois sur le client et sur le serveur. La valeur spécifie quel objet (l'objet client ou l'objet serveur) conserver en cas de conflit. |
| [BodyType](./bodytype) | Spécifie le type de format du contenu du corps de l'élément. |
| [Calendar](./calendar) | Espace de noms de calendrier du protocole ActiveSync |
| [CertificateRetrieval](./certificateretrieval) | Spécifie si les certificats S/MIME DEVRAIENT être renvoyés par le serveur pour chaque destinataire résolu. |
| [CommandCodes](./commandcodes) | Le tableau suivant fournit les codes numériques qui correspondent aux commandes ActiveSync. Le code numérique est utilisé dans le champ Code de commande de l'URI encodé en base64 pour spécifier la commande. |
| [CommandParameters](./commandparameters) | Paramètres de commande. |
| [ComposeMail](./composemail) | Espace de noms ComposeMail du protocole ActiveSync |
| [Contacts](./contacts) | Espace de noms des contacts du protocole ActiveSync |
| [Contacts2](./contacts2) | Espace de noms Contacts2 du protocole ActiveSync |
| [DocumentLibrary](./documentlibrary) | Espace de noms DocumentLibrary du protocole ActiveSync |
| [Email](./email) | Espace de noms de messagerie du protocole ActiveSync |
| [Email2](./email2) | Espace de noms Email2 du protocole ActiveSync |
| [EncryptionSMIMEAlgorithm](./encryptionsmimealgorithm) | Spécifie l'algorithme utilisé lors du chiffrement des messages S/MIME. |
| [FolderClass](./folderclass) | Spécifie la classe de contenu du dossier à surveiller. |
| [FolderHierarchy](./folderhierarchy) | Espace de noms FolderHierarchy du protocole ActiveSync |
| [FolderTypes](./foldertypes) | Spécifie le type de dossier qui a été mis à jour (renommé ou déplacé) ou ajouté sur le serveur. |
| [GAL](./gal) | Espace de noms GAL du protocole ActiveSync |
| [GetItemEstimate](./getitemestimate) | Espace de noms GetItemEstimate du protocole ActiveSync |
| [ItemOperations](./itemoperations) | Espace de noms ItemOperations du protocole ActiveSync |
| [MaxAgeFilter](./maxagefilter) | Spécifie le nombre maximum de jours calendaires pouvant être synchronisés. |
| [MeetingResponse](./meetingresponse) | Espace de noms MeetingResponse du protocole ActiveSync |
| [MergedFreeBusy](./mergedfreebusy) | Spécifie les informations de disponibilité pour les utilisateurs ou la liste de distribution. |
| [MIMESupport](./mimesupport) | Active la prise en charge MIME pour les éléments de courrier électronique envoyés du serveur au client. |
| [MIMETruncation](./mimetruncation) | Spécifie si les données MIME de l'élément de courrier électronique DOIVENT être tronquées lorsqu'elles sont envoyées du serveur au client. |
| [MinDevicePasswordComplexCharacters](./mindevicepasswordcomplexcharacters) | Spécifie le niveau requis de complexité du mot de passe client. Par exemple : Si la valeur de MinDevicePasswordComplexCharacters est 2, un mot de passe avec des caractères alphabétiques majuscules et minuscules serait suffisant, tout comme un mot de passe avec des caractères alphabétiques minuscules et des chiffres. |
| [Move](./move) | Déplacer l'espace de noms du protocole ActiveSync |
| [Namespace](./namespace) | Pages de codes ActiveSync |
| [Notes](./notes) | Espace de noms Notes du protocole ActiveSync |
| [OofState](./oofstate) | Spécifie la disponibilité de la propriété Oof. |
| [Ping](./ping) | Espace de noms Ping du protocole ActiveSync |
| [Provision](./provision) | Provisionner l'espace de noms du protocole ActiveSync |
| [ProvisionPolicyStatuses](./provisionpolicystatuses) | La valeur indique la réussite ou l'échec du client à appliquer les paramètres de stratégie récupérés à partir du serveur. |
| [ProvisionRemoteWipeStatuses](./provisionremotewipestatuses) | La valeur indique le succès ou l'échec d'une opération d'effacement à distance sur le client. |
| [RecipientType](./recipienttype) | Indique le type de destinataire. |
| [ResolveRecipients](./resolverecipients) | Espace de noms ResolveRecipients du protocole ActiveSync |
| [RightsManagement](./rightsmanagement) | Espace de noms RightsManagement du protocole ActiveSync |
| [Search](./search) | Espace de noms de recherche du protocole ActiveSync |
| [ServerType](./servertype) | Spécifie le type de serveur |
| [Settings](./settings) | Espace de noms des paramètres du protocole ActiveSync |
| [SignedSMIMEAlgorithm](./signedsmimealgorithm) | Spécifie l'algorithme utilisé lors de la signature des messages S/MIME. |
| [SMIMEEncryptionAlgorithmNegotiation](./smimeencryptionalgorithmnegotiation) | Contrôle la négociation de l'algorithme de chiffrement. |
| [StoreType](./storetype) | Contient des informations qui spécifient l'emplacement, pour les opérations. |
| [Tasks](./tasks) | Espace de noms des tâches du protocole ActiveSync |
| [UserCreatedFolderTypes](./usercreatedfoldertypes) | Spécifie le type de dossier à créer. |
| [UserResponse](./userresponse) | Indique si la réunion est acceptée, provisoirement acceptée ou refusée. |
| [ValidateCert](./validatecert) | Espace de noms ValidateCert du protocole ActiveSync |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
