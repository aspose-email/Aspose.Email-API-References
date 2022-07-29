---
title: EmptyFolderAsync
second_title: Referencia de la API de Aspose.Email para .NET
description: Vacía la carpeta especificada
type: docs
weight: 200
url: /es/net/aspose.email.clients.exchange.webservice/iasyncewsclient/emptyfolderasync/
---
## IAsyncEwsClient.EmptyFolderAsync method

Vacía la carpeta especificada

```csharp
public Task EmptyFolderAsync(string folderUri, 
    EmptyFolderOptions options = EmptyFolderOptions.None, 
    CancellationToken cancellationToken = default)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| folderUri | String | Especifica que la carpeta esté vacía. |
| options | EmptyFolderOptions | Especifica las opciones de borrado de carpeta |
| cancellationToken | CancellationToken | El token de cancelación. |

### Excepciones

| excepción | condición |
| --- | --- |
| [ExchangeException](../../../aspose.email/exchangeexception) | La operación de carpeta vacía falló |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *folderUri* es`nulo`o`vacío` |

### Ver también

* enum [EmptyFolderOptions](../../emptyfolderoptions)
* interface [IAsyncEwsClient](../../iasyncewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iasyncewsclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->