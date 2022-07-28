---
title: Provision
second_title: Referencia de la API de Aspose.Email para .NET
description: Aprovisionar espacio de nombres del protocolo ActiveSync
type: docs
weight: 1710
url: /es/net/aspose.email.clients.activesync.transportlayer/provision/
---
## Provision enumeration

Aprovisionar espacio de nombres del protocolo ActiveSync

```csharp
public enum Provision
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Provision | `5` | Las capacidades y permisos para el dispositivo. |
| Policies | `6` | Una colección de políticas de seguridad. |
| Policy | `7` | Una política de seguridad. |
| PolicyType | `8` | Especifica el formato en el que se proporcionará la configuración de la directiva. |
| PolicyKey | `9` | Usado por el servidor para marcar el estado de la configuración de la política en el cliente. |
| Data | `10` | La configuración de una política. |
| Status | `11` | Indica el éxito o el fracaso de partes específicas de un comando. |
| RemoteWipe | `12` | Especifica una directiva de borrado remoto del servidor o la confirmación de un cliente de una directiva de borrado remoto. |
| EASProvisionDoc | `13` | La colección de configuraciones de seguridad para el aprovisionamiento de dispositivos. |
| DevicePasswordEnabled | `14` | Indica si un dispositivo cliente requiere contraseña. |
| AlphanumericDevicePasswordRequired | `15` | Indica si un dispositivo cliente requiere una contraseña alfanumérica. |
| RequireStorageCardEncryption | `16` | Indica si el dispositivo tiene que cifrar el contenido que está almacenado en la tarjeta de almacenamiento. |
| PasswordRecoveryEnabled | `17` | Indica si habilitar el envío de una contraseña de recuperación al servidor mediante el comando Configuración. |
| AttachmentsEnabled | `19` | Indica si los archivos adjuntos de correo electrónico están habilitados. |
| MinDevicePasswordLength | `20` | La longitud mínima de la contraseña del dispositivo que el usuario puede ingresar |
| MaxInactivityTimeDeviceLock | `21` | El número de segundos de inactividad antes de que el dispositivo se bloquee. |
| MaxDevicePasswordFailedAttempts | `22` | El número de errores de contraseña permitidos antes de que se borre el dispositivo. |
| MaxAttachmentSize | `23` | El tamaño máximo de archivo adjunto, según lo determina la política de seguridad. |
| AllowSimpleDevicePassword | `24` | Si el dispositivo permite contraseñas simples. |
| DevicePasswordExpiration | `25` | Si la contraseña caduca después del número de días especificado, según lo determine la política. |
| DevicePasswordHistory | `26` | El número mínimo de contraseñas utilizadas previamente que el dispositivo cliente almacena para evitar su reutilización. |
| AllowStorageCard | `27` | Si el dispositivo permite el uso de la tarjeta de almacenamiento. |
| AllowCamera | `28` | Si el dispositivo permite el uso de la cámara integrada. |
| RequireDeviceEncryption | `29` | Si el dispositivo usa cifrado. |
| AllowUnsignedApplications | `30` | Si el dispositivo permite ejecutar aplicaciones no firmadas. |
| AllowUnsignedInstallationPackages | `31` | Si el dispositivo permite la instalación de archivos de gabinete sin firmar (.cab). |
| MinDevicePasswordComplexCharacters | `32` | El número mínimo de caracteres complejos (números y símbolos) contenidos en la contraseña. |
| AllowWiFi | `33` | Si el dispositivo permite el uso de conexiones Wi-Fi. |
| AllowTextMessaging | `34` | Si el dispositivo permite el servicio de mensajes cortos (SMS)/mensajes de texto. |
| AllowPOPIMAPEmail | `35` | Si el dispositivo permite el acceso al correo electrónico POP/IMAP. |
| AllowBluetooth | `36` | Si los perfiles Bluetooth y manos libres están permitidos en el dispositivo. |
| AllowIrDA | `37` | Si el dispositivo permite el uso de conexiones IrDA (infrarrojos). |
| RequireManualSyncWhenRoaming | `38` | Si el dispositivo requiere sincronización manual cuando el dispositivo está en roaming. |
| AllowDesktopSync | `39` | Si el dispositivo permite la sincronización con Desktop ActiveSync. |
| MaxCalendarAgeFilter | `40` | El número máximo de días naturales que se pueden sincronizar. |
| AllowHTMLEmail | `41` | Si el dispositivo utiliza correo electrónico con formato HTML. |
| MaxEmailAgeFilter | `42` | El límite de edad del correo electrónico para la sincronización. |
| MaxEmailBodyTruncationSize | `43` | El tamaño de truncamiento para mensajes de correo electrónico con formato de texto sin formato. |
| MaxEmailHTMLBodyTruncationSize | `44` | El tamaño de truncamiento para mensajes de correo electrónico con formato HTML. |
| RequireSignedSMIMEMessages | `45` | Si se requiere que el dispositivo envíe mensajes S/MIME firmados. |
| RequireEncryptedSMIMEMessages | `46` | Si se requiere que el dispositivo envíe mensajes cifrados. |
| RequireSignedSMIMEAlgorithm | `47` | El algoritmo que se utilizará al firmar un mensaje. |
| RequireEncryptionSMIMEAlgorithm | `48` | El algoritmo que se utilizará al cifrar un mensaje. |
| AllowSMIMEEncryptionAlgorithmNegotiation | `49` | Si el dispositivo puede negociar el algoritmo de cifrado que se utilizará para firmar. |
| AllowSMIMESoftCerts | `50` | Si el dispositivo utiliza certificados de software para firmar los mensajes salientes. |
| AllowBrowser | `51` | Si el dispositivo permite el uso de un navegador web. |
| AllowConsumerEmail | `52` | Si el dispositivo permite el uso de correo electrónico personal. |
| AllowRemoteDesktop | `53` | Si el dispositivo permite el uso de Escritorio remoto. |
| AllowInternetSharing | `54` | Si el dispositivo permite el uso de Internet Sharing. |
| UnapprovedInROMApplicationList | `55` | Una lista de aplicaciones en ROM que no están aprobadas para su ejecución. |
| ApplicationName | `56` | El nombre de una aplicación en ROM (archivo .exe) que no está aprobada para su ejecución. |
| ApprovedApplicationList | `57` | Una lista de aplicaciones en RAM que están aprobadas para su ejecución. |
| Hash | `58` | El hash SHA-1 de una aplicación en memoria que está aprobada para su ejecución. |

### Ver también

* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
