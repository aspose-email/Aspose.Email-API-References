---
title: MeetingResponse
second_title: Aspose.Email für .NET-API-Referenz
description: Nimmt eine Besprechungsanfrage im Ordner Posteingang oder Kalender des Benutzers an nimmt sie mit Vorbehalt an oder lehnt sie ab.
type: docs
weight: 110
url: /de/net/aspose.email.clients.activesync.transportlayer/iactivesynctlclient/meetingresponse/
---
## MeetingResponse(UserResponse, string, string) {#meetingresponse}

Nimmt eine Besprechungsanfrage im Ordner „Posteingang“ oder „Kalender“ des Benutzers an, nimmt sie mit Vorbehalt an oder lehnt sie ab.

```csharp
public MeetingResponseResult MeetingResponse(UserResponse userResponse, string collectionId, 
    string requestId)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| userResponse | UserResponse | Gibt an, ob die Besprechung angenommen, vorläufig angenommen oder abgelehnt wird. |
| collectionId | String | Gibt den Ordner an, der die Besprechungsanfrage enthält. Optional, wenn LongId enthalten ist. Der CollectionId-Wert kann bis zu 64 Zeichen lang sein. |
| requestId | String | Gibt die Server-ID des Nachrichtenelements der Besprechungsanfrage an. Optional, wenn LongId enthalten ist. Der RequestId-Wert kann bis zu 64 Zeichen lang sein. |

### Rückgabewert

Gibt das MeetingResponseResult-Objekt zurück.

### Siehe auch

* class [MeetingResponseResult](../../meetingresponseresult)
* enum [UserResponse](../../userresponse)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Montage [Aspose.Email](../../../)

---

## MeetingResponse(UserResponse, string, string, string, string) {#meetingresponse_1}

Nimmt eine Besprechungsanfrage im Ordner „Posteingang“ oder „Kalender“ des Benutzers an, nimmt sie mit Vorbehalt an oder lehnt sie ab.

```csharp
public MeetingResponseResult MeetingResponse(UserResponse userResponse, string collectionId, 
    string requestId, string longId, string instanceId)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| userResponse | UserResponse | Gibt an, ob die Besprechung angenommen, vorläufig angenommen oder abgelehnt wird. |
| collectionId | String | Gibt den Ordner an, der die Besprechungsanfrage enthält. Optional, wenn LongId enthalten ist. Der CollectionId-Wert kann bis zu 64 Zeichen lang sein. |
| requestId | String | Gibt die Server-ID des Nachrichtenelements der Besprechungsanfrage an. Optional, wenn LongId enthalten ist. Der RequestId-Wert kann bis zu 64 Zeichen lang sein. |
| longId | String | Gibt die lange ID für die Quellbesprechungsanfrage an, die in der Antwortnachricht des Suchbefehls zurückgegeben wird. Wenn die LongId vorhanden ist, sind CollectionId, InstanceId und RequestId nicht vorhanden. Der LongId-Wert kann bis zu 256 Zeichen lang sein. |
| instanceId | String | Gibt die Instanz des wiederkehrenden Meetings an, das geändert werden soll. Die InstanceId wird nicht unterstützt, wenn die Protokollversion 12.1 oder 14.0 ist. Ein Statuswert von 2 wird zurückgegeben, wenn das InstanceId-Element in Anforderungen enthalten ist, in denen die Protokollversion 12.1 oder 14.0 ist. Die InstanceId enthält die Startzeit des zu ändernden Termins oder der Besprechungsinstanz. Wenn die InstanceId nicht in der MeetingResponse-Anforderung enthalten ist, muss die Aktion für jede Instanz des wiederkehrenden Elements ausgeführt werden. Die InstanceId kann die Startzeit einer Ausnahme für einen wiederkehrenden Termin oder eine Besprechung angeben. Die InstanceId kann mit LongId verwendet werden, um ein Kalenderelement zu identifizieren, oder sie kann mit CollectionId und RequestId verwendet werden, um ein Kalenderelement zu identifizieren. Das Format des InstanceId-Werts ist eine Zeichenfolge im dateTime-Format mit den Interpunktionstrennzeichen, z Beispiel: 2010-04-08T18:16:00.000Z. Wenn der angegebene InstanceId-Wert nicht das richtige Format hat, antwortet der Server mit einem Statuselementwert von 104. Wenn der InstanceId-Wert ein einmaliges Meeting angibt, antwortet der Server mit einem Statuselementwert von 146. |

### Rückgabewert

Gibt das MeetingResponseResult-Objekt zurück.

### Siehe auch

* class [MeetingResponseResult](../../meetingresponseresult)
* enum [UserResponse](../../userresponse)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Montage [Aspose.Email](../../../)

---

## MeetingResponse(params MeetingResponseRequest[]) {#meetingresponse_2}

Nimmt eine Besprechungsanfrage im Ordner „Posteingang“ oder „Kalender“ des Benutzers an, nimmt sie mit Vorbehalt an oder lehnt sie ab.

```csharp
public MeetingResponseResult[] MeetingResponse(params MeetingResponseRequest[] request)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| request | MeetingResponseRequest[] | Array von MeetingResponseRequest-Objekten |

### Rückgabewert

Gibt ein Array von MeetingResponseResult-Objekten zurück.

### Siehe auch

* class [MeetingResponseResult](../../meetingresponseresult)
* class [MeetingResponseRequest](../../meetingresponserequest)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Montage [Aspose.Email](../../../)

---

## MeetingResponse(IEnumerable&lt;MeetingResponseRequest&gt;) {#meetingresponse_3}

Nimmt eine Besprechungsanfrage im Ordner „Posteingang“ oder „Kalender“ des Benutzers an, nimmt sie mit Vorbehalt an oder lehnt sie ab.

```csharp
public MeetingResponseResult[] MeetingResponse(IEnumerable<MeetingResponseRequest> request)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| request | IEnumerable`1 | Aufzählung von MeetingResponseRequest-Objekten |

### Rückgabewert

Gibt ein Array von MeetingResponseResult-Objekten zurück.

### Siehe auch

* class [MeetingResponseResult](../../meetingresponseresult)
* class [MeetingResponseRequest](../../meetingresponserequest)
* interface [IActiveSyncTLClient](../../iactivesynctlclient)
* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../iactivesynctlclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
