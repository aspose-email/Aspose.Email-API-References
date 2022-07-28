---
title: Provision
second_title: Aspose.Email for .NET API Referansı
description: ActiveSync protokolünün ad alanını sağlayın
type: docs
weight: 1710
url: /tr/net/aspose.email.clients.activesync.transportlayer/provision/
---
## Provision enumeration

ActiveSync protokolünün ad alanını sağlayın

```csharp
public enum Provision
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| Provision | `5` | Aygıtın yetenekleri ve izinleri. |
| Policies | `6` | Güvenlik ilkeleri koleksiyonu. |
| Policy | `7` | Bir güvenlik politikası. |
| PolicyType | `8` | İlke ayarlarının sağlanacağı biçimi belirtir. |
| PolicyKey | `9` | İstemcideki ilke ayarlarının durumunu işaretlemek için sunucu tarafından kullanılır. |
| Data | `10` | Bir ilkenin ayarları. |
| Status | `11` | Bir komutun belirli bölümlerinin başarısını veya başarısızlığını gösterir. |
| RemoteWipe | `12` | Sunucudan gelen bir uzaktan silme yönergesini veya bir istemcinin uzaktan silme yönergesini onaylamasını belirtir. |
| EASProvisionDoc | `13` | Cihaz temel hazırlığı için güvenlik ayarları koleksiyonu. |
| DevicePasswordEnabled | `14` | İstemci aygıtının parola gerektirip gerektirmediğini gösterir. |
| AlphanumericDevicePasswordRequired | `15` | Bir istemci aygıtın alfasayısal parola gerektirip gerektirmediğini gösterir. |
| RequireStorageCardEncryption | `16` | Cihazın, depolama kartında depolanan içeriği şifrelemesi gerekip gerekmediğini gösterir. |
| PasswordRecoveryEnabled | `17` | Ayarlar komutu kullanılarak sunucuya gönderilecek bir kurtarma parolasının etkinleştirilip etkinleştirilmeyeceğini belirtir. |
| AttachmentsEnabled | `19` | E-posta eklerinin etkin olup olmadığını gösterir. |
| MinDevicePasswordLength | `20` | Kullanıcının girebileceği minimum cihaz parolası uzunluğu |
| MaxInactivityTimeDeviceLock | `21` | Cihaz kendini kilitlemeden önce hareketsiz kalacağı saniye sayısı. |
| MaxDevicePasswordFailedAttempts | `22` | Cihaz silinmeden önce izin verilen parola hatası sayısı. |
| MaxAttachmentSize | `23` | Güvenlik ilkesi tarafından belirlenen maksimum ek boyutu. |
| AllowSimpleDevicePassword | `24` | Cihazın basit parolalara izin verip vermediği. |
| DevicePasswordExpiration | `25` | Parolanın, ilke tarafından belirlendiği şekilde, belirtilen gün sayısından sonra süresinin dolup dolmadığı. |
| DevicePasswordHistory | `26` | İstemci cihazının yeniden kullanımı önlemek için sakladığı önceden kullanılan minimum parola sayısı. |
| AllowStorageCard | `27` | Cihazın depolama kartı kullanımına izin verip vermediği. |
| AllowCamera | `28` | Cihazın yerleşik kamera kullanımına izin verip vermediği. |
| RequireDeviceEncryption | `29` | Cihazın şifreleme kullanıp kullanmadığı. |
| AllowUnsignedApplications | `30` | Aygıtın imzasız uygulamaların yürütülmesine izin verip vermediği. |
| AllowUnsignedInstallationPackages | `31` | Aygıtın imzasız dolap (.cab) dosyalarının kurulmasına izin verip vermediği. |
| MinDevicePasswordComplexCharacters | `32` | Parolada bulunan minimum karmaşık karakter (sayılar ve semboller) sayısı. |
| AllowWiFi | `33` | Cihazın Wi-Fi bağlantılarının kullanımına izin verip vermediği. |
| AllowTextMessaging | `34` | Cihazın Kısa Mesaj Hizmetine (SMS)/metin mesajlaşmaya izin verip vermediği. |
| AllowPOPIMAPEmail | `35` | Cihazın POP/IMAP e-postasına erişime izin verip vermediği. |
| AllowBluetooth | `36` | Cihazda Bluetooth ve eller serbest profillerine izin verilip verilmediği. |
| AllowIrDA | `37` | Cihazın IrDA (kızılötesi) bağlantılarının kullanımına izin verip vermediği. |
| RequireManualSyncWhenRoaming | `38` | Cihaz dolaşımdayken cihazın manuel senkronizasyon gerektirip gerektirmediği. |
| AllowDesktopSync | `39` | Aygıtın Desktop ActiveSync ile senkronizasyona izin verip vermediği. |
| MaxCalendarAgeFilter | `40` | Senkronize edilebilecek maksimum takvim günü sayısı. |
| AllowHTMLEmail | `41` | Cihazın HTML biçimli e-posta kullanıp kullanmadığı. |
| MaxEmailAgeFilter | `42` | Senkronizasyon için e-posta yaş sınırı. |
| MaxEmailBodyTruncationSize | `43` | Düz metin biçimli e-posta iletileri için kesme boyutu. |
| MaxEmailHTMLBodyTruncationSize | `44` | HTML biçimli e-posta iletileri için kesme boyutu. |
| RequireSignedSMIMEMessages | `45` | Cihazın imzalı S/MIME mesajları göndermesi gerekip gerekmediği. |
| RequireEncryptedSMIMEMessages | `46` | Cihazın şifreli mesajlar göndermesi gerekip gerekmediği. |
| RequireSignedSMIMEAlgorithm | `47` | Bir mesaj imzalanırken kullanılacak algoritma. |
| RequireEncryptionSMIMEAlgorithm | `48` | Mesaj şifrelenirken kullanılacak algoritma. |
| AllowSMIMEEncryptionAlgorithmNegotiation | `49` | Cihazın imzalama için kullanılacak şifreleme algoritması üzerinde anlaşıp anlaşamayacağı. |
| AllowSMIMESoftCerts | `50` | Aygıtın giden iletileri imzalamak için yazılım sertifikalarını kullanıp kullanmadığı. |
| AllowBrowser | `51` | Cihazın bir web tarayıcısının kullanımına izin verip vermediği. |
| AllowConsumerEmail | `52` | Cihazın kişisel e-posta kullanımına izin verip vermediği. |
| AllowRemoteDesktop | `53` | Aygıtın Uzak Masaüstü kullanımına izin verip vermediği. |
| AllowInternetSharing | `54` | Cihazın İnternet Paylaşımı kullanımına izin verip vermediği. |
| UnapprovedInROMApplicationList | `55` | Yürütülmesi onaylanmayan ROM içi uygulamaların listesi. |
| ApplicationName | `56` | Yürütme için onaylanmamış bir ROM içi uygulamanın (.exe dosyası) adı. |
| ApprovedApplicationList | `57` | Yürütülmesi onaylanan RAM içi uygulamaların listesi. |
| Hash | `58` | Yürütme için onaylanmış bir bellek içi uygulamanın SHA-1 karması. |

### Ayrıca bakınız

* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
