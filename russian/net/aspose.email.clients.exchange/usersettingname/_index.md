---
title: UserSettingName
second_title: Справочник по Aspose.Email для .NET API
description: Пользовательские настройки которые можно запросить с помощью GetUserSettings.
type: docs
weight: 3600
url: /ru/net/aspose.email.clients.exchange/usersettingname/
---
## UserSettingName enumeration

Пользовательские настройки, которые можно запросить с помощью GetUserSettings.

```csharp
public enum UserSettingName
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| UserDisplayName | `0` | Отображаемое имя пользователя. |
| UserDN | `1` | Устаревшее отличительное имя пользователя. |
| UserDeploymentId | `2` | Идентификатор развертывания пользователя. |
| InternalMailboxServer | `3` | Полное доменное имя сервера почтовых ящиков. |
| InternalRpcClientServer | `4` | Полное доменное имя клиентского сервера RPC. |
| InternalMailboxServerDN | `5` | Устаревшее различающееся имя сервера почтовых ящиков. |
| InternalEcpUrl | `6` | Внутренний URL-адрес панели управления Exchange. |
| InternalEcpVoicemailUrl | `7` | Внутренний URL-адрес панели управления Exchange для настройки голосовой почты. |
| InternalEcpEmailSubscriptionsUrl | `8` | Внутренний URL-адрес панели управления Exchange для подписок по электронной почте. |
| InternalEcpTextMessagingUrl | `9` | Внутренний URL-адрес панели управления Exchange для обмена текстовыми сообщениями. |
| InternalEcpDeliveryReportUrl | `10` | Внутренний URL-адрес панели управления Exchange для отчетов о доставке. |
| InternalEcpRetentionPolicyTagsUrl | `11` | Внутренний URL-адрес панели управления Exchange для тегов RetentionPolicy. |
| InternalEcpPublishingUrl | `12` | Внутренний URL-адрес панели управления Exchange для публикации. |
| InternalEcpPhotoUrl | `13` | Внутренний URL панели управления Exchange для фотографий. |
| InternalEcpConnectUrl | `14` | Внутренний URL-адрес панели управления Exchange для подписок People Connect. |
| InternalEcpTeamMailboxUrl | `15` | Внутренний URL-адрес панели управления Exchange для группового почтового ящика. |
| InternalEcpTeamMailboxCreatingUrl | `16` | Внутренний URL-адрес панели управления Exchange для создания группового почтового ящика. |
| InternalEcpTeamMailboxEditingUrl | `17` | Внутренний URL панели управления Exchange для редактирования группового почтового ящика. |
| InternalEcpTeamMailboxHidingUrl | `18` | Внутренний URL-адрес панели управления Exchange для скрытия группового почтового ящика. |
| InternalEcpExtensionInstallationUrl | `19` | Внутренний URL панели управления Exchange для установки расширения. |
| InternalEwsUrl | `20` | Внутренний URL-адрес веб-служб Exchange. |
| InternalEmwsUrl | `21` | Внутренний URL-адрес веб-служб управления Exchange. |
| InternalOABUrl | `22` | Внутренний URL-адрес автономной адресной книги. |
| InternalPhotosUrl | `23` | Внутренний URL сервиса Photos. |
| InternalUMUrl | `24` | Внутренний URL-адрес служб единой системы обмена сообщениями. |
| InternalWebClientUrls | `25` | Внутренние URL-адреса веб-клиента Exchange. |
| MailboxDN | `26` | Отличительное имя базы данных почтовых ящиков почтового ящика пользователя. |
| PublicFolderServer | `27` | Имя сервера общих папок. |
| ActiveDirectoryServer | `28` | Имя сервера Active Directory. |
| ExternalMailboxServer | `29` | Имя сервера RPC через HTTP. |
| ExternalMailboxServerRequiresSSL | `30` | Указывает, требует ли сервер RPC через HTTP SSL. |
| ExternalMailboxServerAuthenticationMethods | `31` | Методы аутентификации, поддерживаемые сервером RPC через HTTP. |
| EcpVoicemailUrlFragment | `32` | Фрагмент URL-адреса панели управления Exchange для настройки голосовой почты. |
| EcpEmailSubscriptionsUrlFragment | `33` | Фрагмент URL-адреса панели управления Exchange для подписок по электронной почте. |
| EcpTextMessagingUrlFragment | `34` | Фрагмент URL-адреса панели управления Exchange для обмена текстовыми сообщениями. |
| EcpDeliveryReportUrlFragment | `35` | Фрагмент URL панели управления Exchange для отчетов о доставке. |
| EcpRetentionPolicyTagsUrlFragment | `36` | Фрагмент URL-адреса панели управления Exchange для тегов RetentionPolicy. |
| EcpPublishingUrlFragment | `37` | Фрагмент URL-адреса панели управления Exchange для публикации. |
| EcpPhotoUrlFragment | `38` | Фрагмент URL панели управления Exchange для фотографий. |
| EcpConnectUrlFragment | `39` | Фрагмент URL-адреса панели управления Exchange для People Connect. |
| EcpTeamMailboxUrlFragment | `40` | Фрагмент URL-адреса панели управления Exchange для группового почтового ящика. |
| EcpTeamMailboxCreatingUrlFragment | `41` | Фрагмент URL панели управления Exchange для создания группового почтового ящика. |
| EcpTeamMailboxEditingUrlFragment | `42` | Фрагмент URL панели управления Exchange для редактирования группового почтового ящика. |
| EcpExtensionInstallationUrlFragment | `43` | Фрагмент URL панели управления Exchange для установки расширения. |
| ExternalEcpUrl | `44` | Внешний URL-адрес панели управления Exchange. |
| ExternalEcpVoicemailUrl | `45` | Внешний URL-адрес панели управления Exchange для настройки голосовой почты. |
| ExternalEcpEmailSubscriptionsUrl | `46` | Внешний URL-адрес панели управления Exchange для подписок по электронной почте. |
| ExternalEcpTextMessagingUrl | `47` | Внешний URL-адрес панели управления Exchange для обмена текстовыми сообщениями. |
| ExternalEcpDeliveryReportUrl | `48` | Внешний URL-адрес панели управления Exchange для отчетов о доставке. |
| ExternalEcpRetentionPolicyTagsUrl | `49` | Внешний URL-адрес панели управления Exchange для тегов RetentionPolicy. |
| ExternalEcpPublishingUrl | `50` | Внешний URL-адрес панели управления Exchange для публикации. |
| ExternalEcpPhotoUrl | `51` | Внешний URL панели управления Exchange для фотографий. |
| ExternalEcpConnectUrl | `52` | Внешний URL-адрес панели управления Exchange для подписок People Connect. |
| ExternalEcpTeamMailboxUrl | `53` | Внешний URL-адрес панели управления Exchange для группового почтового ящика. |
| ExternalEcpTeamMailboxCreatingUrl | `54` | Внешний URL-адрес панели управления Exchange для создания группового почтового ящика. |
| ExternalEcpTeamMailboxEditingUrl | `55` | Внешний URL-адрес панели управления Exchange для редактирования группового почтового ящика. |
| ExternalEcpTeamMailboxHidingUrl | `56` | Внешний URL-адрес панели управления Exchange для скрытия группового почтового ящика. |
| ExternalEcpExtensionInstallationUrl | `57` | Внешний URL панели управления Exchange для установки расширения. |
| ExternalEwsUrl | `58` | Внешний URL-адрес веб-служб Exchange. |
| ExternalEmwsUrl | `59` | Внешний URL-адрес веб-служб управления Exchange. |
| ExternalOABUrl | `60` | Внешний URL-адрес автономной адресной книги. |
| ExternalPhotosUrl | `61` | Внешний URL службы фотографий. |
| ExternalUMUrl | `62` | Внешний URL-адрес служб единой системы обмена сообщениями. |
| ExternalWebClientUrls | `63` | Внешние URL-адреса веб-клиента Exchange. |
| CrossOrganizationSharingEnabled | `64` | Указывает, что совместное использование между организациями включено. |
| AlternateMailboxes | `65` | Коллекция альтернативных почтовых ящиков. |
| CasVersion | `66` | Версия сервера клиентского доступа, обслуживающего запрос (например, 14.XX.YYY.ZZZ) |
| EwsSupportedSchemas | `67` | Разделенный запятыми список версий схемы, поддерживаемых веб-службами Exchange. Значения версии схемы будут такими же, как значения перечисления ExchangeServerVersion. |
| InternalPop3Connections | `68` | Список настроек внутреннего подключения для поп-протокола |
| ExternalPop3Connections | `69` | Список настроек внешнего подключения для поп-протокола |
| InternalImap4Connections | `70` | Список настроек внутреннего подключения для протокола imap4 |
| ExternalImap4Connections | `71` | Список настроек внешнего подключения для протокола imap4 |
| InternalSmtpConnections | `72` | Список настроек внутреннего подключения для протокола smtp |
| ExternalSmtpConnections | `73` | Список настроек внешнего подключения для протокола smtp |
| InternalServerExclusiveConnect | `74` | Если установлено значение "Выкл", то клиенты не должны подключаться по этому протоколу. Содержание протокола предназначено только для информационных целей. |
| ExternalEwsVersion | `75` | Версия сервера веб-служб Exchange, на которую указывает ExternalEwsUrl. |
| MobileMailboxPolicy | `76` | Параметры политики мобильного почтового ящика. |
| DocumentSharingLocations | `77` | Места обмена документами и их настройки. |
| UserMSOnline | `78` | Является ли учетная запись пользователя учетной записью MSOnline. |
| InternalMailboxServerAuthenticationMethods | `79` | Методы аутентификации, поддерживаемые клиентским сервером RPC. |
| MailboxVersion | `80` | Версия сервера, на котором размещен почтовый ящик пользователя. |
| SPMySiteHostURL | `81` | URL-адрес хоста Sharepoint MySite. |
| SiteMailboxCreationURL | `82` | URL-адрес создания почтового ящика сайта в SharePoint. Он используется Outlook для создания почтового ящика сайта напрямую из SharePoint. |
| InternalRpcHttpServer | `83` | Полное доменное имя сервера, используемого для внутреннего подключения RPC/HTTP. |
| InternalRpcHttpConnectivityRequiresSsl | `84` | Указывает, требуется ли SSL для внутреннего подключения RPC/HTTP. |
| InternalRpcHttpAuthenticationMethod | `85` | Метод проверки подлинности, используемый для внутреннего подключения RPC/HTTP. |
| ExternalServerExclusiveConnect | `86` | Если установлено значение "Вкл", то клиенты должны подключаться только по этому протоколу. |
| ExchangeRpcUrl | `87` | Если установлено, то клиенты могут звонить на сервер через XTC |
| ShowGalAsDefaultView | `88` | Если установлено значение false, клиенты не должны показывать глобальный список адресов по умолчанию, а отображать список контактов. |
| AutoDiscoverSMTPAddress | `89` | Автообнаружение основного SMTP-адреса для пользователя. |
| InteropExternalEwsUrl | `90` | Внешний URL-адрес "взаимодействия" веб-служб Exchange. Под взаимодействием подразумевается URL-адрес сервера E14 (или более поздней версии), который может обслуживать почтовые ящики , размещенные на сервере нижнего уровня (E2K3 и ранее). |
| InteropExternalEwsVersion | `91` | Версия сервера, на который указывает InteropExternalEwsUrl. |
| PublicFolderInformation | `92` | Информация об общих папках (иерархия) |
| RedirectUrl | `93` | Соответствующий версии URL-адрес службы автообнаружения, которая должна отвечать на этот запрос. |
| EwsPartnerUrl | `94` | URL-адрес веб-служб Exchange для партнеров Office365. |
| CertPrincipalName | `95` | Имя сертификата SSL |
| GroupingInformation | `96` | Подсказка группировки для определенных клиентов. |
| InternalOutlookServiceUrl | `98` | Внутренний URL-адрес OutlookService |
| ExternalOutlookServiceUrl | `99` | Внешний URL-адрес OutlookService |

### Примечания

Добавляйте новые значения в конец и синхронизируйтесь с Microsoft.Exchange.Autodiscover.ConfigurationSettings.UserConfigurationSettingName .

### Смотрите также

* пространство имен [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
