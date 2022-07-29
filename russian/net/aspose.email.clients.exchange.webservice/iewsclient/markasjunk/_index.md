---
title: MarkAsJunk
second_title: Справочник по Aspose.Email для .NET API
description: Метод MarkAsJunk перемещает почтовые сообщения в папку нежелательной почты и блокирует отправителя сообщения.
type: docs
weight: 1270
url: /ru/net/aspose.email.clients.exchange.webservice/iewsclient/markasjunk/
---
## MarkAsJunk(bool, params string[]) {#markasjunk_3}

Метод MarkAsJunk перемещает почтовые сообщения в папку нежелательной почты и блокирует отправителя сообщения.

```csharp
public string[] MarkAsJunk(bool isJunk, params string[] messageUriEn)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| isJunk | Boolean | Указывает, помечаются ли сообщения как нежелательная почта. При значении true добавляет отправителя сообщения в черный список. При значении false удаляет отправителя сообщения из черного списка. |
| messageUriEn | String[] | Массив сообщений uri |

### Возвращаемое значение

Возвращает массив идентификаторов сообщений, перемещенных в папку нежелательной почты.

### Смотрите также

* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## MarkAsJunk(bool, bool, params string[]) {#markasjunk_1}

Метод MarkAsJunk перемещает почтовые сообщения в папку нежелательной почты и блокирует отправителя сообщения.

```csharp
public string[] MarkAsJunk(bool isJunk, bool moveItem, params string[] messageUriEn)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| isJunk | Boolean | Указывает, помечаются ли сообщения как нежелательная почта. При значении true добавляет отправителя сообщения в черный список. При значении false удаляет отправителя сообщения из черного списка. |
| moveItem | Boolean | Указывает, перемещаются ли сообщения в папку нежелательной почты. |
| messageUriEn | String[] | Массив сообщений uri |

### Возвращаемое значение

Возвращает массив идентификаторов сообщений, перемещенных в папку нежелательной почты.

### Смотрите также

* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## MarkAsJunk(bool, IEnumerable&lt;string&gt;) {#markasjunk_2}

Метод MarkAsJunk перемещает почтовые сообщения в папку нежелательной почты и блокирует отправителя сообщения.

```csharp
public string[] MarkAsJunk(bool isJunk, IEnumerable<string> messageUriEn)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| isJunk | Boolean | Указывает, помечаются ли сообщения как нежелательная почта. При значении true добавляет отправителя сообщения в черный список. При значении false удаляет отправителя сообщения из черного списка. |
| messageUriEn | IEnumerable`1 | Перечисление uri сообщения |

### Возвращаемое значение

Возвращает идентификатор элемента сообщения, помеченного как нежелательная почта.

### Смотрите также

* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## MarkAsJunk(bool, bool, IEnumerable&lt;string&gt;) {#markasjunk}

Метод MarkAsJunk перемещает почтовые сообщения в папку нежелательной почты и блокирует отправителя сообщения.

```csharp
public string[] MarkAsJunk(bool isJunk, bool moveItem, IEnumerable<string> messageUriEn)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| isJunk | Boolean | Указывает, помечаются ли сообщения как нежелательная почта. При значении true добавляет отправителя сообщения в черный список. При значении false удаляет отправителя сообщения из черного списка. |
| moveItem | Boolean | Указывает, перемещаются ли сообщения в папку нежелательной почты. |
| messageUriEn | IEnumerable`1 | Перечисление uri сообщения |

### Возвращаемое значение

Возвращает массив идентификаторов сообщений, перемещенных в папку нежелательной почты.

### Смотрите также

* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## MarkAsJunk(bool, bool, IEnumerable&lt;string&gt;, out string[], out string[], out string[]) {#markasjunk_4}

Метод MarkAsJunk перемещает почтовые сообщения в папку нежелательной почты и блокирует отправителя сообщения.

```csharp
public void MarkAsJunk(bool isJunk, bool moveItem, IEnumerable<string> messageUriEn, 
    out string[] movedMessageIds, out string[] failedMessageIds, out string[] errorMessages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| isJunk | Boolean | Указывает, помечаются ли сообщения как нежелательная почта. При значении true добавляет отправителя сообщения в черный список. При значении false удаляет отправителя сообщения из черного списка. |
| moveItem | Boolean | Указывает, перемещаются ли сообщения в папку нежелательной почты. |
| messageUriEn | IEnumerable`1 | Перечисление uri сообщения |
| movedMessageIds | String[]& | Возвращает массив идентификаторов сообщений, перемещенных в папку нежелательной почты. |
| failedMessageIds | String[]& | Возвращает массив идентификаторов сообщений, которые не были перемещены в папку нежелательной почты. |
| errorMessages | String[]& | Сообщения об ошибках для неудачных операций |

### Смотрите также

* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
