---
title: Ping
second_title: Справочник по Aspose.Email для .NET API
description: Команда Ping используется чтобы запросить чтобы сервер контролировал указанные папки на наличие изменений которые потребуют повторной синхронизации клиента.
type: docs
weight: 140
url: /ru/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping/
---
## Ping(string, FolderClass) {#ping_5}

Команда Ping используется, чтобы запросить, чтобы сервер контролировал указанные папки на наличие изменений, которые потребуют повторной синхронизации клиента.

```csharp
public string[] Ping(string serverId, FolderClass fClass)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| serverId | String | Элемент Id является обязательным дочерним элементом элемента Folder в командных запросах Ping, который указывает идентификатор сервера папки, подлежащей мониторингу. |
| fClass | FolderClass | Элемент Class является обязательным дочерним элементом элемента Folder в командных запросах Ping, который указывает класс содержимого папки для отслеживания. |

### Возвращаемое значение

Массив папок, в которых были обнаружены изменения

### Смотрите также

* enum [FolderClass](../../folderclass)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* сборка [Aspose.Email](../../../)

---

## Ping(int, string, FolderClass) {#ping_3}

Команда Ping используется, чтобы запросить, чтобы сервер контролировал указанные папки на наличие изменений, которые потребуют повторной синхронизации клиента.

```csharp
public string[] Ping(int heartbeatInterval, string serverId, FolderClass fClass)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| heartbeatInterval | Int32 | HeartbeatInterval определяет период времени в секундах, в течение которого сервер ДОЛЖЕН ждать перед отправкой ответа, если в указанный набор папок не добавляются новые элементы. |
| serverId | String | Элемент Id является обязательным дочерним элементом элемента Folder в командных запросах Ping, который указывает идентификатор сервера папки, подлежащей мониторингу. |
| fClass | FolderClass | Элемент Class является обязательным дочерним элементом элемента Folder в командных запросах Ping, который указывает класс содержимого папки для отслеживания. |

### Возвращаемое значение

Массив папок, в которых были обнаружены изменения

### Смотрите также

* enum [FolderClass](../../folderclass)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* сборка [Aspose.Email](../../../)

---

## Ping(params PingParameter[]) {#ping}

Команда Ping используется, чтобы запросить, чтобы сервер контролировал указанные папки на наличие изменений, которые потребуют повторной синхронизации клиента.

```csharp
public string[] Ping(params PingParameter[] pingParameters)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pingParameters | PingParameter[] | Параметры пинга |

### Возвращаемое значение

Массив папок, в которых были обнаружены изменения

### Смотрите также

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* сборка [Aspose.Email](../../../)

---

## Ping(int, params PingParameter[]) {#ping_1}

Команда Ping используется, чтобы запросить, чтобы сервер контролировал указанные папки на наличие изменений, которые потребуют повторной синхронизации клиента.

```csharp
public string[] Ping(int heartbeatInterval, params PingParameter[] pingParameters)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| heartbeatInterval | Int32 | HeartbeatInterval определяет период времени в секундах, в течение которого сервер ДОЛЖЕН ждать перед отправкой ответа, если в указанный набор папок не добавляются новые элементы. |
| pingParameters | PingParameter[] | Параметры пинга |

### Возвращаемое значение

Массив папок, в которых были обнаружены изменения

### Смотрите также

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* сборка [Aspose.Email](../../../)

---

## Ping(IEnumerable&lt;PingParameter&gt;) {#ping_4}

Команда Ping используется, чтобы запросить, чтобы сервер контролировал указанные папки на наличие изменений, которые потребуют повторной синхронизации клиента.

```csharp
public string[] Ping(IEnumerable<PingParameter> pingParameters)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pingParameters | IEnumerable`1 | Параметры пинга |

### Возвращаемое значение

Массив папок, в которых были обнаружены изменения

### Смотрите также

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* сборка [Aspose.Email](../../../)

---

## Ping(int, IEnumerable&lt;PingParameter&gt;) {#ping_2}

Команда Ping используется, чтобы запросить, чтобы сервер контролировал указанные папки на наличие изменений, которые потребуют повторной синхронизации клиента.

```csharp
public string[] Ping(int heartbeatInterval, IEnumerable<PingParameter> pingParameters)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| heartbeatInterval | Int32 | HeartbeatInterval определяет период времени в секундах, в течение которого сервер ДОЛЖЕН ждать перед отправкой ответа, если в указанный набор папок не добавляются новые элементы. |
| pingParameters | IEnumerable`1 | Параметры пинга |

### Возвращаемое значение

Массив папок, в которых были обнаружены изменения

### Смотрите также

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* пространство имен [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
