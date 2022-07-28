---
title: AirSync
second_title: Referencia de la API de Aspose.Email para .NET
description: Espacio de nombres AirSync del protocolo ActiveSync
type: docs
weight: 960
url: /es/net/aspose.email.clients.activesync.transportlayer/airsync/
---
## AirSync enumeration

Espacio de nombres AirSync del protocolo ActiveSync

```csharp
public enum AirSync
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Sync | `5` | El elemento Sync es un elemento requerido en las solicitudes y respuestas del comando Sync que identifica el cuerpo del HTTP POST que contiene un comando Sync (sección 2.2.2.19). Es el elemento de nivel superior en el flujo XML. |
| Responses | `6` | Contiene respuestas a operaciones procesadas por el servidor. |
| Add | `7` | Crea un nuevo objeto en una colección en el cliente o en el servidor. |
| Change | `8` | Modifica propiedades de un objeto existente en el dispositivo cliente o en el servidor. |
| Delete | `9` | Elimina un objeto en el dispositivo cliente o el servidor. El objeto se identifica por su elemento ServerId. |
| Fetch | `10` | Se usa para solicitar los datos de la aplicación de un elemento que se truncó en una respuesta de sincronización del servidor. |
| SyncKey | `11` | Contiene un valor que utiliza el servidor para marcar el estado de sincronización de una colección. |
| ClientId | `12` | Contiene un identificador único (generalmente un número entero) que genera el cliente para identificar temporalmente un nuevo objeto que se crea mediante el elemento Agregar. |
| ServerId | `13` | Representa un identificador único que es asignado por el servidor a cada objeto que se puede sincronizar. |
| Status | `14` | Indica el motivo de la falla de una solicitud de comando. |
| Collection | `15` | Contiene comandos y opciones que se aplican a una colección particular. |
| Class | `16` | Identifica la clase del elemento que se agrega a la colección. |
| CollectionId | `18` | Especifica el ID del servidor de la carpeta que se sincronizará. |
| GetChanges | `19` | Solicita que el servidor incluya en su respuesta cualquier cambio pendiente en la colección que especifica el elemento ServerId (sección 2.2.3.151.6). |
| MoreAvailable | `20` | Indica que hay más cambios de los que se solicitan en el elemento WindowSize (sección 2.2.3.183). |
| WindowSize | `21` | Especifica un número máximo de elementos modificados en una colección o una solicitud que DEBERÍA incluirse en la respuesta de sincronización. |
| Commands | `22` | Contiene operaciones que se aplican a una colección. |
| Options | `23` | Contiene elementos que controlan ciertos aspectos de cómo se realiza la sincronización. |
| FilterType | `24` | Especifica una ventana de tiempo opcional para los objetos que se envían desde el servidor al cliente. Se aplica a las colecciones de correo electrónico y calendario. |
| Conflict | `27` | Especifica cómo resolver el conflicto que ocurre cuando se cambia un objeto tanto en el cliente como en el servidor. |
| Collections | `28` | Sirve como contenedor para el elemento Colección. |
| ApplicationData | `29` | Contiene datos para un objeto en particular, como un contacto, mensaje de correo electrónico, cita de calendario o elemento de tarea. Se puede usar para cambiar elementos, agregar elementos o recuperar elementos en el dispositivo cliente o servidor. |
| DeletesAsMoves | `30` | Indica que cualquier elemento eliminado DEBE moverse a la carpeta Elementos eliminados. |
| Supported | `32` | Especifica qué elementos de contacto y calendario en una solicitud de sincronización son administrados por el cliente. |
| SoftDelete | `33` | Elimina un objeto del cliente cuando queda fuera de los resultados de FilterType (sección 2.2.3.64.2) o ya no se incluye como parte de las instrucciones de SyncOptions (sección 2.2.3.115.5). |
| MIMESupport | `34` | Habilita la compatibilidad con MIME para elementos de correo electrónico que se envían desde el servidor al cliente. |
| MIMETruncation | `35` | Especifica si los datos MIME del elemento de correo electrónico DEBERÍAN truncarse cuando se envía desde el servidor al cliente. |
| Wait | `36` | Especifica la cantidad de minutos que el servidor DEBERÍA retrasar una respuesta si no se agregan nuevos elementos a las carpetas incluidas, como se especifica en la sección 3.1.5.4. |
| Limit | `37` | Especifica el número máximo de recopilaciones que se pueden sincronizar o el valor máximo/mínimo permitido para el intervalo de espera (sección 2.2.3.182) o el intervalo HeartbeatInterval (sección 2.2.3.79.2). |
| Partial | `38` | Indica al servidor que el cliente envió una lista parcial de colecciones, en cuyo caso el servidor obtiene el resto de las colecciones de su caché. |
| ConversationMode | `39` | Especifica si incluir elementos que se incluyen dentro de la modalidad de conversación dentro de los resultados de la respuesta de sincronización. |
| MaxItems | `40` | Especifica el número máximo de destinatarios (es decir, los N principales destinatarios utilizados con más frecuencia) para mantener sincronizados desde la caché de información de destinatarios. |
| HeartbeatInterval | `41` | Especifica la cantidad de segundos que el servidor DEBERÍA retrasar una respuesta si no se agregan nuevos elementos a las carpetas incluidas, como se especifica en la sección 3.1.5.4. |

### Ver también

* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
