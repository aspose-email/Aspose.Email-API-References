---
title: MeetingResponse
second_title: Référence de l'API Aspose.Email pour .NET
description: Accepte accepte provisoirement ou refuse une demande de réunion dans le dossier Boîte de réception ou Calendrier de lutilisateur.
type: docs
weight: 110
url: /fr/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse/
---
## MeetingResponse(UserResponse, string, string) {#meetingresponse}

Accepte, accepte provisoirement ou refuse une demande de réunion dans le dossier Boîte de réception ou Calendrier de l'utilisateur.

```csharp
public MeetingResponseResult MeetingResponse(UserResponse userResponse, string collectionId, 
    string requestId)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| userResponse | UserResponse | Indique si la réunion est acceptée, provisoirement acceptée ou refusée. |
| collectionId | String | Spécifie le dossier qui contient la demande de réunion. Facultatif si LongId est inclus. La valeur CollectionId peut comporter jusqu'à 64 caractères. |
| requestId | String | Spécifie l'ID de serveur de l'élément de message de demande de réunion. Facultatif si LongId est inclus. La valeur RequestId peut comporter jusqu'à 64 caractères. |

### Return_Value

Renvoie l'objet MeetingResponseResult.

### Voir également

* class [MeetingResponseResult](../../meetingresponseresult)
* enum [UserResponse](../../userresponse)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Assemblée [Aspose.Email](../../../)

---

## MeetingResponse(UserResponse, string, string, string, string) {#meetingresponse_1}

Accepte, accepte provisoirement ou refuse une demande de réunion dans le dossier Boîte de réception ou Calendrier de l'utilisateur.

```csharp
public MeetingResponseResult MeetingResponse(UserResponse userResponse, string collectionId, 
    string requestId, string longId, string instanceId)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| userResponse | UserResponse | Indique si la réunion est acceptée, provisoirement acceptée ou refusée. |
| collectionId | String | Spécifie le dossier qui contient la demande de réunion. Facultatif si LongId est inclus. La valeur CollectionId peut comporter jusqu'à 64 caractères. |
| requestId | String | Spécifie l'ID de serveur de l'élément de message de demande de réunion. Facultatif si LongId est inclus. La valeur RequestId peut comporter jusqu'à 64 caractères. |
| longId | String | Spécifie l'ID long de la demande de réunion source, qui est renvoyé dans le message de réponse de la commande de recherche. Si le LongId est présent, le CollectionId, l'InstanceId et le RequestId ne sont pas présents. La valeur LongId peut comporter jusqu'à 256 caractères. |
| instanceId | String | Spécifie l'instance de la réunion récurrente à modifier. L'InstanceId n'est pas prise en charge lorsque la version du protocole est 12.1 ou 14.0. Une valeur Status de 2 est renvoyée si l'élément InstanceId est inclus dans les requêtes dont la version du protocole est 12.1 ou 14.0. L'InstanceId contient l'heure de début de l'instance de rendez-vous ou de réunion à modifier. Si InstanceId n'est pas inclus dans la demande MeetingResponse, l'action doit être entreprise sur chaque instance de l'élément récurrent. L'InstanceId peut spécifier l'heure de début d'une exception à un rendez-vous ou une réunion récurrents. Le InstanceId peut être utilisé avec le LongId pour identifier un élément de calendrier, ou il peut être utilisé avec le CollectionId et le RequestId pour identifier un élément de calendrier. Le format de la valeur InstanceId est une chaîne au format dateTime avec les séparateurs de ponctuation, pour exemple, 2010-04-08T18:16:00.000Z. Si la valeur InstanceId spécifiée n'est pas au format approprié, le serveur répond avec une valeur d'élément Status de 104. Si la valeur InstanceId spécifie une réunion non récurrente, le serveur répond avec une valeur d'élément Status de 146. |

### Return_Value

Renvoie l'objet MeetingResponseResult.

### Voir également

* class [MeetingResponseResult](../../meetingresponseresult)
* enum [UserResponse](../../userresponse)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Assemblée [Aspose.Email](../../../)

---

## MeetingResponse(params MeetingResponseRequest[]) {#meetingresponse_2}

Accepte, accepte provisoirement ou refuse une demande de réunion dans le dossier Boîte de réception ou Calendrier de l'utilisateur.

```csharp
public MeetingResponseResult[] MeetingResponse(params MeetingResponseRequest[] request)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| request | MeetingResponseRequest[] | Tableau d'objets MeetingResponseRequest |

### Return_Value

Renvoie un tableau d'objets MeetingResponseResult.

### Voir également

* class [MeetingResponseResult](../../meetingresponseresult)
* class [MeetingResponseRequest](../../meetingresponserequest)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Assemblée [Aspose.Email](../../../)

---

## MeetingResponse(IEnumerable&lt;MeetingResponseRequest&gt;) {#meetingresponse_3}

Accepte, accepte provisoirement ou refuse une demande de réunion dans le dossier Boîte de réception ou Calendrier de l'utilisateur.

```csharp
public MeetingResponseResult[] MeetingResponse(IEnumerable<MeetingResponseRequest> request)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| request | IEnumerable`1 | Énumération des objets MeetingResponseRequest |

### Return_Value

Renvoie un tableau d'objets MeetingResponseResult.

### Voir également

* class [MeetingResponseResult](../../meetingresponseresult)
* class [MeetingResponseRequest](../../meetingresponserequest)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* espace de noms [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Assemblée [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
