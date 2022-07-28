---
title: ListMessagesByPage
second_title: Aspose.Email for .NET API Referansı
description: Belirtilen klasördeki iletileri listeleyin.
type: docs
weight: 1150
url: /tr/net/aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage/
---
## ListMessagesByPage(string, int) {#listmessagesbypage_4}

Belirtilen klasördeki iletileri listeleyin.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, int itemsPerPage)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folder | String | İletileri aramak için bir klasör. |
| itemsPerPage | Int32 | Sayfadaki bir dizi öğe |

### Geri dönüş değeri

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)belirtilen klasörden iletileri içeren.

### Ayrıca bakınız

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesByPage(string, MailQuery, int) {#listmessagesbypage_2}

Belirtilen klasördeki iletileri listeleyin.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, MailQuery query, int itemsPerPage)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folder | String | İletileri aramak için bir klasör. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) Bu, arama kriterlerini temsil eder. |
| itemsPerPage | Int32 | Sayfadaki bir dizi öğe |

### Geri dönüş değeri

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)belirtilen klasörden iletileri içeren.

### Ayrıca bakınız

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesByPage(string, int, int) {#listmessagesbypage_5}

Belirtilen klasördeki iletileri listeleyin.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, int itemsPerPage, int offset)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folder | String | İletileri aramak için bir klasör. |
| itemsPerPage | Int32 | Sayfadaki bir dizi öğe |
| offset | Int32 | Görünümdeki sonraki sayfanın bir ofseti |

### Geri dönüş değeri

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)belirtilen klasörden iletileri içeren.

### Ayrıca bakınız

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesByPage(string, MailQuery, int, int) {#listmessagesbypage_3}

Belirtilen klasördeki iletileri listeleyin.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, MailQuery query, int itemsPerPage, 
    int offset)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folder | String | İletileri aramak için bir klasör. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) Bu, arama kriterlerini temsil eder. |
| itemsPerPage | Int32 | Sayfadaki bir dizi öğe |
| offset | Int32 | Görünümdeki sonraki sayfanın bir ofseti |

### Geri dönüş değeri

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)belirtilen klasörden iletileri içeren.

### Ayrıca bakınız

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesByPage(string, int, int, ExchangeListMessagesOptions) {#listmessagesbypage_6}

Belirtilen klasördeki iletileri listeleyin.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, int itemsPerPage, int pageOffset, 
    ExchangeListMessagesOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folder | String | İletileri aramak için bir klasör. |
| itemsPerPage | Int32 | Sayfadaki bir dizi öğe |
| pageOffset | Int32 | Görünümdeki sonraki öğenin bir ofseti |
| options | ExchangeListMessagesOptions | Listeleme ayarlarını belirtir |

### Geri dönüş değeri

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)belirtilen klasörden iletileri içeren.

### Ayrıca bakınız

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesByPage(string, PageInfo) {#listmessagesbypage}

Belirtilen klasördeki iletileri listeleyin.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, PageInfo pageInfo)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folder | String | İletileri aramak için bir klasör. |
| pageInfo | PageInfo | Bir sayfa bilgisi |

### Geri dönüş değeri

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)belirtilen klasörden iletileri içeren.

### Ayrıca bakınız

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [PageInfo](../../../aspose.email.clients/pageinfo)
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessagesByPage(string, PageInfo, ExchangeListMessagesOptions) {#listmessagesbypage_1}

Belirtilen klasördeki iletileri listeleyin.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, PageInfo pageInfo, 
    ExchangeListMessagesOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folder | String | İletileri aramak için bir klasör. |
| pageInfo | PageInfo | Bir sayfa bilgisi |
| options | ExchangeListMessagesOptions | Listeleme ayarlarını belirtir |

### Geri dönüş değeri

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)belirtilen klasörden iletileri içeren.

### Ayrıca bakınız

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [PageInfo](../../../aspose.email.clients/pageinfo)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
