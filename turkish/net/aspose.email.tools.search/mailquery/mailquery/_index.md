---
title: MailQuery
second_title: Aspose.Email for .NET API Referansı
description: Yeni bir örneğini başlatırMailQueryaspose.email.tools.search/mailquery sınıf.
type: docs
weight: 10
url: /tr/net/aspose.email.tools.search/mailquery/mailquery/
---
## MailQuery(string) {#constructor}

Yeni bir örneğini başlatır[`MailQuery`](../../mailquery) sınıf.

```csharp
public MailQuery(string queryString)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| queryString | String | Sorgu dizesi. |

### Notlar

Sorgu dizesi aşağıdaki görünüme sahip olmalıdır.

Basit bir ifade örneği:

'&lt;Alan adı&gt;' &lt;Karşılaştırma operatörü&gt; '&lt;Alan değeri&gt;',

where &lt;Alan Adı&gt; - filtrelemenin yapıldığı bir mesaj alanının adı, &lt;Karşılaştırma operatörü&gt; - adlarından da anlaşılacağı gibi karşılaştırma operatörleri, mesaj alanını ve belirtilen değeri karşılaştırmaya izin verir, &lt;Alan değeri&gt; - değer bir mesaj alanıyla karşılaştırılabilir.

Basit ifadelerin sayısı bir bileşik ifade yapabilir, ör.: (&lt;Basit ifade 1&gt; &amp; &lt;Basit ifade 2&gt;) &#x7C; &lt;Basit ifade 3&gt;,

where "&amp;" - mantıksal-VE operatörü, "&#x7C;" - mantıksal-VEYA operatör

Şu anda aşağıdaki değerlere alan adı olarak izin verilmektedir (&lt;Alan adı&gt;):

"Kime" - iletinin TO alanını temsil eder, "Metin" - iletinin başlığındaki veya gövdesindeki dizeyi temsil eder, "Bcc" - iletinin BCC alanını temsil eder, "Gövde" - mesajın gövdesi, "Cc" - mesajın CC alanını temsil eder, "Kimden" - mesajın bir Gönderen alanını temsil eder, "Konu" - mesajın konusundaki bir dizeyi temsil eder, "InternalDate" - dahili bir mesajı temsil eder mesaj tarihi, "SentDate" - mesajın gönderildiği tarihi temsil eder

Ayrıca, IMAP protokolü için aşağıdaki alan adlarına izin verilir:

"Yanıtlandı" - iletinin /Yanıtlandı bayrağını temsil eder "Görüntülendi" - iletinin /Görünen bayrağını temsil eder "İşaretli" - iletinin /İşaretli bayrağını temsil eder "Taslak" - iletinin /Taslak bayrağını temsil eder "Silindi" - temsil eder a Silinmiş/ ileti bayrağı "Son" - ileti Silinmiş/ bayrağını temsil eder "MessageSize" - ileti boyutunu (bayt olarak) temsil eder

Ayrıca, Exchange için aşağıdaki alan adlarına izin verilir:

"IsRead" - İletinin okunup okunmadığını belirtir "HasAttachment" - İletinin ekleri olup olmadığını gösterir "IsSubmitted" - İletinin Giden Kutusuna gönderilip gönderilmediğini gösterir "ContentClass" - item içerik sınıfını temsil eder

Ayrıca, pst/ost dosyaları için aşağıdaki alan adlarına izin verilir:

"MessageClass" - class mesajını temsil eder "ContainerClass" - class klasör kapsayıcısını temsil eder "Önem" - Bir mesajın önemini temsil eder "MessageSize" - message boyutunu (bayt olarak) temsil eder "FolderName" - bir klasör adını temsilContensCount - klasördeki toplam öğe sayısını temsil eder "UnreadContentsCount" - klasördeki okunmamış öğelerin sayısını temsil eder. "Alt klasörler" - Klasörün alt klasörleri olup olmadığını gösterir "Okundu" - ileti okundu olarak işaretlenir " HasEki" - iletinin en az bir eki var "Gönderilmedi" - ileti hala oluşturuluyor "Değiştirilmemiş" - ileti ilk kaydedildiğinden (gönderilmemişse) veya teslim edildiğinden (gönderildiyse) beri değiştirilmedi "Benden " - iletiyi alan kullanıcı aynı zamanda iletiyi gönderen kullanıcıydı "Yeniden Gönder" - ileti, teslim edilemedi raporuyla yeniden gönderme işlemi için bir istek içeriyor_x000 d_ "NotifyRead" - mesajı gönderen kullanıcı, bir alıcı onu ilk okuduğunda bildirim istedi "NotifyUnread" - mesajı gönderen kullanıcı, bir alıcı okumadan sildiğinde veya Mesaj nesnesinin süresi dolduğunda bildirim istedi "EverRead" - mesaj en az bir kez okundu

Alan değeri (&lt;Alan değeri&gt;) aşağıdaki değerleri alabilir: Metin alanları için - herhangi bir dize, Tarih türü alanları için - "d-MMM-yyy" biçimindeki dize, ör. "10-Feb-2009", Bayraklar için (boole türü alanlar) - "True" veya "False"

### Örnekler

```csharp
MailQuery mailQuery = new MailQuery("(('From' Contains 'test@test.com' | 'Seen' = 'True') & 'SentDate' >= '12-May-2010')");
```

### Ayrıca bakınız

* class [MailQuery](../../mailquery)
* ad alanı [Aspose.Email.Tools.Search](../../mailquery)
* toplantı [Aspose.Email](../../../)

---

## MailQuery(string, string) {#constructor_1}

Yeni bir örneğini başlatır[`MailQuery`](../../mailquery) sınıf.

```csharp
public MailQuery(string queryString, string orderByString)
```

### Notlar

Sıralama sorgusu dizesi aşağıdaki görünüme sahip olmalıdır.

Basit bir ifade örneği:

'&lt;Alan adı&gt;' Siparişe Göre ['ASC'&#x7C;'DESC'],

where &lt;Alan Adı&gt; - sıralamanın yapıldığı bir mesaj alanının adı, ['ASC'&#x7C;'DESC'] - sıralama operatörleri, Artan veya Azalan sıralamaya izin verir,

Basit ifadelerin sayısı bir bileşik ifade yapabilir, ör.: (&lt;Basit ifade 1&gt; &amp; &lt;Basit ifade 2&gt;),

### Örnekler

```csharp
MailQuery mailQuery = new MailQuery("", "(('From' OrderBy 'ASC') & ('SentDate' OrderBy 'DESC'))");
```

### Ayrıca bakınız

* class [MailQuery](../../mailquery)
* ad alanı [Aspose.Email.Tools.Search](../../mailquery)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
