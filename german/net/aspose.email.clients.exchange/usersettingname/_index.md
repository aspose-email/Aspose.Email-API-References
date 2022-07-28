---
title: UserSettingName
second_title: Aspose.Email für .NET-API-Referenz
description: Benutzereinstellungen die mit GetUserSettings angefordert werden können.
type: docs
weight: 3600
url: /de/net/aspose.email.clients.exchange/usersettingname/
---
## UserSettingName enumeration

Benutzereinstellungen, die mit GetUserSettings angefordert werden können.

```csharp
public enum UserSettingName
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| UserDisplayName | `0` | Der Anzeigename des Benutzers. |
| UserDN | `1` | Der Legacy Distinguished Name des Benutzers. |
| UserDeploymentId | `2` | Die Bereitstellungs-ID des Benutzers. |
| InternalMailboxServer | `3` | Der vollständig qualifizierte Domänenname des Postfachservers. |
| InternalRpcClientServer | `4` | Der vollständig qualifizierte Domänenname des RPC-Client-Servers. |
| InternalMailboxServerDN | `5` | Der Legacy Distinguished Name des Postfachservers. |
| InternalEcpUrl | `6` | Die interne URL der Exchange-Systemsteuerung. |
| InternalEcpVoicemailUrl | `7` | Die interne URL der Exchange-Systemsteuerung für die VoiceMail-Anpassung. |
| InternalEcpEmailSubscriptionsUrl | `8` | Die interne URL der Exchange-Systemsteuerung für E-Mail-Abonnements. |
| InternalEcpTextMessagingUrl | `9` | Die interne URL der Exchange-Systemsteuerung für Textnachrichten. |
| InternalEcpDeliveryReportUrl | `10` | Die interne URL der Exchange-Systemsteuerung für Übermittlungsberichte. |
| InternalEcpRetentionPolicyTagsUrl | `11` | Die interne URL der Exchange-Systemsteuerung für RetentionPolicy-Tags. |
| InternalEcpPublishingUrl | `12` | Die interne URL der Exchange-Systemsteuerung zum Veröffentlichen. |
| InternalEcpPhotoUrl | `13` | Die interne URL der Exchange-Systemsteuerung für Fotos. |
| InternalEcpConnectUrl | `14` | Die interne URL der Exchange-Systemsteuerung für People Connect-Abonnements. |
| InternalEcpTeamMailboxUrl | `15` | Die interne URL der Exchange-Systemsteuerung für das Team-Postfach. |
| InternalEcpTeamMailboxCreatingUrl | `16` | Die interne URL der Exchange-Systemsteuerung zum Erstellen von Teampostfächern. |
| InternalEcpTeamMailboxEditingUrl | `17` | Die interne URL der Exchange-Systemsteuerung zum Bearbeiten des Teampostfachs. |
| InternalEcpTeamMailboxHidingUrl | `18` | Die interne URL der Exchange-Systemsteuerung zum Ausblenden des Teampostfachs. |
| InternalEcpExtensionInstallationUrl | `19` | Die interne URL der Exchange-Systemsteuerung für die Erweiterungsinstallation. |
| InternalEwsUrl | `20` | Die interne URL der Exchange-Webdienste. |
| InternalEmwsUrl | `21` | Die interne URL der Exchange-Verwaltungswebdienste. |
| InternalOABUrl | `22` | Die interne URL des Offline-Adressbuchs. |
| InternalPhotosUrl | `23` | Die interne URL des Fotos-Dienstes. |
| InternalUMUrl | `24` | Die interne URL der Unified Messaging-Dienste. |
| InternalWebClientUrls | `25` | Die internen URLs des Exchange-Webclients. |
| MailboxDN | `26` | Der Distinguished Name der Postfachdatenbank des Postfachs des Benutzers. |
| PublicFolderServer | `27` | Der Name des Servers für öffentliche Ordner. |
| ActiveDirectoryServer | `28` | Der Name des Active Directory-Servers. |
| ExternalMailboxServer | `29` | Der Name des RPC-über-HTTP-Servers. |
| ExternalMailboxServerRequiresSSL | `30` | Gibt an, ob der RPC-über-HTTP-Server SSL erfordert. |
| ExternalMailboxServerAuthenticationMethods | `31` | Die vom RPC-über-HTTP-Server unterstützten Authentifizierungsmethoden. |
| EcpVoicemailUrlFragment | `32` | Das URL-Fragment der Exchange-Systemsteuerung für die VoiceMail-Anpassung. |
| EcpEmailSubscriptionsUrlFragment | `33` | Das URL-Fragment der Exchange-Systemsteuerung für E-Mail-Abonnements. |
| EcpTextMessagingUrlFragment | `34` | Das URL-Fragment der Exchange-Systemsteuerung für Textnachrichten. |
| EcpDeliveryReportUrlFragment | `35` | Das URL-Fragment der Exchange-Systemsteuerung für Übermittlungsberichte. |
| EcpRetentionPolicyTagsUrlFragment | `36` | Das URL-Fragment der Exchange-Systemsteuerung für RetentionPolicy-Tags. |
| EcpPublishingUrlFragment | `37` | Das URL-Fragment der Exchange-Systemsteuerung für die Veröffentlichung. |
| EcpPhotoUrlFragment | `38` | Das URL-Fragment der Exchange-Systemsteuerung für Fotos. |
| EcpConnectUrlFragment | `39` | Das URL-Fragment der Exchange-Systemsteuerung für People Connect. |
| EcpTeamMailboxUrlFragment | `40` | Das URL-Fragment der Exchange-Systemsteuerung für das Team-Postfach. |
| EcpTeamMailboxCreatingUrlFragment | `41` | Das URL-Fragment der Exchange-Systemsteuerung zum Erstellen von Team-Postfächern. |
| EcpTeamMailboxEditingUrlFragment | `42` | Das URL-Fragment der Exchange-Systemsteuerung zum Bearbeiten des Teampostfachs. |
| EcpExtensionInstallationUrlFragment | `43` | Das URL-Fragment der Exchange-Systemsteuerung zum Installieren der Erweiterung. |
| ExternalEcpUrl | `44` | Die externe URL der Exchange-Systemsteuerung. |
| ExternalEcpVoicemailUrl | `45` | Die externe URL der Exchange-Systemsteuerung für die VoiceMail-Anpassung. |
| ExternalEcpEmailSubscriptionsUrl | `46` | Die externe URL der Exchange-Systemsteuerung für E-Mail-Abonnements. |
| ExternalEcpTextMessagingUrl | `47` | Die externe URL der Exchange-Systemsteuerung für Textnachrichten. |
| ExternalEcpDeliveryReportUrl | `48` | Die externe URL der Exchange-Systemsteuerung für Übermittlungsberichte. |
| ExternalEcpRetentionPolicyTagsUrl | `49` | Die externe URL der Exchange-Systemsteuerung für RetentionPolicy-Tags. |
| ExternalEcpPublishingUrl | `50` | Die externe URL der Exchange-Systemsteuerung zum Veröffentlichen. |
| ExternalEcpPhotoUrl | `51` | Die externe URL der Exchange-Systemsteuerung für Fotos. |
| ExternalEcpConnectUrl | `52` | Die externe URL der Exchange-Systemsteuerung für People Connect-Abonnements. |
| ExternalEcpTeamMailboxUrl | `53` | Die externe URL der Exchange-Systemsteuerung für das Teampostfach. |
| ExternalEcpTeamMailboxCreatingUrl | `54` | Die externe URL der Exchange-Systemsteuerung zum Erstellen des Teampostfachs. |
| ExternalEcpTeamMailboxEditingUrl | `55` | Die externe URL der Exchange-Systemsteuerung zum Bearbeiten des Teampostfachs. |
| ExternalEcpTeamMailboxHidingUrl | `56` | Die externe URL der Exchange-Systemsteuerung zum Ausblenden des Teampostfachs. |
| ExternalEcpExtensionInstallationUrl | `57` | Die externe URL der Exchange-Systemsteuerung für die Erweiterungsinstallation. |
| ExternalEwsUrl | `58` | Die externe URL der Exchange-Webdienste. |
| ExternalEmwsUrl | `59` | Die externe URL der Exchange-Verwaltungswebdienste. |
| ExternalOABUrl | `60` | Die externe URL des Offline-Adressbuchs. |
| ExternalPhotosUrl | `61` | Die externe URL des Fotos-Dienstes. |
| ExternalUMUrl | `62` | Die externe URL der Unified Messaging-Dienste. |
| ExternalWebClientUrls | `63` | Die externen URLs des Exchange-Webclients. |
| CrossOrganizationSharingEnabled | `64` | Gibt an, dass die organisationsübergreifende Freigabe aktiviert ist. |
| AlternateMailboxes | `65` | Sammlung alternativer Postfächer. |
| CasVersion | `66` | Die Version des Clientzugriffsservers, der die Anfrage bedient (z. B. 14.XX.YYY.ZZZ) |
| EwsSupportedSchemas | `67` | Durch Kommas getrennte Liste von Schemaversionen, die von Exchange-Webdiensten unterstützt werden. Die Schemaversion values sind die gleichen wie die Werte der ExchangeServerVersion-Enumeration. |
| InternalPop3Connections | `68` | Die Liste der internen Verbindungseinstellungen für das Pop-Protokoll |
| ExternalPop3Connections | `69` | Die Liste der externen Verbindungseinstellungen für das Pop-Protokoll |
| InternalImap4Connections | `70` | Die Liste der internen Verbindungseinstellungen für das imap4-Protokoll |
| ExternalImap4Connections | `71` | Die Liste der externen Verbindungseinstellungen für das imap4-Protokoll |
| InternalSmtpConnections | `72` | Die Liste der internen Verbindungseinstellungen für das SMTP-Protokoll |
| ExternalSmtpConnections | `73` | Die Liste der externen Verbindungseinstellungen für das SMTP-Protokoll |
| InternalServerExclusiveConnect | `74` | Wenn auf „Off“ gesetzt, sollten sich Clients nicht über dieses Protokoll verbinden. Der Inhalt des Protokolls dient nur zu Informationszwecken. |
| ExternalEwsVersion | `75` | Die Version des Exchange Web Services-Servers ExternalEwsUrl zeigt auf. |
| MobileMailboxPolicy | `76` | Richtlinieneinstellungen für mobile Postfächer. |
| DocumentSharingLocations | `77` | Dokumentfreigabeorte und ihre Einstellungen. |
| UserMSOnline | `78` | Ob das Benutzerkonto ein MSOnline-Konto ist. |
| InternalMailboxServerAuthenticationMethods | `79` | Die vom RPC-Client-Server unterstützten Authentifizierungsmethoden. |
| MailboxVersion | `80` | Version des Servers, der das Postfach des Benutzers hostet. |
| SPMySiteHostURL | `81` | Sharepoint MySite-Host-URL. |
| SiteMailboxCreationURL | `82` | URL zum Erstellen von Websitepostfächern in SharePoint. Wird von Outlook verwendet, um Websitepostfächer direkt aus SharePoint zu erstellen. |
| InternalRpcHttpServer | `83` | Der FQDN des Servers, der für die interne RPC/HTTP-Konnektivität verwendet wird. |
| InternalRpcHttpConnectivityRequiresSsl | `84` | Gibt an, ob SSL für die interne RPC/HTTP-Konnektivität erforderlich ist. |
| InternalRpcHttpAuthenticationMethod | `85` | Die für die interne RPC/HTTP-Konnektivität verwendete Authentifizierungsmethode. |
| ExternalServerExclusiveConnect | `86` | Wenn auf „On“ gesetzt, sollten sich Clients nur über dieses Protokoll verbinden. |
| ExchangeRpcUrl | `87` | Wenn gesetzt, dann können Clients den Server über XTC anrufen |
| ShowGalAsDefaultView | `88` | Wenn auf „false“ gesetzt, sollten Clients standardmäßig nicht die GAL, sondern die Kontaktliste anzeigen. |
| AutoDiscoverSMTPAddress | `89` | AutoDiscover Primäre SMTP-Adresse für den Benutzer. |
| InteropExternalEwsUrl | `90` | Die externe „Interop“-URL der Exchange-Webdienste. Mit Interop ist eine URL zu einem E14-Server (oder höher) gemeint, der Mailboxen bedienen kann , die auf einem Downlevel-Server (E2K3 und früher) gehostet werden. |
| InteropExternalEwsVersion | `91` | Version des Servers InteropExternalEwsUrl zeigt auf. |
| PublicFolderInformation | `92` | Informationen zu öffentlichen Ordnern (Hierarchie) |
| RedirectUrl | `93` | Die zur Version passende URL des AutoDiscover-Dienstes, der diese Abfrage beantworten soll. |
| EwsPartnerUrl | `94` | Die URL der Exchange-Webdienste für Office365-Partner. |
| CertPrincipalName | `95` | Name des SSL-Zertifikats |
| GroupingInformation | `96` | Der Gruppierungshinweis für bestimmte Clients. |
| InternalOutlookServiceUrl | `98` | Interne OutlookService-URL |
| ExternalOutlookServiceUrl | `99` | URL des externen Outlook-Dienstes |

### Bemerkungen

Neue Werte am Ende hinzufügen und mit Microsoft.Exchange.Autodiscover.ConfigurationSettings.UserConfigurationSettingName. synchronisieren

### Siehe auch

* namensraum [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* Montage [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
