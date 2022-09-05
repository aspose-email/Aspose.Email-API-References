---
title: ForwardAsync
second_title: Справочник по Aspose.Email для .NET API
description: Пересылает указанное сообщение получателю
type: docs
weight: 140
url: /ru/net/aspose.email.clients.smtp/smtpclient/forwardasync/
---
## ForwardAsync(IConnection, string, string, MailMessage) {#forwardasync_4}

Пересылает указанное сообщение получателю

```csharp
public Task ForwardAsync(IConnection connection, string sender, string recipient, 
    MailMessage message)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sender | String | Отправитель пересылаемого сообщения. |
| recipient | String | Получатель пересылаемого сообщения. |
| message | MailMessage | Сообщение для переадресации. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, MailMessage) {#forwardasync}

Пересылает указанное сообщение получателю

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    MailMessage message)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sender | String | Отправитель пересылаемого сообщения. |
| recipients | MailAddressCollection | Получатели пересылаемого сообщения. |
| message | MailMessage | Сообщение для переадресации. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## ForwardAsync(string, string, MailMessage) {#forwardasync_10}

Пересылает указанное сообщение получателю

```csharp
public Task ForwardAsync(string sender, string recipient, MailMessage message)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sender | String | Отправитель пересылаемого сообщения. |
| recipient | String | Получатель пересылаемого сообщения. |
| message | MailMessage | Сообщение для переадресации. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, MailMessage) {#forwardasync_6}

Пересылает указанное сообщение получателю

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, MailMessage message)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sender | String | Отправитель пересылаемого сообщения. |
| recipients | MailAddressCollection | Получатели пересылаемого сообщения. |
| message | MailMessage | Сообщение для переадресации. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, Stream) {#forwardasync_2}

Пересылает указанное сообщение получателю

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    Stream messageStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sender | String | Отправитель пересылаемого сообщения. |
| recipients | MailAddressCollection | Получатели пересылаемого сообщения. |
| messageStream | Stream | Поток, представляющий сообщение в формате eml. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, Stream) {#forwardasync_8}

Пересылает указанное сообщение получателю

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, Stream messageStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sender | String | Отправитель пересылаемого сообщения. |
| recipients | MailAddressCollection | Получатели пересылаемого сообщения. |
| messageStream | Stream | Поток, представляющий сообщение в формате eml. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, string, MailMessage, CancellationToken) {#forwardasync_5}

Пересылает указанное сообщение получателю

```csharp
public Task ForwardAsync(IConnection connection, string sender, string recipient, 
    MailMessage message, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sender | String | Отправитель пересылаемого сообщения. |
| recipient | String | Получатель пересылаемого сообщения. |
| message | MailMessage | Сообщение для переадресации. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, MailMessage, CancellationToken) {#forwardasync_1}

Пересылает указанное сообщение получателю

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    MailMessage message, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sender | String | Отправитель пересылаемого сообщения. |
| recipients | MailAddressCollection | Получатели пересылаемого сообщения. |
| message | MailMessage | Сообщение для переадресации. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## ForwardAsync(string, string, MailMessage, CancellationToken) {#forwardasync_11}

Пересылает указанное сообщение получателю

```csharp
public Task ForwardAsync(string sender, string recipient, MailMessage message, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sender | String | Отправитель пересылаемого сообщения. |
| recipient | String | Получатель пересылаемого сообщения. |
| message | MailMessage | Сообщение для переадресации. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, MailMessage, CancellationToken) {#forwardasync_7}

Пересылает указанное сообщение получателю

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, MailMessage message, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sender | String | Отправитель пересылаемого сообщения. |
| recipients | MailAddressCollection | Получатели пересылаемого сообщения. |
| message | MailMessage | Сообщение для переадресации. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## ForwardAsync(IConnection, string, MailAddressCollection, Stream, CancellationToken) {#forwardasync_3}

Пересылает указанное сообщение получателю

```csharp
public Task ForwardAsync(IConnection connection, string sender, MailAddressCollection recipients, 
    Stream messageStream, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sender | String | Отправитель пересылаемого сообщения. |
| recipients | MailAddressCollection | Получатели пересылаемого сообщения. |
| messageStream | Stream | Поток, представляющий сообщение в формате eml. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## ForwardAsync(string, MailAddressCollection, Stream, CancellationToken) {#forwardasync_9}

Пересылает указанное сообщение получателю

```csharp
public Task ForwardAsync(string sender, MailAddressCollection recipients, Stream messageStream, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sender | String | Отправитель пересылаемого сообщения. |
| recipients | MailAddressCollection | Получатели пересылаемого сообщения. |
| messageStream | Stream | Поток, представляющий сообщение в формате eml. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailAddressCollection](../../../aspose.email/mailaddresscollection)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
