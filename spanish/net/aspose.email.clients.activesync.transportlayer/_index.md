---
title: Aspose.Email.Clients.ActiveSync.TransportLayer
second_title: Referencia de la API de Aspose.Email para .NET
description: 
type: docs
weight: 80
url: /es/net/aspose.email.clients.activesync.transportlayer/
---


## Clases

| Clase | Descripción |
| --- | --- |
| [AccountInformation](./accountinformation) | Contiene la información de la cuenta del usuario. |
| [ActiveSyncTLClient](./activesynctlclient) | Clase básica para implementaciones de clientes ActiveSync |
| [AutodiscoverResult](./autodiscoverresult) | Resultado de la operación de detección automática |
| [Body](./body) | Especifica un campo de datos de longitud variable y formato libre asociado con un elemento almacenado en el servidor. |
| [BodyPart](./bodypart) | Especifica detalles sobre la parte del mensaje de un correo electrónico en una respuesta. El elemento BodyPart DEBE incluirse en una respuesta de comando cuando se especifica BodyPartPreference en una solicitud. |
| [BodyPreference](./bodypreference) | Contiene información de preferencia relacionada con el tipo y el tamaño de la información que se devuelve al buscar, sincronizar o recuperar. |
| [CertificateStatuses](./certificatestatuses) | Indica si el certificado fue validado con éxito. |
| [DataContainer](./datacontainer) | Contiene datos para un objeto en particular, como un contacto, mensaje de correo electrónico, cita de calendario o elemento de tarea. El DataContainer se puede usar para cambiar elementos, agregar elementos o recuperar elementos en el servidor o dispositivo cliente. |
| [DeviceInformation](./deviceinformation) | Solicitud que se utiliza para enviar las propiedades del dispositivo cliente al servidor. |
| [DevicePasswordRequest](./devicepasswordrequest) | Especifica la solicitud para establecer la contraseña de recuperación del dispositivo cliente por parte del servidor. Para borrar una contraseña de recuperación existente, el cliente DEBE enviar una contraseña vacía. |
| [EASProvisionDoc](./easprovisiondoc) | Especifica la colección de configuraciones de seguridad para el aprovisionamiento de dispositivos. |
| [EmptyFolderContentsRequest](./emptyfoldercontentsrequest) | Contiene una solicitud sobre la eliminación del contenido de una carpeta. EmptyFolderContents admite un único elemento secundario del elemento Opciones, DeleteSubFolders, que determina si se eliminan las subcarpetas contenidas en la carpeta. Si la opción DeleteSubFolders no está incluida en la solicitud, las subcarpetas del CollectionId especificado no se eliminan. |
| [FolderInfo](./folderinfo) | La clase FolderInfo contiene información de la carpeta |
| [FolderSyncResult](./foldersyncresult) | Contiene cambios en la jerarquía de carpetas. |
| [ItemEstimate](./itemestimate) | Contiene una evaluación sobre la carpeta solicitada |
| [ItemEstimateOptions](./itemestimateoptions) | Contiene elementos que filtran los resultados de la operación GetItemEstimate. |
| [ItemEstimateRequest](./itemestimaterequest) | Contiene parámetros de solicitud de ItemEstimate |
| [ItemOperationsEmptFldrCntntsResponce](./itemoperationsemptfldrcntntsresponce) | Identifica el cuerpo de la respuesta que contiene la operación que elimina el contenido de una carpeta. |
| [ItemOperationsFetchProperties](./itemoperationsfetchproperties) | Contiene las propiedades que se devuelven para los elementos en la respuesta. |
| [ItemOperationsFetchRequest](./itemoperationsfetchrequest) | Contiene una solicitud sobre la recuperación de un elemento del servidor. |
| [ItemOperationsFetchResponce](./itemoperationsfetchresponce) | Contiene una respuesta sobre la recuperación de elementos del servidor. |
| [ItemOperationsMoveRequest](./itemoperationsmoverequest) | Contiene una solicitud sobre cómo mover una conversación a una carpeta específica. |
| [ItemOperationsMoveResponce](./itemoperationsmoveresponce) | Identifica el cuerpo de la respuesta que contiene la operación que mueve una conversación determinada. |
| [ItemOperationsRequest](./itemoperationsrequest) | Contiene la solicitud ItemOperations. |
| [ItemOperationsResponse](./itemoperationsresponse) | Contiene la respuesta ItemOperations. |
| [ItOpEmpFldCntOptions](./itopempfldcntoptions) | Contiene las opciones para la operación ItemOperations.EmptyFolderContents |
| [ItOpFetchOptions](./itopfetchoptions) | Contiene las opciones para la operación ItemOperations.Fetch. |
| [ItOpMoveOptions](./itopmoveoptions) | Contiene las opciones para la operación ItemOperations.Move. |
| [MeetingResponseRequest](./meetingresponserequest) | Especifica la solicitud de reunión a la que se está respondiendo, la respuesta a esa solicitud de reunión y la carpeta en el servidor en la que se encuentra la solicitud de reunión. |
| [MeetingResponseResult](./meetingresponseresult) | Objeto de resultado de respuesta de reunión |
| [MoveItemData](./moveitemdata) | Contiene información sobre el movimiento de elementos |
| [MoveItemResponse](./moveitemresponse) | Contiene información que describe los elementos movidos. |
| [OOFMessage](./oofmessage) | Especifica el mensaje OOF para una audiencia en particular. Exchange 2007, Exchange 2010 y Exchange 2013 requieren que el mensaje de respuesta para audiencias externas conocidas y desconocidas sea el mismo. La propiedad admite las siguientes tres audiencias para un mensaje OOF: Interno: un usuario que está en la misma organización que el usuario que envía. Externo conocido: un usuario que está fuera de la organización del usuario que envía, pero que está representado en los contactos del usuario que envía. Externo desconocido: un usuario que está fuera de la organización del usuario que envía. organización y no está representada en los contactos del usuario remitente. |
| [OOFReqParametrs](./oofreqparametrs) | Obtiene la configuración de información OOF del servidor. |
| [OOFRequest](./oofrequest) | Especifica una clase para recuperar y configurar la información Fuera de la oficina (OOF). |
| [OOFResponse](./oofresponse) | Especifica una clase para recuperar y configurar la información Fuera de la oficina (OOF). |
| [OOFSettings](./oofsettings) | Configuración de información OOF. |
| [PictureRequest](./picturerequest) | Indica que el cliente está solicitando que se devuelvan fotos en la respuesta del servidor. La imagen no es compatible cuando la versión del protocolo es 12.1 o 14.0. Contiene los datos relacionados con la solicitud de fotos. |
| [PictureRespose](./picturerespose) | Contiene los datos relacionados con las fotos de contacto. La imagen no es compatible cuando la versión del protocolo es 12.1 o 14.0. |
| [PingParameter](./pingparameter) | Contiene los parámetros del comando ping |
| [ProvisionPolicy](./provisionpolicy) | Especifica una política de seguridad. |
| [ProvisionPolicyData](./provisionpolicydata) | Especifica la configuración de una política. |
| [ProvisionRequest](./provisionrequest) | Contiene información de solicitud para el comando de provisión |
| [ProvisionResponse](./provisionresponse) | Contiene información de respuesta para el comando de provisión |
| [QueryType](./querytype) | Especifica las palabras clave que se usarán para hacer coincidir las entradas en la tienda que se está buscando. El valor de Query se usa como un patrón de coincidencia de cadena de prefijo y devuelve entradas que coinciden con el comienzo de la cadena. Por ejemplo, la búsqueda de "John" coincidiría con "John Frum" o "Barry Johnson", pero no con "James Littlejohn". Todas las propiedades de texto no vacías en la GAL que se indexan mediante ANR se comparan con el elemento Query valor. Las comparaciones de búsqueda se realizan mediante coincidencias que no distinguen entre mayúsculas y minúsculas. Para una búsqueda en la biblioteca de documentos de Windows SharePoint Services, este protocolo admite consultas de la siguiente forma: LinkId == valor, donde valor especifica la URL del elemento o carpeta y LinkId indica que el valor debe compararse con la propiedad de ID de enlace. Para la búsqueda de buzón, la sintaxis de consulta es la siguiente: - Las carpetas se pueden especificar de las siguientes maneras: ID especificado Carpeta y subcarpetas especificadas Todas las carpetas de correo electrónico, incluido Borrador, Bandeja de entrada y subcarpetas, Bandeja de salida y Elementos enviados : la consulta de palabra clave básica puede estar compuesta por lo siguiente: El operador básico: Y (sección 2.2.3.10) Un filtro de fecha y hora especificado mediante GreaterThan (sección 2.2.3.78) y LessThan elementos (sección 2.2.3.87) Elementos de texto libre (sección 2.2.3.73) que contienen palabras clave La consulta básica de palabras clave se ejecuta en todas las propiedades indexadas. |
| [Recipient](./recipient) | Representa un único destinatario que se ha resuelto. |
| [ResolveRecipientsAvailabilityRequest](./resolverecipientsavailabilityrequest) | Indica al servidor que el cliente está solicitando datos de disponibilidad e identifica la hora de inicio y finalización de los datos de disponibilidad para recuperar. La disponibilidad no es compatible cuando la versión del protocolo es 12.1. |
| [ResolveRecipientsAvailabilityResponse](./resolverecipientsavailabilityresponse) | Identifica el estado y los datos de disponibilidad de los usuarios o listas de distribución identificados en la solicitud para el tiempo identificado por StartTime y EndTime. Cuando se incluye la Disponibilidad en una solicitud de ResolveRecipients, el servidor recupera información de disponibilidad para los usuarios identificados en los elementos Para incluidos en la solicitud y devuelve la información de disponibilidad en MergedFreeBusy en la respuesta. Cuando el servidor analiza la solicitud, primero resuelve los destinatarios identificados por los elementos Para y luego determina la información de disponibilidad de los usuarios para el período de tiempo especificado, antes de devolver los datos de disponibilidad en MergedFreeBusy. |
| [ResolveRecipientsCertificates](./resolverecipientscertificates) | Contiene información sobre los certificados de un destinatario. |
| [ResolveRecipientsOptions](./resolverecipientsoptions) | Contiene las opciones para resolver la lista de destinatarios. |
| [ResolveRecipientsRequest](./resolverecipientsrequest) | Contiene información para resolver destinatarios. |
| [ResolveRecipientsResponse](./resolverecipientsresponse) | Contiene información sobre si se resolvió el destinatario. Si el destinatario se resolvió, también contiene el tipo de destinatario, la dirección de correo electrónico a la que se resolvió el destinatario y, opcionalmente, el certificado S/MIME para el destinatario. |
| [RightsManagementInformationResponce](./rightsmanagementinformationresponce) | Contiene la configuración de información de administración de derechos recuperada del servidor. |
| [RightsManagementLicense](./rightsmanagementlicense) | Contiene la configuración de la plantilla de política de derechos para la plantilla aplicada al mensaje de correo electrónico que se está sincronizando. |
| [RightsManagementTemplate](./rightsmanagementtemplate) | Contiene el identificador de plantilla, el nombre y la descripción de una plantilla de política de derechos disponible en el cliente. |
| [SearchCondition](./searchcondition) | Especifica una condición para las solicitudes de búsqueda |
| [SearchOptions](./searchoptions) | Contiene las opciones de búsqueda. El nombre de usuario y la contraseña solo se pueden enviar en la solicitud después de recibir un valor de estado de 14. El servidor requiere estas credenciales para acceder a los recursos solicitados. El cliente DEBE enviarlos únicamente a través de una conexión segura o confiable, y solo en respuesta a un valor de Estado de 14. Las opciones admitidas varían según la tienda que se busca. La siguiente tabla enumera las opciones válidas para cada tienda. GAL: rango, nombre de usuario, contraseña, imagen Buzón: rango, recorrido profundo, resultados de reconstrucción, BodyPreference, BodyPartPreference, RightsManagementSupport DocumentLibrary: rango, nombre de usuario, contraseña BodyPartPreference solo es válido en la búsqueda solicitudes de comando que incluyen un ConversationId. |
| [SearchQuery](./searchquery) | Especifica las palabras clave que se usarán para hacer coincidir las entradas en la tienda que se está buscando. El valor de Query se usa como un patrón de coincidencia de cadena de prefijo y devuelve entradas que coinciden con el comienzo de la cadena. Por ejemplo, la búsqueda de "John" coincidiría con "John Frum" o "Barry Johnson", pero no con "James Littlejohn". Todas las propiedades de texto no vacías en la GAL que se indexan mediante ANR se comparan con el elemento Query valor. Las comparaciones de búsqueda se realizan mediante coincidencias que no distinguen entre mayúsculas y minúsculas. Para una búsqueda en la biblioteca de documentos de Windows SharePoint Services, este protocolo admite consultas de la siguiente forma: LinkId == valor, donde valor especifica la URL del elemento o carpeta y LinkId indica que el valor debe compararse con la propiedad de ID de enlace. Para la búsqueda de buzón, la sintaxis de consulta es la siguiente: - Las carpetas se pueden especificar de las siguientes maneras: ID especificado Carpeta y subcarpetas especificadas Todas las carpetas de correo electrónico, incluido Borrador, Bandeja de entrada y subcarpetas, Bandeja de salida y Elementos enviados : la consulta de palabra clave básica puede estar compuesta por lo siguiente: El operador básico: Y (sección 2.2.3.10) Un filtro de fecha y hora especificado mediante GreaterThan (sección 2.2.3.78) y LessThan elementos (sección 2.2.3.87) Elementos de texto libre (sección 2.2.3.73) que contienen palabras clave La consulta básica de palabras clave se ejecuta en todas las propiedades indexadas. |
| [SearchRequest](./searchrequest) | Contiene información de solicitud de búsqueda |
| [SearchRequestStore](./searchrequeststore) | Especifique el nombre, consulta y opciones para la búsqueda. |
| [SearchResponse](./searchresponse) | Contiene información de respuesta de búsqueda |
| [SearchResponseStore](./searchresponsestore) | Contiene los elementos Estado, Resultado, Rango y Total de las entradas de buzón devueltas. |
| [SearchResult](./searchresult) | Contenedor para un elemento de buzón coincidente individual. Cuando el almacén que se busca es el buzón: - Hay un elemento de resultado para cada coincidencia que se encuentra en el buzón. Si no se encuentran coincidencias, un elemento de resultado vacío está presente en el elemento contenedor de la tienda del XML de respuesta. : dentro del elemento de resultado, el elemento de propiedades contiene una lista de propiedades solicitadas para el elemento del buzón. Cuando la tienda que está lo que se busca es la biblioteca de documentos: : el primer resultado que se devuelve en la respuesta de búsqueda son los metadatos de la carpeta raíz o el elemento al que apunta el valor LinkId. El cliente puede elegir ignorar esta entrada si no la requiere. - Si el valor del elemento documentlibrary:LinkId en la solicitud apunta a una carpeta, las propiedades de metadatos de la carpeta se devuelven como el primer elemento y el contenido de la carpeta se devuelven como resultados posteriores. El rango se aplica a estos resultados sin diferencia; por ejemplo, el índice 0 siempre sería para el elemento raíz al que apunta el enlace. : si el valor del elemento documentlibrary:LinkId en la solicitud apunta a un elemento, solo se devuelve un resultado: los metadatos del elemento. - Dentro del elemento Resultado, el elemento Propiedades contiene una lista de propiedades solicitadas para el elemento del buzón. |
| [SearchResultProperties](./searchresultproperties) | Las propiedades de respuesta del comando de búsqueda son un contenedor de propiedades que se aplican a una entrada individual que coincide con la cadena de búsqueda del elemento de consulta. Por ejemplo, el elemento Propiedades contiene un elemento para cada propiedad GAL no vacía con valor de texto que se adjunta a la entrada GAL coincidente. Solo se devuelven aquellas propiedades que están adjuntas a la entrada GAL específica; por lo tanto, se pueden devolver diferentes conjuntos de propiedades en el XML de respuesta para diferentes entradas de GAL coincidentes. Cada elemento en el contenedor de propiedades tiene como ámbito el espacio de nombres apropiado que se especifica en el elemento de búsqueda de nivel superior. |
| [ServerInfo](./serverinfo) | Configuración del servidor en la operación de detección automática |
| [SettingsRequest](./settingsrequest) | El comando Configuración admite operaciones de obtención y configuración en propiedades globales y configuraciones Fuera de la oficina (OOF) para el usuario. El comando Configuración también envía información del dispositivo al servidor, implementa la recuperación de la contraseña/número de identificación personal (PIN) del dispositivo y recupera una lista de las direcciones de correo electrónico del usuario. |
| [SettingsResponse](./settingsresponse) | Especifica una respuesta con la configuración Fuera de la oficina (OOF) y una lista de las cuentas del usuario. |
| [SmartRequest](./smartrequest) | Contiene información de solicitud inteligente |
| [SmartRequestSource](./smartrequestsource) | Contiene información sobre el mensaje de origen. |
| [Status](./status) | Indica el resultado de una operación. |
| [SyncAddClientOperation](./syncaddclientoperation) | Crea un nuevo objeto en una colección en el cliente. |
| [SyncAddResponse](./syncaddresponse) | Sirve para indicar que se debe crear un nuevo objeto en una colección. |
| [SyncAddServerOperation](./syncaddserveroperation) | Crea un nuevo objeto en una colección en el servidor. |
| [SyncChangeClientOperation](./syncchangeclientoperation) | Contiene propiedades de un objeto existente en el dispositivo cliente que se modificaron. El objeto modificado se identifica por su elemento ServerId. |
| [SyncChangeResponse](./syncchangeresponse) | Sirve para Indicar que un objeto ha sido modificado. |
| [SyncChangeServerOperation](./syncchangeserveroperation) | Contiene propiedades de un objeto existente en el servidor que se modificaron. El objeto modificado se identifica por su elemento ServerId. |
| [SyncCollectionRequest](./synccollectionrequest) | La clase contiene comandos y opciones que se aplican a una colección en particular. |
| [SyncCollectionResponse](./synccollectionresponse) | La clase contiene comandos y opciones que se aplican a una respuesta de sincronización. |
| [SyncCommandsRequest](./synccommandsrequest) | Contiene operaciones que se aplican a una colección. Las operaciones disponibles son Add, Delete, Change, Fetch y SoftDelete. |
| [SyncCommandsResponse](./synccommandsresponse) | Contiene operaciones que se aplican a una colección. Las operaciones disponibles son Add, Delete, Change, Fetch y SoftDelete. |
| [SyncDeleteClientOperation](./syncdeleteclientoperation) | Elimina un objeto en el dispositivo cliente o el servidor. El objeto se identifica por su ServerId. |
| [SyncFetchResponse](./syncfetchresponse) | Solicita los datos de la aplicación de un elemento que se truncó en una respuesta de sincronización del servidor. |
| [SyncOperationResponse](./syncoperationresponse) | Clase abstracta base para respuestas de operación de sincronización |
| [SyncOperationsResponse](./syncoperationsresponse) | Contiene respuestas a operaciones como Agregar, Obtener, Cambiar que son procesadas por el servidor. La respuesta contiene un código de estado y otra información, según la operación. |
| [SyncOptions](./syncoptions) | Especifica opciones que controlan ciertos aspectos de cómo se realiza la sincronización. |
| [SyncRequest](./syncrequest) | Contiene parámetros de solicitud de sincronización |
| [UserInformationResponse](./userinformationresponse) | Contiene el estado de la solicitud y una lista de la información de la cuenta de un usuario (direcciones de correo electrónico). |
| [ValueConverter](./valueconverter) | La clase convierte la versión del protocolo ActiveSync de representación de cadena a enumeración y viceversa. |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IActiveSyncTLClient](./iactivesynctlclient) | Interfaz de cliente de ActiveSync |
| [IBaseActiveSyncTLClient](./ibaseactivesynctlclient) | Interfaz de cliente Base ActiveSync |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [ActiveSyncAuthenticationType](./activesyncauthenticationtype) | Enum especifica el tipo de autenticación |
| [AirSync](./airsync) | Espacio de nombres AirSync del protocolo ActiveSync |
| [AirSyncBase](./airsyncbase) | Espacio de nombres AirSyncBase del protocolo ActiveSync |
| [AirsyncClass](./airsyncclass) | Identifica la clase del elemento. Las siguientes clases son compatibles con las búsquedas en buzones cuando la versión del protocolo es 12.1: - Correo electrónico - Calendario - Contactos - Tareas Las clases SMS y Notas solo están disponibles si la versión del protocolo es 14.0 o 14.1. |
| [AirsyncFilterType](./airsyncfiltertype) | Especifica una ventana de tiempo opcional para los objetos |
| [AllowBluetooth](./allowbluetooth) | Especifica el uso de Bluetooth en el dispositivo. |
| [ASProtocolVersions](./asprotocolversions) | ASProtocolVersions indica las versiones del protocolo ActiveSync. |
| [BehaviorReplacement](./behaviorreplacement) | Especifica cómo resolver el conflicto que ocurre cuando se cambia un objeto tanto en el cliente como en el servidor. El valor especifica qué objeto (el objeto del cliente o el objeto del servidor) conservar si hay un conflicto. |
| [BodyType](./bodytype) | Especifica el tipo de formato del contenido del cuerpo del elemento. |
| [Calendar](./calendar) | Espacio de nombres de calendario del protocolo ActiveSync |
| [CertificateRetrieval](./certificateretrieval) | Especifica si el servidor DEBERÍA devolver los certificados S/MIME para cada destinatario resuelto. |
| [CommandCodes](./commandcodes) | La siguiente tabla proporciona los códigos numéricos que corresponden a los comandos de ActiveSync. El código numérico se utiliza en el campo Código de comando del URI codificado en base64 para especificar el comando. |
| [CommandParameters](./commandparameters) | Parámetros del comando. |
| [ComposeMail](./composemail) | Espacio de nombres ComposeMail del protocolo ActiveSync |
| [Contacts](./contacts) | Espacio de nombres de contactos del protocolo ActiveSync |
| [Contacts2](./contacts2) | Espacio de nombres Contacts2 del protocolo ActiveSync |
| [DocumentLibrary](./documentlibrary) | Espacio de nombres DocumentLibrary del protocolo ActiveSync |
| [Email](./email) | Espacio de nombres de correo electrónico del protocolo ActiveSync |
| [Email2](./email2) | Espacio de nombres Email2 del protocolo ActiveSync |
| [EncryptionSMIMEAlgorithm](./encryptionsmimealgorithm) | Especifica el algoritmo utilizado al cifrar mensajes S/MIME. |
| [FolderClass](./folderclass) | Especifica la clase de contenido de la carpeta a monitorear. |
| [FolderHierarchy](./folderhierarchy) | Espacio de nombres de jerarquía de carpetas del protocolo ActiveSync |
| [FolderTypes](./foldertypes) | Especifica el tipo de carpeta que se actualizó (renombró o movió) o agregó en el servidor. |
| [GAL](./gal) | Espacio de nombres GAL del protocolo ActiveSync |
| [GetItemEstimate](./getitemestimate) | Espacio de nombres GetItemEstimate del protocolo ActiveSync |
| [ItemOperations](./itemoperations) | ItemOperations espacio de nombres del protocolo ActiveSync |
| [MaxAgeFilter](./maxagefilter) | Especifica el número máximo de días naturales que se pueden sincronizar. |
| [MeetingResponse](./meetingresponse) | Espacio de nombres MeetingResponse del protocolo ActiveSync |
| [MergedFreeBusy](./mergedfreebusy) | Especifica la información de disponibilidad para los usuarios o la lista de distribución. |
| [MIMESupport](./mimesupport) | Habilita la compatibilidad con MIME para elementos de correo electrónico que se envían desde el servidor al cliente. |
| [MIMETruncation](./mimetruncation) | Especifica si los datos MIME del elemento de correo electrónico DEBERÍAN truncarse cuando se envía desde el servidor al cliente. |
| [MinDevicePasswordComplexCharacters](./mindevicepasswordcomplexcharacters) | Especifica el nivel requerido de complejidad de la contraseña del cliente. Por ejemplo: Si el valor de MinDevicePasswordComplexCharacters es 2, una contraseña con caracteres alfabéticos en mayúsculas y minúsculas sería suficiente, al igual que una contraseña con caracteres alfabéticos en minúsculas y números. |
| [Move](./move) | Mover espacio de nombres del protocolo ActiveSync |
| [Namespace](./namespace) | Páginas de códigos ActiveSync |
| [Notes](./notes) | Espacio de nombres de notas del protocolo ActiveSync |
| [OofState](./oofstate) | Especifica la disponibilidad de la propiedad Oof. |
| [Ping](./ping) | Espacio de nombres de ping del protocolo ActiveSync |
| [Provision](./provision) | Aprovisionar espacio de nombres del protocolo ActiveSync |
| [ProvisionPolicyStatuses](./provisionpolicystatuses) | El valor indica el éxito o el fracaso del cliente al aplicar la configuración de directiva recuperada del servidor. |
| [ProvisionRemoteWipeStatuses](./provisionremotewipestatuses) | El valor indica el éxito o el fracaso de una operación de borrado remoto en el cliente. |
| [RecipientType](./recipienttype) | Indica el tipo de destinatario. |
| [ResolveRecipients](./resolverecipients) | Espacio de nombres ResolveRecipients del protocolo ActiveSync |
| [RightsManagement](./rightsmanagement) | Espacio de nombres RightsManagement del protocolo ActiveSync |
| [Search](./search) | Espacio de nombres de búsqueda del protocolo ActiveSync |
| [ServerType](./servertype) | Especifica el tipo de servidor |
| [Settings](./settings) | Configuración del espacio de nombres del protocolo ActiveSync |
| [SignedSMIMEAlgorithm](./signedsmimealgorithm) | Especifica el algoritmo utilizado al firmar mensajes S/MIME. |
| [SMIMEEncryptionAlgorithmNegotiation](./smimeencryptionalgorithmnegotiation) | Controla la negociación del algoritmo de cifrado. |
| [StoreType](./storetype) | Contiene información que especifica la ubicación, para las operaciones. |
| [Tasks](./tasks) | Espacio de nombres de tareas del protocolo ActiveSync |
| [UserCreatedFolderTypes](./usercreatedfoldertypes) | Especifica el tipo de carpeta que se creará. |
| [UserResponse](./userresponse) | Indica si la reunión está siendo aceptada, tentativamente aceptada o rechazada. |
| [ValidateCert](./validatecert) | Espacio de nombres ValidateCert del protocolo ActiveSync |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
