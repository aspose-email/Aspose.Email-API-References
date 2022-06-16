---
title: DeleteMessage
second_title: Справочник по Aspose.Email для .NET API
description: Помечает сообщение с указанным порядковым номером как удаленное
type: docs
weight: 560
url: /ru/net/aspose.email.clients.imap/imapclient/deletemessage/
---
## DeleteMessage(string) {#deletemessage_8}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public void DeleteMessage(string uniqueId)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | Uid сообщения |

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, int, long) {#deletemessage_1}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public void DeleteMessage(IConnection connection, int sequenceNumber, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string, long) {#deletemessage_4}

Помечает сообщение с указанным уникальным идентификатором как удаленное

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| uniqueId | String | UID сообщения |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessage(int, long) {#deletemessage_7}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public void DeleteMessage(int sequenceNumber, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessage(string, long) {#deletemessage_10}

Помечает сообщение с указанным уникальным идентификатором как удаленное

```csharp
public void DeleteMessage(string uniqueId, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | UID сообщения |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, читайте больше https://tools.ietf.org/html/rfc7162 |

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessage(string, bool) {#deletemessage_9}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если это указывает пользователь. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(string uniqueId, bool commitNow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | Uid сообщения |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string, bool) {#deletemessage_3}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если это указывает пользователь. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, читайте подробнее https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, bool commitNow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | UID сообщения |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessage(string, long, bool) {#deletemessage_11}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если это указывает пользователь. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(string uniqueId, long modificationSequence, bool commitNow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | Uid сообщения |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string, long, bool) {#deletemessage_5}

Помечает сообщение с указанным уникальным идентификатором как удаленное и фиксирует удаление, если это указывает пользователь. Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, читайте подробнее https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, long modificationSequence, 
    bool commitNow)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | uid сообщения |
| modificationSequence | Int64 | Последовательность модификации. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Определяет, должно ли сообщение быть зафиксировано сейчас. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315 |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, int) {#deletemessage}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public void DeleteMessage(IConnection connection, int sequenceNumber)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| sequenceNumber | Int32 | Порядковый номер сообщения |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string) {#deletemessage_2}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public void DeleteMessage(IConnection connection, string uniqueId)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | Uid сообщения |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## DeleteMessage(int) {#deletemessage_6}

Помечает сообщение с указанным порядковым номером как удаленное

```csharp
public void DeleteMessage(int sequenceNumber)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщения |

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
