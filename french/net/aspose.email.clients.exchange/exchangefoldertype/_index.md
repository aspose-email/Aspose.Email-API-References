---
title: ExchangeFolderType
second_title: Référence de l'API Aspose.Email pour .NET
description: Énumère les types de dossiers distingués. Ces valeurs sont également contenues dans la propriété PidTagContainerClass.
type: docs
weight: 3340
url: /fr/net/aspose.email.clients.exchange/exchangefoldertype/
---
## ExchangeFolderType enumeration

Énumère les types de dossiers distingués. Ces valeurs sont également contenues dans la propriété PidTagContainerClass.

```csharp
public enum ExchangeFolderType
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| Undefined | `0` | Le type de dossier n'est pas défini. La valeur est utilisée avec les dossiers bien connus suivants : Racine - Le dossier de niveau supérieur de la hiérarchie de la banque de messages, qui contient tous les autres objets Dossier de cette banque de messages. Finder - Contient les dossiers de recherche par défaut. FreeBusy Data - Contient les données de disponibilité du propriétaire de la boîte aux lettres. Haut des dossiers personnels - Le dossier supérieur de la hiérarchie des messages interpersonnels, qui contient les dossiers de données utilisateur, y compris la plupart des dossiers spéciaux tels que le dossier Boîte de réception. Vues communes - Contient les données des vues par défaut qui sont standard pour la banque de messages et qui peuvent être utilisées par n'importe quel utilisateur d'un client accédant à la banque de messages. Vues personnelles - Contient les données des vues définies par un utilisateur particulier. Action différée - Contient toute action différée Message d'action (DAM) ou message d'erreur différé (DEM) résultant de l'exécution de règles côté client. |
| Note | `1` | Cette valeur représente le type de dossier de message électronique ("IPF.Note"). La valeur est utilisée avec les dossiers bien connus suivants : Éléments supprimés - L'emplacement par défaut des objets qui ont été supprimés. Boîte d'envoi - Courrier électronique sortant Les objets Message sont placés dans ce dossier lorsque l'objet Message est envoyé. Éléments envoyés - L'emplacement par défaut dans lequel les copies des objets Message de courrier électronique sont placées après avoir été soumis (envoyés). Boîte de réception - L'emplacement par défaut pour les messages entrants ( reçus) des objets de message de courrier électronique. Brouillons - L'emplacement par défaut des objets de message de courrier électronique composé qui ont été enregistrés mais pas envoyés. Courrier indésirable - Emplacement par défaut des objets de message de courrier électronique déterminés comme étant du courrier indésirable par une règle de courrier indésirable. Problèmes de synchronisation - Contient des dossiers contenant des messages indiquant des problèmes particuliers rencontrés lors de la synchronisation entre le client et le serveur. Il s'agit du dossier parent des dossiers Conflits, Échecs locaux et Échecs du serveur. Conflits - Contient des objets Message qui indiquent des conflits de synchronisation entre le client et le serveur. Échecs locaux - Contient des messages qui indiquent des échecs de synchronisation côté client. Échecs du serveur - Contient des messages indiquant des échecs de synchronisation côté serveur. Traitement du courrier suivi - Dossier de recherche contenant des objets marqués. File d'attente du spouleur - Contient des objets de courrier électronique qui ont été envoyés ou reçus. |
| RSSFeeds | `2` | Cette valeur représente le type de dossier de message RSS ("IPF.Note.OutlookHomepage"). La valeur est utilisée avec les dossiers bien connus suivants : Flux RSS - Contient des messages de flux RSS (Really Simple Syndication). |
| Appointment | `3` | Cette valeur représente le type de dossier "rendez-vous" ("IPF.Appointment"). La valeur est utilisée avec les dossiers bien connus suivants : Calendar - Contient des objets de calendrier, tels que des rendez-vous. |
| Contact | `4` | Cette valeur représente le type de dossier "contacts" ("IPF.Contact"). La valeur est utilisée avec les dossiers bien connus suivants : Contacts - Contient des objets Contact. Contacts suggérés - Contient des objets Contact qui sont créés lorsqu'un destinataire n'est pas dans un carnet d'adresses. Recherche de contacts - Dossier de recherche qui affiche une liste de contacts correspondant aux critères de recherche. |
| QuickContacts | `5` | Cette valeur représente le type de dossier pour les contacts favoris ("IPF.Contact.MOC.QuickContacts"). La valeur est utilisée avec les dossiers bien connus suivants : Quick Contacts - Contient des objets Contact pour les contacts favoris et les contacts de messagerie instantanée de l'utilisateur. |
| ImContactsList | `6` | Cette valeur représente le type de dossier pour les contacts de messagerie instantanée ("IPF.Contact.MOC.ImContactList"). La valeur est utilisée avec les dossiers bien connus suivants : IM Contacts List - Contient les objets de la liste de distribution personnelle des contacts favoris et des contacts de messagerie instantanée . |
| DocumentLibraries | `7` | Cette valeur représente le type de dossier "documents" ("IPF.ShortcutFolder"). La valeur est utilisée avec les dossiers bien connus suivants : Bibliothèques de documents - Contient des documents à télécharger vers un emplacement partagé. |
| Journal | `8` | Cette valeur représente le type de dossier "Journal" ("IPF.Journal"). La valeur est utilisée avec les dossiers bien connus suivants : Journal - Contient des objets Journal. |
| StickyNote | `9` | Cette valeur représente le type de dossier 'notes' ("IPF.StickyNote"). La valeur est utilisée avec les dossiers bien connus suivants : Notes - Contient des objets Note. |
| Task | `10` | Cette valeur représente le type de dossier 'Task' ("IPF.Task"). La valeur est utilisée avec les dossiers bien connus suivants : To-Do - Dossier de recherche utilisé pour le suivi des objets Task. Tasks - Contient des objets Task. |
| Imap | `11` | Cette valeur représente le type de dossier 'imap' ("IPF.IMAP"). Utilisé pour migrer du profil IMAP vers Exchange. |
| Unknown | `12` | Le type de dossier est inconnu. |

### Voir également

* espace de noms [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
