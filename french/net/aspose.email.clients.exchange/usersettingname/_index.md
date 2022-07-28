---
title: UserSettingName
second_title: Référence de l'API Aspose.Email pour .NET
description: Paramètres utilisateur pouvant être demandés à laide de GetUserSettings.
type: docs
weight: 3600
url: /fr/net/aspose.email.clients.exchange/usersettingname/
---
## UserSettingName enumeration

Paramètres utilisateur pouvant être demandés à l'aide de GetUserSettings.

```csharp
public enum UserSettingName
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| UserDisplayName | `0` | Le nom d'affichage de l'utilisateur. |
| UserDN | `1` | L'ancien nom distinctif de l'utilisateur. |
| UserDeploymentId | `2` | L'ID de déploiement de l'utilisateur. |
| InternalMailboxServer | `3` | Le nom de domaine complet du serveur de boîtes aux lettres. |
| InternalRpcClientServer | `4` | Le nom de domaine complet du serveur client RPC. |
| InternalMailboxServerDN | `5` | Le nom distinctif hérité du serveur de boîtes aux lettres. |
| InternalEcpUrl | `6` | L'URL interne du panneau de configuration Exchange. |
| InternalEcpVoicemailUrl | `7` | L'URL interne du panneau de configuration Exchange pour la personnalisation de la messagerie vocale. |
| InternalEcpEmailSubscriptionsUrl | `8` | L'URL interne du panneau de configuration Exchange pour les abonnements par e-mail. |
| InternalEcpTextMessagingUrl | `9` | L'URL interne du panneau de configuration Exchange pour la messagerie texte. |
| InternalEcpDeliveryReportUrl | `10` | L'URL interne du panneau de configuration Exchange pour les rapports de livraison. |
| InternalEcpRetentionPolicyTagsUrl | `11` | L'URL interne du panneau de configuration Exchange pour les balises RetentionPolicy. |
| InternalEcpPublishingUrl | `12` | L'URL interne du panneau de configuration Exchange pour la publication. |
| InternalEcpPhotoUrl | `13` | L'URL interne du panneau de configuration Exchange pour les photos. |
| InternalEcpConnectUrl | `14` | L'URL interne du panneau de configuration Exchange pour les abonnements People Connect. |
| InternalEcpTeamMailboxUrl | `15` | L'URL interne du panneau de configuration Exchange pour la boîte aux lettres d'équipe. |
| InternalEcpTeamMailboxCreatingUrl | `16` | L'URL interne du panneau de configuration Exchange pour la création de la boîte aux lettres d'équipe. |
| InternalEcpTeamMailboxEditingUrl | `17` | L'URL interne du panneau de configuration Exchange pour modifier la boîte aux lettres d'équipe. |
| InternalEcpTeamMailboxHidingUrl | `18` | L'URL interne du panneau de configuration Exchange pour masquer la boîte aux lettres d'équipe. |
| InternalEcpExtensionInstallationUrl | `19` | L'URL interne du panneau de configuration Exchange pour l'installation de l'extension. |
| InternalEwsUrl | `20` | L'URL interne des services Web Exchange. |
| InternalEmwsUrl | `21` | L'URL interne des services Web de gestion Exchange. |
| InternalOABUrl | `22` | L'URL interne du carnet d'adresses hors ligne. |
| InternalPhotosUrl | `23` | L'URL interne du service Photos. |
| InternalUMUrl | `24` | L'URL interne des services de messagerie unifiée. |
| InternalWebClientUrls | `25` | Les URL internes du client Web Exchange. |
| MailboxDN | `26` | Le nom distinctif de la base de données de boîtes aux lettres de la boîte aux lettres de l'utilisateur. |
| PublicFolderServer | `27` | Le nom du serveur de dossiers publics. |
| ActiveDirectoryServer | `28` | Le nom du serveur Active Directory. |
| ExternalMailboxServer | `29` | Le nom du serveur RPC sur HTTP. |
| ExternalMailboxServerRequiresSSL | `30` | Indique si le serveur RPC sur HTTP nécessite SSL. |
| ExternalMailboxServerAuthenticationMethods | `31` | Les méthodes d'authentification prises en charge par le serveur RPC sur HTTP. |
| EcpVoicemailUrlFragment | `32` | Le fragment d'URL du panneau de configuration Exchange pour la personnalisation de la messagerie vocale. |
| EcpEmailSubscriptionsUrlFragment | `33` | Le fragment d'URL du panneau de configuration Exchange pour les abonnements par e-mail. |
| EcpTextMessagingUrlFragment | `34` | Le fragment d'URL du panneau de configuration Exchange pour la messagerie texte. |
| EcpDeliveryReportUrlFragment | `35` | Le fragment d'URL du panneau de configuration Exchange pour les rapports de livraison. |
| EcpRetentionPolicyTagsUrlFragment | `36` | Le fragment d'URL du panneau de configuration Exchange pour les balises RetentionPolicy. |
| EcpPublishingUrlFragment | `37` | Le fragment d'URL du panneau de configuration Exchange pour la publication. |
| EcpPhotoUrlFragment | `38` | Le fragment d'URL du panneau de configuration Exchange pour les photos. |
| EcpConnectUrlFragment | `39` | Le fragment d'URL du panneau de configuration Exchange pour People Connect. |
| EcpTeamMailboxUrlFragment | `40` | Le fragment d'URL du panneau de configuration Exchange pour la boîte aux lettres d'équipe. |
| EcpTeamMailboxCreatingUrlFragment | `41` | Le fragment d'URL du panneau de configuration Exchange pour la création de la boîte aux lettres d'équipe. |
| EcpTeamMailboxEditingUrlFragment | `42` | Le fragment d'URL du panneau de configuration Exchange pour la modification de la boîte aux lettres d'équipe. |
| EcpExtensionInstallationUrlFragment | `43` | Le fragment d'URL du panneau de configuration Exchange pour l'installation de l'extension. |
| ExternalEcpUrl | `44` | L'URL externe du panneau de configuration Exchange. |
| ExternalEcpVoicemailUrl | `45` | L'URL externe du panneau de configuration Exchange pour la personnalisation de la messagerie vocale. |
| ExternalEcpEmailSubscriptionsUrl | `46` | L'URL externe du panneau de configuration Exchange pour les abonnements par e-mail. |
| ExternalEcpTextMessagingUrl | `47` | L'URL externe du panneau de configuration Exchange pour la messagerie texte. |
| ExternalEcpDeliveryReportUrl | `48` | L'URL externe du panneau de configuration Exchange pour les rapports de livraison. |
| ExternalEcpRetentionPolicyTagsUrl | `49` | L'URL externe du panneau de configuration Exchange pour les balises RetentionPolicy. |
| ExternalEcpPublishingUrl | `50` | L'URL externe du panneau de configuration Exchange pour la publication. |
| ExternalEcpPhotoUrl | `51` | L'URL externe du panneau de configuration Exchange pour les photos. |
| ExternalEcpConnectUrl | `52` | L'URL externe du panneau de configuration Exchange pour les abonnements People Connect. |
| ExternalEcpTeamMailboxUrl | `53` | L'URL externe du panneau de configuration Exchange pour la boîte aux lettres d'équipe. |
| ExternalEcpTeamMailboxCreatingUrl | `54` | L'URL externe du panneau de configuration Exchange pour créer une boîte aux lettres d'équipe. |
| ExternalEcpTeamMailboxEditingUrl | `55` | L'URL externe du panneau de configuration Exchange pour modifier la boîte aux lettres d'équipe. |
| ExternalEcpTeamMailboxHidingUrl | `56` | L'URL externe du panneau de configuration Exchange pour masquer la boîte aux lettres d'équipe. |
| ExternalEcpExtensionInstallationUrl | `57` | L'URL externe du panneau de configuration Exchange pour l'installation de l'extension. |
| ExternalEwsUrl | `58` | L'URL externe des services Web Exchange. |
| ExternalEmwsUrl | `59` | L'URL externe des services Web de gestion Exchange. |
| ExternalOABUrl | `60` | L'URL externe du carnet d'adresses hors ligne. |
| ExternalPhotosUrl | `61` | L'URL externe du service Photos. |
| ExternalUMUrl | `62` | L'URL externe des services de messagerie unifiée. |
| ExternalWebClientUrls | `63` | Les URL externes du client Web Exchange. |
| CrossOrganizationSharingEnabled | `64` | Indique que le partage entre organisations est activé. |
| AlternateMailboxes | `65` | Collection de boîtes aux lettres alternatives. |
| CasVersion | `66` | La version du serveur d'accès au client servant la demande (par exemple, 14.XX.YYY.ZZZ) |
| EwsSupportedSchemas | `67` | Liste séparée par des virgules des versions de schéma prises en charge par les services Web Exchange. La version de schéma values sera la même que les valeurs de l'énumération ExchangeServerVersion. |
| InternalPop3Connections | `68` | La liste des paramètres de connexion interne pour le protocole pop |
| ExternalPop3Connections | `69` | La liste des paramètres de connexion externe pour le protocole pop |
| InternalImap4Connections | `70` | La liste des paramètres de connexion interne pour le protocole imap4 |
| ExternalImap4Connections | `71` | La liste des paramètres de connexion externe pour le protocole imap4 |
| InternalSmtpConnections | `72` | La liste des paramètres de connexion interne pour le protocole smtp |
| ExternalSmtpConnections | `73` | La liste des paramètres de connexion externe pour le protocole smtp |
| InternalServerExclusiveConnect | `74` | S'il est défini sur "Désactivé", les clients ne doivent pas se connecter via ce protocole. Le contenu du protocole est à titre informatif uniquement. |
| ExternalEwsVersion | `75` | La version du serveur de services Web Exchange ExternalEwsUrl pointe vers. |
| MobileMailboxPolicy | `76` | Paramètres de stratégie de boîte aux lettres mobile. |
| DocumentSharingLocations | `77` | Emplacements de partage de documents et leurs paramètres. |
| UserMSOnline | `78` | Si le compte d'utilisateur est un compte MSOnline. |
| InternalMailboxServerAuthenticationMethods | `79` | Les méthodes d'authentification prises en charge par le serveur client RPC. |
| MailboxVersion | `80` | Version du serveur hébergeant la boîte aux lettres de l'utilisateur. |
| SPMySiteHostURL | `81` | URL de l'hôte Sharepoint MySite. |
| SiteMailboxCreationURL | `82` | URL de création de boîte aux lettres de site dans SharePoint. Elle est utilisée par Outlook pour créer directement une boîte aux lettres de site à partir de SharePoint. |
| InternalRpcHttpServer | `83` | Le nom de domaine complet du serveur utilisé pour la connectivité RPC/HTTP interne. |
| InternalRpcHttpConnectivityRequiresSsl | `84` | Indique si SSL est requis pour la connectivité RPC/HTTP interne. |
| InternalRpcHttpAuthenticationMethod | `85` | La méthode d'authentification utilisée pour la connectivité RPC/HTTP interne. |
| ExternalServerExclusiveConnect | `86` | Si défini sur "On", les clients ne doivent se connecter que via ce protocole. |
| ExchangeRpcUrl | `87` | Si défini, les clients peuvent appeler le serveur via XTC |
| ShowGalAsDefaultView | `88` | Si défini sur false, les clients ne doivent pas afficher le GAL par défaut, mais afficher la liste de contacts. |
| AutoDiscoverSMTPAddress | `89` | Adresse SMTP principale de découverte automatique pour l'utilisateur. |
| InteropExternalEwsUrl | `90` | L'URL externe "interop" des services Web Exchange. Par interop, cela signifie une URL vers le serveur E14 (ou version ultérieure) qui peut servir des boîtes aux lettres hébergées sur un serveur de niveau inférieur (E2K3 et versions antérieures). |
| InteropExternalEwsVersion | `91` | Version du serveur vers lequel pointe InteropExternalEwsUrl. |
| PublicFolderInformation | `92` | Informations sur le dossier public (hiérarchie) |
| RedirectUrl | `93` | La version appropriée de l'URL du service de découverte automatique qui doit répondre à cette requête. |
| EwsPartnerUrl | `94` | L'URL des services Web Exchange pour les partenaires Office365. |
| CertPrincipalName | `95` | nom du certificat SSL |
| GroupingInformation | `96` | L'indice de regroupement pour certains clients. |
| InternalOutlookServiceUrl | `98` | URL interne du service Outlook |
| ExternalOutlookServiceUrl | `99` | URL externe du service Outlook |

### Remarques

Ajoutez de nouvelles valeurs à la fin et restez synchronisé avec Microsoft.Exchange.Autodiscover.ConfigurationSettings.UserConfigurationSettingName.

### Voir également

* espace de noms [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
