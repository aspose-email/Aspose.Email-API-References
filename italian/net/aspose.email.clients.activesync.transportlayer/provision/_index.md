---
title: Provision
second_title: Aspose.Email per riferimento all'API .NET
description: Fornitura dello spazio dei nomi del protocollo ActiveSync
type: docs
weight: 1710
url: /it/net/aspose.email.clients.activesync.transportlayer/provision/
---
## Provision enumeration

Fornitura dello spazio dei nomi del protocollo ActiveSync

```csharp
public enum Provision
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Provision | `5` | Le capacità e le autorizzazioni per il dispositivo. |
| Policies | `6` | Una raccolta di criteri di sicurezza. |
| Policy | `7` | Una politica di sicurezza. |
| PolicyType | `8` | Specifica il formato in cui devono essere fornite le impostazioni dei criteri. |
| PolicyKey | `9` | Utilizzato dal server per contrassegnare lo stato delle impostazioni dei criteri sul client. |
| Data | `10` | Le impostazioni per un criterio. |
| Status | `11` | Indica l'esito positivo o negativo di parti specifiche di un comando. |
| RemoteWipe | `12` | Specifica una direttiva di cancellazione remota dal server o la conferma di un client di una direttiva di cancellazione remota. |
| EASProvisionDoc | `13` | La raccolta delle impostazioni di sicurezza per il provisioning dei dispositivi. |
| DevicePasswordEnabled | `14` | Indica se un dispositivo client richiede una password. |
| AlphanumericDevicePasswordRequired | `15` | Indica se un dispositivo client richiede una password alfanumerica. |
| RequireStorageCardEncryption | `16` | Indica se il dispositivo deve crittografare il contenuto archiviato sulla scheda di memoria. |
| PasswordRecoveryEnabled | `17` | Indica se abilitare l'invio di una password di ripristino al server tramite il comando Impostazioni. |
| AttachmentsEnabled | `19` | Indica se gli allegati e-mail sono abilitati. |
| MinDevicePasswordLength | `20` | La lunghezza minima della password del dispositivo che l'utente può inserire |
| MaxInactivityTimeDeviceLock | `21` | Il numero di secondi di inattività prima che il dispositivo si blocchi. |
| MaxDevicePasswordFailedAttempts | `22` | Il numero di password non riuscite consentite prima che il dispositivo venga cancellato. |
| MaxAttachmentSize | `23` | La dimensione massima dell'allegato, come determinato dalla politica di sicurezza. |
| AllowSimpleDevicePassword | `24` | Se il dispositivo consente password semplici. |
| DevicePasswordExpiration | `25` | Se la password scade dopo il numero di giorni specificato, come determinato dalla politica. |
| DevicePasswordHistory | `26` | Il numero minimo di password utilizzate in precedenza memorizzate dal dispositivo client per impedirne il riutilizzo. |
| AllowStorageCard | `27` | Se il dispositivo consente l'utilizzo della scheda di memoria. |
| AllowCamera | `28` | Se il dispositivo consente l'uso della fotocamera integrata. |
| RequireDeviceEncryption | `29` | Se il dispositivo utilizza la crittografia. |
| AllowUnsignedApplications | `30` | Se il dispositivo consente l'esecuzione di applicazioni non firmate. |
| AllowUnsignedInstallationPackages | `31` | Se il dispositivo consente l'installazione di file cabinet (.cab) non firmati. |
| MinDevicePasswordComplexCharacters | `32` | Il numero minimo di caratteri complessi (numeri e simboli) contenuti nella password. |
| AllowWiFi | `33` | Se il dispositivo consente l'utilizzo di connessioni Wi-Fi. |
| AllowTextMessaging | `34` | Se il dispositivo consente SMS (Short Message Service)/messaggistica di testo. |
| AllowPOPIMAPEmail | `35` | Se il dispositivo consente l'accesso all'e-mail POP/IMAP. |
| AllowBluetooth | `36` | Se i profili Bluetooth e vivavoce sono consentiti sul dispositivo. |
| AllowIrDA | `37` | Se il dispositivo consente l'utilizzo di connessioni IrDA (infrarossi). |
| RequireManualSyncWhenRoaming | `38` | Se il dispositivo richiede la sincronizzazione manuale quando il dispositivo è in roaming. |
| AllowDesktopSync | `39` | Se il dispositivo consente la sincronizzazione con Desktop ActiveSync. |
| MaxCalendarAgeFilter | `40` | Il numero massimo di giorni di calendario che possono essere sincronizzati. |
| AllowHTMLEmail | `41` | Indica se il dispositivo utilizza e-mail in formato HTML. |
| MaxEmailAgeFilter | `42` | Il limite di età delle email per la sincronizzazione. |
| MaxEmailBodyTruncationSize | `43` | La dimensione del troncamento per i messaggi di posta elettronica in formato testo normale. |
| MaxEmailHTMLBodyTruncationSize | `44` | La dimensione del troncamento per i messaggi di posta elettronica in formato HTML. |
| RequireSignedSMIMEMessages | `45` | Se il dispositivo è necessario per inviare messaggi S/MIME firmati. |
| RequireEncryptedSMIMEMessages | `46` | Se è necessario che il dispositivo invii messaggi crittografati. |
| RequireSignedSMIMEAlgorithm | `47` | L'algoritmo da utilizzare quando si firma un messaggio. |
| RequireEncryptionSMIMEAlgorithm | `48` | L'algoritmo da utilizzare per crittografare un messaggio. |
| AllowSMIMEEncryptionAlgorithmNegotiation | `49` | Se il dispositivo può negoziare l'algoritmo di crittografia da utilizzare per la firma. |
| AllowSMIMESoftCerts | `50` | Indica se il dispositivo utilizza i certificati software per firmare i messaggi in uscita. |
| AllowBrowser | `51` | Se il dispositivo consente l'utilizzo di un browser web. |
| AllowConsumerEmail | `52` | Se il dispositivo consente l'utilizzo della posta elettronica personale. |
| AllowRemoteDesktop | `53` | Se il dispositivo consente l'utilizzo di Desktop remoto. |
| AllowInternetSharing | `54` | Se il dispositivo consente l'utilizzo di Condivisione Internet. |
| UnapprovedInROMApplicationList | `55` | Un elenco di applicazioni in-ROM che non sono approvate per l'esecuzione. |
| ApplicationName | `56` | Il nome di un'applicazione in-ROM (file .exe) che non è stata approvata per l'esecuzione. |
| ApprovedApplicationList | `57` | Un elenco di applicazioni in-RAM approvate per l'esecuzione. |
| Hash | `58` | L'hash SHA-1 di un'applicazione in memoria approvata per l'esecuzione. |

### Guarda anche

* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
