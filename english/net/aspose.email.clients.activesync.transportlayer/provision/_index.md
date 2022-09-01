---
title: Provision
second_title: Aspose.Email for .NET API Reference
description: Provision namespace of the ActiveSync protocol
type: docs
weight: 1710
url: /net/aspose.email.clients.activesync.transportlayer/provision/
---
## Provision enumeration

Provision namespace of the ActiveSync protocol

```csharp
public enum Provision
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Provision | `5` | The capabilities and permissions for the device. |
| Policies | `6` | A collection of security policies. |
| Policy | `7` | A security policy. |
| PolicyType | `8` | Specifies the format in which the policy settings are to be provided. |
| PolicyKey | `9` | Used by the server to mark the state of policy settings on the client. |
| Data | `10` | The settings for a policy. |
| Status | `11` | Indicates success or failure of specific parts of a command. |
| RemoteWipe | `12` | Specifies either a remote wipe directive from the server or a client's confirmation of a remote wipe directive. |
| EASProvisionDoc | `13` | The collection of security settings for device provisioning. |
| DevicePasswordEnabled | `14` | Indicates whether a client device requires a password. |
| AlphanumericDevicePasswordRequired | `15` | Indicates whether a client device requires an alphanumeric password. |
| RequireStorageCardEncryption | `16` | Indicates whether the device has to encrypt content that is stored on the storage card. |
| PasswordRecoveryEnabled | `17` | Indicates whether to enable a recovery password to be sent to the server by using the Settings command. |
| AttachmentsEnabled | `19` | Indicates whether email attachments are enabled. |
| MinDevicePasswordLength | `20` | The minimum device password length that the user can enter |
| MaxInactivityTimeDeviceLock | `21` | The number of seconds of inactivity before the device locks itself. |
| MaxDevicePasswordFailedAttempts | `22` | The number of password failures that are permitted before the device is wiped. |
| MaxAttachmentSize | `23` | The maximum attachment size, as determined by the security policy. |
| AllowSimpleDevicePassword | `24` | Whether the device allows simple passwords. |
| DevicePasswordExpiration | `25` | Whether the password expires after the specified number of days, as determined by the policy. |
| DevicePasswordHistory | `26` | The minimum number of previously used passwords the client device stores to prevent reuse. |
| AllowStorageCard | `27` | Whether the device allows the use of the storage card. |
| AllowCamera | `28` | Whether the device allows the use of the built-in camera. |
| RequireDeviceEncryption | `29` | Whether the device uses encryption. |
| AllowUnsignedApplications | `30` | Whether the device allows unsigned applications to execute. |
| AllowUnsignedInstallationPackages | `31` | Whether the device allows unsigned cabinet (.cab) files to be installed. |
| MinDevicePasswordComplexCharacters | `32` | The minimum number of complex characters (numbers and symbols) contained within the password. |
| AllowWiFi | `33` | Whether the device allows the use of Wi-Fi connections. |
| AllowTextMessaging | `34` | Whether the device allows Short Message Service (SMS)/text messaging. |
| AllowPOPIMAPEmail | `35` | Whether the device allows access to POP/IMAP email. |
| AllowBluetooth | `36` | Whether Bluetooth and hands-free profiles are allowed on the device. |
| AllowIrDA | `37` | Whether the device allows the use of IrDA (infrared) connections. |
| RequireManualSyncWhenRoaming | `38` | Whether the device requires manual synchronization when the device is roaming. |
| AllowDesktopSync | `39` | Whether the device allows synchronization with Desktop ActiveSync. |
| MaxCalendarAgeFilter | `40` | The maximum number of calendar days that can be synchronized. |
| AllowHTMLEmail | `41` | Whether the device uses HTML-formatted email. |
| MaxEmailAgeFilter | `42` | The email age limit for synchronization. |
| MaxEmailBodyTruncationSize | `43` | The truncation size for plain text–formatted email messages. |
| MaxEmailHTMLBodyTruncationSize | `44` | The truncation size for HTML-formatted email messages. |
| RequireSignedSMIMEMessages | `45` | Whether the device is required to send signed S/MIME messages. |
| RequireEncryptedSMIMEMessages | `46` | Whether the device is required to send encrypted messages. |
| RequireSignedSMIMEAlgorithm | `47` | The algorithm to be used when signing a message. |
| RequireEncryptionSMIMEAlgorithm | `48` | The algorithm to be used when encrypting a message. |
| AllowSMIMEEncryptionAlgorithmNegotiation | `49` | Whether the device can negotiate the encryption algorithm to be used for signing. |
| AllowSMIMESoftCerts | `50` | Whether the device uses soft certificates to sign outgoing messages. |
| AllowBrowser | `51` | Whether the device allows the use of a web browser. |
| AllowConsumerEmail | `52` | Whether the device allows the use of personal email. |
| AllowRemoteDesktop | `53` | Whether the device allows the use of Remote Desktop. |
| AllowInternetSharing | `54` | Whether the device allows the use of Internet Sharing. |
| UnapprovedInROMApplicationList | `55` | A list of in-ROM applications that are not approved for execution. |
| ApplicationName | `56` | The name of an in-ROM application (.exe file) that is not approved for execution. |
| ApprovedApplicationList | `57` | A list of in-RAM applications that are approved for execution. |
| Hash | `58` | The SHA-1 hash of an in-memory application that is approved for execution. |

### See Also

* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
