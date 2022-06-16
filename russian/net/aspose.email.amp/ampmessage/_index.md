---
title: AmpMessage
second_title: Справочник по Aspose.Email для .NET API
description: Сообщение которое позволяет отправителям включать компоненты AMP в электронные письма.
type: docs
weight: 140
url: /ru/net/aspose.email.amp/ampmessage/
---
## AmpMessage class

Сообщение, которое позволяет отправителям включать компоненты AMP в электронные письма.

```csharp
public class AmpMessage : MailMessage
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [AmpMessage](ampmessage)() | Инициализирует новый экземпляр класса[`MailMessage`](../../aspose.email/mailmessage) |

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [AlternateViews](../../aspose.email/mailmessage/alternateviews) { get; } | Получает коллекцию альтернативных представлений сообщения |
| virtual [AmpHtmlBody](../../aspose.email.amp/ampmessage/amphtmlbody) { get; set; } | Получает AmpHtml-представление тела сообщения. |
| virtual [Attachments](../../aspose.email/mailmessage/attachments) { get; } | Получает коллекцию вложений сообщения |
| virtual [Bcc](../../aspose.email/mailmessage/bcc) { get; set; } | Получает или задает коллекцию адресов , содержащую получателей скрытой копии сообщения |
| virtual [Body](../../aspose.email/mailmessage/body) { get; set; } | Получает или задает текстовое представление тела сообщения. Если в сообщении присутствует часть text/plain, свойство возвращает текстовые данные. В противном случае свойство возвращает текстовое содержимое свойства HtmlBody без html-разметки. |
| virtual [BodyEncoding](../../aspose.email/mailmessage/bodyencoding) { get; set; } | Получает или устанавливает кодировку тела |
| [BodyType](../../aspose.email/mailmessage/bodytype) { get; } | Получает тип тела. |
| virtual [CC](../../aspose.email/mailmessage/cc) { get; set; } | Получает или задает коллекцию адресов , содержащую получателей копии |
| virtual [Date](../../aspose.email/mailmessage/date) { get; set; } | Получает или устанавливает дату сообщения |
| virtual [DeliveryNotificationOptions](../../aspose.email/mailmessage/deliverynotificationoptions) { get; set; } | Получает или устанавливает уведомления о доставке |
| [Epilogue](../../aspose.email/mailmessage/epilogue) { get; set; } | Получает или задает текст эпилога. Находится за последней границей. |
| virtual [From](../../aspose.email/mailmessage/from) { get; set; } | Получает или устанавливает адрес отправителя |
| virtual [Headers](../../aspose.email/mailmessage/headers) { get; } | Получает коллекцию заголовков сообщения |
| virtual [HtmlBody](../../aspose.email/mailmessage/htmlbody) { get; set; } | Получает или устанавливает тело html |
| virtual [IsBodyHtml](../../aspose.email/mailmessage/isbodyhtml) { get; set; } | Получает или задает значение, указывающее находится ли тело сообщения в HTML |
| virtual [IsDraft](../../aspose.email/mailmessage/isdraft) { get; set; } | Получает или задает значение, указывающее, было ли отправлено сообщение. |
| virtual [IsEncrypted](../../aspose.email/mailmessage/isencrypted) { get; } | Получает значение, указывающее, зашифровано ли сообщение. |
| virtual [IsReadOnly](../../aspose.email/mailmessage/isreadonly) { get; } | Получает значение, указывающее является ли сообщение только для чтения |
| virtual [IsSigned](../../aspose.email/mailmessage/issigned) { get; } | Получает значение, указывающее, подписано ли сообщение. |
| virtual [LinkedResources](../../aspose.email/mailmessage/linkedresources) { get; } | Получает коллекцию связанных ресурсов сообщения |
| virtual [MessageId](../../aspose.email/mailmessage/messageid) { get; set; } | Получает или устанавливает идентификатор сообщения |
| virtual [OriginalIsTnef](../../aspose.email/mailmessage/originalistnef) { get; } | Получает значение, указывающее , имеет ли исходное сообщение EML формат TNEF. |
| [Preamble](../../aspose.email/mailmessage/preamble) { get; set; } | Получает или задает текст преамбулы. Он расположен перед первой границей и обычно включает пояснительную записку для читателей, не совместимых с MIME. |
| [PreferredTextEncoding](../../aspose.email/mailmessage/preferredtextencoding) { get; set; } | Получает или устанавливает предпочтительную кодировку для всех свойств текста |
| virtual [Priority](../../aspose.email/mailmessage/priority) { get; set; } | Получает или устанавливает приоритет сообщения |
| [ReadReceiptTo](../../aspose.email/mailmessage/readreceiptto) { get; set; } | Получает или задает адрес уведомления о прочтении. |
| virtual [ReplyToList](../../aspose.email/mailmessage/replytolist) { get; set; } | Получает или задает список адресов для ответа на почтовое сообщение |
| virtual [ReversePath](../../aspose.email/mailmessage/reversepath) { get; set; } | Получает или устанавливает адрес ReversePath |
| virtual [Sender](../../aspose.email/mailmessage/sender) { get; set; } | Получает или устанавливает адрес отправителя |
| virtual [Sensitivity](../../aspose.email/mailmessage/sensitivity) { get; set; } | Получает или устанавливает чувствительность сообщения |
| virtual [Subject](../../aspose.email/mailmessage/subject) { get; set; } | Получает или устанавливает строку темы |
| virtual [SubjectEncoding](../../aspose.email/mailmessage/subjectencoding) { get; set; } | Получает или устанавливает кодировку темы |
| [TimeZoneOffset](../../aspose.email/mailmessage/timezoneoffset) { get; set; } | Получает или задает всемирное координированное время (UTC) смещение для дат сообщений. Это свойство определяет разницу часовых поясов, между местным временем и UTC. |
| virtual [To](../../aspose.email/mailmessage/to) { get; set; } | Получает или задает коллекцию адресов, содержащую получателей сообщения |
| virtual [XMailer](../../aspose.email/mailmessage/xmailer) { get; set; } | Получает или устанавливает программу X-Mailer , создавшую сообщение электронной почты |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [AddAlternateView](../../aspose.email/mailmessage/addalternateview)(AlternateView) | Добавить альтернативный вид к сообщению |
| [AddAmpComponent](../../aspose.email.amp/ampmessage/addampcomponent)(AmpComponent) | Добавить компонент усилителя в это сообщение. |
| virtual [AddAttachment](../../aspose.email/mailmessage/addattachment)(Attachment) | Добавить вложение к сообщению |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature)(CmsSigner) | Создает подписанное сообщение. Создает доступную только для чтения копию указанного MailMessage и добавляет к ней цифровую подпись. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature)(X509Certificate2) | Создает подписанное сообщение. Создает доступную только для чтения копию указанного MailMessage и добавляет к ней цифровую подпись. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature)(CmsSigner, bool) | Создает подписанное сообщение. Создает доступную только для чтения копию указанного MailMessage и добавляет к ней цифровую подпись. |
| virtual [AttachSignature](../../aspose.email/mailmessage/attachsignature)(X509Certificate2, bool) | Создает подписанное сообщение. Создает доступную только для чтения копию указанного MailMessage и добавляет к ней цифровую подпись. |
| virtual [CheckBounced](../../aspose.email/mailmessage/checkbounced)() | Проверяет, можно ли рассматривать это сообщение как рикошет. |
| virtual [CheckSignature](../../aspose.email/mailmessage/checksignature)() | Проверка подписи существующего MailMessage. |
| virtual [Clone](../../aspose.email/mailmessage/clone)() | Клонирует этот экземпляр |
| [CreateReadReceipt](../../aspose.email/mailmessage/createreadreceipt)(string, string) | Создает уведомление о прочтении. |
| virtual [Decrypt](../../aspose.email/mailmessage/decrypt)() | Расшифровывает это сообщение |
| virtual [Decrypt](../../aspose.email/mailmessage/decrypt)(X509Certificate2) | Расшифровывает это сообщение |
| [Dispose](../../aspose.email/mailmessage/dispose)() | Освобождает все ресурсы, используемые MailMessage |
| virtual [DKIMSign](../../aspose.email/mailmessage/dkimsign)(RSACryptoServiceProvider, DKIMSignatureInfo) | Подписывает это сообщение, используя подпись DKIM (DomainKeys Identified Mail). |
| virtual [Encrypt](../../aspose.email/mailmessage/encrypt)(X509Certificate2) | Шифрует это сообщение |
| virtual [Encrypt](../../aspose.email/mailmessage/encrypt)(X509Certificate2[]) | Шифрует это сообщение |
| override [Equals](../../aspose.email/mailmessage/equals)(object) | Определяет, равен ли указанный объект текущему объекту. |
| [GetEnumerator](../../aspose.email/mailmessage/getenumerator)() | Возвращает перечислитель, который перебирает коллекцию. |
| override [GetHashCode](../../aspose.email/mailmessage/gethashcode)() | Возвращает хеш-код для объекта |
| virtual [GetHtmlBodyText](../../aspose.email/mailmessage/gethtmlbodytext)(bool) | Получает HTML-текст сообщения в виде простого текста. Этот метод анализирует свойство HtmlBody и возвращает текстовое содержимое без учета разметки html. |
| virtual [GetHtmlBodyText](../../aspose.email/mailmessage/gethtmlbodytext)(HyperlinkRenderingCallback) | Получает htmlbody сообщения в виде простого текста. |
| virtual [GetObjectData](../../aspose.email/mailmessage/getobjectdata)(SerializationInfo, StreamingContext) | ЗаполняетSerializationInfoданными, необходимыми для сериализации целевого объекта. |
| virtual [Import](../../aspose.email/mailmessage/import)(Stream) | Импорт сообщения из потока |
| [RecomposeTnefContent](../../aspose.email/mailmessage/recomposetnefcontent)() | Составляет содержимое в формате TNEF. Обратите внимание, что вложение tnef составляется, если сообщение изначально содержало TNEF и было загружено без флага FileCompatibilityMode.PreserveTnefAttachments, То есть этот метод не создать сообщение tnef из обычного. |
| virtual [RemoveSignature](../../aspose.email/mailmessage/removesignature)() | Удалить подпись |
| virtual [Save](../../aspose.email/mailmessage/save)(Stream) | Сохранить сообщение как поток |
| virtual [Save](../../aspose.email/mailmessage/save)(string) | Сохранить сообщение как файл |
| override [Save](../../aspose.email.amp/ampmessage/save#save_1)(Stream, SaveOptions) | Сохранить сообщение как поток |
| virtual [Save](../../aspose.email/mailmessage/save)(string, SaveOptions) | Сохранить сообщение как файл с дополнительными параметрами. |
| virtual [SetHtmlBody](../../aspose.email/mailmessage/sethtmlbody)(string, bool) | Устанавливает тело HTML. |
| override [ToString](../../aspose.email/mailmessage/tostring)() | Возвращает строку, представляющую текущий объект. |

### Смотрите также

* class [MailMessage](../../aspose.email/mailmessage)
* пространство имен [Aspose.Email.Amp](../../aspose.email.amp)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
