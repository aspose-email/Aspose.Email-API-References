---
title: GetContactAsync
second_title: Aspose.Email for .NET API Referansı
description: Belirtilen tanımlayıcıya göre iletişim bilgilerini alır.
type: docs
weight: 320
url: /tr/net/aspose.email.clients.exchange.webservice/iasyncewsclient/getcontactasync/
---
## IAsyncEwsClient.GetContactAsync method

Belirtilen tanımlayıcıya göre iletişim bilgilerini alır.

```csharp
public Task<Contact> GetContactAsync(string contactId, 
    ExchangeListContactsOptions options = ExchangeListContactsOptions.FetchPhoto, 
    CancellationToken cancellationToken = default)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| contactId | String | Kişi tanımlayıcısı. |
| options | ExchangeListContactsOptions | Kişi alma ayarları. |
| cancellationToken | CancellationToken | İptal belirteci. |

### Geri dönüş değeri

İletişim bilgileri

### Ayrıca bakınız

* class [Contact](../../../aspose.email.personalinfo/contact)
* enum [ExchangeListContactsOptions](../../exchangelistcontactsoptions)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->