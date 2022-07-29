---
title: FetchTaskAsync
second_title: Referencia de la API de Aspose.Email para .NET
description: Obtiene la tarea especificada.
type: docs
weight: 280
url: /es/net/aspose.email.clients.exchange.webservice/iasyncewsclient/fetchtaskasync/
---
## IAsyncEwsClient.FetchTaskAsync method

Obtiene la tarea especificada.

```csharp
public Task<ExchangeTask> FetchTaskAsync(string taskUri, 
    CancellationToken cancellationToken = default)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| taskUri | String | Una tarea uri. |
| cancellationToken | CancellationToken | El token de cancelación. |

### Valor_devuelto

un buscado[`ExchangeTask`](../../exchangetask)

### Excepciones

| excepción | condición |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *taskUri* es`nulo`o`vacío`. |

### Ver también

* class [ExchangeTask](../../exchangetask)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->