---
title: MarkAsJunk
second_title: Aspose.Email for .NET API Referansı
description: MarkAsJunk yöntemi posta iletilerini önemsiz posta klasörüne taşır ve ileti göndericisini engeller.
type: docs
weight: 1270
url: /tr/net/aspose.email.clients.exchange.webservice/iewsclient/markasjunk/
---
## MarkAsJunk(bool, params string[]) {#markasjunk_3}

MarkAsJunk yöntemi, posta iletilerini önemsiz posta klasörüne taşır ve ileti göndericisini engeller.

```csharp
public string[] MarkAsJunk(bool isJunk, params string[] messageUriEn)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| isJunk | Boolean | İletilerin önemsiz posta olarak işaretlenip işaretlenmediğini gösterir. true değeri ileti göndereni engelleme listesine eklerse. false değeri, mesajı göndereni engelleme listesinden kaldırırsa. |
| messageUriEn | String[] | uri mesaj dizisi |

### Geri dönüş değeri

Önemsiz posta klasörüne taşınan ileti kimliği dizisini döndürür.

### Ayrıca bakınız

* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## MarkAsJunk(bool, bool, params string[]) {#markasjunk_1}

MarkAsJunk yöntemi, posta iletilerini önemsiz posta klasörüne taşır ve ileti göndericisini engeller.

```csharp
public string[] MarkAsJunk(bool isJunk, bool moveItem, params string[] messageUriEn)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| isJunk | Boolean | İletilerin önemsiz posta olarak işaretlenip işaretlenmediğini gösterir. true değeri ileti göndereni engelleme listesine eklerse. false değeri, mesajı göndereni engelleme listesinden kaldırırsa. |
| moveItem | Boolean | İletilerin istenmeyen posta klasörüne taşınıp taşınmadığını gösterir. |
| messageUriEn | String[] | uri mesaj dizisi |

### Geri dönüş değeri

Önemsiz posta klasörüne taşınan ileti kimliği dizisini döndürür.

### Ayrıca bakınız

* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## MarkAsJunk(bool, IEnumerable&lt;string&gt;) {#markasjunk_2}

MarkAsJunk yöntemi, posta iletilerini önemsiz posta klasörüne taşır ve ileti göndericisini engeller.

```csharp
public string[] MarkAsJunk(bool isJunk, IEnumerable<string> messageUriEn)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| isJunk | Boolean | İletilerin önemsiz posta olarak işaretlenip işaretlenmediğini gösterir. true değeri ileti göndereni engelleme listesine eklerse. false değeri, mesajı göndereni engelleme listesinden kaldırırsa. |
| messageUriEn | IEnumerable`1 | uri mesajının numaralandırılması |

### Geri dönüş değeri

Önemsiz posta olarak işaretlenen iletinin öğe kimliğini döndürür.

### Ayrıca bakınız

* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## MarkAsJunk(bool, bool, IEnumerable&lt;string&gt;) {#markasjunk}

MarkAsJunk yöntemi, posta iletilerini önemsiz posta klasörüne taşır ve ileti göndericisini engeller.

```csharp
public string[] MarkAsJunk(bool isJunk, bool moveItem, IEnumerable<string> messageUriEn)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| isJunk | Boolean | İletilerin önemsiz posta olarak işaretlenip işaretlenmediğini gösterir. true değeri ileti göndereni engelleme listesine eklerse. false değeri, mesajı göndereni engelleme listesinden kaldırırsa. |
| moveItem | Boolean | İletilerin istenmeyen posta klasörüne taşınıp taşınmadığını gösterir. |
| messageUriEn | IEnumerable`1 | uri mesajının numaralandırılması |

### Geri dönüş değeri

Önemsiz posta klasörüne taşınan ileti kimliği dizisini döndürür.

### Ayrıca bakınız

* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

---

## MarkAsJunk(bool, bool, IEnumerable&lt;string&gt;, out string[], out string[], out string[]) {#markasjunk_4}

MarkAsJunk yöntemi, posta iletilerini önemsiz posta klasörüne taşır ve ileti göndericisini engeller.

```csharp
public void MarkAsJunk(bool isJunk, bool moveItem, IEnumerable<string> messageUriEn, 
    out string[] movedMessageIds, out string[] failedMessageIds, out string[] errorMessages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| isJunk | Boolean | İletilerin önemsiz posta olarak işaretlenip işaretlenmediğini gösterir. true değeri ileti göndereni engelleme listesine eklerse. false değeri, mesajı göndereni engelleme listesinden kaldırırsa. |
| moveItem | Boolean | İletilerin istenmeyen posta klasörüne taşınıp taşınmadığını gösterir. |
| messageUriEn | IEnumerable`1 | uri mesajının numaralandırılması |
| movedMessageIds | String[]& | Önemsiz posta klasörüne taşınan ileti kimliği dizisini döndürür. |
| failedMessageIds | String[]& | Önemsiz posta klasörüne taşınmamış ileti kimliği dizisini döndürür. |
| errorMessages | String[]& | Başarısız işlemler için hata mesajları |

### Ayrıca bakınız

* interface [IEWSClient](../../iewsclient)
* ad alanı [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
