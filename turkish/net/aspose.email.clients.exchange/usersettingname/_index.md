---
title: UserSettingName
second_title: Aspose.Email for .NET API Referansı
description: GetUserSettings kullanılarak istenebilecek kullanıcı ayarları.
type: docs
weight: 3600
url: /tr/net/aspose.email.clients.exchange/usersettingname/
---
## UserSettingName enumeration

GetUserSettings kullanılarak istenebilecek kullanıcı ayarları.

```csharp
public enum UserSettingName
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| UserDisplayName | `0` | Kullanıcının görünen adı. |
| UserDN | `1` | Kullanıcının eski ayırt edici adı. |
| UserDeploymentId | `2` | Kullanıcının dağıtım kimliği. |
| InternalMailboxServer | `3` | Posta kutusu sunucusunun tam etki alanı adı. |
| InternalRpcClientServer | `4` | RPC istemci sunucusunun tam etki alanı adı. |
| InternalMailboxServerDN | `5` | Posta kutusu sunucusunun eski ayırt edici adı. |
| InternalEcpUrl | `6` | Exchange Kontrol Panelinin dahili URL'si. |
| InternalEcpVoicemailUrl | `7` | VoiceMail Özelleştirme için Exchange Kontrol Panelinin dahili URL'si. |
| InternalEcpEmailSubscriptionsUrl | `8` | E-posta Abonelikleri için Exchange Kontrol Panelinin dahili URL'si. |
| InternalEcpTextMessagingUrl | `9` | Metin Mesajlaşması için Exchange Kontrol Panelinin dahili URL'si. |
| InternalEcpDeliveryReportUrl | `10` | Teslimat Raporları için Exchange Kontrol Panelinin dahili URL'si. |
| InternalEcpRetentionPolicyTagsUrl | `11` | RetentionPolicy Etiketleri için Exchange Kontrol Panelinin dahili URL'si. |
| InternalEcpPublishingUrl | `12` | Yayınlama için Exchange Kontrol Panelinin dahili URL'si. |
| InternalEcpPhotoUrl | `13` | Fotoğraflar için Exchange Kontrol Panelinin dahili URL'si. |
| InternalEcpConnectUrl | `14` | People Connect abonelikleri için Exchange Kontrol Panelinin dahili URL'si. |
| InternalEcpTeamMailboxUrl | `15` | Ekip Posta Kutusu için Exchange Kontrol Panelinin dahili URL'si. |
| InternalEcpTeamMailboxCreatingUrl | `16` | Ekip Posta Kutusu oluşturmak için Exchange Kontrol Panelinin dahili URL'si. |
| InternalEcpTeamMailboxEditingUrl | `17` | Ekip Posta Kutusunu düzenlemek için Exchange Kontrol Panelinin dahili URL'si. |
| InternalEcpTeamMailboxHidingUrl | `18` | Ekip Posta Kutusunu gizlemek için Exchange Kontrol Panelinin dahili URL'si. |
| InternalEcpExtensionInstallationUrl | `19` | Uzantı kurulumu için Exchange Kontrol Panelinin dahili URL'si. |
| InternalEwsUrl | `20` | Exchange Web Hizmetlerinin dahili URL'si. |
| InternalEmwsUrl | `21` | Exchange Yönetim Web Hizmetlerinin dahili URL'si. |
| InternalOABUrl | `22` | Çevrimdışı Adres Defterinin dahili URL'si. |
| InternalPhotosUrl | `23` | Fotoğraflar hizmetinin dahili URL'si. |
| InternalUMUrl | `24` | Birleşik Mesajlaşma hizmetlerinin dahili URL'si. |
| InternalWebClientUrls | `25` | Exchange web istemcisinin dahili URL'leri. |
| MailboxDN | `26` | Kullanıcının posta kutusunun posta kutusu veritabanının ayırt edici adı. |
| PublicFolderServer | `27` | Ortak Klasörler sunucusunun adı. |
| ActiveDirectoryServer | `28` | Active Directory sunucusunun adı. |
| ExternalMailboxServer | `29` | HTTP sunucusu üzerinden RPC'nin adı. |
| ExternalMailboxServerRequiresSSL | `30` | HTTP sunucusu üzerinden RPC'nin SSL gerektirip gerektirmediğini gösterir. |
| ExternalMailboxServerAuthenticationMethods | `31` | HTTP sunucusu üzerinden RPC tarafından desteklenen kimlik doğrulama yöntemleri. |
| EcpVoicemailUrlFragment | `32` | VoiceMail Özelleştirmesi için Exchange Kontrol Panelinin URL parçası. |
| EcpEmailSubscriptionsUrlFragment | `33` | E-posta Abonelikleri için Exchange Kontrol Panelinin URL parçası. |
| EcpTextMessagingUrlFragment | `34` | Metin Mesajlaşması için Exchange Kontrol Panelinin URL parçası. |
| EcpDeliveryReportUrlFragment | `35` | Teslimat Raporları için Exchange Kontrol Panelinin URL parçası. |
| EcpRetentionPolicyTagsUrlFragment | `36` | RetentionPolicy Etiketleri için Exchange Kontrol Panelinin URL parçası. |
| EcpPublishingUrlFragment | `37` | Yayınlama için Exchange Kontrol Panelinin URL parçası. |
| EcpPhotoUrlFragment | `38` | Fotoğraflar için Exchange Kontrol Panelinin URL parçası. |
| EcpConnectUrlFragment | `39` | People Connect için Exchange Kontrol Panelinin URL parçası. |
| EcpTeamMailboxUrlFragment | `40` | Ekip Posta Kutusu için Exchange Kontrol Panelinin URL parçası. |
| EcpTeamMailboxCreatingUrlFragment | `41` | Ekip Posta Kutusu oluşturmak için Exchange Kontrol Panelinin URL parçası. |
| EcpTeamMailboxEditingUrlFragment | `42` | Ekip Posta Kutusunu düzenlemek için Exchange Kontrol Panelinin URL parçası. |
| EcpExtensionInstallationUrlFragment | `43` | Uzantıyı yüklemek için Exchange Denetim Masasının URL parçası. |
| ExternalEcpUrl | `44` | Exchange Kontrol Panelinin harici URL'si. |
| ExternalEcpVoicemailUrl | `45` | VoiceMail Özelleştirme için Exchange Kontrol Panelinin harici URL'si. |
| ExternalEcpEmailSubscriptionsUrl | `46` | E-posta Abonelikleri için Exchange Kontrol Panelinin harici URL'si. |
| ExternalEcpTextMessagingUrl | `47` | Metin Mesajlaşması için Exchange Kontrol Panelinin harici URL'si. |
| ExternalEcpDeliveryReportUrl | `48` | Teslimat Raporları için Exchange Kontrol Panelinin harici URL'si. |
| ExternalEcpRetentionPolicyTagsUrl | `49` | RetentionPolicy Etiketleri için Exchange Kontrol Panelinin harici URL'si. |
| ExternalEcpPublishingUrl | `50` | Yayınlama için Exchange Kontrol Panelinin harici URL'si. |
| ExternalEcpPhotoUrl | `51` | Fotoğraflar için Exchange Kontrol Panelinin harici URL'si. |
| ExternalEcpConnectUrl | `52` | People Connect abonelikleri için Exchange Kontrol Panelinin harici URL'si. |
| ExternalEcpTeamMailboxUrl | `53` | Ekip Posta Kutusu için Exchange Kontrol Panelinin harici URL'si. |
| ExternalEcpTeamMailboxCreatingUrl | `54` | Ekip Posta Kutusu oluşturmak için Exchange Kontrol Panelinin harici URL'si. |
| ExternalEcpTeamMailboxEditingUrl | `55` | Ekip Posta Kutusunu düzenlemek için Exchange Kontrol Panelinin harici URL'si. |
| ExternalEcpTeamMailboxHidingUrl | `56` | Ekip Posta Kutusunu gizlemek için Exchange Kontrol Panelinin harici URL'si. |
| ExternalEcpExtensionInstallationUrl | `57` | Uzantı kurulumu için Exchange Kontrol Panelinin harici URL'si. |
| ExternalEwsUrl | `58` | Exchange Web Hizmetlerinin harici URL'si. |
| ExternalEmwsUrl | `59` | Exchange Yönetim Web Hizmetlerinin harici URL'si. |
| ExternalOABUrl | `60` | Çevrimdışı Adres Defterinin harici URL'si. |
| ExternalPhotosUrl | `61` | Fotoğraflar hizmetinin harici URL'si. |
| ExternalUMUrl | `62` | Birleşik Mesajlaşma hizmetlerinin harici URL'si. |
| ExternalWebClientUrls | `63` | Exchange web istemcisinin harici URL'leri. |
| CrossOrganizationSharingEnabled | `64` | Kuruluşlar arası paylaşımın etkinleştirildiğini gösterir. |
| AlternateMailboxes | `65` | Alternatif posta kutuları koleksiyonu. |
| CasVersion | `66` | İsteğe hizmet veren İstemci Erişim Sunucusunun sürümü (örn. 14.XX.YYY.ZZZ) |
| EwsSupportedSchemas | `67` | Exchange Web Hizmetleri tarafından desteklenen şema sürümlerinin virgülle ayrılmış listesi. Şema sürümü değerleri , ExchangeServerVersion numaralandırmasının değerleriyle aynı olacaktır. |
| InternalPop3Connections | `68` | Pop Protocol için dahili bağlantı ayarları listesi |
| ExternalPop3Connections | `69` | Pop Protocol için harici bağlantı ayarları listesi |
| InternalImap4Connections | `70` | imap4 protokolü için dahili bağlantı ayarları listesi |
| ExternalImap4Connections | `71` | imap4 protokolü için harici bağlantı ayarları listesi |
| InternalSmtpConnections | `72` | smtp protokolü için dahili bağlantı ayarları listesi |
| ExternalSmtpConnections | `73` | smtp protokolü için harici bağlantı ayarları listesi |
| InternalServerExclusiveConnect | `74` | "Kapalı" olarak ayarlanırsa, istemciler bu protokol aracılığıyla bağlanmamalıdır. Protokol içeriği yalnızca bilgi amaçlıdır. |
| ExternalEwsVersion | `75` | Exchange Web Hizmetleri sunucusu ExternalEwsUrl'nin sürümü şuraya işaret ediyor. |
| MobileMailboxPolicy | `76` | Mobil Posta Kutusu ilke ayarları. |
| DocumentSharingLocations | `77` | Belge paylaşım konumları ve ayarları. |
| UserMSOnline | `78` | Kullanıcı hesabının bir MSOnline hesabı olup olmadığı. |
| InternalMailboxServerAuthenticationMethods | `79` | RPC istemci sunucusu tarafından desteklenen kimlik doğrulama yöntemleri. |
| MailboxVersion | `80` | Kullanıcının posta kutusunu barındıran sunucunun sürümü. |
| SPMySiteHostURL | `81` | Sharepoint MySite Ana Bilgisayar URL'si. |
| SiteMailboxCreationURL | `82` | SharePoint'te site posta kutusu oluşturma URL'si. Outlook tarafından doğrudan SharePoint'ten site posta kutusu oluşturmak için kullanılır. |
| InternalRpcHttpServer | `83` | Dahili RPC/HTTP bağlantısı için kullanılan sunucunun FQDN'si. |
| InternalRpcHttpConnectivityRequiresSsl | `84` | Dahili RPC/HTTP bağlantısı için SSL'nin gerekli olup olmadığını gösterir. |
| InternalRpcHttpAuthenticationMethod | `85` | Dahili RPC/HTTP bağlantısı için kullanılan kimlik doğrulama yöntemi. |
| ExternalServerExclusiveConnect | `86` | "Açık" olarak ayarlanırsa, istemciler yalnızca bu protokol aracılığıyla bağlanmalıdır. |
| ExchangeRpcUrl | `87` | Ayarlanırsa, istemciler sunucuyu XTC aracılığıyla arayabilir |
| ShowGalAsDefaultView | `88` | Yanlış olarak ayarlanırsa, istemciler varsayılan olarak GAL'yi göstermemeli, kişi listesini göstermelidir. |
| AutoDiscoverSMTPAddress | `89` | Kullanıcı için Birincil SMTP Adresini Otomatik Keşfet. |
| InteropExternalEwsUrl | `90` | Exchange Web Hizmetlerinin 'birlikte çalışma' harici URL'si. Birlikte çalışma ile, alt düzey sunucuda (E2K3 ve öncesi) barındırılan posta kutularına hizmet verebilen E14 (veya üstü) sunucusuna bir URL'dir . |
| InteropExternalEwsVersion | `91` | InteropExternalEwsUrl sunucusunun sürümü. 'yi gösteriyor |
| PublicFolderInformation | `92` | Ortak Klasör (Hiyerarşi) bilgisi |
| RedirectUrl | `93` | Bu sorguyu yanıtlaması gereken Otomatik Bulma hizmetinin sürüme uygun URL'si. |
| EwsPartnerUrl | `94` | Office365 iş ortakları için Exchange Web Hizmetlerinin URL'si. |
| CertPrincipalName | `95` | SSL sertifikası adı |
| GroupingInformation | `96` | Belirli istemciler için gruplandırma ipucu. |
| InternalOutlookServiceUrl | `98` | Dahili Outlook Hizmeti URL'si |
| ExternalOutlookServiceUrl | `99` | Harici Outlook Hizmeti URL'si |

### Notlar

Sona yeni değerler ekleyin ve Microsoft.Exchange.Autodiscover.ConfigurationSettings.UserConfigurationSettingName. ile senkronize kalın

### Ayrıca bakınız

* ad alanı [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
