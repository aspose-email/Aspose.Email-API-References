---
title: SmtpClient
second_title: Referencia de la API de Aspose.Email para .NET
description: Permite que las aplicaciones envíen mensajes utilizando el Protocolo simple de transferencia de correo SMTP.
type: docs
weight: 17030
url: /es/net/aspose.email.clients.smtp/smtpclient/
---
## SmtpClient class

Permite que las aplicaciones envíen mensajes utilizando el Protocolo simple de transferencia de correo (SMTP).

```csharp
public sealed class SmtpClient : EmailClient, IAsyncSmtpClient, IMailTransferAgent
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SmtpClient](smtpclient#constructor)() | Inicializa una nueva instancia del[`SmtpClient`](../smtpclient) clase. |
| [SmtpClient](smtpclient#constructor_1)(Configuration) | Inicializa una nueva instancia del[`SmtpClient`](../smtpclient) clase usando el archivo de configuración settings. |
| [SmtpClient](smtpclient#constructor_2)(string) | Inicializa una nueva instancia del[`SmtpClient`](../smtpclient) clase. |
| [SmtpClient](smtpclient#constructor_4)(string, int) | Inicializa una nueva instancia del[`SmtpClient`](../smtpclient) clase. |
| [SmtpClient](smtpclient#constructor_3)(string, SecurityOptions) | Inicializa una nueva instancia del[`SmtpClient`](../smtpclient) clase. |
| [SmtpClient](smtpclient#constructor_5)(string, int, SecurityOptions) | Inicializa una nueva instancia del[`SmtpClient`](../smtpclient) clase. |
| [SmtpClient](smtpclient#constructor_12)(string, string, ITokenProvider) | Inicializa una nueva instancia del[`SmtpClient`](../smtpclient) clase. |
| [SmtpClient](smtpclient#constructor_14)(string, string, string) | Inicializa una nueva instancia del[`SmtpClient`](../smtpclient) clase. |
| [SmtpClient](smtpclient#constructor_6)(string, int, string, ITokenProvider) | Inicializa una nueva instancia del[`SmtpClient`](../smtpclient) clase. |
| [SmtpClient](smtpclient#constructor_8)(string, int, string, string) | Inicializa una nueva instancia del[`SmtpClient`](../smtpclient) clase. |
| [SmtpClient](smtpclient#constructor_13)(string, string, ITokenProvider, SecurityOptions) | Inicializa una nueva instancia del[`SmtpClient`](../smtpclient) clase. |
| [SmtpClient](smtpclient#constructor_16)(string, string, string, bool) | Inicializa una nueva instancia del[`SmtpClient`](../smtpclient) clase. |
| [SmtpClient](smtpclient#constructor_15)(string, string, string, SecurityOptions) | Inicializa una nueva instancia del[`SmtpClient`](../smtpclient) clase. |
| [SmtpClient](smtpclient#constructor_7)(string, int, string, ITokenProvider, SecurityOptions) | Inicializa una nueva instancia del[`SmtpClient`](../smtpclient) clase. |
| [SmtpClient](smtpclient#constructor_10)(string, int, string, string, bool) | Inicializa una nueva instancia del[`SmtpClient`](../smtpclient) clase. |
| [SmtpClient](smtpclient#constructor_9)(string, int, string, string, SecurityOptions) | Inicializa una nueva instancia del[`SmtpClient`](../smtpclient) clase. |
| [SmtpClient](smtpclient#constructor_17)(string, string, string, bool, SecurityOptions) | Inicializa una nueva instancia del[`SmtpClient`](../smtpclient) clase. |
| [SmtpClient](smtpclient#constructor_11)(string, int, string, string, bool, SecurityOptions) | Inicializa una nueva instancia del[`SmtpClient`](../smtpclient) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients/emailclient/accesstoken) { get; set; } | Obtiene o establece el token de acceso. |
| [AllowedAuthentication](../../aspose.email.clients.smtp/smtpclient/allowedauthentication) { get; set; } | Obtiene o establece la enumeración de los tipos de autenticación permitidos por el usuario |
| virtual [ClientCertificates](../../aspose.email.clients/emailclient/clientcertificates) { get; } | Contiene una colección de certificados de clientes |
| virtual [ConnectionAsgmtMode](../../aspose.email.clients/emailclient/connectionasgmtmode) { get; set; } | Obtiene o establece el valor que define el modo de asignación de la conexión en un entorno de subprocesos múltiples Existen los siguientes tipos de conexión: - La conexión principal es una conexión creada y eliminada junto con el cliente de correo. No se puede crear ni eliminar manualmente. - La conexión predeterminada es la conexión predeterminada para algunos subprocesos. Si existe una conexión predeterminada y ConnectionAsgmtMode lo permite, todos los métodos del cliente de correo electrónico ejecutados en este subproceso usarán implícitamente esta conexión. Solo puede existir una conexión predeterminada por subproceso. Se puede crear de forma manual o automática. Depende de la propiedad EmailClient.ConnectionAsgmtMode. Estas conexiones se pueden crear manualmente con el método EmailClient.CreateConnection(createAsDefaultConnection = true). Si no se usa la conexión predeterminada (depende del modo de asignación de conexión), la conexión principal se usa implícitamente en su lugar. - Las conexiones independientes son conexiones que son no vinculados a subprocesos. Se pueden crear manualmente y se deben usar explícitamente como parámetro de método. Estas conexiones se pueden crear manualmente con el método EmailClient.CreateConnection() o el método EmailClient.CreateConnection(createAsDefaultConnection = false). Existen los siguientes tipos de asignación de conexiones: - ConnectionAsgmtType.UseMainOrDefault Este modo se usa de forma predeterminada en los clientes de correo electrónico. El cliente de correo electrónico utiliza la conexión principal para todas las operaciones de varios subprocesos si no se ha creado una conexión predeterminada o si no se ha pasado explícitamente la conexión como parámetro de método. La conexión principal es una conexión que se crea al mismo tiempo que el cliente de correo electrónico. El usuario puede crear conexiones predeterminadas para subprocesos con el método CreateConnection. Si se crea una conexión predeterminada para el subproceso, se usa implícitamente para todos los métodos de cliente de correo electrónico que se invocan en este subproceso. Si no se crea una conexión predeterminada para el subproceso, se usa la conexión principal para todos los métodos de cliente de correo electrónico que se invocan en este subproceso. thread. El usuario también puede crear conexiones no vinculadas con hilos (no conexiones predeterminadas) con el método CreateConnection. Si el usuario desea utilizar otras conexiones (no principales ni predeterminadas), debe pasar esta conexión explícitamente como parámetro de un método que desee utilizar. El usuario puede crear, además, cualquier número de conexiones. La conexión predeterminada solo puede ser una por subproceso. Tenga en cuenta que las conexiones predeterminadas funcionan correctamente si el usuario utiliza objetos Subproceso para la programación multitarea. Si el usuario usa ConnectionPool o usa objetos Task para la programación multitarea, este modo puede conducir a un comportamiento incorrecto de un programa. Para evitar este problema, el usuario debe eliminar manualmente la conexión predeterminada (si la usa) al final del código que se ejecuta en the thread. - ConnectionAsgmtType.UseMain El cliente de correo electrónico utiliza la conexión principal para todas las operaciones de varios subprocesos. La conexión principal es una conexión que se crea al mismo tiempo que el cliente de correo electrónico. El usuario no puede crear conexiones predeterminadas. El usuario puede crear conexiones no vinculadas con subprocesos (no conexiones predeterminadas) con el método CreateConnection. Si el usuario desea utilizar otras conexiones (no principales ni predeterminadas), debe pasar esta conexión explícitamente como parámetro de un método que desee utilizar. El usuario puede crear, además, cualquier número de conexiones. - ConnectionAsgmtType.UseDefault El cliente de correo electrónico utiliza implícitamente solo conexiones predeterminadas para todas las operaciones de varios subprocesos. La conexión principal no se usa en este modo. Si no se ha creado una conexión predeterminada para algún subproceso (primera invocación del método de cliente de correo electrónico), el cliente de correo electrónico crea una conexión predeterminada implícitamente para el subproceso antes de que se ejecute la primera operación. El usuario no puede cree conexiones predeterminadas para subprocesos con el método CreateConnection porque se crean automáticamente. Cuando se crea una conexión predeterminada para el subproceso, se usa implícitamente para todos los métodos del cliente de correo electrónico que se invocan en este subproceso.read. El usuario también puede crear conexiones no vinculadas con subprocesos (no conexiones predeterminadas) con el método CreateConnection. Si el usuario desea utilizar otras conexiones (no principales ni predeterminadas), debe pasar esta conexión explícitamente como parámetro de un método que desee utilizar. El usuario puede crear, además, cualquier número de conexiones. La conexión predeterminada solo puede ser una por subproceso. Tenga en cuenta que las conexiones predeterminadas funcionan correctamente si el usuario utiliza objetos Subproceso para la programación multitarea. Si el usuario usa ConnectionPool o usa objetos Task para la programación multitarea, este modo puede conducir a un comportamiento incorrecto de un programa. Para evitar este problema, el usuario debe eliminar manualmente la conexión predeterminada al final del código que se ejecuta en el subproceso. |
| virtual [ConnectionCheckupPeriod](../../aspose.email.clients/emailclient/connectioncheckupperiod) { get; set; } | Período de verificación de conexión en milisegundos. El valor predeterminado es 5 min. |
| virtual [ConnectionsQuantity](../../aspose.email.clients/emailclient/connectionsquantity) { get; set; } | Obtiene o establece la cantidad de conexiones en modo multiconexión |
| [ConnectionState](../../aspose.email.clients/emailclient/connectionstate) { get; } | Obtiene el estado actual de la conexión. |
| virtual [CurrentConnection](../../aspose.email.clients/emailclient/currentconnection) { get; } | Obtiene la conexión actual según la opción ConnectionAsgmtMode |
| override [DefaultPort](../../aspose.email.clients.smtp/smtpclient/defaultport) { get; } | Obtiene el puerto predeterminado para client |
| [DeliveryMethod](../../aspose.email.clients.smtp/smtpclient/deliverymethod) { get; set; } | Obtiene o establece el método de entrega. |
| [EnableLogger](../../aspose.email.clients/emailclient/enablelogger) { get; set; } | Obtiene o establece el valor que permite activar/desactivar logger |
| [GreetingTimeout](../../aspose.email.clients/emailclient/greetingtimeout) { get; set; } | Obtiene o establece el tiempo de espera del saludo que se usa al establecer una conexión. Tenga en cuenta que el tiempo de espera del saludo no puede ser infinito. Los clientes de correo electrónico pueden ejecutar operaciones suficientemente largas. Para limitar el tiempo de las operaciones, los usuarios deben utilizar[`Timeout`](../../aspose.email.clients/emailclient/timeout)propiedad. Los valores de esta propiedad deben tener intervalos largos para no evitar operaciones de larga duración. Pero en algunos casos, si EmailClient usará solo la propiedad Timeout, el establecimiento de la conexión puede llevar mucho tiempo. Por ejemplo, el cliente de correo puede usar el modo automático para establecer la conexión. En este modo, el cliente de correo electrónico pasa por todos los parámetros de conexión posibles hasta que se establece la conexión. Servidores SMTP, IMAP y POP3 en caso de conexión correcta estableciendo enviar cadena de saludo al cliente. Los servidores pueden usar el inicio de conexión SSL/TLS implícito o explícito (START TLS). Si el modo de conexión no coincide (por ejemplo, el servidor espera una conexión SSL implícita pero el cliente intenta establecer una conexión SSL explícita o no segura), el servidor no enviará una cadena de saludo. En este caso, el usuario esperará mucho tiempo hasta que el tiempo de espera alcance una cadena de saludo y el cliente pasará a la siguiente opción de conexión. Para evitar este problema, se ha introducido la propiedad GreetingTimeout. Esta propiedad le permite establecer el tiempo de espera para la cadena de saludo, y reducir el tiempo de establecimiento automático de la conexión. |
| [HelloMessage](../../aspose.email.clients.smtp/smtpclient/hellomessage) { get; set; } | Obtiene o establece una cadena HELO/EHLO. |
| virtual [Host](../../aspose.email.clients/emailclient/host) { get; set; } | Obtiene o establece el nombre de host. |
| [LogFileName](../../aspose.email.clients/emailclient/logfilename) { get; set; } | Obtiene o establece el nombre del archivo de registro |
| virtual [Password](../../aspose.email.clients/emailclient/password) { get; set; } | Obtiene o establece la contraseña. Las limitaciones de la contraseña están definidas por la implementación del servidor, a qué cliente se conecta. |
| [PickupDirectoryLocation](../../aspose.email.clients.smtp/smtpclient/pickupdirectorylocation) { get; set; } | Obtiene o establece el directorio donde las aplicaciones guardan los mensajes de correo para que los procese el servidor SMTP local. Tenga en cuenta: solo se permite la ruta absoluta. |
| virtual [Port](../../aspose.email.clients/emailclient/port) { get; set; } | Obtiene o establece el puerto. |
| virtual [Proxy](../../aspose.email.clients/emailclient/proxy) { get; set; } | Obtiene o establece el proxy para el cliente |
| virtual [SecurityOptions](../../aspose.email.clients/emailclient/securityoptions) { get; set; } | Modo de seguridad para un cliente de correo |
| [SmtpQueueLocation](../../aspose.email.clients.smtp/smtpclient/smtpqueuelocation) { get; set; } | Obtiene o establece el directorio donde las aplicaciones guardan los mensajes de correo para ser procesados mediante el envío en la cola SMTP. Tenga en cuenta: solo se permite la ruta absoluta. |
| [SupportedAuthentication](../../aspose.email.clients.smtp/smtpclient/supportedauthentication) { get; } | Obtiene la enumeración de los tipos de autenticación admitidos por el servidor |
| virtual [SupportedEncryption](../../aspose.email.clients/emailclient/supportedencryption) { get; set; } | Define las versiones de los protocolos de encriptación SSL/TLS que se utilizarán. POR FAVOR PRESTA ATENCIÓN, puedes configurar solo aquellas versiones de protocolo compatibles con .net framework. SI ALGUNAS VERSIONES DEL PROTOCOLO NO SON COMPATIBLES CON TU VERSIÓN ACTUAL DE .NET FRAMEWORK, SE IGNORARÁN Y OMITIRÁN. PUEDE LLEVAR A UNA DEGRADACIÓN DEL NIVEL DE SEGURIDAD DE TLS. ¡¡¡EN ESTE CASO NO SE GENERARÁ EXCEPCIÓN!!! Por favor, consulte[`EncryptionProtocols`](../../aspose.email.clients.base/encryptionprotocols) documentación para obtener más detalles. Utilice[`SetSupportedEncryptionUnsafe`](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe) método si desea configurar los protocolos de cifrado sin ninguna verificación de compatibilidad. El valor predeterminado es: Tls &#x7C; Tls11 &#x7C; Tls12 &#x7C; Tls13 (en caso de que su versión actual de .NET Framework sea compatible con estas versiones de TLS) |
| [Timeout](../../aspose.email.clients/emailclient/timeout) { get; set; } | Obtiene o establece el tiempo de espera para las operaciones de correo |
| [TokenProvider](../../aspose.email.clients/emailclient/tokenprovider) { get; set; } | Obtiene o establece TokenProvider que permite recuperar el token de acceso. |
| virtual [UseAuthentication](../../aspose.email.clients/emailclient/useauthentication) { get; set; } | Indica si se utiliza autenticación. |
| [UseDateInLogFileName](../../aspose.email.clients/emailclient/usedateinlogfilename) { get; set; } | Obtiene o establece el valor que indica si se debe usar la fecha en el nombre del archivo de registro. |
| override [UseDefaultCredentials](../../aspose.email.clients.smtp/smtpclient/usedefaultcredentials) { get; set; } | Obtiene o establece un valor booleano que controla si las credenciales predeterminadas se envían con solicitudes. |
| virtual [UseMultiConnection](../../aspose.email.clients/emailclient/usemulticonnection) { get; set; } | Obtiene o establece el valor que indica si el cliente tiene que usar varias conexiones para operaciones de carga pesada. Tenga en cuenta que el uso de este modo no es necesario para aumentar el rendimiento. |
| virtual [UsePipelining](../../aspose.email.clients/emailclient/usepipelining) { get; set; } | Obtiene o establece un objeto que indica si el modo de canalización está habilitado. |
| virtual [Username](../../aspose.email.clients/emailclient/username) { get; set; } | Obtiene o establece el nombre de usuario. |
| [UseTnef](../../aspose.email.clients.smtp/smtpclient/usetnef) { get; set; } | Obtiene o establece un valor booleano que controla si los mensajes se envían en formato TNEF. Tenga en cuenta que ahora el mensaje se envía en formato TNEF cuando se carga un mensaje que contiene tnef. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)() | Crea una nueva conexión independiente para operaciones no vinculadas a subprocesos (no conexión predeterminada). La invocación de este método es similar a la invocación de CreateConnection(createAsDefaultConnection = false) Consulte más en la documentación de la propiedad EmailClient.ConnectionAsgmtMode. |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)(bool) | Crea una nueva conexión (predeterminada o independiente) para operaciones. Consulte más en la documentación de la propiedad EmailClient.ConnectionAsgmtMode. |
| virtual [Dispose](../../aspose.email.clients/emailclient/dispose)() | Finaliza todas las operaciones con un servidor. |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_3)(string, MailAddressCollection, MailMessage) | Reenvía el mensaje especificado al destinatario |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_4)(string, MailAddressCollection, Stream) | Reenvía el mensaje especificado al destinatario |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_5)(string, string, MailMessage) | Reenvía el mensaje especificado al destinatario |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward)(IConnection, string, MailAddressCollection, MailMessage) | Reenvía el mensaje especificado al destinatario |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_1)(IConnection, string, MailAddressCollection, Stream) | Reenvía el mensaje especificado al destinatario |
| [Forward](../../aspose.email.clients.smtp/smtpclient/forward#forward_2)(IConnection, string, string, MailMessage) | Reenvía el mensaje especificado al destinatario |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_6)(string, MailAddressCollection, MailMessage) | Reenvía el mensaje especificado al destinatario |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_8)(string, MailAddressCollection, Stream) | Reenvía el mensaje especificado al destinatario |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_10)(string, string, MailMessage) | Reenvía el mensaje especificado al destinatario |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync)(IConnection, string, MailAddressCollection, MailMessage) | Reenvía el mensaje especificado al destinatario |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_2)(IConnection, string, MailAddressCollection, Stream) | Reenvía el mensaje especificado al destinatario |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_4)(IConnection, string, string, MailMessage) | Reenvía el mensaje especificado al destinatario |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_7)(string, MailAddressCollection, MailMessage, CancellationToken) | Reenvía el mensaje especificado al destinatario |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_9)(string, MailAddressCollection, Stream, CancellationToken) | Reenvía el mensaje especificado al destinatario |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_11)(string, string, MailMessage, CancellationToken) | Reenvía el mensaje especificado al destinatario |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_1)(IConnection, string, MailAddressCollection, MailMessage, CancellationToken) | Reenvía el mensaje especificado al destinatario |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_3)(IConnection, string, MailAddressCollection, Stream, CancellationToken) | Reenvía el mensaje especificado al destinatario |
| [ForwardAsync](../../aspose.email.clients.smtp/smtpclient/forwardasync#forwardasync_5)(IConnection, string, string, MailMessage, CancellationToken) | Reenvía el mensaje especificado al destinatario |
| virtual [GetCapabilities](../../aspose.email.clients/emailclient/getcapabilities)() |  |
| override [Noop](../../aspose.email.clients.smtp/smtpclient/noop#noop)() | Comando 'Sin operación' |
| override [Noop](../../aspose.email.clients.smtp/smtpclient/noop#noop_1)(IConnection) | Comando 'Sin operación' |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync)() | Comando 'Sin operación' |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync_3)(CancellationToken) | Comando 'Sin operación' |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync_1)(IConnection) | Comando 'Sin operación' |
| [NoopAsync](../../aspose.email.clients.smtp/smtpclient/noopasync#noopasync_2)(IConnection, CancellationToken) | Comando 'Sin operación' |
| [ResetLogSettings](../../aspose.email.clients/emailclient/resetlogsettings)() | Restablece la configuración de registro a los valores predeterminados. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_8)(IEnumerable&lt;MailMessage&gt;) | Envía los mensajes especificados. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_5)(MailMessage) | Enviar el mensaje especificado. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_6)(MailMessageCollection) | Enviar la colección de mensajes especificada. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_7)(params MailMessage[]) | Enviar el mensaje especificado. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_3)(IConnection, IEnumerable&lt;MailMessage&gt;) | Envía los mensajes especificados. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send)(IConnection, MailMessage) | Enviar el mensaje especificado. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_1)(IConnection, MailMessageCollection) | Enviar la colección de mensajes especificada. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_2)(IConnection, params MailMessage[]) | Enviar el mensaje especificado. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_9)(string, string, string, string) | Crea y envía el mensaje especificado. |
| [Send](../../aspose.email.clients.smtp/smtpclient/send#send_4)(IConnection, string, string, string, string) | Crea y envía el mensaje especificado. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_16)(IEnumerable&lt;MailMessage&gt;) | Envía los mensajes especificados. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_11)(MailMessage) | Enviar el mensaje especificado. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_13)(MailMessageCollection) | Enviar la colección de mensajes especificada. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_15)(params MailMessage[]) | Enviar el mensaje especificado. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_10)(SmtpSend) |  |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_20)(CancellationToken, params MailMessage[]) | Enviar el mensaje especificado. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_5)(IConnection, IEnumerable&lt;MailMessage&gt;) | Envía los mensajes especificados. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync)(IConnection, MailMessage) | Enviar el mensaje especificado. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_2)(IConnection, MailMessageCollection) | Enviar la colección de mensajes especificada. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_4)(IConnection, params MailMessage[]) | Enviar el mensaje especificado. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_17)(IEnumerable&lt;MailMessage&gt;, CancellationToken) | Envía los mensajes especificados. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_12)(MailMessage, CancellationToken) | Enviar el mensaje especificado. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_14)(MailMessageCollection, CancellationToken) | Enviar la colección de mensajes especificada. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_9)(IConnection, CancellationToken, params MailMessage[]) | Enviar el mensaje especificado. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_6)(IConnection, IEnumerable&lt;MailMessage&gt;, CancellationToken) | Envía los mensajes especificados. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_1)(IConnection, MailMessage, CancellationToken) | Enviar el mensaje especificado. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_3)(IConnection, MailMessageCollection, CancellationToken) | Enviar la colección de mensajes especificada. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_18)(string, string, string, string) | Crea y envía el mensaje especificado. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_7)(IConnection, string, string, string, string) | Crea y envía el mensaje especificado. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_19)(string, string, string, string, CancellationToken) | Crea y envía el mensaje especificado. |
| [SendAsync](../../aspose.email.clients.smtp/smtpclient/sendasync#sendasync_8)(IConnection, string, string, string, string, CancellationToken) | Crea y envía el mensaje especificado. |
| [SendToQueue](../../aspose.email.clients.smtp/smtpclient/sendtoqueue)(IEnumerable&lt;MailMessage&gt;) | Agregar mensajes a la cola |
| [SetSupportedEncryptionUnsafe](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)(EncryptionProtocols) | Define las versiones de los protocolos de encriptación SSL/TLS que se utilizarán. Este método no es seguro y establece los protocolos de encriptación sin ninguna verificación de compatibilidad. Usar[`SupportedEncryption`](../../aspose.email.clients/emailclient/supportedencryption) propiedad para configurar de forma segura solo los protocolos que definitivamente son compatibles con .net framework. Tenga en cuenta que si su actual .net framework no admite este nivel de seguridad, se generará una excepción al intentar establecer una conexión con el servidor. |
| override [ValidateCredentials](../../aspose.email.clients.smtp/smtpclient/validatecredentials#validatecredentials)() | Ejecuta validación de credenciales |
| [ValidateCredentials](../../aspose.email.clients.smtp/smtpclient/validatecredentials#validatecredentials_1)(IConnection) | Ejecuta validación de credenciales |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync)() | Ejecuta validación de credenciales |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync_3)(CancellationToken) | Ejecuta validación de credenciales |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync_1)(IConnection) | Ejecuta validación de credenciales |
| [ValidateCredentialsAsync](../../aspose.email.clients.smtp/smtpclient/validatecredentialsasync#validatecredentialsasync_2)(IConnection, CancellationToken) | Ejecuta validación de credenciales |
| static [CreateAsync](../../aspose.email.clients.smtp/smtpclient/createasync)(string, string, IAsyncTokenProvider, int, SecurityOptions, CancellationToken) | Crea una nueva instancia del[`SmtpClient`](../smtpclient) clase |

### Ver también

* class [EmailClient](../../aspose.email.clients/emailclient)
* interface [IAsyncSmtpClient](../iasyncsmtpclient)
* interface [IMailTransferAgent](../imailtransferagent)
* espacio de nombres [Aspose.Email.Clients.Smtp](../../aspose.email.clients.smtp)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
