---
title: CopyConversationItemsAsync
second_title: Referencia de la API de Aspose.Email para .NET
description: Copia los elementos de conversación que se encuentran en la carpeta especificada en la carpeta de destino especificada
type: docs
weight: 70
url: /es/net/aspose.email.clients.exchange.webservice/iasyncewsclient/copyconversationitemsasync/
---
## IAsyncEwsClient.CopyConversationItemsAsync method

Copia los elementos de conversación, que se encuentran en la carpeta especificada, en la carpeta de destino especificada

```csharp
public Task CopyConversationItemsAsync(string conversationId, string destinationFolderId, 
    string contextFolderId = null, CancellationToken cancellationToken = default)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| conversationId | String | ID de conversación para copiar |
| destinationFolderId | String | ID de la carpeta en la que se copian los elementos |
| contextFolderId | String | ID de la carpeta en la que se encuentran los elementos de conversación. Nota: si se establece en nulo (o vacío), todos los elementos de conversación se copiarán |
| cancellationToken | CancellationToken | El token de cancelación. |

### Excepciones

| excepción | condición |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *conversationId* es`nulo`o`vacío` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *destinationFolderId* es`nulo`o`vacío` |

### Ver también

* interface [IAsyncEwsClient](../../iasyncewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->