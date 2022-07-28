---
title: SharePointAuditOperation
second_title: Référence de l'API Aspose.Email pour .NET
description: Opérations daudit SharePoint
type: docs
weight: 2760
url: /fr/net/aspose.email.clients.activity/sharepointauditoperation/
---
## SharePointAuditOperation enumeration

Opérations d'audit SharePoint

```csharp
public enum SharePointAuditOperation
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| AccessInvitationAccepted | `0` | Cette opération est en aperçu. Le destinataire d'une invitation à afficher ou modifier un fichier (ou dossier) partagé a accédé au fichier partagé en cliquant sur le lien dans l'invitation. |
| AccessInvitationCreated | `1` | Cette opération est en aperçu. L'utilisateur envoie une invitation à une autre personne (à l'intérieur ou à l'extérieur de son organisation) pour afficher ou modifier un fichier ou un dossier partagé sur un site SharePoint ou OneDrive Entreprise. Les détails de l'entrée d'événement identifient le nom du fichier qui a été partagé, l'utilisateur auquel l'invitation a été envoyée, et le type d'autorisation de partage sélectionné par la personne qui a envoyé l'invitation. |
| AccessInvitationExpired | `2` | Cette opération est en aperçu. Une invitation envoyée à un utilisateur externe expire. Par défaut, une invitation envoyée à un utilisateur extérieur à votre organisation expire au bout de 7 jours si l'invitation n'est pas acceptée. |
| AccessInvitationRevoked | `3` | Cette opération est en aperçu. L'administrateur de site ou le propriétaire d'un site ou d'un document dans SharePoint ou OneDrive Entreprise retire une invitation qui a été envoyée à un utilisateur extérieur à votre organisation. Une invitation ne peut être retirée qu'avant d'être acceptée. |
| AccessInvitationUpdated | `4` | Cette opération est en aperçu. L'utilisateur qui a créé et envoyé une invitation à une autre personne pour afficher ou modifier un fichier (ou dossier) partagé sur un site SharePoint ou OneDrive Entreprise renvoie l'invitation. |
| AccessRequestApproved | `5` | L'administrateur du site ou le propriétaire d'un site ou d'un document dans SharePoint ou OneDrive Entreprise approuve une demande d'utilisateur pour accéder au site ou au document. |
| AccessRequestCreated | `6` | L'utilisateur demande l'accès à un site ou un document dans SharePoint ou OneDrive Entreprise auquel il n'est pas autorisé à accéder. |
| AccessRequestRejected | `7` | Cette opération est en aperçu. L'administrateur du site ou le propriétaire d'un site ou d'un document dans SharePoint refuse une demande d'utilisateur pour accéder au site ou au document. |
| ActivationEnabled | `8` | Cette opération est en aperçu. Les utilisateurs peuvent activer le navigateur pour les modèles de formulaire qui ne contiennent pas de code de formulaire, qui nécessitent une confiance totale, activer le rendu sur un appareil mobile ou utiliser une connexion de données gérée par un administrateur de serveur. |
| AdministratorAddedToTermStore | `9` | Cette opération est en aperçu. Administrateur du magasin de termes ajouté. |
| AdministratorDeletedFromTermStore | `10` | Cette opération est en aperçu. Administrateur du magasin de termes supprimé. |
| AllowGroupCreationSet | `11` | Cette opération est en aperçu. L'administrateur ou le propriétaire du site ajoute un niveau d'autorisation à un site SharePoint ou OneDrive Entreprise qui permet à un utilisateur auquel cette autorisation est attribuée de créer un groupe pour ce site. |
| AppCatalogCreated | `12` | Cette opération est en aperçu. Catalogue d'applications créé pour rendre les applications professionnelles personnalisées disponibles pour votre environnement SharePoint. |
| AuditPolicyRemoved | `13` | Cette opération est en aperçu. La politique de cycle de vie des documents a été supprimée pour une collection de sites. |
| AuditPolicyUpdate | `14` | Cette opération est en aperçu. La politique de cycle de vie des documents a été mise à jour pour une collection de sites. |
| AzureStreamingEnabledSet | `15` | Cette opération est en aperçu. Un propriétaire de portail vidéo a autorisé le streaming vidéo à partir d'Azure. |
| CollaborationTypeModified | `16` | Cette opération est en aperçu. Le type de collaboration autorisé sur les sites (par exemple, intranet, extranet ou public) a été modifié. |
| ConnectedSiteSettingModified | `17` | L'utilisateur a créé, modifié ou supprimé le lien entre un projet et un site de projet ou l'utilisateur modifie le paramètre de synchronisation sur le lien dans Project Web App. |
| CreateSSOApplication | `18` | Cette opération est en aperçu. Application cible créée dans le service de magasin sécurisé. |
| CustomFieldOrLookupTableCreated | `19` | L'utilisateur a créé un champ personnalisé ou une table/élément de recherche dans Project Web App. |
| CustomFieldOrLookupTableDeleted | `20` | L'utilisateur a supprimé un champ personnalisé ou une table/élément de recherche dans Project Web App. |
| CustomFieldOrLookupTableModified | `21` | L'utilisateur a modifié un champ personnalisé ou une table/élément de recherche dans Project Web App. |
| CustomizeExemptUsers | `22` | Cette opération est en aperçu. L'administrateur global a personnalisé la liste des agents utilisateurs exemptés dans le centre d'administration SharePoint. Vous pouvez spécifier quels agents utilisateurs exempter de recevoir une page Web entière à indexer. Cela signifie que lorsqu'un agent utilisateur que vous avez spécifié comme exempt rencontre un formulaire InfoPath, le formulaire sera renvoyé sous forme de fichier XML au lieu d'une page Web entière. Cela accélère l'indexation des formulaires InfoPath. |
| DefaultLanguageChangedInTermStore | `23` | Cette opération est en aperçu. Paramètre de langue modifié dans le magasin de terminologie. |
| DelegateModified | `24` | L'utilisateur a créé ou modifié un délégué de sécurité dans Project Web App. |
| DelegateRemoved | `25` | L'utilisateur a supprimé un délégué de sécurité dans Project Web App. |
| DeleteSSOApplication | `26` | Cette opération est en aperçu. Une application SSO a été supprimée. |
| eDiscoveryHoldApplied | `27` | Cette opération est en aperçu. Une conservation inaltérable a été placée sur une source de contenu. Les conservations inaltérables sont gérées à l'aide d'une collection de sites eDiscovery (telle que le centre eDiscovery) dans SharePoint. |
| eDiscoveryHoldRemoved | `28` | Cette opération est en aperçu. Une conservation inaltérable a été supprimée d'une source de contenu. Les conservations inaltérables sont gérées à l'aide d'une collection de sites eDiscovery (telle que le centre eDiscovery) dans SharePoint. |
| eDiscoverySearchPerformed | `29` | Cette opération est en aperçu. Une recherche eDiscovery a été effectuée à l'aide d'une collection de sites eDiscovery dans SharePoint. |
| EngagementAccepted | `30` | L'utilisateur accepte un engagement de ressource dans Project Web App. |
| EngagementModified | `31` | L'utilisateur modifie un engagement de ressource dans Project Web App. |
| EngagementRejected | `32` | L'utilisateur rejette un engagement de ressource dans Project Web App. |
| EnterpriseCalendarModified | `33` | L'utilisateur copie, modifie ou supprime un calendrier d'entreprise dans Project Web App. |
| EntityDeleted | `34` | L'utilisateur supprime une feuille de temps dans Project Web App. |
| EntityForceCheckedIn | `35` | L'utilisateur force l'archivage d'un calendrier, d'un champ personnalisé ou d'une table de choix dans Project Web App. |
| ExemptUserAgentSet | `36` | Cette opération est en aperçu. L'administrateur global ajoute un agent utilisateur à la liste des agents utilisateurs exemptés dans le centre d'administration SharePoint. |
| FileAccessed | `37` | L'utilisateur ou le compte système accède à un fichier sur un site SharePoint ou OneDrive Entreprise. Les comptes système peuvent également générer des événements FileAccessed. |
| FileCheckOutDiscarded | `38` | Cette opération est en aperçu. L'utilisateur supprime (ou annule) un fichier extrait. Cela signifie que toutes les modifications apportées au fichier lors de son extraction sont ignorées et ne sont pas enregistrées dans la version du document dans la bibliothèque de documents. |
| FileCheckedIn | `39` | Cette opération est en aperçu. L'utilisateur archive un document qu'il a extrait d'une bibliothèque de documents SharePoint ou OneDrive Entreprise. |
| FileCheckedOut | `40` | Cette opération est en aperçu. L'utilisateur extrait un document situé dans une bibliothèque de documents SharePoint ou OneDrive Entreprise. Les utilisateurs peuvent extraire et apporter des modifications aux documents qui ont été partagés avec eux. |
| FileCopied | `41` | L'utilisateur copie un document à partir d'un site SharePoint ou OneDrive Entreprise. Le fichier copié peut être enregistré dans un autre dossier sur le site. |
| FileDeleted | `42` | L'utilisateur supprime un document d'un site SharePoint ou OneDrive Entreprise. |
| FileDeletedFirstStageRecycleBin | `43` | L'utilisateur supprime un fichier de la corbeille sur un site SharePoint ou OneDrive Entreprise. |
| FileDeletedSecondStageRecycleBin | `44` | L'utilisateur supprime un fichier de la corbeille secondaire sur un site SharePoint ou OneDrive Entreprise. |
| FileDownloaded | `45` | L'utilisateur télécharge un document à partir d'un site SharePoint ou OneDrive Entreprise. |
| FileFetched | `46` | Cet événement a été remplacé par l'événement FileAccessed et est obsolète. |
| FileModified | `47` | Un compte utilisateur ou système modifie le contenu ou les propriétés d'un document situé sur un site SharePoint ou OneDrive Entreprise. |
| FileMoved | `48` | L'utilisateur déplace un document de son emplacement actuel sur un site SharePoint ou OneDrive Entreprise vers un nouvel emplacement. |
| FilePreviewed | `49` | L'utilisateur prévisualise un document sur un site SharePoint ou OneDrive Entreprise. |
| FileRenamed | `50` | L'utilisateur renomme un document sur un site SharePoint ou OneDrive Entreprise. |
| FileRestored | `51` | L'utilisateur restaure un document à partir de la corbeille d'un site SharePoint ou OneDrive Entreprise. |
| FileSyncDownloadedFull | `52` | L'utilisateur établit une relation de synchronisation et télécharge avec succès des fichiers pour la première fois sur son ordinateur à partir d'une bibliothèque de documents SharePoint ou OneDrive Entreprise. |
| FileSyncDownloadedPartial | `53` | L'utilisateur télécharge avec succès toutes les modifications apportées aux fichiers à partir de la bibliothèque de documents SharePoint ou OneDrive Entreprise. Cet événement indique que toutes les modifications apportées aux fichiers de la bibliothèque de documents ont été téléchargées sur l'ordinateur de l'utilisateur. Seules les modifications ont été téléchargées car la bibliothèque de documents a déjà été téléchargée par l'utilisateur (comme indiqué par l'événement FileSyncDownloadedFull). |
| FileSyncUploadedFull | `54` | Cette opération est en aperçu. L'utilisateur établit une relation de synchronisation et télécharge avec succès des fichiers pour la première fois depuis son ordinateur vers une bibliothèque de documents SharePoint ou OneDrive Entreprise. |
| FileSyncUploadedPartial | `55` | Cette opération est en aperçu. L'utilisateur télécharge avec succès les modifications apportées aux fichiers sur une bibliothèque de documents SharePoint ou OneDrive Entreprise. Cet événement indique que toutes les modifications apportées à la version locale d'un fichier à partir d'une bibliothèque de documents sont téléchargées avec succès vers la bibliothèque de documents. Seules les modifications sont déchargées car ces fichiers ont déjà été téléchargés par l'utilisateur (comme indiqué par l'événement FileSyncUploadedFull). |
| FileUploaded | `56` | L'utilisateur télécharge un document dans un dossier sur un site SharePoint ou OneDrive Entreprise. |
| FileViewed | `57` | Cet événement a été remplacé par l'événement FileAccessed et est obsolète. |
| FolderCopied | `58` | L'utilisateur copie un dossier d'un site SharePoint ou OneDrive Entreprise vers un autre emplacement dans SharePoint ou OneDrive Entreprise. |
| FolderCreated | `59` | L'utilisateur crée un dossier sur un site SharePoint ou OneDrive Entreprise. |
| FolderDeleted | `60` | L'utilisateur supprime un dossier d'un site SharePoint ou OneDrive Entreprise. |
| FolderDeletedFirstStageRecycleBin | `61` | L'utilisateur supprime un dossier de la corbeille sur un site SharePoint ou OneDrive Entreprise . |
| FolderDeletedSecondStageRecycleBin | `62` | L'utilisateur supprime un dossier de la corbeille secondaire sur un site SharePoint ou OneDrive Entreprise. |
| FolderModified | `63` | L'utilisateur modifie un dossier sur un site SharePoint ou OneDrive Entreprise. Cet événement inclut les modifications des métadonnées du dossier, telles que les balises et les propriétés. |
| FolderMoved | `64` | L'utilisateur déplace un dossier d'un site SharePoint ou OneDrive Entreprise. |
| FolderRenamed | `65` | L'utilisateur renomme un dossier sur un site SharePoint ou OneDrive Entreprise. |
| FolderRestored | `66` | L'utilisateur restaure un dossier à partir de la corbeille sur un site SharePoint ou OneDrive Entreprise. |
| GroupAdded | `67` | Cette opération est en aperçu. L'administrateur ou le propriétaire du site crée un groupe pour un site SharePoint ou OneDrive Entreprise, ou effectue une tâche qui aboutit à la création d'un groupe. Par exemple, la première fois qu'un utilisateur crée un lien pour partager un fichier, un groupe système est ajouté au site OneDrive Entreprise de l'utilisateur. Cet événement peut également résulter de la création par un utilisateur d'un lien avec des autorisations de modification vers un fichier partagé. |
| GroupRemoved | `68` | Cette opération est en aperçu. L'utilisateur supprime un groupe d'un site SharePoint ou OneDrive Entreprise. |
| GroupUpdated | `69` | Cette opération est en aperçu. L'administrateur ou le propriétaire du site modifie les paramètres d'un groupe pour un site SharePoint ou OneDrive Entreprise. Cela peut inclure la modification du nom du groupe, qui peut afficher ou modifier l'appartenance au groupe et la manière dont les demandes d'adhésion sont traitées. |
| LanguageAddedToTermStore | `70` | Cette opération est en aperçu. Langue ajoutée au magasin de terminologie. |
| LanguageRemovedFromTermStore | `71` | Cette opération est en aperçu. Langue supprimée du magasin de terminologie. |
| LegacyWorkflowEnabledSet | `72` | Cette opération est en aperçu. L'administrateur ou le propriétaire du site ajoute le type de contenu Tâche de flux de travail SharePoint au site. Les administrateurs généraux peuvent également activer les flux de travail pour l'ensemble de l'organisation dans le centre d'administration SharePoint. |
| LookAndFeelModified | `73` | L'utilisateur modifie un lancement rapide, des formats de diagramme de Gantt ou des formats de groupe. Ou l'utilisateur crée, modifie ou supprime une vue dans Project Web App. |
| ManagedSyncClientAllowed | `74` | L'utilisateur établit avec succès une relation de synchronisation avec un site SharePoint ou OneDrive Entreprise. La relation de synchronisation est réussie car l'ordinateur de l'utilisateur est membre d'un domaine qui a été ajouté à la liste des domaines (appelée la liste des destinataires fiables) qui peuvent accéder aux bibliothèques de documents de votre organisation. Pour plus d'informations sur cette fonctionnalité, voir Utiliser les applets de commande Windows PowerShell pour activer la synchronisation OneDrive pour les domaines figurant sur la liste des destinataires approuvés. |
| MaxQuotaModified | `75` | Cette opération est en aperçu. Le quota maximum pour un site a été modifié. |
| MaxResourceUsageModified | `76` | Cette opération est en aperçu. L'utilisation maximale autorisée des ressources pour un site a été modifiée. |
| MySitePublicEnabledSet | `77` | Cette opération est en aperçu. L'indicateur permettant aux utilisateurs d'avoir des MySites publics a été défini par l'administrateur SharePoint. |
| NewsFeedEnabledSet | `78` | Cette opération est en aperçu. L'administrateur ou le propriétaire du site active les flux RSS pour un site SharePoint ou OneDrive Entreprise. Les administrateurs généraux peuvent activer les flux RSS pour l'ensemble de l'organisation dans le centre d'administration SharePoint. |
| ODBNextUXSettings | `79` | Cette opération est en aperçu. La nouvelle interface utilisateur pour OneDrive Entreprise a été activée. |
| OfficeOnDemandSet | `80` | Cette opération est en aperçu. L'administrateur du site active Office à la demande, qui permet aux utilisateurs d'accéder à la dernière version des applications de bureau Office. Office on Demand est activé dans le centre d'administration SharePoint et nécessite un abonnement Office 365 qui inclut des applications Office complètes et installées. |
| PageViewed | `81` | L'utilisateur affiche une page sur un site SharePoint ou un site OneDrive Entreprise. Cela n'inclut pas l'affichage des fichiers de bibliothèque de documents à partir d'un site SharePoint ou d'un site One Drive for Business sur un navigateur. |
| PeopleResultsScopeSet | `82` | Cette opération est en aperçu. L'administrateur du site crée ou modifie la source des résultats pour les recherches de personnes pour un site SharePoint. |
| PermissionSyncSettingModified | `83` | L'utilisateur modifie les paramètres de synchronisation des autorisations du projet dans Project Web App. |
| PermissionTemplateModified | `84` | L'utilisateur crée, modifie ou supprime un modèle d'autorisations dans Project Web App. |
| PortfolioDataAccessed | `85` | L'utilisateur accède au contenu du portefeuille (bibliothèque de pilotes, priorisation des pilotes, analyses de portefeuille) dans Project Web App. |
| PortfolioDataModified | `86` | L'utilisateur crée, modifie ou supprime des données de portefeuille (bibliothèque de pilotes, priorisation de pilotes, analyses de portefeuille) dans Project Web App. |
| PreviewModeEnabledSet | `87` | Cette opération est en aperçu. L'administrateur du site active l'aperçu du document pour un site SharePoint. |
| ProjectAccessed | `88` | L'utilisateur accède au contenu du projet dans Project Web App. |
| ProjectCheckedIn | `89` | L'utilisateur archive un projet qu'il a extrait d'une Project Web App. |
| ProjectCheckedOut | `90` | L'utilisateur extrait un projet situé dans une Project Web App. Les utilisateurs peuvent extraire et apporter des modifications aux projets qu'ils sont autorisés à ouvrir. |
| ProjectCreated | `91` | L'utilisateur crée un projet dans Project Web App. |
| ProjectDeleted | `92` | L'utilisateur supprime un projet dans Project Web App. |
| ProjectForceCheckedIn | `93` | L'utilisateur force l'archivage d'un projet dans Project Web App. |
| ProjectModified | `94` | L'utilisateur modifie un projet dans Project Web App. |
| ProjectPublished | `95` | L'utilisateur publie un projet dans Project Web App. |
| ProjectWorkflowRestarted | `96` | L'utilisateur redémarre un flux de travail dans Project Web App. |
| PWASettingsAccessed | `97` | L'utilisateur accède aux paramètres de Project Web App via CSOM. |
| PWASettingsModified | `98` | L'utilisateur modifie la configuration d'une Project Web App. |
| QueueJobStateModified | `99` | L'utilisateur annule ou redémarre un travail de file d'attente dans Project Web App. |
| QuotaWarningEnabledModified | `100` | Cette opération est en aperçu. Avertissement de quota de stockage modifié. |
| RenderingEnabled | `101` | Cette opération est en aperçu. Les modèles de formulaires activés pour le navigateur seront rendus par les services de formulaires InfoPath. |
| ReportingAccessed | `102` | L'utilisateur a accédé au point de terminaison de création de rapports dans Project Web App. |
| ReportingSettingModified | `103` | L'utilisateur modifie la configuration des rapports dans Project Web App. |
| ResourceAccessed | `104` | L'utilisateur accède au contenu d'une ressource d'entreprise dans Project Web App. |
| ResourceCheckedIn | `105` | L'utilisateur archive une ressource d'entreprise qu'il a extraite de Project Web App. |
| ResourceCheckedOut | `106` | L'utilisateur extrait une ressource d'entreprise située dans Project Web App. |
| ResourceCreated | `107` | L'utilisateur crée une ressource d'entreprise dans Project Web App. |
| ResourceDeleted | `108` | L'utilisateur supprime une ressource d'entreprise dans Project Web App. |
| ResourceForceCheckedIn | `109` | L'utilisateur force l'archivage d'une ressource d'entreprise dans Project Web App. |
| ResourceModified | `110` | L'utilisateur modifie une ressource d'entreprise dans Project Web App. |
| ResourcePlanCheckedInOrOut | `111` | L'utilisateur archive ou extrait un plan de ressources dans Project Web App. |
| ResourcePlanModified | `112` | L'utilisateur modifie un plan de ressources dans Project Web App. |
| ResourcePlanPublished | `113` | L'utilisateur publie un plan de ressources dans Project Web App. |
| ResourceRedacted | `114` | L'utilisateur masque une ressource d'entreprise en supprimant toutes les informations personnelles dans Project Web App. |
| ResourceWarningEnabledModified | `115` | Cette opération est en aperçu. Avertissement de quota de ressources modifié. |
| SSOGroupCredentialsSet | `116` | Cette opération est en aperçu. Identifiants de groupe définis dans le service de magasin sécurisé. |
| SSOUserCredentialsSet | `117` | Cette opération est en aperçu. Identifiants utilisateur définis dans le service de magasin sécurisé. |
| SearchCenterUrlSet | `118` | Cette opération est en aperçu. URL du centre de recherche définie. |
| SecondaryMySiteOwnerSet | `119` | Cette opération est en aperçu. Un utilisateur a ajouté un propriétaire secondaire à son MySite. |
| SecurityCategoryModified | `120` | L'utilisateur crée, modifie ou supprime une catégorie de sécurité dans Project Web App. |
| SecurityGroupModified | `121` | L'utilisateur crée, modifie ou supprime un groupe de sécurité dans Project Web App. |
| SendToConnectionAdded | `122` | Cette opération est en aperçu. L'administrateur global crée une nouvelle connexion Envoyer vers sur la page de gestion des enregistrements dans le centre d'administration SharePoint. Une connexion Envoyer vers spécifie les paramètres d'un référentiel de documents ou d'un centre d'enregistrements. Lorsque vous créez une connexion Envoyer vers, un organisateur de contenu peut soumettre des documents à l'emplacement spécifié. |
| SendToConnectionRemoved | `123` | Cette opération est en aperçu. L'administrateur général supprime une connexion Envoyer vers sur la page de gestion des enregistrements du centre d'administration SharePoint. |
| SharedLinkCreated | `124` | L'utilisateur crée un lien vers un fichier partagé dans SharePoint ou OneDrive Entreprise. Ce lien peut être envoyé à d'autres personnes pour leur donner accès au fichier. Un utilisateur peut créer deux types de liens : un lien qui permet à un utilisateur d'afficher et de modifier le fichier partagé, ou un lien qui permet à l'utilisateur de simplement afficher le fichier. |
| SharedLinkDisabled | `125` | Cette opération est en aperçu. L'utilisateur désactive (définitivement) un lien qui a été créé pour partager un fichier. |
| SharingInvitationAccepted | `126` | Cette opération est en aperçu. L'utilisateur accepte une invitation à partager un fichier ou un dossier. Cet événement est consigné lorsqu'un utilisateur partage un fichier avec d'autres utilisateurs. |
| SharingRevoked | `127` | Cette opération est en aperçu. L'utilisateur annule le partage d'un fichier ou d'un dossier qui était précédemment partagé avec d'autres utilisateurs. Cet événement est consigné lorsqu'un utilisateur cesse de partager un fichier avec d'autres utilisateurs. |
| SharingSet | `128` | L'utilisateur partage un fichier ou un dossier situé dans SharePoint ou OneDrive Entreprise avec un autre utilisateur au sein de son organisation. |
| SiteAdminChangeRequest | `129` | Cette opération est en aperçu. L'utilisateur demande à être ajouté en tant qu'administrateur de collection de sites pour une collection de sites SharePoint. Les administrateurs de collection de sites disposent d'autorisations de contrôle total pour la collection de sites et tous les sous-sites. |
| SiteCollectionAdminAdded | `130` | Cette opération est en aperçu. L'administrateur ou le propriétaire de la collection de sites ajoute une personne en tant qu'administrateur de collection de sites pour un site SharePoint ou OneDrive Entreprise. Les administrateurs de collection de sites disposent d'autorisations de contrôle total pour la collection de sites et tous les sous-sites. |
| SiteCollectionCreated | `131` | Cette opération est en aperçu. L'administrateur global crée une nouvelle collection de sites dans votre organisation SharePoint. |
| SiteRenamed | `132` | Cette opération est en aperçu. L'administrateur ou le propriétaire du site renomme un site SharePoint ou OneDrive Entreprise |
| StatusReportModified | `133` | L'utilisateur crée, modifie ou supprime un rapport d'état dans Project Web App. |
| SyncGetChanges | `134` | Cette opération est en aperçu. L'utilisateur clique sur Synchroniser dans la barre d'action de SharePoint ou OneDrive Entreprise pour synchroniser toutes les modifications apportées au fichier dans une bibliothèque de documents sur son ordinateur. |
| TaskStatusAccessed | `135` | L'utilisateur accède au statut d'une ou plusieurs tâches dans Project Web App. |
| TaskStatusApproved | `136` | L'utilisateur approuve une mise à jour du statut d'une ou plusieurs tâches dans Project Web App. |
| TaskStatusRejected | `137` | L'utilisateur rejette une mise à jour du statut d'une ou plusieurs tâches dans Project Web App. |
| TaskStatusSaved | `138` | L'utilisateur enregistre une mise à jour de l'état d'une ou plusieurs tâches dans Project Web App. |
| TaskStatusSubmitted | `139` | L'utilisateur soumet une mise à jour d'état d'une ou plusieurs tâches dans Project Web App. |
| TimesheetAccessed | `140` | L'utilisateur accède à une feuille de temps dans Project Web App. |
| TimesheetApproved | `141` | L'utilisateur approuve la feuille de temps dans Project Web App. |
| TimesheetRejected | `142` | L'utilisateur rejette une feuille de temps dans Project Web App. |
| TimesheetSaved | `143` | L'utilisateur enregistre une feuille de temps dans Project Web App. |
| TimesheetSubmitted | `144` | L'utilisateur soumet une feuille de temps d'état dans Project Web App. |
| UnmanagedSyncClientBlocked | `145` | L'utilisateur tente d'établir une relation de synchronisation avec un site SharePoint ou OneDrive Entreprise à partir d'un ordinateur qui n'est pas membre du domaine de votre organisation ou qui est membre d'un domaine qui n'a pas été ajouté à la liste des domaines ( appelée la liste des destinataires approuvés) qui peuvent accéder aux bibliothèques de documents de votre organisation. La relation de synchronisation n'est pas autorisée et l'ordinateur de l'utilisateur ne peut pas synchroniser, télécharger ou télécharger des fichiers sur une bibliothèque de documents. Pour plus d'informations sur cette fonctionnalité, voir Utiliser les applets de commande Windows PowerShell pour activer la synchronisation OneDrive pour les domaines figurant sur la liste des destinataires approuvés. |
| UpdateSSOApplication | `146` | Cette opération est en aperçu. Application cible mise à jour dans le service de magasin sécurisé. |
| UserAddedToGroup | `147` | Cette opération est en aperçu. L'administrateur ou le propriétaire du site ajoute une personne à un groupe sur un site SharePoint ou OneDrive Entreprise. L'ajout d'une personne à un groupe accorde à l'utilisateur les autorisations qui ont été attribuées au groupe. |
| UserRemovedFromGroup | `148` | Cette opération est en aperçu. L'administrateur ou le propriétaire du site supprime une personne d'un groupe sur un site SharePoint ou OneDrive Entreprise. Une fois la personne supprimée, elle ne bénéficie plus des autorisations attribuées au groupe. |
| WorkflowModified | `149` | L'utilisateur crée, modifie ou supprime un type de projet d'entreprise ou des phases ou étapes de flux de travail dans Project Web App. |

### Voir également

* espace de noms [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
