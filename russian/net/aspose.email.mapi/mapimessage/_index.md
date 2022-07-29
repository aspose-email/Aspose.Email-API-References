---
title: MapiMessage
second_title: Справочник по Aspose.Email для .NET API
description: Представляет документ формата сообщения Outlook который можно анализировать.
type: docs
weight: 18450
url: /ru/net/aspose.email.mapi/mapimessage/
---
## MapiMessage class

Представляет документ формата сообщения Outlook, который можно анализировать.

```csharp
public sealed class MapiMessage : MapiMessageItemBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MapiMessage](mapimessage#constructor)() | Инициализирует новый экземпляр[`MapiMessage`](../mapimessage) класс. |
| [MapiMessage](mapimessage#constructor_1)(OutlookMessageFormat) | Инициализирует новый экземпляр[`MapiMessage`](../mapimessage) класс. |
| [MapiMessage](mapimessage#constructor_2)(string, string, string, string) | Инициализирует новый экземпляр[`MapiMessage`](../mapimessage) класс. |
| [MapiMessage](mapimessage#constructor_3)(string, string, string, string, OutlookMessageFormat) | Инициализирует новый экземпляр[`MapiMessage`](../mapimessage) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapimessageitembase/attachments) { get; } | Получает вложения в сообщении. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing) { get; set; } | Содержит платежную информацию, связанную с элементом. |
| [Body](../../aspose.email.mapi/mapimessage/body) { get; set; } | Получает текст сообщения. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml) { get; } | Получает[`BodyRtf`](../mapimessageitembase/bodyrtf) сообщения, преобразованного в HTML, если он присутствует, иначе пустая строка. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf) { get; set; } | Получает или задает текст сообщения в формате RTF. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype) { get; } | Получает тип тела. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories) { get; set; } | Содержит ключевые слова или категории для объекта сообщения. |
| [ClientSubmitTime](../../aspose.email.mapi/mapimessage/clientsubmittime) { get; set; } | Получает или задает дату и время отправки сообщения отправителем. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage) { get; } | Получает кодовую страницу. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies) { get; set; } | Содержит названия компаний, связанных с элементом. |
| [ConversationTopic](../../aspose.email.mapi/mapimessage/conversationtopic) { get; } | Получает тему первого сообщения в ветке беседы. |
| [DeliveryTime](../../aspose.email.mapi/mapimessage/deliverytime) { get; set; } | Получает или устанавливает дату и время сообщения было доставлено. |
| [DisplayBcc](../../aspose.email.mapi/mapimessage/displaybcc) { get; } | Получает список отображаемых имен всех получателей сообщения скрытой копии (BCC), разделенных точкой с запятой (;). |
| [DisplayCc](../../aspose.email.mapi/mapimessage/displaycc) { get; } | Получает список отображаемых имен всех получателей сообщений копии (CC), разделенных точкой с запятой (;). |
| [DisplayName](../../aspose.email.mapi/mapimessage/displayname) { get; } | Получает отображаемое имя сообщения. |
| [DisplayNamePrefix](../../aspose.email.mapi/mapimessage/displaynameprefix) { get; } | Получает префикс отображаемого имени. |
| [DisplayTo](../../aspose.email.mapi/mapimessage/displayto) { get; } | Получает список отображаемых имен основных (Кому) получателей сообщения, разделенных точкой с запятой (;). |
| [Flags](../../aspose.email.mapi/mapimessage/flags) { get; } | Получает флаги сообщения. |
| [Headers](../../aspose.email.mapi/mapimessage/headers) { get; set; } | Получает заголовки транспортного сообщения |
| [InternetMessageId](../../aspose.email.mapi/mapimessage/internetmessageid) { get; } | Получает идентификатор сообщения. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid) { get; } | Идентификатор элемента, используется с server |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass) { get; set; } | Получает строку с учетом регистра, которая идентифицирует определенный отправителем класс сообщения, например IPM.Note. Класс сообщения определяет тип, цель или содержимое сообщения. |
| [MessageFormat](../../aspose.email.mapi/mapimessage/messageformat) { get; } | Получает формат сообщения Outlook. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage) { get; set; } | Содержит информацию о пробеге, связанном с элементом. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties) { get; } | Получает именованные свойства сообщения. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping) { get; } | Получает сопоставление именованного свойства. |
| [NormalizedSubject](../../aspose.email.mapi/mapimessage/normalizedsubject) { get; } | Получает нормализованную тему сообщения. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties) { get; } | Получает набор свойств. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream) { get; } | Получает поток свойств. |
| [ReadReceiptRequested](../../aspose.email.mapi/mapimessage/readreceiptrequested) { get; set; } | Получает или задает значение, указывающее, запрашивается ли уведомление о прочтении. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients) { get; set; } | Получает получателей сообщения. |
| [ReplyTo](../../aspose.email.mapi/mapimessage/replyto) { get; set; } | Получает или задает ответ на имена. |
| [SenderAddressType](../../aspose.email.mapi/mapimessage/senderaddresstype) { get; } | Получает тип адреса электронной почты отправителя сообщения. |
| [SenderEmailAddress](../../aspose.email.mapi/mapimessage/senderemailaddress) { get; set; } | Получает или задает адрес электронной почты отправителя сообщения. |
| [SenderName](../../aspose.email.mapi/mapimessage/sendername) { get; set; } | Получает или задает отображаемое имя отправителя сообщения. |
| [SenderSmtpAddress](../../aspose.email.mapi/mapimessage/sendersmtpaddress) { get; set; } | Получает или задает адрес электронной почты отправителя сообщения. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity) { get; set; } | Получает чувствительность. |
| [SentRepresentingAddressType](../../aspose.email.mapi/mapimessage/sentrepresentingaddresstype) { get; } | Получает тип адреса для пользователя обмена сообщениями, представленного отправителем. |
| [SentRepresentingEmailAddress](../../aspose.email.mapi/mapimessage/sentrepresentingemailaddress) { get; set; } | Получает или задает адрес электронной почты для пользователя обмена сообщениями, представленного отправителем. |
| [SentRepresentingName](../../aspose.email.mapi/mapimessage/sentrepresentingname) { get; set; } | Получает или задает отображаемое имя пользователя обмена сообщениями, представленного отправителем. |
| [SentRepresentingSmtpAddress](../../aspose.email.mapi/mapimessage/sentrepresentingsmtpaddress) { get; } | Получает или задает адрес электронной почты для пользователя обмена сообщениями, представленного отправителем. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject) { get; set; } | Получает или задает тему сообщения. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix) { get; } | Получает префикс темы, который обычно указывает на какое-либо действие над сообщением, например "FW: " для пересылки. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages) { get; } | Получает вспомогательные хранилища. |
| [TransportMessageHeaders](../../aspose.email.mapi/mapimessage/transportmessageheaders) { get; } | Получает информацию о конверте сообщения для конкретного транспорта. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage)(MailMessage) | Создает экземпляр MapiMessage из MailMessage. |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage_2)(string) | Создает экземпляр MapiMessage из MailMessage. |
| static [FromMailMessage](../../aspose.email.mapi/mapimessage/frommailmessage#frommailmessage_1)(MailMessage, MapiConversionOptions) | Создает экземпляр MapiMessage из MailMessage. |
| static [FromProperties](../../aspose.email.mapi/mapimessage/fromproperties)(MapiPropertyCollection) | Создает экземпляр MapiMessage из набора свойств Mapi. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load)(Stream) | Загружает сообщение из потока. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_2)(string) | Загружает сообщение из файла. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_1)(Stream, LoadOptions) | Загружает сообщение из потока с дополнительными опциями. |
| static [Load](../../aspose.email.mapi/mapimessage/load#load_3)(string, LoadOptions) | Загружает сообщение из файла с дополнительными опциями. |
| static [LoadFromTnef](../../aspose.email.mapi/mapimessage/loadfromtnef#loadfromtnef)(Stream) | Загружает сообщение из структуры данных Transport Neutral Encapsulation Format (TNEF) |
| static [LoadFromTnef](../../aspose.email.mapi/mapimessage/loadfromtnef#loadfromtnef_1)(string) | Загружает сообщение из структуры данных Transport Neutral Encapsulation Format (TNEF) |
| [AddCustomProperty](../../aspose.email.mapi/mapimessage/addcustomproperty#addcustomproperty)(MapiProperty, string) | Добавляет пользовательское свойство. |
| [AddCustomProperty](../../aspose.email.mapi/mapimessage/addcustomproperty#addcustomproperty_1)(MapiPropertyType, byte[], string) | Добавляет пользовательское свойство. |
| [CheckBounced](../../aspose.email.mapi/mapimessage/checkbounced)() | Проверяет, можно ли рассматривать это сообщение как рикошет. |
| [Clone](../../aspose.email.mapi/mapimessage/clone)() | Создает новый объект, являющийся копией текущего экземпляра. |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose)() | Выполняет определяемые приложением задачи, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [GetCustomProperties](../../aspose.email.mapi/mapimessage/getcustomproperties)() | Получает коллекцию пользовательских свойств MapiProperties. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty)(PropertyDescriptor) | Получает свойство MAPI по дескриптору свойства. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean)(long) | Получает значение свойства, указанного тегом, в виде логического типа. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes)(long) | Получает строковое значение свойства, указанного тегом. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime)(long) | Получает значение свойства, указанного тегом как тип DateTime. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32)(long) | Получает значение int32 свойства, указанного тегом. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong)(long) | Получает значение свойства, указанного тегом, типа Long (int64). |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort)(long) | Получает значение свойства, указанного тегом, как тип Short. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long) | Получает строковое значение свойства, указанного тегом. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring)(long, int) | Получает строковое значение свойства, указанного тегом. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok)() | Определяет, закодированы ли строковые свойства в Unicode или нет. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty)(long) | Обеспечивает корректное удаление свойства из всех коллекций. |
| [Save](../../aspose.email.mapi/mapimessage/save#save)(Stream) | Сохраняет в указанный поток как Msg. |
| [Save](../../aspose.email.mapi/mapimessage/save#save_2)(string) | Сохраняет в указанный файл как Msg. |
| [Save](../../aspose.email.mapi/mapimessage/save#save_1)(Stream, SaveOptions) | Сохраняет сообщение в виде потока с дополнительными параметрами. |
| [Save](../../aspose.email.mapi/mapimessage/save#save_3)(string, SaveOptions) | Сохраняет сообщение в виде файла с дополнительными параметрами. |
| [SaveAsTemplate](../../aspose.email.mapi/mapimessage/saveastemplate#saveastemplate)(Stream) | Сохраняет в указанный поток как шаблон файла Outlook (формат OFT). |
| [SaveAsTemplate](../../aspose.email.mapi/mapimessage/saveastemplate#saveastemplate_1)(string) | Сохраняет в указанный файл как шаблон файла Outlook (формат OFT). |
| [SaveAsTnef](../../aspose.email.mapi/mapimessage/saveastnef#saveastnef)(Stream) | Сохранить сообщение в формате TNEF. |
| [SaveAsTnef](../../aspose.email.mapi/mapimessage/saveastnef#saveastnef_1)(string) | Сохранить сообщение в формате TNEF. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType) | Задает содержимое тела. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent)(string, BodyContentType, bool) | Задает содержимое тела. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf)(string, bool) | Получает или задает текст сообщения в формате RTF. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags)(MapiMessageFlags) | Устанавливает флаги сообщения. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty)(MapiProperty) | Задает свойство. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty)(PropertyDescriptor, object) | Задает свойство MAPI. |
| [SetStringPropertyValue](../../aspose.email.mapi/mapimessage/setstringpropertyvalue)(long, string) | Задает значение свойства строки. |
| [ToMailMessage](../../aspose.email.mapi/mapimessage/tomailmessage)(MailConversionOptions) | Создает экземпляр MailMessage из этого MapiMessage. |
| [ToMapiMessageItem](../../aspose.email.mapi/mapimessage/tomapimessageitem)() | Преобразование MapiMessage в IMapiMessageItem object в зависимости от MessageClass. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata)(long) | Попытаться получить данные свойства с указанным ключом тега. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime)(long, ref DateTime) | Получает значение указанного свойства как тип DateTime. Возвращаемое значение указывает, успешно ли выполнена операция. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32)(long, ref int) | Получает значение указанного свойства как тип Int32. Возвращаемое значение указывает, успешно ли выполнена операция. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong)(long, ref long) | Получает значение указанного свойства как тип Long. Возвращаемое значение указывает, успешно ли выполнена операция. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long) | Попытаться получить данные свойства в виде строки с указанным тегом. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, int) | Попытаться получить данные свойства в виде строки с указанным тегом и кодовой страницей. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string) | Получает значение указанного свойства как тип String. Возвращаемое значение указывает, успешно ли выполнена операция. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring)(long, ref string, int) | Получает значение указанного свойства как тип String. Возвращаемое значение указывает, успешно ли выполнена операция. |
| static [DestroyAttachments](../../aspose.email.mapi/mapimessage/destroyattachments)(string) | Уничтожает вложения в указанных файлах сообщений Outlook. DestroyAttachments будет игнорировать разбор вложения. |
| static [IsMsgFormat](../../aspose.email.mapi/mapimessage/ismsgformat#ismsgformat)(Stream) | Определяет, имеет ли указанный поток формат MSG. |
| static [IsMsgFormat](../../aspose.email.mapi/mapimessage/ismsgformat#ismsgformat_1)(string) | Определяет, имеет ли указанный файл формат MSG. |
| static [RemoveAttachments](../../aspose.email.mapi/mapimessage/removeattachments)(string) | Удаляет все вложения из указанных файлов сообщений Outlook. |

### Примечания

Экземпляры класса MapiMessage используются для представления файлов документов Microsoft Outlook Message, которые анализируются классом MapiMessageReader. Чтобы получить доступ к отправителю, получателю и содержимому сообщения электронной почты, используйте связанные свойства класса MapiMessage.

### Примеры

В следующем примере показано, как читать файлы сообщений Outlook.

[С#]

[Visual Basic]

```csharp
// Открытие файлов сообщений Outlook
MapiMessage msg = MapiMessage.FromFile(@"c:\outlookmessage.msg");

/прочитать тему
onsole.WriteLine("Subject:" + msg.Subject);

/имя отправителя
onsole.WriteLine("From:" + msg.SenderName);

/ тело сообщения
onsole.WriteLine("Body:" + msg.Body);

/Вложения
oreach(MapiAttachment att in msg.Attachments)

   Console.WriteLine("Attachment Name:"+att.FileName);
   att.Save(att.FileName);
    
```

```csharp
'Открыть файлы сообщений Outlook 
Dim msg As MapiMessage = MapiMessage.FromFile("c:\outlookmessage.msg") 

'читать тему 
Console.WriteLine("Subject:" + msg.Subject) 

'имя отправителя 
Console.WriteLine("From:" + msg.SenderName) 

'тело сообщения 
Console.WriteLine("Body:" + msg.Body) 

'Вложения 
For Each att As MapiAttachment In msg.Attachments 
    Console.WriteLine("Attachment Name:" + att.FileName) 
    att.Save(att.FileName) 
Next
```

### Смотрите также

* class [MapiMessageItemBase](../mapimessageitembase)
* пространство имен [Aspose.Email.Mapi](../../aspose.email.mapi)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
