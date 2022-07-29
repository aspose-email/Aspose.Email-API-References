---
title: CreateItemsAsync
second_title: Referencia de la API de Aspose.Email para .NET
description: Crea los elementos especificados en la carpeta especificada
type: docs
weight: 120
url: /es/net/aspose.email.clients.exchange.webservice/iasyncewsclient/createitemsasync/
---
## IAsyncEwsClient.CreateItemsAsync method

Crea los elementos especificados en la carpeta especificada

```csharp
public Task<IEnumerable<ExchangeUploadItemResult>> CreateItemsAsync(
    IEnumerable<ExchangeStreamedItem> items, string parentFolderUri, 
    CancellationToken cancellationToken = default)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| items | IEnumerable`1 | Los elementos que se cargarán |
| parentFolderUri | String | Especifica la carpeta en la que colocar los elementos. |
| cancellationToken | CancellationToken | El token de cancelación. |

### Valor_devuelto

una matriz de[`ExchangeUploadItemResult`](../../exchangeuploaditemresult)

### Excepciones

| excepción | condición |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *items* es`nulo` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *items* es`vacío` |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *parentFolderUri* es`nulo`o`vacío` |

### Ver también

* class [ExchangeUploadItemResult](../../exchangeuploaditemresult)
* class [ExchangeStreamedItem](../../exchangestreameditem)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->