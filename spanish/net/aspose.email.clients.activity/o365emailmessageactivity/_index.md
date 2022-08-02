---
title: O365EmailMessageActivity
second_title: Referencia de la API de Aspose.Email para .NET
description: Amplía el esquema común con las propiedades específicas de los datos de Office 365 Advanced Threat Protection e Threat Intelligence. Los eventos de Office 365 Advanced Threat Protection ATP y Threat Intelligence están disponibles para los clientes de Office 365 que tienen una suscripción ATP Threat Intelligence o E5 . Cada evento en el feed de ATP e Threat Intelligence corresponde a Un mensaje de correo electrónico enviado o recibido por un usuario en la organización con detecciones realizadas en los mensajes en el momento de la entrega y desde la purga automática de hora cero.
type: docs
weight: 2660
url: /es/net/aspose.email.clients.activity/o365emailmessageactivity/
---
## O365EmailMessageActivity class

Amplía el esquema común con las propiedades específicas de los datos de Office 365 Advanced Threat Protection e Threat Intelligence. Los eventos de Office 365 Advanced Threat Protection (ATP) y Threat Intelligence están disponibles para los clientes de Office 365 que tienen una suscripción ATP, Threat Intelligence o E5 . Cada evento en el feed de ATP e Threat Intelligence corresponde a Un mensaje de correo electrónico enviado o recibido por un usuario en la organización con detecciones realizadas en los mensajes en el momento de la entrega y desde la purga automática de hora cero.

```csharp
public class O365EmailMessageActivity : Content
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [O365EmailMessageActivity](o365emailmessageactivity)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AttachmentData](../../aspose.email.clients.activity/o365emailmessageactivity/attachmentdata) { get; set; } | Datos sobre archivos adjuntos en el mensaje de correo electrónico que desencadenó el evento. Obligatorio: No |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | La dirección IP del dispositivo que se usó cuando se registró la actividad. La dirección IP se muestra en formato de dirección IPv4 o IPv6. Obligatorio: Sí |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | La fecha y hora en Tiempo Universal Coordinado (UTC) cuando el usuario realizó la actividad. Obligatorio: Sí |
| [DetectionMethod](../../aspose.email.clients.activity/o365emailmessageactivity/detectionmethod) { get; set; } | El método o la tecnología utilizada por Office 365 ATP para la detección. Obligatorio: Sí |
| [DetectionType](../../aspose.email.clients.activity/o365emailmessageactivity/detectiontype) { get; set; } | El tipo de detección. Obligatorio: Sí |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | Identificador único de un registro de auditoría. Obligatorio: Sí |
| [InternetMessageId](../../aspose.email.clients.activity/o365emailmessageactivity/internetmessageid) { get; set; } | El Id. de mensaje de Internet. Obligatorio: Sí |
| [NetworkMessageId](../../aspose.email.clients.activity/o365emailmessageactivity/networkmessageid) { get; set; } | Id. de mensaje de red de Exchange Online. Obligatorio: Sí |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | Para la actividad de SharePoint y OneDrive para empresas, el nombre completo de la ruta de acceso del archivo o carpeta al que accede el usuario. Para el registro de auditoría de administración de Exchange, el nombre del objeto que modificó el cmdlet. Obligatorio: No |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | El nombre del usuario o actividad de administrador. Para obtener una descripción de las operaciones/actividades más comunes, consulte Buscar en el registro de auditoría en el Centro de protección de Office 365. Para la actividad de administración de Exchange, esta propiedad identifica el nombre del cmdlet que se ejecutó. Para eventos DLP, puede ser "DlpRuleMatch", "DlpRuleUndo" o "DlpInfo", que se describen en "Esquema DLP" a continuación. Obligatorio: Sí |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | El GUID del inquilino de Office 365 de su organización. Este valor siempre será el mismo para su organización, independientemente del servicio de Office 365 en el que se produzca. Obligatorio: Sí |
| [P1Sender](../../aspose.email.clients.activity/o365emailmessageactivity/p1sender) { get; set; } | La ruta de retorno del remitente del mensaje de correo electrónico. Obligatorio: Sí |
| [P2Sender](../../aspose.email.clients.activity/o365emailmessageactivity/p2sender) { get; set; } | El remitente del mensaje de correo electrónico. Obligatorio: Sí |
| [Recipients](../../aspose.email.clients.activity/o365emailmessageactivity/recipients) { get; set; } | Una matriz de destinatarios del mensaje de correo electrónico. Obligatorio: Sí |
| [RecordType](../../aspose.email.clients.activity/content/recordtype) { get; set; } | El tipo de operación que indica el registro. Obligatorio: Sí |
| [ResultStatus](../../aspose.email.clients.activity/content/resultstatus) { get; set; } | Indica si la acción (especificada en la propiedad Operación) fue exitosa o no. Los valores posibles son Correcto, Parcialmente exitoso o Error. Para la actividad de administración de Exchange, el valor es Verdadero o Falso. Obligatorio: No |
| [Scope](../../aspose.email.clients.activity/content/scope) { get; set; } | ¿Este evento fue creado por un servicio O365 alojado o un servidor local? Los valores posibles son online y onprem. Tenga en cuenta que SharePoint es la única carga de trabajo que actualmente envía eventos desde las instalaciones a O365. Obligatorio: No |
| [SenderIp](../../aspose.email.clients.activity/o365emailmessageactivity/senderip) { get; set; } | La dirección IP que envió el correo electrónico de Office 365. La dirección IP se muestra en formato de dirección IPv4 o IPv6. Obligatorio: Sí |
| [Subject](../../aspose.email.clients.activity/o365emailmessageactivity/subject) { get; set; } | La línea de asunto del mensaje. Obligatorio: Sí |
| [UserId](../../aspose.email.clients.activity/content/userid) { get; set; } | El UPN (Nombre principal de usuario) del usuario que realizó la acción (especificada en la propiedad Operación) que resultó en el registro del registro; por ejemplo, my_name@my_domain_name. Tenga en cuenta que también se incluyen los registros de la actividad realizada por las cuentas del sistema (como SHAREPOINT\system o NT AUTHORITY\SYSTEM). Obligatorio: Sí |
| [UserKey](../../aspose.email.clients.activity/content/userkey) { get; set; } | Un ID alternativo para el usuario identificado en la propiedad UserId. Por ejemplo, esta propiedad se completa con el identificador único de pasaporte (PUID) para eventos realizados por usuarios en SharePoint, OneDrive para la Empresa y Exchange. Esta propiedad también puede especificar el mismo valor que la propiedad UserID para eventos que ocurren en otros servicios y eventos realizados por cuentas del sistema. Obligatorio: Sí |
| [UserType](../../aspose.email.clients.activity/content/usertype) { get; set; } | El tipo de usuario que realizó la operación. Obligatorio: Sí |
| [Verdict](../../aspose.email.clients.activity/o365emailmessageactivity/verdict) { get; set; } | El veredicto del mensaje. Obligatorio: Sí |
| [Workload](../../aspose.email.clients.activity/content/workload) { get; set; } | El servicio de Office 365 donde se produjo la actividad en la cadena de carga de trabajo. Los valores posibles para esta propiedad son: Exchange SharePoint OneDrive AzureActiveDirectory SecurityComplianceCenter Sway ThreatIntelligence Obligatorio: No |

### Ver también

* class [Content](../content)
* espacio de nombres [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
