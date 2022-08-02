---
title: ExchangeFolderType
second_title: Referencia de la API de Aspose.Email para .NET
description: Enumera los tipos de carpeta distinguidos. Estos valores también se encuentran en la propiedad PidTagContainerClass.
type: docs
weight: 3340
url: /es/net/aspose.email.clients.exchange/exchangefoldertype/
---
## ExchangeFolderType enumeration

Enumera los tipos de carpeta distinguidos. Estos valores también se encuentran en la propiedad PidTagContainerClass.

```csharp
public enum ExchangeFolderType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Undefined | `0` | El tipo de carpeta no está establecido. El valor se usa con las siguientes carpetas conocidas: Raíz: la carpeta de nivel superior de la jerarquía del almacén de mensajes, que contiene todos los demás objetos de carpeta en ese almacén de mensajes. Finder: contiene las carpetas de búsqueda predeterminadas. Datos de disponibilidad: contiene los datos de disponibilidad del propietario del buzón. Parte superior de las carpetas personales: la carpeta superior de la jerarquía de mensajes interpersonales, que contiene las carpetas de datos del usuario, incluidas la mayoría de las carpetas especiales, como la carpeta Bandeja de entrada. Vistas comunes: contiene los datos de las vistas predeterminadas que son estándar para el almacén de mensajes y que puede utilizar cualquier usuario de un cliente que acceda al almacén de mensajes. Vistas personales: contiene los datos de las vistas definidas por un usuario en particular. Acción diferida: contiene cualquier acción diferida Mensaje de acción (DAM) o Mensaje de error diferido (DEM) que resulta de la ejecución de reglas del lado del cliente. |
| Note | `1` | Este valor representa el tipo de carpeta del mensaje de correo electrónico ("IPF.Note"). El valor se usa con las siguientes carpetas conocidas: Elementos eliminados: la ubicación predeterminada para los objetos que se han eliminado. Bandeja de salida: correo electrónico saliente Los objetos de mensaje se colocan en esta carpeta cuando se envía el objeto de mensaje. Elementos enviados: la ubicación predeterminada en la que se colocan las copias de los objetos de mensaje de correo electrónico después de que se hayan enviado (enviado). Bandeja de entrada: la ubicación predeterminada para ( recibido) Objetos de mensajes de correo electrónico. Borradores: la ubicación predeterminada para los objetos de mensajes de correo electrónico redactados que se guardaron pero no se enviaron. Correo electrónico no deseado: ubicación predeterminada para los objetos de mensajes de correo electrónico determinados como correo no deseado por una regla de correo electrónico no deseado. Problemas de sincronización: contiene carpetas que contienen mensajes que indican problemas particulares encontrados durante la sincronización entre el cliente y el servidor. Esta es la carpeta principal de las carpetas Conflictos, Fallas locales y Fallas del servidor. Conflictos: contiene objetos de mensaje que indican conflictos de sincronización entre el cliente y el servidor. Fallas locales: contiene mensajes que indican fallas de sincronización del lado del cliente. Fallas del servidor - Contiene mensajes que indican errores de sincronización del lado del servidor. Procesamiento de correo rastreado - Carpeta de búsqueda que contiene objetos marcados. Cola de cola - Contiene objetos de correo electrónico que se han enviado o recibido. |
| RSSFeeds | `2` | Este valor representa el tipo de carpeta de mensajes RSS ("IPF.Note.OutlookHomepage"). El valor se usa con las siguientes carpetas conocidas: Fuentes RSS: contiene mensajes de fuente Really Simple Syndication (RSS). |
| Appointment | `3` | Este valor representa el tipo de carpeta 'cita' ("IPF.Cita"). El valor se utiliza con las siguientes carpetas conocidas: Calendario: contiene objetos de Calendario, como citas. |
| Contact | `4` | Este valor representa el tipo de carpeta 'contactos' ("IPF.Contacto"). El valor se usa con las siguientes carpetas conocidas: Contactos: contiene objetos de contacto. Contactos sugeridos: contiene objetos de contacto que se crean cuando un destinatario no está en una libreta de direcciones. Búsqueda de contactos: carpeta de búsqueda que muestra una lista de contactos que se ajustan a los criterios de búsqueda. |
| QuickContacts | `5` | Este valor representa el tipo de carpeta para contactos favoritos ("IPF.Contact.MOC.QuickContacts"). El valor se usa con las siguientes carpetas conocidas: Contactos rápidos: contiene objetos de contacto para los contactos favoritos del usuario y contactos de mensajería instantánea. |
| ImContactsList | `6` | Este valor representa el tipo de carpeta para los contactos de mensajería instantánea ("IPF.Contact.MOC.ImContactList"). El valor se usa con las siguientes carpetas conocidas: Lista de contactos de IM: contiene objetos de lista de distribución personal de contactos favoritos y contactos de mensajería instantánea . |
| DocumentLibraries | `7` | Este valor representa el tipo de carpeta de "documentos" ("IPF.ShortcutFolder"). El valor se usa con las siguientes carpetas conocidas: Bibliotecas de documentos: contiene documentos que se cargarán en una ubicación compartida. |
| Journal | `8` | Este valor representa el tipo de carpeta 'Diario' ("IPF.Diario"). El valor se utiliza con las siguientes carpetas conocidas: Diario: contiene objetos de Diario. |
| StickyNote | `9` | Este valor representa el tipo de carpeta 'notas' ("IPF.StickyNote"). El valor se usa con las siguientes carpetas conocidas: Notas: contiene objetos de nota. |
| Task | `10` | Este valor representa el tipo de carpeta 'Tarea' ("IPF.Tarea"). El valor se usa con las siguientes carpetas conocidas: Tareas pendientes: carpeta de búsqueda utilizada para rastrear objetos de tareas. Tareas: contiene objetos de tareas. |
| Imap | `11` | Este valor representa el tipo de carpeta 'imap' ("IPF.IMAP"). Se utiliza para migrar del perfil IMAP a Exchange. |
| Unknown | `12` | El tipo de carpeta es desconocido. |

### Ver también

* espacio de nombres [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
