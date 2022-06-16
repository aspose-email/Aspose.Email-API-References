---
title: RemoveMessageFlagsAsync
second_title: Справочник по Aspose.Email для .NET API
description: Снимает флаги сообщения
type: docs
weight: 1000
url: /ru/net/aspose.email.clients.imap/imapclient/removemessageflagsasync/
---
## RemoveMessageFlagsAsync(IConnection, int, ImapMessageFlags) {#removemessageflagsasync}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags)
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

## RemoveMessageFlagsAsync(IConnection, string, ImapMessageFlags) {#removemessageflagsasync_20}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags)
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

## RemoveMessageFlagsAsync(int, ImapMessageFlags) {#removemessageflagsasync_28}

Удаляет флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags)
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

## RemoveMessageFlagsAsync(string, ImapMessageFlags) {#removemessageflagsasync_48}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(string uniqueId, ImapMessageFlags flags)
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

## RemoveMessageFlagsAsync(IConnection, int, ImapMessageFlags, long) {#removemessageflagsasync_1}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, int sequenceNumber, 
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

## RemoveMessageFlagsAsync(IConnection, string, ImapMessageFlags, long) {#removemessageflagsasync_21}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, string uniqueId, 
    ImapMessageFlags flags, long modificationSequence)
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

## RemoveMessageFlagsAsync(int, ImapMessageFlags, long) {#removemessageflagsasync_29}

Удаляет флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(string, ImapMessageFlags, long) {#removemessageflagsasync_49}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
    long modificationSequence)
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

## RemoveMessageFlagsAsync(string, string, ImapMessageFlags) {#removemessageflagsasync_52}

Удаляет флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags)
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

## RemoveMessageFlagsAsync(int, int, ImapMessageFlags) {#removemessageflagsasync_32}

Удаляет флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags)
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

## RemoveMessageFlagsAsync(IConnection, string, string, ImapMessageFlags) {#removemessageflagsasync_24}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
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

## RemoveMessageFlagsAsync(IConnection, int, int, ImapMessageFlags) {#removemessageflagsasync_4}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
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

## RemoveMessageFlagsAsync(string, string, ImapMessageFlags, long) {#removemessageflagsasync_53}

Удаляет флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(int, int, ImapMessageFlags, long) {#removemessageflagsasync_33}

Удаляет флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, long) {#removemessageflagsasync_25}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
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

## RemoveMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, long) {#removemessageflagsasync_5}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
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

## RemoveMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags) {#removemessageflagsasync_44}

Удаляет флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags)
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

## RemoveMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags) {#removemessageflagsasync_40}

Удаляет флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags)
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

## RemoveMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) {#removemessageflagsasync_16}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
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

## RemoveMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) {#removemessageflagsasync_12}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
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

## RemoveMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, long) {#removemessageflagsasync_45}

Удаляет флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, long) {#removemessageflagsasync_41}

Удаляет флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) {#removemessageflagsasync_17}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| uidSet | IEnumerable`1 | Набор набора UID для сообщений |
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

## RemoveMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) {#removemessageflagsasync_13}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
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

## RemoveMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) {#removemessageflagsasync_36}

Удаляет флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
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

## RemoveMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) {#removemessageflagsasync_8}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, 
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

## RemoveMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) {#removemessageflagsasync_37}

Удаляет флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
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

## RemoveMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) {#removemessageflagsasync_9}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, 
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

## RemoveMessageFlagsAsync(IConnection, int, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_3}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, int sequenceNumber, 
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

## RemoveMessageFlagsAsync(IConnection, string, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_23}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, string uniqueId, 
    ImapMessageFlags flags, CancellationToken token)
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

## RemoveMessageFlagsAsync(int, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_31}

Удаляет флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(string, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_51}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
    CancellationToken token)
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

## RemoveMessageFlagsAsync(IConnection, int, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_2}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, int sequenceNumber, 
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

## RemoveMessageFlagsAsync(IConnection, string, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_22}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, string uniqueId, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
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

## RemoveMessageFlagsAsync(int, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_30}

Удаляет флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(string, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_50}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(string, string, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_55}

Удаляет флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
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

---

## RemoveMessageFlagsAsync(int, int, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_35}

Удаляет флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_27}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
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

## RemoveMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_7}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
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

## RemoveMessageFlagsAsync(string, string, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_54}

Удаляет флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(int, int, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_34}

Удаляет флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_26}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
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

## RemoveMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_6}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
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

## RemoveMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_47}

Удаляет флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_43}

Удаляет флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_19}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
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

## RemoveMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_15}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
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

## RemoveMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_46}

Удаляет флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_42}

Удаляет флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
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

## RemoveMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_18}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| uidSet | IEnumerable`1 | Набор набора UID для сообщений |
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

## RemoveMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_14}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
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

## RemoveMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_39}

Удаляет флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
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

## RemoveMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) {#removemessageflagsasync_11}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, 
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

## RemoveMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_38}

Удаляет флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
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

## RemoveMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) {#removemessageflagsasync_10}

Снимает флаги сообщения

```csharp
public Task RemoveMessageFlagsAsync(IConnection connection, 
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

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
