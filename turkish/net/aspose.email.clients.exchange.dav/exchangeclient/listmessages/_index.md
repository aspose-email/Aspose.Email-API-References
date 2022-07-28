---
title: ListMessages
second_title: Aspose.Email for .NET API Referansı
description: Mesajları listeler.
type: docs
weight: 280
url: /tr/net/aspose.email.clients.exchange.dav/exchangeclient/listmessages/
---
## ListMessages(string) {#listmessages}

Mesajları listeler.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folder | String | Dosya. |

### Geri dönüş değeri

A[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Ayrıca bakınız

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* ad alanı [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(string, int) {#listmessages_4}

Mesajları listeler.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folder | String | Dosya. |
| maxNumberOfMessages | Int32 | Maksimum mesaj sayısı |

### Geri dönüş değeri

A[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Ayrıca bakınız

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* ad alanı [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(string, string, bool) {#listmessages_7}

Mesajları listeler.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, string messageClass, 
    bool recursive)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folder | String | Dosya. |
| messageClass | String | Mesaj sınıfı. |
| recursive | Boolean | ayarlanırsa`doğru` [yinelemeli]. |

### Ayrıca bakınız

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* ad alanı [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_3}

Belirtilen klasördeki iletileri listeleyin

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, bool recursive)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folder | String | klasör Uri |
| recursive | Boolean | Özyinelemeli listeleme olup olmadığını gösterir. |

### Geri dönüş değeri

Mesaj bilgisi koleksiyonu

### Ayrıca bakınız

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* ad alanı [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(string, string) {#listmessages_6}

Mesajları listeler.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, string query)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folder | String | Dosya. |
| query | String | Sorgu. |

### Ayrıca bakınız

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* ad alanı [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery, bool) {#listmessages_2}

Mesajları listeler.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query, bool recursive)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folder | String | İletileri içeren klasörün Uri'si. |
| query | MailQuery | bu[`MailQuery`](../../../aspose.email.tools.search/mailquery) Bu, arama kriterlerini temsil eder. |
| recursive | Boolean | Özyinelemeli listeleme olup olmadığını gösterir. |

### Geri dönüş değeri

Mesaj bilgisi koleksiyonu.

### Ayrıca bakınız

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ExchangeClient](../../exchangeclient)
* ad alanı [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions) {#listmessages_1}

Belirtilen klasördeki posta mesajını listeler.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folder | String | klasör url'si |
| options | ExchangeListMessagesOptions | Listeleme ayarlarını belirtir |

### Geri dönüş değeri

A[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) Toplamak.

### Ayrıca bakınız

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [ExchangeClient](../../exchangeclient)
* ad alanı [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(string, int, ExchangeListMessagesOptions) {#listmessages_5}

Belirtilen klasördeki iletileri listeleyin

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    ExchangeListMessagesOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folder | String | klasör Uri |
| maxNumberOfMessages | Int32 | Maksimum mesaj sayısı |
| options | ExchangeListMessagesOptions | Listeleme ayarlarını belirtir |

### Geri dönüş değeri

Mesaj bilgisi koleksiyonu

### Ayrıca bakınız

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [ExchangeClient](../../exchangeclient)
* ad alanı [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
