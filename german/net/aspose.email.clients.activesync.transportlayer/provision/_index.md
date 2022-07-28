---
title: Provision
second_title: Aspose.Email für .NET-API-Referenz
description: Namespace des ActiveSync-Protokolls bereitstellen
type: docs
weight: 1710
url: /de/net/aspose.email.clients.activesync.transportlayer/provision/
---
## Provision enumeration

Namespace des ActiveSync-Protokolls bereitstellen

```csharp
public enum Provision
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Provision | `5` | Die Fähigkeiten und Berechtigungen für das Gerät. |
| Policies | `6` | Eine Sammlung von Sicherheitsrichtlinien. |
| Policy | `7` | Eine Sicherheitsrichtlinie. |
| PolicyType | `8` | Gibt das Format an, in dem die Richtlinieneinstellungen bereitgestellt werden sollen. |
| PolicyKey | `9` | Wird vom Server verwendet, um den Status der Richtlinieneinstellungen auf dem Client zu markieren. |
| Data | `10` | Die Einstellungen für eine Richtlinie. |
| Status | `11` | Zeigt den Erfolg oder Misserfolg bestimmter Teile eines Befehls an. |
| RemoteWipe | `12` | Gibt entweder eine Remote-Wipe-Anweisung vom Server oder die Bestätigung einer Remote-Wipe-Anweisung durch einen Client an. |
| EASProvisionDoc | `13` | Die Sammlung von Sicherheitseinstellungen für die Gerätebereitstellung. |
| DevicePasswordEnabled | `14` | Gibt an, ob ein Client-Gerät ein Passwort erfordert. |
| AlphanumericDevicePasswordRequired | `15` | Gibt an, ob ein Client-Gerät ein alphanumerisches Passwort erfordert. |
| RequireStorageCardEncryption | `16` | Gibt an, ob das Gerät Inhalte verschlüsseln muss, die auf der Speicherkarte gespeichert sind. |
| PasswordRecoveryEnabled | `17` | Gibt an, ob das Senden eines Wiederherstellungskennworts an den Server mithilfe des Befehls „Einstellungen“ aktiviert werden soll. |
| AttachmentsEnabled | `19` | Gibt an, ob E-Mail-Anhänge aktiviert sind. |
| MinDevicePasswordLength | `20` | Die minimale Gerätepasswortlänge, die der Benutzer eingeben kann |
| MaxInactivityTimeDeviceLock | `21` | Die Anzahl der Sekunden der Inaktivität, bevor sich das Gerät selbst sperrt. |
| MaxDevicePasswordFailedAttempts | `22` | Die Anzahl der zulässigen Kennwortfehler, bevor das Gerät gelöscht wird. |
| MaxAttachmentSize | `23` | Die maximale Anhangsgröße gemäß der Sicherheitsrichtlinie. |
| AllowSimpleDevicePassword | `24` | Ob das Gerät einfache Passwörter zulässt. |
| DevicePasswordExpiration | `25` | Ob das Passwort nach der angegebenen Anzahl von Tagen abläuft, wie von der Richtlinie festgelegt. |
| DevicePasswordHistory | `26` | Die Mindestanzahl zuvor verwendeter Kennwörter, die das Clientgerät speichert, um eine Wiederverwendung zu verhindern. |
| AllowStorageCard | `27` | Ob das Gerät die Verwendung der Speicherkarte zulässt. |
| AllowCamera | `28` | Ob das Gerät die Verwendung der eingebauten Kamera erlaubt. |
| RequireDeviceEncryption | `29` | Ob das Gerät Verschlüsselung verwendet. |
| AllowUnsignedApplications | `30` | Ob das Gerät die Ausführung unsignierter Anwendungen zulässt. |
| AllowUnsignedInstallationPackages | `31` | Ob das Gerät die Installation von unsignierten Cabinet-Dateien (.cab) zulässt. |
| MinDevicePasswordComplexCharacters | `32` | Die Mindestanzahl komplexer Zeichen (Zahlen und Symbole), die im Passwort enthalten sind. |
| AllowWiFi | `33` | Ob das Gerät die Verwendung von Wi-Fi-Verbindungen zulässt. |
| AllowTextMessaging | `34` | Ob das Gerät Short Message Service (SMS)/Textnachrichten zulässt. |
| AllowPOPIMAPEmail | `35` | Ob das Gerät den Zugriff auf POP/IMAP-E-Mails zulässt. |
| AllowBluetooth | `36` | Ob Bluetooth- und Freisprechprofile auf dem Gerät erlaubt sind. |
| AllowIrDA | `37` | Ob das Gerät die Verwendung von IrDA-Verbindungen (Infrarot) zulässt. |
| RequireManualSyncWhenRoaming | `38` | Ob das Gerät beim Roaming eine manuelle Synchronisierung benötigt. |
| AllowDesktopSync | `39` | Ob das Gerät die Synchronisierung mit Desktop ActiveSync zulässt. |
| MaxCalendarAgeFilter | `40` | Die maximale Anzahl von Kalendertagen, die synchronisiert werden können. |
| AllowHTMLEmail | `41` | Ob das Gerät HTML-formatierte E-Mails verwendet. |
| MaxEmailAgeFilter | `42` | Die E-Mail-Altersgrenze für die Synchronisierung. |
| MaxEmailBodyTruncationSize | `43` | Die Kürzungsgröße für E-Mail-Nachrichten im Nur-Text-Format. |
| MaxEmailHTMLBodyTruncationSize | `44` | Die Kürzungsgröße für E-Mail-Nachrichten im HTML-Format. |
| RequireSignedSMIMEMessages | `45` | Ob das Gerät signierte S/MIME-Nachrichten senden muss. |
| RequireEncryptedSMIMEMessages | `46` | Ob das Gerät verschlüsselte Nachrichten senden muss. |
| RequireSignedSMIMEAlgorithm | `47` | Der beim Signieren einer Nachricht zu verwendende Algorithmus. |
| RequireEncryptionSMIMEAlgorithm | `48` | Der beim Verschlüsseln einer Nachricht zu verwendende Algorithmus. |
| AllowSMIMEEncryptionAlgorithmNegotiation | `49` | Ob das Gerät den zum Signieren zu verwendenden Verschlüsselungsalgorithmus aushandeln kann. |
| AllowSMIMESoftCerts | `50` | Ob das Gerät Soft-Zertifikate verwendet, um ausgehende Nachrichten zu signieren. |
| AllowBrowser | `51` | Ob das Gerät die Verwendung eines Webbrowsers zulässt. |
| AllowConsumerEmail | `52` | Ob das Gerät die Nutzung privater E-Mails zulässt. |
| AllowRemoteDesktop | `53` | Ob das Gerät die Verwendung von Remote Desktop zulässt. |
| AllowInternetSharing | `54` | Ob das Gerät die Nutzung der Internetfreigabe zulässt. |
| UnapprovedInROMApplicationList | `55` | Eine Liste von In-ROM-Anwendungen, die nicht zur Ausführung zugelassen sind. |
| ApplicationName | `56` | Der Name einer In-ROM-Anwendung (.exe-Datei), die nicht zur Ausführung zugelassen ist. |
| ApprovedApplicationList | `57` | Eine Liste von In-RAM-Anwendungen, die zur Ausführung zugelassen sind. |
| Hash | `58` | Der SHA-1-Hash einer In-Memory-Anwendung, die zur Ausführung genehmigt wurde. |

### Siehe auch

* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
