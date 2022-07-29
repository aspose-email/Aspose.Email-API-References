---
title: GetMessageUniqueIdAsync
second_title: Referencia de la API de Aspose.Email para .NET
description: Obtiene el mensaje id único
type: docs
weight: 120
url: /es/net/aspose.email.clients.pop3/iasyncpop3client/getmessageuniqueidasync/
---
## IAsyncPop3Client.GetMessageUniqueIdAsync method

Obtiene el mensaje id único

```csharp
public Task<string> GetMessageUniqueIdAsync(int sequenceNumber, IConnection connection = null, 
    CancellationToken token = default)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | Int32 | Conexión a un servidor |
| sequenceNumber | IConnection | El número de secuencia del mensaje. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

El identificador único del mensaje.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncPop3Client](../../iasyncpop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../iasyncpop3client)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->