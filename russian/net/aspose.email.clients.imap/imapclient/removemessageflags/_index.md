---
title: RemoveMessageFlags
second_title: Справочник по Aspose.Email для .NET API
description: Снимает флаги сообщения
type: docs
weight: 990
url: /ru/net/aspose.email.clients.imap/imapclient/removemessageflags/
---
## RemoveMessageFlags(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) {#removemessageflags_7}

Снимает флаги сообщения

```csharp
public void RemoveMessageFlags(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| flags | ImapMessageFlags | Флаги для удаления |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) {#removemessageflags_18}

Удаляет флаги сообщения

```csharp
public void RemoveMessageFlags(IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| flags | ImapMessageFlags | Флаги для изменения |

### Смотрите также

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) {#removemessageflags_4}

Снимает флаги сообщения

```csharp
public void RemoveMessageFlags(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| flags | ImapMessageFlags | Флаги для изменения |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) {#removemessageflags_19}

Удаляет флаги сообщения

```csharp
public void RemoveMessageFlags(IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| flags | ImapMessageFlags | Флаги, подлежащие изменению |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Смотрите также

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) {#removemessageflags_5}

Снимает флаги сообщения

```csharp
public void RemoveMessageFlags(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| flags | ImapMessageFlags | Флаги для изменения |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(IConnection, int, ImapMessageFlags) {#removemessageflags}

Снимает флаги сообщения

```csharp
public void RemoveMessageFlags(IConnection connection, int sequenceNumber, ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| flags | ImapMessageFlags | Добавляемые флаги |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(IConnection, string, ImapMessageFlags) {#removemessageflags_10}

Снимает флаги сообщения

```csharp
public void RemoveMessageFlags(IConnection connection, string uniqueId, ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| uniqueId | String | Уникальный идентификатор сообщения |
| flags | ImapMessageFlags | Добавляемые флаги |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(int, ImapMessageFlags) {#removemessageflags_14}

Удаляет флаги сообщения

```csharp
public void RemoveMessageFlags(int sequenceNumber, ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщение |
| flags | ImapMessageFlags | Добавляемые флаги |

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(string, ImapMessageFlags) {#removemessageflags_24}

Снимает флаги сообщения

```csharp
public void RemoveMessageFlags(string uniqueId, ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | Уникальный идентификатор message |
| flags | ImapMessageFlags | Добавляемые флаги |

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(IConnection, int, ImapMessageFlags, long) {#removemessageflags_1}

Снимает флаги сообщения

```csharp
public void RemoveMessageFlags(IConnection connection, int sequenceNumber, ImapMessageFlags flags, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| flags | ImapMessageFlags | Добавляемые флаги |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(IConnection, string, ImapMessageFlags, long) {#removemessageflags_11}

Снимает флаги сообщения

```csharp
public void RemoveMessageFlags(IConnection connection, string uniqueId, ImapMessageFlags flags, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| uniqueId | String | Уникальный идентификатор сообщения |
| flags | ImapMessageFlags | Добавляемые флаги |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(int, ImapMessageFlags, long) {#removemessageflags_15}

Удаляет флаги сообщения

```csharp
public void RemoveMessageFlags(int sequenceNumber, ImapMessageFlags flags, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщение |
| flags | ImapMessageFlags | Добавляемые флаги |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(string, ImapMessageFlags, long) {#removemessageflags_25}

Снимает флаги сообщения

```csharp
public void RemoveMessageFlags(string uniqueId, ImapMessageFlags flags, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | Уникальный идентификатор message |
| flags | ImapMessageFlags | Добавляемые флаги |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(string, string, ImapMessageFlags) {#removemessageflags_26}

Удаляет флаги сообщения

```csharp
public void RemoveMessageFlags(string startUid, string endUid, ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startUid | String | Начальный UID сообщения список сообщений |
| endUid | String | Конечный UID списка сообщений |
| flags | ImapMessageFlags | Флаги для изменено |

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(int, int, ImapMessageFlags) {#removemessageflags_16}

Удаляет флаги сообщения

```csharp
public void RemoveMessageFlags(int startSequence, int endSequence, ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| flags | ImapMessageFlags | Флаги удалить |

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(IConnection, string, string, ImapMessageFlags) {#removemessageflags_12}

Снимает флаги сообщения

```csharp
public void RemoveMessageFlags(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| flags | ImapMessageFlags | Флаги для изменения |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(IConnection, int, int, ImapMessageFlags) {#removemessageflags_2}

Снимает флаги сообщения

```csharp
public void RemoveMessageFlags(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер список сообщений |
| flags | ImapMessageFlags | Флаги для удаления |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(string, string, ImapMessageFlags, long) {#removemessageflags_27}

Удаляет флаги сообщения

```csharp
public void RemoveMessageFlags(string startUid, string endUid, ImapMessageFlags flags, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startUid | String | Начальный UID сообщения список сообщений |
| endUid | String | Конечный UID списка сообщений |
| flags | ImapMessageFlags | Флаги для изменено |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(int, int, ImapMessageFlags, long) {#removemessageflags_17}

Удаляет флаги сообщения

```csharp
public void RemoveMessageFlags(int startSequence, int endSequence, ImapMessageFlags flags, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| flags | ImapMessageFlags | Флаги для удаления |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(IConnection, string, string, ImapMessageFlags, long) {#removemessageflags_13}

Снимает флаги сообщения

```csharp
public void RemoveMessageFlags(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| flags | ImapMessageFlags | Флаги, подлежащие изменению |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(IConnection, int, int, ImapMessageFlags, long) {#removemessageflags_3}

Снимает флаги сообщения

```csharp
public void RemoveMessageFlags(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер список сообщений |
| flags | ImapMessageFlags | Флаги для удаления |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(IEnumerable&lt;string&gt;, ImapMessageFlags) {#removemessageflags_22}

Удаляет флаги сообщения

```csharp
public void RemoveMessageFlags(IEnumerable<string> uidSet, ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| flags | ImapMessageFlags | Флаги для изменения |

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(IEnumerable&lt;int&gt;, ImapMessageFlags) {#removemessageflags_20}

Удаляет флаги сообщения

```csharp
public void RemoveMessageFlags(IEnumerable<int> sequenceSet, ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Набор последовательности номера для сообщений |
| flags | ImapMessageFlags | Флаги для удаления |

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) {#removemessageflags_8}

Снимает флаги сообщения

```csharp
public void RemoveMessageFlags(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| flags | ImapMessageFlags | Флаги для изменения |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) {#removemessageflags_6}

Снимает флаги сообщения

```csharp
public void RemoveMessageFlags(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| flags | ImapMessageFlags | Флаги для удаления |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(IEnumerable&lt;string&gt;, ImapMessageFlags, long) {#removemessageflags_23}

Удаляет флаги сообщения

```csharp
public void RemoveMessageFlags(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| flags | ImapMessageFlags | Флаги, подлежащие изменению |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(IEnumerable&lt;int&gt;, ImapMessageFlags, long) {#removemessageflags_21}

Удаляет флаги сообщения

```csharp
public void RemoveMessageFlags(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Набор последовательности номера для сообщений |
| flags | ImapMessageFlags | Флаги для удаления |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## RemoveMessageFlags(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) {#removemessageflags_9}

Снимает флаги сообщения

```csharp
public void RemoveMessageFlags(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| uidSet | IEnumerable`1 | Набор набора UID для сообщений |
| flags | ImapMessageFlags | Флаги для изменения |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
