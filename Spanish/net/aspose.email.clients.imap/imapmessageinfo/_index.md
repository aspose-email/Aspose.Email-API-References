---
title: ImapMessageInfo
second_title: Referencia de la API de Aspose.Email para .NET
description: Representa un objeto de mensaje Imap.
type: docs
weight: 16370
url: /es/net/aspose.email.clients.imap/imapmessageinfo/
---
## ImapMessageInfo class

Representa un objeto de mensaje Imap.

```csharp
public sealed class ImapMessageInfo : MessageInfoBase
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Answered](../../aspose.email.clients.imap/imapmessageinfo/answered) { get; } | Obtiene un valor que indica si la propiedad Flags contiene el indicador Contestado. |
| virtual [Bcc](../../aspose.email.clients/messageinfobase/bcc) { get; } | Obtiene una copia oculta del mensaje de correo electrónico. |
| virtual [CC](../../aspose.email.clients/messageinfobase/cc) { get; } | Obtiene CC del mensaje de correo electrónico. |
| [ConversationId](../../aspose.email.clients.imap/imapmessageinfo/conversationid) { get; } | Obtiene un valor que indica el id. de conversación. |
| virtual [Date](../../aspose.email.clients/messageinfobase/date) { get; } | La fecha de origen especifica la fecha y la hora en que el creador del mensaje indicó que el mensaje estaba completo y listo para ingresar al sistema de entrega de correo. Por ejemplo, este podría ser el momento en que un usuario presiona el botón "enviar" o "enviar" en un programa de aplicación. En cualquier caso, no tiene la intención específica de transmitir el momento en que el mensaje se transporta realmente, pero más bien, el momento en que el ser humano u otro creador del mensaje ha puesto el mensaje en su forma final, listo para el transporte. (por ejemplo, un usuario de computadora portátil que no está conectado a una red puede poner en cola un mensaje para su entrega. La fecha de origen pretende contener la fecha y la hora en que el usuario puso en cola el mensaje, no la hora en que el usuario se conectó a la red para enviar el mensaje.) |
| [Deleted](../../aspose.email.clients.imap/imapmessageinfo/deleted) { get; } | Obtiene un valor que indica si la propiedad Flags contiene el indicador Eliminado. |
| [Draft](../../aspose.email.clients.imap/imapmessageinfo/draft) { get; } | Obtiene un valor que indica si la propiedad Flags contiene el indicador Draft. |
| [ExtraParameters](../../aspose.email.clients.imap/imapmessageinfo/extraparameters) { get; } | Obtiene parámetros extra de un mensaje. |
| [Flagged](../../aspose.email.clients.imap/imapmessageinfo/flagged) { get; } | Obtiene un valor que indica si la propiedad Flags contiene el indicador Flagged. |
| [Flags](../../aspose.email.clients.imap/imapmessageinfo/flags) { get; } | Obtiene las banderas del mensaje. |
| [From](../../aspose.email.clients/messageinfobase/from) { get; } | Obtiene la lista de autores de este mensaje. |
| [Headers](../../aspose.email.clients/messageinfobase/headers) { get; } | Obtiene los encabezados del mensaje de correo electrónico. |
| [InternalDate](../../aspose.email.clients.imap/imapmessageinfo/internaldate) { get; } | La fecha y hora internas del mensaje en el servidor. Esta no es la fecha y hora en el encabezado [RFC-2822], sino una fecha y hora que refleja cuándo se recibió el mensaje. : en el caso de mensajes entregados a través de [SMTP], DEBERÍA ser la fecha y la hora de la entrega final del mensaje según lo definido por [SMTP]. - En el caso de mensajes entregados por el comando IMAP4rev1 COPY, DEBERÍA ser la fecha y hora internas del mensaje de origen. - En el caso de mensajes entregados por el comando IMAP4rev1 APPEND, DEBERÍA ser la fecha y hora especificadas en la descripción del comando APPEND. - Todos los demás casos están definidos por la implementación. |
| [IsRead](../../aspose.email.clients.imap/imapmessageinfo/isread) { get; } | Obtiene un valor que indica si la propiedad Flags contiene el indicador de lectura. |
| [ListUnsubscribe](../../aspose.email.clients/messageinfobase/listunsubscribe) { get; } | El campo Lista-Cancelar suscripción describe el comando (preferiblemente usando el correo) para cancelar directamente la suscripción del usuario (eliminándolo de la lista). Para obtener más detalles, consulte https://tools.ietf.org/html/rfc2369 |
| [MessageId](../../aspose.email.clients/messageinfobase/messageid) { get; } | Obtiene el ID del mensaje. |
| [ModificationSequence](../../aspose.email.clients.imap/imapmessageinfo/modificationsequence) { get; } | Obtiene la secuencia de modificación de este mensaje. Ver más: https://tools.ietf.org/html/rfc7162 |
| [ParentFolder](../../aspose.email.clients.imap/imapmessageinfo/parentfolder) { get; } | Obtiene la carpeta principal para el mensaje |
| virtual [Properties](../../aspose.email.clients/messageinfobase/properties) { get; } | Obtiene las propiedades de un mapi. |
| [Recent](../../aspose.email.clients.imap/imapmessageinfo/recent) { get; } | Obtiene un valor que indica si la propiedad Flags contiene el indicador Recent. |
| [ReplyTo](../../aspose.email.clients/messageinfobase/replyto) { get; } | Obtiene la lista de direcciones que deben recibir respuestas a este mensaje. |
| [Sender](../../aspose.email.clients/messageinfobase/sender) { get; } | Obtiene el remitente de este mensaje. |
| [SequenceNumber](../../aspose.email.clients.imap/imapmessageinfo/sequencenumber) { get; } | Obtiene el número de secuencia del mensaje. |
| [Size](../../aspose.email.clients/messageinfobase/size) { get; } | Obtiene el tamaño del mensaje de correo electrónico. |
| [Subject](../../aspose.email.clients/messageinfobase/subject) { get; } | Obtiene el asunto del mensaje de correo electrónico. |
| virtual [To](../../aspose.email.clients/messageinfobase/to) { get; } | Obtiene los destinatarios del mensaje de correo electrónico. |
| [UniqueId](../../aspose.email.clients.imap/imapmessageinfo/uniqueid) { get; } | Obtiene el ID único del mensaje. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ContainsKeyword](../../aspose.email.clients.imap/imapmessageinfo/containskeyword)(string) | Obtiene un valor que indica si la propiedad Flags contiene el indicador de palabra clave. |
| virtual [Dispose](../../aspose.email.clients/messageinfobase/dispose)() | Realiza tareas asociadas con liberar, liberar o restablecer recursos no administrados. |
| override [ToString](../../aspose.email.clients.imap/imapmessageinfo/tostring)() | Devuelve una cadena que representa el objeto actual. |

### Ver también

* class [MessageInfoBase](../../aspose.email.clients/messageinfobase)
* espacio de nombres [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
