---
title: PersonalStorageQueryBuilder
second_title: Справочник по Aspose.Email для .NET API
description: Представляет построитель поискового выражения  который используется pst.
type: docs
weight: 20310
url: /ru/net/aspose.email.storage.pst/personalstoragequerybuilder/
---
## PersonalStorageQueryBuilder class

Представляет построитель поискового выражения , который используется pst.

```csharp
public sealed class PersonalStorageQueryBuilder : MailQueryBuilder
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PersonalStorageQueryBuilder](personalstoragequerybuilder)() | Инициализирует новый экземпляр[`PersonalStorageQueryBuilder`](../personalstoragequerybuilder) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Bcc](../../aspose.email.tools.search/mailquerybuilder/bcc) { get; } | Получает поле, позволяющее найти сообщения, содержащие указанную строку в поле BCC структуры конверта. |
| [Body](../../aspose.email.tools.search/mailquerybuilder/body) { get; } | Получает поле, позволяющее найти сообщения, содержащие указанную строку в теле сообщения. |
| [Cc](../../aspose.email.tools.search/mailquerybuilder/cc) { get; } | Получает поле, позволяющее найти сообщения, содержащие указанную строку в поле CC структуры конверта. |
| [ContainerClass](../../aspose.email.storage.pst/personalstoragequerybuilder/containerclass) { get; } | Получает папки с указанным классом сообщений. |
| [ContentsCount](../../aspose.email.storage.pst/personalstoragequerybuilder/contentscount) { get; } | Поиск папок с указанным количеством содержимого. |
| [DefaultEncoding](../../aspose.email.tools.search/mailquerybuilder/defaultencoding) { get; } | Получает кодировку (набор символов) по умолчанию для построителя запросов |
| [FolderName](../../aspose.email.storage.pst/personalstoragequerybuilder/foldername) { get; } | Поиск папок с указанным отображаемым именем. |
| [From](../../aspose.email.tools.search/mailquerybuilder/from) { get; } | Получает поле, позволяющее найти сообщения, содержащие указанную строку в поле FROM структуры конверта. |
| [Importance](../../aspose.email.storage.pst/personalstoragequerybuilder/importance) { get; } | Поиск сообщений с указанной важностью. |
| [InternalDate](../../aspose.email.tools.search/mailquerybuilder/internaldate) { get; } | Получает поле, позволяющее находить сообщения по внутренней дате. |
| [MessageClass](../../aspose.email.storage.pst/personalstoragequerybuilder/messageclass) { get; } | Получает сообщения с указанным классом сообщений. |
| [MessageId](../../aspose.email.storage.pst/personalstoragequerybuilder/messageid) { get; } | Получает поле, позволяющее найти сообщения, содержащие указанную строку в поле MessageId структуры конверта. |
| [MessageSize](../../aspose.email.storage.pst/personalstoragequerybuilder/messagesize) { get; } | Поиск сообщений указанного размера. |
| [OnlyFoldersCreatedByUser](../../aspose.email.storage.pst/personalstoragequerybuilder/onlyfolderscreatedbyuser) { get; } | Получает папки, созданные пользователем, т.е. исключает все стандартные папки IPM. |
| [SentDate](../../aspose.email.tools.search/mailquerybuilder/sentdate) { get; } | Получает поле, позволяющее находить сообщения по дате отправки. |
| [Subject](../../aspose.email.tools.search/mailquerybuilder/subject) { get; } | Получает поле, позволяющее найти сообщения, содержащие указанную строку в поле SUBJECT структуры конверта. |
| [Text](../../aspose.email.tools.search/mailquerybuilder/text) { get; } | Получает поле, позволяющее найти сообщения, содержащие указанную строку в заголовках (тема, от, кому, копия) и теле сообщения. |
| [To](../../aspose.email.tools.search/mailquerybuilder/to) { get; } | Получает поле, позволяющее найти сообщения, содержащие указанную строку в поле TO структуры конверта. |
| [UnreadContentsCount](../../aspose.email.storage.pst/personalstoragequerybuilder/unreadcontentscount) { get; } | Поиск в папках с указанным количеством непрочитанного содержимого. |

## Методы

| Имя | Описание |
| --- | --- |
| [FindConversationThread](../../aspose.email.storage.pst/personalstoragequerybuilder/findconversationthread)(MessageInfo) | Находит ветку беседы. |
| [GetQuery](../../aspose.email.tools.search/mailquerybuilder/getquery)() | Получает запрос. |
| [HasFlags](../../aspose.email.storage.pst/personalstoragequerybuilder/hasflags)(MapiMessageFlags) | Поиск сообщений с указанными флагами. |
| [HasNoFlags](../../aspose.email.storage.pst/personalstoragequerybuilder/hasnoflags)(MapiMessageFlags) | Поиск сообщений с неопределенными флагами. |
| [HasNoSubfolders](../../aspose.email.storage.pst/personalstoragequerybuilder/hasnosubfolders)() | Поиск в папках, не содержащих вложенных папок. |
| [HasSubfolders](../../aspose.email.storage.pst/personalstoragequerybuilder/hassubfolders)() | Поиск папок, содержащих подпапки. |
| [Or](../../aspose.email.tools.search/mailquerybuilder/or)(MailQuery, MailQuery) | Поиск сообщений, соответствующих любому ключу поиска. Обеспечивает дизъюнкт между двумя выражениями (ИЛИ). |

### Смотрите также

* class [MailQueryBuilder](../../aspose.email.tools.search/mailquerybuilder)
* пространство имен [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
