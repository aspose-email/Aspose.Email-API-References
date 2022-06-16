---
title: ListMessages
second_title: Справочник по Aspose.Email для .NET API
description: Список сообщений. Получает информацию для поискового сообщения
type: docs
weight: 870
url: /ru/net/aspose.email.clients.imap/imapclient/listmessages/
---
## ListMessages(string, ImapListFields, int) {#listmessages_21}

Список сообщений. Получает информацию для поискового сообщения

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, ImapListFields fieldsList, 
    int maxNumberOfMessages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderName | String | Папка для получения сообщений. |
| fieldsList | ImapListFields | Поля, которые могут быть получены с сервера. |
| maxNumberOfMessages | Int32 | Максимальное количество сообщений. |

### Возвращаемое значение

ImapMessageInfoCollection

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не отображаются в списке

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* enum [ImapListFields](../../imaplistfields)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, ImapListFields, int) {#listmessages_8}

Список сообщений. Получает информацию для поискового сообщения

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    ImapListFields fieldsList, int maxNumberOfMessages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| folderName | String | Папка для получения сообщений. |
| fieldsList | ImapListFields | Поля, которые могут быть получены с сервера. |
| maxNumberOfMessages | Int32 | Максимальное количество сообщений. |

### Возвращаемое значение

ImapMessageInfoCollection

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не отображаются в списке

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [ImapListFields](../../imaplistfields)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(string, IEnumerable&lt;string&gt;) {#listmessages_26}

Список сообщений. Получает информацию для поискового сообщения

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, IEnumerable<string> uniqueIdLst)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderName | String | Папка для получения сообщений. |
| uniqueIdLst | IEnumerable`1 | Список уникальных идентификаторов для[`ImapMessageInfo`](../../imapmessageinfo)для получения с сервера. |

### Возвращаемое значение

ImapMessageInfoCollection

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не отображаются в списке

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(string, IEnumerable&lt;int&gt;) {#listmessages_25}

Список сообщений. Получает информацию для поискового сообщения

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, IEnumerable<int> sequenceNumberLst)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderName | String | Папка для получения сообщений. |
| sequenceNumberLst | IEnumerable`1 | список sequenceNumber для[`ImapMessageInfo`](../../imapmessageinfo)для получения с сервера. |

### Возвращаемое значение

ImapMessageInfoCollection

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не отображаются в списке

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, IEnumerable&lt;string&gt;) {#listmessages_13}

Список сообщений. Получает информацию для поискового сообщения

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    IEnumerable<string> uniqueIdLst)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| folderName | String | Папка для получения сообщений. |
| uniqueIdLst | IEnumerable`1 | Список уникальных идентификаторов для[`ImapMessageInfo`](../../imapmessageinfo)для получения с сервера. |

### Возвращаемое значение

ImapMessageInfoCollection

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не отображаются в списке

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, IEnumerable&lt;int&gt;) {#listmessages_12}

Список сообщений. Получает информацию для поискового сообщения

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    IEnumerable<int> sequenceNumberLst)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| folderName | String | Папка для получения сообщений. |
| sequenceNumberLst | IEnumerable`1 | список sequenceNumber для[`ImapMessageInfo`](../../imapmessageinfo)для получения с сервера. |

### Возвращаемое значение

