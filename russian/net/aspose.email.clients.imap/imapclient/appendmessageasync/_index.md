---
title: AppendMessageAsync
second_title: Справочник по Aspose.Email для .NET API
description: Загружает почтовое сообщение в текущую папку Если текущая папка не указана используется папка по умолчанию.
type: docs
weight: 370
url: /ru/net/aspose.email.clients.imap/imapclient/appendmessageasync/
---
## AppendMessageAsync(IConnection, MailMessage) {#appendmessageasync}

Загружает почтовое сообщение в текущую папку Если текущая папка не указана, используется папка по умолчанию.

```csharp
public Task<string> AppendMessageAsync(IConnection connection, MailMessage message)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| message | MailMessage | Почтовое сообщение для загрузки |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, string, MailMessage) {#appendmessageasync_3}

Загружает почтовое сообщение в указанную папку

```csharp
public Task<string> AppendMessageAsync(IConnection connection, string folderName, 
    MailMessage message)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| folderName | String | Папка, в которую будет поступать почтовое сообщение |
| message | MailMessage | Почтовое сообщение для загрузки |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, string) {#appendmessageasync_2}

Загружает почтовое сообщение в текущую папку Если текущая папка не указана, используется папка по умолчанию.

```csharp
public Task<string> AppendMessageAsync(IConnection connection, string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| fileName | String | Имя файла (*.eml) почтового сообщения, которое будет загружено |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, string, string) {#appendmessageasync_5}

Загружает почтовое сообщение в указанную папку

```csharp
public Task<string> AppendMessageAsync(IConnection connection, string folderName, string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| folderName | String | Папка, в которую будет поступать почтовое сообщение |
| fileName | String | Имя файла (*.eml) почтового сообщения, которое будет загружено |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessageAsync(MailMessage) {#appendmessageasync_8}

Загружает почтовое сообщение в текущую папку Если текущая папка не указана, используется папка по умолчанию.

```csharp
public Task<string> AppendMessageAsync(MailMessage message)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| message | MailMessage | Почтовое сообщение для загрузки |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessageAsync(string, MailMessage) {#appendmessageasync_11}

Загружает почтовое сообщение в указанную папку

```csharp
public Task<string> AppendMessageAsync(string folderName, MailMessage message)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderName | String | Папка, в которую будет поступать почтовое сообщение |
| message | MailMessage | Почтовое сообщение для загрузки |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessageAsync(string) {#appendmessageasync_10}

Загружает почтовое сообщение в текущую папку Если текущая папка не указана, используется папка по умолчанию.

```csharp
public Task<string> AppendMessageAsync(string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла (*.eml) почтового сообщения, которое будет загружено |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessageAsync(string, string) {#appendmessageasync_13}

Загружает почтовое сообщение в указанную папку

```csharp
public Task<string> AppendMessageAsync(string folderName, string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderName | String | Папка, в которую будет поступать почтовое сообщение |
| fileName | String | Имя файла (*.eml) почтового сообщения, которое будет загружено |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, MailMessage, CancellationToken) {#appendmessageasync_1}

Загружает почтовое сообщение в текущую папку Если текущая папка не указана, используется папка по умолчанию.

```csharp
public Task<string> AppendMessageAsync(IConnection connection, MailMessage message, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| message | MailMessage | Почтовое сообщение для загрузки |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, string, MailMessage, CancellationToken) {#appendmessageasync_4}

Загружает почтовое сообщение в указанную папку

```csharp
public Task<string> AppendMessageAsync(IConnection connection, string folderName, 
    MailMessage message, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| folderName | String | Папка, в которую будет поступать почтовое сообщение |
| message | MailMessage | Почтовое сообщение для загрузки |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, string, CancellationToken) {#appendmessageasync_7}

Загружает почтовое сообщение в текущую папку Если текущая папка не указана, используется папка по умолчанию.

```csharp
public Task<string> AppendMessageAsync(IConnection connection, string fileName, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| fileName | String | Имя файла (*.eml) почтового сообщения, которое будет загружено |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessageAsync(IConnection, string, string, CancellationToken) {#appendmessageasync_6}

Загружает почтовое сообщение в указанную папку

```csharp
public Task<string> AppendMessageAsync(IConnection connection, string folderName, string fileName, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| folderName | String | Папка, в которую будет поступать почтовое сообщение |
| fileName | String | Имя файла (*.eml) почтового сообщения, которое будет загружено |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessageAsync(MailMessage, CancellationToken) {#appendmessageasync_9}

Загружает почтовое сообщение в текущую папку Если текущая папка не указана, используется папка по умолчанию.

```csharp
public Task<string> AppendMessageAsync(MailMessage message, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| message | MailMessage | Почтовое сообщение для загрузки |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessageAsync(string, MailMessage, CancellationToken) {#appendmessageasync_12}

Загружает почтовое сообщение в указанную папку

```csharp
public Task<string> AppendMessageAsync(string folderName, MailMessage message, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderName | String | Папка, в которую будет поступать почтовое сообщение |
| message | MailMessage | Почтовое сообщение для загрузки |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessageAsync(string, CancellationToken) {#appendmessageasync_15}

Загружает почтовое сообщение в текущую папку Если текущая папка не указана, используется папка по умолчанию.

```csharp
public Task<string> AppendMessageAsync(string fileName, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла (*.eml) почтового сообщения, которое будет загружено |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessageAsync(string, string, CancellationToken) {#appendmessageasync_14}

Загружает почтовое сообщение в указанную папку

```csharp
public Task<string> AppendMessageAsync(string folderName, string fileName, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderName | String | Папка, в которую будет поступать почтовое сообщение |
| fileName | String | Имя файла (*.eml) почтового сообщения, которое будет загружено |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
