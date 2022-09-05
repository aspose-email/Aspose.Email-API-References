---
title: IGmailClient
second_title: Aspose.Email for .NET API 参考
description: 代表 Gmail 客户端的接口
type: docs
weight: 15790
url: /zh/net/aspose.email.clients.google/igmailclient/
---
## IGmailClient interface

代表 Gmail 客户端的接口

```csharp
public interface IGmailClient : IBaseGmailClient
```

## 方法

| 姓名 | 描述 |
| --- | --- |
| [ClearCalendar](../../aspose.email.clients.google/igmailclient/clearcalendar)(string) | 清除日历。 |
| [CreateAccessRule](../../aspose.email.clients.google/igmailclient/createaccessrule)(string, AccessControlRule) | 创建访问规则 |
| [CreateAppointment](../../aspose.email.clients.google/igmailclient/createappointment)(string, Appointment) | 创建约会。 |
| [CreateCalendar](../../aspose.email.clients.google/igmailclient/createcalendar#createcalendar)(Calendar) | 创建一个日历。 |
| [CreateCalendar](../../aspose.email.clients.google/igmailclient/createcalendar#createcalendar_1)(Calendar, bool) | 创建一个日历。 |
| [CreateContact](../../aspose.email.clients.google/igmailclient/createcontact#createcontact)(Contact) | 为指定的电子邮件创建联系人 |
| [CreateContact](../../aspose.email.clients.google/igmailclient/createcontact#createcontact_1)(Contact, string) | 为指定的电子邮件创建联系人 |
| [CreateContactPhoto](../../aspose.email.clients.google/igmailclient/createcontactphoto)(Contact, byte[]) | 创建联系人照片 |
| [DeleteAccessRule](../../aspose.email.clients.google/igmailclient/deleteaccessrule)(string, string) | 删除访问规则 |
| [DeleteAppointment](../../aspose.email.clients.google/igmailclient/deleteappointment)(string, string) | 删除约会。 |
| [DeleteCalendar](../../aspose.email.clients.google/igmailclient/deletecalendar)(string) | 删除日历。 |
| [DeleteContact](../../aspose.email.clients.google/igmailclient/deletecontact)(string) | 删除指定的联系人 |
| [DeleteContactPhoto](../../aspose.email.clients.google/igmailclient/deletecontactphoto)(ContactPhoto) | 删除联系人照片 |
| [FetchAccessRule](../../aspose.email.clients.google/igmailclient/fetchaccessrule)(string, string) | 获取访问规则 |
| [FetchAppointment](../../aspose.email.clients.google/igmailclient/fetchappointment)(string, string) | 按标识符获取约会。 |
| [FetchCalendar](../../aspose.email.clients.google/igmailclient/fetchcalendar)(string) | 按标识符获取日历。 |
| [GetAllContacts](../../aspose.email.clients.google/igmailclient/getallcontacts)() | 获取所有联系人。 |
| [GetAllGroups](../../aspose.email.clients.google/igmailclient/getallgroups)() | 获取所有联系人组。 |
| [GetColors](../../aspose.email.clients.google/igmailclient/getcolors)() | 获取颜色信息 |
| [GetContact](../../aspose.email.clients.google/igmailclient/getcontact#getcontact)(Contact) | 联系刷新[`Contact`](../../aspose.email.personalinfo/contact)对象，代表 gmail 的联系人当操作失败时 |
| [GetContact](../../aspose.email.clients.google/igmailclient/getcontact#getcontact_1)(string) | 获取联系人 |
| [GetContactsFromGroup](../../aspose.email.clients.google/igmailclient/getcontactsfromgroup)(string) | 获取属于指定组的联系人。 |
| [GetFreebusyInfo](../../aspose.email.clients.google/igmailclient/getfreebusyinfo)(FreebusyQuery) | 获取忙/闲信息 |
| [GetPhoto](../../aspose.email.clients.google/igmailclient/getphoto#getphoto)(ContactPhoto) | 获取联系人照片 |
| [GetPhoto](../../aspose.email.clients.google/igmailclient/getphoto#getphoto_1)(string) | 获取联系人照片 |
| [GetSetting](../../aspose.email.clients.google/igmailclient/getsetting)(string) | 按名称获取设置 |
| [GetSettings](../../aspose.email.clients.google/igmailclient/getsettings)() | 获取设置字典 |
| [ImportAppointment](../../aspose.email.clients.google/igmailclient/importappointment)(string, Appointment) | 将约会导入日历 |
| [ListAccessRules](../../aspose.email.clients.google/igmailclient/listaccessrules)(string) | 获取访问规则列表 |
| [ListAppointmentInstances](../../aspose.email.clients.google/igmailclient/listappointmentinstances)(string, string) | 获取日历的约会实例列表。 |
| [ListAppointments](../../aspose.email.clients.google/igmailclient/listappointments)(string) | 获取日历的约会列表。 |
| [ListCalendars](../../aspose.email.clients.google/igmailclient/listcalendars#listcalendars)() | 获取日历数组。 |
| [ListCalendars](../../aspose.email.clients.google/igmailclient/listcalendars#listcalendars_1)(AccessRole, bool) | 获取日历数组。 |
| [MoveAppointment](../../aspose.email.clients.google/igmailclient/moveappointment#moveappointment)(string, string, string) | 将约会移动到另一个日历。 |
| [MoveAppointment](../../aspose.email.clients.google/igmailclient/moveappointment#moveappointment_1)(string, string, string, bool) | 将约会移动到另一个日历。 |
| [UpdateAccessRule](../../aspose.email.clients.google/igmailclient/updateaccessrule)(string, AccessControlRule) | 更新访问规则 |
| [UpdateAppointment](../../aspose.email.clients.google/igmailclient/updateappointment)(string, Appointment) | 更新约会。 |
| [UpdateCalendar](../../aspose.email.clients.google/igmailclient/updatecalendar#updatecalendar)(Calendar) | 更新日历 |
| [UpdateCalendar](../../aspose.email.clients.google/igmailclient/updatecalendar#updatecalendar_1)(Calendar, bool) | 更新日历 |
| [UpdateContact](../../aspose.email.clients.google/igmailclient/updatecontact)(Contact) | 更新联系人 |
| [UpdateContactPhoto](../../aspose.email.clients.google/igmailclient/updatecontactphoto)(ContactPhoto) | 创建或更新联系人照片 |

### 也可以看看

* interface [IBaseGmailClient](../ibasegmailclient)
* 命名空间 [Aspose.Email.Clients.Google](../../aspose.email.clients.google)
* 部件 [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
