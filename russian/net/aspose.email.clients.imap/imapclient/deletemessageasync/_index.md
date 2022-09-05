---
title: DeleteMessageAsync
second_title: Справочник по Aspose.Email для .NET API
description: Помечает сообщение с указанным порядковым номером как удаленное
type: docs
weight: 570
url: /ru/net/aspose.email.clients.imap/imapclient/deletemessageasync/
---
## DeleteMessageAsync(IConnection, int) {#deletemessageasync}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceNumber | Int32 | Порядковый номер сообщения |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string) {#deletemessageasync_4}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | UID сообщения |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(int) {#deletemessageasync_12}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessageAsync(int sequenceNumber)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщения |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(string) {#deletemessageasync_16}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessageAsync(string uniqueId)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | UID сообщения |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, int, long) {#deletemessageasync_1}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long) {#deletemessageasync_7}

Помечает сообщение с указанным уникальным идентификатором как удаленное

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | UID сообщения |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(int, long) {#deletemessageasync_13}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessageAsync(int sequenceNumber, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long) {#deletemessageasync_19}

Помечает сообщение с указанным уникальным идентификатором как удаленное

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | UID сообщения |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, bool) {#deletemessageasync_17}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, bool commitNow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | UID сообщения |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, bool) {#deletemessageasync_5}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, bool commitNow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | UID сообщения |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long, bool) {#deletemessageasync_20}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence, bool commitNow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | UID сообщения |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long, bool) {#deletemessageasync_8}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence, 
    bool commitNow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | UID сообщения |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, int, CancellationToken) {#deletemessageasync_3}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, CancellationToken) {#deletemessageasync_11}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | UID сообщения |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(int, CancellationToken) {#deletemessageasync_15}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessageAsync(int sequenceNumber, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, CancellationToken) {#deletemessageasync_23}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessageAsync(string uniqueId, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | UID сообщения |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, int, long, CancellationToken) {#deletemessageasync_2}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, 
    long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long, CancellationToken) {#deletemessageasync_10}

Помечает сообщение с указанным уникальным идентификатором как удаленное

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | UID сообщения |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(int, long, CancellationToken) {#deletemessageasync_14}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessageAsync(int sequenceNumber, long modificationSequence, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long, CancellationToken) {#deletemessageasync_22}

Помечает сообщение с указанным уникальным идентификатором как удаленное

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | UID сообщения |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, bool, CancellationToken) {#deletemessageasync_18}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, bool commitNow, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | UID сообщения |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, bool, CancellationToken) {#deletemessageasync_6}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, bool commitNow, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | UID сообщения |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, long, bool, CancellationToken) {#deletemessageasync_21}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(string uniqueId, long modificationSequence, bool commitNow, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | UID сообщения |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, long, bool, CancellationToken) {#deletemessageasync_9}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | UID сообщения |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
