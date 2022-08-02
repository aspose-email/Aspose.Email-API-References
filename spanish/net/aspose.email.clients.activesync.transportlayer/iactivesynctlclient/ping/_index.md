---
title: Ping
second_title: Referencia de la API de Aspose.Email para .NET
description: El comando Ping se utiliza para solicitar que el servidor supervise las carpetas especificadas en busca de cambios que requieran que el cliente vuelva a sincronizar.
type: docs
weight: 140
url: /es/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping/
---
## Ping(string, FolderClass) {#ping_5}

El comando Ping se utiliza para solicitar que el servidor supervise las carpetas especificadas en busca de cambios que requieran que el cliente vuelva a sincronizar.

```csharp
public string[] Ping(string serverId, FolderClass fClass)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| serverId | String | El elemento Id es un elemento secundario obligatorio del elemento Folder en las solicitudes de comando Ping que especifica el ID del servidor de la carpeta que se supervisará. |
| fClass | FolderClass | El elemento Clase es un elemento secundario obligatorio del elemento Carpeta en las solicitudes de comando Ping que especifica la clase de contenido de la carpeta que se supervisará. |

### Valor_devuelto

Matriz de carpetas donde se han descubierto cambios

### Ver también

* enum [FolderClass](../../folderclass)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* asamblea [Aspose.Email](../../../)

---

## Ping(int, string, FolderClass) {#ping_3}

El comando Ping se utiliza para solicitar que el servidor supervise las carpetas especificadas en busca de cambios que requieran que el cliente vuelva a sincronizar.

```csharp
public string[] Ping(int heartbeatInterval, string serverId, FolderClass fClass)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| heartbeatInterval | Int32 | HeartbeatInterval especifica el tiempo, en segundos, que el servidor DEBE esperar antes de enviar una respuesta si no se agregan elementos nuevos al conjunto de carpetas especificado. |
| serverId | String | El elemento Id es un elemento secundario obligatorio del elemento Folder en las solicitudes de comando Ping que especifica el ID del servidor de la carpeta que se supervisará. |
| fClass | FolderClass | El elemento Clase es un elemento secundario obligatorio del elemento Carpeta en las solicitudes de comando Ping que especifica la clase de contenido de la carpeta que se supervisará. |

### Valor_devuelto

Matriz de carpetas donde se han descubierto cambios

### Ver también

* enum [FolderClass](../../folderclass)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* asamblea [Aspose.Email](../../../)

---

## Ping(params PingParameter[]) {#ping}

El comando Ping se utiliza para solicitar que el servidor supervise las carpetas especificadas en busca de cambios que requieran que el cliente vuelva a sincronizar.

```csharp
public string[] Ping(params PingParameter[] pingParameters)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pingParameters | PingParameter[] | Parámetros de ping |

### Valor_devuelto

Matriz de carpetas donde se han descubierto cambios

### Ver también

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* asamblea [Aspose.Email](../../../)

---

## Ping(int, params PingParameter[]) {#ping_1}

El comando Ping se utiliza para solicitar que el servidor supervise las carpetas especificadas en busca de cambios que requieran que el cliente vuelva a sincronizar.

```csharp
public string[] Ping(int heartbeatInterval, params PingParameter[] pingParameters)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| heartbeatInterval | Int32 | HeartbeatInterval especifica el tiempo, en segundos, que el servidor DEBE esperar antes de enviar una respuesta si no se agregan elementos nuevos al conjunto de carpetas especificado. |
| pingParameters | PingParameter[] | Parámetros de ping |

### Valor_devuelto

Matriz de carpetas donde se han descubierto cambios

### Ver también

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* asamblea [Aspose.Email](../../../)

---

## Ping(IEnumerable&lt;PingParameter&gt;) {#ping_4}

El comando Ping se utiliza para solicitar que el servidor supervise las carpetas especificadas en busca de cambios que requieran que el cliente vuelva a sincronizar.

```csharp
public string[] Ping(IEnumerable<PingParameter> pingParameters)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pingParameters | IEnumerable`1 | Parámetros de ping |

### Valor_devuelto

Matriz de carpetas donde se han descubierto cambios

### Ver también

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* asamblea [Aspose.Email](../../../)

---

## Ping(int, IEnumerable&lt;PingParameter&gt;) {#ping_2}

El comando Ping se utiliza para solicitar que el servidor supervise las carpetas especificadas en busca de cambios que requieran que el cliente vuelva a sincronizar.

```csharp
public string[] Ping(int heartbeatInterval, IEnumerable<PingParameter> pingParameters)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| heartbeatInterval | Int32 | HeartbeatInterval especifica el tiempo, en segundos, que el servidor DEBE esperar antes de enviar una respuesta si no se agregan elementos nuevos al conjunto de carpetas especificado. |
| pingParameters | IEnumerable`1 | Parámetros de ping |

### Valor_devuelto

Matriz de carpetas donde se han descubierto cambios

### Ver también

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
