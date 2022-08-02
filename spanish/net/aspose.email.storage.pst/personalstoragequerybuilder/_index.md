---
title: PersonalStorageQueryBuilder
second_title: Referencia de la API de Aspose.Email para .NET
description: Representa el generador de expresión de búsqueda que usa pst.
type: docs
weight: 20310
url: /es/net/aspose.email.storage.pst/personalstoragequerybuilder/
---
## PersonalStorageQueryBuilder class

Representa el generador de expresión de búsqueda que usa pst.

```csharp
public sealed class PersonalStorageQueryBuilder : MailQueryBuilder
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PersonalStorageQueryBuilder](personalstoragequerybuilder)() | Inicializa una nueva instancia del[`PersonalStorageQueryBuilder`](../personalstoragequerybuilder) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Bcc](../../aspose.email.tools.search/mailquerybuilder/bcc) { get; } | Obtiene el campo que permite buscar mensajes que contengan la cadena especificada en el campo BCC de la estructura del sobre. |
| [Body](../../aspose.email.tools.search/mailquerybuilder/body) { get; } | Obtiene el campo que permite buscar mensajes que contengan la cadena especificada en el cuerpo del mensaje. |
| [Cc](../../aspose.email.tools.search/mailquerybuilder/cc) { get; } | Obtiene el campo que permite buscar mensajes que contengan la cadena especificada en el campo CC de la estructura del sobre. |
| [ContainerClass](../../aspose.email.storage.pst/personalstoragequerybuilder/containerclass) { get; } | Obtiene carpetas con una clase de mensaje especificada. |
| [ContentsCount](../../aspose.email.storage.pst/personalstoragequerybuilder/contentscount) { get; } | Carpetas de búsqueda con un recuento de contenido especificado. |
| [DefaultEncoding](../../aspose.email.tools.search/mailquerybuilder/defaultencoding) { get; } | Obtiene la codificación predeterminada (juego de caracteres) para el generador de consultas |
| [FolderName](../../aspose.email.storage.pst/personalstoragequerybuilder/foldername) { get; } | Carpetas de búsqueda con un nombre para mostrar especificado. |
| [From](../../aspose.email.tools.search/mailquerybuilder/from) { get; } | Obtiene el campo que permite buscar mensajes que contengan la cadena especificada en el campo FROM de la estructura del sobre. |
| [Importance](../../aspose.email.storage.pst/personalstoragequerybuilder/importance) { get; } | Buscar mensajes con una importancia especificada. |
| [InternalDate](../../aspose.email.tools.search/mailquerybuilder/internaldate) { get; } | Obtiene el campo que permite buscar mensajes por fecha interna. |
| [MessageClass](../../aspose.email.storage.pst/personalstoragequerybuilder/messageclass) { get; } | Obtiene mensajes con una clase de mensaje especificada. |
| [MessageId](../../aspose.email.storage.pst/personalstoragequerybuilder/messageid) { get; } | Obtiene el campo que permite encontrar mensajes que contienen la cadena especificada en el campo MessageId de la estructura del sobre. |
| [MessageSize](../../aspose.email.storage.pst/personalstoragequerybuilder/messagesize) { get; } | Buscar mensajes con un tamaño especificado. |
| [OnlyFoldersCreatedByUser](../../aspose.email.storage.pst/personalstoragequerybuilder/onlyfolderscreatedbyuser) { get; } | Obtiene las carpetas creadas por el usuario, es decir, excluye todas las carpetas estándar de IPM. |
| [SentDate](../../aspose.email.tools.search/mailquerybuilder/sentdate) { get; } | Obtiene el campo que permite buscar mensajes por fecha de envío. |
| [Subject](../../aspose.email.tools.search/mailquerybuilder/subject) { get; } | Obtiene el campo que permite buscar mensajes que contengan la cadena especificada en el campo SUBJECT de la estructura del sobre. |
| [Text](../../aspose.email.tools.search/mailquerybuilder/text) { get; } | Obtiene el campo que permite encontrar los mensajes que contienen la cadena especificada en los encabezados (asunto, de, para, cc) y cuerpo del mensaje. |
| [To](../../aspose.email.tools.search/mailquerybuilder/to) { get; } | Obtiene el campo que permite encontrar mensajes que contienen la cadena especificada en el campo TO de la estructura del sobre. |
| [UnreadContentsCount](../../aspose.email.storage.pst/personalstoragequerybuilder/unreadcontentscount) { get; } | Carpetas de búsqueda con un recuento de contenido no leído especificado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FindConversationThread](../../aspose.email.storage.pst/personalstoragequerybuilder/findconversationthread)(MessageInfo) | Encuentra el hilo de conversación. |
| [GetQuery](../../aspose.email.tools.search/mailquerybuilder/getquery)() | Obtiene la consulta. |
| [HasFlags](../../aspose.email.storage.pst/personalstoragequerybuilder/hasflags)(MapiMessageFlags) | Buscar mensajes con las banderas especificadas. |
| [HasNoFlags](../../aspose.email.storage.pst/personalstoragequerybuilder/hasnoflags)(MapiMessageFlags) | Buscar mensajes con banderas no especificadas. |
| [HasNoSubfolders](../../aspose.email.storage.pst/personalstoragequerybuilder/hasnosubfolders)() | Carpetas de búsqueda que no contienen subcarpetas. |
| [HasSubfolders](../../aspose.email.storage.pst/personalstoragequerybuilder/hassubfolders)() | Carpetas de búsqueda que contienen subcarpetas. |
| [Or](../../aspose.email.tools.search/mailquerybuilder/or)(MailQuery, MailQuery) | Buscar mensajes que coincidan con cualquiera de las claves de búsqueda. Proporciona disyunción entre dos expresiones (OR). |

### Ver también

* class [MailQueryBuilder](../../aspose.email.tools.search/mailquerybuilder)
* espacio de nombres [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
