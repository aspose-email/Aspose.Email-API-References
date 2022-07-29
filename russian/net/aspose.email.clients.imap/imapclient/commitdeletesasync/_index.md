---
title: CommitDeletesAsync
second_title: Справочник по Aspose.Email для .NET API
description: Подтвердить удаление
type: docs
weight: 470
url: /ru/net/aspose.email.clients.imap/imapclient/commitdeletesasync/
---
## CommitDeletesAsync(IConnection) {#commitdeletesasync_1}

Подтвердить удаление

```csharp
public Task CommitDeletesAsync(IConnection connection)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, int) {#commitdeletesasync_2}

Подтвердить удаление

```csharp
public Task CommitDeletesAsync(IConnection connection, int sleep)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sleep | Int32 | Время ожидания завершения операции в миллисекундах |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## CommitDeletesAsync() {#commitdeletesasync}

Подтвердить удаление

```csharp
public Task CommitDeletesAsync()
```

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## CommitDeletesAsync(int) {#commitdeletesasync_11}

Подтвердить удаление

```csharp
public Task CommitDeletesAsync(int sleep)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sleep | Int32 | Время ожидания завершения операции в миллисекундах |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## CommitDeletesAsync(IEnumerable&lt;string&gt;) {#commitdeletesasync_13}

Зафиксировать удаление Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IEnumerable<string> uidSet)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор уникальных идентификаторов для сообщений |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## CommitDeletesAsync(string) {#commitdeletesasync_15}

Зафиксировать удаление Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string uniqueId)
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

## CommitDeletesAsync(string, string) {#commitdeletesasync_16}

Зафиксировать удаление Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string startUid, string endUid)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, IEnumerable&lt;string&gt;) {#commitdeletesasync_4}

Зафиксировать удаление Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, IEnumerable<string> uidSet)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uidSet | IEnumerable`1 | Набор уникальных идентификаторов для сообщений |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, string) {#commitdeletesasync_6}

Подтвердить удаление

```csharp
public Task CommitDeletesAsync(IConnection connection, string uniqueId)
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

## CommitDeletesAsync(IConnection, string, string) {#commitdeletesasync_7}

Зафиксировать удаление Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, string startUid, string endUid)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, CancellationToken) {#commitdeletesasync_10}

Подтвердить удаление

```csharp
public Task CommitDeletesAsync(IConnection connection, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, int, CancellationToken) {#commitdeletesasync_3}

Подтвердить удаление

```csharp
public Task CommitDeletesAsync(IConnection connection, int sleep, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sleep | Int32 | Время ожидания завершения операции в миллисекундах |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## CommitDeletesAsync(CancellationToken) {#commitdeletesasync_19}

Подтвердить удаление

```csharp
public Task CommitDeletesAsync(CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## CommitDeletesAsync(int, CancellationToken) {#commitdeletesasync_12}

Подтвердить удаление

```csharp
public Task CommitDeletesAsync(int sleep, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sleep | Int32 | Время ожидания завершения операции в миллисекундах |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## CommitDeletesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#commitdeletesasync_14}

Зафиксировать удаление Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IEnumerable<string> uidSet, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор уникальных идентификаторов для сообщений |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## CommitDeletesAsync(string, CancellationToken) {#commitdeletesasync_18}

Зафиксировать удаление Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string uniqueId, CancellationToken token)
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

## CommitDeletesAsync(string, string, CancellationToken) {#commitdeletesasync_17}

Зафиксировать удаление Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string startUid, string endUid, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, IEnumerable&lt;string&gt;, CancellationToken) {#commitdeletesasync_5}

Зафиксировать удаление Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, IEnumerable<string> uidSet, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uidSet | IEnumerable`1 | Набор уникальных идентификаторов для сообщений |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, string, CancellationToken) {#commitdeletesasync_9}

Подтвердить удаление

```csharp
public Task CommitDeletesAsync(IConnection connection, string uniqueId, CancellationToken token)
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

## CommitDeletesAsync(IConnection, string, string, CancellationToken) {#commitdeletesasync_8}

Зафиксировать удаление Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, string startUid, string endUid, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
