---
title: O365URLTimeOfClickActivity
second_title: Referencia de la API de Aspose.Email para .NET
description: Amplía el esquema común con las propiedades específicas de los datos de Office 365 Advanced Threat Protection e Threat Intelligence. Los eventos de Office 365 Advanced Threat Protection ATP y Threat Intelligence están disponibles para los clientes de Office 365 que tienen una suscripción ATP Threat Intelligence o E5 . Cada evento en la fuente ATP e Inteligencia de amenazas corresponde a las URL en las que hizo clic un usuario de la organización que se detectaron como malintencionadas en el momento del clic en función de la protección de vínculos seguros de ATP de Office 365.
type: docs
weight: 2670
url: /es/net/aspose.email.clients.activity/o365urltimeofclickactivity/
---
## O365URLTimeOfClickActivity class

Amplía el esquema común con las propiedades específicas de los datos de Office 365 Advanced Threat Protection e Threat Intelligence. Los eventos de Office 365 Advanced Threat Protection (ATP) y Threat Intelligence están disponibles para los clientes de Office 365 que tienen una suscripción ATP, Threat Intelligence o E5 . Cada evento en la fuente ATP e Inteligencia de amenazas corresponde a las URL en las que hizo clic un usuario de la organización que se detectaron como malintencionadas en el momento del clic en función de la protección de vínculos seguros de ATP de Office 365.

```csharp
public class O365URLTimeOfClickActivity : Content
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [O365URLTimeOfClickActivity](o365urltimeofclickactivity)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AppName](../../aspose.email.clients.activity/o365urltimeofclickactivity/appname) { get; set; } | Servicio de Office 365 desde el que se hizo clic en la URL (por ejemplo, Correo). Obligatorio: Sí |
| [Blocked](../../aspose.email.clients.activity/o365urltimeofclickactivity/blocked) { get; set; } | Esto es cierto si el clic en la URL está bloqueado por la protección de Vínculos seguros de ATP de Office 365. Obligatorio: Sí |
| [ClickedThrough](../../aspose.email.clients.activity/o365urltimeofclickactivity/clickedthrough) { get; set; } | Esto es cierto si el usuario hace clic en el bloqueo de URL (lo anula) en función de las políticas de la organización para la protección de vínculos seguros de ATP de Office 365. Obligatorio: Sí |
| [ClientIP](../../aspose.email.clients.activity/content/clientip) { get; set; } | La dirección IP del dispositivo que se usó cuando se registró la actividad. La dirección IP se muestra en formato de dirección IPv4 o IPv6. Obligatorio: Sí |
| [CreationTime](../../aspose.email.clients.activity/content/creationtime) { get; set; } | La fecha y hora en Tiempo Universal Coordinado (UTC) cuando el usuario realizó la actividad. Obligatorio: Sí |
| [Id](../../aspose.email.clients.activity/content/id) { get; set; } | Identificador único de un registro de auditoría. Obligatorio: Sí |
| [ObjectId](../../aspose.email.clients.activity/content/objectid) { get; set; } | Para la actividad de SharePoint y OneDrive para empresas, el nombre completo de la ruta de acceso del archivo o carpeta al que accede el usuario. Para el registro de auditoría de administración de Exchange, el nombre del objeto que modificó el cmdlet. Obligatorio: No |
| [Operation](../../aspose.email.clients.activity/content/operation) { get; set; } | El nombre del usuario o actividad de administrador. Para obtener una descripción de las operaciones/actividades más comunes, consulte Buscar en el registro de auditoría en el Centro de protección de Office 365. Para la actividad de administración de Exchange, esta propiedad identifica el nombre del cmdlet que se ejecutó. Para eventos DLP, puede ser "DlpRuleMatch", "DlpRuleUndo" o "DlpInfo", que se describen en "Esquema DLP" a continuación. Obligatorio: Sí |
| [OrganizationId](../../aspose.email.clients.activity/content/organizationid) { get; set; } | El GUID del inquilino de Office 365 de su organización. Este valor siempre será el mismo para su organización, independientemente del servicio de Office 365 en el que se produzca. Obligatorio: Sí |
| [RecordType](../../aspose.email.clients.activity/content/recordtype) { get; set; } | El tipo de operación que indica el registro. Obligatorio: Sí |
| [ResultStatus](../../aspose.email.clients.activity/content/resultstatus) { get; set; } | Indica si la acción (especificada en la propiedad Operación) fue exitosa o no. Los valores posibles son Correcto, Parcialmente exitoso o Error. Para la actividad de administración de Exchange, el valor es Verdadero o Falso. Obligatorio: No |
| [Scope](../../aspose.email.clients.activity/content/scope) { get; set; } | ¿Este evento fue creado por un servicio O365 alojado o un servidor local? Los valores posibles son online y onprem. Tenga en cuenta que SharePoint es la única carga de trabajo que actualmente envía eventos desde las instalaciones a O365. Obligatorio: No |
| [SourceId](../../aspose.email.clients.activity/o365urltimeofclickactivity/sourceid) { get; set; } | Identificador del servicio de Office 365 desde el que se hizo clic en la URL (p. ej., para Correo, este es el Id. de mensaje de red de Exchange Online). Obligatorio: Sí |
| [TimeOfClick](../../aspose.email.clients.activity/o365urltimeofclickactivity/timeofclick) { get; set; } | La fecha y la hora en hora universal coordinada (UTC) cuando el usuario hizo clic en la URL. Obligatorio: Sí |
| [URL](../../aspose.email.clients.activity/o365urltimeofclickactivity/url) { get; set; } | URL pulsada por el usuario. Obligatorio: Sí |
| [UserId](../../aspose.email.clients.activity/content/userid) { get; set; } | El UPN (Nombre principal de usuario) del usuario que realizó la acción (especificada en la propiedad Operación) que resultó en el registro del registro; por ejemplo, my_name@my_domain_name. Tenga en cuenta que también se incluyen los registros de la actividad realizada por las cuentas del sistema (como SHAREPOINT\system o NT AUTHORITY\SYSTEM). Obligatorio: Sí |
| [UserIp](../../aspose.email.clients.activity/o365urltimeofclickactivity/userip) { get; set; } | La dirección IP del usuario que hizo clic en la URL. La dirección IP se muestra en formato de dirección IPv4 o IPv6. Obligatorio: Sí |
| [UserKey](../../aspose.email.clients.activity/content/userkey) { get; set; } | Un ID alternativo para el usuario identificado en la propiedad UserId. Por ejemplo, esta propiedad se completa con el identificador único de pasaporte (PUID) para eventos realizados por usuarios en SharePoint, OneDrive para la Empresa y Exchange. Esta propiedad también puede especificar el mismo valor que la propiedad UserID para eventos que ocurren en otros servicios y eventos realizados por cuentas del sistema. Obligatorio: Sí |
| [UserType](../../aspose.email.clients.activity/content/usertype) { get; set; } | El tipo de usuario que realizó la operación. Obligatorio: Sí |
| [Workload](../../aspose.email.clients.activity/content/workload) { get; set; } | El servicio de Office 365 donde se produjo la actividad en la cadena de carga de trabajo. Los valores posibles para esta propiedad son: Exchange SharePoint OneDrive AzureActiveDirectory SecurityComplianceCenter Sway ThreatIntelligence Obligatorio: No |

### Ver también

* class [Content](../content)
* espacio de nombres [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
