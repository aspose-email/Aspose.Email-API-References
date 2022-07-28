---
title: IGmailClient
second_title: Aspose.Email بريد إلكتروني لمرجع .NET API
description: يمثل واجهة عميل Gmail
type: docs
weight: 15790
url: /ar/net/aspose.email.clients.google/igmailclient/
---
## IGmailClient interface

يمثل واجهة عميل Gmail

```csharp
public interface IGmailClient : IBaseGmailClient
```

## طُرق

| اسم | وصف |
| --- | --- |
| [ClearCalendar](../../aspose.email.clients.google/igmailclient/clearcalendar)(string) | يمسح تقويمًا . |
| [CreateAccessRule](../../aspose.email.clients.google/igmailclient/createaccessrule)(string, AccessControlRule) | إنشاء قاعدة وصول |
| [CreateAppointment](../../aspose.email.clients.google/igmailclient/createappointment)(string, Appointment) | إنشاء موعد . |
| [CreateCalendar](../../aspose.email.clients.google/igmailclient/createcalendar#createcalendar)(Calendar) | إنشاء تقويم . |
| [CreateCalendar](../../aspose.email.clients.google/igmailclient/createcalendar#createcalendar_1)(Calendar, bool) | إنشاء تقويم . |
| [CreateContact](../../aspose.email.clients.google/igmailclient/createcontact#createcontact)(Contact) | إنشاء جهة اتصال للبريد الإلكتروني المحدد |
| [CreateContact](../../aspose.email.clients.google/igmailclient/createcontact#createcontact_1)(Contact, string) | إنشاء جهة اتصال للبريد الإلكتروني المحدد |
| [CreateContactPhoto](../../aspose.email.clients.google/igmailclient/createcontactphoto)(Contact, byte[]) | ينشئ جهة اتصال photo |
| [DeleteAccessRule](../../aspose.email.clients.google/igmailclient/deleteaccessrule)(string, string) | حذف قاعدة الوصول |
| [DeleteAppointment](../../aspose.email.clients.google/igmailclient/deleteappointment)(string, string) | حذف موعد . |
| [DeleteCalendar](../../aspose.email.clients.google/igmailclient/deletecalendar)(string) | حذف تقويم . |
| [DeleteContact](../../aspose.email.clients.google/igmailclient/deletecontact)(string) | حذف جهة اتصال محددة |
| [DeleteContactPhoto](../../aspose.email.clients.google/igmailclient/deletecontactphoto)(ContactPhoto) | حذف جهة الاتصال photo |
| [FetchAccessRule](../../aspose.email.clients.google/igmailclient/fetchaccessrule)(string, string) | جلب قاعدة الوصول |
| [FetchAppointment](../../aspose.email.clients.google/igmailclient/fetchappointment)(string, string) | جلب الموعد عن طريق المعرف . |
| [FetchCalendar](../../aspose.email.clients.google/igmailclient/fetchcalendar)(string) | جلب التقويم حسب المعرف. |
| [GetAllContacts](../../aspose.email.clients.google/igmailclient/getallcontacts)() | جلب جميع جهات الاتصال. |
| [GetAllGroups](../../aspose.email.clients.google/igmailclient/getallgroups)() | جلب جميع مجموعات جهات الاتصال. |
| [GetColors](../../aspose.email.clients.google/igmailclient/getcolors)() | يحصل على معلومات اللون |
| [GetContact](../../aspose.email.clients.google/igmailclient/getcontact#getcontact)(Contact) | اتصل للتحديث[`Contact`](../../aspose.email.personalinfo/contact) الكائن ، الذي يمثل جهة اتصال gmail عندما تفشل العملية |
| [GetContact](../../aspose.email.clients.google/igmailclient/getcontact#getcontact_1)(string) | جلب contact |
| [GetContactsFromGroup](../../aspose.email.clients.google/igmailclient/getcontactsfromgroup)(string) | جلب جهات الاتصال التي تنتمي إلى المجموعة المحددة. |
| [GetFreebusyInfo](../../aspose.email.clients.google/igmailclient/getfreebusyinfo)(FreebusyQuery) | الحصول على معلومات التوفر / الانشغال |
| [GetPhoto](../../aspose.email.clients.google/igmailclient/getphoto#getphoto)(ContactPhoto) | إحضار صورة جهة اتصال |
| [GetPhoto](../../aspose.email.clients.google/igmailclient/getphoto#getphoto_1)(string) | إحضار صورة جهة اتصال |
| [GetSetting](../../aspose.email.clients.google/igmailclient/getsetting)(string) | يحصل على الإعدادات بالاسم |
| [GetSettings](../../aspose.email.clients.google/igmailclient/getsettings)() | يحصل على قاموس الإعدادات |
| [ImportAppointment](../../aspose.email.clients.google/igmailclient/importappointment)(string, Appointment) | موعد الواردات إلى التقويم |
| [ListAccessRules](../../aspose.email.clients.google/igmailclient/listaccessrules)(string) | يحصل على قائمة قواعد الوصول |
| [ListAppointmentInstances](../../aspose.email.clients.google/igmailclient/listappointmentinstances)(string, string) | يحصل على قائمة بنماذج الموعد للتقويم . |
| [ListAppointments](../../aspose.email.clients.google/igmailclient/listappointments)(string) | يحصل على قائمة بمواعيد التقويم . |
| [ListCalendars](../../aspose.email.clients.google/igmailclient/listcalendars#listcalendars)() | الحصول على مجموعة من التقاويم . |
| [ListCalendars](../../aspose.email.clients.google/igmailclient/listcalendars#listcalendars_1)(AccessRole, bool) | الحصول على مجموعة من التقاويم . |
| [MoveAppointment](../../aspose.email.clients.google/igmailclient/moveappointment#moveappointment)(string, string, string) | نقل موعد إلى تقويم آخر. |
| [MoveAppointment](../../aspose.email.clients.google/igmailclient/moveappointment#moveappointment_1)(string, string, string, bool) | نقل موعد إلى تقويم آخر. |
| [UpdateAccessRule](../../aspose.email.clients.google/igmailclient/updateaccessrule)(string, AccessControlRule) | قاعدة وصول التحديثات |
| [UpdateAppointment](../../aspose.email.clients.google/igmailclient/updateappointment)(string, Appointment) | يقوم بتحديث موعد . |
| [UpdateCalendar](../../aspose.email.clients.google/igmailclient/updatecalendar#updatecalendar)(Calendar) | يحدّث تقويمًا |
| [UpdateCalendar](../../aspose.email.clients.google/igmailclient/updatecalendar#updatecalendar_1)(Calendar, bool) | يحدّث تقويمًا |
| [UpdateContact](../../aspose.email.clients.google/igmailclient/updatecontact)(Contact) | اتصل بتحديثات |
| [UpdateContactPhoto](../../aspose.email.clients.google/igmailclient/updatecontactphoto)(ContactPhoto) | إنشاء أو تحديث جهة الاتصال photo |

### أنظر أيضا

* interface [IBaseGmailClient](../ibasegmailclient)
* مساحة الاسم [Aspose.Email.Clients.Google](../../aspose.email.clients.google)
* المجسم [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
