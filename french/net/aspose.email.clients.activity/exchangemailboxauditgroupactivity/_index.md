---
title: ExchangeMailboxAuditGroupActivity
second_title: Référence de l'API Aspose.Email pour .NET
description: 
type: docs
weight: 2530
url: /fr/net/aspose.email.clients.activity/exchangemailboxauditgroupactivity/
---
## ExchangeMailboxAuditGroupActivity class

```csharp
public class ExchangeMailboxAuditGroupActivity : Content
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ExchangeMailboxAuditGroupActivity](exchangemailboxauditgroupactivity)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [AffectedItems](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/affecteditems) { get; set; } | Informations sur chaque élément du groupe. |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | L'adresse IP de l'appareil qui a été utilisée lors de la journalisation de l'activité. L'adresse IP est affichée au format d'adresse IPv4 ou IPv6. Obligatoire : Oui |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | La date et l'heure en temps universel coordonné (UTC) auxquelles l'utilisateur a effectué l'activité. Obligatoire : Oui |
| [CrossMailboxOperations](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/crossmailboxoperations) { get; set; } | Indique si l'opération a impliqué plusieurs boîtes aux lettres. |
| [DestFolder](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/destfolder) { get; set; } | Le dossier de destination, pour des opérations telles que Déplacer. |
| [DestMailboxId](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/destmailboxid) { get; set; } | Défini uniquement si le paramètre CrossMailboxOperations est True. Spécifie le GUID de la boîte aux lettres cible. |
| [DestMailboxOwnerMasterAccountSid](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/destmailboxownermasteraccountsid) { get; set; } | Défini uniquement si le paramètre CrossMailboxOperations est True. Spécifie le SID du compte principal SID du propriétaire de la boîte aux lettres cible. |
| [DestMailboxOwnerSid](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/destmailboxownersid) { get; set; } | Défini uniquement si le paramètre CrossMailboxOperations est True. Spécifie le SID de la boîte aux lettres cible. |
| [DestMailboxOwnerUPN](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/destmailboxownerupn) { get; set; } | Défini uniquement si le paramètre CrossMailboxOperations est True. Spécifie l'UPN du propriétaire de la boîte aux lettres cible. |
| [Folder](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/folder) { get; set; } | Le dossier où se trouve un groupe d'éléments. |
| [Folders](../../aspose.email.clients.activity/exchangemailboxauditgroupactivity/folders) { get; set; } | Informations sur les dossiers source impliqués dans une opération ; par exemple, si des dossiers sont sélectionnés puis supprimés. |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | Identifiant unique d'un enregistrement d'audit. Obligatoire : Oui |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | Pour l'activité SharePoint et OneDrive Entreprise, le chemin d'accès complet du fichier ou du dossier auquel l'utilisateur accède. Pour la journalisation d'audit de l'administrateur Exchange, le nom de l'objet qui a été modifié par l'applet de commande. Obligatoire : Non |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | Le nom de l'activité de l'utilisateur ou de l'administrateur. Pour une description des opérations/activités les plus courantes, voir Rechercher dans le journal d'audit dans le Centre de protection Office 365. Pour l'activité d'administration Exchange, cette propriété identifie le nom de la cmdlet qui a été exécutée. Pour les événements DLP, cela peut être "DlpRuleMatch", "DlpRuleUndo" ou "DlpInfo", qui sont décrits sous "Schéma DLP" ci-dessous. Obligatoire : Oui |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | Le GUID du locataire Office 365 de votre organisation. Cette valeur sera toujours la même pour votre organisation, quel que soit le service Office 365 dans lequel elle se produit. Obligatoire : Oui |
| [RecordType](../../aspose.email.clients.activity/content/recordtype) { get; set; } | Le type d'opération indiqué par l'enregistrement. Obligatoire : Oui |
| [ResultStatus](../../aspose.email.clients.activity/content/resultstatus) { get; set; } | Indique si l'action (spécifiée dans la propriété Operation) a réussi ou non. Les valeurs possibles sont Succeeded, PartiallySucceded ou Failed. Pour l'activité d'administration Exchange, la valeur est True ou False. Obligatoire : Non |
| [Scope](../../aspose.email.clients.activity/content/scope) { get; set; } | Cet événement a-t-il été créé par un service O365 hébergé ou un serveur sur site ? Les valeurs possibles sont en ligne et sur site. Notez que SharePoint est la seule charge de travail qui envoie actuellement des événements sur site vers O365. Obligatoire : Non |
| [UserId](../../aspose.email.clients.activity/content/userid) { get; set; } | L'UPN (User Principal Name) de l'utilisateur qui a effectué l'action (spécifiée dans la propriété Operation) qui a entraîné la journalisation de l'enregistrement ; par exemple, my_name@my_domain_name. Notez que les enregistrements des activités effectuées par les comptes système (tels que SHAREPOINT\system ou NT AUTHORITY\SYSTEM) sont également inclus. Obligatoire : Oui |
| [UserKey](../../aspose.email.clients.activity/content/userkey) { get; set; } | Un ID alternatif pour l'utilisateur identifié dans la propriété UserId. Par exemple, cette propriété est renseignée avec l'ID unique de passeport (PUID) pour les événements effectués par les utilisateurs dans SharePoint, OneDrive Entreprise et Exchange. Cette propriété peut également spécifier la même valeur que la propriété UserID pour les événements se produisant dans d'autres services et les événements exécutés par des comptes système. Obligatoire : Oui |
| [UserType](../../aspose.email.clients.activity/content/usertype) { get; set; } | Le type d'utilisateur qui a effectué l'opération. Obligatoire : Oui |
| [Workload](../../aspose.email.clients.activity/content/workload) { get; set; } | Le service Office 365 où l'activité s'est produite dans la chaîne Workload. Les valeurs possibles pour cette propriété sont : Exchange SharePoint OneDrive AzureActiveDirectory SecurityComplianceCenter Sway ThreatIntelligence Obligatoire : Non |

### Voir également

* class [Content](../content)
* espace de noms [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
