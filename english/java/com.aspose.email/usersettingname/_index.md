---
title: UserSettingName
second_title: Aspose.Email for Java API Reference
description: User settings that can be requested using GetUserSettings.
type: docs
weight: 700
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
| [ActiveDirectoryServer](#ActiveDirectoryServer) | The name of the Active Directory server. |
| [AlternateMailboxes](#AlternateMailboxes) | Collection of alternate mailboxes. |
| [AutoDiscoverSMTPAddress](#AutoDiscoverSMTPAddress) | AutoDiscover Primary SMTP Address for the user. |
| [CasVersion](#CasVersion) | The version of the Client Access Server serving the request (e.g. |
| [CertPrincipalName](#CertPrincipalName) | SSL certificate name |
| [CrossOrganizationSharingEnabled](#CrossOrganizationSharingEnabled) | Indicates that cross-organization sharing is enabled. |
| [DocumentSharingLocations](#DocumentSharingLocations) | Document sharing locations and their settings. |
| [EcpConnectUrlFragment](#EcpConnectUrlFragment) | The URL fragment of the Exchange Control Panel for People Connect. |
| [EcpDeliveryReportUrlFragment](#EcpDeliveryReportUrlFragment) | The URL fragment of the Exchange Control Panel for Delivery Reports. |
| [EcpEmailSubscriptionsUrlFragment](#EcpEmailSubscriptionsUrlFragment) | The URL fragment of the Exchange Control Panel for Email Subscriptions. |
| [EcpExtensionInstallationUrlFragment](#EcpExtensionInstallationUrlFragment) | The URL fragment of the Exchange Control Panel for installing extension. |
| [EcpPhotoUrlFragment](#EcpPhotoUrlFragment) | The URL fragment of the Exchange Control Panel for photos. |
| [EcpPublishingUrlFragment](#EcpPublishingUrlFragment) | The URL fragment of the Exchange Control Panel for Publishing. |
| [EcpRetentionPolicyTagsUrlFragment](#EcpRetentionPolicyTagsUrlFragment) | The URL fragment of the Exchange Control Panel for RetentionPolicy Tags. |
| [EcpTeamMailboxCreatingUrlFragment](#EcpTeamMailboxCreatingUrlFragment) | The URL fragment of the Exchange Control Panel for creating Team Mailbox. |
| [EcpTeamMailboxEditingUrlFragment](#EcpTeamMailboxEditingUrlFragment) | The URL fragment of the Exchange Control Panel for editing Team Mailbox. |
| [EcpTeamMailboxUrlFragment](#EcpTeamMailboxUrlFragment) | The URL fragment of the Exchange Control Panel for Team Mailbox. |
| [EcpTextMessagingUrlFragment](#EcpTextMessagingUrlFragment) | The URL fragment of the Exchange Control Panel for Text Messaging. |
| [EcpVoicemailUrlFragment](#EcpVoicemailUrlFragment) | The URL fragment of the Exchange Control Panel for VoiceMail Customization. |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [EwsPartnerUrl](#EwsPartnerUrl) | The URL of the Exchange Web Services for Office365 partners. |
| [EwsSupportedSchemas](#EwsSupportedSchemas) | Comma-separated list of schema versions supported by Exchange Web Services. |
| [ExchangeRpcUrl](#ExchangeRpcUrl) | If set, then clients can call the server via XTC |
| [ExternalEcpConnectUrl](#ExternalEcpConnectUrl) | The external URL of the Exchange Control Panel for People Connect subscriptions. |
| [ExternalEcpDeliveryReportUrl](#ExternalEcpDeliveryReportUrl) | The external URL of the Exchange Control Panel for Delivery Reports. |
| [ExternalEcpEmailSubscriptionsUrl](#ExternalEcpEmailSubscriptionsUrl) | The external URL of the Exchange Control Panel for Email Subscriptions. |
| [ExternalEcpExtensionInstallationUrl](#ExternalEcpExtensionInstallationUrl) | The external URL of the Exchange Control Panel for the extension installation. |
| [ExternalEcpPhotoUrl](#ExternalEcpPhotoUrl) | The external URL of the Exchange Control Panel for photos. |
| [ExternalEcpPublishingUrl](#ExternalEcpPublishingUrl) | The external URL of the Exchange Control Panel for Publishing. |
| [ExternalEcpRetentionPolicyTagsUrl](#ExternalEcpRetentionPolicyTagsUrl) | The external URL of the Exchange Control Panel for RetentionPolicy Tags. |
| [ExternalEcpTeamMailboxCreatingUrl](#ExternalEcpTeamMailboxCreatingUrl) | The external URL of the Exchange Control Panel for creating Team Mailbox. |
| [ExternalEcpTeamMailboxEditingUrl](#ExternalEcpTeamMailboxEditingUrl) | The external URL of the Exchange Control Panel for editing Team Mailbox. |
| [ExternalEcpTeamMailboxHidingUrl](#ExternalEcpTeamMailboxHidingUrl) | The external URL of the Exchange Control Panel for hiding Team Mailbox. |
| [ExternalEcpTeamMailboxUrl](#ExternalEcpTeamMailboxUrl) | The external URL of the Exchange Control Panel for Team Mailbox. |
| [ExternalEcpTextMessagingUrl](#ExternalEcpTextMessagingUrl) | The external URL of the Exchange Control Panel for Text Messaging. |
| [ExternalEcpUrl](#ExternalEcpUrl) | The external URL of the Exchange Control Panel. |
| [ExternalEcpVoicemailUrl](#ExternalEcpVoicemailUrl) | The external URL of the Exchange Control Panel for VoiceMail Customization. |
| [ExternalEmwsUrl](#ExternalEmwsUrl) | The external URL of the Exchange Management Web Services. |
| [ExternalEwsUrl](#ExternalEwsUrl) | The external URL of the Exchange Web Services. |
| [ExternalEwsVersion](#ExternalEwsVersion) | The version of the Exchange Web Services server ExternalEwsUrl is pointing to. |
| [ExternalImap4Connections](#ExternalImap4Connections) | The external connection settings list for imap4 protocol |
| [ExternalMailboxServer](#ExternalMailboxServer) | The name of the RPC over HTTP server. |
| [ExternalMailboxServerAuthenticationMethods](#ExternalMailboxServerAuthenticationMethods) | The authentication methods supported by the RPC over HTTP server. |
| [ExternalMailboxServerRequiresSSL](#ExternalMailboxServerRequiresSSL) | Indicates whether the RPC over HTTP server requires SSL. |
| [ExternalOABUrl](#ExternalOABUrl) | The external URL of the Offline Address Book. |
| [ExternalOutlookServiceUrl](#ExternalOutlookServiceUrl) | External OutlookService URL |
| [ExternalPhotosUrl](#ExternalPhotosUrl) | The external URL of the Photos service. |
| [ExternalPop3Connections](#ExternalPop3Connections) | The external connection settings list for pop protocol |
| [ExternalServerExclusiveConnect](#ExternalServerExclusiveConnect) | If set to "On" then clients should only connect via this protocol. |
| [ExternalSmtpConnections](#ExternalSmtpConnections) | The external connection settings list for smtp protocol |
| [ExternalUMUrl](#ExternalUMUrl) | The external URL of the Unified Messaging services. |
| [ExternalWebClientUrls](#ExternalWebClientUrls) | The external URLs of the Exchange web client. |
| [GroupingInformation](#GroupingInformation) | The grouping hint for certain clients. |
| [InternalEcpConnectUrl](#InternalEcpConnectUrl) | The internal URL of the Exchange Control Panel for People Connect subscriptions. |
| [InternalEcpDeliveryReportUrl](#InternalEcpDeliveryReportUrl) | The internal URL of the Exchange Control Panel for Delivery Reports. |
| [InternalEcpEmailSubscriptionsUrl](#InternalEcpEmailSubscriptionsUrl) | The internal URL of the Exchange Control Panel for Email Subscriptions. |
| [InternalEcpExtensionInstallationUrl](#InternalEcpExtensionInstallationUrl) | The internal URL of the Exchange Control Panel for the extension installation. |
| [InternalEcpPhotoUrl](#InternalEcpPhotoUrl) | The internal URL of the Exchange Control Panel for photos. |
| [InternalEcpPublishingUrl](#InternalEcpPublishingUrl) | The internal URL of the Exchange Control Panel for Publishing. |
| [InternalEcpRetentionPolicyTagsUrl](#InternalEcpRetentionPolicyTagsUrl) | The internal URL of the Exchange Control Panel for RetentionPolicy Tags. |
| [InternalEcpTeamMailboxCreatingUrl](#InternalEcpTeamMailboxCreatingUrl) | The internal URL of the Exchange Control Panel for creating Team Mailbox. |
| [InternalEcpTeamMailboxEditingUrl](#InternalEcpTeamMailboxEditingUrl) | The internal URL of the Exchange Control Panel for editing Team Mailbox. |
| [InternalEcpTeamMailboxHidingUrl](#InternalEcpTeamMailboxHidingUrl) | The internal URL of the Exchange Control Panel for hiding Team Mailbox. |
| [InternalEcpTeamMailboxUrl](#InternalEcpTeamMailboxUrl) | The internal URL of the Exchange Control Panel for Team Mailbox. |
| [InternalEcpTextMessagingUrl](#InternalEcpTextMessagingUrl) | The internal URL of the Exchange Control Panel for Text Messaging. |
| [InternalEcpUrl](#InternalEcpUrl) | The internal URL of the Exchange Control Panel. |
| [InternalEcpVoicemailUrl](#InternalEcpVoicemailUrl) | The internal URL of the Exchange Control Panel for VoiceMail Customization. |
| [InternalEmwsUrl](#InternalEmwsUrl) | The internal URL of the Exchange Management Web Services. |
| [InternalEwsUrl](#InternalEwsUrl) | The internal URL of the Exchange Web Services. |
| [InternalImap4Connections](#InternalImap4Connections) | The internal connection settings list for imap4 protocol |
| [InternalMailboxServer](#InternalMailboxServer) | The fully qualified domain name of the mailbox server. |
| [InternalMailboxServerAuthenticationMethods](#InternalMailboxServerAuthenticationMethods) | The authentication methods supported by the RPC client server. |
| [InternalMailboxServerDN](#InternalMailboxServerDN) | The legacy distinguished name of the mailbox server. |
| [InternalOABUrl](#InternalOABUrl) | The internal URL of the Offline Address Book. |
| [InternalOutlookServiceUrl](#InternalOutlookServiceUrl) | Internal OutlookService URL |
| [InternalPhotosUrl](#InternalPhotosUrl) | The internal URL of the Photos service. |
| [InternalPop3Connections](#InternalPop3Connections) | The internal connection settings list for pop protocol |
| [InternalRpcClientServer](#InternalRpcClientServer) | The fully qualified domain name of the RPC client server. |
| [InternalRpcHttpAuthenticationMethod](#InternalRpcHttpAuthenticationMethod) | The authentication method used for internal RPC/HTTP connectivity. |
| [InternalRpcHttpConnectivityRequiresSsl](#InternalRpcHttpConnectivityRequiresSsl) | Indicates whether SSL is required for internal RPC/HTTP connectivity. |
| [InternalRpcHttpServer](#InternalRpcHttpServer) | The FQDN of the server used for internal RPC/HTTP connectivity. |
| [InternalServerExclusiveConnect](#InternalServerExclusiveConnect) | If set to "Off" then clients should not connect via this protocol. |
| [InternalSmtpConnections](#InternalSmtpConnections) | The internal connection settings list for smtp protocol |
| [InternalUMUrl](#InternalUMUrl) | The internal URL of the Unified Messaging services. |
| [InternalWebClientUrls](#InternalWebClientUrls) | The internal URLs of the Exchange web client. |
| [InteropExternalEwsUrl](#InteropExternalEwsUrl) | The 'interop' external URL of the Exchange Web Services. |
| [InteropExternalEwsVersion](#InteropExternalEwsVersion) | Version of server InteropExternalEwsUrl is pointing to. |
| [MailboxDN](#MailboxDN) | The distinguished name of the mailbox database of the user's mailbox. |
| [MailboxVersion](#MailboxVersion) | Version of the server hosting the user's mailbox. |
| [MobileMailboxPolicy](#MobileMailboxPolicy) | Mobile Mailbox policy settings. |
| [PublicFolderInformation](#PublicFolderInformation) | Public Folder (Hierarchy) information |
| [PublicFolderServer](#PublicFolderServer) | The name of the Public Folders server. |
| [RedirectUrl](#RedirectUrl) | The version appropriate URL of the AutoDiscover service that should answer this query. |
| [SPMySiteHostURL](#SPMySiteHostURL) | Sharepoint MySite Host URL. |
| [ShowGalAsDefaultView](#ShowGalAsDefaultView) | If set to false then clients should not show the GAL by default, but show the contact list. |
| [SiteMailboxCreationURL](#SiteMailboxCreationURL) | Site mailbox creation URL in SharePoint. |
| [UserDN](#UserDN) | The legacy distinguished name of the user. |
| [UserDeploymentId](#UserDeploymentId) | The deployment Id of the user. |
| [UserDisplayName](#UserDisplayName) | The display name of the user. |
| [UserMSOnline](#UserMSOnline) | Whether the user account is an MSOnline account. |
## Methods

| Method | Description |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(System.Enum arg0)](#CloneTo-com.aspose.ms.System.Enum-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [format(System.Type arg0, Object arg1, String arg2)](#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-) |  |
| [format(Class<?> arg0, long arg1, String arg2)](#format-java.lang.Class----long-java.lang.String-) |  |
| [getClass()](#getClass--) |  |
| [getName(System.Type arg0, Object arg1)](#getName-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [getName(Class<?> arg0, long arg1)](#getName-java.lang.Class----long-) |  |
| [getNames(System.Type arg0)](#getNames-com.aspose.ms.System.Type-) |  |
| [getNames(Class<?> arg0)](#getNames-java.lang.Class----) |  |
| [getUnderlyingType(System.Type arg0)](#getUnderlyingType-com.aspose.ms.System.Type-) |  |
| [getUnderlyingType(Class<?> arg0)](#getUnderlyingType-java.lang.Class----) |  |
| [getValue(Class<?> arg0, String arg1)](#getValue-java.lang.Class----java.lang.String-) |  |
| [getValues(System.Type arg0)](#getValues-com.aspose.ms.System.Type-) |  |
| [get_Caption()](#get-Caption--) |  |
| [get_Value()](#get-Value--) |  |
| [hashCode()](#hashCode--) |  |
| [isDefined(System.Type arg0, Object arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [isDefined(System.Type arg0, String arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.String-) |  |
| [isDefined(System.Type arg0, long arg1)](#isDefined-com.aspose.ms.System.Type-long-) |  |
| [isDefined(Class<?> arg0, long arg1)](#isDefined-java.lang.Class----long-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(System.Type arg0, String arg1)](#parse-com.aspose.ms.System.Type-java.lang.String-) |  |
| [parse(System.Type arg0, String arg1, Boolean arg2)](#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-) |  |
| [parse(Class<?> arg0, String arg1)](#parse-java.lang.Class----java.lang.String-) |  |
| [parse(Class<?> arg0, String arg1, Boolean arg2)](#parse-java.lang.Class----java.lang.String-java.lang.Boolean-) |  |
| [register(System.Enum.AbstractEnum arg0)](#register-com.aspose.ms.System.Enum.AbstractEnum-) |  |
| [toObject(System.Type arg0, Object arg1)](#toObject-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [toString()](#toString--) |  |
| [toString(Class<?> arg0, long arg1)](#toString-java.lang.Class----long-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ActiveDirectoryServer {#ActiveDirectoryServer}
```
public static final int ActiveDirectoryServer
```


The name of the Active Directory server.

### AlternateMailboxes {#AlternateMailboxes}
```
public static final int AlternateMailboxes
```


Collection of alternate mailboxes.

### AutoDiscoverSMTPAddress {#AutoDiscoverSMTPAddress}
```
public static final int AutoDiscoverSMTPAddress
```


AutoDiscover Primary SMTP Address for the user.

### CasVersion {#CasVersion}
```
public static final int CasVersion
```


The version of the Client Access Server serving the request (e.g. 14.XX.YYY.ZZZ)

### CertPrincipalName {#CertPrincipalName}
```
public static final int CertPrincipalName
```


SSL certificate name

### CrossOrganizationSharingEnabled {#CrossOrganizationSharingEnabled}
```
public static final int CrossOrganizationSharingEnabled
```


Indicates that cross-organization sharing is enabled.

### DocumentSharingLocations {#DocumentSharingLocations}
```
public static final int DocumentSharingLocations
```


Document sharing locations and their settings.

### EcpConnectUrlFragment {#EcpConnectUrlFragment}
```
public static final int EcpConnectUrlFragment
```


The URL fragment of the Exchange Control Panel for People Connect.

### EcpDeliveryReportUrlFragment {#EcpDeliveryReportUrlFragment}
```
public static final int EcpDeliveryReportUrlFragment
```


The URL fragment of the Exchange Control Panel for Delivery Reports.

### EcpEmailSubscriptionsUrlFragment {#EcpEmailSubscriptionsUrlFragment}
```
public static final int EcpEmailSubscriptionsUrlFragment
```


The URL fragment of the Exchange Control Panel for Email Subscriptions.

### EcpExtensionInstallationUrlFragment {#EcpExtensionInstallationUrlFragment}
```
public static final int EcpExtensionInstallationUrlFragment
```


The URL fragment of the Exchange Control Panel for installing extension.

### EcpPhotoUrlFragment {#EcpPhotoUrlFragment}
```
public static final int EcpPhotoUrlFragment
```


The URL fragment of the Exchange Control Panel for photos.

### EcpPublishingUrlFragment {#EcpPublishingUrlFragment}
```
public static final int EcpPublishingUrlFragment
```


The URL fragment of the Exchange Control Panel for Publishing.

### EcpRetentionPolicyTagsUrlFragment {#EcpRetentionPolicyTagsUrlFragment}
```
public static final int EcpRetentionPolicyTagsUrlFragment
```


The URL fragment of the Exchange Control Panel for RetentionPolicy Tags.

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

### EcpTeamMailboxUrlFragment {#EcpTeamMailboxUrlFragment}
```
public static final int EcpTeamMailboxUrlFragment
```


The URL fragment of the Exchange Control Panel for Team Mailbox.

### EcpTextMessagingUrlFragment {#EcpTextMessagingUrlFragment}
```
public static final int EcpTextMessagingUrlFragment
```


The URL fragment of the Exchange Control Panel for Text Messaging.

### EcpVoicemailUrlFragment {#EcpVoicemailUrlFragment}
```
public static final int EcpVoicemailUrlFragment
```


The URL fragment of the Exchange Control Panel for VoiceMail Customization.

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### EwsPartnerUrl {#EwsPartnerUrl}
```
public static final int EwsPartnerUrl
```


The URL of the Exchange Web Services for Office365 partners.

### EwsSupportedSchemas {#EwsSupportedSchemas}
```
public static final int EwsSupportedSchemas
```


Comma-separated list of schema versions supported by Exchange Web Services. The schema version values will be the same as the values of the ExchangeServerVersion enumeration.

### ExchangeRpcUrl {#ExchangeRpcUrl}
```
public static final int ExchangeRpcUrl
```


If set, then clients can call the server via XTC

### ExternalEcpConnectUrl {#ExternalEcpConnectUrl}
```
public static final int ExternalEcpConnectUrl
```


The external URL of the Exchange Control Panel for People Connect subscriptions.

### ExternalEcpDeliveryReportUrl {#ExternalEcpDeliveryReportUrl}
```
public static final int ExternalEcpDeliveryReportUrl
```


The external URL of the Exchange Control Panel for Delivery Reports.

### ExternalEcpEmailSubscriptionsUrl {#ExternalEcpEmailSubscriptionsUrl}
```
public static final int ExternalEcpEmailSubscriptionsUrl
```


The external URL of the Exchange Control Panel for Email Subscriptions.

### ExternalEcpExtensionInstallationUrl {#ExternalEcpExtensionInstallationUrl}
```
public static final int ExternalEcpExtensionInstallationUrl
```


The external URL of the Exchange Control Panel for the extension installation.

### ExternalEcpPhotoUrl {#ExternalEcpPhotoUrl}
```
public static final int ExternalEcpPhotoUrl
```


The external URL of the Exchange Control Panel for photos.

### ExternalEcpPublishingUrl {#ExternalEcpPublishingUrl}
```
public static final int ExternalEcpPublishingUrl
```


The external URL of the Exchange Control Panel for Publishing.

### ExternalEcpRetentionPolicyTagsUrl {#ExternalEcpRetentionPolicyTagsUrl}
```
public static final int ExternalEcpRetentionPolicyTagsUrl
```


The external URL of the Exchange Control Panel for RetentionPolicy Tags.

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

### ExternalEcpTeamMailboxUrl {#ExternalEcpTeamMailboxUrl}
```
public static final int ExternalEcpTeamMailboxUrl
```


The external URL of the Exchange Control Panel for Team Mailbox.

### ExternalEcpTextMessagingUrl {#ExternalEcpTextMessagingUrl}
```
public static final int ExternalEcpTextMessagingUrl
```


The external URL of the Exchange Control Panel for Text Messaging.

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

### ExternalEmwsUrl {#ExternalEmwsUrl}
```
public static final int ExternalEmwsUrl
```


The external URL of the Exchange Management Web Services.

### ExternalEwsUrl {#ExternalEwsUrl}
```
public static final int ExternalEwsUrl
```


The external URL of the Exchange Web Services.

### ExternalEwsVersion {#ExternalEwsVersion}
```
public static final int ExternalEwsVersion
```


The version of the Exchange Web Services server ExternalEwsUrl is pointing to.

### ExternalImap4Connections {#ExternalImap4Connections}
```
public static final int ExternalImap4Connections
```


The external connection settings list for imap4 protocol

### ExternalMailboxServer {#ExternalMailboxServer}
```
public static final int ExternalMailboxServer
```


The name of the RPC over HTTP server.

### ExternalMailboxServerAuthenticationMethods {#ExternalMailboxServerAuthenticationMethods}
```
public static final int ExternalMailboxServerAuthenticationMethods
```


The authentication methods supported by the RPC over HTTP server.

### ExternalMailboxServerRequiresSSL {#ExternalMailboxServerRequiresSSL}
```
public static final int ExternalMailboxServerRequiresSSL
```


Indicates whether the RPC over HTTP server requires SSL.

### ExternalOABUrl {#ExternalOABUrl}
```
public static final int ExternalOABUrl
```


The external URL of the Offline Address Book.

### ExternalOutlookServiceUrl {#ExternalOutlookServiceUrl}
```
public static final int ExternalOutlookServiceUrl
```


External OutlookService URL

### ExternalPhotosUrl {#ExternalPhotosUrl}
```
public static final int ExternalPhotosUrl
```


The external URL of the Photos service.

### ExternalPop3Connections {#ExternalPop3Connections}
```
public static final int ExternalPop3Connections
```


The external connection settings list for pop protocol

### ExternalServerExclusiveConnect {#ExternalServerExclusiveConnect}
```
public static final int ExternalServerExclusiveConnect
```


If set to "On" then clients should only connect via this protocol.

### ExternalSmtpConnections {#ExternalSmtpConnections}
```
public static final int ExternalSmtpConnections
```


The external connection settings list for smtp protocol

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

### GroupingInformation {#GroupingInformation}
```
public static final int GroupingInformation
```


The grouping hint for certain clients.

### InternalEcpConnectUrl {#InternalEcpConnectUrl}
```
public static final int InternalEcpConnectUrl
```


The internal URL of the Exchange Control Panel for People Connect subscriptions.

### InternalEcpDeliveryReportUrl {#InternalEcpDeliveryReportUrl}
```
public static final int InternalEcpDeliveryReportUrl
```


The internal URL of the Exchange Control Panel for Delivery Reports.

### InternalEcpEmailSubscriptionsUrl {#InternalEcpEmailSubscriptionsUrl}
```
public static final int InternalEcpEmailSubscriptionsUrl
```


The internal URL of the Exchange Control Panel for Email Subscriptions.

### InternalEcpExtensionInstallationUrl {#InternalEcpExtensionInstallationUrl}
```
public static final int InternalEcpExtensionInstallationUrl
```


The internal URL of the Exchange Control Panel for the extension installation.

### InternalEcpPhotoUrl {#InternalEcpPhotoUrl}
```
public static final int InternalEcpPhotoUrl
```


The internal URL of the Exchange Control Panel for photos.

### InternalEcpPublishingUrl {#InternalEcpPublishingUrl}
```
public static final int InternalEcpPublishingUrl
```


The internal URL of the Exchange Control Panel for Publishing.

### InternalEcpRetentionPolicyTagsUrl {#InternalEcpRetentionPolicyTagsUrl}
```
public static final int InternalEcpRetentionPolicyTagsUrl
```


The internal URL of the Exchange Control Panel for RetentionPolicy Tags.

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

### InternalEcpTeamMailboxUrl {#InternalEcpTeamMailboxUrl}
```
public static final int InternalEcpTeamMailboxUrl
```


The internal URL of the Exchange Control Panel for Team Mailbox.

### InternalEcpTextMessagingUrl {#InternalEcpTextMessagingUrl}
```
public static final int InternalEcpTextMessagingUrl
```


The internal URL of the Exchange Control Panel for Text Messaging.

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

### InternalEmwsUrl {#InternalEmwsUrl}
```
public static final int InternalEmwsUrl
```


The internal URL of the Exchange Management Web Services.

### InternalEwsUrl {#InternalEwsUrl}
```
public static final int InternalEwsUrl
```


The internal URL of the Exchange Web Services.

### InternalImap4Connections {#InternalImap4Connections}
```
public static final int InternalImap4Connections
```


The internal connection settings list for imap4 protocol

### InternalMailboxServer {#InternalMailboxServer}
```
public static final int InternalMailboxServer
```


The fully qualified domain name of the mailbox server.

### InternalMailboxServerAuthenticationMethods {#InternalMailboxServerAuthenticationMethods}
```
public static final int InternalMailboxServerAuthenticationMethods
```


The authentication methods supported by the RPC client server.

### InternalMailboxServerDN {#InternalMailboxServerDN}
```
public static final int InternalMailboxServerDN
```


The legacy distinguished name of the mailbox server.

### InternalOABUrl {#InternalOABUrl}
```
public static final int InternalOABUrl
```


The internal URL of the Offline Address Book.

### InternalOutlookServiceUrl {#InternalOutlookServiceUrl}
```
public static final int InternalOutlookServiceUrl
```


Internal OutlookService URL

### InternalPhotosUrl {#InternalPhotosUrl}
```
public static final int InternalPhotosUrl
```


The internal URL of the Photos service.

### InternalPop3Connections {#InternalPop3Connections}
```
public static final int InternalPop3Connections
```


The internal connection settings list for pop protocol

### InternalRpcClientServer {#InternalRpcClientServer}
```
public static final int InternalRpcClientServer
```


The fully qualified domain name of the RPC client server.

### InternalRpcHttpAuthenticationMethod {#InternalRpcHttpAuthenticationMethod}
```
public static final int InternalRpcHttpAuthenticationMethod
```


The authentication method used for internal RPC/HTTP connectivity.

### InternalRpcHttpConnectivityRequiresSsl {#InternalRpcHttpConnectivityRequiresSsl}
```
public static final int InternalRpcHttpConnectivityRequiresSsl
```


Indicates whether SSL is required for internal RPC/HTTP connectivity.

### InternalRpcHttpServer {#InternalRpcHttpServer}
```
public static final int InternalRpcHttpServer
```


The FQDN of the server used for internal RPC/HTTP connectivity.

### InternalServerExclusiveConnect {#InternalServerExclusiveConnect}
```
public static final int InternalServerExclusiveConnect
```


If set to "Off" then clients should not connect via this protocol. The protocol contents are for informational purposes only.

### InternalSmtpConnections {#InternalSmtpConnections}
```
public static final int InternalSmtpConnections
```


The internal connection settings list for smtp protocol

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

### MailboxDN {#MailboxDN}
```
public static final int MailboxDN
```


The distinguished name of the mailbox database of the user's mailbox.

### MailboxVersion {#MailboxVersion}
```
public static final int MailboxVersion
```


Version of the server hosting the user's mailbox.

### MobileMailboxPolicy {#MobileMailboxPolicy}
```
public static final int MobileMailboxPolicy
```


Mobile Mailbox policy settings.

### PublicFolderInformation {#PublicFolderInformation}
```
public static final int PublicFolderInformation
```


Public Folder (Hierarchy) information

### PublicFolderServer {#PublicFolderServer}
```
public static final int PublicFolderServer
```


The name of the Public Folders server.

### RedirectUrl {#RedirectUrl}
```
public static final int RedirectUrl
```


The version appropriate URL of the AutoDiscover service that should answer this query.

### SPMySiteHostURL {#SPMySiteHostURL}
```
public static final int SPMySiteHostURL
```


Sharepoint MySite Host URL.

### ShowGalAsDefaultView {#ShowGalAsDefaultView}
```
public static final int ShowGalAsDefaultView
```


If set to false then clients should not show the GAL by default, but show the contact list.

### SiteMailboxCreationURL {#SiteMailboxCreationURL}
```
public static final int SiteMailboxCreationURL
```


Site mailbox creation URL in SharePoint. It's used by Outlook to create site mailbox from SharePoint directly.

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

### UserDisplayName {#UserDisplayName}
```
public static final int UserDisplayName
```


The display name of the user.

### UserMSOnline {#UserMSOnline}
```
public static final int UserMSOnline
```


Whether the user account is an MSOnline account.

### Clone() {#Clone--}
```
public System.Enum Clone()
```




**Returns:**
com.aspose.ms.System.Enum
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### format(Class<?> arg0, long arg1, String arg2) {#format-java.lang.Class----long-java.lang.String-}
```
public static String format(Class<?> arg0, long arg1, String arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getName(System.Type arg0, Object arg1) {#getName-com.aspose.ms.System.Type-java.lang.Object-}
```
public static String getName(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.String
### getName(Class<?> arg0, long arg1) {#getName-java.lang.Class----long-}
```
public static String getName(Class<?> arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
java.lang.String
### getNames(System.Type arg0) {#getNames-com.aspose.ms.System.Type-}
```
public static String[] getNames(System.Type arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### getValues(System.Type arg0) {#getValues-com.aspose.ms.System.Type-}
```
public static System.Array getValues(System.Type arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Array
### get_Caption() {#get-Caption--}
```
public String get_Caption()
```




**Returns:**
java.lang.String
### get_Value() {#get-Value--}
```
public long get_Value()
```




**Returns:**
long
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDefined(System.Type arg0, Object arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.Object-}
```
public static boolean isDefined(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
boolean
### isDefined(System.Type arg0, String arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
boolean
### isDefined(System.Type arg0, long arg1) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | long |  |

**Returns:**
boolean
### isDefined(Class<?> arg0, long arg1) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parse(System.Type arg0, String arg1) {#parse-com.aspose.ms.System.Type-java.lang.String-}
```
public static long parse(System.Type arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(System.Type arg0, String arg1, Boolean arg2) {#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-}
```
public static long parse(System.Type arg0, String arg1, Boolean arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1) {#parse-java.lang.Class----java.lang.String-}
```
public static long parse(Class<?> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1, Boolean arg2) {#parse-java.lang.Class----java.lang.String-java.lang.Boolean-}
```
public static long parse(Class<?> arg0, String arg1, Boolean arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### register(System.Enum.AbstractEnum arg0) {#register-com.aspose.ms.System.Enum.AbstractEnum-}
```
public static void register(System.Enum.AbstractEnum arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toString(Class<?> arg0, long arg1) {#toString-java.lang.Class----long-}
```
public static String toString(Class<?> arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

