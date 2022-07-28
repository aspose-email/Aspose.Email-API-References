---
title: O365EmailMessageActivity
second_title: Référence de l'API Aspose.Email pour .NET
description: Étend le schéma commun avec les propriétés spécifiques aux données Office 365 Advanced Threat Protection et Threat Intelligence. Les événements Office 365 Advanced Threat Protection ATP et Threat Intelligence sont disponibles pour les clients Office 365 qui ont un abonnement ATP Threat Intelligence ou E5 . Chaque événement du flux ATP et Threat Intelligence correspond à Un e-mail envoyé ou reçu par un utilisateur de lorganisation avec des détections effectuées sur les messages au moment de la livraison et à partir de la purge automatique de lheure zéro.
type: docs
weight: 2660
url: /fr/net/aspose.email.clients.activity/o365emailmessageactivity/
---
## O365EmailMessageActivity class

Étend le schéma commun avec les propriétés spécifiques aux données Office 365 Advanced Threat Protection et Threat Intelligence. Les événements Office 365 Advanced Threat Protection (ATP) et Threat Intelligence sont disponibles pour les clients Office 365 qui ont un abonnement ATP, Threat Intelligence ou E5 . Chaque événement du flux ATP et Threat Intelligence correspond à Un e-mail envoyé ou reçu par un utilisateur de l'organisation avec des détections effectuées sur les messages au moment de la livraison et à partir de la purge automatique de l'heure zéro.

```csharp
public class O365EmailMessageActivity : Content
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [O365EmailMessageActivity](o365emailmessageactivity)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [AttachmentData](../../aspose.email.clients.activity/o365emailmessageactivity/attachmentdata) { get; set; } | Données sur les pièces jointes dans l'e-mail qui a déclenché l'événement. Obligatoire : Non |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | L'adresse IP de l'appareil qui a été utilisée lors de la journalisation de l'activité. L'adresse IP est affichée au format d'adresse IPv4 ou IPv6. Obligatoire : Oui |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | La date et l'heure en temps universel coordonné (UTC) auxquelles l'utilisateur a effectué l'activité. Obligatoire : Oui |
| [DetectionMethod](../../aspose.email.clients.activity/o365emailmessageactivity/detectionmethod) { get; set; } | La méthode ou la technologie utilisée par Office 365 ATP pour la détection. Obligatoire : Oui |
| [DetectionType](../../aspose.email.clients.activity/o365emailmessageactivity/detectiontype) { get; set; } | Le type de détection. Obligatoire : Oui |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | Identifiant unique d'un enregistrement d'audit. Obligatoire : Oui |
| [InternetMessageId](../../aspose.email.clients.activity/o365emailmessageactivity/internetmessageid) { get; set; } | L'ID de message Internet. Obligatoire : Oui |
| [NetworkMessageId](../../aspose.email.clients.activity/o365emailmessageactivity/networkmessageid) { get; set; } | L'identifiant de message du réseau Exchange Online. Obligatoire : Oui |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | Pour l'activité SharePoint et OneDrive Entreprise, le chemin d'accès complet du fichier ou du dossier auquel l'utilisateur accède. Pour la journalisation d'audit de l'administrateur Exchange, le nom de l'objet qui a été modifié par l'applet de commande. Obligatoire : Non |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | Le nom de l'activité de l'utilisateur ou de l'administrateur. Pour une description des opérations/activités les plus courantes, voir Rechercher dans le journal d'audit dans le Centre de protection Office 365. Pour l'activité d'administration Exchange, cette propriété identifie le nom de la cmdlet qui a été exécutée. Pour les événements DLP, cela peut être "DlpRuleMatch", "DlpRuleUndo" ou "DlpInfo", qui sont décrits sous "Schéma DLP" ci-dessous. Obligatoire : Oui |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | Le GUID du locataire Office 365 de votre organisation. Cette valeur sera toujours la même pour votre organisation, quel que soit le service Office 365 dans lequel elle se produit. Obligatoire : Oui |
| [P1Sender](../../aspose.email.clients.activity/o365emailmessageactivity/p1sender) { get; set; } | Le chemin de retour de l'expéditeur du message électronique. Obligatoire : Oui |
| [P2Sender](../../aspose.email.clients.activity/o365emailmessageactivity/p2sender) { get; set; } | L'expéditeur de l'e-mail. Obligatoire : Oui |
| [Recipients](../../aspose.email.clients.activity/o365emailmessageactivity/recipients) { get; set; } | Un tableau des destinataires du message électronique. Obligatoire : Oui |
| [RecordType](../../aspose.email.clients.activity/content/recordtype) { get; set; } | Le type d'opération indiqué par l'enregistrement. Obligatoire : Oui |
| [ResultStatus](../../aspose.email.clients.activity/content/resultstatus) { get; set; } | Indique si l'action (spécifiée dans la propriété Operation) a réussi ou non. Les valeurs possibles sont Succeeded, PartiallySucceded ou Failed. Pour l'activité d'administration Exchange, la valeur est True ou False. Obligatoire : Non |
| [Scope](../../aspose.email.clients.activity/content/scope) { get; set; } | Cet événement a-t-il été créé par un service O365 hébergé ou un serveur sur site ? Les valeurs possibles sont en ligne et sur site. Notez que SharePoint est la seule charge de travail qui envoie actuellement des événements sur site vers O365. Obligatoire : Non |
| [SenderIp](../../aspose.email.clients.activity/o365emailmessageactivity/senderip) { get; set; } | L'adresse IP qui a soumis l'e-mail d'Office 365. L'adresse IP est affichée au format d'adresse IPv4 ou IPv6. Obligatoire : Oui |
| [Subject](../../aspose.email.clients.activity/o365emailmessageactivity/subject) { get; set; } | La ligne d'objet du message. Obligatoire : Oui |
| [UserId](../../aspose.email.clients.activity/content/userid) { get; set; } | L'UPN (User Principal Name) de l'utilisateur qui a effectué l'action (spécifiée dans la propriété Operation) qui a entraîné la journalisation de l'enregistrement ; par exemple, my_name@my_domain_name. Notez que les enregistrements des activités effectuées par les comptes système (tels que SHAREPOINT\system ou NT AUTHORITY\SYSTEM) sont également inclus. Obligatoire : Oui |
| [UserKey](../../aspose.email.clients.activity/content/userkey) { get; set; } | Un ID alternatif pour l'utilisateur identifié dans la propriété UserId. Par exemple, cette propriété est renseignée avec l'ID unique de passeport (PUID) pour les événements effectués par les utilisateurs dans SharePoint, OneDrive Entreprise et Exchange. Cette propriété peut également spécifier la même valeur que la propriété UserID pour les événements se produisant dans d'autres services et les événements exécutés par des comptes système. Obligatoire : Oui |
| [UserType](../../aspose.email.clients.activity/content/usertype) { get; set; } | Le type d'utilisateur qui a effectué l'opération. Obligatoire : Oui |
| [Verdict](../../aspose.email.clients.activity/o365emailmessageactivity/verdict) { get; set; } | Le verdict du message. Obligatoire : Oui |
| [Workload](../../aspose.email.clients.activity/content/workload) { get; set; } | Le service Office 365 où l'activité s'est produite dans la chaîne Workload. Les valeurs possibles pour cette propriété sont : Exchange SharePoint OneDrive AzureActiveDirectory SecurityComplianceCenter Sway ThreatIntelligence Obligatoire : Non |

### Voir également

* class [Content](../content)
* espace de noms [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
