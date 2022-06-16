---
title: ExchangeMessageInfo
second_title: Справочник по Aspose.Email для .NET API
description: ExchangeMessageInfo представляет информацию о сообщении электронной почты полученную из хранилища Exchange.
type: docs
weight: 3400
url: /ru/net/aspose.email.clients.exchange/exchangemessageinfo/
---
## ExchangeMessageInfo class

ExchangeMessageInfo представляет информацию о сообщении электронной почты, полученную из хранилища Exchange.

```csharp
public abstract class ExchangeMessageInfo : MessageInfoBase
```

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [Attachments](../../aspose.email.clients.exchange/exchangemessageinfo/attachments) { get; } | Получает вложения сообщения |
| virtual [Bcc](../../aspose.email.clients/messageinfobase/bcc) { get; } | Получает скрытую копию сообщения электронной почты. |
| virtual [CC](../../aspose.email.clients/messageinfobase/cc) { get; } | Получает копию сообщения электронной почты. |
| virtual [Date](../../aspose.email.clients/messageinfobase/date) { get; } | Дата создания указывает дату и время, когда создатель сообщения указал что сообщение было завершено и готово к отправке по почте система. Например, это может быть время, когда пользователь нажимает кнопку "отправить" или "отправить" в прикладной программе. В любом случае, он конкретно не предназначен для передачи времени фактической передачи сообщения, а скорее времени, в которое человек или другой создатель сообщения поставил сообщение в его окончательную форму, готово к транспортировке. (Например, пользователь портативного компьютера, не подключенный к сети, может поставить сообщение в очередь на доставку. Дата создания должна содержать дату и время, когда пользователь поставил сообщение в очередь, не время, когда пользователь подключился к сети для отправки сообщения.) |
| [From](../../aspose.email.clients/messageinfobase/from) { get; } | Получает список авторов этого сообщения. |
| virtual [HasAttachments](../../aspose.email.clients.exchange/exchangemessageinfo/hasattachments) { get; } | Получает значение, указывающее, содержит ли сообщение хотя бы одно вложение. |
| [Headers](../../aspose.email.clients/messageinfobase/headers) { get; } | Получает заголовки сообщения электронной почты. |
| virtual [InternalDate](../../aspose.email.clients.exchange/exchangemessageinfo/internaldate) { get; } | Внутренняя дата и время сообщения на сервере. Это не дата и время в заголовке [RFC-2822], а скорее дата и время, отражающие время получения сообщения. - В случае сообщений, доставленных через [SMTP], это ДОЛЖНО быть датой и временем окончательной доставки сообщения, как определено [SMTP]. - В случае сообщений, доставленных командой COPY IMAP4rev1, это ДОЛЖНЫ быть внутренние дата и время исходного сообщения. - В случае сообщений, доставленных командой IMAP4rev1 APPEND, это ДОЛЖНЫ быть дата и время, указанные в описании команды APPEND. - Все остальные случаи определяются реализацией. |
| virtual [IsRead](../../aspose.email.clients.exchange/exchangemessageinfo/isread) { get; } | Получает значение, указывающее, прочитано ли сообщение |
| [ListUnsubscribe](../../aspose.email.clients/messageinfobase/listunsubscribe) { get; } | Поле List-Unsubscribe описывает команду (желательно с использованием почты) для прямой отписки пользователя (удаление его из списка). Подробнее см. https://tools.ietf.org/html/rfc2369 |
| virtual [MessageClass](../../aspose.email.clients.exchange/exchangemessageinfo/messageclass) { get; } | Получает строку, представляющую класс сообщения. Свойство соответствует свойству MAPI PidTagMessageClass. |
| [MessageId](../../aspose.email.clients/messageinfobase/messageid) { get; } | Получает идентификатор сообщения. |
| virtual [MessageInfoType](../../aspose.email.clients.exchange/exchangemessageinfo/messageinfotype) { get; } | Получает тип сообщения |
| virtual [Properties](../../aspose.email.clients/messageinfobase/properties) { get; } | Получает свойства карты. |
| [ReplyTo](../../aspose.email.clients/messageinfobase/replyto) { get; } | Получает список адресов, которые должны получать ответы на это сообщение. |
| [Sender](../../aspose.email.clients/messageinfobase/sender) { get; } | Получает отправителя этого сообщения. |
| [Size](../../aspose.email.clients/messageinfobase/size) { get; } | Получает размер сообщения электронной почты. |
| [Subject](../../aspose.email.clients/messageinfobase/subject) { get; } | Получает тему сообщения электронной почты. |
| virtual [To](../../aspose.email.clients/messageinfobase/to) { get; } | Получает получателей сообщения электронной почты. |
| virtual [UniqueUri](../../aspose.email.clients.exchange/exchangemessageinfo/uniqueuri) { get; } | Получает уникальный URI сообщения. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Dispose](../../aspose.email.clients/messageinfobase/dispose)() | Выполняет задачи, связанные с освобождением, освобождением или сбросом неуправляемых ресурсов. |
| override [ToString](../../aspose.email.clients/messageinfobase/tostring)() | Строка, представляющая текущий объект. |

### Смотрите также

* class [MessageInfoBase](../../aspose.email.clients/messageinfobase)
* пространство имен [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
