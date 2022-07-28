---
title: O365URLTimeOfClickActivity
second_title: Référence de l'API Aspose.Email pour .NET
description: Étend le schéma commun avec les propriétés spécifiques aux données Office 365 Advanced Threat Protection et Threat Intelligence. Les événements Office 365 Advanced Threat Protection ATP et Threat Intelligence sont disponibles pour les clients Office 365 qui ont un abonnement ATP Threat Intelligence ou E5 . Chaque événement du flux ATP et Threat Intelligence correspond aux URL sur lesquelles un utilisateur de lorganisation a cliqué et qui ont été détectées comme malveillantes au moment du clic en fonction de la protection Office 365 ATP Safe Links.
type: docs
weight: 2670
url: /fr/net/aspose.email.clients.activity/o365urltimeofclickactivity/
---
## O365URLTimeOfClickActivity class

Étend le schéma commun avec les propriétés spécifiques aux données Office 365 Advanced Threat Protection et Threat Intelligence. Les événements Office 365 Advanced Threat Protection (ATP) et Threat Intelligence sont disponibles pour les clients Office 365 qui ont un abonnement ATP, Threat Intelligence ou E5 . Chaque événement du flux ATP et Threat Intelligence correspond aux URL sur lesquelles un utilisateur de l'organisation a cliqué et qui ont été détectées comme malveillantes au moment du clic en fonction de la protection Office 365 ATP Safe Links.

```csharp
public class O365URLTimeOfClickActivity : Content
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [O365URLTimeOfClickActivity](o365urltimeofclickactivity)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [AppName](../../aspose.email.clients.activity/o365urltimeofclickactivity/appname) { get; set; } | Service Office 365 à partir duquel l'URL a été cliqué (par exemple Mail). Obligatoire : Oui |
| [Blocked](../../aspose.email.clients.activity/o365urltimeofclickactivity/blocked) { get; set; } | Ceci est vrai si le clic sur l'URL est bloqué par la protection Office 365 ATP Safe Links. Obligatoire : Oui |
| [ClickedThrough](../../aspose.email.clients.activity/o365urltimeofclickactivity/clickedthrough) { get; set; } | Ceci est vrai si l'utilisateur clique sur le bloc d'URL (écrasé) en fonction des politiques de l'organisation pour la protection Office 365 ATP Safe Links. Obligatoire : Oui |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | L'adresse IP de l'appareil qui a été utilisée lors de la journalisation de l'activité. L'adresse IP est affichée au format d'adresse IPv4 ou IPv6. Obligatoire : Oui |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | La date et l'heure en temps universel coordonné (UTC) auxquelles l'utilisateur a effectué l'activité. Obligatoire : Oui |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | Identifiant unique d'un enregistrement d'audit. Obligatoire : Oui |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | Pour l'activité SharePoint et OneDrive Entreprise, le chemin d'accès complet du fichier ou du dossier auquel l'utilisateur accède. Pour la journalisation d'audit de l'administrateur Exchange, le nom de l'objet qui a été modifié par l'applet de commande. Obligatoire : Non |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | Le nom de l'activité de l'utilisateur ou de l'administrateur. Pour une description des opérations/activités les plus courantes, voir Rechercher dans le journal d'audit dans le Centre de protection Office 365. Pour l'activité d'administration Exchange, cette propriété identifie le nom de la cmdlet qui a été exécutée. Pour les événements DLP, cela peut être "DlpRuleMatch", "DlpRuleUndo" ou "DlpInfo", qui sont décrits sous "Schéma DLP" ci-dessous. Obligatoire : Oui |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | Le GUID du locataire Office 365 de votre organisation. Cette valeur sera toujours la même pour votre organisation, quel que soit le service Office 365 dans lequel elle se produit. Obligatoire : Oui |
| [RecordType](../../aspose.email.clients.activity/content/recordtype) { get; set; } | Le type d'opération indiqué par l'enregistrement. Obligatoire : Oui |
| [ResultStatus](../../aspose.email.clients.activity/content/resultstatus) { get; set; } | Indique si l'action (spécifiée dans la propriété Operation) a réussi ou non. Les valeurs possibles sont Succeeded, PartiallySucceded ou Failed. Pour l'activité d'administration Exchange, la valeur est True ou False. Obligatoire : Non |
| [Scope](../../aspose.email.clients.activity/content/scope) { get; set; } | Cet événement a-t-il été créé par un service O365 hébergé ou un serveur sur site ? Les valeurs possibles sont en ligne et sur site. Notez que SharePoint est la seule charge de travail qui envoie actuellement des événements sur site vers O365. Obligatoire : Non |
| [SourceId](../../aspose.email.clients.activity/o365urltimeofclickactivity/sourceid) { get; set; } | Identifiant du service Office 365 à partir duquel l'URL a été cliqué (par exemple, pour Mail, il s'agit de l'ID de message du réseau Exchange Online). Obligatoire : Oui |
| [TimeOfClick](../../aspose.email.clients.activity/o365urltimeofclickactivity/timeofclick) { get; set; } | La date et l'heure en temps universel coordonné (UTC) auxquelles l'utilisateur a cliqué sur l'URL. Obligatoire : Oui |
| [URL](../../aspose.email.clients.activity/o365urltimeofclickactivity/url) { get; set; } | URL cliquée par l'utilisateur. Obligatoire : Oui |
| [UserId](../../aspose.email.clients.activity/content/userid) { get; set; } | L'UPN (User Principal Name) de l'utilisateur qui a effectué l'action (spécifiée dans la propriété Operation) qui a entraîné la journalisation de l'enregistrement ; par exemple, my_name@my_domain_name. Notez que les enregistrements des activités effectuées par les comptes système (tels que SHAREPOINT\system ou NT AUTHORITY\SYSTEM) sont également inclus. Obligatoire : Oui |
| [UserIp](../../aspose.email.clients.activity/o365urltimeofclickactivity/userip) { get; set; } | L'adresse IP de l'utilisateur qui a cliqué sur l'URL. L'adresse IP est affichée au format d'adresse IPv4 ou IPv6. Obligatoire : Oui |
| [UserKey](../../aspose.email.clients.activity/content/userkey) { get; set; } | Un ID alternatif pour l'utilisateur identifié dans la propriété UserId. Par exemple, cette propriété est renseignée avec l'ID unique de passeport (PUID) pour les événements effectués par les utilisateurs dans SharePoint, OneDrive Entreprise et Exchange. Cette propriété peut également spécifier la même valeur que la propriété UserID pour les événements se produisant dans d'autres services et les événements exécutés par des comptes système. Obligatoire : Oui |
| [UserType](../../aspose.email.clients.activity/content/usertype) { get; set; } | Le type d'utilisateur qui a effectué l'opération. Obligatoire : Oui |
| [Workload](../../aspose.email.clients.activity/content/workload) { get; set; } | Le service Office 365 où l'activité s'est produite dans la chaîne Workload. Les valeurs possibles pour cette propriété sont : Exchange SharePoint OneDrive AzureActiveDirectory SecurityComplianceCenter Sway ThreatIntelligence Obligatoire : Non |

### Voir également

* class [Content](../content)
* espace de noms [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
