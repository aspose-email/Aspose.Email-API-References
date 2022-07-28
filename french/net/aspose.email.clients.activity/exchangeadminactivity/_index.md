---
title: ExchangeAdminActivity
second_title: Référence de l'API Aspose.Email pour .NET
description: Étend le schéma commun avec les propriétés spécifiques à toutes les données daudit dadministration Exchange.
type: docs
weight: 2480
url: /fr/net/aspose.email.clients.activity/exchangeadminactivity/
---
## ExchangeAdminActivity class

Étend le schéma commun avec les propriétés spécifiques à toutes les données d'audit d'administration Exchange.

```csharp
public class ExchangeAdminActivity : Content
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ExchangeAdminActivity](exchangeadminactivity)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | L'adresse IP de l'appareil qui a été utilisée lors de la journalisation de l'activité. L'adresse IP est affichée au format d'adresse IPv4 ou IPv6. Obligatoire : Oui |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | La date et l'heure en temps universel coordonné (UTC) auxquelles l'utilisateur a effectué l'activité. Obligatoire : Oui |
| [ExternalAccess](../../aspose.email.clients.activity/exchangeadminactivity/externalaccess) { get; set; } | Spécifie si l'applet de commande a été exécutée par un utilisateur de votre organisation, par le personnel du centre de données Microsoft ou un compte de service du centre de données, ou par un administrateur délégué. La valeur False indique que l'applet de commande a été exécutée par une personne de votre organisation. La valeur True indique que l'applet de commande a été exécutée par le personnel du centre de données, un compte de service du centre de données ou un administrateur délégué. |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | Identifiant unique d'un enregistrement d'audit. Obligatoire : Oui |
| [ModifiedObjectResolvedName](../../aspose.email.clients.activity/exchangeadminactivity/modifiedobjectresolvedname) { get; set; } | Il s'agit du nom convivial de l'objet qui a été modifié par l'applet de commande. Ceci est enregistré uniquement si l'applet de commande modifie l'objet. |
| [ModifiedProperties](../../aspose.email.clients.activity/exchangeadminactivity/modifiedproperties) { get; set; } | La propriété est incluse pour les événements d'administration. La propriété inclut le nom de la propriété qui a été modifiée, la nouvelle valeur de la propriété modifiée et la valeur précédente de l'objet modifié. |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | Pour l'activité SharePoint et OneDrive Entreprise, le chemin d'accès complet du fichier ou du dossier auquel l'utilisateur accède. Pour la journalisation d'audit de l'administrateur Exchange, le nom de l'objet qui a été modifié par l'applet de commande. Obligatoire : Non |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | Le nom de l'activité de l'utilisateur ou de l'administrateur. Pour une description des opérations/activités les plus courantes, voir Rechercher dans le journal d'audit dans le Centre de protection Office 365. Pour l'activité d'administration Exchange, cette propriété identifie le nom de la cmdlet qui a été exécutée. Pour les événements DLP, cela peut être "DlpRuleMatch", "DlpRuleUndo" ou "DlpInfo", qui sont décrits sous "Schéma DLP" ci-dessous. Obligatoire : Oui |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | Le GUID du locataire Office 365 de votre organisation. Cette valeur sera toujours la même pour votre organisation, quel que soit le service Office 365 dans lequel elle se produit. Obligatoire : Oui |
| [OrganizationName](../../aspose.email.clients.activity/exchangeadminactivity/organizationname) { get; set; } | Le nom du locataire. |
| [OriginatingServer](../../aspose.email.clients.activity/exchangeadminactivity/originatingserver) { get; set; } | Le nom du serveur à partir duquel l'applet de commande a été exécutée. |
| [Parameters](../../aspose.email.clients.activity/exchangeadminactivity/parameters) { get; set; } | Nom et valeur de tous les paramètres utilisés avec l'applet de commande identifiée dans la propriété Operations. |
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
