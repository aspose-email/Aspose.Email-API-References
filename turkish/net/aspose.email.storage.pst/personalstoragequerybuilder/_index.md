---
title: PersonalStorageQueryBuilder
second_title: Aspose.Email for .NET API Referansı
description: pst. tarafından kullanılan arama ifadesi oluşturucusunu temsil eder
type: docs
weight: 20310
url: /tr/net/aspose.email.storage.pst/personalstoragequerybuilder/
---
## PersonalStorageQueryBuilder class

pst. tarafından kullanılan arama ifadesi oluşturucusunu temsil eder

```csharp
public sealed class PersonalStorageQueryBuilder : MailQueryBuilder
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PersonalStorageQueryBuilder](personalstoragequerybuilder)() | Yeni bir örneğini başlatır[`PersonalStorageQueryBuilder`](../personalstoragequerybuilder) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Bcc](../../aspose.email.tools.search/mailquerybuilder/bcc) { get; } | Zarf yapısının BCC alanında belirtilen dizeyi içeren iletileri bulmayı sağlayan alanı alır. |
| [Body](../../aspose.email.tools.search/mailquerybuilder/body) { get; } | İletinin gövdesinde belirtilen dizeyi içeren iletileri bulmayı sağlayan alanı alır. |
| [Cc](../../aspose.email.tools.search/mailquerybuilder/cc) { get; } | Zarf yapısının CC alanında belirtilen dizeyi içeren iletileri bulmayı sağlayan alanı alır. |
| [ContainerClass](../../aspose.email.storage.pst/personalstoragequerybuilder/containerclass) { get; } | Belirtilen mesaj sınıfına sahip klasörleri alır. |
| [ContentsCount](../../aspose.email.storage.pst/personalstoragequerybuilder/contentscount) { get; } | Belirtilen içerik sayısına sahip klasörleri arayın. |
| [DefaultEncoding](../../aspose.email.tools.search/mailquerybuilder/defaultencoding) { get; } | Sorgu oluşturucu için varsayılan kodlamayı (karakter kümesi) alır |
| [FolderName](../../aspose.email.storage.pst/personalstoragequerybuilder/foldername) { get; } | Belirtilen görünen ada sahip klasörleri arayın. |
| [From](../../aspose.email.tools.search/mailquerybuilder/from) { get; } | Zarf yapısının FROM alanında belirtilen dizeyi içeren mesajları bulmayı sağlayan alanı alır. |
| [Importance](../../aspose.email.storage.pst/personalstoragequerybuilder/importance) { get; } | Belirtilen öneme sahip iletileri arayın. |
| [InternalDate](../../aspose.email.tools.search/mailquerybuilder/internaldate) { get; } | İletileri dahili tarihe göre bulmayı sağlayan alanı alır. |
| [MessageClass](../../aspose.email.storage.pst/personalstoragequerybuilder/messageclass) { get; } | Belirtilen mesaj sınıfına sahip mesajları alır. |
| [MessageId](../../aspose.email.storage.pst/personalstoragequerybuilder/messageid) { get; } | Zarf yapısının MessageId alanında belirtilen dizeyi içeren iletileri bulmayı sağlayan alanı alır. |
| [MessageSize](../../aspose.email.storage.pst/personalstoragequerybuilder/messagesize) { get; } | Belirtilen boyuta sahip iletileri arayın. |
| [OnlyFoldersCreatedByUser](../../aspose.email.storage.pst/personalstoragequerybuilder/onlyfolderscreatedbyuser) { get; } | Kullanıcı tarafından oluşturulan klasörleri alır, yani tüm standart IPM klasörlerini hariç tutar. |
| [SentDate](../../aspose.email.tools.search/mailquerybuilder/sentdate) { get; } | Gönderilme tarihine göre mesajların bulunmasını sağlayan alanı alır. |
| [Subject](../../aspose.email.tools.search/mailquerybuilder/subject) { get; } | Zarf yapısının KONU alanında belirtilen dizeyi içeren iletileri bulmayı sağlayan alanı alır. |
| [Text](../../aspose.email.tools.search/mailquerybuilder/text) { get; } | İletinin başlıklarında (subject, from, to, cc) ve gövdesinde belirtilen dizeyi içeren iletileri bulmayı sağlayan alanı alır. |
| [To](../../aspose.email.tools.search/mailquerybuilder/to) { get; } | Zarf yapısının TO alanında belirtilen dizeyi içeren iletileri bulmayı sağlayan alanı alır. |
| [UnreadContentsCount](../../aspose.email.storage.pst/personalstoragequerybuilder/unreadcontentscount) { get; } | Belirtilen okunmamış içerik sayısına sahip klasörleri arayın. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [FindConversationThread](../../aspose.email.storage.pst/personalstoragequerybuilder/findconversationthread)(MessageInfo) | Konuşma dizisini bulur. |
| [GetQuery](../../aspose.email.tools.search/mailquerybuilder/getquery)() | Sorguyu alır. |
| [HasFlags](../../aspose.email.storage.pst/personalstoragequerybuilder/hasflags)(MapiMessageFlags) | Belirtilen bayraklara sahip iletileri arayın. |
| [HasNoFlags](../../aspose.email.storage.pst/personalstoragequerybuilder/hasnoflags)(MapiMessageFlags) | Belirtilmemiş bayraklara sahip iletileri arayın. |
| [HasNoSubfolders](../../aspose.email.storage.pst/personalstoragequerybuilder/hasnosubfolders)() | Alt klasör içermeyen klasörleri arayın. |
| [HasSubfolders](../../aspose.email.storage.pst/personalstoragequerybuilder/hassubfolders)() | Alt klasörleri içeren klasörleri arayın. |
| [Or](../../aspose.email.tools.search/mailquerybuilder/or)(MailQuery, MailQuery) | Her iki arama tuşuyla da eşleşen iletileri arayın. İki ifade (OR) arasında ayrım sağlar. |

### Ayrıca bakınız

* class [MailQueryBuilder](../../aspose.email.tools.search/mailquerybuilder)
* ad alanı [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
