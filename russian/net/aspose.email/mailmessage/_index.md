---
title: MailMessage
second_title: Справочник по Aspose.Email для .NET API
description: Представляет сообщение электронной почты. Это позволяет получить доступ к свойствам сообщения ex. тема тело сообщения адреса отправителя и получателя и т.д. Также оно может быть отправлено и доставлено посредством поддерживаемых почтовых протоколов.
type: docs
weight: 17710
url: /ru/net/aspose.email/mailmessage/
---
## MailMessage class

Представляет сообщение электронной почты. Это позволяет получить доступ к свойствам сообщения, ex. тема, тело сообщения, адреса отправителя и получателя и т.д. Также оно может быть отправлено и доставлено посредством поддерживаемых почтовых протоколов.

```csharp
public class MailMessage : IDisposable, IEnumerable<MailMessage>, IMessage, 
    IPreferredTextEncodingProvider, ISerializable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MailMessage](mailmessage#constructor)() | Инициализирует новый экземпляр[`MailMessage`](../mailmessage) класс |
| [MailMessage](mailmessage#constructor_2)(bool) | Инициализирует новый экземпляр[`MailMessage`](../mailmessage) класс |
| [MailMessage](mailmessage#constructor_1)(MailAddress, MailAddress) | Инициализирует новый экземпляр[`MailMessage`](../mailmessage) класс |
| [MailMessage](mailmessage#constructor_3)(string, string) | Инициализирует новый экземпляр[`MailMessage`](../mailmessage) класс |
| [MailMessage](mailmessage#constructor_4)(string, string, string, string) | Инициализирует новый экземпляр[`MailMessage`](../mailmessage) класс |

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [AlternateViews](../../aspose.email/mailmessage/alternateviews) { get; } | Получает коллекцию альтернативных представлений message |
| virtual [Attachments](../../aspose.email/mailmessage/attachments) { get; } | Получает коллекцию вложений сообщения |
| virtual [Bcc](../../aspose.email/mailmessage/bcc) { get; set; } | Получает или задает коллекцию адресов , содержащую получателей скрытой копии сообщения message . |
| virtual [Body](../../aspose.email/mailmessage/body) { get; set; } | Получает или задает простое текстовое представление тела сообщения. Если в сообщении присутствует часть text/plain, свойство возвращает его текстовые данные. В противном случае свойство возвращает текстовое содержимое свойства HtmlBody без разметки html. |
| virtual [BodyEncoding](../../aspose.email/mailmessage/bodyencoding) { get; set; } | Получает или задает кодировку body |
| [BodyType](../../aspose.email/mailmessage/bodytype) { get; } | Получает тип тела. |
| virtual [CC](../../aspose.email/mailmessage/cc) { get; set; } | Получает или задает набор адресов , который содержит получателей копии |
| virtual [Date](../../aspose.email/mailmessage/date) { get; set; } | Получает или устанавливает дату сообщения |
| virtual [DeliveryNotificationOptions](../../aspose.email/mailmessage/deliverynotificationoptions) { get; set; } | Получает или устанавливает уведомления о доставке |
| [Epilogue](../../aspose.email/mailmessage/epilogue) { get; set; } | Получает или задает текст эпилога. Он располагается после последней границы. |
| virtual [From](../../aspose.email/mailmessage/from) { get; set; } | Получает или задает адрес from |
| virtual [Headers](../../aspose.email/mailmessage/headers) { get; } | Получает коллекцию заголовков message |
| virtual [HtmlBody](../../aspose.email/mailmessage/htmlbody) { get; set; } | Получает или задает html body |
| virtual [IsBodyHtml](../../aspose.email/mailmessage/isbodyhtml) { get; set; } | Получает или задает значение, указывающее , находится ли тело сообщения в формате Html . |
| virtual [IsDraft](../../aspose.email/mailmessage/isdraft) { get; set; } | Получает или задает значение, указывающее, было ли отправлено сообщение. |
| virtual [IsEncrypted](../../aspose.email/mailmessage/isencrypted) { get; } | Получает значение, указывающее, зашифровано ли сообщение. |
| virtual [IsReadOnly](../../aspose.email/mailmessage/isreadonly) { get; } | Получает значение, указывающее , доступно ли сообщение только для чтения |
| virtual [IsSigned](../../aspose.email/mailmessage/issigned) { get; } | Получает значение, указывающее, подписано ли сообщение. |
| virtual [LinkedResources](../../aspose.email/mailmessage/linkedresources) { get; } | Получает коллекцию связанных ресурсов message |
| virtual [MessageId](../../aspose.email/mailmessage/messageid) { get; set; } | Получает или задает сообщение id |
| virtual [OriginalIsTnef](../../aspose.email/mailmessage/originalistnef) { get; } | Получает значение, указывающее , имеет ли исходное сообщение EML формат TNEF. |
| [Preamble](../../aspose.email/mailmessage/preamble) { get; set; } | Получает или задает текст преамбулы. Он расположен перед первой границей и обычно включает пояснительное примечание для читателей, не совместимых с MIME. |
| [PreferredTextEncoding](../../aspose.email/mailmessage/preferredtextencoding) { get; set; } | Получает или задает предпочтительную кодировку для всех текстовых свойств |
| virtual [Priority](../../aspose.email/mailmessage/priority) { get; set; } | Получает или устанавливает приоритет сообщения |
| [ReadReceiptTo](../../aspose.email/mailmessage/readreceiptto) { get; set; } | Получает или задает адрес уведомления о прочтении. |
| virtual [ReplyToList](../../aspose.email/mailmessage/replytolist) { get; set; } | Получает или задает список адресов для ответа на почтовое сообщение |
| virtual [ReversePath](../../aspose.email/mailmessage/reversepath) { get; set; } | Получает или задает адрес обратного пути |
| virtual [Sender](../../aspose.email/mailmessage/sender) { get; set; } | Получает или устанавливает адрес отправителя |
| virtual [Sensitivity](../../aspose.email/mailmessage/sensitivity) { get; set; } | Получает или задает чувствительность сообщения |
| virtual [Subject](../../aspose.email/mailmessage/subject) { get; set; } | Получает или устанавливает строку темы |
| virtual [SubjectEncoding](../../aspose.email/mailmessage/subjectencoding) { get; set; } | Получает или задает кодировку subject |
| [TimeZoneOffset](../../aspose.email/mailmessage/timezoneoffset) { get; set; } | Получает или задает смещение всемирного координированного времени (UTC) для дат сообщений. Это свойство определяет разницу часовых поясов между местным временем и временем UTC. |
| virtual [To](../../aspose.email/mailmessage/to) { get; set; } | Получает или задает коллекцию адресов, содержащую получателей сообщения message . |
| virtual [XMailer](../../aspose.email/mailmessage/xmailer) { get; set; } | Получает или устанавливает программу X-Mailer , создавшую сообщение электронной почты |

## Методы

| Имя | Описание |
| --- | --- |
| static [Load](../../aspose.email/mailmessage/load#load)(Stream) | Загрузить сообщение из потока |
| static [Load](../../aspose.email/mailmessage/load#load_2)(string) | Загрузить сообщение из файла |
| static [Load](../../aspose.email/mailmessage/load#load_1)(Stream, LoadOptions) | Загрузить сообщение из потока с дополнительными параметрами. |
| static [Load](../../aspose.email/mailmessage/load#load_3)(string, LoadOptions) | Загрузить сообщение из файла с дополнительными параметрами. |
| virtual [AddAlternateView](../../aspose.email/mailmessage/addalternateview)(AlternateView) | Добавить альтернативный вид к message |
| virtual [AddAttachment](../../aspose.email/mailmessage/addattachment)(Attachment) | Добавить вложение к сообщению |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature#attachsignature)(CmsSigner) | Создает подписанное сообщение. Создает доступную только для чтения копию указанного сообщения MailMessage и добавляет к нему цифровую подпись. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature#attachsignature_2)(X509Certificate2) | Создает подписанное сообщение. Создает доступную только для чтения копию указанного сообщения MailMessage и добавляет к нему цифровую подпись. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature#attachsignature_1)(CmsSigner, bool) | Создает подписанное сообщение. Создает доступную только для чтения копию указанного сообщения MailMessage и добавляет к нему цифровую подпись. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature#attachsignature_3)(X509Certificate2, bool) | Создает подписанное сообщение. Создает доступную только для чтения копию указанного сообщения MailMessage и добавляет к нему цифровую подпись. |
| virtual [CheckBounced](../../aspose.email/mailmessage/checkbounced)() | Проверяет, можно ли рассматривать это сообщение как рикошет. |
| virtual [CheckSignature](../../aspose.email/mailmessage/checksignature)() | Проверка подписи существующего MailMessage. |
| virtual [Clone](../../aspose.email/mailmessage/clone)() | Клонирует этот экземпляр |
| [CreateReadReceipt](../../aspose.email/mailmessage/createreadreceipt)(string, string) | Создает уведомление о прочтении. |
| virtual [Decrypt](../../aspose.email/mailmessage/decrypt#decrypt)() | Расшифровывает это сообщение |
| virtual [Decrypt](../../aspose.email/mailmessage/decrypt#decrypt_1)(X509Certificate2) | Расшифровывает это сообщение |
| [Dispose](../../aspose.email/mailmessage/dispose)() | Освобождает все ресурсы, используемые MailMessage |
| virtual [DKIMSign](../../aspose.email/mailmessage/dkimsign)(RSACryptoServiceProvider, DKIMSignatureInfo) | Подписывает это сообщение, используя подпись DKIM (DomainKeys Identified Mail). |
| virtual [Encrypt](../../aspose.email/mailmessage/encrypt#encrypt)(X509Certificate2) | Шифрует это сообщение |
| virtual [Encrypt](../../aspose.email/mailmessage/encrypt#encrypt_1)(X509Certificate2[]) | Шифрует это сообщение |
| override [Equals](../../aspose.email/mailmessage/equals)(object) | Определяет, равен ли указанный объект текущему объекту. |
| [GetEnumerator](../../aspose.email/mailmessage/getenumerator)() | Возвращает перечислитель, который перебирает коллекцию. |
| override [GetHashCode](../../aspose.email/mailmessage/gethashcode)() | Возвращает хэш-код для object |
| virtual [GetHtmlBodyText](../../aspose.email/mailmessage/gethtmlbodytext#gethtmlbodytext_1)(bool) | Получает HTML-текст сообщения в виде простого текста. Этот метод анализирует свойство HtmlBody и возвращает содержимое в виде обычного текста, игнорируя разметку html. |
| virtual [GetHtmlBodyText](../../aspose.email/mailmessage/gethtmlbodytext#gethtmlbodytext)(HyperlinkRenderingCallback) | Получает htmlbody сообщения в виде обычного текста. |
| virtual [GetObjectData](../../aspose.email/mailmessage/getobjectdata)(SerializationInfo, StreamingContext) | ЗаполняетSerializationInfo с данными, необходимыми для сериализации целевого объекта. |
| virtual [Import](../../aspose.email/mailmessage/import)(Stream) | Импортирует сообщение из потока |
| [RecomposeTnefContent](../../aspose.email/mailmessage/recomposetnefcontent)() | Составляет содержимое TNEF. Обратите внимание, что вложение tnef составляется, если сообщение изначально содержало TNEF и было загружено без флага FileCompatibilityMode.PreserveTnefAttachments, То есть этот метод не создает сообщение tnef из обычного. |
| virtual [RemoveSignature](../../aspose.email/mailmessage/removesignature)() | Удалить подпись |
| virtual [Save](../../aspose.email/mailmessage/save#save)(Stream) | Сохранить сообщение как поток |
| virtual [Save](../../aspose.email/mailmessage/save#save_2)(string) | Сохранить сообщение как файл |
| virtual [Save](../../aspose.email/mailmessage/save#save_1)(Stream, SaveOptions) | Сохранить сообщение как поток с дополнительными параметрами. |
| virtual [Save](../../aspose.email/mailmessage/save#save_3)(string, SaveOptions) | Сохранить сообщение как файл с дополнительными параметрами. |
| virtual [SetHtmlBody](../../aspose.email/mailmessage/sethtmlbody)(string, bool) | Устанавливает тело HTML. |
| override [ToString](../../aspose.email/mailmessage/tostring)() | Возвращает строку, представляющую текущий объект. |
| static [CheckSignature](../../aspose.email/mailmessage/checksignature#checksignature)(Stream) | Проверяет подпись указанного сообщения eml. |
| static [CheckSignature](../../aspose.email/mailmessage/checksignature#checksignature_1)(string) | Проверяет подпись указанного файла eml. |
| static [ValidateMessage](../../aspose.email/mailmessage/validatemessage#validatemessage)(Stream) | Проверка сообщения eml на соответствие спецификации mime. |
| static [ValidateMessage](../../aspose.email/mailmessage/validatemessage#validatemessage_1)(string) | Проверка сообщения eml на соответствие спецификации mime. |

### Смотрите также

* interface [IMessage](../imessage)
* interface [IPreferredTextEncodingProvider](../ipreferredtextencodingprovider)
* пространство имен [Aspose.Email](../../aspose.email)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
