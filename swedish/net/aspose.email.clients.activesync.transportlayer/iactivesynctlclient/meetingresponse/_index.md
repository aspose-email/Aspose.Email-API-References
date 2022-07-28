---
title: MeetingResponse
second_title: Aspose.Email för .NET API-referens
description: Accepterar accepterar preliminärt eller avslår en mötesförfrågan i användarens inkorgsmapp eller kalendermapp.
type: docs
weight: 110
url: /sv/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse/
---
## MeetingResponse(UserResponse, string, string) {#meetingresponse}

Accepterar, accepterar preliminärt eller avslår en mötesförfrågan i användarens inkorgsmapp eller kalendermapp.

```csharp
public MeetingResponseResult MeetingResponse(UserResponse userResponse, string collectionId, 
    string requestId)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userResponse | UserResponse | Anger om mötet accepteras, preliminärt accepteras eller avvisas. |
| collectionId | String | Anger mappen som innehåller mötesförfrågan. Valfritt om LongId ingår. CollectionId-värdet kan vara upp till 64 tecken långt. |
| requestId | String | Anger server-ID för meddelandeobjektet för mötesbegäran. Valfritt om LongId ingår. Värdet RequestId kan vara upp till 64 tecken långt. |

### Returvärde

Returnerar MeetingResponseResult-objekt.

### Se även

* class [MeetingResponseResult](../../meetingresponseresult)
* enum [UserResponse](../../userresponse)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* hopsättning [Aspose.Email](../../../)

---

## MeetingResponse(UserResponse, string, string, string, string) {#meetingresponse_1}

Accepterar, accepterar preliminärt eller avslår en mötesförfrågan i användarens inkorgsmapp eller kalendermapp.

```csharp
public MeetingResponseResult MeetingResponse(UserResponse userResponse, string collectionId, 
    string requestId, string longId, string instanceId)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userResponse | UserResponse | Anger om mötet accepteras, preliminärt accepteras eller avvisas. |
| collectionId | String | Anger mappen som innehåller mötesförfrågan. Valfritt om LongId ingår. CollectionId-värdet kan vara upp till 64 tecken långt. |
| requestId | String | Anger server-ID för meddelandeobjektet för mötesbegäran. Valfritt om LongId ingår. Värdet RequestId kan vara upp till 64 tecken långt. |
| longId | String | Anger det långa ID:t för källmötesbegäran, som returneras i sökkommandotsvarsmeddelandet. Om LongId finns finns inte CollectionId, InstanceId och RequestId. LongId-värdet kan vara upp till 256 tecken långt. |
| instanceId | String | Anger instansen av det återkommande mötet som ska ändras. InstanceId stöds inte när protokollversionen är 12.1 eller 14.0. Ett statusvärde på 2 returneras om InstanceId-elementet ingår i förfrågningar där protokollversionen är 12.1 eller 14.0. InstanceId innehåller starttiden för mötet eller mötesinstansen som ska ändras. Om InstanceId inte ingår i MeetingResponse-begäran, ska åtgärden vidtas på varje instans av det återkommande objektet. InstanceId kan ange starttiden för ett undantag från ett återkommande möte eller möte. InstanceId kan användas med LongId för att identifiera ett kalenderobjekt, eller så kan det användas med CollectionId och RequestId för att identifiera ett kalenderobjekt. Formatet för InstanceId-värdet är en sträng i formatet dateTime med skiljetecken, t.ex. exempel, 2010-04-08T18:16:00.000Z. Om det angivna InstanceId-värdet inte är i rätt format svarar servern med ett Statuselementvärde på 104. Om InstanceId-värdet anger ett engångsmöte svarar servern med ett Statuselementvärde på 146. |

### Returvärde

Returnerar MeetingResponseResult-objekt.

### Se även

* class [MeetingResponseResult](../../meetingresponseresult)
* enum [UserResponse](../../userresponse)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* hopsättning [Aspose.Email](../../../)

---

## MeetingResponse(params MeetingResponseRequest[]) {#meetingresponse_2}

Accepterar, accepterar preliminärt eller avslår en mötesförfrågan i användarens inkorgsmapp eller kalendermapp.

```csharp
public MeetingResponseResult[] MeetingResponse(params MeetingResponseRequest[] request)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| request | MeetingResponseRequest[] | Array av MeetingResponseRequest-objekt |

### Returvärde

Returnerar array av MeetingResponseResult-objekt.

### Se även

* class [MeetingResponseResult](../../meetingresponseresult)
* class [MeetingResponseRequest](../../meetingresponserequest)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* hopsättning [Aspose.Email](../../../)

---

## MeetingResponse(IEnumerable&lt;MeetingResponseRequest&gt;) {#meetingresponse_3}

Accepterar, accepterar preliminärt eller avslår en mötesförfrågan i användarens inkorgsmapp eller kalendermapp.

```csharp
public MeetingResponseResult[] MeetingResponse(IEnumerable<MeetingResponseRequest> request)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| request | IEnumerable`1 | Uppräkning av MeetingResponseRequest-objekt |

### Returvärde

Returnerar array av MeetingResponseResult-objekt.

### Se även

* class [MeetingResponseResult](../../meetingresponseresult)
* class [MeetingResponseRequest](../../meetingresponserequest)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
