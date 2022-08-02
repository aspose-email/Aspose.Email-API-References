---
title: MeetingResponse
second_title: Referencia de la API de Aspose.Email para .NET
description: Acepta acepta tentativamente o rechaza una solicitud de reunión en la carpeta Bandeja de entrada o la carpeta Calendario del usuario.
type: docs
weight: 110
url: /es/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse/
---
## MeetingResponse(UserResponse, string, string) {#meetingresponse}

Acepta, acepta tentativamente o rechaza una solicitud de reunión en la carpeta Bandeja de entrada o la carpeta Calendario del usuario.

```csharp
public MeetingResponseResult MeetingResponse(UserResponse userResponse, string collectionId, 
    string requestId)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| userResponse | UserResponse | Indica si la reunión se acepta, se acepta provisionalmente o se rechaza. |
| collectionId | String | Especifica la carpeta que contiene la solicitud de reunión. Opcional si se incluye LongId. El valor de CollectionId puede tener hasta 64 caracteres de longitud. |
| requestId | String | Especifica el ID del servidor del elemento del mensaje de solicitud de reunión. Opcional si se incluye LongId. El valor de RequestId puede tener hasta 64 caracteres de longitud. |

### Valor_devuelto

Devuelve el objeto MeetingResponseResult.

### Ver también

* class [MeetingResponseResult](../../meetingresponseresult)
* enum [UserResponse](../../userresponse)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* asamblea [Aspose.Email](../../../)

---

## MeetingResponse(UserResponse, string, string, string, string) {#meetingresponse_1}

Acepta, acepta tentativamente o rechaza una solicitud de reunión en la carpeta Bandeja de entrada o la carpeta Calendario del usuario.

```csharp
public MeetingResponseResult MeetingResponse(UserResponse userResponse, string collectionId, 
    string requestId, string longId, string instanceId)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| userResponse | UserResponse | Indica si la reunión se acepta, se acepta provisionalmente o se rechaza. |
| collectionId | String | Especifica la carpeta que contiene la solicitud de reunión. Opcional si se incluye LongId. El valor de CollectionId puede tener hasta 64 caracteres de longitud. |
| requestId | String | Especifica el ID del servidor del elemento del mensaje de solicitud de reunión. Opcional si se incluye LongId. El valor de RequestId puede tener hasta 64 caracteres de longitud. |
| longId | String | Especifica el ID largo de la convocatoria de reunión de origen, que se devuelve en el mensaje de respuesta del comando de búsqueda. Si LongId está presente, CollectionId, InstanceId y RequestId no están presentes. El valor LongId puede tener hasta 256 caracteres de longitud. |
| instanceId | String | Especifica la instancia de la reunión periódica que se modificará. InstanceId no se admite cuando la versión del protocolo es 12.1 o 14.0. Se devuelve un valor de Estado de 2 si el elemento InstanceId se incluye en las solicitudes en las que la versión del protocolo es 12.1 o 14.0. El InstanceId contiene la hora de inicio de la instancia de cita o reunión que se va a modificar. Si InstanceId no está incluido en la solicitud MeetingResponse, entonces la acción se debe realizar en cada instancia del elemento recurrente. InstanceId puede especificar la hora de inicio de una excepción a una cita o reunión periódica. InstanceId se puede usar con LongId para identificar un elemento de calendario, o se puede usar con CollectionId y RequestId para identificar un elemento de calendario. El formato del valor de InstanceId es una cadena en formato de fecha y hora con los separadores de puntuación, para ejemplo, 2010-04-08T18:16:00.000Z. Si el valor de InstanceId especificado no tiene el formato adecuado, el servidor responde con un valor de elemento de estado de 104. Si el valor de InstanceId especifica una reunión no periódica, el servidor responde con un valor de elemento de estado de 146. |

### Valor_devuelto

Devuelve el objeto MeetingResponseResult.

### Ver también

* class [MeetingResponseResult](../../meetingresponseresult)
* enum [UserResponse](../../userresponse)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* asamblea [Aspose.Email](../../../)

---

## MeetingResponse(params MeetingResponseRequest[]) {#meetingresponse_2}

Acepta, acepta tentativamente o rechaza una solicitud de reunión en la carpeta Bandeja de entrada o la carpeta Calendario del usuario.

```csharp
public MeetingResponseResult[] MeetingResponse(params MeetingResponseRequest[] request)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| request | MeetingResponseRequest[] | Matriz de objetos MeetingResponseRequest |

### Valor_devuelto

Devuelve una matriz de objetos MeetingResponseResult.

### Ver también

* class [MeetingResponseResult](../../meetingresponseresult)
* class [MeetingResponseRequest](../../meetingresponserequest)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* asamblea [Aspose.Email](../../../)

---

## MeetingResponse(IEnumerable&lt;MeetingResponseRequest&gt;) {#meetingresponse_3}

Acepta, acepta tentativamente o rechaza una solicitud de reunión en la carpeta Bandeja de entrada o la carpeta Calendario del usuario.

```csharp
public MeetingResponseResult[] MeetingResponse(IEnumerable<MeetingResponseRequest> request)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| request | IEnumerable`1 | Enumeración de objetos MeetingResponseRequest |

### Valor_devuelto

Devuelve una matriz de objetos MeetingResponseResult.

### Ver también

* class [MeetingResponseResult](../../meetingresponseresult)
* class [MeetingResponseRequest](../../meetingresponserequest)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
