---
title: FetchMessagesAsync
second_title: Справочник по Aspose.Email для .NET API
description: Выбирает сообщения асинхронно
type: docs
weight: 680
url: /ru/net/aspose.email.clients.imap/imapclient/fetchmessagesasync/
---
## FetchMessagesAsync(IEnumerable&lt;int&gt;) {#fetchmessagesasync_4}

Выбирает сообщения асинхронно

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
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## FetchMessagesAsync(IEnumerable&lt;string&gt;) {#fetchmessagesasync_6}

Выбирает сообщения асинхронно

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
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## FetchMessagesAsync(IConnection, IEnumerable&lt;int&gt;) {#fetchmessagesasync}

Асинхронно получает сообщения

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IConnection connection, 
    IEnumerable<int> sequenceNumbers)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| sequenceNumbers | IEnumerable`1 | Порядковые номера сообщений |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## FetchMessagesAsync(IConnection, IEnumerable&lt;string&gt;) {#fetchmessagesasync_2}

Асинхронно получает сообщения

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IConnection connection, IEnumerable<string> uids)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| uids | IEnumerable`1 | Порядковые номера сообщений |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## FetchMessagesAsync(IEnumerable&lt;int&gt;, CancellationToken) {#fetchmessagesasync_5}

Выбирает сообщения асинхронно

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
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## FetchMessagesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#fetchmessagesasync_7}

Выбирает сообщения асинхронно

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
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## FetchMessagesAsync(IConnection, IEnumerable&lt;int&gt;, CancellationToken) {#fetchmessagesasync_1}

Асинхронно получает сообщения

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IConnection connection, 
    IEnumerable<int> sequenceNumbers, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| sequenceNumbers | IEnumerable`1 | Порядковые номера сообщений |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## FetchMessagesAsync(IConnection, IEnumerable&lt;string&gt;, CancellationToken) {#fetchmessagesasync_3}

Асинхронно получает сообщения

```csharp
public Task<IList<MailMessage>> FetchMessagesAsync(IConnection connection, 
    IEnumerable<string> uids, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| uids | IEnumerable`1 | Порядковые номера сообщений |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
