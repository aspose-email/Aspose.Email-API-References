---
title: DeleteMessagesAsync
second_title: Справочник по Aspose.Email для .NET API
description: Помечает сообщение с указанным уникальным идентификатором как удаленное
type: docs
weight: 590
url: /ru/net/aspose.email.clients.imap/imapclient/deletemessagesasync/
---
## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long) {#deletemessagesasync_19}

Помечает сообщение с указанным уникальным идентификатором как удаленное

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, long) {#deletemessagesasync_45}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long) {#deletemessagesasync_51}

Помечает сообщение с указанным уникальным идентификатором как удаленное

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, bool) {#deletemessagesasync_49}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, bool commitNow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, bool) {#deletemessagesasync_17}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, bool commitNow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, bool) {#deletemessagesasync_52}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    bool commitNow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, bool) {#deletemessagesasync_20}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, bool commitNow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
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

## DeleteMessagesAsync(IConnection, int, int) {#deletemessagesasync}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string) {#deletemessagesasync_24}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid)
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

## DeleteMessagesAsync(int, int) {#deletemessagesasync_32}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string) {#deletemessagesasync_56}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid)
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

## DeleteMessagesAsync(IConnection, int, int, long) {#deletemessagesasync_1}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, long) {#deletemessagesasync_27}

Помечает сообщение с указанным уникальным идентификатором как удаленное

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(int, int, long) {#deletemessagesasync_33}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long) {#deletemessagesasync_59}

Помечает сообщение с указанным уникальным идентификатором как удаленное

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, bool) {#deletemessagesasync_57}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, bool commitNow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, bool) {#deletemessagesasync_25}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    bool commitNow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long, bool) {#deletemessagesasync_60}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    bool commitNow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, long, bool) {#deletemessagesasync_28}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, bool commitNow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
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

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessagesasync_4}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo для удаления |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessagesasync_36}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo для удаления |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessagesasync_7}

Помечает сообщение с указанным уникальным идентификатором как удаленное

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo для удаления |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessagesasync_39}

Помечает сообщение с указанным уникальным идентификатором как удаленное

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo для удаления |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessagesasync_37}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo для удаления |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessagesasync_5}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo для удаления |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessagesasync_40}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, bool commitNow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo для удаления |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessagesasync_8}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, bool commitNow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo для удаления |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, CancellationToken) {#deletemessagesasync_15}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, CancellationToken) {#deletemessagesasync_23}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, CancellationToken) {#deletemessagesasync_47}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#deletemessagesasync_55}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, long, CancellationToken) {#deletemessagesasync_14}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
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

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, CancellationToken) {#deletemessagesasync_22}

Помечает сообщение с указанным уникальным идентификатором как удаленное

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
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

## DeleteMessagesAsync(IEnumerable&lt;int&gt;, long, CancellationToken) {#deletemessagesasync_46}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet, long modificationSequence, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, CancellationToken) {#deletemessagesasync_54}

Помечает сообщение с указанным уникальным идентификатором как удаленное

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, bool, CancellationToken) {#deletemessagesasync_50}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, bool commitNow, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, bool, CancellationToken) {#deletemessagesasync_18}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, bool commitNow, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
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

## DeleteMessagesAsync(IEnumerable&lt;string&gt;, long, bool, CancellationToken) {#deletemessagesasync_53}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
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

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;, long, bool, CancellationToken) {#deletemessagesasync_21}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
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

---

## DeleteMessagesAsync(IConnection, int, int, CancellationToken) {#deletemessagesasync_3}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, CancellationToken) {#deletemessagesasync_31}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
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

---

## DeleteMessagesAsync(int, int, CancellationToken) {#deletemessagesasync_35}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, CancellationToken) {#deletemessagesasync_63}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, CancellationToken token)
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

## DeleteMessagesAsync(IConnection, int, int, long, CancellationToken) {#deletemessagesasync_2}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
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

## DeleteMessagesAsync(IConnection, string, string, long, CancellationToken) {#deletemessagesasync_30}

Помечает сообщение с указанным уникальным идентификатором как удаленное

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
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

## DeleteMessagesAsync(int, int, long, CancellationToken) {#deletemessagesasync_34}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(int startSequence, int endSequence, long modificationSequence, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, long, CancellationToken) {#deletemessagesasync_62}

Помечает сообщение с указанным уникальным идентификатором как удаленное

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(string, string, bool, CancellationToken) {#deletemessagesasync_58}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, bool commitNow, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, string, string, bool, CancellationToken) {#deletemessagesasync_26}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    bool commitNow, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
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

## DeleteMessagesAsync(string, string, long, bool, CancellationToken) {#deletemessagesasync_61}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(string startUid, string endUid, long modificationSequence, 
    bool commitNow, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
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

## DeleteMessagesAsync(IConnection, string, string, long, bool, CancellationToken) {#deletemessagesasync_29}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, string startUid, string endUid, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
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

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) {#deletemessagesasync_11}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo для удаления |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, CancellationToken) {#deletemessagesasync_43}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo для удаления |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) {#deletemessagesasync_10}

Помечает сообщение с указанным уникальным идентификатором как удаленное

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo для удаления |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, CancellationToken) {#deletemessagesasync_42}

Помечает сообщение с указанным уникальным идентификатором как удаленное

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo для удаления |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) {#deletemessagesasync_38}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo для удаления |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool, CancellationToken) {#deletemessagesasync_6}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo для удаления |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) {#deletemessagesasync_41}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, bool commitNow, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo для удаления |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool, CancellationToken) {#deletemessagesasync_9}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если пользователь укажет это. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public Task DeleteMessagesAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, bool commitNow, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo для удаления |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;) {#deletemessagesasync_12}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;string&gt;) {#deletemessagesasync_16}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<string> uidSet)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uidSet | IEnumerable`1 | Набор UID для сообщений |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;int&gt;) {#deletemessagesasync_44}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(IEnumerable<int> sequenceSet)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IEnumerable&lt;string&gt;) {#deletemessagesasync_48}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(IEnumerable<string> uidSet)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор UID для сообщений |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessagesAsync(IConnection, IEnumerable&lt;int&gt;, long) {#deletemessagesasync_13}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public Task DeleteMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
