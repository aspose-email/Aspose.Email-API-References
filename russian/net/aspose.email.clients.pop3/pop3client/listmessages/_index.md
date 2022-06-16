---
title: ListMessages
second_title: Справочник по Aspose.Email для .NET API
description: Список сообщений. Получает информацию для поискового сообщения
type: docs
weight: 290
url: /ru/net/aspose.email.clients.pop3/pop3client/listmessages/
---
## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_13}

Список сообщений. Получает информацию для поискового сообщения

```csharp
public Pop3MessageInfoCollection ListMessages(IEnumerable<string> uniqueIdLst)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueIdLst | IEnumerable`1 | Список уникальных идентификаторов для[`Pop3MessageInfo`](../../pop3messageinfo)для получения с сервера. |

### Возвращаемое значение

Pop3MessageInfoCollection

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не отображаются в списке

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;int&gt;) {#listmessages_12}

Список сообщений. Получает информацию для поискового сообщения

```csharp
public Pop3MessageInfoCollection ListMessages(IEnumerable<int> sequenceNumberLst)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumberLst | IEnumerable`1 | список sequenceNumber для[`Pop3MessageInfo`](../../pop3messageinfo)для получения с сервера. |

### Возвращаемое значение

Pop3MessageInfoCollection

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не отображаются в списке

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessages(IConnection, IEnumerable&lt;string&gt;) {#listmessages_7}

Список сообщений. Получает информацию для поискового сообщения

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, 
    IEnumerable<string> uniqueIdLst)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| uniqueIdLst | IEnumerable`1 | Список уникальных идентификаторов для[`Pop3MessageInfo`](../../pop3messageinfo)для получения с сервера. |

### Возвращаемое значение

Pop3MessageInfoCollection

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не отображаются в списке

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessages(IConnection, IEnumerable&lt;int&gt;) {#listmessages_6}

Список сообщений. Получает информацию для поискового сообщения

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, 
    IEnumerable<int> sequenceNumberLst)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| sequenceNumberLst | IEnumerable`1 | список sequenceNumber для[`Pop3MessageInfo`](../../pop3messageinfo)для получения с сервера. |

### Возвращаемое значение

Pop3MessageInfoCollection

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не отображаются в списке

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessages(IConnection) {#listmessages_1}

Список сообщений. Получает информацию для поискового сообщения

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |

### Возвращаемое значение

Pop3MessageInfoCollection

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не отображаются в списке

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessages(IConnection, bool) {#listmessages_5}

Список сообщений. Получает информацию для поискового сообщения

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, bool closeTransaction)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| closeTransaction | Boolean | Указывает, должна ли текущая транзакция быть закрыта до получения списка. |

### Возвращаемое значение

Pop3MessageInfoCollection

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не отображаются в списке

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessages(IConnection, MailQuery) {#listmessages_4}

Список сообщений.

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, MailQuery query)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery)объект. |

### Возвращаемое значение

Коллекция объектов Pop3MessageInfo.

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessages(IConnection, Pop3ListFields) {#listmessages_2}

Список сообщений.

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, Pop3ListFields fields)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| fields | Pop3ListFields | Поля, которые мы хотим получить |

### Возвращаемое значение

Pop3MessageInfoCollection

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не перечислены

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessages(IConnection, Pop3ListFields, bool, MailQuery) {#listmessages_3}

Список сообщений.

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, Pop3ListFields fields, 
    bool closeTransaction, MailQuery query)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| fields | Pop3ListFields | Поля, которые мы хотим получить |
| closeTransaction | Boolean | Указывает, должна ли текущая транзакция быть закрыта до получения списка. |
| query | MailQuery | Объект[`MailQuery`](../../../aspose.email.tools.search/mailquery). |

### Возвращаемое значение

Pop3MessageInfoCollection

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

Список сообщений. Получает информацию для поискового сообщения

```csharp
public Pop3MessageInfoCollection ListMessages()
```

### Возвращаемое значение

Pop3MessageInfoCollection

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не отображаются в списке

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessages(bool) {#listmessages_11}

Список сообщений. Получает информацию для поискового сообщения

```csharp
public Pop3MessageInfoCollection ListMessages(bool closeTransaction)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| closeTransaction | Boolean | Указывает, должна ли текущая транзакция быть закрыта до получения списка. |

### Возвращаемое значение

Pop3MessageInfoCollection

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не отображаются в списке

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessages(MailQuery) {#listmessages_10}

Список сообщений.

```csharp
public Pop3MessageInfoCollection ListMessages(MailQuery query)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| query | MailQuery | Объект[`MailQuery`](../../../aspose.email.tools.search/mailquery). |

### Возвращаемое значение

Коллекция объектов Pop3MessageInfo.

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessages(Pop3ListFields) {#listmessages_8}

Список сообщений.

```csharp
public Pop3MessageInfoCollection ListMessages(Pop3ListFields fields)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fields | Pop3ListFields | Поля, которые мы хотим получить |

### Возвращаемое значение

Pop3MessageInfoCollection

### Примечания

Обратите внимание, что сообщения помечены как удаленные не перечислены

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessages(Pop3ListFields, bool, MailQuery) {#listmessages_9}

Список сообщений.

```csharp
public Pop3MessageInfoCollection ListMessages(Pop3ListFields fields, bool closeTransaction, 
    MailQuery query)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fields | Pop3ListFields | Поля, которые мы хотим получить |
| closeTransaction | Boolean | Указывает если текущая транзакция должна быть закрыта до получения списка. |
| query | MailQuery | Объект[`MailQuery`](../../../aspose.email.tools.search/mailquery). |

### Возвращаемое значение

Pop3MessageInfoCollection

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
