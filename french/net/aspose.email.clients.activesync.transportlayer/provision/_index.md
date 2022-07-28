---
title: Provision
second_title: Référence de l'API Aspose.Email pour .NET
description: Provisionner lespace de noms du protocole ActiveSync
type: docs
weight: 1710
url: /fr/net/aspose.email.clients.activesync.transportlayer/provision/
---
## Provision enumeration

Provisionner l'espace de noms du protocole ActiveSync

```csharp
public enum Provision
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| Provision | `5` | Les capacités et les autorisations de l'appareil. |
| Policies | `6` | Une collection de politiques de sécurité. |
| Policy | `7` | Une politique de sécurité. |
| PolicyType | `8` | Spécifie le format dans lequel les paramètres de stratégie doivent être fournis. |
| PolicyKey | `9` | Utilisé par le serveur pour marquer l'état des paramètres de stratégie sur le client. |
| Data | `10` | Les paramètres d'une politique. |
| Status | `11` | Indique le succès ou l'échec de parties spécifiques d'une commande. |
| RemoteWipe | `12` | Spécifie soit une directive d'effacement à distance du serveur, soit la confirmation d'un client d'une directive d'effacement à distance. |
| EASProvisionDoc | `13` | La collection de paramètres de sécurité pour le provisionnement des appareils. |
| DevicePasswordEnabled | `14` | Indique si un appareil client nécessite un mot de passe. |
| AlphanumericDevicePasswordRequired | `15` | Indique si un appareil client nécessite un mot de passe alphanumérique. |
| RequireStorageCardEncryption | `16` | Indique si l'appareil doit chiffrer le contenu stocké sur la carte de stockage. |
| PasswordRecoveryEnabled | `17` | Indique s'il faut activer l'envoi d'un mot de passe de récupération au serveur à l'aide de la commande Paramètres. |
| AttachmentsEnabled | `19` | Indique si les pièces jointes aux e-mails sont activées. |
| MinDevicePasswordLength | `20` | La longueur minimale du mot de passe de l'appareil que l'utilisateur peut entrer |
| MaxInactivityTimeDeviceLock | `21` | Le nombre de secondes d'inactivité avant que l'appareil ne se verrouille. |
| MaxDevicePasswordFailedAttempts | `22` | Le nombre d'échecs de mot de passe autorisés avant que l'appareil ne soit effacé. |
| MaxAttachmentSize | `23` | La taille maximale des pièces jointes, telle que déterminée par la politique de sécurité. |
| AllowSimpleDevicePassword | `24` | Indique si l'appareil autorise les mots de passe simples. |
| DevicePasswordExpiration | `25` | Indique si le mot de passe expire après le nombre de jours spécifié, tel que déterminé par la politique. |
| DevicePasswordHistory | `26` | Le nombre minimum de mots de passe précédemment utilisés que l'appareil client stocke pour empêcher leur réutilisation. |
| AllowStorageCard | `27` | Indique si l'appareil autorise l'utilisation de la carte de stockage. |
| AllowCamera | `28` | Si l'appareil permet l'utilisation de la caméra intégrée. |
| RequireDeviceEncryption | `29` | Indique si l'appareil utilise le chiffrement. |
| AllowUnsignedApplications | `30` | Indique si l'appareil autorise l'exécution d'applications non signées. |
| AllowUnsignedInstallationPackages | `31` | Indique si l'appareil autorise l'installation de fichiers cabinet non signés (.cab). |
| MinDevicePasswordComplexCharacters | `32` | Le nombre minimum de caractères complexes (chiffres et symboles) contenus dans le mot de passe. |
| AllowWiFi | `33` | Indique si l'appareil autorise l'utilisation de connexions Wi-Fi. |
| AllowTextMessaging | `34` | Indique si l'appareil autorise le service de messages courts (SMS)/la messagerie texte. |
| AllowPOPIMAPEmail | `35` | Indique si l'appareil autorise l'accès aux e-mails POP/IMAP. |
| AllowBluetooth | `36` | Indique si les profils Bluetooth et mains libres sont autorisés sur l'appareil. |
| AllowIrDA | `37` | Indique si l'appareil autorise l'utilisation de connexions IrDA (infrarouge). |
| RequireManualSyncWhenRoaming | `38` | Indique si l'appareil nécessite une synchronisation manuelle lorsqu'il est en itinérance. |
| AllowDesktopSync | `39` | Indique si l'appareil autorise la synchronisation avec Desktop ActiveSync. |
| MaxCalendarAgeFilter | `40` | Le nombre maximum de jours calendaires pouvant être synchronisés. |
| AllowHTMLEmail | `41` | Indique si l'appareil utilise des e-mails au format HTML. |
| MaxEmailAgeFilter | `42` | La limite d'âge des e-mails pour la synchronisation. |
| MaxEmailBodyTruncationSize | `43` | Taille de troncature pour les e-mails au format texte brut. |
| MaxEmailHTMLBodyTruncationSize | `44` | La taille de troncature pour les e-mails au format HTML. |
| RequireSignedSMIMEMessages | `45` | Indique si l'appareil doit envoyer des messages S/MIME signés. |
| RequireEncryptedSMIMEMessages | `46` | Indique si l'appareil doit envoyer des messages chiffrés. |
| RequireSignedSMIMEAlgorithm | `47` | L'algorithme à utiliser lors de la signature d'un message. |
| RequireEncryptionSMIMEAlgorithm | `48` | L'algorithme à utiliser lors du chiffrement d'un message. |
| AllowSMIMEEncryptionAlgorithmNegotiation | `49` | Indique si l'appareil peut négocier l'algorithme de chiffrement à utiliser pour la signature. |
| AllowSMIMESoftCerts | `50` | Indique si l'appareil utilise des certificats logiciels pour signer les messages sortants. |
| AllowBrowser | `51` | Indique si l'appareil autorise l'utilisation d'un navigateur Web. |
| AllowConsumerEmail | `52` | Indique si l'appareil autorise l'utilisation de l'e-mail personnel. |
| AllowRemoteDesktop | `53` | Indique si l'appareil autorise l'utilisation de Remote Desktop. |
| AllowInternetSharing | `54` | Indique si l'appareil autorise l'utilisation du partage Internet. |
| UnapprovedInROMApplicationList | `55` | Une liste d'applications en ROM dont l'exécution n'est pas approuvée. |
| ApplicationName | `56` | Le nom d'une application in-ROM (fichier .exe) dont l'exécution n'est pas approuvée. |
| ApprovedApplicationList | `57` | Une liste des applications en RAM dont l'exécution est approuvée. |
| Hash | `58` | Le hachage SHA-1 d'une application en mémoire dont l'exécution est approuvée. |

### Voir également

* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* Assemblée [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
