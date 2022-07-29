---
title: CommandCodes
second_title: Referencia de la API de Aspose.Email para .NET
description: La siguiente tabla proporciona los códigos numéricos que corresponden a los comandos de ActiveSync. El código numérico se utiliza en el campo Código de comando del URI codificado en base64 para especificar el comando.
type: docs
weight: 1100
url: /es/net/aspose.email.clients.activesync.transportlayer/commandcodes/
---
## CommandCodes enumeration

La siguiente tabla proporciona los códigos numéricos que corresponden a los comandos de ActiveSync. El código numérico se utiliza en el campo Código de comando del URI codificado en base64 para especificar el comando.

```csharp
public enum CommandCodes
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Undefined | `-3` | Código de comando no definido. |
| Options | `-2` | El comando OPTIONS se usa para descubrir qué versiones de protocolo son compatibles y qué comandos de protocolo son compatibles en el servidor. |
| Autodiscover | `-1` | El comando Detección automática facilita el descubrimiento de la información de configuración de la cuenta principal mediante el uso de la dirección del Protocolo simple de transferencia de correo (SMTP) del usuario como entrada principal. |
| Sync | `0` | Sincroniza los cambios en una carpeta entre el cliente y el servidor. |
| SendMail | `1` | Envía correo al servidor. Este comando se emite en el URI del comando HTTP POST y no contiene un cuerpo XML. En su lugar, el cuerpo contendrá el mensaje MIME. |
| SmartForward | `2` | Reenvía un objeto de mensaje sin recuperar el objeto de mensaje completo del servidor. |
| SmartReply | `3` | Responde a un objeto de mensaje sin recuperar el objeto de mensaje completo del servidor. |
| GetAttachment | `4` | Recupera un archivo adjunto de correo electrónico del servidor. |
| FolderSync | `9` | Sincroniza la jerarquía de carpetas pero no sincroniza los elementos de las carpetas. |
| FolderCreate | `10` | Crea una carpeta de correo electrónico, calendario o contactos en el servidor. |
| FolderDelete | `11` | Elimina una carpeta del servidor. |
| FolderUpdate | `12` | Mueve una carpeta de una ubicación a otra en el servidor y se utiliza para cambiar el nombre de las carpetas. |
| MoveItems | `13` | Mueve elementos de una carpeta a otra. |
| GetItemEstimate | `14` | Obtiene una estimación del número de elementos en una carpeta que está sincronizada. |
| MeetingResponse | `15` | Se usa para aceptar, aceptar tentativamente o rechazar una solicitud de reunión en la carpeta Bandeja de entrada del usuario. |
| Search | `16` | Encuentra y recupera información sobre contactos y destinatarios en la Lista global de direcciones. |
| Settings | `17` | Admite obtener y configurar propiedades globales, como Fuera de la oficina (OOF) e información del dispositivo. |
| Ping | `18` | Solicita que el servidor supervise las carpetas especificadas en busca de cambios que requieran que el cliente vuelva a sincronizar. |
| ItemOperations | `19` | Identifica el cuerpo de la solicitud o respuesta que contiene un conjunto de comandos que operan en elementos. |
| Provision | `20` | Obtiene la configuración de la política de seguridad establecida por el administrador del servidor, como el requisito de longitud mínima de la contraseña del usuario. |
| ResolveRecipients | `21` | Resuelve una lista de destinatarios proporcionados y, opcionalmente, obtiene sus certificados S/MIME para que los clientes puedan enviar mensajes cifrados. |
| ValidateCert | `22` | Valida un certificado que se ha recibido a través de un correo S/MIME. |

### Ver también

* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->