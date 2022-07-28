---
title: RightsManagementLicense
second_title: Aspose.Email for .NET API Referansı
description: Eşitlenmekte olan e-posta iletisine uygulanan şablon için hak ilkesi şablon ayarlarını içerir.
type: docs
weight: 1900
url: /tr/net/aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/
---
## RightsManagementLicense class

Eşitlenmekte olan e-posta iletisine uygulanan şablon için hak ilkesi şablon ayarlarını içerir.

```csharp
public class RightsManagementLicense
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [RightsManagementLicense](rightsmanagementlicense)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ContentExpiryDate](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/contentexpirydate) { get; set; } | Lisansın sona erme tarihini belirtir. Hak yönetimi lisansının ayarlanmış bir sona erme tarihi yoksa ContentExpiryDate öğesi "9999-12-30T23:59:59.999Z" olarak ayarlanır. |
| [ContentOwner](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/contentowner) { get; set; } | Kullanıcı e-posta iletisini ilettiğinde, yanıtladığında veya yanıtladığında orijinal e-postanın içeriğinin kullanıcı tarafından değiştirilip değiştirilemeyeceğini belirtir. E-posta kullanıcı tarafından değiştirilebiliyorsa değer DOĞRU'dur; aksi takdirde, FALSE. YANLIŞ değeri, istemcinin orijinal haklarla yönetilen e-posta mesajını SmartForward veya SmartReply isteğinden DIŞLAMASI ZORUNLUDUR. Sonuç olarak, EditAllowed öğesi FALSE olarak ayarlanmışsa satır içi yanıtlara izin verilmez. EditAllowed, YANLIŞ olarak ayarlandığında ve bir SmartForward veya SmartReply isteğinde ReplaceMime mevcut olmadığında, sunucu, haklarla yönetilen orijinal e-posta mesajını yeni mesaja ek olarak ekler. Tersine, ReplaceMime varsa, sunucu haklarla yönetilen orijinal e-posta iletisini ek olarak eklemez. |
| [EditAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/editallowed) { get; set; } | Kullanıcı e-posta iletisini ilettiğinde, yanıtladığında veya yanıtladığında orijinal e-postanın içeriğinin kullanıcı tarafından değiştirilip değiştirilemeyeceğini belirtir. E-posta kullanıcı tarafından değiştirilebiliyorsa değer DOĞRU'dur; aksi takdirde, FALSE. YANLIŞ değeri, istemcinin orijinal haklarla yönetilen e-posta mesajını SmartForward veya SmartReply isteğinden DIŞLAMASI ZORUNLUDUR. Sonuç olarak, EditAllowed öğesi FALSE olarak ayarlanmışsa satır içi yanıtlara izin verilmez. EditAllowed, FALSE olarak ayarlandığında ve ReplaceMime bir SmartForward veya SmartReply isteğinde mevcut olmadığında, sunucu, haklarla yönetilen orijinal e-posta mesajını yeni mesaja ek olarak ekler. Tersine, composemail:ReplaceMime varsa, sunucu haklarla yönetilen orijinal e-posta iletisini ek olarak eklemez. |
| [ExportAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/exportallowed) { get; set; } | E-posta iletisindeki IRM korumasının kullanıcı tarafından kaldırılıp kaldırılamayacağını belirtir. Kullanıcı, e-posta iletisinin tamamını ilettiğinde, yanıtladığında veya yanıtladığında kullanıcı IRM korumasını kaldırabiliyorsa, değer DOĞRU'dur; aksi takdirde, FALSE. Hakları yönetilen bir e-posta iletisi SmartForward veya SmartReply komutu kullanılarak yönlendirilir veya yanıtlanırsa, aşağıdaki koşullar değerlendirilir: - Orijinal hak ilkesi şablonunda ExportAllowed öğesi TRUE olarak ayarlanır - Yeni iletisi "Kısıtlama Yok" şablonuna ayarlanmıştır (ŞablonKimliği değeri "00000000-0000-0000-0000-000000000000") Her iki koşul da doğruysa, giden iletiden IRM koruması kaldırılır. Orijinal ileti, IRM korumasını korur. |
| [ExtractAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/extractallowed) { get; set; } | Kullanıcının e-posta mesajının içeriğini kopyalayıp kopyalayamayacağını belirtir. E-posta mesajının içeriği kesilebiliyorsa, kopyalanabiliyorsa veya içerikten ekran görüntüsü alınabiliyorsa değer DOĞRU'dur; aksi takdirde, YANLIŞ. |
| [ForwardAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/forwardallowed) { get; set; } | Kullanıcının e-posta mesajını iletip iletmeyeceğini belirtir. Kullanıcı e-posta mesajını iletebiliyorsa değer DOĞRU'dur; aksi takdirde, YANLIŞ. |
| [ModifyRecipientsAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/modifyrecipientsallowed) { get; set; } | Kullanıcı, e-posta iletisini ilettiğinde veya yanıt verdiğinde alıcı listesini değiştirip değiştiremeyeceğini belirtir. Kullanıcı alıcı (1) listesini değiştirebiliyorsa değer DOĞRU'dur; aksi takdirde, YANLIŞ. |
| [Owner](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/owner) { get; set; } | Kullanıcının e-posta iletisinin sahibi olup olmadığını belirtir. Kullanıcı, e-posta iletisinin sahibiyse değer DOĞRU'dur; aksi halde YANLIŞ. DOĞRU değeri, kimliği doğrulanmış kullanıcının bu ileti üzerinde sahip haklarına sahip olduğunu gösterir. Bu öğe yalnızca bilgi sunumu amacıyla kullanılır. İzin verilen öğeler (EditAllowed, ReplyAllowed, vb.), belirli bir eyleme izin verilip verilmediğini veya kısıtlanıp kısıtlanmadığını değerlendirmek için kullanılır. |
| [PrintAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/printallowed) { get; set; } | E-postanın kullanıcı tarafından yazdırılıp yazdırılamayacağını belirtir. Bu öğe, bir e-posta iletisinin yazdırılması için istemci desteğini göstermez; yalnızca, istemci yazdırmayı destekliyorsa e-posta iletisinin yazdırılıp yazdırılamayacağını belirtir. E-posta kullanıcı tarafından yazdırılabiliyorsa, değer DOĞRU'dur; aksi takdirde, YANLIŞ. |
| [ProgrammaticAccessAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/programmaticaccessallowed) { get; set; } | E-posta mesajının içeriğine üçüncü şahıs uygulamaları tarafından programlı olarak erişilip erişilemeyeceğini belirtir. Üçüncü şahıs uygulamaları e-posta mesajının içeriğine programlı olarak erişebiliyorsa değer DOĞRU'dur; aksi halde YANLIŞ. DOĞRU değeri, korunan içeriğe diğer uygulamalar tarafından erişilebilir olup olmadığını gösterir. Korumalı içerik, ileti gövdesinden ve eklerden oluşur. |
| [ReplyAllAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/replyallallowed) { get; set; } | Kullanıcının, orijinal e-posta iletisinin tüm alıcılarına (1) yanıt verip veremeyeceğini belirtir. Kullanıcı, e-posta iletisinin tüm alıcılarını yanıtlayabiliyorsa, değer DOĞRU'dur; aksi takdirde, YANLIŞ. |
| [ReplyAllowed](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/replyallowed) { get; set; } | Kullanıcının e-posta mesajını yanıtlamasına izin verilip verilmediğini belirtir. Kullanıcı e-posta mesajını yanıtlayabiliyorsa değer DOĞRU'dur; aksi takdirde, YANLIŞ. |
| [TemplateDescription](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templatedescription) { get; set; } | Üst RightsManagementLicense öğesi tarafından temsil edilen hak ilkesi şablonunun açıklamasını içerir. Bu öğe yalnızca bilgilendirme amaçlı sunum amacıyla kullanılır. TemplateDescription öğesinin maksimum uzunluğu 10240 karakterdir. |
| [TemplateID](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templateid) { get; set; } | Üst RightsManagementLicense öğesi tarafından temsil edilen hak ilkesi şablonunu tanımlayan bir dize içerir. |
| [TemplateName](../../aspose.email.clients.activesync.transportlayer/rightsmanagementlicense/templatename) { get; set; } | Üst RightsManagementLicense öğesi tarafından temsil edilen hak ilkesi şablonunun adını belirtir. Bu öğe yalnızca bilgilendirme amaçlı sunum amacıyla kullanılır. TemplateName öğesinin maksimum uzunluğu 256 karakterdir. |

### Ayrıca bakınız

* ad alanı [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
