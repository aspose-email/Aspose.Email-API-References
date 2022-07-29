---
title: CreateTaskAsync
second_title: Aspose.Email für .NET-API-Referenz
description: Erstellt die angegebene Aufgabe im angegebenen Ordner.
type: docs
weight: 140
url: /de/net/aspose.email.clients.exchange.webservice/iasyncewsclient/createtaskasync/
---
## IAsyncEwsClient.CreateTaskAsync method

Erstellt die angegebene Aufgabe im angegebenen Ordner.

```csharp
public Task<string> CreateTaskAsync(ExchangeTask task, string folder = null, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| task | ExchangeTask | Eine zu erstellende Aufgabe. |
| folder | String | Ein Ordner, in dem die Aufgabe erstellt werden soll. Die Mappe[`TasksUri`](../../../aspose.email.clients.exchange/exchangemailboxinfo/tasksuri) is wird standardmäßig verwendet. |
| cancellationToken | CancellationToken | Das Abbruchtoken. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *task* ist`Null`. |

### Siehe auch

* class [ExchangeTask](../../exchangetask)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* namensraum [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->