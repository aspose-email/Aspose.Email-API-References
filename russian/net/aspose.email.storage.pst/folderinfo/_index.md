---
title: FolderInfo
second_title: Справочник по Aspose.Email для .NET API
description: Представляет информацию о личной папке в PST.
type: docs
weight: 20110
url: /ru/net/aspose.email.storage.pst/folderinfo/
---
## FolderInfo class

Представляет информацию о личной папке в PST.

```csharp
public sealed class FolderInfo
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FolderInfo](folderinfo)() | Инициализирует новый экземпляр класса[`FolderInfo`](../folderinfo). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [ContainerClass](../../aspose.email.storage.pst/folderinfo/containerclass) { get; } | Получает класс контейнера объекта папки. |
| [ContentCount](../../aspose.email.storage.pst/folderinfo/contentcount) { get; } | Получает общее количество элементов в папке. |
| [ContentUnreadCount](../../aspose.email.storage.pst/folderinfo/contentunreadcount) { get; } | Получает количество непрочитанных элементов в папке. |
| [DisplayName](../../aspose.email.storage.pst/folderinfo/displayname) { get; } | Получает отображаемое имя папки. |
| [EntryId](../../aspose.email.storage.pst/folderinfo/entryid) { get; } | Получает идентификатор записи. |
| [EntryIdString](../../aspose.email.storage.pst/folderinfo/entryidstring) { get; } | Получает строковое представление идентификатора записи. |
| [HasSubFolders](../../aspose.email.storage.pst/folderinfo/hassubfolders) { get; } | Получает значение, указывающее, есть ли у объекта Folder вложенные папки. |
| [LastModificationTime](../../aspose.email.storage.pst/folderinfo/lastmodificationtime) { get; } | Получает время последней модификации. |
| [Properties](../../aspose.email.storage.pst/folderinfo/properties) { get; } | Получает свойства папки. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddFile](../../aspose.email.storage.pst/folderinfo/addfile)(string, string) | Добавляет файл в папку pst. |
| [AddMapiMessageItem](../../aspose.email.storage.pst/folderinfo/addmapimessageitem)(IMapiMessageItem) | Добавляет объект IMapiMessageItem в папку. |
| [AddMessage](../../aspose.email.storage.pst/folderinfo/addmessage)(MapiMessage) | Добавляет новое сообщение в папку. |
| [AddMessages](../../aspose.email.storage.pst/folderinfo/addmessages)(IEnumerable&lt;MapiMessage&gt;) | Обеспечивает добавление сообщений в массовом режиме. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder)(string) | Добавляет новую подпапку. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder_1)(string, bool) | Добавляет новую подпапку. |
| [AddSubFolder](../../aspose.email.storage.pst/folderinfo/addsubfolder#addsubfolder_2)(string, string) | Добавляет новую подпапку. |
| [ChangeContainerClass](../../aspose.email.storage.pst/folderinfo/changecontainerclass)(string) | Изменяет класс контейнера. |
| [ChangeDisplayName](../../aspose.email.storage.pst/folderinfo/changedisplayname)(string) | Изменяет отображаемое имя. |
| [ChangeMessages](../../aspose.email.storage.pst/folderinfo/changemessages#changemessages)(MapiPropertyCollection) | Изменяет все сообщения в папке. |
| [ChangeMessages](../../aspose.email.storage.pst/folderinfo/changemessages#changemessages_1)(IEnumerable&lt;string&gt;, MapiPropertyCollection) | Изменяет сообщения в папке. |
| [DeleteChildItem](../../aspose.email.storage.pst/folderinfo/deletechilditem)(byte[]) | Удаляет элемент (папку или сообщение) по его entryId. |
| [DeleteChildItems](../../aspose.email.storage.pst/folderinfo/deletechilditems)(IEnumerable&lt;string&gt;) | Удаляет дочерние сообщения. |
| [EnumerateFolders](../../aspose.email.storage.pst/folderinfo/enumeratefolders#enumeratefolders)() | Предоставляет перечислитель, который поддерживает итерацию подпапок в папке. |
| [EnumerateFolders](../../aspose.email.storage.pst/folderinfo/enumeratefolders#enumeratefolders_1)(FolderKind) | Предоставляет перечислитель, который поддерживает итерацию подпапок в папке. |
| [EnumerateMapiMessages](../../aspose.email.storage.pst/folderinfo/enumeratemapimessages)() | Предоставляет перечислитель, который поддерживает итерацию сообщений в папке. |
| [EnumerateMessageObjects](../../aspose.email.storage.pst/folderinfo/enumeratemessageobjects)() | Предоставляет перечислитель, который поддерживает итерацию сообщений в папке. |
| [EnumerateMessages](../../aspose.email.storage.pst/folderinfo/enumeratemessages)() | Предоставляет перечислитель, который поддерживает итерацию сообщений в папке. |
| [EnumerateMessagesEntryId](../../aspose.email.storage.pst/folderinfo/enumeratemessagesentryid)() | Перечисляет entryID сообщений. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents)() | Получить коллекцию сообщений. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_3)(bool) | Получить коллекцию сообщений. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_2)(MailQuery) | Получить коллекцию сообщений. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_1)(MessageKind) | Получить коллекцию сообщений. |
| [GetContents](../../aspose.email.storage.pst/folderinfo/getcontents#getcontents_4)(int, int) | Получает коллекцию сообщений. |
| [GetSubFolder](../../aspose.email.storage.pst/folderinfo/getsubfolder#getsubfolder)(string) | Получить подпапку. |
| [GetSubFolder](../../aspose.email.storage.pst/folderinfo/getsubfolder#getsubfolder_1)(string, bool) | Получает вложенную папку. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders)() | Получает набор вложенных папок. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders_1)(FolderKind) | Получает набор вложенных папок. |
| [GetSubFolders](../../aspose.email.storage.pst/folderinfo/getsubfolders#getsubfolders_2)(MailQuery) | Получает набор вложенных папок. |
| [MergeWith](../../aspose.email.storage.pst/folderinfo/mergewith#mergewith)(FolderInfo) | Сливает папку с папкой из другого pst. |
| [MergeWith](../../aspose.email.storage.pst/folderinfo/mergewith#mergewith_1)(FolderInfo, bool) | Сливает папку с папкой из другого pst. Событие OnItemMoved вызывается как для сообщений, так и для каталогов. |
| [MoveContents](../../aspose.email.storage.pst/folderinfo/movecontents)(FolderInfo) | Перемещает содержимое в новую папку. |
| [MoveSubfolders](../../aspose.email.storage.pst/folderinfo/movesubfolders)(FolderInfo) | Перемещает вложенные папки в новую родительскую папку. |
| [RetrieveFullPath](../../aspose.email.storage.pst/folderinfo/retrievefullpath)() | Получает полный путь к папке в файле PST. |
| [UpdateMessage](../../aspose.email.storage.pst/folderinfo/updatemessage)(string, MapiMessageItemBase) | Обновляет сообщение в папке. |

### Смотрите также

* пространство имен [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
