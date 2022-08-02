---
title: ActiveSyncTLClient
second_title: Referencia de la API de Aspose.Email para .NET
description: Clase básica para implementaciones de clientes ActiveSync
type: docs
weight: 950
url: /es/net/aspose.email.clients.activesync.transportlayer/activesynctlclient/
---
## ActiveSyncTLClient class

Clase básica para implementaciones de clientes ActiveSync

```csharp
public class ActiveSyncTLClient : IBaseActiveSyncTLClient
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [AuthenticationType](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/authenticationtype) { get; set; } | Obtiene o establece el tipo de autenticación que utiliza el cliente de ActiveSync. |
| virtual [AutodiscoverUri](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscoveruri) { get; set; } | Obtiene o establece el servicio de detección automática uri |
| virtual [Credentials](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/credentials) { get; } | Credenciales de usuario para Exchange server |
| virtual [DeviceID](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/deviceid) { get; set; } | Un GUID que identifica el dispositivo. El ID del dispositivo se especifica mediante la parte de la regla ABNF de especificación de ID de dispositivo del valor de consulta de texto sin formato. El valor, representado por la regla ABNF device-id, es una cadena que especifica el dispositivo. Cada dispositivo DEBE tener una cadena de ID de dispositivo única. Cada solicitud del dispositivo DEBE incluir la misma cadena de ID de dispositivo. |
| virtual [DeviceType](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/devicetype) { get; set; } | El tipo de dispositivo se especifica mediante la parte de la regla ABNF de especificación de tipo de dispositivo del valor de consulta de texto sin formato. El valor, representado por la regla ABNF de tipo de dispositivo, es cualquier cadena que especifica un tipo de dispositivo. "SP" especifica un SmartPhone y "PPC" especifica un PocketPC. Otros dispositivos cliente envían cadenas únicas para su tipo de dispositivo específico. Cada solicitud de un dispositivo cliente DEBE incluir la misma cadena de tipo de dispositivo. |
| virtual [PolicyState](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/policystate) { get; set; } | Un entero sin signo que indica el estado de la configuración de la política en el dispositivo cliente, como se especifica en [MS-ASPROV] sección 2.2.2.41. |
| virtual [Proxy](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/proxy) { get; set; } | Obtiene o establece el proxy. |
| virtual [SupportedServerCommands](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/supportedservercommands) { get; } | Obtiene las versiones de los comandos de ActiveSync que son compatibles |
| virtual [SupportedServerProtocols](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/supportedserverprotocols) { get; } | Obtiene las versiones de los protocolos ActiveSync que son compatibles |
| virtual [Timeout](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/timeout) { get; set; } | Obtiene o establece el número de milisegundos de espera antes de que se agote el tiempo de espera de la operación. El valor predeterminado es 100 000 milisegundos (100 segundos). |
| virtual [Uri](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/uri) { get; } | Obtiene la URL del servicio ActiveSync |
| virtual [UserAgent](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/useragent) { get; set; } | El campo de encabezado de solicitud de agente de usuario contiene información sobre el agente de usuario que origina la solicitud. Esto es para fines estadísticos, el seguimiento de violaciones de protocolo y el reconocimiento automatizado de agentes de usuario con el fin de adaptar las respuestas para evitar limitaciones particulares de agentes de usuario. Los agentes de usuario DEBERÍAN incluir este campo con las solicitudes. El campo puede contener varios tokens de productos (sección 3.8) y comentarios que identifican al agente y cualquier subproducto que forme una parte significativa del agente de usuario. Por convención, los tokens de productos se enumeran en orden de importancia para identificar la aplicación. Ejemplo: User-Agent: CERN-LineMode/2.15 libwww/2.17b3 |
| virtual [Version](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/version) { get; } | Obtiene la versión del protocolo que se utiliza en el cliente ActiveSync. |
| static [DefaultTimeout](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/defaulttimeout) { get; set; } | Obtiene o establece el valor de tiempo de espera predeterminado para las instancias de cliente de ActiveSync El valor predeterminado es 100 000 milisegundos (100 segundos). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [Autodiscover](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscover)(string) | El comando Detección automática facilita el descubrimiento de la información de configuración de la cuenta principal mediante el uso de la dirección del Protocolo simple de transferencia de correo (SMTP) del usuario como entrada principal. |
| [Dispose](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/dispose)() | Realiza tareas asociadas con liberar, liberar o restablecer recursos no administrados. |
| static [Autodiscover](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscover)(string, NetworkCredential, string) | El comando Detección automática facilita el descubrimiento de la información de configuración de la cuenta principal mediante el uso de la dirección del Protocolo simple de transferencia de correo (SMTP) del usuario como entrada principal. |
| static [GetInstance](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getinstance#getinstance)(string, NetworkCredential) | Obtiene una instancia del cliente ActiveSync La versión del protocolo ActiveSync se selecciona automáticamente según la respuesta del servidor. |
| static [GetInstance](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getinstance#getinstance_1)(string, NetworkCredential, ASProtocolVersions) | Obtiene una instancia del cliente ActiveSync |
| static [GetOptions](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getoptions)(string, NetworkCredential, out string[], out string[]) | El método estático GetOptions se usa para descubrir qué versiones de protocolo se admiten y qué comandos de protocolo se admiten en el servidor. El cliente usa el método estático GetOptions para determinar si el servidor admite las mismas versiones del protocolo que admite el cliente. |

### Ver también

* interface [IBaseActiveSyncTLClient](../ibaseactivesynctlclient)
* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
