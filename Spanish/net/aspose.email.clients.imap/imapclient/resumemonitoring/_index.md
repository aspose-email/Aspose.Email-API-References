---
title: ResumeMonitoring
second_title: Referencia de la API de Aspose.Email para .NET
description: Reanuda la supervisión de los cambios de mensajes para la carpeta especificada. A diferencia del método StartMonitoring encontrará todos los cambios de buzón faltantes y llamará para devolver la llamada.
type: docs
weight: 1070
url: /es/net/aspose.email.clients.imap/imapclient/resumemonitoring/
---
## ImapClient.ResumeMonitoring method

Reanuda la supervisión de los cambios de mensajes para la carpeta especificada. A diferencia del método StartMonitoring, encontrará todos los cambios de buzón faltantes y llamará para devolver la llamada.

```csharp
public void ResumeMonitoring(ImapMonitoringEventHandler callback, 
    ImapMonitoringErrorEventHandler errorCallback, IImapMonitoringState monitoringState)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| callback | ImapMonitoringEventHandler | La función de devolución de llamada para monitorear la operación. |
| errorCallback | ImapMonitoringErrorEventHandler | La función de devolución de llamada para monitorear el manejo de errores. El monitoreo de la carpeta especificada se detiene cuando se llama a esta devolución de llamada. |
| monitoringState | IImapMonitoringState | El estado de supervisión desde el que reanudar la supervisión de carpetas. Puede recuperarse de[`MonitoringState`](../../imapmonitoringerroreventargs/monitoringstate) . |

### Ver también

* delegate [ImapMonitoringEventHandler](../../imapmonitoringeventhandler)
* delegate [ImapMonitoringErrorEventHandler](../../imapmonitoringerroreventhandler)
* interface [IImapMonitoringState](../../iimapmonitoringstate)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->