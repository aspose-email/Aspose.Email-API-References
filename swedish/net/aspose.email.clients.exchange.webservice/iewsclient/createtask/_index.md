---
title: CreateTask
second_title: Aspose.Email för .NET API-referens
description: Skapar den givna uppgiften i standarduppgiftsmappen.
type: docs
weight: 550
url: /sv/net/aspose.email.clients.exchange.webservice/iewsclient/createtask/
---
## CreateTask(ExchangeTask) {#createtask}

Skapar den givna uppgiften i standarduppgiftsmappen.

```csharp
public string CreateTask(ExchangeTask task)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| task | ExchangeTask | En uppgift att skapa. |

### Returvärde

En uppgift uri

### Undantag

| undantag | skick |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *task* är`null`. |

### Se även

* class [ExchangeTask](../../exchangetask)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## CreateTask(string, ExchangeTask) {#createtask_2}

Skapar den givna uppgiften i den angivna mappen.

```csharp
public string CreateTask(string folder, ExchangeTask task)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | String | En mapp där uppgiften ska skapas. |
| task | ExchangeTask | En uppgift att skapa. |

### Returvärde

En uppgift uri

### Undantag

| undantag | skick |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *folder* är`null`eller`tömma`. |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *task* är`null`. |

### Se även

* class [ExchangeTask](../../exchangetask)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->