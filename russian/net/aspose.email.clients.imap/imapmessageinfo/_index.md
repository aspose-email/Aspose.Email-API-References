---
title: ImapMessageInfo
second_title: Справочник по Aspose.Email для .NET API
description: Представляет объект сообщения Imap.
type: docs
weight: 16370
url: /ru/net/aspose.email.clients.imap/imapmessageinfo/
---
## ImapMessageInfo class

Представляет объект сообщения Imap.

```csharp
public sealed class ImapMessageInfo : MessageInfoBase
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Answered](../../aspose.email.clients.imap/imapmessageinfo/answered) { get; } | Получает значение, указывающее, содержит ли свойство Flags флаг Answered. |
| virtual [Bcc](../../aspose.email.clients/messageinfobase/bcc) { get; } | Получает скрытую копию сообщения электронной почты. |
| virtual [CC](../../aspose.email.clients/messageinfobase/cc) { get; } | Получает копию сообщения электронной почты. |
| [ConversationId](../../aspose.email.clients.imap/imapmessageinfo/conversationid) { get; } | Получает значение, указывающее идентификатор диалога. |
| virtual [Date](../../aspose.email.clients/messageinfobase/date) { get; } | Дата создания указывает дату и время, когда создатель сообщения указал что сообщение было завершено и готово к отправке по почте система. Например, это может быть время, когда пользователь нажимает кнопку "отправить" или "отправить" в прикладной программе. В любом случае, он конкретно не предназначен для передачи времени фактической передачи сообщения, а скорее времени, в которое человек или другой создатель сообщения поставил сообщение в его окончательную форму, готово к транспортировке. (Например, пользователь портативного компьютера, не подключенный к сети, может поставить сообщение в очередь на доставку. Дата создания должна содержать дату и время, когда пользователь поставил сообщение в очередь, не время, когда пользователь подключился к сети для отправки сообщения.) |
| [Deleted](../../aspose.email.clients.imap/imapmessageinfo/deleted) { get; } | Получает значение, указывающее, содержит ли свойство Flags флаг Deleted. |
| [Draft](../../aspose.email.clients.imap/imapmessageinfo/draft) { get; } | Получает значение, указывающее, содержит ли свойство Flags флаг Draft. |
| [ExtraParameters](../../aspose.email.clients.imap/imapmessageinfo/extraparameters) { get; } | Получает дополнительные параметры сообщения. |
| [Flagged](../../aspose.email.clients.imap/imapmessageinfo/flagged) { get; } | Получает значение, указывающее, содержит ли свойство Flags флаг Flagged. |
| [Flags](../../aspose.email.clients.imap/imapmessageinfo/flags) { get; } | Получает флаги сообщения. |
| [From](../../aspose.email.clients/messageinfobase/from) { get; } | Получает список авторов этого сообщения. |
| [Headers](../../aspose.email.clients/messageinfobase/headers) { get; } | Получает заголовки сообщения электронной почты. |
| [InternalDate](../../aspose.email.clients.imap/imapmessageinfo/internaldate) { get; } | Внутренняя дата и время сообщения на сервере. Это не дата и время в заголовке [RFC-2822], а скорее дата и время, отражающие время получения сообщения. - В случае сообщений, доставленных через [SMTP], это ДОЛЖНО быть датой и временем окончательной доставки сообщения, как определено [SMTP]. - В случае сообщений, доставленных командой COPY IMAP4rev1, это ДОЛЖНЫ быть внутренние дата и время исходного сообщения. - В случае сообщений, доставленных командой IMAP4rev1 APPEND, это ДОЛЖНЫ быть дата и время, указанные в описании команды APPEND. - Все остальные случаи определяются реализацией. |
| [IsRead](../../aspose.email.clients.imap/imapmessageinfo/isread) { get; } | Получает значение, указывающее, содержит ли свойство Flags флаг чтения. |
| [ListUnsubscribe](../../aspose.email.clients/messageinfobase/listunsubscribe) { get; } | Поле List-Unsubscribe описывает команду (желательно с использованием почты) для прямой отписки пользователя (удаление его из списка). Подробнее см. https://tools.ietf.org/html/rfc2369 |
| [MessageId](../../aspose.email.clients/messageinfobase/messageid) { get; } | Получает идентификатор сообщения. |
| [ModificationSequence](../../aspose.email.clients.imap/imapmessageinfo/modificationsequence) { get; } | Получает последовательность модификации этого сообщения. Подробнее:https://tools.ietf.org/html/rfc7162 |
| [ParentFolder](../../aspose.email.clients.imap/imapmessageinfo/parentfolder) { get; } | Получает родительскую папку для сообщения |
| virtual [Properties](../../aspose.email.clients/messageinfobase/properties) { get; } | Получает свойства карты. |
| [Recent](../../aspose.email.clients.imap/imapmessageinfo/recent) { get; } | Получает значение, указывающее, содержит ли свойство Flags флаг Recent. |
| [ReplyTo](../../aspose.email.clients/messageinfobase/replyto) { get; } | Получает список адресов, которые должны получать ответы на это сообщение. |
| [Sender](../../aspose.email.clients/messageinfobase/sender) { get; } | Получает отправителя этого сообщения. |
| [SequenceNumber](../../aspose.email.clients.imap/imapmessageinfo/sequencenumber) { get; } | Получает порядковый номер сообщения. |
| [Size](../../aspose.email.clients/messageinfobase/size) { get; } | Получает размер сообщения электронной почты. |
| [Subject](../../aspose.email.clients/messageinfobase/subject) { get; } | Получает тему сообщения электронной почты. |
| virtual [To](../../aspose.email.clients/messageinfobase/to) { get; } | Получает получателей сообщения электронной почты. |
| [UniqueId](../../aspose.email.clients.imap/imapmessageinfo/uniqueid) { get; } | Получает уникальный идентификатор сообщения. |

## Методы

| Имя | Описание |
| --- | --- |
| [ContainsKeyword](../../aspose.email.clients.imap/imapmessageinfo/containskeyword)(string) | Получает значение, указывающее, содержит ли свойство Flags флаг ключевого слова. |
| virtual [Dispose](../../aspose.email.clients/messageinfobase/dispose)() | Выполняет задачи, связанные с освобождением, освобождением или сбросом неуправляемых ресурсов. |
| override [ToString](../../aspose.email.clients.imap/imapmessageinfo/tostring)() | Возвращает строку, представляющую текущий объект. |

### Смотрите также

* class [MessageInfoBase](../../aspose.email.clients/messageinfobase)
* пространство имен [Aspose.Email.Clients.Imap](../../aspose.email.clients.imap)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
