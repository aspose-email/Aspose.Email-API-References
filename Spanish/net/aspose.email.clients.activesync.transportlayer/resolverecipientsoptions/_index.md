---
title: ResolveRecipientsOptions
second_title: Referencia de la API de Aspose.Email para .NET
description: Contiene las opciones para resolver la lista de destinatarios.
type: docs
weight: 1850
url: /es/net/aspose.email.clients.activesync.transportlayer/resolverecipientsoptions/
---
## ResolveRecipientsOptions class

Contiene las opciones para resolver la lista de destinatarios.

```csharp
public class ResolveRecipientsOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ResolveRecipientsOptions](resolverecipientsoptions)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Availability](../../aspose.email.clients.activesync.transportlayer/resolverecipientsoptions/availability) { get; set; } | Indica al servidor que el cliente solicita datos de disponibilidad e identifica la hora de inicio y la hora de finalización de los datos de disponibilidad para recuperar. Cuando la disponibilidad se incluye en una solicitud de ResolveRecipients, el servidor recupera la disponibilidad información para los usuarios identificados en los elementos Para incluidos en la solicitud y devuelve la información de disponibilidad en MergedFreeBusy en la respuesta. Si el elemento Disponibilidad está incluido en la solicitud ResolveRecipients, la solicitud también DEBE incluir un valor de Hora de inicio y un valor de Hora de finalización válidos. Cuando el servidor analiza la solicitud, primero resuelve los destinatarios identificados por los elementos Para y luego determina la información de disponibilidad de los usuarios para el período de tiempo especificado, antes de devolver los datos de disponibilidad en MergedFreeBusy. |
| [CertificateRetrieval](../../aspose.email.clients.activesync.transportlayer/resolverecipientsoptions/certificateretrieval) { get; set; } | Especifica si el servidor DEBERÍA devolver los certificados S/MIME para cada destinatario resuelto. |
| [MaxAmbiguousRecipients](../../aspose.email.clients.activesync.transportlayer/resolverecipientsoptions/maxambiguousrecipients) { get; set; } | Limita la cantidad de sugerencias que se devuelven para cada nodo de destinatario ambiguo en la respuesta. El valor de MaxAmbiguousRecipients está limitado a un rango de 0–9999. Cada nodo destinatario ambiguo recibe solo esta cantidad de sugerencias y no más. El cliente puede utilizar el recuento de destinatarios, devuelto en RecipientCount, para determinar el número total de sugerencias disponibles para ese destinatario. |
| [MaxCertificates](../../aspose.email.clients.activesync.transportlayer/resolverecipientsoptions/maxcertificates) { get; set; } | Limita la cantidad total de certificados que devuelve el servidor. El valor de MaxCertificates está limitado a un rango de 0 a 9999. Este límite garantiza que ningún destinatario individual reciba un conjunto incompleto de certificados. Si se alcanza el límite MaxCertificates al enumerar certificados para una lista de direcciones, esa lista de direcciones no obtendrá ningún certificado y se devolverá un valor de estado de 8. |
| [Picture](../../aspose.email.clients.activesync.transportlayer/resolverecipientsoptions/picture) { get; set; } | Indica que el cliente está solicitando que se devuelvan fotos de contacto en la respuesta del servidor. La imagen no es compatible cuando la versión del protocolo es 12.1 o 14.0. Contiene los datos relacionados con las fotos de contacto. |

### Ver también

* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->