---
title: UserSettingName
second_title: Aspose.Email per riferimento all'API .NET
description: Impostazioni utente che possono essere richieste utilizzando GetUserSettings.
type: docs
weight: 3600
url: /it/net/aspose.email.clients.exchange/usersettingname/
---
## UserSettingName enumeration

Impostazioni utente che possono essere richieste utilizzando GetUserSettings.

```csharp
public enum UserSettingName
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| UserDisplayName | `0` | Il nome visualizzato dell'utente. |
| UserDN | `1` | Il nome distinto legacy dell'utente. |
| UserDeploymentId | `2` | L'ID distribuzione dell'utente. |
| InternalMailboxServer | `3` | Il nome di dominio completo del server delle cassette postali. |
| InternalRpcClientServer | `4` | Il nome di dominio completo del server client RPC. |
| InternalMailboxServerDN | `5` | Il nome distinto legacy del server delle cassette postali. |
| InternalEcpUrl | `6` | L'URL interno del Pannello di controllo di Exchange. |
| InternalEcpVoicemailUrl | `7` | L'URL interno del Pannello di controllo di Exchange per la personalizzazione della posta vocale. |
| InternalEcpEmailSubscriptionsUrl | `8` | L'URL interno del Pannello di controllo di Exchange per gli abbonamenti e-mail. |
| InternalEcpTextMessagingUrl | `9` | L'URL interno del Pannello di controllo di Exchange per la messaggistica di testo. |
| InternalEcpDeliveryReportUrl | `10` | L'URL interno del pannello di controllo di Exchange per i rapporti di consegna. |
| InternalEcpRetentionPolicyTagsUrl | `11` | L'URL interno del pannello di controllo di Exchange per i tag RetentionPolicy. |
| InternalEcpPublishingUrl | `12` | L'URL interno del Pannello di controllo di Exchange per la pubblicazione. |
| InternalEcpPhotoUrl | `13` | L'URL interno del Pannello di controllo di Exchange per le foto. |
| InternalEcpConnectUrl | `14` | L'URL interno del Pannello di controllo di Exchange per gli abbonamenti People Connect. |
| InternalEcpTeamMailboxUrl | `15` | L'URL interno del pannello di controllo di Exchange per la cassetta postale del team. |
| InternalEcpTeamMailboxCreatingUrl | `16` | L'URL interno del Pannello di controllo di Exchange per la creazione della cassetta postale del team. |
| InternalEcpTeamMailboxEditingUrl | `17` | L'URL interno del pannello di controllo di Exchange per la modifica della casella di posta del team. |
| InternalEcpTeamMailboxHidingUrl | `18` | L'URL interno del pannello di controllo di Exchange per nascondere la casella di posta del team. |
| InternalEcpExtensionInstallationUrl | `19` | L'URL interno del Pannello di controllo di Exchange per l'installazione dell'estensione. |
| InternalEwsUrl | `20` | L'URL interno dei servizi Web di Exchange. |
| InternalEmwsUrl | `21` | L'URL interno dei servizi Web di gestione di Exchange. |
| InternalOABUrl | `22` | L'URL interno della Rubrica offline. |
| InternalPhotosUrl | `23` | L'URL interno del servizio Foto. |
| InternalUMUrl | `24` | L'URL interno dei servizi di messaggistica unificata. |
| InternalWebClientUrls | `25` | Gli URL interni del client Web Exchange. |
| MailboxDN | `26` | Il nome distinto del database delle cassette postali della cassetta postale dell'utente. |
| PublicFolderServer | `27` | Il nome del server delle cartelle pubbliche. |
| ActiveDirectoryServer | `28` | Il nome del server Active Directory. |
| ExternalMailboxServer | `29` | Il nome del server RPC su HTTP. |
| ExternalMailboxServerRequiresSSL | `30` | Indica se il server RPC su HTTP richiede SSL. |
| ExternalMailboxServerAuthenticationMethods | `31` | I metodi di autenticazione supportati dal server RPC su HTTP. |
| EcpVoicemailUrlFragment | `32` | Il frammento URL del Pannello di controllo di Exchange per la personalizzazione della segreteria telefonica. |
| EcpEmailSubscriptionsUrlFragment | `33` | Il frammento URL del Pannello di controllo di Exchange per le sottoscrizioni e-mail. |
| EcpTextMessagingUrlFragment | `34` | Il frammento URL del Pannello di controllo di Exchange per la messaggistica di testo. |
| EcpDeliveryReportUrlFragment | `35` | Il frammento URL del Pannello di controllo di Exchange per i rapporti di recapito. |
| EcpRetentionPolicyTagsUrlFragment | `36` | Il frammento URL del Pannello di controllo di Exchange per i tag RetentionPolicy. |
| EcpPublishingUrlFragment | `37` | Il frammento di URL del Pannello di controllo di Exchange per la pubblicazione. |
| EcpPhotoUrlFragment | `38` | Il frammento URL del Pannello di controllo di Exchange per le foto. |
| EcpConnectUrlFragment | `39` | Il frammento URL del Pannello di controllo di Exchange per People Connect. |
| EcpTeamMailboxUrlFragment | `40` | Il frammento di URL del pannello di controllo di Exchange per la cassetta postale del team. |
| EcpTeamMailboxCreatingUrlFragment | `41` | Il frammento URL del Pannello di controllo di Exchange per la creazione della cassetta postale del team. |
| EcpTeamMailboxEditingUrlFragment | `42` | Il frammento URL del Pannello di controllo di Exchange per la modifica della cassetta postale del team. |
| EcpExtensionInstallationUrlFragment | `43` | Il frammento URL del Pannello di controllo di Exchange per l'installazione dell'estensione. |
| ExternalEcpUrl | `44` | L'URL esterno del Pannello di controllo di Exchange. |
| ExternalEcpVoicemailUrl | `45` | L'URL esterno del pannello di controllo di Exchange per la personalizzazione della segreteria telefonica. |
| ExternalEcpEmailSubscriptionsUrl | `46` | L'URL esterno del pannello di controllo di Exchange per gli abbonamenti e-mail. |
| ExternalEcpTextMessagingUrl | `47` | L'URL esterno del Pannello di controllo di Exchange per la messaggistica di testo. |
| ExternalEcpDeliveryReportUrl | `48` | L'URL esterno del pannello di controllo di Exchange per i rapporti di consegna. |
| ExternalEcpRetentionPolicyTagsUrl | `49` | L'URL esterno del pannello di controllo di Exchange per i tag RetentionPolicy. |
| ExternalEcpPublishingUrl | `50` | L'URL esterno del Pannello di controllo di Exchange per la pubblicazione. |
| ExternalEcpPhotoUrl | `51` | L'URL esterno del pannello di controllo di Exchange per le foto. |
| ExternalEcpConnectUrl | `52` | L'URL esterno del Pannello di controllo di Exchange per gli abbonamenti People Connect. |
| ExternalEcpTeamMailboxUrl | `53` | L'URL esterno del pannello di controllo di Exchange per la cassetta postale del team. |
| ExternalEcpTeamMailboxCreatingUrl | `54` | L'URL esterno del pannello di controllo di Exchange per la creazione della cassetta postale del team. |
| ExternalEcpTeamMailboxEditingUrl | `55` | L'URL esterno del pannello di controllo di Exchange per la modifica della casella di posta del team. |
| ExternalEcpTeamMailboxHidingUrl | `56` | L'URL esterno del pannello di controllo di Exchange per nascondere la casella di posta del team. |
| ExternalEcpExtensionInstallationUrl | `57` | L'URL esterno del Pannello di controllo di Exchange per l'installazione dell'estensione. |
| ExternalEwsUrl | `58` | L'URL esterno dei servizi Web di Exchange. |
| ExternalEmwsUrl | `59` | L'URL esterno dei servizi Web di gestione di Exchange. |
| ExternalOABUrl | `60` | L'URL esterno della Rubrica offline. |
| ExternalPhotosUrl | `61` | L'URL esterno del servizio Foto. |
| ExternalUMUrl | `62` | L'URL esterno dei servizi di messaggistica unificata. |
| ExternalWebClientUrls | `63` | Gli URL esterni del client Web Exchange. |
| CrossOrganizationSharingEnabled | `64` | Indica che la condivisione tra organizzazioni è abilitata. |
| AlternateMailboxes | `65` | Raccolta di cassette postali alternative. |
| CasVersion | `66` | La versione del Client Access Server che serve la richiesta (es. 14.XX.YYY.ZZZ) |
| EwsSupportedSchemas | `67` | Elenco separato da virgole delle versioni dello schema supportate da Servizi Web Exchange. I valori della versione dello schema saranno gli stessi dei valori dell'enumerazione ExchangeServerVersion. |
| InternalPop3Connections | `68` | L'elenco delle impostazioni di connessione interna per il protocollo pop |
| ExternalPop3Connections | `69` | L'elenco delle impostazioni di connessione esterna per il protocollo pop |
| InternalImap4Connections | `70` | L'elenco delle impostazioni di connessione interna per il protocollo imap4 |
| ExternalImap4Connections | `71` | L'elenco delle impostazioni di connessione esterna per il protocollo imap4 |
| InternalSmtpConnections | `72` | L'elenco delle impostazioni di connessione interna per il protocollo SMTP |
| ExternalSmtpConnections | `73` | L'elenco delle impostazioni di connessione esterna per il protocollo SMTP |
| InternalServerExclusiveConnect | `74` | Se impostato su "Off", i client non dovrebbero connettersi tramite questo protocollo. I contenuti del protocollo sono solo a scopo informativo. |
| ExternalEwsVersion | `75` | La versione del server Servizi Web Exchange a cui punta ExternalEwsUrl. |
| MobileMailboxPolicy | `76` | Impostazioni dei criteri per le cassette postali mobili. |
| DocumentSharingLocations | `77` | Posizioni di condivisione dei documenti e relative impostazioni. |
| UserMSOnline | `78` | Se l'account utente è un account MSOnline. |
| InternalMailboxServerAuthenticationMethods | `79` | I metodi di autenticazione supportati dal server client RPC. |
| MailboxVersion | `80` | Versione del server che ospita la casella di posta dell'utente. |
| SPMySiteHostURL | `81` | URL host MySite di Sharepoint. |
| SiteMailboxCreationURL | `82` | URL di creazione della cassetta postale del sito in SharePoint. Viene utilizzato da Outlook per creare la cassetta postale del sito direttamente da SharePoint. |
| InternalRpcHttpServer | `83` | L'FQDN del server utilizzato per la connettività RPC/HTTP interna. |
| InternalRpcHttpConnectivityRequiresSsl | `84` | Indica se è richiesto SSL per la connettività RPC/HTTP interna. |
| InternalRpcHttpAuthenticationMethod | `85` | Il metodo di autenticazione utilizzato per la connettività RPC/HTTP interna. |
| ExternalServerExclusiveConnect | `86` | Se impostato su "On", i client dovrebbero connettersi solo tramite questo protocollo. |
| ExchangeRpcUrl | `87` | Se impostato, i client possono chiamare il server tramite XTC |
| ShowGalAsDefaultView | `88` | Se impostato su false, i client non dovrebbero mostrare il GAL per impostazione predefinita, ma mostrare l'elenco dei contatti. |
| AutoDiscoverSMTPAddress | `89` | AutoDiscover Indirizzo SMTP primario per l'utente. |
| InteropExternalEwsUrl | `90` | L'URL esterno di "interoperabilità" dei servizi Web di Exchange. Per interoperabilità si intende un URL del server E14 (o successivo) che può servire le cassette postali ospitate nel server di livello inferiore (E2K3 e precedenti). |
| InteropExternalEwsVersion | `91` | La versione del server a cui punta InteropExternalEwsUrl. |
| PublicFolderInformation | `92` | Informazioni sulla cartella pubblica (gerarchia) |
| RedirectUrl | `93` | L'URL appropriato della versione del servizio di individuazione automatica che dovrebbe rispondere a questa query. |
| EwsPartnerUrl | `94` | L'URL dei servizi Web Exchange per i partner di Office365. |
| CertPrincipalName | `95` | nome certificato SSL |
| GroupingInformation | `96` | Il suggerimento di raggruppamento per determinati client. |
| InternalOutlookServiceUrl | `98` | URL del servizio Outlook interno |
| ExternalOutlookServiceUrl | `99` | URL del servizio Outlook esterno |

### Osservazioni

Aggiungi nuovi valori alla fine e mantieni la sincronizzazione con Microsoft.Exchange.Autodiscover.ConfigurationSettings.UserConfigurationSettingName.

### Guarda anche

* spazio dei nomi [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
