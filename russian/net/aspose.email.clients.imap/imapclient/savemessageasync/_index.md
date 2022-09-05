---
title: SaveMessageAsync
second_title: Справочник по Aspose.Email для .NET API
description: Загружает сообщение с указанным порядковым номером и записывает его данные в предоставленный поток
type: docs
weight: 1100
url: /ru/net/aspose.email.clients.imap/imapclient/savemessageasync/
---
## SaveMessageAsync(IConnection, int, Stream) {#savemessageasync}

Загружает сообщение с указанным порядковым номером и записывает его данные в предоставленный поток

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, Stream resultStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| resultStream | Stream | Поток, который будет получать сообщение |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, Stream) {#savemessageasync_4}

Загружает сообщение с указанным порядковым номером и записывает его данные в предоставленный поток

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, Stream resultStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | Уникальный идентификатор сообщения |
| resultStream | Stream | Поток, который будет получать сообщение |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, string) {#savemessageasync_6}

Загружает сообщение с указанным порядковым номером и записывает его данные в локальный файл

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | Уникальный идентификатор сообщения |
| fileName | String | Путь к локальному файлу. Это не может быть каталог |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, string) {#savemessageasync_2}

Загружает сообщение с указанным порядковым номером и записывает его данные в локальный файл

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| fileName | String | Путь к локальному файлу. Это не может быть каталог |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## SaveMessageAsync(int, Stream) {#savemessageasync_8}

Загружает сообщение с указанным порядковым номером и записывает его данные в предоставленный поток

```csharp
public Task SaveMessageAsync(int sequenceNumber, Stream resultStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| resultStream | Stream | Поток, который будет получать сообщение |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## SaveMessageAsync(string, Stream) {#savemessageasync_12}

Загружает сообщение с указанным порядковым номером и записывает его данные в предоставленный поток

```csharp
public Task SaveMessageAsync(string uniqueId, Stream resultStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | Уникальный идентификатор сообщения |
| resultStream | Stream | Поток, который будет получать сообщение |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## SaveMessageAsync(string, string) {#savemessageasync_14}

Загружает сообщение с указанным порядковым номером и записывает его данные в локальный файл

```csharp
public Task SaveMessageAsync(string uniqueId, string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | Уникальный идентификатор сообщения |
| fileName | String | Путь к локальному файлу. Это не может быть каталог |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## SaveMessageAsync(int, string) {#savemessageasync_10}

Загружает сообщение с указанным порядковым номером и записывает его данные в локальный файл

```csharp
public Task SaveMessageAsync(int sequenceNumber, string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| fileName | String | Путь к локальному файлу. Это не может быть каталог |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, Stream, CancellationToken) {#savemessageasync_1}

Загружает сообщение с указанным порядковым номером и записывает его данные в предоставленный поток

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, Stream resultStream, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| resultStream | Stream | Поток, который будет получать сообщение |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, Stream, CancellationToken) {#savemessageasync_5}

Загружает сообщение с указанным порядковым номером и записывает его данные в предоставленный поток

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, Stream resultStream, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | Уникальный идентификатор сообщения |
| resultStream | Stream | Поток, который будет получать сообщение |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, string, CancellationToken) {#savemessageasync_7}

Загружает сообщение с указанным порядковым номером и записывает его данные в локальный файл

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, string fileName, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | Уникальный идентификатор сообщения |
| fileName | String | Путь к локальному файлу. Это не может быть каталог |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, string, CancellationToken) {#savemessageasync_3}

Загружает сообщение с указанным порядковым номером и записывает его данные в локальный файл

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, string fileName, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| fileName | String | Путь к локальному файлу. Это не может быть каталог |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## SaveMessageAsync(int, Stream, CancellationToken) {#savemessageasync_9}

Загружает сообщение с указанным порядковым номером и записывает его данные в предоставленный поток

```csharp
public Task SaveMessageAsync(int sequenceNumber, Stream resultStream, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| resultStream | Stream | Поток, который будет получать сообщение |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## SaveMessageAsync(string, Stream, CancellationToken) {#savemessageasync_13}

Загружает сообщение с указанным порядковым номером и записывает его данные в предоставленный поток

```csharp
public Task SaveMessageAsync(string uniqueId, Stream resultStream, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | Уникальный идентификатор сообщения |
| resultStream | Stream | Поток, который будет получать сообщение |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## SaveMessageAsync(string, string, CancellationToken) {#savemessageasync_15}

Загружает сообщение с указанным порядковым номером и записывает его данные в локальный файл

```csharp
public Task SaveMessageAsync(string uniqueId, string fileName, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | Уникальный идентификатор сообщения |
| fileName | String | Путь к локальному файлу. Это не может быть каталог |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## SaveMessageAsync(int, string, CancellationToken) {#savemessageasync_11}

Загружает сообщение с указанным порядковым номером и записывает его данные в локальный файл

```csharp
public Task SaveMessageAsync(int sequenceNumber, string fileName, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| fileName | String | Путь к локальному файлу. Это не может быть каталог |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
