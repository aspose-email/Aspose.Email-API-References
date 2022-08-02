---
title: SyncCollectionRequest
second_title: Referencia de la API de Aspose.Email para .NET
description: La clase contiene comandos y opciones que se aplican a una colección en particular.
type: docs
weight: 2190
url: /es/net/aspose.email.clients.activesync.transportlayer/synccollectionrequest/
---
## SyncCollectionRequest class

La clase contiene comandos y opciones que se aplican a una colección en particular.

```csharp
public class SyncCollectionRequest
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SyncCollectionRequest](synccollectionrequest)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CollectionId](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/collectionid) { get; set; } | Especifica el ID del servidor de la carpeta que se sincronizará. |
| [Commands](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/commands) { get; set; } | Contiene operaciones que se aplican a una colección. Las operaciones disponibles son Add, Delete, Change, Fetch y SoftDelete. |
| [ConversationMode](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/conversationmode) { get; set; } | Especifica si incluir elementos que se incluyen dentro de la modalidad de conversación dentro de los resultados de la respuesta de sincronización. Establecer el valor del elemento ConversationMode en TRUE da como resultado la recuperación de todos los correos electrónicos que coinciden con las conversaciones recibidas dentro del filtro de fecha especificado. Sin embargo, aunque el cuerpo de los correos electrónicos fuera de ese filtro basado en el tiempo no se recuperará, las vistas previas de texto se recuperarán si se solicitaron las vistas previas. Establecer el valor del elemento ConversationMode en FALSO en una solicitud de sincronización da como resultado la sincronización de elementos que cumplen los criterios del valor del elemento FilterType (sección 2.2.3.64). Establecer el valor del elemento ConversationMode en TRUE expande el conjunto de resultados para incluir también cualquier elemento con valores email2:ConversationId ([MS-ASEMAIL] sección 2.2.2.14) idénticos a los del conjunto de resultados de FilterType. El valor del elemento ConversationMode no tiene impacto en los elementos fuera de la colección especificada por el elemento CollectionId (sección 2.2.3.30.5); el conjunto de resultados siempre se limita a los elementos de la colección especificada. El valor del elemento ConversationMode solo limita o amplía los resultados determinados por el valor del elemento FilterType. |
| [DeletesAsMoves](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/deletesasmoves) { get; set; } | Solicitudes que indican que los elementos eliminados DEBERÍAN moverse a la carpeta Elementos eliminados. Si el elemento DeletesAsMoves se establece en falso, la eliminación es permanente. Si el cliente desea eliminar elementos de forma permanente, la solicitud DEBE incluir el elemento DeletesAsMoves con un valor FALSO. Un valor de VERDADERO, que es el valor predeterminado, indica que los elementos eliminados se mueven a la carpeta Elementos eliminados. |
| [GetChanges](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/getchanges) { get; set; } | Solicita que el servidor incluya en su respuesta cualquier cambio pendiente en la colección que especifica el elemento ServerId (sección 2.2.3.151.6). Si ha habido cambios desde la última sincronización, la respuesta del servidor incluye un elemento Comandos (sección 2.2.3.32) que contiene adiciones, eliminaciones y cambios. Si el cliente no desea que se devuelvan los cambios del servidor, la solicitud DEBE incluir el elemento GetChanges con un valor de FALSO. Un valor de TRUE indica que el cliente desea que se devuelvan los cambios del servidor. Se asume un valor de TRUE cuando el elemento GetChanges está vacío. Cuando el elemento GetChanges no está presente en la solicitud, el comportamiento depende del valor del elemento SyncKey, como se especifica en la sección 2.2.3.166.4. Si el elemento SyncKey tiene un valor de 0, la solicitud se maneja como si el elemento GetChanges estuviera establecido en FALSE. Si el elemento SyncKey tiene un valor distinto de cero, la solicitud se maneja como si el elemento GetChanges estuviera establecido a VERDADERO. |
| [Options](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/options) { get; } | Especifica opciones que controlan ciertos aspectos de cómo se realiza la sincronización. Número permitido 0...2. Las opciones de sincronización permiten al cliente especificar la configuración de contenido y truncamiento. Estos ajustes están encapsulados dentro de un elemento secundario airsyncbase:BodyPreference, como se especifica en [MS-ASAIRS] sección 2.2.2.7. Debido a que las opciones de sincronización se especifican en una colección, el cliente puede especificar un valor único del elemento airsyncbase:BodyPreference para cada colección que se sincroniza. Para obtener más detalles sobre el elemento airsyncbase:BodyPreference, consulte [MS-ASAIRS] sección 2.2. 2.7. El servidor conserva el bloque de opciones en todas las solicitudes, utilizando un concepto denominado "opciones adhesivas". Si el bloque de opciones no está incluido en una solicitud, se utiliza el bloque de opciones anterior. Cada vez que el cliente especifica nuevas opciones al incluir un bloque de opciones en la solicitud, el servidor DEBE reemplazar el bloque de opciones original con el nuevo bloque de opciones. Si se incluyen dos elementos de opciones en una sola solicitud de comando de sincronización, uno de los elementos de opciones DEBE especifica las opciones de sincronización para la clase de SMS, mientras que el otro elemento Opciones especifica las opciones para la clase predeterminada de la carpeta dada. |
| [Supported](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/supported) { get; } | Los elementos de la clase Contacto y la clase Calendario que no son fantasmas se pueden incluir como elementos secundarios del elemento Compatible. Para obtener detalles sobre el uso de propiedades fantasma, consulte la sección 2.2.3.154. |
| [SyncKey](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/synckey) { get; set; } | El servidor utiliza el valor SyncKey para marcar el estado de sincronización de una colección. Una clave de sincronización de valor 0 (cero) inicializa el estado de sincronización en el servidor y provoca una sincronización completa de la colección. |
| [WindowSize](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/windowsize) { get; set; } | Especifica un número máximo de elementos modificados en una colección o una solicitud que DEBERÍA incluirse en la respuesta de sincronización. Si no se define WindowSize, el servidor se comporta como si se enviara un elemento WindowSize con un valor de 100. El servidor interpreta el valor 0 (cero) y los valores superiores a 512 como 512. |

### Ver también

* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
