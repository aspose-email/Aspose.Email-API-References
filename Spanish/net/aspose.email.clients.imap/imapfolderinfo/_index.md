---
title: ImapFolderInfo
second_title: Referencia de la API de Aspose.Email para .NET
description: Representa una carpeta IMAP.
type: docs
weight: 16300
url: /es/net/aspose.email.clients.imap/imapfolderinfo/
---
## ImapFolderInfo class

Representa una carpeta IMAP.

```csharp
public sealed class ImapFolderInfo
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [FolderType](../../aspose.email.clients.imap/imapfolderinfo/foldertype) { get; } | Obtiene información sobre el propósito de la carpeta en caso de que se use como carpeta especial. Esta opción es accesible solo en caso de que el servidor admita LISTA IMAP: buzones de correo de uso especial (rfc6154) Ver más: http://tools.ietf.org /html/rfc6154 |
| [HasChildren](../../aspose.email.clients.imap/imapfolderinfo/haschildren) { get; } | Obtiene el valor que indica si la carpeta contiene subcarpetas. Esta opción solo es accesible en caso de que el servidor admita las extensiones de comando IMAP4 LIST (rfc5258) Ver más: http://tools.ietf.org/html/rfc5258 Si el valor es`verdadero` , indica que la carpeta tiene subcarpetas secundarias a las que puede acceder el usuario autenticado actualmente; de lo contrario, false. |
| [HighestModSequence](../../aspose.email.clients.imap/imapfolderinfo/highestmodsequence) { get; } | Obtiene el valor de todos los mensajes en el buzón. Ver más: https://tools.ietf.org/html/rfc7162 |
| [Marked](../../aspose.email.clients.imap/imapfolderinfo/marked) { get; } | Obtiene un valor que indica si está marcada esta carpeta. |
| [Name](../../aspose.email.clients.imap/imapfolderinfo/name) { get; } | Obtiene el nombre de la carpeta. |
| [NewMessageCount](../../aspose.email.clients.imap/imapfolderinfo/newmessagecount) { get; } | Obtiene el número de los nuevos mensajes. |
| [NoInferiors](../../aspose.email.clients.imap/imapfolderinfo/noinferiors) { get; } | Obtiene un valor que indica si esta carpeta puede tener niveles secundarios. Si es`Verdadero` , entonces no existen niveles secundarios ahora y ninguno se puede crear en el futuro |
| [NoModSeq](../../aspose.email.clients.imap/imapfolderinfo/nomodseq) { get; } | Obtiene el valor que indica si el buzón admite secuencias de modificación. Esta propiedad solo funciona si el servidor admite la extensión CONDSTORE. Lea más https://tools.ietf.org/html/rfc4551#section-3.1.2 |
| [NonExistent](../../aspose.email.clients.imap/imapfolderinfo/nonexistent) { get; } | Obtiene el valor que indica si el nombre de una carpeta se refiere a una carpeta existente. Ver más: http://tools.ietf.org/html/rfc5258 |
| [ReadOnly](../../aspose.email.clients.imap/imapfolderinfo/readonly) { get; } | Obtiene un valor que indica si la carpeta es de solo lectura. |
| [RecentMessageCount](../../aspose.email.clients.imap/imapfolderinfo/recentmessagecount) { get; } | Obtiene el número de mensajes que llegaron recientemente. |
| [Remote](../../aspose.email.clients.imap/imapfolderinfo/remote) { get; } | Obtiene el valor que indica que una carpeta es un buzón de correo remoto. Esta opción solo es accesible en caso de que el servidor admita las extensiones de comando IMAP4 LIST (rfc5258) Ver más: http://tools.ietf.org/html/rfc5258 |
| [Selectable](../../aspose.email.clients.imap/imapfolderinfo/selectable) { get; } | Obtiene un valor que indica si es posible seleccionar esta carpeta. |
| [Subscribed](../../aspose.email.clients.imap/imapfolderinfo/subscribed) { get; } | Obtiene el valor que indica que un nombre de carpeta está suscrito. Ver más: http://tools.ietf.org/html/rfc5258 |
| [TotalMessageCount](../../aspose.email.clients.imap/imapfolderinfo/totalmessagecount) { get; } | Obtiene el número de mensajes en la carpeta. |
| [UIDNext](../../aspose.email.clients.imap/imapfolderinfo/uidnext) { get; } | Obtiene el ID de validez del buzón. |
| [UidNotSticky](../../aspose.email.clients.imap/imapfolderinfo/uidnotsticky) { get; } | Obtiene el valor que indica si el almacén de correo no admite UID persistentes Esta propiedad solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315 |
| [ValidityId](../../aspose.email.clients.imap/imapfolderinfo/validityid) { get; } | Obtiene el ID de validez del buzón. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [ToString](../../aspose.email.clients.imap/imapfolderinfo/tostring)() | Devuelve una cadena que representa el objeto actual. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [InBox](../../aspose.email.clients.imap/imapfolderinfo/inbox) | Obtiene el nombre de la bandeja de entrada. |

### Ver también

* espacio de nombres [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->