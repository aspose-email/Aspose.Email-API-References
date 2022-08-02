---
title: AutodiscoverService
second_title: Referencia de la API de Aspose.Email para .NET
description: Representa un enlace al servicio de detección automática de Exchange.
type: docs
weight: 3090
url: /es/net/aspose.email.clients.exchange/autodiscoverservice/
---
## AutodiscoverService class

Representa un enlace al servicio de detección automática de Exchange.

```csharp
public sealed class AutodiscoverService : AutodiscoverServiceBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [AutodiscoverService](autodiscoverservice#constructor)() | Inicializa una nueva instancia del[`AutodiscoverService`](../autodiscoverservice) clase. |
| [AutodiscoverService](autodiscoverservice#constructor_1)(ExchangeVersion) | Inicializa una nueva instancia del[`AutodiscoverService`](../autodiscoverservice) clase. |
| [AutodiscoverService](autodiscoverservice#constructor_2)(string) | Inicializa una nueva instancia del[`AutodiscoverService`](../autodiscoverservice) clase. |
| [AutodiscoverService](autodiscoverservice#constructor_4)(Uri) | Inicializa una nueva instancia del[`AutodiscoverService`](../autodiscoverservice) clase. |
| [AutodiscoverService](autodiscoverservice#constructor_3)(string, ExchangeVersion) | Inicializa una nueva instancia del[`AutodiscoverService`](../autodiscoverservice) clase. |
| [AutodiscoverService](autodiscoverservice#constructor_5)(Uri, ExchangeVersion) | Inicializa una nueva instancia del[`AutodiscoverService`](../autodiscoverservice) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AcceptGzipEncoding](../../aspose.email.clients.exchange/autodiscoverservicebase/acceptgzipencoding) { get; set; } | Obtiene o establece un valor que indica si se debe aceptar la codificación de compresión GZip. |
| [ClientRequestId](../../aspose.email.clients.exchange/autodiscoverservicebase/clientrequestid) { get; set; } | Obtiene o establece el ID de solicitud para la solicitud. |
| [ConnectionGroupName](../../aspose.email.clients.exchange/autodiscoverservicebase/connectiongroupname) { get; set; } | Obtiene o establece el nombre del grupo de conexión para la solicitud. |
| [CookieContainer](../../aspose.email.clients.exchange/autodiscoverservicebase/cookiecontainer) { get; set; } | Obtiene o establece el contenedor de cookies. |
| [Credentials](../../aspose.email.clients.exchange/autodiscoverservicebase/credentials) { get; set; } | Obtiene o establece las credenciales utilizadas para autenticarse con los servicios web de Exchange. Al configurar Credentials property automáticamente se establece UseDefaultCredentials en false. |
| [Domain](../../aspose.email.clients.exchange/autodiscoverservice/domain) { get; set; } | Obtiene o establece el dominio al que está vinculado este servicio. Cuando se establece esta propiedad, el nombre del dominio se utiliza para determinar automáticamente la URL del servicio de detección automática. |
| [EnableScpLookup](../../aspose.email.clients.exchange/autodiscoverservice/enablescplookup) { get; set; } | Obtiene o establece un valor que indica si AutodiscoverService debe realizar una búsqueda de registros SCP (ServiceConnectionPoint) al determinar la URL del servicio de detección automática. |
| [HttpHeaders](../../aspose.email.clients.exchange/autodiscoverservicebase/httpheaders) { get; } | Obtiene una colección de encabezados HTTP que se enviarán con cada solicitud a EWS. |
| [HttpResponseHeaders](../../aspose.email.clients.exchange/autodiscoverservicebase/httpresponseheaders) { get; } | Obtiene una colección de encabezados HTTP de la última respuesta. |
| [IsExternal](../../aspose.email.clients.exchange/autodiscoverservice/isexternal) { get; } | Obtiene un valor que indica si el servicio de detección automática al que apunta la URL es interno (dentro de la red corporativa) o externo (fuera de la red corporativa). |
| [KeepAlive](../../aspose.email.clients.exchange/autodiscoverservicebase/keepalive) { get; set; } | Obtiene o establece si la solicitud al recurso de Internet debe contener un encabezado HTTP de conexión con el valor Keep-alive |
| [LogFileName](../../aspose.email.clients.exchange/autodiscoverservicebase/logfilename) { get; set; } | Obtiene o establece el nombre del archivo de registro |
| [PreAuthenticate](../../aspose.email.clients.exchange/autodiscoverservicebase/preauthenticate) { get; set; } | Obtiene o establece un valor que indica si se debe realizar la autenticación previa HTTP. |
| [RedirectionUrlValidationCallback](../../aspose.email.clients.exchange/autodiscoverservice/redirectionurlvalidationcallback) { get; set; } | Obtiene o establece la devolución de llamada de validación de URL de redirección. |
| [RequestedServerVersion](../../aspose.email.clients.exchange/autodiscoverservicebase/requestedserverversion) { get; } | Obtiene la versión del servidor solicitada. |
| [ReturnClientRequestId](../../aspose.email.clients.exchange/autodiscoverservicebase/returnclientrequestid) { get; set; } | Obtiene o establece un indicador para indicar si el cliente requiere que el lado del servidor devuelva la solicitud id. |
| [SendClientLatencies](../../aspose.email.clients.exchange/autodiscoverservicebase/sendclientlatencies) { get; set; } | Obtiene o establece un valor que indica si la información de latencia del cliente se transfiere al servidor. |
| [ServerInfo](../../aspose.email.clients.exchange/autodiscoverservicebase/serverinfo) { get; } | Obtiene información asociada al servidor que procesó la última solicitud. Será nulo si no se ha procesado ninguna solicitud. |
| [Timeout](../../aspose.email.clients.exchange/autodiscoverservicebase/timeout) { get; set; } | Obtiene o establece el tiempo de espera utilizado al enviar solicitudes HTTP y al recibir respuestas HTTP, en milisegundos. El valor predeterminado es 100000. |
| [Url](../../aspose.email.clients.exchange/autodiscoverservice/url) { get; set; } | Obtiene o establece la URL a la que está vinculado este servicio. |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/autodiscoverservicebase/usedateinlogfilename) { get; set; } | Obtiene o establece el valor que indica si se debe usar la fecha en el nombre del archivo de registro. |
| [UseDefaultCredentials](../../aspose.email.clients.exchange/autodiscoverservicebase/usedefaultcredentials) { get; set; } | Obtiene o establece un valor que indica si las credenciales del usuario actualmente conectado a Windows deben usarse para autenticarse con los servicios web de Exchange. Establecer UseDefaultCredentials en verdadero establece automáticamente la propiedad Credentials en null. |
| [UserAgent](../../aspose.email.clients.exchange/autodiscoverservicebase/useragent) { get; set; } | Obtiene o establece el agente de usuario. |
| [WebProxy](../../aspose.email.clients.exchange/autodiscoverservicebase/webproxy) { get; set; } | Obtiene o establece el proxy web que debe usarse al enviar solicitudes a EWS. Establezca esta propiedad en nulo para usar el proxy web predeterminado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetUserSettings](../../aspose.email.clients.exchange/autodiscoverservice/getusersettings)(string, params UserSettingName[]) | Recupera la configuración especificada para una sola dirección SMTP. |
| [GetUsersSettings](../../aspose.email.clients.exchange/autodiscoverservice/getuserssettings)(IEnumerable&lt;string&gt;, params UserSettingName[]) | Recupera la configuración especificada para un conjunto de usuarios. |

### Ver también

* class [AutodiscoverServiceBase](../autodiscoverservicebase)
* espacio de nombres [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
