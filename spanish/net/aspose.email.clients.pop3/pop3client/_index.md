---
title: Pop3Client
second_title: Referencia de la API de Aspose.Email para .NET
description: Permite que las aplicaciones accedan y manipulen los mensajes mediante el Protocolo de oficina de correos versión 3 POP3.
type: docs
weight: 16880
url: /es/net/aspose.email.clients.pop3/pop3client/
---
## Pop3Client class

Permite que las aplicaciones accedan y manipulen los mensajes mediante el Protocolo de oficina de correos versión 3 (POP3).

```csharp
public sealed class Pop3Client : EmailClient, IAsyncPop3Client
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Pop3Client](pop3client#constructor)() | Inicializa una nueva instancia del[`Pop3Client`](../pop3client) clase |
| [Pop3Client](pop3client#constructor_1)(string) | Inicializa una nueva instancia del[`Pop3Client`](../pop3client) clase |
| [Pop3Client](pop3client#constructor_3)(string, int) | Inicializa una nueva instancia del[`Pop3Client`](../pop3client) clase |
| [Pop3Client](pop3client#constructor_2)(string, SecurityOptions) | Inicializa una nueva instancia del[`Pop3Client`](../pop3client) clase |
| [Pop3Client](pop3client#constructor_4)(string, int, SecurityOptions) | Inicializa una nueva instancia del[`Pop3Client`](../pop3client) clase |
| [Pop3Client](pop3client#constructor_11)(string, string, string) | Inicializa una nueva instancia del[`Pop3Client`](../pop3client) clase |
| [Pop3Client](pop3client#constructor_6)(string, int, string, string) | Inicializa una nueva instancia del[`Pop3Client`](../pop3client) clase |
| [Pop3Client](pop3client#constructor_12)(string, string, string, SecurityOptions) | Inicializa una nueva instancia del[`Pop3Client`](../pop3client) clase |
| [Pop3Client](pop3client#constructor_5)(string, int, string, ITokenProvider, SecurityOptions) | Inicializa una nueva instancia del[`Pop3Client`](../pop3client) clase |
| [Pop3Client](pop3client#constructor_9)(string, int, string, string, RemoteCertificateValidationCallback) | Inicializa una nueva instancia del[`Pop3Client`](../pop3client) clase |
| [Pop3Client](pop3client#constructor_7)(string, int, string, string, SecurityOptions) | Inicializa una nueva instancia del[`Pop3Client`](../pop3client) clase |
| [Pop3Client](pop3client#constructor_8)(string, int, string, string, bool, SecurityOptions) | Inicializa una nueva instancia del[`Pop3Client`](../pop3client) clase |
| [Pop3Client](pop3client#constructor_10)(string, int, string, string, RemoteCertificateValidationCallback, SecurityOptions) | Inicializa una nueva instancia del[`Pop3Client`](../pop3client) clase |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients/emailclient/accesstoken) { get; set; } | Obtiene o establece el token de acceso. |
| [AllowedAuthentication](../../aspose.email.clients.pop3/pop3client/allowedauthentication) { get; set; } | Obtiene o establece la enumeración de los tipos de autenticación permitidos por el usuario |
| virtual [ClientCertificates](../../aspose.email.clients/emailclient/clientcertificates) { get; } | Contiene una colección de certificados de clientes |
| virtual [ConnectionAsgmtMode](../../aspose.email.clients/emailclient/connectionasgmtmode) { get; set; } | Obtiene o establece el valor que define el modo de asignación de la conexión en un entorno de subprocesos múltiples Existen los siguientes tipos de conexión: - La conexión principal es una conexión creada y eliminada junto con el cliente de correo. No se puede crear ni eliminar manualmente. - La conexión predeterminada es la conexión predeterminada para algunos subprocesos. Si existe una conexión predeterminada y ConnectionAsgmtMode lo permite, todos los métodos del cliente de correo electrónico ejecutados en este subproceso usarán implícitamente esta conexión. Solo puede existir una conexión predeterminada por subproceso. Se puede crear de forma manual o automática. Depende de la propiedad EmailClient.ConnectionAsgmtMode. Estas conexiones se pueden crear manualmente con el método EmailClient.CreateConnection(createAsDefaultConnection = true). Si no se usa la conexión predeterminada (depende del modo de asignación de conexión), la conexión principal se usa implícitamente en su lugar. - Las conexiones independientes son conexiones que son no vinculados a subprocesos. Se pueden crear manualmente y se deben usar explícitamente como parámetro de método. Estas conexiones se pueden crear manualmente con el método EmailClient.CreateConnection() o el método EmailClient.CreateConnection(createAsDefaultConnection = false). Existen los siguientes tipos de asignación de conexiones: - ConnectionAsgmtType.UseMainOrDefault Este modo se usa de forma predeterminada en los clientes de correo electrónico. El cliente de correo electrónico utiliza la conexión principal para todas las operaciones de varios subprocesos si no se ha creado una conexión predeterminada o si no se ha pasado explícitamente la conexión como parámetro de método. La conexión principal es una conexión que se crea al mismo tiempo que el cliente de correo electrónico. El usuario puede crear conexiones predeterminadas para subprocesos con el método CreateConnection. Si se crea una conexión predeterminada para el subproceso, se usa implícitamente para todos los métodos de cliente de correo electrónico que se invocan en este subproceso. Si no se crea una conexión predeterminada para el subproceso, se usa la conexión principal para todos los métodos de cliente de correo electrónico que se invocan en este subproceso. thread. El usuario también puede crear conexiones no vinculadas con hilos (no conexiones predeterminadas) con el método CreateConnection. Si el usuario desea utilizar otras conexiones (no principales ni predeterminadas), debe pasar esta conexión explícitamente como parámetro de un método que desee utilizar. El usuario puede crear, además, cualquier número de conexiones. La conexión predeterminada solo puede ser una por subproceso. Tenga en cuenta que las conexiones predeterminadas funcionan correctamente si el usuario utiliza objetos Subproceso para la programación multitarea. Si el usuario usa ConnectionPool o usa objetos Task para la programación multitarea, este modo puede conducir a un comportamiento incorrecto de un programa. Para evitar este problema, el usuario debe eliminar manualmente la conexión predeterminada (si la usa) al final del código que se ejecuta en the thread. - ConnectionAsgmtType.UseMain El cliente de correo electrónico utiliza la conexión principal para todas las operaciones de varios subprocesos. La conexión principal es una conexión que se crea al mismo tiempo que el cliente de correo electrónico. El usuario no puede crear conexiones predeterminadas. El usuario puede crear conexiones no vinculadas con subprocesos (no conexiones predeterminadas) con el método CreateConnection. Si el usuario desea utilizar otras conexiones (no principales ni predeterminadas), debe pasar esta conexión explícitamente como parámetro de un método que desee utilizar. El usuario puede crear, además, cualquier número de conexiones. - ConnectionAsgmtType.UseDefault El cliente de correo electrónico utiliza implícitamente solo conexiones predeterminadas para todas las operaciones de varios subprocesos. La conexión principal no se usa en este modo. Si no se ha creado una conexión predeterminada para algún subproceso (primera invocación del método de cliente de correo electrónico), el cliente de correo electrónico crea una conexión predeterminada implícitamente para el subproceso antes de que se ejecute la primera operación. El usuario no puede cree conexiones predeterminadas para subprocesos con el método CreateConnection porque se crean automáticamente. Cuando se crea una conexión predeterminada para el subproceso, se usa implícitamente para todos los métodos del cliente de correo electrónico que se invocan en este subproceso.read. El usuario también puede crear conexiones no vinculadas con subprocesos (no conexiones predeterminadas) con el método CreateConnection. Si el usuario desea utilizar otras conexiones (no principales ni predeterminadas), debe pasar esta conexión explícitamente como parámetro de un método que desee utilizar. El usuario puede crear, además, cualquier número de conexiones. La conexión predeterminada solo puede ser una por subproceso. Tenga en cuenta que las conexiones predeterminadas funcionan correctamente si el usuario utiliza objetos Subproceso para la programación multitarea. Si el usuario usa ConnectionPool o usa objetos Task para la programación multitarea, este modo puede conducir a un comportamiento incorrecto de un programa. Para evitar este problema, el usuario debe eliminar manualmente la conexión predeterminada al final del código que se ejecuta en el subproceso. |
| virtual [ConnectionCheckupPeriod](../../aspose.email.clients/emailclient/connectioncheckupperiod) { get; set; } | Período de verificación de conexión en milisegundos. El valor predeterminado es 5 min. |
| virtual [ConnectionsQuantity](../../aspose.email.clients/emailclient/connectionsquantity) { get; set; } | Obtiene o establece la cantidad de conexiones en modo multiconexión |
| [ConnectionState](../../aspose.email.clients/emailclient/connectionstate) { get; } | Obtiene el estado actual de la conexión. |
| virtual [CurrentConnection](../../aspose.email.clients/emailclient/currentconnection) { get; } | Obtiene la conexión actual según la opción ConnectionAsgmtMode |
| override [DefaultPort](../../aspose.email.clients.pop3/pop3client/defaultport) { get; } | Obtiene el puerto predeterminado para client |
| [EnableLogger](../../aspose.email.clients/emailclient/enablelogger) { get; set; } | Obtiene o establece el valor que permite activar/desactivar logger |
| [GreetingTimeout](../../aspose.email.clients/emailclient/greetingtimeout) { get; set; } | Obtiene o establece el tiempo de espera del saludo que se usa al establecer una conexión. Tenga en cuenta que el tiempo de espera del saludo no puede ser infinito. Los clientes de correo electrónico pueden ejecutar operaciones suficientemente largas. Para limitar el tiempo de las operaciones, los usuarios deben utilizar[`Timeout`](../../aspose.email.clients/emailclient/timeout)propiedad. Los valores de esta propiedad deben tener intervalos largos para no evitar operaciones de larga duración. Pero en algunos casos, si EmailClient usará solo la propiedad Timeout, el establecimiento de la conexión puede llevar mucho tiempo. Por ejemplo, el cliente de correo puede usar el modo automático para establecer la conexión. En este modo, el cliente de correo electrónico pasa por todos los parámetros de conexión posibles hasta que se establece la conexión. Servidores SMTP, IMAP y POP3 en caso de conexión correcta estableciendo enviar cadena de saludo al cliente. Los servidores pueden usar el inicio de conexión SSL/TLS implícito o explícito (START TLS). Si el modo de conexión no coincide (por ejemplo, el servidor espera una conexión SSL implícita pero el cliente intenta establecer una conexión SSL explícita o no segura), el servidor no enviará una cadena de saludo. En este caso, el usuario esperará mucho tiempo hasta que el tiempo de espera alcance una cadena de saludo y el cliente pasará a la siguiente opción de conexión. Para evitar este problema, se ha introducido la propiedad GreetingTimeout. Esta propiedad le permite establecer el tiempo de espera para la cadena de saludo, y reducir el tiempo de establecimiento automático de la conexión. |
| virtual [Host](../../aspose.email.clients/emailclient/host) { get; set; } | Obtiene o establece el nombre de host. |
| [LogFileName](../../aspose.email.clients/emailclient/logfilename) { get; set; } | Obtiene o establece el nombre del archivo de registro |
| virtual [Password](../../aspose.email.clients/emailclient/password) { get; set; } | Obtiene o establece la contraseña. Las limitaciones de la contraseña están definidas por la implementación del servidor, a qué cliente se conecta. |
| virtual [Port](../../aspose.email.clients/emailclient/port) { get; set; } | Obtiene o establece el puerto. |
| virtual [Proxy](../../aspose.email.clients/emailclient/proxy) { get; set; } | Obtiene o establece el proxy para el cliente |
| virtual [SecurityOptions](../../aspose.email.clients/emailclient/securityoptions) { get; set; } | Modo de seguridad para un cliente de correo |
| [SupportedAuthentication](../../aspose.email.clients.pop3/pop3client/supportedauthentication) { get; } | Obtiene la enumeración de los tipos de autenticación admitidos por el servidor |
| virtual [SupportedEncryption](../../aspose.email.clients/emailclient/supportedencryption) { get; set; } | Define las versiones de los protocolos de encriptación SSL/TLS que se utilizarán. POR FAVOR PRESTA ATENCIÓN, puedes configurar solo aquellas versiones de protocolo compatibles con .net framework. SI ALGUNAS VERSIONES DEL PROTOCOLO NO SON COMPATIBLES CON TU VERSIÓN ACTUAL DE .NET FRAMEWORK, SE IGNORARÁN Y OMITIRÁN. PUEDE LLEVAR A UNA DEGRADACIÓN DEL NIVEL DE SEGURIDAD DE TLS. ¡¡¡EN ESTE CASO NO SE GENERARÁ EXCEPCIÓN!!! Por favor, consulte[`EncryptionProtocols`](../../aspose.email.clients.base/encryptionprotocols) documentación para obtener más detalles. Utilice[`SetSupportedEncryptionUnsafe`](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe) método si desea configurar los protocolos de cifrado sin ninguna verificación de compatibilidad. El valor predeterminado es: Tls &#x7C; Tls11 &#x7C; Tls12 &#x7C; Tls13 (en caso de que su versión actual de .NET Framework sea compatible con estas versiones de TLS) |
| [Timeout](../../aspose.email.clients/emailclient/timeout) { get; set; } | Obtiene o establece el tiempo de espera para las operaciones de correo |
| [TokenProvider](../../aspose.email.clients/emailclient/tokenprovider) { get; set; } | Obtiene o establece TokenProvider que permite recuperar el token de acceso. |
| virtual [UseAuthentication](../../aspose.email.clients/emailclient/useauthentication) { get; set; } | Indica si se utiliza autenticación. |
| [UseDateInLogFileName](../../aspose.email.clients/emailclient/usedateinlogfilename) { get; set; } | Obtiene o establece el valor que indica si se debe usar la fecha en el nombre del archivo de registro. |
| virtual [UseDefaultCredentials](../../aspose.email.clients/emailclient/usedefaultcredentials) { get; set; } | Obtiene o establece un valor booleano que controla si las credenciales predeterminadas se envían con solicitudes. ¡Esta opción se usa SOLO con autenticación NTLM! |
| virtual [UseMultiConnection](../../aspose.email.clients/emailclient/usemulticonnection) { get; set; } | Obtiene o establece el valor que indica si el cliente tiene que usar varias conexiones para operaciones de carga pesada. Tenga en cuenta que el uso de este modo no es necesario para aumentar el rendimiento. |
| virtual [UsePipelining](../../aspose.email.clients/emailclient/usepipelining) { get; set; } | Obtiene o establece un objeto que indica si el modo de canalización está habilitado. |
| virtual [Username](../../aspose.email.clients/emailclient/username) { get; set; } | Obtiene o establece el nombre de usuario. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes)() | Confirmar las eliminaciones |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes_1)(IConnection) | Confirmar las eliminaciones |
| [CommitDeletes](../../aspose.email.clients.pop3/pop3client/commitdeletes#commitdeletes_2)(int) | Confirmar las eliminaciones |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync)() | Confirmar las eliminaciones |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_5)(CancellationToken) | Confirmar las eliminaciones |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_1)(IConnection) | Confirmar las eliminaciones |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_3)(int) | Confirmar las eliminaciones |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_2)(IConnection, CancellationToken) | Confirmar las eliminaciones |
| [CommitDeletesAsync](../../aspose.email.clients.pop3/pop3client/commitdeletesasync#commitdeletesasync_4)(int, CancellationToken) | Confirmar las eliminaciones |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)() | Crea una nueva conexión independiente para operaciones no vinculadas a subprocesos (no conexión predeterminada). La invocación de este método es similar a la invocación de CreateConnection(createAsDefaultConnection = false) Consulte más en la documentación de la propiedad EmailClient.ConnectionAsgmtMode. |
| virtual [CreateConnection](../../aspose.email.clients/emailclient/createconnection)(bool) | Crea una nueva conexión (predeterminada o independiente) para operaciones. Consulte más en la documentación de la propiedad EmailClient.ConnectionAsgmtMode. |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_2)(int) | Borra el mensaje |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_3)(string) | Borra el mensaje |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage)(IConnection, int) | Borra el mensaje |
| [DeleteMessage](../../aspose.email.clients.pop3/pop3client/deletemessage#deletemessage_1)(IConnection, string) | Borra el mensaje |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_4)(int) | Borra el mensaje |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_6)(string) | Borra el mensaje |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync)(IConnection, int) | Borra el mensaje |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_2)(IConnection, string) | Borra el mensaje |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_5)(int, CancellationToken) | Borra el mensaje |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_7)(string, CancellationToken) | Borra el mensaje |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_1)(IConnection, int, CancellationToken) | Borra el mensaje |
| [DeleteMessageAsync](../../aspose.email.clients.pop3/pop3client/deletemessageasync#deletemessageasync_3)(IConnection, string, CancellationToken) | Borra el mensaje |
| [DeleteMessages](../../aspose.email.clients.pop3/pop3client/deletemessages#deletemessages)() | Borra todos los mensajes |
| [DeleteMessages](../../aspose.email.clients.pop3/pop3client/deletemessages#deletemessages_1)(IConnection) | Borra todos los mensajes |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync)() | Borra todos los mensajes |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_3)(CancellationToken) | Borra todos los mensajes |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_1)(IConnection) | Borra todos los mensajes |
| [DeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/deletemessagesasync#deletemessagesasync_2)(IConnection, CancellationToken) | Borra todos los mensajes |
| virtual [Dispose](../../aspose.email.clients/emailclient/dispose)() | Finaliza todas las operaciones con un servidor. |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_2)(int) | Obtiene el mensaje |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_3)(string) | Obtiene el mensaje |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage)(IConnection, int) | Obtiene el mensaje |
| [FetchMessage](../../aspose.email.clients.pop3/pop3client/fetchmessage#fetchmessage_1)(IConnection, string) | Obtiene el mensaje |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_4)(int) | Obtiene el mensaje |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_6)(string) | Obtiene el mensaje |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync)(IConnection, int) | Obtiene el mensaje |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_2)(IConnection, string) | Obtiene el mensaje |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_5)(int, CancellationToken) | Obtiene el mensaje |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_7)(string, CancellationToken) | Obtiene el mensaje |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_1)(IConnection, int, CancellationToken) | Obtiene el mensaje |
| [FetchMessageAsync](../../aspose.email.clients.pop3/pop3client/fetchmessageasync#fetchmessageasync_3)(IConnection, string, CancellationToken) | Obtiene el mensaje |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_2)(IEnumerable&lt;int&gt;) | Obtiene los mensajes |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_3)(IEnumerable&lt;string&gt;) | Obtiene los mensajes |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages)(IConnection, IEnumerable&lt;int&gt;) | Obtiene los mensajes |
| [FetchMessages](../../aspose.email.clients.pop3/pop3client/fetchmessages#fetchmessages_1)(IConnection, IEnumerable&lt;string&gt;) | Obtiene los mensajes |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_4)(IEnumerable&lt;int&gt;) | Obtiene los mensajes de forma asíncrona |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_6)(IEnumerable&lt;string&gt;) | Obtiene los mensajes de forma asíncrona |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync)(IConnection, IEnumerable&lt;int&gt;) | Obtiene los mensajes de forma asíncrona |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_2)(IConnection, IEnumerable&lt;string&gt;) | Obtiene los mensajes de forma asíncrona |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_5)(IEnumerable&lt;int&gt;, CancellationToken) | Obtiene los mensajes de forma asíncrona |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_7)(IEnumerable&lt;string&gt;, CancellationToken) | Obtiene los mensajes de forma asíncrona |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_1)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | Obtiene los mensajes de forma asíncrona |
| [FetchMessagesAsync](../../aspose.email.clients.pop3/pop3client/fetchmessagesasync#fetchmessagesasync_3)(IConnection, IEnumerable&lt;string&gt;, CancellationToken) | Obtiene los mensajes de forma asíncrona |
| virtual [GetCapabilities](../../aspose.email.clients/emailclient/getcapabilities)() |  |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo)() | Obtiene el estado del buzón info |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_3)(bool) | Obtiene el estado del buzón info |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_1)(IConnection) | Obtiene el estado del buzón info |
| [GetMailboxInfo](../../aspose.email.clients.pop3/pop3client/getmailboxinfo#getmailboxinfo_2)(IConnection, bool) | Obtiene el estado del buzón info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync)() | Obtiene el estado del buzón info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_5)(bool) | Obtiene el estado del buzón info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_7)(CancellationToken) | Obtiene el estado del buzón info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_1)(IConnection) | Obtiene el estado del buzón info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_6)(bool, CancellationToken) | Obtiene el estado del buzón info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_2)(IConnection, bool) | Obtiene el estado del buzón info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_4)(IConnection, CancellationToken) | Obtiene el estado del buzón info |
| [GetMailboxInfoAsync](../../aspose.email.clients.pop3/pop3client/getmailboxinfoasync#getmailboxinfoasync_3)(IConnection, bool, CancellationToken) | Obtiene el estado del buzón info |
| [GetMailboxSize](../../aspose.email.clients.pop3/pop3client/getmailboxsize#getmailboxsize)() | Obtiene el tamaño del buzón |
| [GetMailboxSize](../../aspose.email.clients.pop3/pop3client/getmailboxsize#getmailboxsize_1)(IConnection) | Obtiene el tamaño del buzón |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync)() | Obtiene el tamaño del buzón |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_3)(CancellationToken) | Obtiene el tamaño del buzón |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_1)(IConnection) | Obtiene el tamaño del buzón |
| [GetMailboxSizeAsync](../../aspose.email.clients.pop3/pop3client/getmailboxsizeasync#getmailboxsizeasync_2)(IConnection, CancellationToken) | Obtiene el tamaño del buzón |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount)() | Obtiene el mensaje count |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_3)(bool) | Obtiene el mensaje count |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_1)(IConnection) | Obtiene el mensaje count |
| [GetMessageCount](../../aspose.email.clients.pop3/pop3client/getmessagecount#getmessagecount_2)(IConnection, bool) | Obtiene el mensaje count |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync)() | Obtiene el mensaje count |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_5)(bool) | Obtiene el mensaje count |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_7)(CancellationToken) | Obtiene el mensaje count |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_1)(IConnection) | Obtiene el mensaje count |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_6)(bool, CancellationToken) | Obtiene el mensaje count |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_2)(IConnection, bool) | Obtiene el mensaje count |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_4)(IConnection, CancellationToken) | Obtiene el mensaje count |
| [GetMessageCountAsync](../../aspose.email.clients.pop3/pop3client/getmessagecountasync#getmessagecountasync_3)(IConnection, bool, CancellationToken) | Obtiene el mensaje count |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_2)(int) | Obtiene los encabezados del mensaje |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_3)(string) | Obtiene los encabezados del mensaje |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders)(IConnection, int) | Obtiene los encabezados del mensaje |
| [GetMessageHeaders](../../aspose.email.clients.pop3/pop3client/getmessageheaders#getmessageheaders_1)(IConnection, string) | Obtiene los encabezados del mensaje |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_4)(int) | Obtiene los encabezados del mensaje |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_6)(string) | Obtiene los encabezados del mensaje |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync)(IConnection, int) | Obtiene los encabezados del mensaje |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_2)(IConnection, string) | Obtiene los encabezados del mensaje |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_5)(int, CancellationToken) | Obtiene los encabezados del mensaje |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_7)(string, CancellationToken) | Obtiene los encabezados del mensaje |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_1)(IConnection, int, CancellationToken) | Obtiene los encabezados del mensaje |
| [GetMessageHeadersAsync](../../aspose.email.clients.pop3/pop3client/getmessageheadersasync#getmessageheadersasync_3)(IConnection, string, CancellationToken) | Obtiene los encabezados del mensaje |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_4)(int) | Obtiene la información de ese mensaje |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_6)(string) | Obtiene la información de ese mensaje |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo)(IConnection, int) | Obtiene la información de ese mensaje |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_2)(IConnection, string) | Obtiene la información de ese mensaje |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_5)(int, Pop3ListFields) | Obtiene la información de ese mensaje |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_7)(string, Pop3ListFields) | Obtiene la información de ese mensaje |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_1)(IConnection, int, Pop3ListFields) | Obtiene la información de ese mensaje |
| [GetMessageInfo](../../aspose.email.clients.pop3/pop3client/getmessageinfo#getmessageinfo_3)(IConnection, string, Pop3ListFields) | Obtiene la información de ese mensaje |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_8)(int) | Obtiene la información de ese mensaje |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_12)(string) | Obtiene la información de ese mensaje |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync)(IConnection, int) | Obtiene la información de ese mensaje |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_4)(IConnection, string) | Obtiene la información de ese mensaje |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_11)(int, CancellationToken) | Obtiene la información de ese mensaje |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_9)(int, Pop3ListFields) | Obtiene la información de ese mensaje |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_15)(string, CancellationToken) | Obtiene la información de ese mensaje |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_13)(string, Pop3ListFields) | Obtiene la información de ese mensaje |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_3)(IConnection, int, CancellationToken) | Obtiene la información de ese mensaje |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_1)(IConnection, int, Pop3ListFields) | Obtiene la información de ese mensaje |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_7)(IConnection, string, CancellationToken) | Obtiene la información de ese mensaje |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_5)(IConnection, string, Pop3ListFields) | Obtiene la información de ese mensaje |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_10)(int, Pop3ListFields, CancellationToken) | Obtiene la información de ese mensaje |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_14)(string, Pop3ListFields, CancellationToken) | Obtiene la información de ese mensaje |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_2)(IConnection, int, Pop3ListFields, CancellationToken) | Obtiene la información de ese mensaje |
| [GetMessageInfoAsync](../../aspose.email.clients.pop3/pop3client/getmessageinfoasync#getmessageinfoasync_6)(IConnection, string, Pop3ListFields, CancellationToken) | Obtiene la información de ese mensaje |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_2)(int) | Obtiene el tamaño del mensaje |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_3)(string) | Obtiene el tamaño del mensaje |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize)(IConnection, int) | Obtiene el tamaño del mensaje |
| [GetMessageSize](../../aspose.email.clients.pop3/pop3client/getmessagesize#getmessagesize_1)(IConnection, string) | Obtiene el tamaño del mensaje |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_4)(int) | Obtiene el tamaño del mensaje |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_6)(string) | Obtiene el tamaño del mensaje |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync)(IConnection, int) | Obtiene el tamaño del mensaje |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_2)(IConnection, string) | Obtiene el tamaño del mensaje |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_5)(int, CancellationToken) | Obtiene el tamaño del mensaje |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_7)(string, CancellationToken) | Obtiene el tamaño del mensaje |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_1)(IConnection, int, CancellationToken) | Obtiene el tamaño del mensaje |
| [GetMessageSizeAsync](../../aspose.email.clients.pop3/pop3client/getmessagesizeasync#getmessagesizeasync_3)(IConnection, string, CancellationToken) | Obtiene el tamaño del mensaje |
| [GetMessageUniqueId](../../aspose.email.clients.pop3/pop3client/getmessageuniqueid#getmessageuniqueid_1)(int) | Obtiene el mensaje id único |
| [GetMessageUniqueId](../../aspose.email.clients.pop3/pop3client/getmessageuniqueid#getmessageuniqueid)(IConnection, int) | Obtiene el mensaje id único |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_2)(int) | Obtiene el mensaje id único |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync)(IConnection, int) | Obtiene el mensaje id único |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_3)(int, CancellationToken) | Obtiene el mensaje id único |
| [GetMessageUniqueIdAsync](../../aspose.email.clients.pop3/pop3client/getmessageuniqueidasync#getmessageuniqueidasync_1)(IConnection, int, CancellationToken) | Obtiene el mensaje id único |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages)() | Lista los mensajes. Obtiene información para buscar el mensaje |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_11)(bool) | Lista los mensajes. Obtiene información para buscar el mensaje |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_1)(IConnection) | Lista los mensajes. Obtiene información para buscar el mensaje |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_12)(IEnumerable&lt;int&gt;) | Lista los mensajes. Obtiene información para buscar el mensaje |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_13)(IEnumerable&lt;string&gt;) | Lista los mensajes. Obtiene información para buscar el mensaje |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_10)(MailQuery) | Lista los mensajes. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_8)(Pop3ListFields) | Lista los mensajes. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_5)(IConnection, bool) | Lista los mensajes. Obtiene información para buscar el mensaje |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_6)(IConnection, IEnumerable&lt;int&gt;) | Lista los mensajes. Obtiene información para buscar el mensaje |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_7)(IConnection, IEnumerable&lt;string&gt;) | Lista los mensajes. Obtiene información para buscar el mensaje |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_4)(IConnection, MailQuery) | Lista los mensajes. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_2)(IConnection, Pop3ListFields) | Lista los mensajes. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_9)(Pop3ListFields, bool, MailQuery) | Lista los mensajes. |
| [ListMessages](../../aspose.email.clients.pop3/pop3client/listmessages#listmessages_3)(IConnection, Pop3ListFields, bool, MailQuery) | Lista los mensajes. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync)() | Lista los mensajes. Obtiene información para buscar el mensaje |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_17)(bool) | Lista los mensajes. Obtiene información para buscar el mensaje |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_19)(CancellationToken) | Lista los mensajes. Obtiene información para buscar el mensaje |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_1)(IConnection) | Lista los mensajes. Obtiene información para buscar el mensaje |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_15)(MailQuery) | Lista los mensajes. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_11)(Pop3ListFields) | Lista los mensajes. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_18)(bool, CancellationToken) | Lista los mensajes. Obtiene información para buscar el mensaje |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_8)(IConnection, bool) | Lista los mensajes. Obtiene información para buscar el mensaje |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_10)(IConnection, CancellationToken) | Lista los mensajes. Obtiene información para buscar el mensaje |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_6)(IConnection, MailQuery) | Lista los mensajes. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_2)(IConnection, Pop3ListFields) | Lista los mensajes. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_16)(MailQuery, CancellationToken) | Lista los mensajes. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_14)(Pop3ListFields, CancellationToken) | Lista los mensajes. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_9)(IConnection, bool, CancellationToken) | Lista los mensajes. Obtiene información para buscar el mensaje |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_7)(IConnection, MailQuery, CancellationToken) | Lista los mensajes. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_5)(IConnection, Pop3ListFields, CancellationToken) | Lista los mensajes. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_12)(Pop3ListFields, bool, MailQuery) | Lista los mensajes. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_3)(IConnection, Pop3ListFields, bool, MailQuery) | Lista los mensajes. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_13)(Pop3ListFields, bool, MailQuery, CancellationToken) | Lista los mensajes. |
| [ListMessagesAsync](../../aspose.email.clients.pop3/pop3client/listmessagesasync#listmessagesasync_4)(IConnection, Pop3ListFields, bool, MailQuery, CancellationToken) | Lista los mensajes. |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_3)(IEnumerable&lt;int&gt;) | Carga la lista de Pop3MessageInfo |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_2)(IEnumerable&lt;Pop3MessageInfo&gt;) | Carga la lista de Pop3MessageInfo |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist_1)(IConnection, IEnumerable&lt;int&gt;) | Carga la lista de Pop3MessageInfo |
| [LoadMessageInfoList](../../aspose.email.clients.pop3/pop3client/loadmessageinfolist#loadmessageinfolist)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;) | Carga la lista de Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_7)(IEnumerable&lt;int&gt;) | Carga la lista de Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_5)(IEnumerable&lt;Pop3MessageInfo&gt;) | Carga la lista de Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_4)(Pop3LoadMessageInfoList) | Carga la lista de Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_2)(IConnection, IEnumerable&lt;int&gt;) | Carga la lista de Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;) | Carga la lista de Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_8)(IEnumerable&lt;int&gt;, CancellationToken) | Carga la lista de Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_6)(IEnumerable&lt;Pop3MessageInfo&gt;, CancellationToken) | Carga la lista de Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_3)(IConnection, IEnumerable&lt;int&gt;, CancellationToken) | Carga la lista de Pop3MessageInfo |
| [LoadMessageInfoListAsync](../../aspose.email.clients.pop3/pop3client/loadmessageinfolistasync#loadmessageinfolistasync_1)(IConnection, IEnumerable&lt;Pop3MessageInfo&gt;, CancellationToken) | Carga la lista de Pop3MessageInfo |
| override [Noop](../../aspose.email.clients.pop3/pop3client/noop#noop)() | Comando 'Sin operación' |
| override [Noop](../../aspose.email.clients.pop3/pop3client/noop#noop_1)(IConnection) | Comando 'Sin operación' |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync)() | Comando 'Sin operación' |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_3)(CancellationToken) | Comando 'Sin operación' |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_1)(IConnection) | Comando 'Sin operación' |
| [NoopAsync](../../aspose.email.clients.pop3/pop3client/noopasync#noopasync_2)(IConnection, CancellationToken) | Comando 'Sin operación' |
| [ResetLogSettings](../../aspose.email.clients/emailclient/resetlogsettings)() | Restablece la configuración de registro a los valores predeterminados. |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_4)(int, Stream) | Obtiene y guarda el mensaje como flujo |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_5)(int, string) | Obtiene y guarda el mensaje en un archivo |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_6)(string, Stream) | Obtiene y guarda el mensaje como flujo |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_7)(string, string) | Obtiene y guarda el mensaje en un archivo |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage)(IConnection, int, Stream) | Obtiene y guarda el mensaje como flujo |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_1)(IConnection, int, string) | Obtiene y guarda el mensaje en un archivo |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_2)(IConnection, string, Stream) | Obtiene y guarda el mensaje como flujo |
| [SaveMessage](../../aspose.email.clients.pop3/pop3client/savemessage#savemessage_3)(IConnection, string, string) | Obtiene y guarda el mensaje en un archivo |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_8)(int, Stream) | Obtiene y guarda el mensaje como flujo |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_10)(int, string) | Obtiene y guarda el mensaje en un archivo |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_12)(string, Stream) | Obtiene y guarda el mensaje como flujo |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_14)(string, string) | Obtiene y guarda el mensaje en un archivo |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync)(IConnection, int, Stream) | Obtiene y guarda el mensaje como flujo |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_2)(IConnection, int, string) | Obtiene y guarda el mensaje en un archivo |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_4)(IConnection, string, Stream) | Obtiene y guarda el mensaje como flujo |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_6)(IConnection, string, string) | Obtiene y guarda el mensaje en un archivo |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_9)(int, Stream, CancellationToken) | Obtiene y guarda el mensaje como flujo |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_11)(int, string, CancellationToken) | Obtiene y guarda el mensaje en un archivo |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_13)(string, Stream, CancellationToken) | Obtiene y guarda el mensaje como flujo |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_15)(string, string, CancellationToken) | Obtiene y guarda el mensaje en un archivo |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_1)(IConnection, int, Stream, CancellationToken) | Obtiene y guarda el mensaje como flujo |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_3)(IConnection, int, string, CancellationToken) | Obtiene y guarda el mensaje en un archivo |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_5)(IConnection, string, Stream, CancellationToken) | Obtiene y guarda el mensaje como flujo |
| [SaveMessageAsync](../../aspose.email.clients.pop3/pop3client/savemessageasync#savemessageasync_7)(IConnection, string, string, CancellationToken) | Obtiene y guarda el mensaje en un archivo |
| [SetSupportedEncryptionUnsafe](../../aspose.email.clients/emailclient/setsupportedencryptionunsafe)(EncryptionProtocols) | Define las versiones de los protocolos de encriptación SSL/TLS que se utilizarán. Este método no es seguro y establece los protocolos de encriptación sin ninguna verificación de compatibilidad. Usar[`SupportedEncryption`](../../aspose.email.clients/emailclient/supportedencryption) propiedad para configurar de forma segura solo los protocolos que definitivamente son compatibles con .net framework. Tenga en cuenta que si su actual .net framework no admite este nivel de seguridad, se generará una excepción al intentar establecer una conexión con el servidor. |
| [UndeleteMessages](../../aspose.email.clients.pop3/pop3client/undeletemessages#undeletemessages)() | Recupera los mensajes. Si el servidor POP3 marcó algún mensaje como eliminado, se desmarcará. |
| [UndeleteMessages](../../aspose.email.clients.pop3/pop3client/undeletemessages#undeletemessages_1)(IConnection) | Recupera los mensajes. Si el servidor POP3 marcó algún mensaje como eliminado, se desmarcará. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync)() | Recupera los mensajes. Si el servidor POP3 marcó algún mensaje como eliminado, se desmarcará. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_3)(CancellationToken) | Recupera los mensajes. Si el servidor POP3 marcó algún mensaje como eliminado, se desmarcará. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_1)(IConnection) | Recupera los mensajes. Si el servidor POP3 marcó algún mensaje como eliminado, se desmarcará. |
| [UndeleteMessagesAsync](../../aspose.email.clients.pop3/pop3client/undeletemessagesasync#undeletemessagesasync_2)(IConnection, CancellationToken) | Recupera los mensajes. Si el servidor POP3 marcó algún mensaje como eliminado, se desmarcará. |
| override [ValidateCredentials](../../aspose.email.clients.pop3/pop3client/validatecredentials#validatecredentials)() | Ejecuta validación de credenciales |
| [ValidateCredentials](../../aspose.email.clients.pop3/pop3client/validatecredentials#validatecredentials_1)(IConnection) | Ejecuta validación de credenciales |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync)() | Ejecuta validación de credenciales |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_3)(CancellationToken) | Ejecuta validación de credenciales |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_1)(IConnection) | Ejecuta validación de credenciales |
| [ValidateCredentialsAsync](../../aspose.email.clients.pop3/pop3client/validatecredentialsasync#validatecredentialsasync_2)(IConnection, CancellationToken) | Ejecuta validación de credenciales |
| static [CreateAsync](../../aspose.email.clients.pop3/pop3client/createasync)(string, string, IAsyncTokenProvider, int, SecurityOptions, CancellationToken) | Crea una nueva instancia del[`Pop3Client`](../pop3client) clase |

### Ver también

* class [EmailClient](../../aspose.email.clients/emailclient)
* interface [IAsyncPop3Client](../iasyncpop3client)
* espacio de nombres [Aspose.Email.Clients.Pop3](../../aspose.email.clients.pop3)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
