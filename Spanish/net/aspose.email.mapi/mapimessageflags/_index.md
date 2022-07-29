---
title: MapiMessageFlags
second_title: Referencia de la API de Aspose.Email para .NET
description: MapiMessageFlags.
type: docs
weight: 18460
url: /es/net/aspose.email.mapi/mapimessageflags/
---
## MapiMessageFlags enumeration

MapiMessageFlags.

```csharp
[Flags]
public enum MapiMessageFlags : long
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| MSGFLAG_ZERO | `0` |  |
| MSGFLAG_READ | `1` | El mensaje se marca como leído. |
| MSGFLAG_UNMODIFIED | `2` | El mensaje no se ha modificado desde que se guardó por primera vez (si no se envió) o se entregó (si se envió). |
| MSGFLAG_SUBMIT | `4` | El mensaje se marca para enviar como resultado de una llamada a IMessage::SubmitMessage. Los proveedores de almacenamiento de mensajes establecen este indicador; el cliente tiene acceso de solo lectura. |
| MSGFLAG_UNSENT | `8` | El mensaje aún se está redactando. Se guarda, pero no se ha enviado. |
| MSGFLAG_HASATTACH | `10` | El mensaje tiene al menos un archivo adjunto. |
| MSGFLAG_FROMME | `20` | El usuario que recibió el mensaje también fue el usuario que envió el mensaje. |
| MSGFLAG_ASSOCIATED | `40` | MSGFLAG_ASOCIADO. |
| MSGFLAG_RESEND | `80` | El mensaje incluye una solicitud para una operación de reenvío con un informe de no entrega. |
| MSGFLAG_NOTIFYREAD | `100` | El usuario que envió el mensaje ha solicitado una notificación cuando un destinatario lo lea por primera vez. |
| MSGFLAG_NOTIFYUNREAD | `200` | El usuario que envió el mensaje ha solicitado una notificación cuando un destinatario lo elimine antes de leerlo o el objeto Mensaje expire. |
| MSGFLAG_EVERREAD | `400` | El mensaje se ha leído al menos una vez. El servidor establece o borra esta bandera siempre que elMSGFLAG_READ el indicador está establecido o borrado. |
| MSGFLAG_ORIGIN_X400 | `1000` | El mensaje entrante llegó a través de un enlace X.400. |
| MSGFLAG_ORIGIN_INTERNET | `2000` | El mensaje entrante llegó a través de Internet. |
| MSGFLAG_ORIGIN_MISC_EXT | `8000` | El mensaje entrante llegó a través de un enlace externo que no es X.400 o Internet. |

### Ver también

* espacio de nombres [Aspose.Email.Mapi](../../aspose.email.mapi)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->