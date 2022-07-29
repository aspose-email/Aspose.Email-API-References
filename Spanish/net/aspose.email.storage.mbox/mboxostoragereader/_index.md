---
title: MboxoStorageReader
second_title: Referencia de la API de Aspose.Email para .NET
description: Representa el lector de almacenamiento en formato mboxo este formato está siendo utilizado por Eudora.
type: docs
weight: 20050
url: /es/net/aspose.email.storage.mbox/mboxostoragereader/
---
## MboxoStorageReader class

Representa el lector de almacenamiento en formato mboxo, este formato está siendo utilizado por Eudora.

```csharp
public sealed class MboxoStorageReader : MboxStorageReader
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MboxoStorageReader](mboxostoragereader#constructor)(Stream, MboxLoadOptions) | Inicializa una nueva instancia del[`MboxoStorageReader`](../mboxostoragereader) clase. |
| [MboxoStorageReader](mboxostoragereader#constructor_2)(string, MboxLoadOptions) | Inicializa una nueva instancia del[`MboxrdStorageReader`](../mboxrdstoragereader) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BaseStream](../../aspose.email.storage.mbox/mboxstoragereader/basestream) { get; } | Obtiene el flujo base. |
| [CurrentDataSize](../../aspose.email.storage.mbox/mboxstoragereader/currentdatasize) { get; } | Obtiene el número de bytes que lee el método ReadNextMessage. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../aspose.email.storage.mbox/mboxstoragereader/dispose)() | Realiza tareas definidas por la aplicación asociadas con liberar, liberar o restablecer recursos no administrados. |
| [EnumerateMessages](../../aspose.email.storage.mbox/mboxstoragereader/enumeratemessages)() | Expone el enumerador, que admite una iteración de mensajes en el almacenamiento. |
| override [GetTotalItemsCount](../../aspose.email.storage.mbox/mboxostoragereader/gettotalitemscount)() | Devuelve el número de mensajes en un almacenamiento. |
| override [ReadNextMessage](../../aspose.email.storage.mbox/mboxostoragereader/readnextmessage#readnextmessage)() | Lee el siguiente mensaje del flujo de almacenamiento subyacente. |
| override [ReadNextMessage](../../aspose.email.storage.mbox/mboxostoragereader/readnextmessage#readnextmessage_1)(out string) | Lee el siguiente mensaje del flujo de almacenamiento subyacente. |

### Ver también

* class [MboxStorageReader](../mboxstoragereader)
* espacio de nombres [Aspose.Email.Storage.Mbox](../../aspose.email.storage.mbox)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->