---
title: IBaseActiveSyncTLClient
second_title: Referencia de la API de Aspose.Email para .NET
description: Interfaz de cliente Base ActiveSync
type: docs
weight: 1320
url: /es/net/aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/
---
## IBaseActiveSyncTLClient interface

Interfaz de cliente Base ActiveSync

```csharp
public interface IBaseActiveSyncTLClient : IDisposable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AuthenticationType](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/authenticationtype) { get; set; } | Obtiene o establece el tipo de autenticación que utiliza el cliente de ActiveSync. |
| [AutodiscoverUri](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/autodiscoveruri) { get; set; } | Obtiene la detección automática uri |
| [Credentials](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/credentials) { get; } | Credenciales de usuario para Exchange server |
| [DeviceID](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/deviceid) { get; set; } | Un GUID que identifica el dispositivo. El ID del dispositivo se especifica mediante la parte de la regla ABNF de especificación de ID de dispositivo del valor de consulta de texto sin formato. El valor, representado por la regla ABNF device-id, es una cadena que especifica el dispositivo. Cada dispositivo DEBE tener una cadena de ID de dispositivo única. Cada solicitud del dispositivo DEBE incluir la misma cadena de ID de dispositivo. |
| [DeviceType](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/devicetype) { get; set; } | El tipo de dispositivo se especifica mediante la parte de la regla ABNF de especificación de tipo de dispositivo del valor de consulta de texto sin formato. El valor, representado por la regla ABNF de tipo de dispositivo, es cualquier cadena que especifica un tipo de dispositivo. "SP" especifica un SmartPhone y "PPC" especifica un PocketPC. Otros dispositivos cliente envían cadenas únicas para su tipo de dispositivo específico. Cada solicitud de un dispositivo cliente DEBE incluir la misma cadena de tipo de dispositivo. |
| [PolicyState](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/policystate) { get; set; } | Un entero sin signo que indica el estado de la configuración de la política en el dispositivo cliente, como se especifica en [MS-ASPROV] sección 2.2.2.41. |
| [Proxy](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/proxy) { get; set; } | Obtiene o establece el proxy. |
| [SupportedServerCommands](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/supportedservercommands) { get; } | Obtiene las versiones de los comandos de ActiveSync que son compatibles con el servidor |
| [SupportedServerProtocols](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/supportedserverprotocols) { get; } | Obtiene las versiones de los protocolos ActiveSync que son compatibles con el servidor |
| [Timeout](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/timeout) { get; set; } | Obtiene o establece el número de milisegundos de espera antes de que se agote el tiempo de espera de la operación. El valor predeterminado es 100 000 milisegundos (100 segundos). |
| [Uri](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/uri) { get; } | Obtiene el servidor uri |
| [UserAgent](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/useragent) { get; set; } | El campo de encabezado de solicitud de agente de usuario contiene información sobre el agente de usuario que origina la solicitud. Esto es para fines estadísticos, el seguimiento de violaciones de protocolo y el reconocimiento automatizado de agentes de usuario con el fin de adaptar las respuestas para evitar limitaciones particulares de agentes de usuario. Los agentes de usuario DEBERÍAN incluir este campo con las solicitudes. El campo puede contener varios tokens de productos (sección 3.8) y comentarios que identifican al agente y cualquier subproducto que forme una parte significativa del agente de usuario. Por convención, los tokens de productos se enumeran en orden de importancia para identificar la aplicación. Ejemplo: User-Agent: CERN-LineMode/2.15 libwww/2.17b3 |
| [Version](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/version) { get; } | Obtiene la versión del protocolo que se utiliza en el cliente ActiveSync. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Autodiscover](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/autodiscover)(string) | El comando Detección automática facilita el descubrimiento de la información de configuración de la cuenta principal mediante el uso de la dirección del Protocolo simple de transferencia de correo (SMTP) del usuario como entrada principal. |

### Ver también

* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
