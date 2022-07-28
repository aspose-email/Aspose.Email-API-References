---
title: IGmailClient
second_title: Aspose.Email for .NET API Referansı
description: Gmail client arayüzünü temsil eder
type: docs
weight: 15790
url: /tr/net/aspose.email.clients.google/igmailclient/
---
## IGmailClient interface

Gmail client arayüzünü temsil eder

```csharp
public interface IGmailClient : IBaseGmailClient
```

## yöntemler

| İsim | Tanım |
| --- | --- |
| [ClearCalendar](../../aspose.email.clients.google/igmailclient/clearcalendar)(string) | Bir takvimi temizler. |
| [CreateAccessRule](../../aspose.email.clients.google/igmailclient/createaccessrule)(string, AccessControlRule) | Erişim kuralı oluşturur |
| [CreateAppointment](../../aspose.email.clients.google/igmailclient/createappointment)(string, Appointment) | Bir randevu oluşturur. |
| [CreateCalendar](../../aspose.email.clients.google/igmailclient/createcalendar#createcalendar)(Calendar) | Bir takvim oluşturur. |
| [CreateCalendar](../../aspose.email.clients.google/igmailclient/createcalendar#createcalendar_1)(Calendar, bool) | Bir takvim oluşturur. |
| [CreateContact](../../aspose.email.clients.google/igmailclient/createcontact#createcontact)(Contact) | Belirtilen email için kişi oluşturur |
| [CreateContact](../../aspose.email.clients.google/igmailclient/createcontact#createcontact_1)(Contact, string) | Belirtilen email için kişi oluşturur |
| [CreateContactPhoto](../../aspose.email.clients.google/igmailclient/createcontactphoto)(Contact, byte[]) | Kişi photo oluşturur |
| [DeleteAccessRule](../../aspose.email.clients.google/igmailclient/deleteaccessrule)(string, string) | Erişim kuralını siler |
| [DeleteAppointment](../../aspose.email.clients.google/igmailclient/deleteappointment)(string, string) | Bir randevuyu siler. |
| [DeleteCalendar](../../aspose.email.clients.google/igmailclient/deletecalendar)(string) | Bir takvimi siler. |
| [DeleteContact](../../aspose.email.clients.google/igmailclient/deletecontact)(string) | Belirtilen kişiyi siler |
| [DeleteContactPhoto](../../aspose.email.clients.google/igmailclient/deletecontactphoto)(ContactPhoto) | Kişi photo siler |
| [FetchAccessRule](../../aspose.email.clients.google/igmailclient/fetchaccessrule)(string, string) | Erişim kuralı getirir |
| [FetchAppointment](../../aspose.email.clients.google/igmailclient/fetchappointment)(string, string) | Tanımlayıcıya göre randevuyu getirir. |
| [FetchCalendar](../../aspose.email.clients.google/igmailclient/fetchcalendar)(string) | Tanımlayıcıya göre takvimi getirir. |
| [GetAllContacts](../../aspose.email.clients.google/igmailclient/getallcontacts)() | Tüm kişileri getirir. |
| [GetAllGroups](../../aspose.email.clients.google/igmailclient/getallgroups)() | Tüm kişi gruplarını getirir. |
| [GetColors](../../aspose.email.clients.google/igmailclient/getcolors)() | Renk bilgilerini alır |
| [GetContact](../../aspose.email.clients.google/igmailclient/getcontact#getcontact)(Contact) | Yenilemek için iletişime geçin[`Contact`](../../aspose.email.personalinfo/contact) gmail kişisini temsil eden nesne işlem başarısız olduğunda |
| [GetContact](../../aspose.email.clients.google/igmailclient/getcontact#getcontact_1)(string) | contact 'yi getirir |
| [GetContactsFromGroup](../../aspose.email.clients.google/igmailclient/getcontactsfromgroup)(string) | Belirtilen gruba ait kişileri getirir. |
| [GetFreebusyInfo](../../aspose.email.clients.google/igmailclient/getfreebusyinfo)(FreebusyQuery) | Serbest/meşgul bilgilerini alır |
| [GetPhoto](../../aspose.email.clients.google/igmailclient/getphoto#getphoto)(ContactPhoto) | Bir kişi photo getirir |
| [GetPhoto](../../aspose.email.clients.google/igmailclient/getphoto#getphoto_1)(string) | Bir kişi photo getirir |
| [GetSetting](../../aspose.email.clients.google/igmailclient/getsetting)(string) | Ayarları adına göre alır |
| [GetSettings](../../aspose.email.clients.google/igmailclient/getsettings)() | Ayarlar sözlüğünü alır |
| [ImportAppointment](../../aspose.email.clients.google/igmailclient/importappointment)(string, Appointment) | Randevuyu takvime aktarır |
| [ListAccessRules](../../aspose.email.clients.google/igmailclient/listaccessrules)(string) | Erişim kurallarının listesini alır |
| [ListAppointmentInstances](../../aspose.email.clients.google/igmailclient/listappointmentinstances)(string, string) | Takvim için randevu örneklerinin listesini alır. |
| [ListAppointments](../../aspose.email.clients.google/igmailclient/listappointments)(string) | Takvim için randevuların listesini alır. |
| [ListCalendars](../../aspose.email.clients.google/igmailclient/listcalendars#listcalendars)() | Takvim dizisini alır. |
| [ListCalendars](../../aspose.email.clients.google/igmailclient/listcalendars#listcalendars_1)(AccessRole, bool) | Takvim dizisini alır. |
| [MoveAppointment](../../aspose.email.clients.google/igmailclient/moveappointment#moveappointment)(string, string, string) | Randevuyu başka bir takvime taşır. |
| [MoveAppointment](../../aspose.email.clients.google/igmailclient/moveappointment#moveappointment_1)(string, string, string, bool) | Randevuyu başka bir takvime taşır. |
| [UpdateAccessRule](../../aspose.email.clients.google/igmailclient/updateaccessrule)(string, AccessControlRule) | Erişim kuralını günceller |
| [UpdateAppointment](../../aspose.email.clients.google/igmailclient/updateappointment)(string, Appointment) | Bir randevuyu günceller. |
| [UpdateCalendar](../../aspose.email.clients.google/igmailclient/updatecalendar#updatecalendar)(Calendar) | Bir takvimi günceller |
| [UpdateCalendar](../../aspose.email.clients.google/igmailclient/updatecalendar#updatecalendar_1)(Calendar, bool) | Bir takvimi günceller |
| [UpdateContact](../../aspose.email.clients.google/igmailclient/updatecontact)(Contact) | kişisini günceller |
| [UpdateContactPhoto](../../aspose.email.clients.google/igmailclient/updatecontactphoto)(ContactPhoto) | Kişiyi oluşturur veya günceller photo |

### Ayrıca bakınız

* interface [IBaseGmailClient](../ibasegmailclient)
* ad alanı [Aspose.Email.Clients.Google](../../aspose.email.clients.google)
* toplantı [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
