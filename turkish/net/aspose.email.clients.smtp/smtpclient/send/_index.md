---
title: Send
second_title: Aspose.Email for .NET API Referansı
description: Belirtilen mesajı oluşturur ve gönderir.
type: docs
weight: 170
url: /tr/net/aspose.email.clients.smtp/smtpclient/send/
---
## Send(string, string, string, string) {#send_9}

Belirtilen mesajı oluşturur ve gönderir.

```csharp
public void Send(string from, string recipients, string subject, string body)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| from | String | İletiyi gönderenin adresini içeren bir Dize. |
| recipients | String | Alıcıların adresini içeren bir Dize. |
| subject | String | Mesaj konusu. |
| body | String | Bir mesaj gövdesi. |

### Ayrıca bakınız

* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## Send(MailMessage) {#send_5}

Belirtilen iletiyi gönderin.

```csharp
public void Send(MailMessage message)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| message | MailMessage | Bir e-posta mesajını temsil eden MailMessage. |

### Ayrıca bakınız

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## Send(params MailMessage[]) {#send_7}

Belirtilen iletiyi gönderin.

```csharp
public void Send(params MailMessage[] messages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| messages | MailMessage[] | Gönderilecek e-posta mesajlarını temsil eden MailMessage dizisi. |

### Ayrıca bakınız

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## Send(MailMessageCollection) {#send_6}

Belirtilen ileti koleksiyonunu gönderin.

```csharp
public void Send(MailMessageCollection messages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| messages | MailMessageCollection | Mesajların toplanması. |

### Ayrıca bakınız

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## Send(IEnumerable&lt;MailMessage&gt;) {#send_8}

Belirtilen mesajları gönderin.

```csharp
public void Send(IEnumerable<MailMessage> messages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| messages | IEnumerable`1 | İleti yinelemesini destekleyen IEnumerator. |

### Ayrıca bakınız

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## Send(IConnection, string, string, string, string) {#send_4}

Belirtilen mesajı oluşturur ve gönderir.

```csharp
public void Send(IConnection connection, string from, string recipients, string subject, 
    string body)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| from | String | İletiyi gönderenin adresini içeren bir Dize. |
| recipients | String | Alıcıların adresini içeren bir Dize. |
| subject | String | Mesaj konusu. |
| body | String | Bir mesaj gövdesi. |

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## Send(IConnection, MailMessage) {#send}

Belirtilen iletiyi gönderin.

```csharp
public void Send(IConnection connection, MailMessage message)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| message | MailMessage | Bir e-posta mesajını temsil eden MailMessage. |

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## Send(IConnection, params MailMessage[]) {#send_2}

Belirtilen iletiyi gönderin.

```csharp
public void Send(IConnection connection, params MailMessage[] messages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| messages | MailMessage[] | Gönderilecek e-posta mesajlarını temsil eden MailMessage dizisi. |

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## Send(IConnection, MailMessageCollection) {#send_1}

Belirtilen ileti koleksiyonunu gönderin.

```csharp
public void Send(IConnection connection, MailMessageCollection messages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| messages | MailMessageCollection | Mesajların toplanması. |

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

---

## Send(IConnection, IEnumerable&lt;MailMessage&gt;) {#send_3}

Belirtilen mesajları gönderin.

```csharp
public void Send(IConnection connection, IEnumerable<MailMessage> messages)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| connection | IConnection | Bir sunucuya bağlantı |
| messages | IEnumerable`1 | İleti yinelemesini destekleyen IEnumerator. |

### Ayrıca bakınız

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* ad alanı [Aspose.Email.Clients.Smtp](../../smtpclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
