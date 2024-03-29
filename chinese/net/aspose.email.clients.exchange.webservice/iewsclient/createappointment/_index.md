---
title: CreateAppointment
second_title: Aspose.Email for .NET API 参考
description: 创建约会
type: docs
weight: 460
url: /zh/net/aspose.email.clients.exchange.webservice/iewsclient/createappointment/
---
## CreateAppointment(Appointment) {#createappointment}

创建约会。

```csharp
public string CreateAppointment(Appointment appointment)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| appointment | Appointment | 日历约会。 |

### 返回值

返回预约 UID

### 也可以看看

* class [Appointment](../../../aspose.email.calendar/appointment)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## CreateAppointment(Appointment, string) {#createappointment_1}

创建约会。

```csharp
public string CreateAppointment(Appointment appointment, string folderUri)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| appointment | Appointment | 日历约会。 |
| folderUri | String | 约会父文件夹的 uri。 |

### 返回值

返回预约 UID

### 也可以看看

* class [Appointment](../../../aspose.email.calendar/appointment)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

---

## CreateAppointment(MapiCalendar, string, bool) {#createappointment_4}

创建约会。

```csharp
public string CreateAppointment(MapiCalendar appointment, string folderUri, 
    bool suppressInvitations)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| appointment | MapiCalendar | 日历约会。 |
| folderUri | String | 约会父文件夹的 uri。 |
| suppressInvitations | Boolean | 如果为真，则不会向与会者发送邀请。 |

### 返回值

将 PidLidGlobalObjectId 作为 base64 字符串返回

### 也可以看看

* class [MapiCalendar](../../../aspose.email.mapi/mapicalendar)
* interface [IEWSClient](../../iewsclient)
* 命名空间 [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* 部件 [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
