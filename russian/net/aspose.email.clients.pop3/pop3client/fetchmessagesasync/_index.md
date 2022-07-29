---
title: FetchMessagesAsync
second_title: Справочник по Aspose.Email для .NET API
description: Получает сообщения асинхронно
type: docs
weight: 140
url: /ru/net/aspose.email.clients.pop3/pop3client/fetchmessagesasync/
---
## FetchMessagesAsync(IEnumerable&lt;int&gt;) {#fetchmessagesasync_4}

Получает сообщения асинхронно

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IEnumerable<int> sequenceNumbers)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumbers | IEnumerable`1 | Порядковые номера сообщений |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## FetchMessagesAsync(IEnumerable&lt;string&gt;) {#fetchmessagesasync_6}

Получает сообщения асинхронно

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IEnumerable<string> uids)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uids | IEnumerable`1 | Порядковые номера сообщений |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## FetchMessagesAsync(IConnection, IEnumerable&lt;int&gt;) {#fetchmessagesasync}

Получает сообщения асинхронно

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IConnection connection, 
    IEnumerable<int> sequenceNumbers)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceNumbers | IEnumerable`1 | Порядковые номера сообщений |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## FetchMessagesAsync(IConnection, IEnumerable&lt;string&gt;) {#fetchmessagesasync_2}

Получает сообщения асинхронно

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IConnection connection, IEnumerable<string> uids)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uids | IEnumerable`1 | Порядковые номера сообщений |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## FetchMessagesAsync(IEnumerable&lt;int&gt;, CancellationToken) {#fetchmessagesasync_5}

Получает сообщения асинхронно

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IEnumerable<int> sequenceNumbers, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumbers | IEnumerable`1 | Порядковые номера сообщений |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## FetchMessagesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#fetchmessagesasync_7}

Получает сообщения асинхронно

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IEnumerable<string> uids, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uids | IEnumerable`1 | Порядковые номера сообщений |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## FetchMessagesAsync(IConnection, IEnumerable&lt;int&gt;, CancellationToken) {#fetchmessagesasync_1}

Получает сообщения асинхронно

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IConnection connection, 
    IEnumerable<int> sequenceNumbers, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceNumbers | IEnumerable`1 | Порядковые номера сообщений |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## FetchMessagesAsync(IConnection, IEnumerable&lt;string&gt;, CancellationToken) {#fetchmessagesasync_3}

Получает сообщения асинхронно

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IConnection connection, 
    IEnumerable<string> uids, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uids | IEnumerable`1 | Порядковые номера сообщений |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
