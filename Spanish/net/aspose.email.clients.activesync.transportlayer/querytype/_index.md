---
title: QueryType
second_title: Referencia de la API de Aspose.Email para .NET
description: Especifica las palabras clave que se usarán para hacer coincidir las entradas en la tienda que se está buscando. El valor de Query se usa como un patrón de coincidencia de cadena de prefijo y devuelve entradas que coinciden con el comienzo de la cadena. Por ejemplo la búsqueda de John coincidiría con John Frum o Barry Johnson pero no con James Littlejohn. Todas las propiedades de texto no vacías en la GAL que se indexan mediante ANR se comparan con el elemento Query valor. Las comparaciones de búsqueda se realizan mediante coincidencias que no distinguen entre mayúsculas y minúsculas. Para una búsqueda en la biblioteca de documentos de Windows SharePoint Services este protocolo admite consultas de la siguiente forma LinkId  valor donde valor especifica la URL del elemento o carpeta y LinkId indica que el valor debe compararse con la propiedad de ID de enlace. Para la búsqueda de buzón la sintaxis de consulta es la siguiente - Las carpetas se pueden especificar de las siguientes maneras ID especificado Carpeta y subcarpetas especificadas Todas las carpetas de correo electrónico incluido Borrador Bandeja de entrada y subcarpetas Bandeja de salida y Elementos enviados  la consulta de palabra clave básica puede estar compuesta por lo siguiente El operador básico Y sección 2.2.3.10 Un filtro de fecha y hora especificado mediante GreaterThan sección 2.2.3.78 y LessThan elementos sección 2.2.3.87 Elementos de texto libre sección 2.2.3.73 que contienen palabras clave La consulta básica de palabras clave se ejecuta en todas las propiedades indexadas.
type: docs
weight: 1780
url: /es/net/aspose.email.clients.activesync.transportlayer/querytype/
---
## QueryType class

Especifica las palabras clave que se usarán para hacer coincidir las entradas en la tienda que se está buscando. El valor de Query se usa como un patrón de coincidencia de cadena de prefijo y devuelve entradas que coinciden con el comienzo de la cadena. Por ejemplo, la búsqueda de "John" coincidiría con "John Frum" o "Barry Johnson", pero no con "James Littlejohn". Todas las propiedades de texto no vacías en la GAL que se indexan mediante ANR se comparan con el elemento Query valor. Las comparaciones de búsqueda se realizan mediante coincidencias que no distinguen entre mayúsculas y minúsculas. Para una búsqueda en la biblioteca de documentos de Windows SharePoint Services, este protocolo admite consultas de la siguiente forma: LinkId == valor, donde valor especifica la URL del elemento o carpeta y LinkId indica que el valor debe compararse con la propiedad de ID de enlace. Para la búsqueda de buzón, la sintaxis de consulta es la siguiente: - Las carpetas se pueden especificar de las siguientes maneras: ID especificado Carpeta y subcarpetas especificadas Todas las carpetas de correo electrónico, incluido Borrador, Bandeja de entrada y subcarpetas, Bandeja de salida y Elementos enviados : la consulta de palabra clave básica puede estar compuesta por lo siguiente: El operador básico: Y (sección 2.2.3.10) Un filtro de fecha y hora especificado mediante GreaterThan (sección 2.2.3.78) y LessThan elementos (sección 2.2.3.87) Elementos de texto libre (sección 2.2.3.73) que contienen palabras clave La consulta básica de palabras clave se ejecuta en todas las propiedades indexadas.

```csharp
public class QueryType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [QueryType](querytype)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Class](../../aspose.email.clients.activesync.transportlayer/querytype/class) { get; } | Identifica la clase del elemento. Los valores válidos del elemento airsync:Class son: - Tasks - Email - Calendar - Contacts - Notes - SMS Las siguientes clases son compatibles con las búsquedas de buzones cuando la versión del protocolo es 12.1: Contactos, Tareas. Las clases SMS y Notes solo están disponibles si la versión del protocolo es 14.0 o 14.1. La solicitud de búsqueda puede incluir uno o más elementos de clase en la solicitud para limitar el tipo de datos incluidos en la respuesta de búsqueda. Si uno o más elementos de clase no se incluyen en la solicitud de búsqueda, el servidor devolverá todas las clases admitidas. Si la clase se incluye como elemento secundario de cualquier elemento que no sea el elemento Y, el servidor responde con un valor de estado de 8 (Búsqueda demasiado compleja). |
| [CollectionId](../../aspose.email.clients.activesync.transportlayer/querytype/collectionid) { get; } | Especifica la carpeta en la que buscar. Si DeepTraversal está presente, se aplica a todas las carpetas bajo cada CollectionId. Si CollectionId se incluye como elemento secundario de cualquier elemento que no sea Y, el servidor responde con un valor de Estado de 8 (SearchTooComplex). |
| [ConversationId](../../aspose.email.clients.activesync.transportlayer/querytype/conversationid) { get; set; } | Especifica la conversación que buscar. El valor es un GUID. ConversationId no se admite cuando la versión del protocolo es 12.1. Si ConversationId se incluye como elemento secundario de cualquier elemento que no sea And, el servidor responde con un valor de estado de 8 (SearchTooComplex). |
| [FreeText](../../aspose.email.clients.activesync.transportlayer/querytype/freetext) { get; set; } | Especifica un valor de cadena para buscar. Si la propiedad FreeText se establece de forma diferente a la propiedad And, el servidor responde con un valor de Estado de 8 (SearchTooComplex). |
| [GreaterThan](../../aspose.email.clients.activesync.transportlayer/querytype/greaterthan) { get; set; } | Especifica una propiedad y un valor que se comparan para las condiciones 'Mayor que' durante una búsqueda. |
| [LessThan](../../aspose.email.clients.activesync.transportlayer/querytype/lessthan) { get; set; } | Especifica una propiedad y un valor que se comparan para las condiciones 'Menor que' durante una búsqueda. |

### Ver también

* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
