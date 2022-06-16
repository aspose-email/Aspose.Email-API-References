---
title: GraphClient
second_title: Справочник по Aspose.Email для .NET API
description: Предоставляет доступ к MS Exchange Server Office365 с помощью REST API.
type: docs
weight: 15920
url: /ru/net/aspose.email.clients.graph/graphclient/
---
## GraphClient class

Предоставляет доступ к MS Exchange Server (Office365) с помощью REST API.

```csharp
public abstract class GraphClient : IDisposable
```

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [MultipleServicesTokenProvider](../../aspose.email.clients.graph/graphclient/multipleservicestokenprovider) { get; set; } | Получает или задает объект, позволяющий получить маркер доступа OAuth. |
| virtual [Proxy](../../aspose.email.clients.graph/graphclient/proxy) { get; set; } | Получает или устанавливает данные для прокси-доступа к серверу Exchange. |
| virtual [Resource](../../aspose.email.clients.graph/graphclient/resource) { get; set; } | Получает или задает тип ресурса. |
| virtual [ResourceId](../../aspose.email.clients.graph/graphclient/resourceid) { get; set; } | Получает или устанавливает идентификатор ресурса. Например, для пользователей это может быть основное имя пользователя (UPN) или идентификатор пользователя |
| virtual [TenantId](../../aspose.email.clients.graph/graphclient/tenantid) { get; set; } | Получает или задает идентификатор арендатора |
| virtual [Timeout](../../aspose.email.clients.graph/graphclient/timeout) { get; set; } | Получает или задает количество миллисекунд ожидания до истечения времени ожидания операции. Значение по умолчанию — 100 000 миллисекунд (100 секунд). |
| virtual [TokenProvider](../../aspose.email.clients.graph/graphclient/tokenprovider) { get; set; } | Получает или задает объект, позволяющий получить маркер доступа OAuth. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Dispose](../../aspose.email.clients.graph/graphclient/dispose)() | Выполняет определяемые приложением задачи, связанные с освобождением, освобождением или сбросом неуправляемых ресурсов. |
| static [GetClient](../../aspose.email.clients.graph/graphclient/getclient#getclient)(IMultipleServicesTokenProvider, string) | Инициализирует новый экземпляр класса[`GraphClient`](../graphclient)на основе |
| static [GetClient](../../aspose.email.clients.graph/graphclient/getclient#getclient_1)(ITokenProvider, string) | Инициализирует новый экземпляр класса[`GraphClient`](../graphclient)на основе |

### Смотрите также

* пространство имен [Aspose.Email.Clients.Graph](../../aspose.email.clients.graph)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->