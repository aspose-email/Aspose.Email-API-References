---
title: Send
second_title: Справочник по Aspose.Email для .NET API
description: Создает и отправляет указанное сообщение.
type: docs
weight: 170
url: /ru/net/aspose.email.clients.smtp/smtpclient/send/
---
## Send(string, string, string, string) {#send_9}

Создает и отправляет указанное сообщение.

```csharp
public void Send(string from, string recipients, string subject, string body)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| from | String | Строка, содержащая адрес отправителя сообщения. |
| recipients | String | Строка, содержащая адреса получателей. |
| subject | String | Тема сообщения. |
| body | String | Тело сообщения. |

### Смотрите также

* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## Send(MailMessage) {#send_5}

Отправить указанное сообщение.

```csharp
public void Send(MailMessage message)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| message | MailMessage | Объект MailMessage, представляющий сообщение электронной почты. |

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## Send(params MailMessage[]) {#send_7}

Отправить указанное сообщение.

```csharp
public void Send(params MailMessage[] messages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messages | MailMessage[] | Массив MailMessage, который представляет сообщения электронной почты для отправки. |

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## Send(MailMessageCollection) {#send_6}

Отправить указанную коллекцию сообщений.

```csharp
public void Send(MailMessageCollection messages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messages | MailMessageCollection | Сбор сообщений. |

### Смотрите также

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## Send(IEnumerable&lt;MailMessage&gt;) {#send_8}

Отправить указанные сообщения.

```csharp
public void Send(IEnumerable<MailMessage> messages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messages | IEnumerable`1 | IEnumerator, поддерживающий итерацию сообщения. |

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## Send(IConnection, string, string, string, string) {#send_4}

Создает и отправляет указанное сообщение.

```csharp
public void Send(IConnection connection, string from, string recipients, string subject, 
    string body)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| from | String | Строка, содержащая адрес отправителя сообщения. |
| recipients | String | Строка, содержащая адреса получателей. |
| subject | String | Тема сообщения. |
| body | String | Тело сообщения. |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## Send(IConnection, MailMessage) {#send}

Отправить указанное сообщение.

```csharp
public void Send(IConnection connection, MailMessage message)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| message | MailMessage | Объект MailMessage, представляющий сообщение электронной почты. |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## Send(IConnection, params MailMessage[]) {#send_2}

Отправить указанное сообщение.

```csharp
public void Send(IConnection connection, params MailMessage[] messages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messages | MailMessage[] | Массив MailMessage, который представляет сообщения электронной почты для отправки. |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## Send(IConnection, MailMessageCollection) {#send_1}

Отправить указанную коллекцию сообщений.

```csharp
public void Send(IConnection connection, MailMessageCollection messages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messages | MailMessageCollection | Сбор сообщений. |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## Send(IConnection, IEnumerable&lt;MailMessage&gt;) {#send_3}

Отправить указанные сообщения.

```csharp
public void Send(IConnection connection, IEnumerable<MailMessage> messages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messages | IEnumerable`1 | IEnumerator, поддерживающий итерацию сообщения. |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
