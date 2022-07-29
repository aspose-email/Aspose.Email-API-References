---
title: MoveMessageAsync
second_title: Справочник по Aspose.Email для .NET API
description: Перемещает сообщение
type: docs
weight: 940
url: /ru/net/aspose.email.clients.imap/imapclient/movemessageasync/
---
## MoveMessageAsync(int, string, bool) {#movemessageasync_9}

Перемещает сообщение

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName, bool commitDeletions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string, bool) {#movemessageasync_13}

Перемещает сообщение

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName, bool commitDeletions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | UID сообщения |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string) {#movemessageasync}

Перемещает сообщениеeg

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| folderName | String | Имя папки, куда нужно переместить сообщение |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, string, string) {#movemessageasync_4}

Перемещает сообщение

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | UID сообщения |
| folderName | String | Имя папки, куда нужно переместить сообщение |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessageAsync(int, string) {#movemessageasync_8}

Перемещает сообщение

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| folderName | String | Имя папки, куда нужно переместить сообщение |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string) {#movemessageasync_12}

Перемещает сообщение

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | UID сообщения |
| folderName | String | Имя папки, куда нужно переместить сообщение |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string, bool, CancellationToken) {#movemessageasync_2}

Перемещает сообщениеeg

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, string, string, bool, CancellationToken) {#movemessageasync_6}

Перемещает сообщение

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | UID сообщения |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessageAsync(int, string, bool, CancellationToken) {#movemessageasync_10}

Перемещает сообщение

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName, bool commitDeletions, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string, bool, CancellationToken) {#movemessageasync_14}

Перемещает сообщение

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName, bool commitDeletions, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | UID сообщения |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string, CancellationToken) {#movemessageasync_3}

Перемещает сообщениеeg

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, string, string, CancellationToken) {#movemessageasync_7}

Перемещает сообщение

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | UID сообщения |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessageAsync(int, string, CancellationToken) {#movemessageasync_11}

Перемещает сообщение

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string, CancellationToken) {#movemessageasync_15}

Перемещает сообщение

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | UID сообщения |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string, bool) {#movemessageasync_1}

Перемещает сообщениеeg

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName, 
    bool commitDeletions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, string, string, bool) {#movemessageasync_5}

Перемещает сообщение

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName, 
    bool commitDeletions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | UID сообщения |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