ImapMessageInfoCollection

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не отображаются в списке

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, long, bool, IEnumerable&lt;string&gt;) {#listmessages_11}

Получает список сообщений в указанной папке

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    long modificationSequence, bool retrieveRecursively, IEnumerable<string> messageExtraFields)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Connection на сервер |
| folderName | String | Папка для получения сообщений. |
| modificationSequence | Int64 | Последовательность модификации |
| retrieveRecursively | Boolean | Указывает, должны ли сообщения извлекаться рекурсивно. |
| messageExtraFields | IEnumerable`1 | Список дополнительных параметров для сообщения, которое будет запрошено. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(IConnection) {#listmessages_1}

Получает список сообщений в текущей папке

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Connection на сервер |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(IConnection, string) {#listmessages_7}

Получает список сообщений в указанной папке

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Connection на сервер |
| folderName | String | Папка для получения сообщений. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(IConnection, bool) {#listmessages_4}

Получает список сообщений в текущей папке

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, bool retrieveRecursively)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Connection на сервер |
| retrieveRecursively | Boolean | Указывает, должны ли сообщения извлекаться рекурсивно. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(IConnection, long) {#listmessages_6}

Получает список сообщений в текущей папке, которые имеют последовательность модификации больше указанного значения. Подробнее https://tools.ietf.org/html/rfc7162

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Connection на сервер |
| modificationSequence | Int64 | Последовательность модификаций |

### Возвращаемое значение

Коллекция[`ImapMessageInfo`](../../imapmessageinfo)представляет информацию о сообщениях.

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, bool) {#listmessages_10}

Получает список сообщений в указанной папке

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    bool retrieveRecursively)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Connection на сервер |
| folderName | String | Папка для получения сообщений. |
| retrieveRecursively | Boolean | Указывает, должны ли сообщения извлекаться рекурсивно. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

Получает список сообщений в текущей папке

```csharp
public ImapMessageInfoCollection ListMessages()
```

### Возвращаемое значение

Коллекция ImapMessageInfo объекты

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_19}

Получает список сообщений в текущей папке

```csharp
public ImapMessageInfoCollection ListMessages(IEnumerable<string> messageExtraFields)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | List дополнительных параметров для сообщения, которое будет запрошено. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(bool) {#listmessages_16}

Получает список сообщений в текущей папке

```csharp
public ImapMessageInfoCollection ListMessages(bool retrieveRecursively)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| retrieveRecursively | Boolean | Указывает , если сообщения должны извлекаться рекурсивно. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(string) {#listmessages_20}

Получает список сообщений в указанной папке

```csharp
public ImapMessageInfoCollection ListMessages(string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderName | String | Папка для получения сообщений. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_23}

Получает список сообщений в указанной папке

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, bool retrieveRecursively)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderName | String | Папка для получения сообщений. |
| retrieveRecursively | Boolean | Указывает, должны ли сообщения извлекаться рекурсивно. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(string, bool, IEnumerable&lt;string&gt;) {#listmessages_24}

Получает список сообщений в указанной папке

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, bool retrieveRecursively, 
    IEnumerable<string> messageExtraFields)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderName | String | Папка для получения сообщений. |
| retrieveRecursively | Boolean | Указывает, должны ли сообщения извлекаться рекурсивно. |
| messageExtraFields | IEnumerable`1 | Список дополнительных параметров для сообщения, которое будет запрошено. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(long) {#listmessages_18}

Получает список сообщений в текущей папке, которые имеют последовательность модификации больше указанного значения. Подробнее https://tools.ietf.org/html/rfc7162

```csharp
public ImapMessageInfoCollection ListMessages(long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| modificationSequence | Int64 | Модификация sequence |

### Возвращаемое значение

Коллекция[`ImapMessageInfo`](../../imapmessageinfo), представляющая информацию о сообщениях.

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, MailQuery, int) {#listmessages_9}

Получает список сообщений в текущей папке.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    MailQuery query, int maxNumberOfMessages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| folderName | String | Расположение сообщений |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery), представляющий поисковый запрос. |
| maxNumberOfMessages | Int32 | Максимальное количество сообщений. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo.

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(IConnection, MailQuery) {#listmessages_2}

Получает список сообщений в текущей папке.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, MailQuery query)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery), представляющий поисковый запрос. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo.

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(IConnection, MailQuery, int) {#listmessages_3}

Получает список сообщений в текущей папке.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, MailQuery query, 
    int maxNumberOfMessages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery), представляющий поисковый запрос. |
| maxNumberOfMessages | Int32 | Максимальное количество сообщений. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo.

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(MailQuery) {#listmessages_14}

Получает список сообщений в текущей папке.

```csharp
public ImapMessageInfoCollection ListMessages(MailQuery query)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery), представляющий поисковый запрос. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo.

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery, int) {#listmessages_22}

Получает список сообщений в текущей папке.

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, MailQuery query, 
    int maxNumberOfMessages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| имяпапки | String | Расположение сообщений |
| запрос | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery), представляющий поисковый запрос. |
| maxNumberOfMessages | Int32 | Максимальное количество сообщений. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo.

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(MailQuery, int) {#listmessages_15}

Получает список сообщений в текущей папке.

```csharp
public ImapMessageInfoCollection ListMessages(MailQuery query, int maxNumberOfMessages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery), представляющий поисковый запрос. |
| maxNumberOfMessages | Int32 | Максимальное количество сообщений. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo.

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(IConnection, int) {#listmessages_5}

Получает список сообщений в текущей папке.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, int maxNumberOfMessages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| maxNumberOfMessages | Int32 | Максимальное количество Сообщения. |

### Возвращаемое значение

Коллекция[`ImapMessageInfo`](../../imapmessageinfo)представляющая информацию о сообщениях.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages*имеет отрицательное значение. |

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(int) {#listmessages_17}

Получает список сообщений в текущей папке.

```csharp
public ImapMessageInfoCollection ListMessages(int maxNumberOfMessages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | Максимальное количество сообщений. |

### Возвращаемое значение

Коллекция[`ImapMessageInfo`](../../imapmessageinfo)представляющая информацию о сообщениях.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages*имеет отрицательное значение. |

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
