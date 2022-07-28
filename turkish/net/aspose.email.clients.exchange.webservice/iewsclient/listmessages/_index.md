---
title: ListMessages
second_title: Aspose.Email for .NET API Referansı
description: Mesajları listeler.
type: docs
weight: 1140
url: /tr/net/aspose.email.clients.exchange.webservice/iewsclient/listmessages/
---
## ListMessages(string) {#listmessages_2}

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
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions) {#listmessages_3}

Mesajları listeler.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folder | String | Dosya. |
| options | ExchangeListMessagesOptions | Listeleme ayarlarını belirtir |

### Geri dönüş değeri

A[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Ayrıca bakınız

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(string, int) {#listmessages_8}

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
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(string, int, ExchangeListMessagesOptions) {#listmessages_9}

Mesajları listeler.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    ExchangeListMessagesOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folder | String | Dosya. |
| maxNumberOfMessages | Int32 | Maksimum mesaj sayısı |
| options | ExchangeListMessagesOptions | Listeleme ayarlarını belirtir |

### Geri dönüş değeri

A[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Ayrıca bakınız

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(string, string, bool) {#listmessages_13}

Belirtilen klasördeki iletileri listeleyin

```csharp
public ExchangeMessageInfoCollection ListMessages(string mailbox, string folder, bool recursive)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| mailbox | String | Klasör kimliği sınıfını başlatmak için kullanılan posta kutusu. |
| folder | String | İletileri aramak için bir klasör |
| recursive | Boolean | Özyinelemeli listeleme olup olmadığını gösterir |

### Geri dönüş değeri

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) belirtilen klasörden mesajları içeren

### Ayrıca bakınız

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(string, string, MailQuery) {#listmessages_12}

Belirtilen klasördeki iletileri listeleyin.

```csharp
public ExchangeMessageInfoCollection ListMessages(string mailbox, string folder, MailQuery query)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| mailbox | String | Klasör kimliği sınıfını başlatmak için kullanılan posta kutusu. |
| folder | String | İletileri aramak için bir klasör. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) mesaj arama kriterlerini temsil eder. |

### Geri dönüş değeri

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)belirtilen klasörden iletileri içeren.

### Ayrıca bakınız

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_7}

Belirtilen klasördeki iletileri listeleyin

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, bool recursive)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folder | String | İletileri aramak için bir klasör |
| recursive | Boolean | Özyinelemeli listeleme olup olmadığını gösterir |

### Geri dönüş değeri

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) belirtilen klasörden mesajları içeren

### Ayrıca bakınız

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions, IEnumerable&lt;PropertyDescriptor&gt;) {#listmessages_4}

Belirtilen klasördeki iletileri listeleyin

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options, IEnumerable<PropertyDescriptor> extendedProperties)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folder | String | İletileri aramak için bir klasör |
| options | ExchangeListMessagesOptions | Listeleme ayarlarını belirtir |
| extendedProperties | IEnumerable`1 | Alınan mesajların genişletilmiş özellikleri |

### Geri dönüş değeri

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) belirtilen klasörden mesajları içeren

### Ayrıca bakınız

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor)
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery) {#listmessages_5}

Belirtilen klasördeki iletileri listeleyin.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folder | String | İletileri aramak için bir klasör. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) mesaj arama kriterlerini temsil eder. |

### Geri dönüş değeri

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) belirtilen klasörden iletileri içeren.

### Ayrıca bakınız

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery, bool) {#listmessages_6}

Belirtilen klasördeki iletileri listeleyin.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query, bool recursive)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folder | String | İletileri aramak için bir klasör. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) mesaj arama kriterlerini temsil eder. |
| recursive | Boolean | Özyinelemeli listeleme olup olmadığını gösterir. |

### Geri dönüş değeri

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) belirtilen klasörden iletileri içeren.

### Ayrıca bakınız

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(string, int, MailQuery, bool) {#listmessages_11}

Belirtilen klasördeki iletileri listeleyin.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    MailQuery query, bool recursive)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folder | String | İletileri aramak için bir klasör. |
| maxNumberOfMessages | Int32 | Maksimum mesaj sayısı. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) mesaj arama kriterlerini temsil eder. |
| recursive | Boolean | Özyinelemeli listeleme olup olmadığını gösterir. |

### Geri dönüş değeri

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)belirtilen klasörden iletileri içeren.

### Ayrıca bakınız

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_1}

Belirtilen klasördeki iletileri listeleyin.

```csharp
public ExchangeMessageInfoCollection ListMessages(IEnumerable<string> iDs)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| iDs | IEnumerable`1 | Mesaj kimliklerinin numaralandırılması |

### Geri dönüş değeri

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) içeren mesajlar içerir.

### Ayrıca bakınız

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

Gelen kutusu klasöründeki iletileri listeleyin.

```csharp
public ExchangeMessageInfoCollection ListMessages()
```

### Geri dönüş değeri

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) gelen kutusu klasöründen.

### Ayrıca bakınız

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## ListMessages(string, int, MailQuery) {#listmessages_10}

Belirtilen klasördeki iletileri listeleyin.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    MailQuery query)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| folder | String | İletileri aramak için bir klasör. |
| maxNumberOfMessages | Int32 | Maksimum mesaj sayısı. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) mesaj arama kriterlerini temsil eder. |

### Geri dönüş değeri

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)belirtilen klasörden iletileri içeren.

### Ayrıca bakınız

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
