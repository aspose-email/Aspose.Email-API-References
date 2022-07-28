---
title: ForwardAsync
second_title: Aspose.Email for .NET API Referansı
description: Belirtilen mesajı alıcıya iletir
type: docs
weight: 140
url: /tr/net/aspose.email.clients.smtp/smtpclient/forwardasync/
---
## ForwardAsync(IConnection, string, string, MailMessage) {#forwardasync_4}

Belirtilen mesajı alıcıya iletir

```csharp
public Task ForwardAsync(IConnection connection, string sender, string recipient, 
    MailMessage message)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sender | String | Yönlendirilen mesajın göndericisi. |
| recipient | String | Yönlendirilen mesajın alıcısı. |
| message | MailMessage | Bir yönlendirme için mesaj. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, MailMessage) {#forwardasync}

Belirtilen mesajı alıcıya iletir

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    MailMessage message)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sender | String | Yönlendirilen mesajın göndericisi. |
| recipients | MailAddressCollection | İletilen mesajın alıcıları. |
| message | MailMessage | Bir yönlendirme için mesaj. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## ForwardAsync(string, string, MailMessage) {#forwardasync_10}

Belirtilen mesajı alıcıya iletir

```csharp
public Task ForwardAsync(string sender, string recipient, MailMessage message)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sender | String | Yönlendirilen mesajın göndericisi. |
| recipient | String | Yönlendirilen mesajın alıcısı. |
| message | MailMessage | Bir yönlendirme için mesaj. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, MailMessage) {#forwardasync_6}

Belirtilen mesajı alıcıya iletir

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, MailMessage message)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sender | String | Yönlendirilen mesajın göndericisi. |
| recipients | MailAddressCollection | İletilen mesajın alıcıları. |
| message | MailMessage | Bir yönlendirme için mesaj. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, Stream) {#forwardasync_2}

Belirtilen mesajı alıcıya iletir

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    Stream messageStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sender | String | Yönlendirilen mesajın göndericisi. |
| recipients | MailAddressCollection | İletilen mesajın alıcıları. |
| messageStream | Stream | İletiyi eml biçiminde temsil eden akış. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, Stream) {#forwardasync_8}

Belirtilen mesajı alıcıya iletir

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, Stream messageStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sender | String | Yönlendirilen mesajın göndericisi. |
| recipients | MailAddressCollection | İletilen mesajın alıcıları. |
| messageStream | Stream | İletiyi eml biçiminde temsil eden akış. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, string, MailMessage, CancellationToken) {#forwardasync_5}

Belirtilen mesajı alıcıya iletir

```csharp
public Task ForwardAsync(IConnection connection, string sender, string recipient, 
    MailMessage message, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sender | String | Yönlendirilen mesajın göndericisi. |
| recipient | String | Yönlendirilen mesajın alıcısı. |
| message | MailMessage | Bir yönlendirme için mesaj. |
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

## ForwardAsync(IConnection, string, MailAddressCollection, MailMessage, CancellationToken) {#forwardasync_1}

Belirtilen mesajı alıcıya iletir

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    MailMessage message, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sender | String | Yönlendirilen mesajın göndericisi. |
| recipients | MailAddressCollection | İletilen mesajın alıcıları. |
| message | MailMessage | Bir yönlendirme için mesaj. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## ForwardAsync(string, string, MailMessage, CancellationToken) {#forwardasync_11}

Belirtilen mesajı alıcıya iletir

```csharp
public Task ForwardAsync(string sender, string recipient, MailMessage message, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sender | String | Yönlendirilen mesajın göndericisi. |
| recipient | String | Yönlendirilen mesajın alıcısı. |
| message | MailMessage | Bir yönlendirme için mesaj. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, MailMessage, CancellationToken) {#forwardasync_7}

Belirtilen mesajı alıcıya iletir

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, MailMessage message, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sender | String | Yönlendirilen mesajın göndericisi. |
| recipients | MailAddressCollection | İletilen mesajın alıcıları. |
| message | MailMessage | Bir yönlendirme için mesaj. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, Stream, CancellationToken) {#forwardasync_3}

Belirtilen mesajı alıcıya iletir

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    Stream messageStream, CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| sender | String | Yönlendirilen mesajın göndericisi. |
| recipients | MailAddressCollection | İletilen mesajın alıcıları. |
| messageStream | Stream | İletiyi eml biçiminde temsil eden akış. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, Stream, CancellationToken) {#forwardasync_9}

Belirtilen mesajı alıcıya iletir

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, Stream messageStream, 
    CancellationToken token)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| sender | String | Yönlendirilen mesajın göndericisi. |
| recipients | MailAddressCollection | İletilen mesajın alıcıları. |
| messageStream | Stream | İletiyi eml biçiminde temsil eden akış. |
| token | CancellationToken | İşlemlerin iptal edilmesi gerektiğine dair bildirim yayar. |

### Geri dönüş değeri

Bu işlem için temsilci ile görev nesnesi

### Ayrıca bakınız

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
