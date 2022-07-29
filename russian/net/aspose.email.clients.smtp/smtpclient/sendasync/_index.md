---
title: SendAsync
second_title: Справочник по Aspose.Email для .NET API
description: Создает и отправляет указанное сообщение.
type: docs
weight: 180
url: /ru/net/aspose.email.clients.smtp/smtpclient/sendasync/
---
## SendAsync(string, string, string, string) {#sendasync_18}

Создает и отправляет указанное сообщение.

```csharp
public Task SendAsync(string from, string recipients, string subject, string body)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| from | String | Строка, содержащая адрес отправителя сообщения. |
| recipients | String | Строка, содержащая адреса получателей. |
| subject | String | Тема сообщения. |
| body | String | Тело сообщения. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## SendAsync(MailMessage) {#sendasync_11}

Отправить указанное сообщение.

```csharp
public Task SendAsync(MailMessage message)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| message | MailMessage | Объект MailMessage, представляющий сообщение электронной почты. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## SendAsync(params MailMessage[]) {#sendasync_15}

Отправить указанное сообщение.

```csharp
public Task SendAsync(params MailMessage[] messages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messages | MailMessage[] | Массив MailMessage, который представляет сообщения электронной почты для отправки. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## SendAsync(MailMessageCollection) {#sendasync_13}

Отправить указанную коллекцию сообщений.

```csharp
public Task SendAsync(MailMessageCollection messages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messages | MailMessageCollection | Сбор сообщений. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## SendAsync(IEnumerable&lt;MailMessage&gt;) {#sendasync_16}

Отправить указанные сообщения.

```csharp
public Task SendAsync(IEnumerable<MailMessage> messages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messages | IEnumerable`1 | IEnumerator, поддерживающий итерацию сообщения. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## SendAsync(IConnection, string, string, string, string) {#sendasync_7}

Создает и отправляет указанное сообщение.

```csharp
public Task SendAsync(IConnection connection, string from, string recipients, string subject, 
    string body)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| from | String | Строка, содержащая адрес отправителя сообщения. |
| recipients | String | Строка, содержащая адреса получателей. |
| subject | String | Тема сообщения. |
| body | String | Тело сообщения. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessage) {#sendasync}

Отправить указанное сообщение.

```csharp
public Task SendAsync(IConnection connection, MailMessage message)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| message | MailMessage | Объект MailMessage, представляющий сообщение электронной почты. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## SendAsync(IConnection, params MailMessage[]) {#sendasync_4}

Отправить указанное сообщение.

```csharp
public Task SendAsync(IConnection connection, params MailMessage[] messages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messages | MailMessage[] | Массив MailMessage, который представляет сообщения электронной почты для отправки. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessageCollection) {#sendasync_2}

Отправить указанную коллекцию сообщений.

```csharp
public Task SendAsync(IConnection connection, MailMessageCollection messages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messages | MailMessageCollection | Сбор сообщений. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## SendAsync(IConnection, IEnumerable&lt;MailMessage&gt;) {#sendasync_5}

Отправить указанные сообщения.

```csharp
public Task SendAsync(IConnection connection, IEnumerable<MailMessage> messages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messages | IEnumerable`1 | IEnumerator, поддерживающий итерацию сообщения. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## SendAsync(string, string, string, string, CancellationToken) {#sendasync_19}

Создает и отправляет указанное сообщение.

```csharp
public Task SendAsync(string from, string recipients, string subject, string body, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| from | String | Строка, содержащая адрес отправителя сообщения. |
| recipients | String | Строка, содержащая адреса получателей. |
| subject | String | Тема сообщения. |
| body | String | Тело сообщения. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## SendAsync(MailMessage, CancellationToken) {#sendasync_12}

Отправить указанное сообщение.

```csharp
public Task SendAsync(MailMessage message, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| message | MailMessage | Объект MailMessage, представляющий сообщение электронной почты. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## SendAsync(CancellationToken, params MailMessage[]) {#sendasync_20}

Отправить указанное сообщение.

```csharp
public Task SendAsync(CancellationToken token, params MailMessage[] messages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |
| messages | MailMessage[] | Массив MailMessage, который представляет сообщения электронной почты для отправки. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## SendAsync(MailMessageCollection, CancellationToken) {#sendasync_14}

Отправить указанную коллекцию сообщений.

```csharp
public Task SendAsync(MailMessageCollection messages, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messages | MailMessageCollection | Сбор сообщений. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## SendAsync(IEnumerable&lt;MailMessage&gt;, CancellationToken) {#sendasync_17}

Отправить указанные сообщения.

```csharp
public Task SendAsync(IEnumerable<MailMessage> messages, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messages | IEnumerable`1 | IEnumerator, поддерживающий итерацию сообщения. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## SendAsync(IConnection, string, string, string, string, CancellationToken) {#sendasync_8}

Создает и отправляет указанное сообщение.

```csharp
public Task SendAsync(IConnection connection, string from, string recipients, string subject, 
    string body, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| from | String | Строка, содержащая адрес отправителя сообщения. |
| recipients | String | Строка, содержащая адреса получателей. |
| subject | String | Тема сообщения. |
| body | String | Тело сообщения. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessage, CancellationToken) {#sendasync_1}

Отправить указанное сообщение.

```csharp
public Task SendAsync(IConnection connection, MailMessage message, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| message | MailMessage | Объект MailMessage, представляющий сообщение электронной почты. |
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

## SendAsync(IConnection, CancellationToken, params MailMessage[]) {#sendasync_9}

Отправить указанное сообщение.

```csharp
public Task SendAsync(IConnection connection, CancellationToken token, 
    params MailMessage[] messages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |
| messages | MailMessage[] | Массив MailMessage, который представляет сообщения электронной почты для отправки. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## SendAsync(IConnection, MailMessageCollection, CancellationToken) {#sendasync_3}

Отправить указанную коллекцию сообщений.

```csharp
public Task SendAsync(IConnection connection, MailMessageCollection messages, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messages | MailMessageCollection | Сбор сообщений. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessageCollection](../../../aspose.email/mailmessagecollection)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

---

## SendAsync(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#sendasync_6}

Отправить указанные сообщения.

```csharp
public Task SendAsync(IConnection connection, IEnumerable<MailMessage> messages, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messages | IEnumerable`1 | IEnumerator, поддерживающий итерацию сообщения. |
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

## SendAsync(SmtpSend) {#sendasync_10}

```csharp
public Task SendAsync(SmtpSend parameters)
```

### Смотрите также

* class [SmtpSend](../../../aspose.email.clients.smtp.models/smtpsend)
* class [SmtpClient](../../smtpclient)
* пространство имен [Aspose.Email.Clients.Smtp](../../smtpclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
