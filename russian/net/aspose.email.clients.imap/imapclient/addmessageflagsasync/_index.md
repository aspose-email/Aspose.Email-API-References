---
title: AddMessageFlagsAsync
second_title: Справочник по Aspose.Email для .NET API
description: Добавляет флаги сообщения
type: docs
weight: 350
url: /ru/net/aspose.email.clients.imap/imapclient/addmessageflagsasync/
---
## AddMessageFlagsAsync(int, int, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_35}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| flags | ImapMessageFlags | Флаги для удаления |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_27}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| flags | ImapMessageFlags | Флаги для изменения |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_7}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер список сообщений |
| flags | ImapMessageFlags | Флаги для удаления |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены . |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, string, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_54}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startUid | String | Начальный UID сообщения список сообщений |
| endUid | String | Конечный UID списка сообщений |
| flags | ImapMessageFlags | Флаги для изменено |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, int, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_34}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| flags | ImapMessageFlags | Флаги для удаления |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_26}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| flags | ImapMessageFlags | Флаги, подлежащие изменению |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_6}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер список сообщений |
| flags | ImapMessageFlags | Флаги для удаления |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_47}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| flags | ImapMessageFlags | Флаги для изменения |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены . |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_43}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Набор последовательности номера для сообщений |
| flags | ImapMessageFlags | Флаги для удаления |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменен. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_19}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| flags | ImapMessageFlags | Флаги для изменения |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_15}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| flags | ImapMessageFlags | Флаги для удаления |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_46}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| flags | ImapMessageFlags | Флаги, подлежащие изменению |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_42}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Набор последовательности номера для сообщений |
| flags | ImapMessageFlags | Флаги для удаления |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_18}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| flags | ImapMessageFlags | Флаги для изменения |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_14}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| flags | ImapMessageFlags | Флаги для удаления |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_39}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| flags | ImapMessageFlags | Флаги для изменения |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_11}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| flags | ImapMessageFlags | Флаги для изменения |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_38}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| flags | ImapMessageFlags | Флаги, подлежащие изменению |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_10}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, long modificationSequence, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| flags | ImapMessageFlags | Флаги для изменения |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, ImapMessageFlags) {#addmessageflagsasync}

Добавляет флаги к сообщению

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int sequenceNumber, ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| flags | ImapMessageFlags | Добавляемые флаги |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, ImapMessageFlags) {#addmessageflagsasync_20}

Добавляет флаги к сообщению

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| uniqueId | String | Уникальный идентификатор сообщения |
| flags | ImapMessageFlags | Добавляемые флаги |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, ImapMessageFlags) {#addmessageflagsasync_28}

Добавляет флаги к сообщению

```csharp
public Task AddMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщение |
| flags | ImapMessageFlags | Добавляемые флаги |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, ImapMessageFlags) {#addmessageflagsasync_48}

Добавляет к сообщению флаги

```csharp
public Task AddMessageFlagsAsync(string uniqueId, ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | Уникальный идентификатор message |
| flags | ImapMessageFlags | Добавляемые флаги |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, ImapMessageFlags, long) {#addmessageflagsasync_1}

Добавляет флаги к сообщению

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| flags | ImapMessageFlags | Добавляемые флаги |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи, с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, ImapMessageFlags, long) {#addmessageflagsasync_21}

Добавляет флаги к сообщению

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| uniqueId | String | Уникальный идентификатор сообщения |
| flags | ImapMessageFlags | Добавляемые флаги |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи, с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, ImapMessageFlags, long) {#addmessageflagsasync_29}

Добавляет флаги к сообщению

```csharp
public Task AddMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщение |
| flags | ImapMessageFlags | Добавляемые флаги |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи, с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, ImapMessageFlags, long) {#addmessageflagsasync_49}

Добавляет к сообщению флаги

```csharp
public Task AddMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | Уникальный идентификатор message |
| flags | ImapMessageFlags | Добавляемые флаги |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи, с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, string, ImapMessageFlags) {#addmessageflagsasync_52}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startUid | String | Начальный UID сообщения список сообщений |
| endUid | String | Конечный UID списка сообщений |
| flags | ImapMessageFlags | Флаги для изменен |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, int, ImapMessageFlags) {#addmessageflagsasync_32}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| flags | ImapMessageFlags | Флаги подлежащий удалению |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, string, ImapMessageFlags) {#addmessageflagsasync_24}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| flags | ImapMessageFlags | Флаги для изменения |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, int, ImapMessageFlags) {#addmessageflagsasync_4}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер список сообщений |
| flags | ImapMessageFlags | Флаги для удаления |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, string, ImapMessageFlags, long) {#addmessageflagsasync_53}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startUid | String | Начальный UID сообщения список сообщений |
| endUid | String | Конечный UID списка сообщений |
| flags | ImapMessageFlags | Флаги для изменено |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи, с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, int, ImapMessageFlags, long) {#addmessageflagsasync_33}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| flags | ImapMessageFlags | Флаги для удаления |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи, с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, long) {#addmessageflagsasync_25}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| flags | ImapMessageFlags | Флаги, подлежащие изменению |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи, с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, long) {#addmessageflagsasync_5}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер список сообщений |
| flags | ImapMessageFlags | Флаги для удаления |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи, с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags) {#addmessageflagsasync_44}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| flags | ImapMessageFlags | Флаги для изменения |

### Возвращаемое значение

Объект задачи, с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags) {#addmessageflagsasync_40}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Набор последовательности номера для сообщений |
| flags | ImapMessageFlags | Флаги, которые необходимо удалить |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) {#addmessageflagsasync_16}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| flags | ImapMessageFlags | Флаги для изменения |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) {#addmessageflagsasync_12}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| flags | ImapMessageFlags | Флаги для удаления |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, long) {#addmessageflagsasync_45}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| flags | ImapMessageFlags | Флаги, подлежащие изменению |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи, с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, long) {#addmessageflagsasync_41}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Набор последовательности номера для сообщений |
| flags | ImapMessageFlags | Флаги для удаления |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи, с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) {#addmessageflagsasync_17}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| flags | ImapMessageFlags | Флаги для изменения |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи, с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) {#addmessageflagsasync_13}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| flags | ImapMessageFlags | Флаги для удаления |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи, с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) {#addmessageflagsasync_36}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| flags | ImapMessageFlags | Флаги для изменения |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) {#addmessageflagsasync_8}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| flags | ImapMessageFlags | Флаги для изменения |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) {#addmessageflagsasync_37}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| flags | ImapMessageFlags | Флаги, подлежащие изменению |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи, с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) {#addmessageflagsasync_9}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| flags | ImapMessageFlags | Флаги для изменения |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи, с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_3}

Добавляет флаги к сообщению

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| flags | ImapMessageFlags | Добавляемые флаги |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_23}

Добавляет флаги к сообщению

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| uniqueId | String | Уникальный идентификатор сообщения |
| flags | ImapMessageFlags | Добавляемые флаги |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_31}

