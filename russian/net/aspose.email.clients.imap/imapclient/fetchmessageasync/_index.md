---
title: FetchMessageAsync
second_title: Справочник по Aspose.Email для .NET API
description: Получает сообщение
type: docs
weight: 660
url: /ru/net/aspose.email.clients.imap/imapclient/fetchmessageasync/
---
## FetchMessageAsync(IConnection, int) {#fetchmessageasync}

Получает сообщение

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, int sequenceNumber)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceNumber | Int32 | Порядковый номер сообщения |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, int, bool) {#fetchmessageasync_1}

Получает сообщение

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, int sequenceNumber, 
    bool ignoreAttachment)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| ignoreAttachment | Boolean | Значение, определяющее, следует ли загружать вложения. Если установлено значение`истинный` , то извлекаются только заголовки сообщений, тело сообщения и информация о вложениях. Содержимое вложения не загружено |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## FetchMessageAsync(int) {#fetchmessageasync_6}

Получает сообщение

```csharp
public Task<MailMessage> FetchMessageAsync(int sequenceNumber)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщения |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## FetchMessageAsync(int, bool) {#fetchmessageasync_7}

Получает сообщение

```csharp
public Task<MailMessage> FetchMessageAsync(int sequenceNumber, bool ignoreAttachment)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| ignoreAttachment | Boolean | Значение, определяющее, следует ли загружать вложения. Если установлено значение`истинный` , то извлекаются только заголовки сообщений, тело сообщения и информация о вложениях. Содержимое вложения не загружено |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, string) {#fetchmessageasync_4}

Получает сообщение

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, string uniqueId)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | Уникальный идентификатор сообщения |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## FetchMessageAsync(string) {#fetchmessageasync_10}

Получает сообщение

```csharp
public Task<MailMessage> FetchMessageAsync(string uniqueId)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | Уникальный идентификатор сообщения |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, int, CancellationToken) {#fetchmessageasync_3}

Получает сообщение

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, int sequenceNumber, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceNumber | Int32 | Порядковый номер сообщения |
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

## FetchMessageAsync(IConnection, int, bool, CancellationToken) {#fetchmessageasync_2}

Получает сообщение

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, int sequenceNumber, 
    bool ignoreAttachment, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| ignoreAttachment | Boolean | Значение, определяющее, следует ли загружать вложения. Если установлено значение`истинный` , то извлекаются только заголовки сообщений, тело сообщения и информация о вложениях. Содержимое вложения не загружено |
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

## FetchMessageAsync(int, CancellationToken) {#fetchmessageasync_9}

Получает сообщение

```csharp
public Task<MailMessage> FetchMessageAsync(int sequenceNumber, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## FetchMessageAsync(int, bool, CancellationToken) {#fetchmessageasync_8}

Получает сообщение

```csharp
public Task<MailMessage> FetchMessageAsync(int sequenceNumber, bool ignoreAttachment, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| ignoreAttachment | Boolean | Значение, определяющее, следует ли загружать вложения. Если установлено значение`истинный` , то извлекаются только заголовки сообщений, тело сообщения и информация о вложениях. Содержимое вложения не загружено |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## FetchMessageAsync(IConnection, string, CancellationToken) {#fetchmessageasync_5}

Получает сообщение

```csharp
public Task<MailMessage> FetchMessageAsync(IConnection connection, string uniqueId, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | Уникальный идентификатор сообщения |
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

## FetchMessageAsync(string, CancellationToken) {#fetchmessageasync_11}

Получает сообщение

```csharp
public Task<MailMessage> FetchMessageAsync(string uniqueId, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | Уникальный идентификатор сообщения |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
