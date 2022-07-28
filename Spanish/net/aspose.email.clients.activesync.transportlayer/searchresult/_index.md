---
title: SearchResult
second_title: Referencia de la API de Aspose.Email para .NET
description: Contenedor para un elemento de buzón coincidente individual. Cuando el almacén que se busca es el buzón - Hay un elemento de resultado para cada coincidencia que se encuentra en el buzón. Si no se encuentran coincidencias un elemento de resultado vacío está presente en el elemento contenedor de la tienda del XML de respuesta.  dentro del elemento de resultado el elemento de propiedades contiene una lista de propiedades solicitadas para el elemento del buzón. Cuando la tienda que está lo que se busca es la biblioteca de documentos  el primer resultado que se devuelve en la respuesta de búsqueda son los metadatos de la carpeta raíz o el elemento al que apunta el valor LinkId. El cliente puede elegir ignorar esta entrada si no la requiere. - Si el valor del elemento documentlibraryLinkId en la solicitud apunta a una carpeta las propiedades de metadatos de la carpeta se devuelven como el primer elemento y el contenido de la carpeta se devuelven como resultados posteriores. El rango se aplica a estos resultados sin diferencia por ejemplo el índice 0 siempre sería para el elemento raíz al que apunta el enlace.  si el valor del elemento documentlibraryLinkId en la solicitud apunta a un elemento solo se devuelve un resultado los metadatos del elemento. - Dentro del elemento Resultado el elemento Propiedades contiene una lista de propiedades solicitadas para el elemento del buzón.
type: docs
weight: 2010
url: /es/net/aspose.email.clients.activesync.transportlayer/searchresult/
---
## SearchResult class

Contenedor para un elemento de buzón coincidente individual. Cuando el almacén que se busca es el buzón: - Hay un elemento de resultado para cada coincidencia que se encuentra en el buzón. Si no se encuentran coincidencias, un elemento de resultado vacío está presente en el elemento contenedor de la tienda del XML de respuesta. : dentro del elemento de resultado, el elemento de propiedades contiene una lista de propiedades solicitadas para el elemento del buzón. Cuando la tienda que está lo que se busca es la biblioteca de documentos: : el primer resultado que se devuelve en la respuesta de búsqueda son los metadatos de la carpeta raíz o el elemento al que apunta el valor LinkId. El cliente puede elegir ignorar esta entrada si no la requiere. - Si el valor del elemento documentlibrary:LinkId en la solicitud apunta a una carpeta, las propiedades de metadatos de la carpeta se devuelven como el primer elemento y el contenido de la carpeta se devuelven como resultados posteriores. El rango se aplica a estos resultados sin diferencia; por ejemplo, el índice 0 siempre sería para el elemento raíz al que apunta el enlace. : si el valor del elemento documentlibrary:LinkId en la solicitud apunta a un elemento, solo se devuelve un resultado: los metadatos del elemento. - Dentro del elemento Resultado, el elemento Propiedades contiene una lista de propiedades solicitadas para el elemento del buzón.

```csharp
public class SearchResult
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SearchResult](searchresult)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Class](../../aspose.email.clients.activesync.transportlayer/searchresult/class) { get; set; } | Identifica la clase del artículo. |
| [CollectionId](../../aspose.email.clients.activesync.transportlayer/searchresult/collectionid) { get; } | Especifica las carpetas en las que se encontró el elemento. |
| [LongId](../../aspose.email.clients.activesync.transportlayer/searchresult/longid) { get; set; } | Especifica un identificador único que asigna el servidor a cada conjunto de resultados que se devuelve. El valor de LongId se puede usar como el ID largo especificado en la solicitud de comando ItemOperations, la solicitud de comando SmartReply, la solicitud de comando SmartForward o la solicitud del comando MeetingResponse para hacer referencia al conjunto de resultados. El cliente DEBE almacenar el valor de LongId como una cadena opaca de hasta 256 caracteres. |
| [Properties](../../aspose.email.clients.activesync.transportlayer/searchresult/properties) { get; set; } | Las propiedades de respuesta del comando de búsqueda son un contenedor de propiedades que se aplican a una entrada individual que coincide con la cadena de búsqueda del elemento de consulta. Por ejemplo, el elemento Propiedades contiene un elemento para cada propiedad GAL no vacía con valor de texto que se adjunta a la entrada GAL coincidente. Solo se devuelven aquellas propiedades que están adjuntas a la entrada GAL específica; por lo tanto, se pueden devolver diferentes conjuntos de propiedades en el XML de respuesta para diferentes entradas de GAL coincidentes. Cada elemento en el contenedor de propiedades tiene como ámbito el espacio de nombres apropiado que se especifica en el elemento de búsqueda de nivel superior. |

### Ver también

* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
