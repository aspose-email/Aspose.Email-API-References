---
title: IEWSClient.CreateTask
second_title: Aspose.Email for .NET API Reference
description: IEWSClient method. Creates the given task in the default task folder
type: docs
weight: 550
url: /net/aspose.email.clients.exchange.webservice/iewsclient/createtask/
---
## CreateTask(ExchangeTask) {#createtask}

Creates the given task in the default task folder.

```csharp
public string CreateTask(ExchangeTask task)
```

| Parameter | Type | Description |
| --- | --- | --- |
| task | ExchangeTask | A task to create. |

### Return Value

A task uri

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception/) | *task* is `null`. |

### See Also

* class [ExchangeTask](../../exchangetask/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## CreateTask(string, ExchangeTask) {#createtask_1}

Creates the given task in the specified folder.

```csharp
public string CreateTask(string folder, ExchangeTask task)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | A folder where task should be created. |
| task | ExchangeTask | A task to create. |

### Return Value

A task uri

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | *folder* is `null` or `empty`. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception/) | *task* is `null`. |

### See Also

* class [ExchangeTask](../../exchangetask/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)


