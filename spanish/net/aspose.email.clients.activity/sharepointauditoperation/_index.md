---
title: SharePointAuditOperation
second_title: Referencia de la API de Aspose.Email para .NET
description: Operaciones de auditoría de SharePoint
type: docs
weight: 2760
url: /es/net/aspose.email.clients.activity/sharepointauditoperation/
---
## SharePointAuditOperation enumeration

Operaciones de auditoría de SharePoint

```csharp
public enum SharePointAuditOperation
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| AccessInvitationAccepted | `0` | Esta operación está en Vista previa. El destinatario de una invitación para ver o editar un archivo (o carpeta) compartido ha accedido al archivo compartido haciendo clic en el enlace de la invitación. |
| AccessInvitationCreated | `1` | Esta operación está en Vista previa. El usuario envía una invitación a otra persona (dentro o fuera de su organización) para ver o editar un archivo o una carpeta compartidos en un sitio de SharePoint o OneDrive para empresas. Los detalles de la entrada del evento identifican el nombre del archivo que se compartió, el usuario al que se envió la invitación, y el tipo de permiso de uso compartido seleccionado por la persona que envió la invitación. |
| AccessInvitationExpired | `2` | Esta operación está en Vista previa. Caduca una invitación enviada a un usuario externo. De forma predeterminada, una invitación enviada a un usuario fuera de su organización caduca después de 7 días si no se acepta la invitación. |
| AccessInvitationRevoked | `3` | Esta operación está en Vista previa. El administrador del sitio o propietario de un sitio o documento en SharePoint o OneDrive para la Empresa retira una invitación que se envió a un usuario fuera de su organización. Una invitación solo se puede retirar antes de que se acepte. |
| AccessInvitationUpdated | `4` | Esta operación está en Vista previa. El usuario que creó y envió una invitación a otra persona para ver o editar un archivo (o carpeta) compartido en un sitio de SharePoint o OneDrive para empresas vuelve a enviar la invitación. |
| AccessRequestApproved | `5` | El administrador del sitio o propietario de un sitio o documento en SharePoint o OneDrive for Business aprueba una solicitud de usuario para acceder al sitio o documento. |
| AccessRequestCreated | `6` | El usuario solicita acceso a un sitio o documento en SharePoint o OneDrive for Business para el que no tiene permiso de acceso. |
| AccessRequestRejected | `7` | Esta operación está en Vista previa. El administrador del sitio o propietario de un sitio o documento en SharePoint rechaza una solicitud de usuario para acceder al sitio o documento. |
| ActivationEnabled | `8` | Esta operación está en Vista previa. Los usuarios pueden habilitar en el navegador plantillas de formulario que no contengan código de formulario, requieran plena confianza, habiliten la representación en un dispositivo móvil o usen una conexión de datos administrada por un administrador de servidor. |
| AdministratorAddedToTermStore | `9` | Esta operación está en Vista previa. Se agregó el administrador del almacén de términos. |
| AdministratorDeletedFromTermStore | `10` | Esta operación está en Vista previa. Se eliminó el administrador del almacén de términos. |
| AllowGroupCreationSet | `11` | Esta operación está en Vista previa. El administrador o propietario del sitio agrega un nivel de permiso a un sitio de SharePoint o OneDrive for Business que permite que un usuario al que se le haya asignado ese permiso cree un grupo para ese sitio. |
| AppCatalogCreated | `12` | Esta operación está en Vista previa. Catálogo de aplicaciones creado para que las aplicaciones comerciales personalizadas estén disponibles para su entorno de SharePoint. |
| AuditPolicyRemoved | `13` | Esta operación está en Vista previa. Se eliminó la política de ciclo de vida del documento para una colección de sitios. |
| AuditPolicyUpdate | `14` | Esta operación está en Vista previa. La política de ciclo de vida del documento se ha actualizado para una colección de sitios. |
| AzureStreamingEnabledSet | `15` | Esta operación está en Vista previa. El propietario de un portal de video ha permitido la transmisión de video desde Azure. |
| CollaborationTypeModified | `16` | Esta operación está en Vista previa. Se modificó el tipo de colaboración permitida en los sitios (por ejemplo, intranet, extranet o público). |
| ConnectedSiteSettingModified | `17` | El usuario ha creado, modificado o eliminado el vínculo entre un proyecto y un sitio de proyecto o el usuario modifica la configuración de sincronización en el vínculo en Project Web App. |
| CreateSSOApplication | `18` | Esta operación está en Vista previa. Aplicación de destino creada en el servicio de almacenamiento seguro. |
| CustomFieldOrLookupTableCreated | `19` | El usuario creó un campo personalizado o una tabla/elemento de búsqueda en Project Web App. |
| CustomFieldOrLookupTableDeleted | `20` | El usuario eliminó un campo personalizado o una tabla/elemento de búsqueda en Project Web App. |
| CustomFieldOrLookupTableModified | `21` | El usuario modificó un campo personalizado o una tabla/elemento de búsqueda en Project Web App. |
| CustomizeExemptUsers | `22` | Esta operación está en Vista previa. El administrador global personalizó la lista de agentes de usuario exentos en el centro de administración de SharePoint. Puede especificar qué agentes de usuario eximir de recibir una página web completa para indexar. Esto significa que cuando un agente de usuario que ha especificado como exento encuentra un formulario de InfoPath, el formulario se devolverá como un archivo XML en lugar de una página web completa. Esto hace que la indexación de formularios de InfoPath sea más rápida. |
| DefaultLanguageChangedInTermStore | `23` | Esta operación está en Vista previa. Configuración de idioma cambiada en el almacén de terminología. |
| DelegateModified | `24` | El usuario creó o modificó un delegado de seguridad en Project Web App. |
| DelegateRemoved | `25` | El usuario eliminó un delegado de seguridad en Project Web App. |
| DeleteSSOApplication | `26` | Esta operación está en Vista previa. Se eliminó una aplicación SSO. |
| eDiscoveryHoldApplied | `27` | Esta operación está en Vista previa. Se colocó una retención local en una fuente de contenido. Las retenciones locales se administran mediante una colección de sitios de exhibición de documentos electrónicos (como el Centro de exhibición de documentos electrónicos) en SharePoint. |
| eDiscoveryHoldRemoved | `28` | Esta operación está en Vista previa. Se eliminó una retención local de una fuente de contenido. Las retenciones locales se administran mediante una colección de sitios de exhibición de documentos electrónicos (como el Centro de exhibición de documentos electrónicos) en SharePoint. |
| eDiscoverySearchPerformed | `29` | Esta operación está en Vista previa. Se realizó una búsqueda de exhibición de documentos electrónicos mediante una colección de sitios de exhibición de documentos electrónicos en SharePoint. |
| EngagementAccepted | `30` | El usuario acepta una participación de recursos en Project Web App. |
| EngagementModified | `31` | El usuario modifica una participación de recursos en Project Web App. |
| EngagementRejected | `32` | El usuario rechaza una participación de recursos en Project Web App. |
| EnterpriseCalendarModified | `33` | El usuario copia, modifica o elimina un calendario empresarial en Project Web App. |
| EntityDeleted | `34` | El usuario elimina un parte de horas en Project Web App. |
| EntityForceCheckedIn | `35` | El usuario fuerza un registro en un calendario, campo personalizado o tabla de búsqueda en Project Web App. |
| ExemptUserAgentSet | `36` | Esta operación está en Vista previa. El administrador global agrega un agente de usuario a la lista de agentes de usuario exentos en el centro de administración de SharePoint. |
| FileAccessed | `37` | La cuenta de usuario o del sistema accede a un archivo en un sitio de SharePoint o OneDrive para empresas. Las cuentas del sistema también pueden generar eventos FileAccessed. |
| FileCheckOutDiscarded | `38` | Esta operación está en Vista previa. El usuario descarta (o deshace) un archivo desprotegido. Eso significa que los cambios realizados en el archivo cuando se desprotegió se descartan y no se guardan en la versión del documento en la biblioteca de documentos. |
| FileCheckedIn | `39` | Esta operación está en Vista previa. El usuario registra un documento que desprotegió de una biblioteca de documentos de SharePoint o OneDrive para empresas. |
| FileCheckedOut | `40` | Esta operación está en Vista previa. El usuario desprotege un documento ubicado en una biblioteca de documentos de SharePoint o OneDrive para empresas. Los usuarios pueden desproteger y realizar cambios en los documentos que se han compartido con ellos. |
| FileCopied | `41` | El usuario copia un documento de un sitio de SharePoint o OneDrive para empresas. El archivo copiado se puede guardar en otra carpeta del sitio. |
| FileDeleted | `42` | El usuario elimina un documento de un sitio de SharePoint o OneDrive para empresas. |
| FileDeletedFirstStageRecycleBin | `43` | El usuario elimina un archivo de la papelera de reciclaje en un sitio de SharePoint o OneDrive para empresas. |
| FileDeletedSecondStageRecycleBin | `44` | El usuario elimina un archivo de la papelera de reciclaje de segunda etapa en un sitio de SharePoint o OneDrive para empresas. |
| FileDownloaded | `45` | El usuario descarga un documento de un sitio de SharePoint o OneDrive para empresas. |
| FileFetched | `46` | Este evento ha sido reemplazado por el evento FileAccessed y ha quedado obsoleto. |
| FileModified | `47` | La cuenta de usuario o del sistema modifica el contenido o las propiedades de un documento ubicado en un sitio de SharePoint o OneDrive para empresas. |
| FileMoved | `48` | El usuario mueve un documento desde su ubicación actual en un sitio de SharePoint o OneDrive for Business a una nueva ubicación. |
| FilePreviewed | `49` | El usuario obtiene una vista previa de un documento en un sitio de SharePoint o OneDrive para empresas. |
| FileRenamed | `50` | El usuario cambia el nombre de un documento en un sitio de SharePoint o OneDrive para empresas. |
| FileRestored | `51` | El usuario restaura un documento de la papelera de reciclaje de un sitio de SharePoint o OneDrive for Business. |
| FileSyncDownloadedFull | `52` | El usuario establece una relación de sincronización y descarga archivos correctamente por primera vez a su computadora desde una biblioteca de documentos de SharePoint o OneDrive para empresas. |
| FileSyncDownloadedPartial | `53` | El usuario descarga correctamente cualquier cambio en los archivos de la biblioteca de documentos de SharePoint o OneDrive para empresas. Este evento indica que los cambios realizados en los archivos de la biblioteca de documentos se descargaron en el equipo del usuario. Solo se descargaron los cambios porque el usuario descargó previamente la biblioteca de documentos (como lo indica el evento FileSyncDownloadedFull). |
| FileSyncUploadedFull | `54` | Esta operación está en Vista previa. El usuario establece una relación de sincronización y carga correctamente los archivos por primera vez desde su computadora a una biblioteca de documentos de SharePoint o OneDrive para empresas. |
| FileSyncUploadedPartial | `55` | Esta operación está en Vista previa. El usuario carga correctamente los cambios en los archivos en una biblioteca de documentos de SharePoint o OneDrive para empresas. Este evento indica que los cambios realizados en la versión local de un archivo de una biblioteca de documentos se cargan correctamente en la biblioteca de documentos. Solo se descargan los cambios porque el usuario cargó previamente esos archivos (como lo indica el evento FileSyncUploadedFull). |
| FileUploaded | `56` | El usuario carga un documento en una carpeta en un sitio de SharePoint o OneDrive para empresas. |
| FileViewed | `57` | Este evento ha sido reemplazado por el evento FileAccessed y ha quedado obsoleto. |
| FolderCopied | `58` | El usuario copia una carpeta de un sitio de SharePoint o OneDrive para la Empresa a otra ubicación en SharePoint o OneDrive para la Empresa. |
| FolderCreated | `59` | El usuario crea una carpeta en un sitio de SharePoint o OneDrive para empresas. |
| FolderDeleted | `60` | El usuario elimina una carpeta de un sitio de SharePoint o OneDrive para empresas. |
| FolderDeletedFirstStageRecycleBin | `61` | El usuario elimina una carpeta de la papelera de reciclaje en un sitio de SharePoint o OneDrive para empresas . |
| FolderDeletedSecondStageRecycleBin | `62` | El usuario elimina una carpeta de la papelera de reciclaje de la segunda etapa en un sitio de SharePoint o OneDrive para empresas. |
| FolderModified | `63` | El usuario modifica una carpeta en un sitio de SharePoint o OneDrive para empresas. Este evento incluye cambios en los metadatos de la carpeta, como etiquetas y propiedades. |
| FolderMoved | `64` | El usuario mueve una carpeta desde un sitio de SharePoint o OneDrive for Business. |
| FolderRenamed | `65` | El usuario cambia el nombre de una carpeta en un sitio de SharePoint o OneDrive para empresas. |
| FolderRestored | `66` | El usuario restaura una carpeta de la Papelera de reciclaje en un sitio de SharePoint o OneDrive para empresas. |
| GroupAdded | `67` | Esta operación está en Vista previa. El administrador o propietario del sitio crea un grupo para un sitio de SharePoint o OneDrive para la Empresa, o realiza una tarea que resulta en la creación de un grupo. Por ejemplo, la primera vez que un usuario crea un vínculo para compartir un archivo, se agrega un grupo del sistema al sitio de OneDrive para la Empresa del usuario. Este evento también puede ser el resultado de que un usuario cree un enlace con permisos de edición a un archivo compartido. |
| GroupRemoved | `68` | Esta operación está en Vista previa. El usuario elimina un grupo de un sitio de SharePoint o OneDrive para empresas. |
| GroupUpdated | `69` | Esta operación está en Vista previa. El administrador o propietario del sitio cambia la configuración de un grupo para un sitio de SharePoint o OneDrive para la Empresa. Esto puede incluir cambiar el nombre del grupo, quién puede ver o editar la membresía del grupo y cómo se manejan las solicitudes de membresía. |
| LanguageAddedToTermStore | `70` | Esta operación está en Vista previa. Idioma añadido al almacén de terminología. |
| LanguageRemovedFromTermStore | `71` | Esta operación está en Vista previa. Idioma eliminado del almacén de terminología. |
| LegacyWorkflowEnabledSet | `72` | Esta operación está en Vista previa. El administrador o propietario del sitio agrega el tipo de contenido Tarea de flujo de trabajo de SharePoint al sitio. Los administradores globales también pueden habilitar flujos de trabajo para toda la organización en el centro de administración de SharePoint. |
| LookAndFeelModified | `73` | El usuario modifica un inicio rápido, formatos de diagrama de Gantt o formatos de grupo. O el usuario crea, modifica o elimina una vista en Project Web App. |
| ManagedSyncClientAllowed | `74` | El usuario establece correctamente una relación de sincronización con un sitio de SharePoint o OneDrive para empresas. La relación de sincronización es correcta porque el equipo del usuario es miembro de un dominio que se agregó a la lista de dominios (llamada lista de destinatarios seguros) que pueden acceder a las bibliotecas de documentos de su organización. Para obtener más información sobre esta función, consulte Usar cmdlets de Windows PowerShell para habilitar la sincronización de OneDrive para dominios que están en la lista de destinatarios seguros. |
| MaxQuotaModified | `75` | Esta operación está en Vista previa. Se modificó la cuota máxima de un sitio. |
| MaxResourceUsageModified | `76` | Esta operación está en Vista previa. Se modificó el uso máximo permitido de recursos para un sitio. |
| MySitePublicEnabledSet | `77` | Esta operación está en Vista previa. El indicador que permite a los usuarios tener MySites públicos ha sido establecido por el administrador de SharePoint. |
| NewsFeedEnabledSet | `78` | Esta operación está en Vista previa. El administrador o propietario del sitio habilita las fuentes RSS para un sitio de SharePoint o OneDrive para la Empresa. Los administradores globales pueden habilitar fuentes RSS para toda la organización en el centro de administración de SharePoint. |
| ODBNextUXSettings | `79` | Esta operación está en Vista previa. Se ha habilitado la nueva interfaz de usuario para OneDrive for Business. |
| OfficeOnDemandSet | `80` | Esta operación está en Vista previa. El administrador del sitio habilita Office on Demand, que permite a los usuarios acceder a la versión más reciente de las aplicaciones de escritorio de Office. Office on Demand está habilitado en el centro de administración de SharePoint y requiere una suscripción a Office 365 que incluye aplicaciones de Office completas e instaladas. |
| PageViewed | `81` | El usuario ve una página en un sitio de SharePoint o en un sitio de OneDrive para la Empresa. Esto no incluye la visualización de archivos de biblioteca de documentos desde un sitio de SharePoint o un sitio de One Drive for Business en un navegador. |
| PeopleResultsScopeSet | `82` | Esta operación está en Vista previa. El administrador del sitio crea o cambia la fuente de resultados para las búsquedas de personas para un sitio de SharePoint. |
| PermissionSyncSettingModified | `83` | El usuario modifica la configuración de sincronización de permisos del proyecto en Project Web App. |
| PermissionTemplateModified | `84` | El usuario crea, modifica o elimina una plantilla de permisos en Project Web App. |
| PortfolioDataAccessed | `85` | El usuario accede al contenido de la cartera (biblioteca de controladores, priorización de controladores, análisis de cartera) en Project Web App. |
| PortfolioDataModified | `86` | El usuario crea, modifica o elimina datos de cartera (biblioteca de controladores, priorización de controladores, análisis de cartera) en Project Web App. |
| PreviewModeEnabledSet | `87` | Esta operación está en Vista previa. El administrador del sitio habilita la vista previa de documentos para un sitio de SharePoint. |
| ProjectAccessed | `88` | El usuario accede al contenido del proyecto en Project Web App. |
| ProjectCheckedIn | `89` | El usuario registra un proyecto que desprotegió de Project Web App. |
| ProjectCheckedOut | `90` | El usuario desprotege un proyecto ubicado en Project Web App. Los usuarios pueden desproteger y realizar cambios en los proyectos que tienen permiso para abrir. |
| ProjectCreated | `91` | El usuario crea un proyecto en Project Web App. |
| ProjectDeleted | `92` | El usuario elimina un proyecto en Project Web App. |
| ProjectForceCheckedIn | `93` | El usuario fuerza un registro en un proyecto en Project Web App. |
| ProjectModified | `94` | El usuario modifica un proyecto en Project Web App. |
| ProjectPublished | `95` | El usuario publica un proyecto en Project Web App. |
| ProjectWorkflowRestarted | `96` | El usuario reinicia un flujo de trabajo en Project Web App. |
| PWASettingsAccessed | `97` | El usuario accede a la configuración de Project Web App a través de CSOM. |
| PWASettingsModified | `98` | El usuario modifica la configuración de una aplicación web de Project. |
| QueueJobStateModified | `99` | El usuario cancela o reinicia un trabajo en cola en Project Web App. |
| QuotaWarningEnabledModified | `100` | Esta operación está en Vista previa. Advertencia de cuota de almacenamiento modificada. |
| RenderingEnabled | `101` | Esta operación está en Vista previa. Los servicios de formularios de InfoPath representarán las plantillas de formulario habilitadas para navegador. |
| ReportingAccessed | `102` | El usuario accedió al extremo de informes en Project Web App. |
| ReportingSettingModified | `103` | El usuario modifica la configuración de informes en Project Web App. |
| ResourceAccessed | `104` | El usuario accede a un contenido de recursos empresariales en Project Web App. |
| ResourceCheckedIn | `105` | El usuario protege un recurso empresarial que desprotegió de Project Web App. |
| ResourceCheckedOut | `106` | El usuario desprotege un recurso empresarial ubicado en Project Web App. |
| ResourceCreated | `107` | El usuario crea un recurso empresarial en Project Web App. |
| ResourceDeleted | `108` | El usuario elimina un recurso empresarial en Project Web App. |
| ResourceForceCheckedIn | `109` | El usuario fuerza un registro de un recurso empresarial en Project Web App. |
| ResourceModified | `110` | El usuario modifica un recurso empresarial en Project Web App. |
| ResourcePlanCheckedInOrOut | `111` | El usuario registra o retira un plan de recursos en Project Web App. |
| ResourcePlanModified | `112` | El usuario modifica un plan de recursos en Project Web App. |
| ResourcePlanPublished | `113` | El usuario publica un plan de recursos en Project Web App. |
| ResourceRedacted | `114` | El usuario redacta un recurso empresarial eliminando toda la información personal en Project Web App. |
| ResourceWarningEnabledModified | `115` | Esta operación está en Vista previa. Advertencia de cuota de recursos modificada. |
| SSOGroupCredentialsSet | `116` | Esta operación está en Vista previa. Credenciales de grupo establecidas en el servicio de almacenamiento seguro. |
| SSOUserCredentialsSet | `117` | Esta operación está en Vista previa. Credenciales de usuario establecidas en el servicio de almacenamiento seguro. |
| SearchCenterUrlSet | `118` | Esta operación está en Vista previa. Conjunto de URL del centro de búsqueda. |
| SecondaryMySiteOwnerSet | `119` | Esta operación está en Vista previa. Un usuario ha agregado un propietario secundario a su Mi sitio. |
| SecurityCategoryModified | `120` | El usuario crea, modifica o elimina una categoría de seguridad en Project Web App. |
| SecurityGroupModified | `121` | El usuario crea, modifica o elimina un grupo de seguridad en Project Web App. |
| SendToConnectionAdded | `122` | Esta operación está en Vista previa. El administrador global crea una nueva conexión Enviar a en la página de administración de registros en el centro de administración de SharePoint. Una conexión Enviar a especifica la configuración de un repositorio de documentos o un centro de registros. Cuando crea una conexión Enviar a, un organizador de contenido puede enviar documentos a la ubicación especificada. |
| SendToConnectionRemoved | `123` | Esta operación está en Vista previa. El administrador global elimina una conexión Enviar a en la página de administración de registros en el centro de administración de SharePoint. |
| SharedLinkCreated | `124` | El usuario crea un vínculo a un archivo compartido en SharePoint o OneDrive para empresas. Este enlace se puede enviar a otras personas para darles acceso al archivo. Un usuario puede crear dos tipos de enlaces: un enlace que le permite ver y editar el archivo compartido, o un enlace que le permite al usuario simplemente ver el archivo. |
| SharedLinkDisabled | `125` | Esta operación está en Vista previa. El usuario deshabilita (permanentemente) un enlace que se creó para compartir un archivo. |
| SharingInvitationAccepted | `126` | Esta operación está en Vista previa. El usuario acepta una invitación para compartir un archivo o carpeta. Este evento se registra cuando un usuario comparte un archivo con otros usuarios. |
| SharingRevoked | `127` | Esta operación está en Vista previa. El usuario deja de compartir un archivo o una carpeta que se compartió previamente con otros usuarios. Este evento se registra cuando un usuario deja de compartir un archivo con otros usuarios. |
| SharingSet | `128` | El usuario comparte un archivo o carpeta ubicado en SharePoint o OneDrive for Business con otro usuario dentro de su organización. |
| SiteAdminChangeRequest | `129` | Esta operación está en Vista previa. El usuario solicita que se le agregue como administrador de la colección de sitios para una colección de sitios de SharePoint. Los administradores de la colección de sitios tienen permisos de control total para la colección de sitios y todos los subsitios. |
| SiteCollectionAdminAdded | `130` | Esta operación está en Vista previa. El administrador o propietario de la colección de sitios agrega una persona como administrador de la colección de sitios para un sitio de SharePoint o OneDrive para la Empresa. Los administradores de la colección de sitios tienen permisos de control total para la colección de sitios y todos los subsitios. |
| SiteCollectionCreated | `131` | Esta operación está en Vista previa. El administrador global crea una nueva colección de sitios en su organización de SharePoint. |
| SiteRenamed | `132` | Esta operación está en Vista previa. El propietario o el administrador del sitio cambia el nombre de un sitio de SharePoint o OneDrive para la empresa |
| StatusReportModified | `133` | El usuario crea, modifica o elimina un informe de estado en Project Web App. |
| SyncGetChanges | `134` | Esta operación está en Vista previa. El usuario hace clic en Sincronizar en la bandeja de acciones de SharePoint o OneDrive for Business para sincronizar cualquier cambio en el archivo de una biblioteca de documentos con su computadora. |
| TaskStatusAccessed | `135` | El usuario accede al estado de una o más tareas en Project Web App. |
| TaskStatusApproved | `136` | El usuario aprueba una actualización de estado de una o más tareas en Project Web App. |
| TaskStatusRejected | `137` | El usuario rechaza una actualización de estado de una o más tareas en Project Web App. |
| TaskStatusSaved | `138` | El usuario guarda una actualización de estado de una o más tareas en Project Web App. |
| TaskStatusSubmitted | `139` | El usuario envía una actualización de estado de una o más tareas en Project Web App. |
| TimesheetAccessed | `140` | El usuario accede a un parte de horas en Project Web App. |
| TimesheetApproved | `141` | El usuario aprueba el parte de horas en Project Web App. |
| TimesheetRejected | `142` | El usuario rechaza un parte de horas en Project Web App. |
| TimesheetSaved | `143` | El usuario guarda un parte de horas en Project Web App. |
| TimesheetSubmitted | `144` | El usuario envía un parte de horas de estado en Project Web App. |
| UnmanagedSyncClientBlocked | `145` | El usuario intenta establecer una relación de sincronización con un sitio de SharePoint o OneDrive for Business desde una computadora que no es miembro del dominio de su organización o es miembro de un dominio que no se ha agregado a la lista de dominios ( denominada lista de destinatarios seguros) que pueden acceder a las bibliotecas de documentos de su organización. La relación de sincronización no está permitida y el equipo del usuario no puede sincronizar, descargar o cargar archivos en una biblioteca de documentos. Para obtener información sobre esta característica, consulte Usar cmdlets de Windows PowerShell para habilitar la sincronización de OneDrive para dominios que están en la lista de destinatarios seguros. |
| UpdateSSOApplication | `146` | Esta operación está en Vista previa. Aplicación de destino actualizada en el servicio de almacenamiento seguro. |
| UserAddedToGroup | `147` | Esta operación está en Vista previa. El administrador o propietario del sitio agrega una persona a un grupo en un sitio de SharePoint o OneDrive para la Empresa. Agregar una persona a un grupo otorga al usuario los permisos que se le asignaron al grupo. |
| UserRemovedFromGroup | `148` | Esta operación está en Vista previa. El administrador o propietario del sitio quita a una persona de un grupo en un sitio de SharePoint o OneDrive para la Empresa. Después de eliminar a la persona, ya no se le otorgan los permisos que se le asignaron al grupo. |
| WorkflowModified | `149` | El usuario crea, modifica o elimina un tipo de proyecto empresarial o fases o etapas de flujo de trabajo en Project Web App. |

### Ver también

* espacio de nombres [Aspose.Email.Clients.Activity](../../aspose.email.clients.activity)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
