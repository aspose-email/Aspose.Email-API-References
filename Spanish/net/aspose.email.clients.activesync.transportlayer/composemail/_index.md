---
title: ComposeMail
second_title: Referencia de la API de Aspose.Email para .NET
description: Espacio de nombres ComposeMail del protocolo ActiveSync
type: docs
weight: 1120
url: /es/net/aspose.email.clients.activesync.transportlayer/composemail/
---
## ComposeMail enumeration

Espacio de nombres ComposeMail del protocolo ActiveSync

```csharp
public enum ComposeMail
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| SendMail | `5` | El elemento SendMail es un elemento obligatorio en las solicitudes y respuestas del comando SendMail que identifica el cuerpo del HTTP POST que contiene un comando SendMail (sección 2.2.2.15). |
| SmartForward | `6` | El elemento SmartForward es un elemento obligatorio en las solicitudes y respuestas de comandos de SmartForward que identifica el cuerpo de HTTP POST que contiene un comando de SmartForward (sección 2.2.2.17). |
| SmartReply | `7` | El elemento SmartReply es un elemento obligatorio en las solicitudes y respuestas de comandos SmartReply que identifica el cuerpo de HTTP POST que contiene un comando SmartReply (sección 2.2.2.18). |
| SaveInSentItems | `8` | El elemento SaveInSentItems especifica si se almacenará una copia del mensaje en la carpeta Elementos enviados. |
| ReplaceMime | `9` | Especifica si el cliente está enviando el mensaje completo. |
| Source | `11` | Contiene información sobre el mensaje de origen. |
| FolderId | `12` | Especifica la ID de la carpeta para el mensaje de origen, que se devuelve en el mensaje de respuesta del comando FolderSync (sección 2.2.2.4.2). |
| ItemId | `13` | Especifica el ID de elemento para el mensaje de origen, que se devuelve en el mensaje de respuesta del comando de sincronización (sección 2.2.2.19.2). |
| LongId | `14` | Este elemento especifica el ID largo de la solicitud de reunión de origen, que se devuelve en el mensaje de respuesta del comando de búsqueda (sección 2.2.2.14.2). |
| InstanceId | `15` | El elemento InstanceId es un elemento secundario opcional del elemento Source en las solicitudes de comando SmartForward y las solicitudes de comando SmartReply que especifica la instancia de una recurrencia para el elemento de origen. |
| Mime | `16` | Contiene el mensaje codificado en MIME. |
| ClientId | `17` | Especifica el ID de mensaje único (MID) del cliente. |
| Status | `18` | Indica el motivo de la falla de una solicitud de comando. |
| AccountId | `19` | Identifica la cuenta desde la que se envía un correo electrónico. |

### Ver también

* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->