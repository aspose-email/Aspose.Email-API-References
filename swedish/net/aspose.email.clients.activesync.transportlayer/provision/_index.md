---
title: Provision
second_title: Aspose.Email för .NET API-referens
description: Tillhandahålla namnutrymmet för ActiveSync-protokollet
type: docs
weight: 1710
url: /sv/net/aspose.email.clients.activesync.transportlayer/provision/
---
## Provision enumeration

Tillhandahålla namnutrymmet för ActiveSync-protokollet

```csharp
public enum Provision
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| Provision | `5` | Möjligheterna och behörigheterna för enheten. |
| Policies | `6` | En samling säkerhetspolicyer. |
| Policy | `7` | En säkerhetspolicy. |
| PolicyType | `8` | Anger formatet som policyinställningarna ska tillhandahållas i. |
| PolicyKey | `9` | Används av servern för att markera tillståndet för policyinställningar på klienten. |
| Data | `10` | Inställningarna för en policy. |
| Status | `11` | Indikerar framgång eller misslyckande för specifika delar av ett kommando. |
| RemoteWipe | `12` | Anger antingen ett fjärrspoleringsdirektiv från servern eller en klients bekräftelse av ett fjärrspolningsdirektiv. |
| EASProvisionDoc | `13` | Samlingen av säkerhetsinställningar för enhetsprovisionering. |
| DevicePasswordEnabled | `14` | Indikerar om en klientenhet kräver ett lösenord. |
| AlphanumericDevicePasswordRequired | `15` | Indikerar om en klientenhet kräver ett alfanumeriskt lösenord. |
| RequireStorageCardEncryption | `16` | Indikerar om enheten måste kryptera innehåll som är lagrat på minneskortet. |
| PasswordRecoveryEnabled | `17` | Indikerar om ett återställningslösenord ska kunna skickas till servern genom att använda kommandot Inställningar. |
| AttachmentsEnabled | `19` | Indikerar om e-postbilagor är aktiverade. |
| MinDevicePasswordLength | `20` | Minsta enhetslösenordslängd som användaren kan ange |
| MaxInactivityTimeDeviceLock | `21` | Antalet sekunders inaktivitet innan enheten låser sig. |
| MaxDevicePasswordFailedAttempts | `22` | Antalet lösenordsfel som är tillåtna innan enheten raderas. |
| MaxAttachmentSize | `23` | Den maximala bifogade storleken, enligt säkerhetspolicyn. |
| AllowSimpleDevicePassword | `24` | Om enheten tillåter enkla lösenord. |
| DevicePasswordExpiration | `25` | Om lösenordet upphör att gälla efter det angivna antalet dagar, enligt policyn. |
| DevicePasswordHistory | `26` | Det minsta antalet tidigare använda lösenord som klientenheten lagrar för att förhindra återanvändning. |
| AllowStorageCard | `27` | Om enheten tillåter användning av minneskortet. |
| AllowCamera | `28` | Om enheten tillåter användning av den inbyggda kameran. |
| RequireDeviceEncryption | `29` | Om enheten använder kryptering. |
| AllowUnsignedApplications | `30` | Om enheten tillåter att osignerade applikationer körs. |
| AllowUnsignedInstallationPackages | `31` | Om enheten tillåter att osignerade skåpfiler (.cab) installeras. |
| MinDevicePasswordComplexCharacters | `32` | Det minsta antalet komplexa tecken (siffror och symboler) som finns i lösenordet. |
| AllowWiFi | `33` | Om enheten tillåter användning av Wi-Fi-anslutningar. |
| AllowTextMessaging | `34` | Om enheten tillåter Short Message Service (SMS)/textmeddelanden. |
| AllowPOPIMAPEmail | `35` | Om enheten tillåter åtkomst till POP/IMAP-e-post. |
| AllowBluetooth | `36` | Om Bluetooth och handsfree-profiler är tillåtna på enheten. |
| AllowIrDA | `37` | Om enheten tillåter användning av IrDA (infraröda) anslutningar. |
| RequireManualSyncWhenRoaming | `38` | Om enheten kräver manuell synkronisering när enheten roaming. |
| AllowDesktopSync | `39` | Om enheten tillåter synkronisering med Desktop ActiveSync. |
| MaxCalendarAgeFilter | `40` | Det maximala antalet kalenderdagar som kan synkroniseras. |
| AllowHTMLEmail | `41` | Om enheten använder HTML-formaterad e-post. |
| MaxEmailAgeFilter | `42` | Åldersgränsen för e-post för synkronisering. |
| MaxEmailBodyTruncationSize | `43` | Trunkeringsstorleken för e-postmeddelanden med vanlig text. |
| MaxEmailHTMLBodyTruncationSize | `44` | Trunkeringsstorleken för HTML-formaterade e-postmeddelanden. |
| RequireSignedSMIMEMessages | `45` | Om enheten måste skicka signerade S/MIME-meddelanden. |
| RequireEncryptedSMIMEMessages | `46` | Om enheten måste skicka krypterade meddelanden. |
| RequireSignedSMIMEAlgorithm | `47` | Algoritmen som ska användas när ett meddelande signeras. |
| RequireEncryptionSMIMEAlgorithm | `48` | Algoritmen som ska användas vid kryptering av ett meddelande. |
| AllowSMIMEEncryptionAlgorithmNegotiation | `49` | Om enheten kan förhandla om krypteringsalgoritmen som ska användas för signering. |
| AllowSMIMESoftCerts | `50` | Om enheten använder mjuka certifikat för att signera utgående meddelanden. |
| AllowBrowser | `51` | Om enheten tillåter användning av en webbläsare. |
| AllowConsumerEmail | `52` | Om enheten tillåter användning av personlig e-post. |
| AllowRemoteDesktop | `53` | Om enheten tillåter användning av Remote Desktop. |
| AllowInternetSharing | `54` | Om enheten tillåter användning av Internetdelning. |
| UnapprovedInROMApplicationList | `55` | En lista över in-ROM-applikationer som inte är godkända för körning. |
| ApplicationName | `56` | Namnet på en in-ROM-applikation (.exe-fil) som inte är godkänd för körning. |
| ApprovedApplicationList | `57` | En lista över in-RAM-applikationer som är godkända för exekvering. |
| Hash | `58` | SHA-1-hash för en applikation i minnet som är godkänd för körning. |

### Se även

* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
