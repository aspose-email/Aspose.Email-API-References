---
title: AppendMessagesAsync
second_title: Справочник по Aspose.Email для .NET API
description: Загружает почтовые сообщения в текущую папку
type: docs
weight: 390
url: /ru/net/aspose.email.clients.imap/imapclient/appendmessagesasync/
---
## AppendMessagesAsync(IConnection, string, IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync_2}

Загружает почтовые сообщения в текущую папку

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, string folderName, 
    IEnumerable<MailMessage> messages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| folderName | String | Папка, в которую будет поступать почтовое сообщение |
| messages | IEnumerable`1 | Перечисление сообщений электронной почты для загрузки |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessagesAsync(IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync_4}

Загружает почтовое сообщение в текущую папку Если текущая папка не указана, используется папка по умолчанию.

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IEnumerable<MailMessage> messages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messages | IEnumerable`1 | Перечисление сообщений электронной почты для загрузки |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessagesAsync(string, IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync_6}

Загружает почтовые сообщения в текущую папку

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(string folderName, 
    IEnumerable<MailMessage> messages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderName | String | Папка, в которую будет поступать почтовое сообщение |
| messages | IEnumerable`1 | Перечисление сообщений электронной почты для загрузки |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessagesAsync(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_1}

Загружает почтовые сообщения в текущую папку Если текущая папка не указана, используется папка по умолчанию.

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, 
    IEnumerable<MailMessage> messages, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messages | IEnumerable`1 | Перечисление сообщений электронной почты для загрузки |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessagesAsync(IConnection, string, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_3}

Загружает почтовые сообщения в текущую папку

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, string folderName, 
    IEnumerable<MailMessage> messages, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| folderName | String | Папка, в которую будет поступать почтовое сообщение |
| messages | IEnumerable`1 | Перечисление сообщений электронной почты для загрузки |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessagesAsync(IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_5}

Загружает почтовое сообщение в текущую папку Если текущая папка не указана, используется папка по умолчанию.

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IEnumerable<MailMessage> messages, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messages | IEnumerable`1 | Перечисление сообщений электронной почты для загрузки |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessagesAsync(string, IEnumerable&lt;MailMessage&gt;, CancellationToken) {#appendmessagesasync_7}

Загружает почтовые сообщения в текущую папку

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(string folderName, 
    IEnumerable<MailMessage> messages, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderName | String | Папка, в которую будет поступать почтовое сообщение |
| messages | IEnumerable`1 | Перечисление сообщений электронной почты для загрузки |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [AppendMessagesResult](../../appendmessagesresult)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessagesAsync(IConnection, IEnumerable&lt;MailMessage&gt;) {#appendmessagesasync}

Загружает почтовые сообщения в текущую папку Если текущая папка не указана, используется папка по умолчанию.

```csharp
public Task<AppendMessagesResult> AppendMessagesAsync(IConnection connection, 
    IEnumerable<MailMessage> messages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messages | IEnumerable`1 | Перечисление сообщений электронной почты для загрузки |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [AppendMessagesResult](../../appendmessagesresult)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
