---
title: UserSettingName
second_title: Aspose.Email för .NET API-referens
description: Användarinställningar som kan begäras med GetUserSettings.
type: docs
weight: 3600
url: /sv/net/aspose.email.clients.exchange/usersettingname/
---
## UserSettingName enumeration

Användarinställningar som kan begäras med GetUserSettings.

```csharp
public enum UserSettingName
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| UserDisplayName | `0` | Användarens visningsnamn. |
| UserDN | `1` | Det äldre distinguerade namnet på användaren. |
| UserDeploymentId | `2` | Användarens distributions-ID. |
| InternalMailboxServer | `3` | Det fullständigt kvalificerade domännamnet för postlådeservern. |
| InternalRpcClientServer | `4` | Det fullständigt kvalificerade domännamnet för RPC-klientservern. |
| InternalMailboxServerDN | `5` | Det äldre distinguerade namnet på postlådeservern. |
| InternalEcpUrl | `6` | Den interna webbadressen till Exchange-kontrollpanelen. |
| InternalEcpVoicemailUrl | `7` | Den interna webbadressen till Exchange-kontrollpanelen för anpassning av röstmeddelanden. |
| InternalEcpEmailSubscriptionsUrl | `8` | Den interna webbadressen till Exchange-kontrollpanelen för e-postprenumerationer. |
| InternalEcpTextMessagingUrl | `9` | Den interna webbadressen till Exchange-kontrollpanelen för textmeddelanden. |
| InternalEcpDeliveryReportUrl | `10` | Den interna webbadressen till Exchange-kontrollpanelen för leveransrapporter. |
| InternalEcpRetentionPolicyTagsUrl | `11` | Den interna webbadressen till Exchange-kontrollpanelen för RetentionPolicy-taggar. |
| InternalEcpPublishingUrl | `12` | Den interna webbadressen till Exchange Control Panel for Publishing. |
| InternalEcpPhotoUrl | `13` | Den interna webbadressen till Exchange-kontrollpanelen för foton. |
| InternalEcpConnectUrl | `14` | Den interna webbadressen till Exchange-kontrollpanelen för People Connect-prenumerationer. |
| InternalEcpTeamMailboxUrl | `15` | Den interna webbadressen till Exchange Control Panel for Team Mailbox. |
| InternalEcpTeamMailboxCreatingUrl | `16` | Den interna URL-adressen till Exchange-kontrollpanelen för att skapa Team Mailbox. |
| InternalEcpTeamMailboxEditingUrl | `17` | Den interna webbadressen till Exchange Kontrollpanel för redigering av Team Mailbox. |
| InternalEcpTeamMailboxHidingUrl | `18` | Den interna webbadressen till Exchange-kontrollpanelen för att dölja Team Mailbox. |
| InternalEcpExtensionInstallationUrl | `19` | Den interna URL-adressen till Exchange-kontrollpanelen för tilläggsinstallationen. |
| InternalEwsUrl | `20` | Den interna webbadressen till Exchange Web Services. |
| InternalEmwsUrl | `21` | Den interna webbadressen till Exchange Management Web Services. |
| InternalOABUrl | `22` | Den interna webbadressen till offlineadressboken. |
| InternalPhotosUrl | `23` | Den interna webbadressen till tjänsten Foton. |
| InternalUMUrl | `24` | Den interna webbadressen till Unified Messaging-tjänsterna. |
| InternalWebClientUrls | `25` | Exchange-webbklientens interna webbadresser. |
| MailboxDN | `26` | Det unika namnet på postlådedatabasen för användarens postlåda. |
| PublicFolderServer | `27` | Namnet på servern för offentliga mappar. |
| ActiveDirectoryServer | `28` | Namnet på Active Directory-servern. |
| ExternalMailboxServer | `29` | Namnet på RPC över HTTP-servern. |
| ExternalMailboxServerRequiresSSL | `30` | Indikerar om RPC över HTTP-servern kräver SSL. |
| ExternalMailboxServerAuthenticationMethods | `31` | De autentiseringsmetoder som stöds av RPC över HTTP-servern. |
| EcpVoicemailUrlFragment | `32` | URL-fragmentet för Exchange-kontrollpanelen för anpassning av röstmeddelanden. |
| EcpEmailSubscriptionsUrlFragment | `33` | URL-fragmentet för Exchange-kontrollpanelen för e-postprenumerationer. |
| EcpTextMessagingUrlFragment | `34` | URL-fragmentet för Exchange Control Panel for Text Messaging. |
| EcpDeliveryReportUrlFragment | `35` | URL-fragmentet för Exchange-kontrollpanelen för leveransrapporter. |
| EcpRetentionPolicyTagsUrlFragment | `36` | URL-fragmentet för Exchange-kontrollpanelen för RetentionPolicy-taggar. |
| EcpPublishingUrlFragment | `37` | URL-fragmentet för Exchange Control Panel for Publishing. |
| EcpPhotoUrlFragment | `38` | URL-fragmentet av Exchange Kontrollpanel för foton. |
| EcpConnectUrlFragment | `39` | URL-fragmentet för Exchange Control Panel for People Connect. |
| EcpTeamMailboxUrlFragment | `40` | URL-fragmentet för Exchange-kontrollpanelen för Team Mailbox. |
| EcpTeamMailboxCreatingUrlFragment | `41` | URL-fragmentet för Exchange-kontrollpanelen för att skapa Team Mailbox. |
| EcpTeamMailboxEditingUrlFragment | `42` | URL-fragmentet för Exchange-kontrollpanelen för redigering av Team Mailbox. |
| EcpExtensionInstallationUrlFragment | `43` | URL-fragmentet av Exchange-kontrollpanelen för installation av tillägg. |
| ExternalEcpUrl | `44` | Den externa webbadressen till Exchange-kontrollpanelen. |
| ExternalEcpVoicemailUrl | `45` | Den externa URL:en till Exchange-kontrollpanelen för anpassning av röstmeddelanden. |
| ExternalEcpEmailSubscriptionsUrl | `46` | Den externa webbadressen till Exchange-kontrollpanelen för e-postprenumerationer. |
| ExternalEcpTextMessagingUrl | `47` | Den externa webbadressen till Exchange Kontrollpanel för textmeddelanden. |
| ExternalEcpDeliveryReportUrl | `48` | Den externa webbadressen till Exchange-kontrollpanelen för leveransrapporter. |
| ExternalEcpRetentionPolicyTagsUrl | `49` | Den externa webbadressen till Exchange-kontrollpanelen för RetentionPolicy-taggar. |
| ExternalEcpPublishingUrl | `50` | Den externa webbadressen till Exchange Kontrollpanel för publicering. |
| ExternalEcpPhotoUrl | `51` | Den externa webbadressen till Exchange-kontrollpanelen för foton. |
| ExternalEcpConnectUrl | `52` | Den externa webbadressen till Exchange-kontrollpanelen för People Connect-prenumerationer. |
| ExternalEcpTeamMailboxUrl | `53` | Den externa URL:en för Exchange-kontrollpanelen för Team Mailbox. |
| ExternalEcpTeamMailboxCreatingUrl | `54` | Den externa URL-adressen till Exchange-kontrollpanelen för att skapa Team Mailbox. |
| ExternalEcpTeamMailboxEditingUrl | `55` | Den externa URL:en till Exchange Kontrollpanel för redigering av Team Mailbox. |
| ExternalEcpTeamMailboxHidingUrl | `56` | Den externa URL-adressen till Exchange-kontrollpanelen för att dölja Team Mailbox. |
| ExternalEcpExtensionInstallationUrl | `57` | Den externa URL-adressen till Exchange-kontrollpanelen för tilläggsinstallationen. |
| ExternalEwsUrl | `58` | Den externa webbadressen till Exchange Web Services. |
| ExternalEmwsUrl | `59` | Den externa webbadressen till Exchange Management Web Services. |
| ExternalOABUrl | `60` | Den externa webbadressen till offlineadressboken. |
| ExternalPhotosUrl | `61` | Den externa webbadressen till tjänsten Foton. |
| ExternalUMUrl | `62` | Den externa webbadressen till Unified Messaging-tjänsterna. |
| ExternalWebClientUrls | `63` | De externa webbadresserna för Exchange-webbklienten. |
| CrossOrganizationSharingEnabled | `64` | Indikerar att delning mellan organisationer är aktiverat. |
| AlternateMailboxes | `65` | Samling av alternativa brevlådor. |
| CasVersion | `66` | Den version av klientåtkomstservern som betjänar begäran (t.ex. 14.XX.YYY.ZZZ) |
| EwsSupportedSchemas | `67` | Kommaseparerad lista över schemaversioner som stöds av Exchange Web Services. Schematversionen values kommer att vara samma som värdena för ExchangeServerVersion-uppräkningen. |
| InternalPop3Connections | `68` | Listan med interna anslutningsinställningar för pop protocol |
| ExternalPop3Connections | `69` | Listan med externa anslutningsinställningar för pop protocol |
| InternalImap4Connections | `70` | Listan med interna anslutningsinställningar för imap4 protocol |
| ExternalImap4Connections | `71` | Listan med externa anslutningsinställningar för imap4 protocol |
| InternalSmtpConnections | `72` | Listan med interna anslutningsinställningar för smtp protocol |
| ExternalSmtpConnections | `73` | Listan med externa anslutningsinställningar för smtp protocol |
| InternalServerExclusiveConnect | `74` | Om inställt på "Av" bör klienter inte ansluta via detta protokoll. Protokollinnehållet är endast för informationsändamål. |
| ExternalEwsVersion | `75` | Den version av Exchange Web Services-servern ExternalEwsUrl pekar på. |
| MobileMailboxPolicy | `76` | Policyinställningar för mobil brevlåda. |
| DocumentSharingLocations | `77` | Dokumentdelningsplatser och deras inställningar. |
| UserMSOnline | `78` | Om användarkontot är ett MSOnline-konto. |
| InternalMailboxServerAuthenticationMethods | `79` | De autentiseringsmetoder som stöds av RPC-klientservern. |
| MailboxVersion | `80` | Version av servern som är värd för användarens postlåda. |
| SPMySiteHostURL | `81` | Sharepoint MySite Host URL. |
| SiteMailboxCreationURL | `82` | URL för skapande av webbplatspostlåda i SharePoint. Den används av Outlook för att skapa webbplatspostlåda direkt från SharePoint. |
| InternalRpcHttpServer | `83` | FQDN för servern som används för intern RPC/HTTP-anslutning. |
| InternalRpcHttpConnectivityRequiresSsl | `84` | Indikerar om SSL krävs för intern RPC/HTTP-anslutning. |
| InternalRpcHttpAuthenticationMethod | `85` | Autentiseringsmetoden som används för intern RPC/HTTP-anslutning. |
| ExternalServerExclusiveConnect | `86` | Om inställt på "På" bör klienter endast ansluta via detta protokoll. |
| ExchangeRpcUrl | `87` | Om inställt kan klienter anropa servern via XTC |
| ShowGalAsDefaultView | `88` | Om inställt på false ska klienter inte visa GAL som standard, utan visa kontaktlistan. |
| AutoDiscoverSMTPAddress | `89` | AutoDiscover Primär SMTP-adress för användaren. |
| InteropExternalEwsUrl | `90` | Den externa "interop"-URL:n för Exchange Web Services. Med interop betyder det en URL till E14-server (eller senare) som kan betjäna postlådor som är värd för nednivåserver (E2K3 och tidigare). |
| InteropExternalEwsVersion | `91` | Version av servern som InteropExternalEwsUrl pekar på. |
| PublicFolderInformation | `92` | Information om offentlig mapp (hierarki) |
| RedirectUrl | `93` | Den version som är lämplig URL för AutoDiscover-tjänsten som ska svara på denna fråga. |
| EwsPartnerUrl | `94` | URL-adressen till Exchange Web Services för Office365-partners. |
| CertPrincipalName | `95` | SSL-certifikatnamn |
| GroupingInformation | `96` | Grupperingstipset för vissa klienter. |
| InternalOutlookServiceUrl | `98` | Internal OutlookService URL |
| ExternalOutlookServiceUrl | `99` | Extern OutlookService URL |

### Anmärkningar

Lägg till nya värden i slutet och håll synkroniserad med Microsoft.Exchange.Autodiscover.ConfigurationSettings.UserConfigurationSettingName.

### Se även

* namnutrymme [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
