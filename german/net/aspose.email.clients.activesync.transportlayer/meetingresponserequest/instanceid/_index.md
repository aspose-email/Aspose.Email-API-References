---
title: InstanceId
second_title: Aspose.Email für .NET-API-Referenz
description: Gibt die Instanz des wiederkehrenden Meetings an das geändert werden soll. Die InstanceId wird nicht unterstützt wenn die Protokollversion 12.1 oder 14.0 ist. Ein Statuswert von 2 wird zurückgegeben wenn das InstanceId-Element in Anforderungen enthalten ist in denen die Protokollversion 12.1 oder 14.0 ist. Die InstanceId enthält die Startzeit des zu ändernden Termins oder der Besprechungsinstanz. Wenn die InstanceId nicht in der MeetingResponse-Anforderung enthalten ist muss die Aktion für jede Instanz des wiederkehrenden Elements ausgeführt werden. Die InstanceId kann die Startzeit einer Ausnahme für einen wiederkehrenden Termin oder eine Besprechung angeben. Die InstanceId kann mit LongId verwendet werden um ein Kalenderelement zu identifizieren oder sie kann mit CollectionId und RequestId verwendet werden um ein Kalenderelement zu identifizieren. Das Format des InstanceId-Werts ist eine Zeichenfolge im dateTime-Format mit den Interpunktionstrennzeichen z Beispiel 2010-04-08T181600.000Z. Wenn der angegebene InstanceId-Wert nicht das richtige Format hat antwortet der Server mit einem Statuselementwert von 104. Wenn der InstanceId-Wert ein einmaliges Meeting angibt antwortet der Server mit einem Statuselementwert von 146.
type: docs
weight: 30
url: /de/net/aspose.email.clients.activesync.transportlayer/meetingresponserequest/instanceid/
---
## MeetingResponseRequest.InstanceId property

Gibt die Instanz des wiederkehrenden Meetings an, das geändert werden soll. Die InstanceId wird nicht unterstützt, wenn die Protokollversion 12.1 oder 14.0 ist. Ein Statuswert von 2 wird zurückgegeben, wenn das InstanceId-Element in Anforderungen enthalten ist, in denen die Protokollversion 12.1 oder 14.0 ist. Die InstanceId enthält die Startzeit des zu ändernden Termins oder der Besprechungsinstanz. Wenn die InstanceId nicht in der MeetingResponse-Anforderung enthalten ist, muss die Aktion für jede Instanz des wiederkehrenden Elements ausgeführt werden. Die InstanceId kann die Startzeit einer Ausnahme für einen wiederkehrenden Termin oder eine Besprechung angeben. Die InstanceId kann mit LongId verwendet werden, um ein Kalenderelement zu identifizieren, oder sie kann mit CollectionId und RequestId verwendet werden, um ein Kalenderelement zu identifizieren. Das Format des InstanceId-Werts ist eine Zeichenfolge im dateTime-Format mit den Interpunktionstrennzeichen, z Beispiel: 2010-04-08T18:16:00.000Z. Wenn der angegebene InstanceId-Wert nicht das richtige Format hat, antwortet der Server mit einem Statuselementwert von 104. Wenn der InstanceId-Wert ein einmaliges Meeting angibt, antwortet der Server mit einem Statuselementwert von 146.

```csharp
public string InstanceId { get; set; }
```

### Siehe auch

* class [MeetingResponseRequest](../../meetingresponserequest)
* namensraum [Aspose.Email.Clients.ActiveSync.TransportLayer](../../meetingresponserequest)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->