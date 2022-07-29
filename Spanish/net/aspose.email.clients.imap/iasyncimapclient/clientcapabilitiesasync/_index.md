---
title: ClientCapabilitiesAsync
second_title: Referencia de la API de Aspose.Email para .NET
description: Notifica al servidor qué extensiones son compatibles con el cliente. Tenga en cuenta que esta operación solo funciona en caso de que el servidor admita RFC5161 Ver más https//tools.ietf.org/html/rfc5161
type: docs
weight: 60
url: /es/net/aspose.email.clients.imap/iasyncimapclient/clientcapabilitiesasync/
---
## IAsyncImapClient.ClientCapabilitiesAsync method

Notifica al servidor qué extensiones son compatibles con el cliente. Tenga en cuenta que esta operación solo funciona en caso de que el servidor admita RFC5161 Ver más https://tools.ietf.org/html/rfc5161

```csharp
public Task<IEnumerable<string>> ClientCapabilitiesAsync(IEnumerable<string> capabilityNames, 
    IConnection connection = null, CancellationToken token = default)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IEnumerable`1 | Conexión a un servidor |
| token | IConnection | Propaga la notificación de que las operaciones deben cancelarse. |
| capabilityNames | CancellationToken | Matriz de capacidades que son compatibles con el cliente |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->