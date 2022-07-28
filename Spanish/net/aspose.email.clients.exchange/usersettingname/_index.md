---
title: UserSettingName
second_title: Referencia de la API de Aspose.Email para .NET
description: Configuración de usuario que se puede solicitar mediante GetUserSettings.
type: docs
weight: 3600
url: /es/net/aspose.email.clients.exchange/usersettingname/
---
## UserSettingName enumeration

Configuración de usuario que se puede solicitar mediante GetUserSettings.

```csharp
public enum UserSettingName
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| UserDisplayName | `0` | El nombre para mostrar del usuario. |
| UserDN | `1` | El nombre distinguido heredado del usuario. |
| UserDeploymentId | `2` | El ID de implementación del usuario. |
| InternalMailboxServer | `3` | El nombre de dominio completo del servidor de buzón. |
| InternalRpcClientServer | `4` | El nombre de dominio completo del servidor del cliente RPC. |
| InternalMailboxServerDN | `5` | El nombre distinguido heredado del servidor de buzones. |
| InternalEcpUrl | `6` | La URL interna del Panel de control de Exchange. |
| InternalEcpVoicemailUrl | `7` | La URL interna del Panel de control de Exchange para la personalización del correo de voz. |
| InternalEcpEmailSubscriptionsUrl | `8` | La URL interna del Panel de control de Exchange para suscripciones de correo electrónico. |
| InternalEcpTextMessagingUrl | `9` | La URL interna del Panel de control de Exchange para mensajería de texto. |
| InternalEcpDeliveryReportUrl | `10` | La URL interna del Panel de control de Exchange para informes de entrega. |
| InternalEcpRetentionPolicyTagsUrl | `11` | La URL interna del Panel de control de Exchange para etiquetas de política de retención. |
| InternalEcpPublishingUrl | `12` | La URL interna del Panel de control de Exchange para publicación. |
| InternalEcpPhotoUrl | `13` | La URL interna del Panel de control de Exchange para fotos. |
| InternalEcpConnectUrl | `14` | La URL interna del Panel de control de Exchange para suscripciones de People Connect. |
| InternalEcpTeamMailboxUrl | `15` | La URL interna del Panel de control de Exchange para Team Mailbox. |
| InternalEcpTeamMailboxCreatingUrl | `16` | La URL interna del Panel de control de Exchange para crear el buzón del equipo. |
| InternalEcpTeamMailboxEditingUrl | `17` | La URL interna del Panel de control de Exchange para editar el buzón del equipo. |
| InternalEcpTeamMailboxHidingUrl | `18` | La URL interna del Panel de control de Exchange para ocultar el buzón del equipo. |
| InternalEcpExtensionInstallationUrl | `19` | La URL interna del Panel de control de Exchange para la instalación de la extensión. |
| InternalEwsUrl | `20` | La URL interna de los servicios web de Exchange. |
| InternalEmwsUrl | `21` | La URL interna de los servicios web de administración de Exchange. |
| InternalOABUrl | `22` | La URL interna de la libreta de direcciones sin conexión. |
| InternalPhotosUrl | `23` | La URL interna del servicio Fotos. |
| InternalUMUrl | `24` | La URL interna de los servicios de mensajería unificada. |
| InternalWebClientUrls | `25` | Las direcciones URL internas del cliente web de Exchange. |
| MailboxDN | `26` | El nombre distinguido de la base de datos de buzones del buzón del usuario. |
| PublicFolderServer | `27` | El nombre del servidor de carpetas públicas. |
| ActiveDirectoryServer | `28` | El nombre del servidor de Active Directory. |
| ExternalMailboxServer | `29` | El nombre del servidor RPC sobre HTTP. |
| ExternalMailboxServerRequiresSSL | `30` | Indica si el servidor RPC sobre HTTP requiere SSL. |
| ExternalMailboxServerAuthenticationMethods | `31` | Los métodos de autenticación compatibles con el servidor RPC sobre HTTP. |
| EcpVoicemailUrlFragment | `32` | El fragmento de URL del Panel de control de Exchange para la personalización del correo de voz. |
| EcpEmailSubscriptionsUrlFragment | `33` | El fragmento de URL del Panel de control de Exchange para suscripciones de correo electrónico. |
| EcpTextMessagingUrlFragment | `34` | El fragmento de URL del Panel de control de Exchange para mensajería de texto. |
| EcpDeliveryReportUrlFragment | `35` | El fragmento de URL del Panel de control de Exchange para informes de entrega. |
| EcpRetentionPolicyTagsUrlFragment | `36` | El fragmento de URL del Panel de control de Exchange para etiquetas de política de retención. |
| EcpPublishingUrlFragment | `37` | El fragmento de URL del Panel de control de Exchange para publicación. |
| EcpPhotoUrlFragment | `38` | El fragmento de URL del Panel de control de Exchange para fotos. |
| EcpConnectUrlFragment | `39` | El fragmento de URL del Panel de control de Exchange para People Connect. |
| EcpTeamMailboxUrlFragment | `40` | El fragmento de URL del Panel de control de Exchange para Team Mailbox. |
| EcpTeamMailboxCreatingUrlFragment | `41` | El fragmento de URL del Panel de control de Exchange para crear el buzón del equipo. |
| EcpTeamMailboxEditingUrlFragment | `42` | El fragmento de URL del Panel de control de Exchange para editar el buzón del equipo. |
| EcpExtensionInstallationUrlFragment | `43` | El fragmento de URL del Panel de control de Exchange para instalar la extensión. |
| ExternalEcpUrl | `44` | La URL externa del Panel de control de Exchange. |
| ExternalEcpVoicemailUrl | `45` | La URL externa del Panel de control de Exchange para la personalización del correo de voz. |
| ExternalEcpEmailSubscriptionsUrl | `46` | La URL externa del Panel de control de Exchange para suscripciones de correo electrónico. |
| ExternalEcpTextMessagingUrl | `47` | La URL externa del Panel de control de Exchange para mensajería de texto. |
| ExternalEcpDeliveryReportUrl | `48` | La URL externa del Panel de control de Exchange para informes de entrega. |
| ExternalEcpRetentionPolicyTagsUrl | `49` | La URL externa del Panel de control de Exchange para etiquetas de política de retención. |
| ExternalEcpPublishingUrl | `50` | La URL externa del Panel de control de Exchange para publicación. |
| ExternalEcpPhotoUrl | `51` | La URL externa del Panel de control de Exchange para fotos. |
| ExternalEcpConnectUrl | `52` | La URL externa del Panel de control de Exchange para suscripciones de People Connect. |
| ExternalEcpTeamMailboxUrl | `53` | La URL externa del Panel de control de Exchange para Team Mailbox. |
| ExternalEcpTeamMailboxCreatingUrl | `54` | La URL externa del Panel de control de Exchange para crear el buzón del equipo. |
| ExternalEcpTeamMailboxEditingUrl | `55` | La URL externa del Panel de control de Exchange para editar el buzón del equipo. |
| ExternalEcpTeamMailboxHidingUrl | `56` | La URL externa del Panel de control de Exchange para ocultar el buzón del equipo. |
| ExternalEcpExtensionInstallationUrl | `57` | La URL externa del Panel de control de Exchange para la instalación de la extensión. |
| ExternalEwsUrl | `58` | La URL externa de los servicios web de Exchange. |
| ExternalEmwsUrl | `59` | La URL externa de los servicios web de administración de Exchange. |
| ExternalOABUrl | `60` | La URL externa de la libreta de direcciones sin conexión. |
| ExternalPhotosUrl | `61` | La URL externa del servicio Fotos. |
| ExternalUMUrl | `62` | La URL externa de los servicios de mensajería unificada. |
| ExternalWebClientUrls | `63` | Las direcciones URL externas del cliente web de Exchange. |
| CrossOrganizationSharingEnabled | `64` | Indica que el uso compartido entre organizaciones está habilitado. |
| AlternateMailboxes | `65` | Colección de buzones alternativos. |
| CasVersion | `66` | La versión del servidor de acceso de cliente que atiende la solicitud (p. ej., 14.XX.YYY.ZZZ) |
| EwsSupportedSchemas | `67` | Lista separada por comas de las versiones de esquema admitidas por Exchange Web Services. Los valores de la versión del esquema serán los mismos que los valores de la enumeración ExchangeServerVersion. |
| InternalPop3Connections | `68` | La lista de configuración de conexión interna para el protocolo pop |
| ExternalPop3Connections | `69` | La lista de configuración de conexión externa para el protocolo pop |
| InternalImap4Connections | `70` | La lista de configuración de conexión interna para imap4 protocol |
| ExternalImap4Connections | `71` | La lista de configuración de conexión externa para imap4 protocol |
| InternalSmtpConnections | `72` | La lista de configuración de conexión interna para el protocolo smtp |
| ExternalSmtpConnections | `73` | La lista de configuración de conexión externa para el protocolo smtp |
| InternalServerExclusiveConnect | `74` | Si se establece en "Desactivado", los clientes no deben conectarse a través de este protocolo. El contenido del protocolo es solo para fines informativos. |
| ExternalEwsVersion | `75` | La versión del servidor de servicios web de Exchange ExternalEwsUrl apunta a. |
| MobileMailboxPolicy | `76` | Configuración de directiva de buzón móvil. |
| DocumentSharingLocations | `77` | Ubicaciones para compartir documentos y sus configuraciones. |
| UserMSOnline | `78` | Si la cuenta de usuario es una cuenta de MSOnline. |
| InternalMailboxServerAuthenticationMethods | `79` | Los métodos de autenticación admitidos por el servidor del cliente RPC. |
| MailboxVersion | `80` | Versión del servidor que aloja el buzón del usuario. |
| SPMySiteHostURL | `81` | URL del host de Sharepoint MySite. |
| SiteMailboxCreationURL | `82` | Dirección URL de creación del buzón del sitio en SharePoint. Outlook lo utiliza para crear el buzón del sitio directamente desde SharePoint. |
| InternalRpcHttpServer | `83` | El FQDN del servidor utilizado para la conectividad RPC/HTTP interna. |
| InternalRpcHttpConnectivityRequiresSsl | `84` | Indica si se requiere SSL para la conectividad RPC/HTTP interna. |
| InternalRpcHttpAuthenticationMethod | `85` | El método de autenticación utilizado para la conectividad RPC/HTTP interna. |
| ExternalServerExclusiveConnect | `86` | Si se establece en "Activado", los clientes solo deben conectarse a través de este protocolo. |
| ExchangeRpcUrl | `87` | Si se establece, los clientes pueden llamar al servidor a través de XTC |
| ShowGalAsDefaultView | `88` | Si se establece en falso, los clientes no deberían mostrar la GAL de forma predeterminada, sino mostrar la lista de contactos. |
| AutoDiscoverSMTPAddress | `89` | Dirección SMTP principal de AutoDiscover para el usuario. |
| InteropExternalEwsUrl | `90` | La URL externa de 'interoperabilidad' de los servicios web de Exchange. Por interoperabilidad se refiere a una URL al servidor E14 (o posterior) que puede servir buzones que están alojados en un servidor de nivel inferior (E2K3 y anterior). |
| InteropExternalEwsVersion | `91` | Versión del servidor a la que apunta InteropExternalEwsUrl. |
| PublicFolderInformation | `92` | Información de carpeta pública (jerarquía) |
| RedirectUrl | `93` | La versión URL apropiada del servicio AutoDiscover que debería responder a esta consulta. |
| EwsPartnerUrl | `94` | La URL de los servicios web de Exchange para socios de Office365. |
| CertPrincipalName | `95` | nombre del certificado SSL |
| GroupingInformation | `96` | La sugerencia de agrupación para ciertos clientes. |
| InternalOutlookServiceUrl | `98` | URL interna del servicio de Outlook |
| ExternalOutlookServiceUrl | `99` | URL de servicio externo de Outlook |

### Observaciones

Agregue nuevos valores al final y manténgase sincronizado con Microsoft.Exchange.Autodiscover.ConfigurationSettings.UserConfigurationSettingName.

### Ver también

* espacio de nombres [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
