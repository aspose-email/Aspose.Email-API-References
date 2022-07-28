---
title: Ping
second_title: Référence de l'API Aspose.Email pour .NET
description: La commande Ping est utilisée pour demander au serveur de surveiller les dossiers spécifiés à la recherche de modifications nécessitant une resynchronisation du client.
type: docs
weight: 140
url: /fr/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/ping/
---
## Ping(string, FolderClass) {#ping_5}

La commande Ping est utilisée pour demander au serveur de surveiller les dossiers spécifiés à la recherche de modifications nécessitant une resynchronisation du client.

```csharp
public string[] Ping(string serverId, FolderClass fClass)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| serverId | String | L'élément Id est un élément enfant obligatoire de l'élément Dossier dans les demandes de commande Ping qui spécifie l'ID de serveur du dossier à surveiller. |
| fClass | FolderClass | L'élément Class est un élément enfant obligatoire de l'élément Folder dans les demandes de commande Ping qui spécifie la classe de contenu du dossier à surveiller. |

### Return_Value

Tableau de dossiers dans lesquels des modifications ont été découvertes

### Voir également

* enum [FolderClass](../../folderclass)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Assemblée [Aspose.Email](../../../)

---

## Ping(int, string, FolderClass) {#ping_3}

La commande Ping est utilisée pour demander au serveur de surveiller les dossiers spécifiés à la recherche de modifications nécessitant une resynchronisation du client.

```csharp
public string[] Ping(int heartbeatInterval, string serverId, FolderClass fClass)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| heartbeatInterval | Int32 | Le HeartbeatInterval spécifie la durée, en secondes, que le serveur DEVRAIT attendre avant d'envoyer une réponse si aucun nouvel élément n'est ajouté à l'ensemble de dossiers spécifié. |
| serverId | String | L'élément Id est un élément enfant obligatoire de l'élément Dossier dans les demandes de commande Ping qui spécifie l'ID de serveur du dossier à surveiller. |
| fClass | FolderClass | L'élément Class est un élément enfant obligatoire de l'élément Folder dans les demandes de commande Ping qui spécifie la classe de contenu du dossier à surveiller. |

### Return_Value

Tableau de dossiers dans lesquels des modifications ont été découvertes

### Voir également

* enum [FolderClass](../../folderclass)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Assemblée [Aspose.Email](../../../)

---

## Ping(params PingParameter[]) {#ping}

La commande Ping est utilisée pour demander au serveur de surveiller les dossiers spécifiés à la recherche de modifications nécessitant une resynchronisation du client.

```csharp
public string[] Ping(params PingParameter[] pingParameters)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pingParameters | PingParameter[] | Paramètres de ping |

### Return_Value

Tableau de dossiers dans lesquels des modifications ont été découvertes

### Voir également

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Assemblée [Aspose.Email](../../../)

---

## Ping(int, params PingParameter[]) {#ping_1}

La commande Ping est utilisée pour demander au serveur de surveiller les dossiers spécifiés à la recherche de modifications nécessitant une resynchronisation du client.

```csharp
public string[] Ping(int heartbeatInterval, params PingParameter[] pingParameters)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| heartbeatInterval | Int32 | Le HeartbeatInterval spécifie la durée, en secondes, que le serveur DEVRAIT attendre avant d'envoyer une réponse si aucun nouvel élément n'est ajouté à l'ensemble de dossiers spécifié. |
| pingParameters | PingParameter[] | Paramètres de ping |

### Return_Value

Tableau de dossiers dans lesquels des modifications ont été découvertes

### Voir également

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Assemblée [Aspose.Email](../../../)

---

## Ping(IEnumerable&lt;PingParameter&gt;) {#ping_4}

La commande Ping est utilisée pour demander au serveur de surveiller les dossiers spécifiés à la recherche de modifications nécessitant une resynchronisation du client.

```csharp
public string[] Ping(IEnumerable<PingParameter> pingParameters)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pingParameters | IEnumerable`1 | Paramètres de ping |

### Return_Value

Tableau de dossiers dans lesquels des modifications ont été découvertes

### Voir également

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Assemblée [Aspose.Email](../../../)

---

## Ping(int, IEnumerable&lt;PingParameter&gt;) {#ping_2}

La commande Ping est utilisée pour demander au serveur de surveiller les dossiers spécifiés à la recherche de modifications nécessitant une resynchronisation du client.

```csharp
public string[] Ping(int heartbeatInterval, IEnumerable<PingParameter> pingParameters)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| heartbeatInterval | Int32 | Le HeartbeatInterval spécifie la durée, en secondes, que le serveur DEVRAIT attendre avant d'envoyer une réponse si aucun nouvel élément n'est ajouté à l'ensemble de dossiers spécifié. |
| pingParameters | IEnumerable`1 | Paramètres de ping |

### Return_Value

Tableau de dossiers dans lesquels des modifications ont été découvertes

### Voir également

* class [PingParameter](../../pingparameter)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
