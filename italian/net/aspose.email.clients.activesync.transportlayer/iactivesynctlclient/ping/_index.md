---
title: Ping
second_title: Aspose.Email per riferimento all'API .NET
description: Il comando Ping viene utilizzato per richiedere al server di monitorare le cartelle specificate per le modifiche che richiederebbero la risincronizzazione del client.
type: docs
weight: 140
url: /it/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping/
---
## Ping(string, FolderClass) {#ping_5}

Il comando Ping viene utilizzato per richiedere al server di monitorare le cartelle specificate per le modifiche che richiederebbero la risincronizzazione del client.

```csharp
public string[] Ping(string serverId, FolderClass fClass)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| serverId | String | L'elemento Id è un elemento figlio obbligatorio dell'elemento Folder nelle richieste di comando Ping che specifica l'ID server della cartella da monitorare. |
| fClass | FolderClass | L'elemento Class è un elemento figlio obbligatorio dell'elemento Folder nelle richieste di comando Ping che specifica la classe di contenuto della cartella da monitorare. |

### Valore di ritorno

Matrice di cartelle in cui sono state rilevate le modifiche

### Guarda anche

* enum [FolderClass](../../folderclass)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assemblea [Aspose.Email](../../../)

---

## Ping(int, string, FolderClass) {#ping_3}

Il comando Ping viene utilizzato per richiedere al server di monitorare le cartelle specificate per le modifiche che richiederebbero la risincronizzazione del client.

```csharp
public string[] Ping(int heartbeatInterval, string serverId, FolderClass fClass)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| heartbeatInterval | Int32 | HeartbeatInterval specifica il periodo di tempo, in secondi, che il server DOVREBBE attendere prima di inviare una risposta se non vengono aggiunti nuovi elementi all'insieme di cartelle specificato. |
| serverId | String | L'elemento Id è un elemento figlio obbligatorio dell'elemento Folder nelle richieste di comando Ping che specifica l'ID server della cartella da monitorare. |
| fClass | FolderClass | L'elemento Class è un elemento figlio obbligatorio dell'elemento Folder nelle richieste di comando Ping che specifica la classe di contenuto della cartella da monitorare. |

### Valore di ritorno

Matrice di cartelle in cui sono state rilevate le modifiche

### Guarda anche

* enum [FolderClass](../../folderclass)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assemblea [Aspose.Email](../../../)

---

## Ping(params PingParameter[]) {#ping}

Il comando Ping viene utilizzato per richiedere al server di monitorare le cartelle specificate per le modifiche che richiederebbero la risincronizzazione del client.

```csharp
public string[] Ping(params PingParameter[] pingParameters)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pingParameters | PingParameter[] | Parametri di ping |

### Valore di ritorno

Matrice di cartelle in cui sono state rilevate le modifiche

### Guarda anche

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assemblea [Aspose.Email](../../../)

---

## Ping(int, params PingParameter[]) {#ping_1}

Il comando Ping viene utilizzato per richiedere al server di monitorare le cartelle specificate per le modifiche che richiederebbero la risincronizzazione del client.

```csharp
public string[] Ping(int heartbeatInterval, params PingParameter[] pingParameters)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| heartbeatInterval | Int32 | HeartbeatInterval specifica il periodo di tempo, in secondi, che il server DOVREBBE attendere prima di inviare una risposta se non vengono aggiunti nuovi elementi all'insieme di cartelle specificato. |
| pingParameters | PingParameter[] | Parametri di ping |

### Valore di ritorno

Matrice di cartelle in cui sono state rilevate le modifiche

### Guarda anche

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assemblea [Aspose.Email](../../../)

---

## Ping(IEnumerable&lt;PingParameter&gt;) {#ping_4}

Il comando Ping viene utilizzato per richiedere al server di monitorare le cartelle specificate per le modifiche che richiederebbero la risincronizzazione del client.

```csharp
public string[] Ping(IEnumerable<PingParameter> pingParameters)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pingParameters | IEnumerable`1 | Parametri di ping |

### Valore di ritorno

Matrice di cartelle in cui sono state rilevate le modifiche

### Guarda anche

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assemblea [Aspose.Email](../../../)

---

## Ping(int, IEnumerable&lt;PingParameter&gt;) {#ping_2}

Il comando Ping viene utilizzato per richiedere al server di monitorare le cartelle specificate per le modifiche che richiederebbero la risincronizzazione del client.

```csharp
public string[] Ping(int heartbeatInterval, IEnumerable<PingParameter> pingParameters)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| heartbeatInterval | Int32 | HeartbeatInterval specifica il periodo di tempo, in secondi, che il server DOVREBBE attendere prima di inviare una risposta se non vengono aggiunti nuovi elementi all'insieme di cartelle specificato. |
| pingParameters | IEnumerable`1 | Parametri di ping |

### Valore di ritorno

Matrice di cartelle in cui sono state rilevate le modifiche

### Guarda anche

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