Добавляет флаги к сообщению

```csharp
public Task AddMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщение |
| flags | ImapMessageFlags | Добавляемые флаги |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены . |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_51}

Добавляет к сообщению флаги

```csharp
public Task AddMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | Уникальный идентификатор message |
| flags | ImapMessageFlags | Добавляемые флаги |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, int, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_2}

Добавляет флаги к сообщению

```csharp
public Task AddMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| flags | ImapMessageFlags | Добавляемые флаги |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(IConnection, string, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_22}

Добавляет флаги к сообщению

```csharp
public Task AddMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| uniqueId | String | Уникальный идентификатор сообщения |
| flags | ImapMessageFlags | Добавляемые флаги |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(int, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_30}

Добавляет флаги к сообщению

```csharp
public Task AddMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщение |
| flags | ImapMessageFlags | Добавляемые флаги |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, ImapMessageFlags, long, CancellationToken) {#addmessageflagsasync_50}

Добавляет к сообщению флаги

```csharp
public Task AddMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | Уникальный идентификатор message |
| flags | ImapMessageFlags | Добавляемые флаги |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AddMessageFlagsAsync(string, string, ImapMessageFlags, CancellationToken) {#addmessageflagsasync_55}

Добавляет флаги сообщения

```csharp
public Task AddMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startUid | String | Начальный UID сообщения список сообщений |
| endUid | String | Конечный UID списка сообщений |
| flags | ImapMessageFlags | Флаги для изменено |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
