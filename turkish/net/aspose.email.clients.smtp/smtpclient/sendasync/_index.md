---
title: SendAsync
second_title: Aspose.Email for .NET API Referansı
description: Belirtilen mesajı oluşturur ve gönderir.
type: docs
weight: 180
url: /tr/net/aspose.email.clients.smtp/smtpclient/sendasync/
---
## SendAsync(string, string, string, string) {#sendasync_18}

Belirtilen mesajı oluşturur ve gönderir.

```csharp
public Task SendAsync(string from, string recipients, string subject, string body)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| from | String | İletiyi gönderenin adresini içeren bir Dize. |
| recipients | String | Alıcıların adresini içeren bir Dize. |
| subject | String | Mesaj konusu. |
| body | String | Bir mesaj gövdesi. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## SendAsync(MailMessage) {#sendasync_11}

Belirtilen iletiyi gönderin.

```csharp
public Task SendAsync(MailMessage message)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| message | MailMessage | Bir e-posta mesajını temsil eden MailMessage. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## SendAsync(params MailMessage[]) {#sendasync_15}

Belirtilen iletiyi gönderin.

```csharp
public Task SendAsync(params MailMessage[] messages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| messages | MailMessage[] | Gönderilecek e-posta mesajlarını temsil eden MailMessage dizisi. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## SendAsync(MailMessageCollection) {#sendasync_13}

Belirtilen ileti koleksiyonunu gönderin.

```csharp
public Task SendAsync(MailMessageCollection messages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| messages | MailMessageCollection | Mesajların toplanması. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## SendAsync(IEnumerable&lt;MailMessage&gt;) {#sendasync_16}

Belirtilen mesajları gönderin.

```csharp
public Task SendAsync(IEnumerable<MailMessage> messages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| messages | IEnumerable`1 | İleti yinelemesini destekleyen IEnumerator. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## SendAsync(IConnection, string, string, string, string) {#sendasync_7}

Belirtilen mesajı oluşturur ve gönderir.

```csharp
public Task SendAsync(IConnection connection, string from, string recipients, string subject, 
    string body)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| from | String | İletiyi gönderenin adresini içeren bir Dize. |
| recipients | String | Alıcıların adresini içeren bir Dize. |
| subject | String | Mesaj konusu. |
| body | String | Bir mesaj gövdesi. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessage) {#sendasync}

Belirtilen iletiyi gönderin.

```csharp
public Task SendAsync(IConnection connection, MailMessage message)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| message | MailMessage | Bir e-posta mesajını temsil eden MailMessage. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## SendAsync(IConnection, params MailMessage[]) {#sendasync_4}

Belirtilen iletiyi gönderin.

```csharp
public Task SendAsync(IConnection connection, params MailMessage[] messages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| messages | MailMessage[] | Gönderilecek e-posta mesajlarını temsil eden MailMessage dizisi. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessageCollection) {#sendasync_2}

Belirtilen ileti koleksiyonunu gönderin.

```csharp
public Task SendAsync(IConnection connection, MailMessageCollection messages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| messages | MailMessageCollection | Mesajların toplanması. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## SendAsync(IConnection, IEnumerable&lt;MailMessage&gt;) {#sendasync_5}

Belirtilen mesajları gönderin.

```csharp
public Task SendAsync(IConnection connection, IEnumerable<MailMessage> messages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| messages | IEnumerable`1 | İleti yinelemesini destekleyen IEnumerator. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## SendAsync(string, string, string, string, CancellationToken) {#sendasync_19}

Belirtilen mesajı oluşturur ve gönderir.

```csharp
public Task SendAsync(string from, string recipients, string subject, string body, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| from | String | İletiyi gönderenin adresini içeren bir Dize. |
| recipients | String | Alıcıların adresini içeren bir Dize. |
| subject | String | Mesaj konusu. |
| body | String | Bir mesaj gövdesi. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## SendAsync(MailMessage, CancellationToken) {#sendasync_12}

Belirtilen iletiyi gönderin.

```csharp
public Task SendAsync(MailMessage message, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| message | MailMessage | Bir e-posta mesajını temsil eden MailMessage. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## SendAsync(CancellationToken, params MailMessage[]) {#sendasync_20}

Belirtilen iletiyi gönderin.

```csharp
public Task SendAsync(CancellationToken token, params MailMessage[] messages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |
| messages | MailMessage[] | Gönderilecek e-posta mesajlarını temsil eden MailMessage dizisi. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## SendAsync(MailMessageCollection, CancellationToken) {#sendasync_14}

Belirtilen ileti koleksiyonunu gönderin.

```csharp
public Task SendAsync(MailMessageCollection messages, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| messages | MailMessageCollection | Mesajların toplanması. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## SendAsync(IEnumerable&lt;MailMessage&gt;, CancellationToken) {#sendasync_17}

Belirtilen mesajları gönderin.

```csharp
public Task SendAsync(IEnumerable<MailMessage> messages, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| messages | IEnumerable`1 | İleti yinelemesini destekleyen IEnumerator. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## SendAsync(IConnection, string, string, string, string, CancellationToken) {#sendasync_8}

Belirtilen mesajı oluşturur ve gönderir.

```csharp
public Task SendAsync(IConnection connection, string from, string recipients, string subject, 
    string body, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| from | String | İletiyi gönderenin adresini içeren bir Dize. |
| recipients | String | Alıcıların adresini içeren bir Dize. |
| subject | String | Mesaj konusu. |
| body | String | Bir mesaj gövdesi. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessage, CancellationToken) {#sendasync_1}

Belirtilen iletiyi gönderin.

```csharp
public Task SendAsync(IConnection connection, MailMessage message, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| message | MailMessage | Bir e-posta mesajını temsil eden MailMessage. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## SendAsync(IConnection, CancellationToken, params MailMessage[]) {#sendasync_9}

Belirtilen iletiyi gönderin.

```csharp
public Task SendAsync(IConnection connection, CancellationToken token, 
    params MailMessage[] messages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |
| messages | MailMessage[] | Gönderilecek e-posta mesajlarını temsil eden MailMessage dizisi. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessageCollection, CancellationToken) {#sendasync_3}

Belirtilen ileti koleksiyonunu gönderin.

```csharp
public Task SendAsync(IConnection connection, MailMessageCollection messages, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| messages | MailMessageCollection | Mesajların toplanması. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## SendAsync(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#sendasync_6}

Belirtilen mesajları gönderin.

```csharp
public Task SendAsync(IConnection connection, IEnumerable<MailMessage> messages, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| messages | IEnumerable`1 | İleti yinelemesini destekleyen IEnumerator. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## SendAsync(SmtpSend) {#sendasync_10}

```csharp
public Task SendAsync(SmtpSend parameters)
```

### Ayrıca bakınız

* class [SmtpSend](../../../aspose.email.clients.smtp.models/smtpsend)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
