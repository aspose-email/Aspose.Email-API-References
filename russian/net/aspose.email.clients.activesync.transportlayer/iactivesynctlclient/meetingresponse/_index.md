---
title: MeetingResponse
second_title: Справочник по Aspose.Email для .NET API
description: Принимает предварительно принимает или отклоняет приглашение на собрание в папке Входящие или в папке Календарь пользователя.
type: docs
weight: 110
url: /ru/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse/
---
## MeetingResponse(UserResponse, string, string) {#meetingresponse}

Принимает, предварительно принимает или отклоняет приглашение на собрание в папке "Входящие" или в папке "Календарь" пользователя.

```csharp
public MeetingResponseResult MeetingResponse(UserResponse userResponse, string collectionId, 
    string requestId)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| userResponse | UserResponse | Указывает, принимается ли собрание, предварительно принимается или отклоняется. |
| collectionId | String | Указывает папку, содержащую приглашение на собрание. Необязательно, если включен LongId. Значение CollectionId может иметь длину до 64 символов. |
| requestId | String | Указывает идентификатор сервера элемента сообщения с приглашением на собрание. Необязательно, если включен LongId. Значение RequestId может иметь длину до 64 символов. |

### Возвращаемое значение

Возвращает объект MeetingResponseResult.

### Смотрите также

* class [MeetingResponseResult](../../meetingresponseresult)
* enum [UserResponse](../../userresponse)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* сборка [Aspose.Email](../../../)

---

## MeetingResponse(UserResponse, string, string, string, string) {#meetingresponse_1}

Принимает, предварительно принимает или отклоняет приглашение на собрание в папке "Входящие" или в папке "Календарь" пользователя.

```csharp
public MeetingResponseResult MeetingResponse(UserResponse userResponse, string collectionId, 
    string requestId, string longId, string instanceId)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| userResponse | UserResponse | Указывает, принимается ли собрание, предварительно принимается или отклоняется. |
| collectionId | String | Указывает папку, содержащую приглашение на собрание. Необязательно, если включен LongId. Значение CollectionId может иметь длину до 64 символов. |
| requestId | String | Указывает идентификатор сервера элемента сообщения с приглашением на собрание. Необязательно, если включен LongId. Значение RequestId может иметь длину до 64 символов. |
| longId | String | Указывает длинный идентификатор исходного приглашения на собрание, который возвращается в ответном сообщении на команду поиска. Если LongId присутствует, то CollectionId, InstanceId и RequestId отсутствуют. Значение LongId может иметь длину до 256 символов. |
| instanceId | String | Указывает экземпляр повторяющегося собрания, который необходимо изменить. InstanceId не поддерживается, если используется версия протокола 12.1 или 14.0. Значение состояния 2 возвращается, если элемент InstanceId включен в запросы с версией протокола 12.1 или 14.0. InstanceId содержит время начала экземпляра встречи или собрания, который необходимо изменить. Если InstanceId не включен в запрос MeetingResponse, то действие должно выполняться для каждого экземпляра повторяющегося элемента. InstanceId может указывать время начала исключения для повторяющейся встречи или собрания. InstanceId можно использовать с LongId для идентификации элемента календаря или с CollectionId и RequestId для идентификации элемента календаря. например, 2010-04-08T18:16:00.000Z. Если указанное значение InstanceId имеет неправильный формат, сервер отвечает значением элемента Status, равным 104. Если значение InstanceId указывает на неповторяющееся совещание, сервер отвечает значением элемента Status, равным 146. |

### Возвращаемое значение

Возвращает объект MeetingResponseResult.

### Смотрите также

* class [MeetingResponseResult](../../meetingresponseresult)
* enum [UserResponse](../../userresponse)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* сборка [Aspose.Email](../../../)

---

## MeetingResponse(params MeetingResponseRequest[]) {#meetingresponse_2}

Принимает, предварительно принимает или отклоняет приглашение на собрание в папке "Входящие" или в папке "Календарь" пользователя.

```csharp
public MeetingResponseResult[] MeetingResponse(params MeetingResponseRequest[] request)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| request | MeetingResponseRequest[] | Массив объектов MeetingResponseRequest |

### Возвращаемое значение

Возвращает массив объектов MeetingResponseResult.

### Смотрите также

* class [MeetingResponseResult](../../meetingresponseresult)
* class [MeetingResponseRequest](../../meetingresponserequest)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* сборка [Aspose.Email](../../../)

---

## MeetingResponse(IEnumerable&lt;MeetingResponseRequest&gt;) {#meetingresponse_3}

Принимает, предварительно принимает или отклоняет приглашение на собрание в папке "Входящие" или в папке "Календарь" пользователя.

```csharp
public MeetingResponseResult[] MeetingResponse(IEnumerable<MeetingResponseRequest> request)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| request | IEnumerable`1 | Перечисление объектов MeetingResponseRequest |

### Возвращаемое значение

Возвращает массив объектов MeetingResponseResult.

### Смотрите также

* class [MeetingResponseResult](../../meetingresponseresult)
* class [MeetingResponseRequest](../../meetingresponserequest)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
