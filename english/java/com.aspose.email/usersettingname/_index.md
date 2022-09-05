---
title: UserSettingName
second_title: Aspose.Email for Java API Reference
description:  User settings that can be requested using GetUserSettings.
type: docs
weight: 689
url: /java/com.aspose.email/usersettingname/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class UserSettingName extends System.Enum
```

User settings that can be requested using GetUserSettings.

--------------------

Add new values to the end and keep in sync with Microsoft.Exchange.Autodiscover.ConfigurationSettings.UserConfigurationSettingName.
## Fields

| Field | Description |
| --- | --- |
| [UserDisplayName](#UserDisplayName) | The display name of the user. |
| [UserDN](#UserDN) | The legacy distinguished name of the user. |
| [UserDeploymentId](#UserDeploymentId) | The deployment Id of the user. |
| [InternalMailboxServer](#InternalMailboxServer) | The fully qualified domain name of the mailbox server. |
| [InternalRpcClientServer](#InternalRpcClientServer) | The fully qualified domain name of the RPC client server. |
| [InternalMailboxServerDN](#InternalMailboxServerDN) | The legacy distinguished name of the mailbox server. |
| [InternalEcpUrl](#InternalEcpUrl) | The internal URL of the Exchange Control Panel. |
| [InternalEcpVoicemailUrl](#InternalEcpVoicemailUrl) | The internal URL of the Exchange Control Panel for VoiceMail Customization. |
| [InternalEcpEmailSubscriptionsUrl](#InternalEcpEmailSubscriptionsUrl) | The internal URL of the Exchange Control Panel for Email Subscriptions. |
| [InternalEcpTextMessagingUrl](#InternalEcpTextMessagingUrl) | The internal URL of the Exchange Control Panel for Text Messaging. |
| [InternalEcpDeliveryReportUrl](#InternalEcpDeliveryReportUrl) | The internal URL of the Exchange Control Panel for Delivery Reports. |
| [InternalEcpRetentionPolicyTagsUrl](#InternalEcpRetentionPolicyTagsUrl) | The internal URL of the Exchange Control Panel for RetentionPolicy Tags. |
| [InternalEcpPublishingUrl](#InternalEcpPublishingUrl) | The internal URL of the Exchange Control Panel for Publishing. |
| [InternalEcpPhotoUrl](#InternalEcpPhotoUrl) | The internal URL of the Exchange Control Panel for photos. |
| [InternalEcpConnectUrl](#InternalEcpConnectUrl) | The internal URL of the Exchange Control Panel for People Connect subscriptions. |
| [InternalEcpTeamMailboxUrl](#InternalEcpTeamMailboxUrl) | The internal URL of the Exchange Control Panel for Team Mailbox. |
| [InternalEcpTeamMailboxCreatingUrl](#InternalEcpTeamMailboxCreatingUrl) | The internal URL of the Exchange Control Panel for creating Team Mailbox. |
| [InternalEcpTeamMailboxEditingUrl](#InternalEcpTeamMailboxEditingUrl) | The internal URL of the Exchange Control Panel for editing Team Mailbox. |
| [InternalEcpTeamMailboxHidingUrl](#InternalEcpTeamMailboxHidingUrl) | The internal URL of the Exchange Control Panel for hiding Team Mailbox. |
| [InternalEcpExtensionInstallationUrl](#InternalEcpExtensionInstallationUrl) | The internal URL of the Exchange Control Panel for the extension installation. |
| [InternalEwsUrl](#InternalEwsUrl) | The internal URL of the Exchange Web Services. |
| [InternalEmwsUrl](#InternalEmwsUrl) | The internal URL of the Exchange Management Web Services. |
| [InternalOABUrl](#InternalOABUrl) | The internal URL of the Offline Address Book. |
| [InternalPhotosUrl](#InternalPhotosUrl) | The internal URL of the Photos service. |
| [InternalUMUrl](#InternalUMUrl) | The internal URL of the Unified Messaging services. |
| [InternalWebClientUrls](#InternalWebClientUrls) | The internal URLs of the Exchange web client. |
| [MailboxDN](#MailboxDN) | The distinguished name of the mailbox database of the user's mailbox. |
| [PublicFolderServer](#PublicFolderServer) | The name of the Public Folders server. |
| [ActiveDirectoryServer](#ActiveDirectoryServer) | The name of the Active Directory server. |
| [ExternalMailboxServer](#ExternalMailboxServer) | The name of the RPC over HTTP server. |
| [ExternalMailboxServerRequiresSSL](#ExternalMailboxServerRequiresSSL) | Indicates whether the RPC over HTTP server requires SSL. |
| [ExternalMailboxServerAuthenticationMethods](#ExternalMailboxServerAuthenticationMethods) | The authentication methods supported by the RPC over HTTP server. |
| [EcpVoicemailUrlFragment](#EcpVoicemailUrlFragment) | The URL fragment of the Exchange Control Panel for VoiceMail Customization. |
| [EcpEmailSubscriptionsUrlFragment](#EcpEmailSubscriptionsUrlFragment) | The URL fragment of the Exchange Control Panel for Email Subscriptions. |
| [EcpTextMessagingUrlFragment](#EcpTextMessagingUrlFragment) | The URL fragment of the Exchange Control Panel for Text Messaging. |
| [EcpDeliveryReportUrlFragment](#EcpDeliveryReportUrlFragment) | The URL fragment of the Exchange Control Panel for Delivery Reports. |
| [EcpRetentionPolicyTagsUrlFragment](#EcpRetentionPolicyTagsUrlFragment) | The URL fragment of the Exchange Control Panel for RetentionPolicy Tags. |
| [EcpPublishingUrlFragment](#EcpPublishingUrlFragment) | The URL fragment of the Exchange Control Panel for Publishing. |
| [EcpPhotoUrlFragment](#EcpPhotoUrlFragment) | The URL fragment of the Exchange Control Panel for photos. |
| [EcpConnectUrlFragment](#EcpConnectUrlFragment) | The URL fragment of the Exchange Control Panel for People Connect. |
| [EcpTeamMailboxUrlFragment](#EcpTeamMailboxUrlFragment) | The URL fragment of the Exchange Control Panel for Team Mailbox. |
| [EcpTeamMailboxCreatingUrlFragment](#EcpTeamMailboxCreatingUrlFragment) | The URL fragment of the Exchange Control Panel for creating Team Mailbox. |
| [EcpTeamMailboxEditingUrlFragment](#EcpTeamMailboxEditingUrlFragment) | The URL fragment of the Exchange Control Panel for editing Team Mailbox. |
| [EcpExtensionInstallationUrlFragment](#EcpExtensionInstallationUrlFragment) | The URL fragment of the Exchange Control Panel for installing extension. |
| [ExternalEcpUrl](#ExternalEcpUrl) | The external URL of the Exchange Control Panel. |
| [ExternalEcpVoicemailUrl](#ExternalEcpVoicemailUrl) | The external URL of the Exchange Control Panel for VoiceMail Customization. |
| [ExternalEcpEmailSubscriptionsUrl](#ExternalEcpEmailSubscriptionsUrl) | The external URL of the Exchange Control Panel for Email Subscriptions. |
| [ExternalEcpTextMessagingUrl](#ExternalEcpTextMessagingUrl) | The external URL of the Exchange Control Panel for Text Messaging. |
| [ExternalEcpDeliveryReportUrl](#ExternalEcpDeliveryReportUrl) | The external URL of the Exchange Control Panel for Delivery Reports. |
| [ExternalEcpRetentionPolicyTagsUrl](#ExternalEcpRetentionPolicyTagsUrl) | The external URL of the Exchange Control Panel for RetentionPolicy Tags. |
| [ExternalEcpPublishingUrl](#ExternalEcpPublishingUrl) | The external URL of the Exchange Control Panel for Publishing. |
| [ExternalEcpPhotoUrl](#ExternalEcpPhotoUrl) | The external URL of the Exchange Control Panel for photos. |
| [ExternalEcpConnectUrl](#ExternalEcpConnectUrl) | The external URL of the Exchange Control Panel for People Connect subscriptions. |
| [ExternalEcpTeamMailboxUrl](#ExternalEcpTeamMailboxUrl) | The external URL of the Exchange Control Panel for Team Mailbox. |
| [ExternalEcpTeamMailboxCreatingUrl](#ExternalEcpTeamMailboxCreatingUrl) | The external URL of the Exchange Control Panel for creating Team Mailbox. |
| [ExternalEcpTeamMailboxEditingUrl](#ExternalEcpTeamMailboxEditingUrl) | The external URL of the Exchange Control Panel for editing Team Mailbox. |
| [ExternalEcpTeamMailboxHidingUrl](#ExternalEcpTeamMailboxHidingUrl) | The external URL of the Exchange Control Panel for hiding Team Mailbox. |
| [ExternalEcpExtensionInstallationUrl](#ExternalEcpExtensionInstallationUrl) | The external URL of the Exchange Control Panel for the extension installation. |
| [ExternalEwsUrl](#ExternalEwsUrl) | The external URL of the Exchange Web Services. |
| [ExternalEmwsUrl](#ExternalEmwsUrl) | The external URL of the Exchange Management Web Services. |
| [ExternalOABUrl](#ExternalOABUrl) | The external URL of the Offline Address Book. |
| [ExternalPhotosUrl](#ExternalPhotosUrl) | The external URL of the Photos service. |
| [ExternalUMUrl](#ExternalUMUrl) | The external URL of the Unified Messaging services. |
| [ExternalWebClientUrls](#ExternalWebClientUrls) | The external URLs of the Exchange web client. |
| [CrossOrganizationSharingEnabled](#CrossOrganizationSharingEnabled) | Indicates that cross-organization sharing is enabled. |
| [AlternateMailboxes](#AlternateMailboxes) | Collection of alternate mailboxes. |
| [CasVersion](#CasVersion) | The version of the Client Access Server serving the request (e.g. |
| [EwsSupportedSchemas](#EwsSupportedSchemas) | Comma-separated list of schema versions supported by Exchange Web Services. |
| [InternalPop3Connections](#InternalPop3Connections) | The internal connection settings list for pop protocol |
| [ExternalPop3Connections](#ExternalPop3Connections) | The external connection settings list for pop protocol |
| [InternalImap4Connections](#InternalImap4Connections) | The internal connection settings list for imap4 protocol |
| [ExternalImap4Connections](#ExternalImap4Connections) | The external connection settings list for imap4 protocol |
| [InternalSmtpConnections](#InternalSmtpConnections) | The internal connection settings list for smtp protocol |
| [ExternalSmtpConnections](#ExternalSmtpConnections) | The external connection settings list for smtp protocol |
| [InternalServerExclusiveConnect](#InternalServerExclusiveConnect) | If set to "Off" then clients should not connect via this protocol. |
| [ExternalEwsVersion](#ExternalEwsVersion) | The version of the Exchange Web Services server ExternalEwsUrl is pointing to. |
| [MobileMailboxPolicy](#MobileMailboxPolicy) | Mobile Mailbox policy settings. |
| [DocumentSharingLocations](#DocumentSharingLocations) | Document sharing locations and their settings. |
| [UserMSOnline](#UserMSOnline) | Whether the user account is an MSOnline account. |
| [InternalMailboxServerAuthenticationMethods](#InternalMailboxServerAuthenticationMethods) | The authentication methods supported by the RPC client server. |
| [MailboxVersion](#MailboxVersion) | Version of the server hosting the user's mailbox. |
| [SPMySiteHostURL](#SPMySiteHostURL) | Sharepoint MySite Host URL. |
| [SiteMailboxCreationURL](#SiteMailboxCreationURL) | Site mailbox creation URL in SharePoint. |
| [InternalRpcHttpServer](#InternalRpcHttpServer) | The FQDN of the server used for internal RPC/HTTP connectivity. |
| [InternalRpcHttpConnectivityRequiresSsl](#InternalRpcHttpConnectivityRequiresSsl) | Indicates whether SSL is required for internal RPC/HTTP connectivity. |
| [InternalRpcHttpAuthenticationMethod](#InternalRpcHttpAuthenticationMethod) | The authentication method used for internal RPC/HTTP connectivity. |
| [ExternalServerExclusiveConnect](#ExternalServerExclusiveConnect) | If set to "On" then clients should only connect via this protocol. |
| [ExchangeRpcUrl](#ExchangeRpcUrl) | If set, then clients can call the server via XTC |
| [ShowGalAsDefaultView](#ShowGalAsDefaultView) | If set to false then clients should not show the GAL by default, but show the contact list. |
| [AutoDiscoverSMTPAddress](#AutoDiscoverSMTPAddress) | AutoDiscover Primary SMTP Address for the user. |
| [InteropExternalEwsUrl](#InteropExternalEwsUrl) | The 'interop' external URL of the Exchange Web Services. |
| [InteropExternalEwsVersion](#InteropExternalEwsVersion) | Version of server InteropExternalEwsUrl is pointing to. |
| [PublicFolderInformation](#PublicFolderInformation) | Public Folder (Hierarchy) information |
| [RedirectUrl](#RedirectUrl) | The version appropriate URL of the AutoDiscover service that should answer this query. |
| [EwsPartnerUrl](#EwsPartnerUrl) | The URL of the Exchange Web Services for Office365 partners. |
| [CertPrincipalName](#CertPrincipalName) | SSL certificate name |
| [GroupingInformation](#GroupingInformation) | The grouping hint for certain clients. |
| [InternalOutlookServiceUrl](#InternalOutlookServiceUrl) | Internal OutlookService URL |
| [ExternalOutlookServiceUrl](#ExternalOutlookServiceUrl) | External OutlookService URL |
### UserDisplayName {#UserDisplayName}
```
public static final int UserDisplayName
```


The display name of the user.

### UserDN {#UserDN}
```
public static final int UserDN
```


The legacy distinguished name of the user.

### UserDeploymentId {#UserDeploymentId}
```
public static final int UserDeploymentId
```


The deployment Id of the user.

### InternalMailboxServer {#InternalMailboxServer}
```
public static final int InternalMailboxServer
```


The fully qualified domain name of the mailbox server.

### InternalRpcClientServer {#InternalRpcClientServer}
```
public static final int InternalRpcClientServer
```


The fully qualified domain name of the RPC client server.

### InternalMailboxServerDN {#InternalMailboxServerDN}
```
public static final int InternalMailboxServerDN
```


The legacy distinguished name of the mailbox server.

### InternalEcpUrl {#InternalEcpUrl}
```
public static final int InternalEcpUrl
```


The internal URL of the Exchange Control Panel.

### InternalEcpVoicemailUrl {#InternalEcpVoicemailUrl}
```
public static final int InternalEcpVoicemailUrl
```


The internal URL of the Exchange Control Panel for VoiceMail Customization.

### InternalEcpEmailSubscriptionsUrl {#InternalEcpEmailSubscriptionsUrl}
```
public static final int InternalEcpEmailSubscriptionsUrl
```


The internal URL of the Exchange Control Panel for Email Subscriptions.

### InternalEcpTextMessagingUrl {#InternalEcpTextMessagingUrl}
```
public static final int InternalEcpTextMessagingUrl
```


The internal URL of the Exchange Control Panel for Text Messaging.

### InternalEcpDeliveryReportUrl {#InternalEcpDeliveryReportUrl}
```
public static final int InternalEcpDeliveryReportUrl
```


The internal URL of the Exchange Control Panel for Delivery Reports.

### InternalEcpRetentionPolicyTagsUrl {#InternalEcpRetentionPolicyTagsUrl}
```
public static final int InternalEcpRetentionPolicyTagsUrl
```


The internal URL of the Exchange Control Panel for RetentionPolicy Tags.

### InternalEcpPublishingUrl {#InternalEcpPublishingUrl}
```
public static final int InternalEcpPublishingUrl
```


The internal URL of the Exchange Control Panel for Publishing.

### InternalEcpPhotoUrl {#InternalEcpPhotoUrl}
```
public static final int InternalEcpPhotoUrl
```


The internal URL of the Exchange Control Panel for photos.

### InternalEcpConnectUrl {#InternalEcpConnectUrl}
```
public static final int InternalEcpConnectUrl
```


The internal URL of the Exchange Control Panel for People Connect subscriptions.

### InternalEcpTeamMailboxUrl {#InternalEcpTeamMailboxUrl}
```
public static final int InternalEcpTeamMailboxUrl
```


The internal URL of the Exchange Control Panel for Team Mailbox.

### InternalEcpTeamMailboxCreatingUrl {#InternalEcpTeamMailboxCreatingUrl}
```
public static final int InternalEcpTeamMailboxCreatingUrl
```


The internal URL of the Exchange Control Panel for creating Team Mailbox.

### InternalEcpTeamMailboxEditingUrl {#InternalEcpTeamMailboxEditingUrl}
```
public static final int InternalEcpTeamMailboxEditingUrl
```


The internal URL of the Exchange Control Panel for editing Team Mailbox.

### InternalEcpTeamMailboxHidingUrl {#InternalEcpTeamMailboxHidingUrl}
```
public static final int InternalEcpTeamMailboxHidingUrl
```


The internal URL of the Exchange Control Panel for hiding Team Mailbox.

### InternalEcpExtensionInstallationUrl {#InternalEcpExtensionInstallationUrl}
```
public static final int InternalEcpExtensionInstallationUrl
```


The internal URL of the Exchange Control Panel for the extension installation.

### InternalEwsUrl {#InternalEwsUrl}
```
public static final int InternalEwsUrl
```


The internal URL of the Exchange Web Services.

### InternalEmwsUrl {#InternalEmwsUrl}
```
public static final int InternalEmwsUrl
```


The internal URL of the Exchange Management Web Services.

### InternalOABUrl {#InternalOABUrl}
```
public static final int InternalOABUrl
```


The internal URL of the Offline Address Book.

### InternalPhotosUrl {#InternalPhotosUrl}
```
public static final int InternalPhotosUrl
```


The internal URL of the Photos service.

### InternalUMUrl {#InternalUMUrl}
```
public static final int InternalUMUrl
```


The internal URL of the Unified Messaging services.

### InternalWebClientUrls {#InternalWebClientUrls}
```
public static final int InternalWebClientUrls
```


The internal URLs of the Exchange web client.

### MailboxDN {#MailboxDN}
```
public static final int MailboxDN
```


The distinguished name of the mailbox database of the user's mailbox.

### PublicFolderServer {#PublicFolderServer}
```
public static final int PublicFolderServer
```


The name of the Public Folders server.

### ActiveDirectoryServer {#ActiveDirectoryServer}
```
public static final int ActiveDirectoryServer
```


The name of the Active Directory server.

### ExternalMailboxServer {#ExternalMailboxServer}
```
public static final int ExternalMailboxServer
```


The name of the RPC over HTTP server.

### ExternalMailboxServerRequiresSSL {#ExternalMailboxServerRequiresSSL}
```
public static final int ExternalMailboxServerRequiresSSL
```


Indicates whether the RPC over HTTP server requires SSL.

### ExternalMailboxServerAuthenticationMethods {#ExternalMailboxServerAuthenticationMethods}
```
public static final int ExternalMailboxServerAuthenticationMethods
```


The authentication methods supported by the RPC over HTTP server.

### EcpVoicemailUrlFragment {#EcpVoicemailUrlFragment}
```
public static final int EcpVoicemailUrlFragment
```


The URL fragment of the Exchange Control Panel for VoiceMail Customization.

### EcpEmailSubscriptionsUrlFragment {#EcpEmailSubscriptionsUrlFragment}
```
public static final int EcpEmailSubscriptionsUrlFragment
```


The URL fragment of the Exchange Control Panel for Email Subscriptions.

### EcpTextMessagingUrlFragment {#EcpTextMessagingUrlFragment}
```
public static final int EcpTextMessagingUrlFragment
```


The URL fragment of the Exchange Control Panel for Text Messaging.

### EcpDeliveryReportUrlFragment {#EcpDeliveryReportUrlFragment}
```
public static final int EcpDeliveryReportUrlFragment
```


The URL fragment of the Exchange Control Panel for Delivery Reports.

### EcpRetentionPolicyTagsUrlFragment {#EcpRetentionPolicyTagsUrlFragment}
```
public static final int EcpRetentionPolicyTagsUrlFragment
```


The URL fragment of the Exchange Control Panel for RetentionPolicy Tags.

### EcpPublishingUrlFragment {#EcpPublishingUrlFragment}
```
public static final int EcpPublishingUrlFragment
```


The URL fragment of the Exchange Control Panel for Publishing.

### EcpPhotoUrlFragment {#EcpPhotoUrlFragment}
```
public static final int EcpPhotoUrlFragment
```


The URL fragment of the Exchange Control Panel for photos.

### EcpConnectUrlFragment {#EcpConnectUrlFragment}
```
public static final int EcpConnectUrlFragment
```


The URL fragment of the Exchange Control Panel for People Connect.

### EcpTeamMailboxUrlFragment {#EcpTeamMailboxUrlFragment}
```
public static final int EcpTeamMailboxUrlFragment
```


The URL fragment of the Exchange Control Panel for Team Mailbox.

### EcpTeamMailboxCreatingUrlFragment {#EcpTeamMailboxCreatingUrlFragment}
```
public static final int EcpTeamMailboxCreatingUrlFragment
```


The URL fragment of the Exchange Control Panel for creating Team Mailbox.

### EcpTeamMailboxEditingUrlFragment {#EcpTeamMailboxEditingUrlFragment}
```
public static final int EcpTeamMailboxEditingUrlFragment
```


The URL fragment of the Exchange Control Panel for editing Team Mailbox.

### EcpExtensionInstallationUrlFragment {#EcpExtensionInstallationUrlFragment}
```
public static final int EcpExtensionInstallationUrlFragment
```


The URL fragment of the Exchange Control Panel for installing extension.

### ExternalEcpUrl {#ExternalEcpUrl}
```
public static final int ExternalEcpUrl
```


The external URL of the Exchange Control Panel.

### ExternalEcpVoicemailUrl {#ExternalEcpVoicemailUrl}
```
public static final int ExternalEcpVoicemailUrl
```


The external URL of the Exchange Control Panel for VoiceMail Customization.

### ExternalEcpEmailSubscriptionsUrl {#ExternalEcpEmailSubscriptionsUrl}
```
public static final int ExternalEcpEmailSubscriptionsUrl
```


The external URL of the Exchange Control Panel for Email Subscriptions.

### ExternalEcpTextMessagingUrl {#ExternalEcpTextMessagingUrl}
```
public static final int ExternalEcpTextMessagingUrl
```


The external URL of the Exchange Control Panel for Text Messaging.

### ExternalEcpDeliveryReportUrl {#ExternalEcpDeliveryReportUrl}
```
public static final int ExternalEcpDeliveryReportUrl
```


The external URL of the Exchange Control Panel for Delivery Reports.

### ExternalEcpRetentionPolicyTagsUrl {#ExternalEcpRetentionPolicyTagsUrl}
```
public static final int ExternalEcpRetentionPolicyTagsUrl
```


The external URL of the Exchange Control Panel for RetentionPolicy Tags.

### ExternalEcpPublishingUrl {#ExternalEcpPublishingUrl}
```
public static final int ExternalEcpPublishingUrl
```


The external URL of the Exchange Control Panel for Publishing.

### ExternalEcpPhotoUrl {#ExternalEcpPhotoUrl}
```
public static final int ExternalEcpPhotoUrl
```


The external URL of the Exchange Control Panel for photos.

### ExternalEcpConnectUrl {#ExternalEcpConnectUrl}
```
public static final int ExternalEcpConnectUrl
```


The external URL of the Exchange Control Panel for People Connect subscriptions.

### ExternalEcpTeamMailboxUrl {#ExternalEcpTeamMailboxUrl}
```
public static final int ExternalEcpTeamMailboxUrl
```


The external URL of the Exchange Control Panel for Team Mailbox.

### ExternalEcpTeamMailboxCreatingUrl {#ExternalEcpTeamMailboxCreatingUrl}
```
public static final int ExternalEcpTeamMailboxCreatingUrl
```


The external URL of the Exchange Control Panel for creating Team Mailbox.

### ExternalEcpTeamMailboxEditingUrl {#ExternalEcpTeamMailboxEditingUrl}
```
public static final int ExternalEcpTeamMailboxEditingUrl
```


The external URL of the Exchange Control Panel for editing Team Mailbox.

### ExternalEcpTeamMailboxHidingUrl {#ExternalEcpTeamMailboxHidingUrl}
```
public static final int ExternalEcpTeamMailboxHidingUrl
```


The external URL of the Exchange Control Panel for hiding Team Mailbox.

### ExternalEcpExtensionInstallationUrl {#ExternalEcpExtensionInstallationUrl}
```
public static final int ExternalEcpExtensionInstallationUrl
```


The external URL of the Exchange Control Panel for the extension installation.

### ExternalEwsUrl {#ExternalEwsUrl}
```
public static final int ExternalEwsUrl
```


The external URL of the Exchange Web Services.

### ExternalEmwsUrl {#ExternalEmwsUrl}
```
public static final int ExternalEmwsUrl
```


The external URL of the Exchange Management Web Services.

### ExternalOABUrl {#ExternalOABUrl}
```
public static final int ExternalOABUrl
```


The external URL of the Offline Address Book.

### ExternalPhotosUrl {#ExternalPhotosUrl}
```
public static final int ExternalPhotosUrl
```


The external URL of the Photos service.

### ExternalUMUrl {#ExternalUMUrl}
```
public static final int ExternalUMUrl
```


The external URL of the Unified Messaging services.

### ExternalWebClientUrls {#ExternalWebClientUrls}
```
public static final int ExternalWebClientUrls
```


The external URLs of the Exchange web client.

### CrossOrganizationSharingEnabled {#CrossOrganizationSharingEnabled}
```
public static final int CrossOrganizationSharingEnabled
```


Indicates that cross-organization sharing is enabled.

### AlternateMailboxes {#AlternateMailboxes}
```
public static final int AlternateMailboxes
```


Collection of alternate mailboxes.

### CasVersion {#CasVersion}
```
public static final int CasVersion
```


The version of the Client Access Server serving the request (e.g. 14.XX.YYY.ZZZ)

### EwsSupportedSchemas {#EwsSupportedSchemas}
```
public static final int EwsSupportedSchemas
```


Comma-separated list of schema versions supported by Exchange Web Services. The schema version values will be the same as the values of the ExchangeServerVersion enumeration.

### InternalPop3Connections {#InternalPop3Connections}
```
public static final int InternalPop3Connections
```


The internal connection settings list for pop protocol

### ExternalPop3Connections {#ExternalPop3Connections}
```
public static final int ExternalPop3Connections
```


The external connection settings list for pop protocol

### InternalImap4Connections {#InternalImap4Connections}
```
public static final int InternalImap4Connections
```


The internal connection settings list for imap4 protocol

### ExternalImap4Connections {#ExternalImap4Connections}
```
public static final int ExternalImap4Connections
```


The external connection settings list for imap4 protocol

### InternalSmtpConnections {#InternalSmtpConnections}
```
public static final int InternalSmtpConnections
```


The internal connection settings list for smtp protocol

### ExternalSmtpConnections {#ExternalSmtpConnections}
```
public static final int ExternalSmtpConnections
```


The external connection settings list for smtp protocol

### InternalServerExclusiveConnect {#InternalServerExclusiveConnect}
```
public static final int InternalServerExclusiveConnect
```


If set to "Off" then clients should not connect via this protocol. The protocol contents are for informational purposes only.

### ExternalEwsVersion {#ExternalEwsVersion}
```
public static final int ExternalEwsVersion
```


The version of the Exchange Web Services server ExternalEwsUrl is pointing to.

### MobileMailboxPolicy {#MobileMailboxPolicy}
```
public static final int MobileMailboxPolicy
```


Mobile Mailbox policy settings.

### DocumentSharingLocations {#DocumentSharingLocations}
```
public static final int DocumentSharingLocations
```


Document sharing locations and their settings.

### UserMSOnline {#UserMSOnline}
```
public static final int UserMSOnline
```


Whether the user account is an MSOnline account.

### InternalMailboxServerAuthenticationMethods {#InternalMailboxServerAuthenticationMethods}
```
public static final int InternalMailboxServerAuthenticationMethods
```


The authentication methods supported by the RPC client server.

### MailboxVersion {#MailboxVersion}
```
public static final int MailboxVersion
```


Version of the server hosting the user's mailbox.

### SPMySiteHostURL {#SPMySiteHostURL}
```
public static final int SPMySiteHostURL
```


Sharepoint MySite Host URL.

### SiteMailboxCreationURL {#SiteMailboxCreationURL}
```
public static final int SiteMailboxCreationURL
```


Site mailbox creation URL in SharePoint. It's used by Outlook to create site mailbox from SharePoint directly.

### InternalRpcHttpServer {#InternalRpcHttpServer}
```
public static final int InternalRpcHttpServer
```


The FQDN of the server used for internal RPC/HTTP connectivity.

### InternalRpcHttpConnectivityRequiresSsl {#InternalRpcHttpConnectivityRequiresSsl}
```
public static final int InternalRpcHttpConnectivityRequiresSsl
```


Indicates whether SSL is required for internal RPC/HTTP connectivity.

### InternalRpcHttpAuthenticationMethod {#InternalRpcHttpAuthenticationMethod}
```
public static final int InternalRpcHttpAuthenticationMethod
```


The authentication method used for internal RPC/HTTP connectivity.

### ExternalServerExclusiveConnect {#ExternalServerExclusiveConnect}
```
public static final int ExternalServerExclusiveConnect
```


If set to "On" then clients should only connect via this protocol.

### ExchangeRpcUrl {#ExchangeRpcUrl}
```
public static final int ExchangeRpcUrl
```


If set, then clients can call the server via XTC

### ShowGalAsDefaultView {#ShowGalAsDefaultView}
```
public static final int ShowGalAsDefaultView
```


If set to false then clients should not show the GAL by default, but show the contact list.

### AutoDiscoverSMTPAddress {#AutoDiscoverSMTPAddress}
```
public static final int AutoDiscoverSMTPAddress
```


AutoDiscover Primary SMTP Address for the user.

### InteropExternalEwsUrl {#InteropExternalEwsUrl}
```
public static final int InteropExternalEwsUrl
```


The 'interop' external URL of the Exchange Web Services. By interop it means a URL to E14 (or later) server that can serve mailboxes that are hosted in downlevel server (E2K3 and earlier).

### InteropExternalEwsVersion {#InteropExternalEwsVersion}
```
public static final int InteropExternalEwsVersion
```


Version of server InteropExternalEwsUrl is pointing to.

### PublicFolderInformation {#PublicFolderInformation}
```
public static final int PublicFolderInformation
```


Public Folder (Hierarchy) information

### RedirectUrl {#RedirectUrl}
```
public static final int RedirectUrl
```


The version appropriate URL of the AutoDiscover service that should answer this query.

### EwsPartnerUrl {#EwsPartnerUrl}
```
public static final int EwsPartnerUrl
```


The URL of the Exchange Web Services for Office365 partners.

### CertPrincipalName {#CertPrincipalName}
```
public static final int CertPrincipalName
```


SSL certificate name

### GroupingInformation {#GroupingInformation}
```
public static final int GroupingInformation
```


The grouping hint for certain clients.

### InternalOutlookServiceUrl {#InternalOutlookServiceUrl}
```
public static final int InternalOutlookServiceUrl
```


Internal OutlookService URL

### ExternalOutlookServiceUrl {#ExternalOutlookServiceUrl}
```
public static final int ExternalOutlookServiceUrl
```


External OutlookService URL

