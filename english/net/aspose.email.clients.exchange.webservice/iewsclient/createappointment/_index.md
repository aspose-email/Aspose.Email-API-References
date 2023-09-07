---
title: IEWSClient.CreateAppointment
second_title: Aspose.Email for .NET API Reference
description: IEWSClient method. Creates appointment
type: docs
weight: 460
url: /net/aspose.email.clients.exchange.webservice/iewsclient/createappointment/
---
## CreateAppointment(Appointment) {#createappointment}

Creates appointment.

```csharp
public string CreateAppointment(Appointment appointment)
```

| Parameter | Type | Description |
| --- | --- | --- |
| appointment | Appointment | Calendar appointment. |

### Return Value

Returns appointment UID

### See Also

* class [Appointment](../../../aspose.email.calendar/appointment/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## CreateAppointment(Appointment, string) {#createappointment_1}

Creates appointment.

```csharp
public string CreateAppointment(Appointment appointment, string folderUri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| appointment | Appointment | Calendar appointment. |
| folderUri | String | An uri of appointments parent folder. |

### Return Value

Returns appointment UID

### See Also

* class [Appointment](../../../aspose.email.calendar/appointment/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## CreateAppointment(MapiCalendar, string, bool) {#createappointment_2}

Creates appointment.

```csharp
public string CreateAppointment(MapiCalendar appointment, string folderUri, 
    bool suppressInvitations)
```

| Parameter | Type | Description |
| --- | --- | --- |
| appointment | MapiCalendar | Calendar appointment. |
| folderUri | String | An uri of appointments parent folder. |
| suppressInvitations | Boolean | If true, invitations won't be sent to attendees. |

### Return Value

Returns PidLidGlobalObjectId as base64 string

### See Also

* class [MapiCalendar](../../../aspose.email.mapi/mapicalendar/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)


