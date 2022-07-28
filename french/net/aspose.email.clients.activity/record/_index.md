---
title: Record
second_title: Référence de l'API Aspose.Email pour .NET
description: Enregistrement du journal daudit
type: docs
weight: 2720
url: /fr/net/aspose.email.clients.activity/record/
---
## Record class

Enregistrement du journal d'audit

```csharp
public class Record
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Record](record)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [AzureActiveDirectoryEventType](../../aspose.email.clients.activity/record/azureactivedirectoryeventtype) { get; set; } | Obtient ou définit le type d'événement Azure AD. Obligatoire : Oui |
| [Client](../../aspose.email.clients.activity/record/client) { get; set; } | Obtient ou définit des détails sur l'appareil client, le système d'exploitation de l'appareil et le navigateur de l'appareil qui ont été utilisés pour l'événement de connexion au compte. Obligatoire : Non |
| [ClientIP](../../aspose.email.clients.activity/record/clientip) { get; set; } | Obtient ou définit l'adresse IP de l'appareil utilisé lors de la journalisation de l'activité. L'adresse IP est affichée au format d'adresse IPv4 ou IPv6. Obligatoire : Oui |
| [CreationTime](../../aspose.email.clients.activity/record/creationtime) { get; set; } | Obtient ou définit la date et l'heure en temps universel coordonné (UTC) lorsque l'utilisateur a effectué l'activité. Obligatoire : Oui |
| [ExtendedProperties](../../aspose.email.clients.activity/record/extendedproperties) { get; set; } | Obtient ou définit la liste des propriétés étendues pour le paramètre en cours de modification. Chaque propriété aura un nom et une valeur. Obligatoire : Non |
| [Id](../../aspose.email.clients.activity/record/id) { get; set; } | Obtient ou définit l'identifiant unique d'un enregistrement d'audit. Obligatoire : Oui |
| [LoginStatus](../../aspose.email.clients.activity/record/loginstatus) { get; set; } | Obtient ou définit l'état de connexion Obligatoire : Oui |
| [ObjectId](../../aspose.email.clients.activity/record/objectid) { get; set; } | Obtient ou définit l'identifiant de l'objet. Pour l'activité SharePoint et OneDrive Entreprise, le chemin d'accès complet du fichier ou du dossier auquel l'utilisateur accède. Pour la journalisation d'audit de l'administrateur Exchange, le nom de l'objet qui a été modifié par l'applet de commande. Obligatoire : Non |
| [Operation](../../aspose.email.clients.activity/record/operation) { get; set; } | Obtient ou définit le nom de l'activité de l'utilisateur ou de l'administrateur. Pour une description des opérations/activités les plus courantes, voir Rechercher dans le journal d'audit dans le Centre de protection Office 365. Pour l'activité d'administration Exchange, cette propriété identifie le nom de la cmdlet qui a été exécutée. Pour les événements DLP, cela peut être "DlpRuleMatch", "DlpRuleUndo" ou "DlpInfo", qui sont décrits sous "Schéma DLP" ci-dessous. Obligatoire : Oui |
| [OrganizationId](../../aspose.email.clients.activity/record/organizationid) { get; set; } | Obtient ou définit le GUID du locataire Office 365 de votre organisation. Cette valeur sera toujours la même pour votre organisation, quel que soit le service Office 365 dans lequel elle se produit. Obligatoire : Oui |
| [RecordType](../../aspose.email.clients.activity/record/recordtype) { get; set; } | Obtient ou définit le type d'opération indiqué par l'enregistrement. Obligatoire : Oui |
| [ResultStatus](../../aspose.email.clients.activity/record/resultstatus) { get; set; } | Obtient ou définit la valeur qui indique si l'action (spécifiée dans la propriété Operation) a réussi ou non. Obligatoire : Non |
| [UserDomain](../../aspose.email.clients.activity/record/userdomain) { get; set; } | Obtient ou définit les informations d'identité du locataire (TII). Obligatoire : Oui |
| [UserId](../../aspose.email.clients.activity/record/userid) { get; set; } | Obtient ou définit l'UPN (User Principal Name) de l'utilisateur qui a effectué l'action (spécifiée dans la propriété Operation) qui a entraîné la journalisation de l'enregistrement ; par exemple, my_name@my_domain_name. Notez que les enregistrements des activités effectuées par les comptes système (tels que SHAREPOINT\system ou NT AUTHORITY\SYSTEM) sont également inclus. Obligatoire : Oui |
| [UserKey](../../aspose.email.clients.activity/record/userkey) { get; set; } | Obtient ou définit un ID alternatif pour l'utilisateur identifié dans la propriété UserId. Par exemple, cette propriété est renseignée avec l'ID unique de passeport (PUID) pour les événements effectués par les utilisateurs dans SharePoint, OneDrive Entreprise et Exchange. Cette propriété peut également spécifier la même valeur que la propriété UserID pour les événements se produisant dans d'autres services et les événements exécutés par des comptes système. Obligatoire : Oui |
| [UserType](../../aspose.email.clients.activity/record/usertype) { get; set; } | Obtient ou définit le type d'utilisateur qui a effectué l'opération. Obligatoire : Oui |
| [Workload](../../aspose.email.clients.activity/record/workload) { get; set; } | Obtient ou définit le service Office 365 où l'activité s'est produite. Obligatoire : Non |

### Voir également

* espace de noms [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
