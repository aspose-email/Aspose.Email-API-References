---
title: ExchangeMailboxActivity
second_title: Référence de l'API Aspose.Email pour .NET
description: Étend le schéma commun avec les propriétés spécifiques à toutes les données daudit de boîte aux lettres Exchange.
type: docs
weight: 2510
url: /fr/net/aspose.email.clients.activity/exchangemailboxactivity/
---
## ExchangeMailboxActivity class

Étend le schéma commun avec les propriétés spécifiques à toutes les données d'audit de boîte aux lettres Exchange.

```csharp
public class ExchangeMailboxActivity : Content
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ExchangeMailboxActivity](exchangemailboxactivity)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [ClientInfoString](../../aspose.email.clients.activity/exchangemailboxactivity/clientinfostring) { get; set; } | Informations sur le client de messagerie utilisé pour effectuer l'opération, telles que la version du navigateur, la version d'Outlook et les informations sur l'appareil mobile. |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | L'adresse IP de l'appareil qui a été utilisée lors de la journalisation de l'activité. L'adresse IP est affichée au format d'adresse IPv4 ou IPv6. Obligatoire : Oui |
| [ClientIPAddress](../../aspose.email.clients.activity/exchangemailboxactivity/clientipaddress) { get; set; } | L'adresse IP de l'appareil qui a été utilisée lors de l'enregistrement de l'opération. L'adresse IP est affichée au format d'adresse IPv4 ou IPv6. |
| [ClientMachineName](../../aspose.email.clients.activity/exchangemailboxactivity/clientmachinename) { get; set; } | Le nom de la machine qui héberge le client Outlook. |
| [ClientProcessName](../../aspose.email.clients.activity/exchangemailboxactivity/clientprocessname) { get; set; } | Le client de messagerie utilisé pour accéder à la boîte aux lettres. |
| [ClientVersion](../../aspose.email.clients.activity/exchangemailboxactivity/clientversion) { get; set; } | La version du client de messagerie. |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | La date et l'heure en temps universel coordonné (UTC) auxquelles l'utilisateur a effectué l'activité. Obligatoire : Oui |
| [ExternalAccess](../../aspose.email.clients.activity/exchangemailboxactivity/externalaccess) { get; set; } | Ceci est vrai si le domaine de l'utilisateur de connexion est différent du domaine du propriétaire de la boîte aux lettres. |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | Identifiant unique d'un enregistrement d'audit. Obligatoire : Oui |
| [InternalLogonType](../../aspose.email.clients.activity/exchangemailboxactivity/internallogontype) { get; set; } | Réservé à un usage interne. |
| [LogonType](../../aspose.email.clients.activity/exchangemailboxactivity/logontype) { get; set; } | Indique le type d'utilisateur qui a accédé à la boîte aux lettres et effectué l'opération qui a été consignée. |
| [LogonUserDisplayName](../../aspose.email.clients.activity/exchangemailboxactivity/logonuserdisplayname) { get; set; } | Le nom convivial de l'utilisateur qui a effectué l'opération. |
| [LogonUserSid](../../aspose.email.clients.activity/exchangemailboxactivity/logonusersid) { get; set; } | Le SID de l'utilisateur qui a effectué l'opération. |
| [MailboxGuid](../../aspose.email.clients.activity/exchangemailboxactivity/mailboxguid) { get; set; } | Le GUID Exchange de la boîte aux lettres à laquelle on a accédé. |
| [MailboxOwnerMasterAccountSid](../../aspose.email.clients.activity/exchangemailboxactivity/mailboxownermasteraccountsid) { get; set; } | SID du compte principal du propriétaire de la boîte aux lettres. |
| [MailboxOwnerSid](../../aspose.email.clients.activity/exchangemailboxactivity/mailboxownersid) { get; set; } | Le SID du propriétaire de la boîte aux lettres. |
| [MailboxOwnerUPN](../../aspose.email.clients.activity/exchangemailboxactivity/mailboxownerupn) { get; set; } | L'adresse e-mail de la personne propriétaire de la boîte aux lettres à laquelle on a accédé. |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | Pour l'activité SharePoint et OneDrive Entreprise, le chemin d'accès complet du fichier ou du dossier auquel l'utilisateur accède. Pour la journalisation d'audit de l'administrateur Exchange, le nom de l'objet qui a été modifié par l'applet de commande. Obligatoire : Non |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | Le nom de l'activité de l'utilisateur ou de l'administrateur. Pour une description des opérations/activités les plus courantes, voir Rechercher dans le journal d'audit dans le Centre de protection Office 365. Pour l'activité d'administration Exchange, cette propriété identifie le nom de la cmdlet qui a été exécutée. Pour les événements DLP, cela peut être "DlpRuleMatch", "DlpRuleUndo" ou "DlpInfo", qui sont décrits sous "Schéma DLP" ci-dessous. Obligatoire : Oui |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | Le GUID du locataire Office 365 de votre organisation. Cette valeur sera toujours la même pour votre organisation, quel que soit le service Office 365 dans lequel elle se produit. Obligatoire : Oui |
| [OrganizationName](../../aspose.email.clients.activity/exchangemailboxactivity/organizationname) { get; set; } | Le nom du locataire. |
| [OriginatingServer](../../aspose.email.clients.activity/exchangemailboxactivity/originatingserver) { get; set; } | C'est d'où vient l'opération. |
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
