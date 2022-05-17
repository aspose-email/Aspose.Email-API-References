---
title: EASProvisionDoc
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 1190
url: /net/aspose.email.clients.activesync.transportlayer/easprovisiondoc/
---
## EASProvisionDoc class

Specifies the collection of security settings for device provisioning.

```csharp
public class EASProvisionDoc
```

## Constructors

| Name | Description |
| --- | --- |
| [EASProvisionDoc](easprovisiondoc)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AllowBluetooth](allowbluetooth) { get; set; } | Specifies the use of Bluetooth on the device. This property SHOULD be ignored if the client does not support Bluetooth. |
| [AllowBrowser](allowbrowser) { get; set; } | Specifies whether the device allows the use of a web browser. |
| [AllowCamera](allowcamera) { get; set; } | Specifies whether the device allows the use of the built-in camera. This property SHOULD be ignored if the client does not have a camera and no camera can be attached to the device. |
| [AllowConsumerEmail](allowconsumeremail) { get; set; } | Specifies whether the device allows the user to configure a personal email account. |
| [AllowDesktopSync](allowdesktopsync) { get; set; } | Specifies whether the device allows synchronization with Desktop ActiveSync. This property SHOULD be ignored if the client does not support connecting to a personal computer. |
| [AllowHTMLEmail](allowhtmlemail) { get; set; } | Specifies whether the client uses HTML-formatted email. |
| [AllowInternetSharing](allowinternetsharing) { get; set; } | Specifies whether the device allows the use of Internet Sharing. This property SHOULD be ignored if the client does not support sharing its internet connection with other devices. |
| [AllowIrDA](allowirda) { get; set; } | Specifies whether the device allows the use of IrDA (infrared) connections. This property SHOULD be ignored if the client does not have the capability of transmitting or receiving infrared signals. |
| [AllowPOPIMAPEmail](allowpopimapemail) { get; set; } | Specifies whether the device allows access to POP or IMAP email. |
| [AllowRemoteDesktop](allowremotedesktop) { get; set; } | Specifies whether the device allows the use of Remote Desktop. This property SHOULD be ignored if the client does not support connecting remotely to a personal computer. |
| [AllowSimpleDevicePassword](allowsimpledevicepassword) { get; set; } | Specifies whether the client allows simple passwords. A simple password is one consisting only of repeated ("2222") or sequential ("abcd") characters. If AllowSimpleDevicePassword is null, a client SHOULD treat this value as TRUE. If the value of the DevicePasswordEnabled is set to FALSE, the client SHOULD ignore this property. |
| [AllowSMIMEEncryptionAlgorithmNegotiation](allowsmimeencryptionalgorithmnegotiation) { get; set; } | Controls the negotiation of the encryption algorithm. |
| [AllowSMIMESoftCerts](allowsmimesoftcerts) { get; set; } | Specifies whether the client can use soft certificates to sign outgoing messages. |
| [AllowStorageCard](allowstoragecard) { get; set; } | Specifies whether the device allows use of the storage card. This property SHOULD be ignored if the client does not support storing data on removable storage. |
| [AllowTextMessaging](allowtextmessaging) { get; set; } | Specifies whether the device allows the use of SMS or text messaging. This property SHOULD be ignored if the client does not support SMS or text messaging. |
| [AllowUnsignedApplications](allowunsignedapplications) { get; set; } | Specifies whether the device allows unsigned applications to execute. |
| [AllowUnsignedInstallationPackages](allowunsignedinstallationpackages) { get; set; } | Specifies whether the device allows unsigned cabinet (.cab) files to be installed. |
| [AllowWiFi](allowwifi) { get; set; } | Specifies whether the device allows the use of Wi-Fi connections. This property SHOULD be ignored if the client does not have Wi-Fi capability. |
| [AlphanumericDevicePasswordRequired](alphanumericdevicepasswordrequired) { get; set; } | Specifies whether a client requires an alphanumeric password. If AlphanumericDevicePasswordRequired is null, a client SHOULD treat this value as FALSE. If the value of the DevicePasswordEnabled is FALSE, the client SHOULD ignore this property. |
| [ApprovedApplicationList](approvedapplicationlist) { get; } | Specifies a list of in-memory applications that are approved for execution. Only in-memory applications are affected by this property. This property does not apply to in-ROM applications. If non empty, the client MUST only allow the in-memory applications specified by this property to execute. |
| [AttachmentsEnabled](attachmentsenabled) { get; set; } | Specifies whether email attachments are enabled. |
| [DevicePasswordEnabled](devicepasswordenabled) { get; set; } | Specifies whether a client requires a password. |
| [DevicePasswordExpiration](devicepasswordexpiration) { get; set; } | Specifies the maximum number of days until a password expires. The DevicePasswordExpiration can be null, indicating that no password expiration policy is set. Valid values are listed bellow: = 0 - Passwords do not expire. &gt; 0 - Passwords expire in the specified maximum number of days. If DevicePasswordExpiration is null, a client SHOULD treat this value as 0. If the value of the DevicePasswordEnabled is set to FALSE, the client SHOULD ignore this property. |
| [DevicePasswordHistory](devicepasswordhistory) { get; set; } | Specifies the minimum number of previously used passwords stored to prevent reuse by the client. Valid values are listed bellow: = 0 - Storage of previously used passwords is not required. &gt; 0 - The minimum number of previously used passwords to be stored. If DevicePasswordHistory is null, then a client SHOULD treat this value as 0. If the value of the DevicePasswordEnabled is set to TRUE, the client disallows the user from using a stored prior password after a password expires. If the value of the DevicePasswordEnabled is set to FALSE, the client SHOULD ignore this property. |
| [MaxAttachmentSize](maxattachmentsize) { get; set; } | Specifies the maximum attachment size in bytes as determined by security policy. If the property is null, the client interprets this as meaning no maximum attachment size has been set by the security policy. |
| [MaxCalendarAgeFilter](maxcalendaragefilter) { get; set; } | Specifies the maximum number of calendar days that can be synchronized. Valid values are listed bellow: All days 2 weeks 1 month 3 months 6 months |
| [MaxDevicePasswordFailedAttempts](maxdevicepasswordfailedattempts) { get; set; } | Specifies the maximum number of failed password logon attempts that are permitted. The client SHOULD perform a local wipe or enter a timed lock out mode if the maximum number of failed password logon attempts is reached. The MaxDevicePasswordFailedAttempts can be null or have a value in the range from 4 through 16. If the property is null, the client interprets this as meaning that no maximum number of failed password logon attempts has been set by the security policy. If the value of the DevicePasswordEnabled is set to FALSE, the client ignores this property. |
| [MaxEmailAgeFilter](maxemailagefilter) { get; set; } | Specifies the email age limit for synchronization. Valid values are listed bellow: Sync all 1 day 3 days 1 week 2 weeks 1 month |
| [MaxEmailBodyTruncationSize](maxemailbodytruncationsize) { get; set; } | Specifies the truncation size for plain text–formatted email. Valid values are listed bellow: -1 No truncation. =0 Truncate only the header. &gt;0 Truncate the email body to the specified size. |
| [MaxEmailHTMLBodyTruncationSize](maxemailhtmlbodytruncationsize) { get; set; } | Specifies the truncation size for HTML-formatted email. Valid values are listed bellow: -1 No truncation. =0 Truncate only the header. &gt;0 Truncate the email body to the specified size. |
| [MaxInactivityTimeDeviceLock](maxinactivitytimedevicelock) { get; set; } | Specifies the maximum number of seconds of inactivity before the device locks itself. If this value is greater than or equal to 9999, the client interprets it as unlimited. If the MaxInactivityTimeDeviceLock is null, the client interprets this as meaning that no time device lock has been set by the security policy. |
| [MinDevicePasswordComplexCharacters](mindevicepasswordcomplexcharacters) { get; set; } | Specifies the required level of complexity of the client password. The value specifies the number of character groups that are required to be present in the password. The character groups are defined as: Lower case alphabetical characters = 1 Lower case and Upper case alphabetical characters = 2 Lower case, Upper case alphabetical characters and Numbers = 3 Lower case and Upper case alphabetical characters, Numbers and Non-alphanumeric characters = 4 For example: If the value of MinDevicePasswordComplexCharacters is 2, a password with both upper case and lower case alphabetical characters would be sufficient, as would a password with lower case alphabetical characters and numbers. |
| [MinDevicePasswordLength](mindevicepasswordlength) { get; set; } | Specifies the minimum client password length. The MinDevicePasswordLength can be empty or have a value no less than 1 and no greater than 16. If the property is null or the value of this property is 1, there is no minimum length for the device password. If the value of the DevicePasswordEnabled is FALSE, the client SHOULD ignore this property . |
| [PasswordRecoveryEnabled](passwordrecoveryenabled) { get; set; } | Specifies whether the server supports storage of a recovery password to be sent by the client using the Settings command. A recovery password is a special password created by the client that gives the administrator or user the ability to log on to the device one time, after which the user is required to create a new password. The client then creates a new recovery password. If the PasswordRecoveryEnabled is set to TRUE, the server supports storage of a recovery password sent by the device. If the property is set to FALSE, the device SHOULD NOT send a recovery password, because the server does not support storage of the password. If PasswordRecoveryEnabled is null, a client SHOULD treat this value as FALSE. If the value of the DevicePasswordEnabled is FALSE, the client SHOULD ignore this property. This property SHOULD be ignored if the client does not support recovery passwords. |
| [RequireDeviceEncryption](requiredeviceencryption) { get; set; } | Specifies whether the client uses encryption. |
| [RequireEncryptedSMIMEMessages](requireencryptedsmimemessages) { get; set; } | Specifies whether the client sends encrypted email messages. |
| [RequireEncryptionSMIMEAlgorithm](requireencryptionsmimealgorithm) { get; set; } | Specifies the algorithm used when encrypting S/MIME messages. |
| [RequireManualSyncWhenRoaming](requiremanualsyncwhenroaming) { get; set; } | Specifies whether the device requires manual synchronization when the device is roaming. |
| [RequireSignedSMIMEAlgorithm](requiresignedsmimealgorithm) { get; set; } | Specifies the algorithm used when signing S/MIME messages. |
| [RequireSignedSMIMEMessages](requiresignedsmimemessages) { get; set; } | Specifies whether the client sends signed S/MIME messages. |
| [RequireStorageCardEncryption](requirestoragecardencryption) { get; set; } | Specifies whether the device encrypts content that is stored on the device. This property SHOULD be ignored if the client does not support storing data on removable storage. |
| [UnapprovedInROMApplicationList](unapprovedinromapplicationlist) { get; } | Specifies a list of in-ROM applications that are not approved for execution. Only applications that are preinstalled in ROM are affected by the entries in this property. This property does not apply to applications that are installed in-memory. |

### See Also

* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
