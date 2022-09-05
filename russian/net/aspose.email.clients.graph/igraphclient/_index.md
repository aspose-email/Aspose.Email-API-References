---
title: IGraphClient
second_title: Справочник по Aspose.Email для .NET API
description: Представляет интерфейс для клиента Exchange REST.
type: docs
weight: 15950
url: /ru/net/aspose.email.clients.graph/igraphclient/
---
## IGraphClient interface

Представляет интерфейс для клиента Exchange REST.

```csharp
public interface IGraphClient : IDisposable
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [MultipleServicesTokenProvider](../../aspose.email.clients.graph/igraphclient/multipleservicestokenprovider) { get; set; } | Получает или задает объект, позволяющий получить токен доступа OAuth. |
| [Proxy](../../aspose.email.clients.graph/igraphclient/proxy) { get; set; } | Получает или задает данные для прокси-доступа к серверу Exchange. |
| [Resource](../../aspose.email.clients.graph/igraphclient/resource) { get; set; } | Получает или задает тип ресурса. |
| [ResourceId](../../aspose.email.clients.graph/igraphclient/resourceid) { get; set; } | Получает или устанавливает идентификатор ресурса. Например, для пользователей это может быть имя участника-пользователя (UPN) или идентификатор пользователя |
| [TenantId](../../aspose.email.clients.graph/igraphclient/tenantid) { get; set; } | Получает или задает идентификатор арендатора |
| [Timeout](../../aspose.email.clients.graph/igraphclient/timeout) { get; set; } | Получает или задает количество миллисекунд ожидания до истечения времени ожидания операции. Значение по умолчанию — 100 000 миллисекунд (100 секунд). |
| [TokenProvider](../../aspose.email.clients.graph/igraphclient/tokenprovider) { get; set; } | Получает или задает объект, позволяющий получить токен доступа OAuth. |

## Методы

| Имя | Описание |
| --- | --- |
| [CopyFolder](../../aspose.email.clients.graph/igraphclient/copyfolder)(string, string) | Скопируйте почтовую папку и ее содержимое в другую почтовую папку. |
| [CopyMessage](../../aspose.email.clients.graph/igraphclient/copymessage)(string, string) | Скопируйте сообщение в другую почтовую папку. |
| [CopyNotebook](../../aspose.email.clients.graph/igraphclient/copynotebook)(string, string, string) | Копирует записную книжку в папку Notebooks в целевой библиотеке документов. Папка создается, если она не существует. Для операций копирования вы следуете асинхронному шаблону вызова: сначала вызываете действие копирования, а затем опрашиваете конечную точку операции для получения результата. Разрешения Для вызова требуется одно из следующих разрешений. этот API. Делегированный (рабочая или учебная учетная запись) Notes.Create, Notes.ReadWrite, Notes.ReadWrite.All Делегированный (личная учетная запись Microsoft) Notes.Create, Notes.ReadWrite Application Notes.ReadWrite.All |
| [CreateAttachment](../../aspose.email.clients.graph/igraphclient/createattachment)(string, MapiAttachment) | Создает новое вложение для указанного item |
| [CreateCategory](../../aspose.email.clients.graph/igraphclient/createcategory)(string, CategoryPreset) | Создает[`OutlookCategory`](../outlookcategory) объект в основном списке категорий пользователя. |
| [CreateFolder](../../aspose.email.clients.graph/igraphclient/createfolder#createfolder)(string) | Создать новую папку. |
| [CreateFolder](../../aspose.email.clients.graph/igraphclient/createfolder#createfolder_1)(string, string) | Создать новую папку. |
| [CreateMessage](../../aspose.email.clients.graph/igraphclient/createmessage)(string, MapiMessage) | Создает сообщение в указанной папке |
| [CreateNotebook](../../aspose.email.clients.graph/igraphclient/createnotebook)(Notebook) | Создать новый блокнот OneNote. Разрешения Для вызова этого API требуется одно из следующих разрешений. Делегированные (рабочая или учебная учетная запись) Notes.Create, Notes.ReadWrite, Notes.ReadWrite.All Делегированные (личная учетная запись Microsoft) Notes. Создать, Notes.ReadWrite Application Notes.ReadWrite.All |
| [CreateOrUpdateOverride](../../aspose.email.clients.graph/igraphclient/createorupdateoverride#createorupdateoverride)(ClassificationOverride) | Создать переопределение для отправителя, идентифицируемого по SMTP-адресу. Будущие сообщения с этого SMTP-адреса будут последовательно классифицироваться в соответствии с указанными в переопределении. - Максимальное количество переопределений, поддерживаемых для почтового ящика, составляет 1000, исходя из уникальных SMTP-адресов отправителя. |
| [CreateOrUpdateOverride](../../aspose.email.clients.graph/igraphclient/createorupdateoverride#createorupdateoverride_1)(MailAddress, ClassificationType) | Создать переопределение для отправителя, идентифицируемого по SMTP-адресу. Будущие сообщения с этого SMTP-адреса будут последовательно классифицироваться в соответствии с указанными в переопределении. - Максимальное количество переопределений, поддерживаемых для почтового ящика, составляет 1000, исходя из уникальных SMTP-адресов отправителя. |
| [CreateRule](../../aspose.email.clients.graph/igraphclient/createrule)(InboxRule) | Создайте правило для сообщений, указав набор условий и действий. Outlook выполняет эти действия, если входящее сообщение в папке "Входящие" пользователя соответствует указанным условиям. Разрешения: Для вызова этого API требуется одно из следующих разрешений. узнать больше, в том числе о том, как выбрать разрешения, см. в разделе Permissions. Delegated (рабочая или учебная учетная запись) MailboxSettings.ReadWrite Delegated (личная учетная запись Microsoft) MailboxSettings.ReadWrite Application MailboxSettings.ReadWrite |
| [Delete](../../aspose.email.clients.graph/igraphclient/delete)(string) | Удалить объект. |
| [DeleteAttachment](../../aspose.email.clients.graph/igraphclient/deleteattachment)(string) | Удаляет вложение |
| [FetchAttachment](../../aspose.email.clients.graph/igraphclient/fetchattachment)(string) | Получает вложение для указанного id |
| [FetchCategory](../../aspose.email.clients.graph/igraphclient/fetchcategory)(string) | Получить свойства и взаимосвязи указанного объекта outlookCategory. |
| [FetchMessage](../../aspose.email.clients.graph/igraphclient/fetchmessage)(string) | Получает сообщение в указанном id |
| [FetchNotebook](../../aspose.email.clients.graph/igraphclient/fetchnotebook)(string) | Получение свойств и взаимосвязей объекта блокнота. Разрешения Для вызова этого API требуется одно из следующих разрешений. Делегировано (рабочая или учебная учетная запись) Notes.Create, Notes.Read, Notes.ReadWrite, Notes.Read.All , Notes.ReadWrite.All Делегированный (личная учетная запись Microsoft) Notes.Create, Notes.Read, Notes.ReadWrite Application Notes.Read.All, Notes.ReadWrite.All |
| [FetchRule](../../aspose.email.clients.graph/igraphclient/fetchrule)(string) | Получить свойства и отношения объекта правила сообщения. Разрешения Для вызова этого API требуется одно из следующих разрешений. Чтобы узнать больше, в том числе о том, как выбрать разрешения, см. Разрешения. Делегированный (рабочая или учебная учетная запись) MailboxSettings.Read Делегированный (личная учетная запись Microsoft) MailboxSettings.Read Application MailboxSettings.Read |
| [GetFolder](../../aspose.email.clients.graph/igraphclient/getfolder)(string) | Получает папку по идентификатору. |
| [GetOneNoteOperationStatus](../../aspose.email.clients.graph/igraphclient/getonenoteoperationstatus)(string) | Получить статус долго выполняющейся операции OneNote. Это относится к операциям, которые возвращают заголовок Operation-Location в ответе, например CopyNotebook, CopyToNotebook, CopyToSectionGroup и CopyToSection. Вы можете опрашивать конечную точку Operation-Location до тех пор, пока не Свойство состояния возвращает завершение или сбой. Если состояние завершено, свойство resourceLocation содержит URI конечной точки ресурса. |
| [ListAttachments](../../aspose.email.clients.graph/igraphclient/listattachments)(string) | Список вложений из родительского сообщения. |
| [ListCategories](../../aspose.email.clients.graph/igraphclient/listcategories)() | Получить все категории, которые были определены для пользователя. |
| [ListFolders](../../aspose.email.clients.graph/igraphclient/listfolders#listfolders)() | Список папок из родительской папки для папок, отображаемых в обычных почтовых клиентах, таких как почтовый ящик. |
| [ListFolders](../../aspose.email.clients.graph/igraphclient/listfolders#listfolders_1)(string) | Список папок из родительской папки для папок, отображаемых в обычных почтовых клиентах, таких как почтовый ящик. |
| [ListMessages](../../aspose.email.clients.graph/igraphclient/listmessages#listmessages_1)(string) | Список MessageInfo из родительской папки. |
| [ListMessages](../../aspose.email.clients.graph/igraphclient/listmessages#listmessages)(string, PageInfo, MailQuery) | Список MessageInfo из родительской папки. |
| [ListNotebooks](../../aspose.email.clients.graph/igraphclient/listnotebooks)() | Получить список объектов записной книжки. Разрешения Для вызова этого API требуется одно из следующих разрешений. Делегированные (рабочая или учебная учетная запись) Notes.Create, Notes.Read, Notes.ReadWrite, Notes.Read.All, Notes. ReadWrite.All Делегированный (личная учетная запись Microsoft) Notes.Create, Notes.Read, Notes.ReadWrite Application Notes.Read.All, Notes.ReadWrite.All |
| [ListOverrides](../../aspose.email.clients.graph/igraphclient/listoverrides)() | Получить переопределения, настроенные пользователем, чтобы всегда классифицировать сообщения от определенных отправителей определенным образом. Каждое переопределение соответствует SMTP-адресу отправителя. Изначально у пользователя нет переопределений. для вызова этого API требуются следующие разрешения. Чтобы узнать больше, в том числе о том, как выбрать разрешения, см. Разрешения. Делегированные (рабочая или учебная учетная запись) Mail.Read Делегированные (личная учетная запись Microsoft) Mail.Read Application Mail.Read |
| [ListRules](../../aspose.email.clients.graph/igraphclient/listrules)() | Получить все объекты messageRule, определенные для папки "Входящие" пользователя. Permissions Для вызова этого API требуется одно из следующих разрешений. Делегированный (личная учетная запись Microsoft) MailboxSettings.Read Application MailboxSettings.Read |
| [MoveFolder](../../aspose.email.clients.graph/igraphclient/movefolder)(string, string) | Переместить почтовую папку и ее содержимое в другую почтовую папку. |
| [MoveMessage](../../aspose.email.clients.graph/igraphclient/movemessage)(string, string) | Переместить сообщение в другую почтовую папку. |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send)(MapiMessage) | Отправляет электронное сообщение |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send_2)(string) | Отправить сообщение в папку черновиков. Черновик сообщения может быть черновиком нового сообщения, черновиком ответа, черновиком ответа всем или черновиком пересылки. Затем сообщение сохраняется в папке "Отправленные". |
| [Send](../../aspose.email.clients.graph/igraphclient/send#send_1)(MapiMessage, bool) | Отправляет электронное сообщение |
| [SetRead](../../aspose.email.clients.graph/igraphclient/setread)(string) | Пометить сообщение как прочитанное |
| [UpdateCategory](../../aspose.email.clients.graph/igraphclient/updatecategory)(OutlookCategory) | Обновляет предустановленную цветовую константу для указанной категории |
| [UpdateFolder](../../aspose.email.clients.graph/igraphclient/updatefolder)(FolderInfo) | Папка обновлений. |
| [UpdateMessage](../../aspose.email.clients.graph/igraphclient/updatemessage#updatemessage)(MapiMessage) | Обновляет сообщение |
| [UpdateMessage](../../aspose.email.clients.graph/igraphclient/updatemessage#updatemessage_1)(MapiMessage, UpdateSettings) | Обновляет сообщение |
| [UpdateOverride](../../aspose.email.clients.graph/igraphclient/updateoverride)(ClassificationOverride) | Измените поле classifyAs переопределения, как указано. Этот метод нельзя использовать для изменения каких-либо других полей в экземпляре ClassificationOverride. Если для отправителя существует переопределение, и отправитель меняет свое отображаемое имя, вы можете использовать CreateOrUpdateOverride для принудительное обновление поля имени в существующем переопределении. Если для отправителя существует переопределение, и отправитель меняет свой SMTP-адрес, удаление существующего переопределения и создание нового с новым SMTP-адресом — единственный способ "обновить" переопределение для этого отправителя. Разрешения: Для вызова этого API требуется одно из следующих разрешений. Чтобы узнать больше, в том числе о том, как выбрать разрешения, см. Разрешения. Делегировано (рабочая или учебная учетная запись) Mail.ReadWrite Делегировано (личная учетная запись Майкрософт) Mail.ReadWrite Приложение Mail.ReadWrite |
| [UpdateRule](../../aspose.email.clients.graph/igraphclient/updaterule)(InboxRule) | Измените доступные для записи свойства объекта messageRule и сохраните изменения. Разрешения Для вызова этого API требуется одно из следующих разрешений. Чтобы узнать больше, в том числе о том, как выбрать разрешения, см. Разрешения. Делегированные (рабочая или учебная учетная запись) MailboxSettings. ReadWrite Делегированный (личный аккаунт Microsoft) MailboxSettings.ReadWrite Application MailboxSettings.ReadWrite |

### Смотрите также

* пространство имен [Aspose.Email.Clients.Graph](../../aspose.email.clients.graph)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
