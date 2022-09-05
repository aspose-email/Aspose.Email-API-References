---
title: IGmailClient
second_title: Справочник по Aspose.Email для .NET API
description: Представляет интерфейс клиента Gmail
type: docs
weight: 15790
url: /ru/net/aspose.email.clients.google/igmailclient/
---
## IGmailClient interface

Представляет интерфейс клиента Gmail

```csharp
public interface IGmailClient : IBaseGmailClient
```

## Методы

| Имя | Описание |
| --- | --- |
| [ClearCalendar](../../aspose.email.clients.google/igmailclient/clearcalendar)(string) | Очищает календарь. |
| [CreateAccessRule](../../aspose.email.clients.google/igmailclient/createaccessrule)(string, AccessControlRule) | Создает правило доступа |
| [CreateAppointment](../../aspose.email.clients.google/igmailclient/createappointment)(string, Appointment) | Создает встречу. |
| [CreateCalendar](../../aspose.email.clients.google/igmailclient/createcalendar#createcalendar)(Calendar) | Создает календарь. |
| [CreateCalendar](../../aspose.email.clients.google/igmailclient/createcalendar#createcalendar_1)(Calendar, bool) | Создает календарь. |
| [CreateContact](../../aspose.email.clients.google/igmailclient/createcontact#createcontact)(Contact) | Создает контакт для указанного адреса электронной почты |
| [CreateContact](../../aspose.email.clients.google/igmailclient/createcontact#createcontact_1)(Contact, string) | Создает контакт для указанного адреса электронной почты |
| [CreateContactPhoto](../../aspose.email.clients.google/igmailclient/createcontactphoto)(Contact, byte[]) | Создает фото контакта |
| [DeleteAccessRule](../../aspose.email.clients.google/igmailclient/deleteaccessrule)(string, string) | Удаляет правило доступа |
| [DeleteAppointment](../../aspose.email.clients.google/igmailclient/deleteappointment)(string, string) | Удаляет встречу. |
| [DeleteCalendar](../../aspose.email.clients.google/igmailclient/deletecalendar)(string) | Удаляет календарь. |
| [DeleteContact](../../aspose.email.clients.google/igmailclient/deletecontact)(string) | Удаляет указанный контакт |
| [DeleteContactPhoto](../../aspose.email.clients.google/igmailclient/deletecontactphoto)(ContactPhoto) | Удаляет фото контакта |
| [FetchAccessRule](../../aspose.email.clients.google/igmailclient/fetchaccessrule)(string, string) | Получает правило доступа |
| [FetchAppointment](../../aspose.email.clients.google/igmailclient/fetchappointment)(string, string) | Выбирает встречу по идентификатору. |
| [FetchCalendar](../../aspose.email.clients.google/igmailclient/fetchcalendar)(string) | Выбирает календарь по идентификатору. |
| [GetAllContacts](../../aspose.email.clients.google/igmailclient/getallcontacts)() | Извлекает все контакты. |
| [GetAllGroups](../../aspose.email.clients.google/igmailclient/getallgroups)() | Извлекает все группы контактов. |
| [GetColors](../../aspose.email.clients.google/igmailclient/getcolors)() | Получает информацию о цвете |
| [GetContact](../../aspose.email.clients.google/igmailclient/getcontact#getcontact)(Contact) | Свяжитесь, чтобы обновить[`Contact`](../../aspose.email.personalinfo/contact) объект, представляющий контакт gmail когда операция не удалась |
| [GetContact](../../aspose.email.clients.google/igmailclient/getcontact#getcontact_1)(string) | Получает контакт |
| [GetContactsFromGroup](../../aspose.email.clients.google/igmailclient/getcontactsfromgroup)(string) | Выбирает контакты, принадлежащие указанной группе. |
| [GetFreebusyInfo](../../aspose.email.clients.google/igmailclient/getfreebusyinfo)(FreebusyQuery) | Получает информацию о занятости |
| [GetPhoto](../../aspose.email.clients.google/igmailclient/getphoto#getphoto)(ContactPhoto) | Извлекает фото контакта |
| [GetPhoto](../../aspose.email.clients.google/igmailclient/getphoto#getphoto_1)(string) | Извлекает фото контакта |
| [GetSetting](../../aspose.email.clients.google/igmailclient/getsetting)(string) | Получает настройки по имени |
| [GetSettings](../../aspose.email.clients.google/igmailclient/getsettings)() | Получить словарь настроек |
| [ImportAppointment](../../aspose.email.clients.google/igmailclient/importappointment)(string, Appointment) | Импорт встречи в календарь |
| [ListAccessRules](../../aspose.email.clients.google/igmailclient/listaccessrules)(string) | Получает список правил доступа |
| [ListAppointmentInstances](../../aspose.email.clients.google/igmailclient/listappointmentinstances)(string, string) | Получает список экземпляров встречи для календаря. |
| [ListAppointments](../../aspose.email.clients.google/igmailclient/listappointments)(string) | Получает список встреч для календаря. |
| [ListCalendars](../../aspose.email.clients.google/igmailclient/listcalendars#listcalendars)() | Получает массив календарей. |
| [ListCalendars](../../aspose.email.clients.google/igmailclient/listcalendars#listcalendars_1)(AccessRole, bool) | Получает массив календарей. |
| [MoveAppointment](../../aspose.email.clients.google/igmailclient/moveappointment#moveappointment)(string, string, string) | Перемещает встречу в другой календарь. |
| [MoveAppointment](../../aspose.email.clients.google/igmailclient/moveappointment#moveappointment_1)(string, string, string, bool) | Перемещает встречу в другой календарь. |
| [UpdateAccessRule](../../aspose.email.clients.google/igmailclient/updateaccessrule)(string, AccessControlRule) | Обновляет правило доступа |
| [UpdateAppointment](../../aspose.email.clients.google/igmailclient/updateappointment)(string, Appointment) | Обновляет встречу. |
| [UpdateCalendar](../../aspose.email.clients.google/igmailclient/updatecalendar#updatecalendar)(Calendar) | Обновляет календарь |
| [UpdateCalendar](../../aspose.email.clients.google/igmailclient/updatecalendar#updatecalendar_1)(Calendar, bool) | Обновляет календарь |
| [UpdateContact](../../aspose.email.clients.google/igmailclient/updatecontact)(Contact) | Обновляет контакт |
| [UpdateContactPhoto](../../aspose.email.clients.google/igmailclient/updatecontactphoto)(ContactPhoto) | Создает или обновляет контакт photo |

### Смотрите также

* interface [IBaseGmailClient](../ibasegmailclient)
* пространство имен [Aspose.Email.Clients.Google](../../aspose.email.clients.google)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
