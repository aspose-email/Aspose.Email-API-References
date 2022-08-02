---
title: Record
second_title: Referencia de la API de Aspose.Email para .NET
description: registro de registro de auditoría
type: docs
weight: 2720
url: /es/net/aspose.email.clients.activity/record/
---
## Record class

registro de registro de auditoría

```csharp
public class Record
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Record](record)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AzureActiveDirectoryEventType](../../aspose.email.clients.activity/record/azureactivedirectoryeventtype) { get; set; } | Obtiene o establece el tipo de evento de Azure AD. Obligatorio: Sí |
| [Client](../../aspose.email.clients.activity/record/client) { get; set; } | Obtiene o establece detalles sobre el dispositivo cliente, el sistema operativo del dispositivo y el navegador del dispositivo que se utilizó para el evento de inicio de sesión de la cuenta. Obligatorio: No |
| [ClientIP](../../aspose.email.clients.activity/record/clientip) { get; set; } | Obtiene o establece la dirección IP del dispositivo que se usó cuando se registró la actividad. La dirección IP se muestra en formato de dirección IPv4 o IPv6. Obligatorio: Sí |
| [CreationTime](../../aspose.email.clients.activity/record/creationtime) { get; set; } | Obtiene o establece la fecha y la hora en Hora Universal Coordinada (UTC) cuando el usuario realizó la actividad. Obligatorio: Sí |
| [ExtendedProperties](../../aspose.email.clients.activity/record/extendedproperties) { get; set; } | Obtiene o establece una lista de propiedades extendidas para la configuración que se está modificando. Cada propiedad tendrá un Nombre y Valor. Obligatorio: No |
| [Id](../../aspose.email.clients.activity/record/id) { get; set; } | Obtiene o establece el identificador único de un registro de auditoría. Obligatorio: Sí |
| [LoginStatus](../../aspose.email.clients.activity/record/loginstatus) { get; set; } | Obtiene o establece el estado de inicio de sesión Obligatorio: Sí |
| [ObjectId](../../aspose.email.clients.activity/record/objectid) { get; set; } | Obtiene o establece el identificador de objeto. Para la actividad de SharePoint y OneDrive para empresas, el nombre completo de la ruta de acceso del archivo o carpeta al que accede el usuario. Para el registro de auditoría de administración de Exchange, el nombre del objeto que modificó el cmdlet. Obligatorio: No |
| [Operation](../../aspose.email.clients.activity/record/operation) { get; set; } | Obtiene o establece el nombre de la actividad del usuario o administrador. Para obtener una descripción de las operaciones/actividades más comunes, consulte Buscar en el registro de auditoría en el Centro de protección de Office 365. Para la actividad de administración de Exchange, esta propiedad identifica el nombre del cmdlet que se ejecutó. Para eventos DLP, puede ser "DlpRuleMatch", "DlpRuleUndo" o "DlpInfo", que se describen en "Esquema DLP" a continuación. Obligatorio: Sí |
| [OrganizationId](../../aspose.email.clients.activity/record/organizationid) { get; set; } | Obtiene o establece GUID para el arrendatario de Office 365 de su organización. Este valor siempre será el mismo para su organización, independientemente del servicio de Office 365 en el que se produzca. Obligatorio: Sí |
| [RecordType](../../aspose.email.clients.activity/record/recordtype) { get; set; } | Obtiene o establece el tipo de operación indicada por el registro. Obligatorio: Sí |
| [ResultStatus](../../aspose.email.clients.activity/record/resultstatus) { get; set; } | Obtiene o establece el valor que indica si la acción (especificada en la propiedad Operación) fue exitosa o no. Obligatorio: No |
| [UserDomain](../../aspose.email.clients.activity/record/userdomain) { get; set; } | Obtiene o establece la información de identidad del arrendatario (TII). Obligatorio: Sí |
| [UserId](../../aspose.email.clients.activity/record/userid) { get; set; } | Obtiene o establece el UPN (Nombre principal de usuario) del usuario que realizó la acción (especificada en la propiedad Operación) que resultó en el registro; por ejemplo, my_name@my_domain_name. Tenga en cuenta que también se incluyen los registros de la actividad realizada por las cuentas del sistema (como SHAREPOINT\system o NT AUTHORITY\SYSTEM). Obligatorio: Sí |
| [UserKey](../../aspose.email.clients.activity/record/userkey) { get; set; } | Obtiene o establece un ID alternativo para el usuario identificado en la propiedad UserId. Por ejemplo, esta propiedad se completa con el identificador único de pasaporte (PUID) para eventos realizados por usuarios en SharePoint, OneDrive para la Empresa y Exchange. Esta propiedad también puede especificar el mismo valor que la propiedad UserID para eventos que ocurren en otros servicios y eventos realizados por cuentas del sistema. Obligatorio: Sí |
| [UserType](../../aspose.email.clients.activity/record/usertype) { get; set; } | Obtiene o establece el tipo de usuario que realizó la operación. Obligatorio: Sí |
| [Workload](../../aspose.email.clients.activity/record/workload) { get; set; } | Obtiene o establece el servicio de Office 365 donde se produjo la actividad. Obligatorio: No |

### Ver también

* espacio de nombres [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
