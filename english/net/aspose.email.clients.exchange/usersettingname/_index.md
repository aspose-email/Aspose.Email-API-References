---
title: UserSettingName
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 3600
url: /net/aspose.email.clients.exchange/usersettingname/
---
## UserSettingName enumeration

User settings that can be requested using GetUserSettings.

```csharp
public enum UserSettingName
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| UserDisplayName | `0` | The display name of the user. |
| UserDN | `1` | The legacy distinguished name of the user. |
| UserDeploymentId | `2` | The deployment Id of the user. |
| InternalMailboxServer | `3` | The fully qualified domain name of the mailbox server. |
| InternalRpcClientServer | `4` | The fully qualified domain name of the RPC client server. |
| InternalMailboxServerDN | `5` | The legacy distinguished name of the mailbox server. |
| InternalEcpUrl | `6` | The internal URL of the Exchange Control Panel. |
| InternalEcpVoicemailUrl | `7` | The internal URL of the Exchange Control Panel for VoiceMail Customization. |
| InternalEcpEmailSubscriptionsUrl | `8` | The internal URL of the Exchange Control Panel for Email Subscriptions. |
| InternalEcpTextMessagingUrl | `9` | The internal URL of the Exchange Control Panel for Text Messaging. |
| InternalEcpDeliveryReportUrl | `10` | The internal URL of the Exchange Control Panel for Delivery Reports. |
| InternalEcpRetentionPolicyTagsUrl | `11` | The internal URL of the Exchange Control Panel for RetentionPolicy Tags. |
| InternalEcpPublishingUrl | `12` | The internal URL of the Exchange Control Panel for Publishing. |
| InternalEcpPhotoUrl | `13` | The internal URL of the Exchange Control Panel for photos. |
| InternalEcpConnectUrl | `14` | The internal URL of the Exchange Control Panel for People Connect subscriptions. |
| InternalEcpTeamMailboxUrl | `15` | The internal URL of the Exchange Control Panel for Team Mailbox. |
| InternalEcpTeamMailboxCreatingUrl | `16` | The internal URL of the Exchange Control Panel for creating Team Mailbox. |
| InternalEcpTeamMailboxEditingUrl | `17` | The internal URL of the Exchange Control Panel for editing Team Mailbox. |
| InternalEcpTeamMailboxHidingUrl | `18` | The internal URL of the Exchange Control Panel for hiding Team Mailbox. |
| InternalEcpExtensionInstallationUrl | `19` | The internal URL of the Exchange Control Panel for the extension installation. |
| InternalEwsUrl | `20` | The internal URL of the Exchange Web Services. |
| InternalEmwsUrl | `21` | The internal URL of the Exchange Management Web Services. |
| InternalOABUrl | `22` | The internal URL of the Offline Address Book. |
| InternalPhotosUrl | `23` | The internal URL of the Photos service. |
| InternalUMUrl | `24` | The internal URL of the Unified Messaging services. |
| InternalWebClientUrls | `25` | The internal URLs of the Exchange web client. |
| MailboxDN | `26` | The distinguished name of the mailbox database of the user's mailbox. |
| PublicFolderServer | `27` | The name of the Public Folders server. |
| ActiveDirectoryServer | `28` | The name of the Active Directory server. |
| ExternalMailboxServer | `29` | The name of the RPC over HTTP server. |
| ExternalMailboxServerRequiresSSL | `30` | Indicates whether the RPC over HTTP server requires SSL. |
| ExternalMailboxServerAuthenticationMethods | `31` | The authentication methods supported by the RPC over HTTP server. |
| EcpVoicemailUrlFragment | `32` | The URL fragment of the Exchange Control Panel for VoiceMail Customization. |
| EcpEmailSubscriptionsUrlFragment | `33` | The URL fragment of the Exchange Control Panel for Email Subscriptions. |
| EcpTextMessagingUrlFragment | `34` | The URL fragment of the Exchange Control Panel for Text Messaging. |
| EcpDeliveryReportUrlFragment | `35` | The URL fragment of the Exchange Control Panel for Delivery Reports. |
| EcpRetentionPolicyTagsUrlFragment | `36` | The URL fragment of the Exchange Control Panel for RetentionPolicy Tags. |
| EcpPublishingUrlFragment | `37` | The URL fragment of the Exchange Control Panel for Publishing. |
| EcpPhotoUrlFragment | `38` | The URL fragment of the Exchange Control Panel for photos. |
| EcpConnectUrlFragment | `39` | The URL fragment of the Exchange Control Panel for People Connect. |
| EcpTeamMailboxUrlFragment | `40` | The URL fragment of the Exchange Control Panel for Team Mailbox. |
| EcpTeamMailboxCreatingUrlFragment | `41` | The URL fragment of the Exchange Control Panel for creating Team Mailbox. |
| EcpTeamMailboxEditingUrlFragment | `42` | The URL fragment of the Exchange Control Panel for editing Team Mailbox. |
| EcpExtensionInstallationUrlFragment | `43` | The URL fragment of the Exchange Control Panel for installing extension. |
| ExternalEcpUrl | `44` | The external URL of the Exchange Control Panel. |
| ExternalEcpVoicemailUrl | `45` | The external URL of the Exchange Control Panel for VoiceMail Customization. |
| ExternalEcpEmailSubscriptionsUrl | `46` | The external URL of the Exchange Control Panel for Email Subscriptions. |
| ExternalEcpTextMessagingUrl | `47` | The external URL of the Exchange Control Panel for Text Messaging. |
| ExternalEcpDeliveryReportUrl | `48` | The external URL of the Exchange Control Panel for Delivery Reports. |
| ExternalEcpRetentionPolicyTagsUrl | `49` | The external URL of the Exchange Control Panel for RetentionPolicy Tags. |
| ExternalEcpPublishingUrl | `50` | The external URL of the Exchange Control Panel for Publishing. |
| ExternalEcpPhotoUrl | `51` | The external URL of the Exchange Control Panel for photos. |
| ExternalEcpConnectUrl | `52` | The external URL of the Exchange Control Panel for People Connect subscriptions. |
| ExternalEcpTeamMailboxUrl | `53` | The external URL of the Exchange Control Panel for Team Mailbox. |
| ExternalEcpTeamMailboxCreatingUrl | `54` | The external URL of the Exchange Control Panel for creating Team Mailbox. |
| ExternalEcpTeamMailboxEditingUrl | `55` | The external URL of the Exchange Control Panel for editing Team Mailbox. |
| ExternalEcpTeamMailboxHidingUrl | `56` | The external URL of the Exchange Control Panel for hiding Team Mailbox. |
| ExternalEcpExtensionInstallationUrl | `57` | The external URL of the Exchange Control Panel for the extension installation. |
| ExternalEwsUrl | `58` | The external URL of the Exchange Web Services. |
| ExternalEmwsUrl | `59` | The external URL of the Exchange Management Web Services. |
| ExternalOABUrl | `60` | The external URL of the Offline Address Book. |
| ExternalPhotosUrl | `61` | The external URL of the Photos service. |
| ExternalUMUrl | `62` | The external URL of the Unified Messaging services. |
| ExternalWebClientUrls | `63` | The external URLs of the Exchange web client. |
| CrossOrganizationSharingEnabled | `64` | Indicates that cross-organization sharing is enabled. |
| AlternateMailboxes | `65` | Collection of alternate mailboxes. |
| CasVersion | `66` | The version of the Client Access Server serving the request (e.g. 14.XX.YYY.ZZZ) |
| EwsSupportedSchemas | `67` | Comma-separated list of schema versions supported by Exchange Web Services. The schema version values will be the same as the values of the ExchangeServerVersion enumeration. |
| InternalPop3Connections | `68` | The internal connection settings list for pop protocol |
| ExternalPop3Connections | `69` | The external connection settings list for pop protocol |
| InternalImap4Connections | `70` | The internal connection settings list for imap4 protocol |
| ExternalImap4Connections | `71` | The external connection settings list for imap4 protocol |
| InternalSmtpConnections | `72` | The internal connection settings list for smtp protocol |
| ExternalSmtpConnections | `73` | The external connection settings list for smtp protocol |
| InternalServerExclusiveConnect | `74` | If set to "Off" then clients should not connect via this protocol. The protocol contents are for informational purposes only. |
| ExternalEwsVersion | `75` | The version of the Exchange Web Services server ExternalEwsUrl is pointing to. |
| MobileMailboxPolicy | `76` | Mobile Mailbox policy settings. |
| DocumentSharingLocations | `77` | Document sharing locations and their settings. |
| UserMSOnline | `78` | Whether the user account is an MSOnline account. |
| InternalMailboxServerAuthenticationMethods | `79` | The authentication methods supported by the RPC client server. |
| MailboxVersion | `80` | Version of the server hosting the user's mailbox. |
| SPMySiteHostURL | `81` | Sharepoint MySite Host URL. |
| SiteMailboxCreationURL | `82` | Site mailbox creation URL in SharePoint. It's used by Outlook to create site mailbox from SharePoint directly. |
| InternalRpcHttpServer | `83` | The FQDN of the server used for internal RPC/HTTP connectivity. |
| InternalRpcHttpConnectivityRequiresSsl | `84` | Indicates whether SSL is required for internal RPC/HTTP connectivity. |
| InternalRpcHttpAuthenticationMethod | `85` | The authentication method used for internal RPC/HTTP connectivity. |
| ExternalServerExclusiveConnect | `86` | If set to "On" then clients should only connect via this protocol. |
| ExchangeRpcUrl | `87` | If set, then clients can call the server via XTC |
| ShowGalAsDefaultView | `88` | If set to false then clients should not show the GAL by default, but show the contact list. |
| AutoDiscoverSMTPAddress | `89` | AutoDiscover Primary SMTP Address for the user. |
| InteropExternalEwsUrl | `90` | The 'interop' external URL of the Exchange Web Services. By interop it means a URL to E14 (or later) server that can serve mailboxes that are hosted in downlevel server (E2K3 and earlier). |
| InteropExternalEwsVersion | `91` | Version of server InteropExternalEwsUrl is pointing to. |
| PublicFolderInformation | `92` | Public Folder (Hierarchy) information |
| RedirectUrl | `93` | The version appropriate URL of the AutoDiscover service that should answer this query. |
| EwsPartnerUrl | `94` | The URL of the Exchange Web Services for Office365 partners. |
| CertPrincipalName | `95` | SSL certificate name |
| GroupingInformation | `96` | The grouping hint for certain clients. |
| InternalOutlookServiceUrl | `98` | Internal OutlookService URL |
| ExternalOutlookServiceUrl | `99` | External OutlookService URL |

### Remarks

Add new values to the end and keep in sync with Microsoft.Exchange.Autodiscover.ConfigurationSettings.UserConfigurationSettingName.

### See Also

* namespace [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
