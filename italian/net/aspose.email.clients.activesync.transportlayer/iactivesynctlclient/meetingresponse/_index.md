---
title: MeetingResponse
second_title: Aspose.Email per riferimento all'API .NET
description: Accetta accetta provvisoriamente o rifiuta una convocazione di riunione nella cartella Posta in arrivo o nella cartella Calendario dellutente.
type: docs
weight: 110
url: /it/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse/
---
## MeetingResponse(UserResponse, string, string) {#meetingresponse}

Accetta, accetta provvisoriamente o rifiuta una convocazione di riunione nella cartella Posta in arrivo o nella cartella Calendario dell'utente.

```csharp
public MeetingResponseResult MeetingResponse(UserResponse userResponse, string collectionId, 
    string requestId)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| userResponse | UserResponse | Indica se la riunione viene accettata, accettata provvisoriamente o rifiutata. |
| collectionId | String | Specifica la cartella che contiene la richiesta di riunione. Facoltativo se è incluso LongId. Il valore CollectionId può avere una lunghezza massima di 64 caratteri. |
| requestId | String | Specifica l'ID del server dell'elemento del messaggio di richiesta di riunione. Facoltativo se LongId è incluso. Il valore RequestId può avere una lunghezza massima di 64 caratteri. |

### Valore di ritorno

Restituisce l'oggetto MeetingResponseResult.

### Guarda anche

* class [MeetingResponseResult](../../meetingresponseresult)
* enum [UserResponse](../../userresponse)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assemblea [Aspose.Email](../../../)

---

## MeetingResponse(UserResponse, string, string, string, string) {#meetingresponse_1}

Accetta, accetta provvisoriamente o rifiuta una convocazione di riunione nella cartella Posta in arrivo o nella cartella Calendario dell'utente.

```csharp
public MeetingResponseResult MeetingResponse(UserResponse userResponse, string collectionId, 
    string requestId, string longId, string instanceId)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| userResponse | UserResponse | Indica se la riunione viene accettata, accettata provvisoriamente o rifiutata. |
| collectionId | String | Specifica la cartella che contiene la richiesta di riunione. Facoltativo se è incluso LongId. Il valore CollectionId può avere una lunghezza massima di 64 caratteri. |
| requestId | String | Specifica l'ID del server dell'elemento del messaggio di richiesta di riunione. Facoltativo se LongId è incluso. Il valore RequestId può avere una lunghezza massima di 64 caratteri. |
| longId | String | Specifica l'ID lungo per la convocazione di riunione di origine, che viene restituito nel messaggio di risposta al comando di ricerca. Se LongId è presente, CollectionId, InstanceId e RequestId non sono presenti. Il valore LongId può avere una lunghezza massima di 256 caratteri. |
| instanceId | String | Specifica l'istanza della riunione ricorrente da modificare. InstanceId non è supportato quando la versione del protocollo è 12.1 o 14.0. Viene restituito un valore di stato pari a 2 se l'elemento InstanceId è incluso nelle richieste in cui la versione del protocollo è 12.1 o 14.0. InstanceId contiene l'ora di inizio dell'appuntamento o dell'istanza della riunione da modificare. Se InstanceId non è incluso nella richiesta MeetingResponse, l'azione deve essere eseguita su ogni istanza dell'elemento ricorrente. InstanceId può specificare l'ora di inizio di un'eccezione per un appuntamento o una riunione ricorrente. L'InstanceId può essere utilizzato con LongId per identificare un elemento del calendario, oppure può essere utilizzato con CollectionId e RequestId per identificare un elemento del calendario. Il formato del valore InstanceId è una stringa in formato dateTime con i separatori di punteggiatura, per esempio, 2010-04-08T18:16:00.000Z. Se il valore InstanceId specificato non è nel formato corretto, il server risponde con un valore dell'elemento Status di 104. Se il valore InstanceId specifica una riunione non ricorrente, il server risponde con un valore dell'elemento Status di 146. |

### Valore di ritorno

Restituisce l'oggetto MeetingResponseResult.

### Guarda anche

* class [MeetingResponseResult](../../meetingresponseresult)
* enum [UserResponse](../../userresponse)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assemblea [Aspose.Email](../../../)

---

## MeetingResponse(params MeetingResponseRequest[]) {#meetingresponse_2}

Accetta, accetta provvisoriamente o rifiuta una convocazione di riunione nella cartella Posta in arrivo o nella cartella Calendario dell'utente.

```csharp
public MeetingResponseResult[] MeetingResponse(params MeetingResponseRequest[] request)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| request | MeetingResponseRequest[] | Matrice di oggetti MeetingResponseRequest |

### Valore di ritorno

Restituisce una matrice di oggetti MeetingResponseResult.

### Guarda anche

* class [MeetingResponseResult](../../meetingresponseresult)
* class [MeetingResponseRequest](../../meetingresponserequest)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assemblea [Aspose.Email](../../../)

---

## MeetingResponse(IEnumerable&lt;MeetingResponseRequest&gt;) {#meetingresponse_3}

Accetta, accetta provvisoriamente o rifiuta una convocazione di riunione nella cartella Posta in arrivo o nella cartella Calendario dell'utente.

```csharp
public MeetingResponseResult[] MeetingResponse(IEnumerable<MeetingResponseRequest> request)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| request | IEnumerable`1 | Enumerazione degli oggetti MeetingResponseRequest |

### Valore di ritorno

Restituisce una matrice di oggetti MeetingResponseResult.

### Guarda anche

* class [MeetingResponseResult](../../meetingresponseresult)
* class [MeetingResponseRequest](../../meetingresponserequest)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
