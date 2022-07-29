---
title: PersonalStorage
second_title: Справочник по Aspose.Email для .NET API
description: Представляет файл личной таблицы хранения .pst.
type: docs
weight: 20290
url: /ru/net/aspose.email.storage.pst/personalstorage/
---
## PersonalStorage class

Представляет файл личной таблицы хранения (.pst).

```csharp
public class PersonalStorage : IDisposable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PersonalStorage](personalstorage)(TraversalExceptionsCallback) | Инициализирует новый экземпляр[`PersonalStorage`](../personalstorage) class. Позволяет установить метод обратного вызова для обработки исключений, возникающих при обходе PST. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [CanWrite](../../aspose.email.storage.pst/personalstorage/canwrite) { get; } | Получает значение, указывающее, поддерживает ли текущий pst запись. |
| [Format](../../aspose.email.storage.pst/personalstorage/format) { get; } | Получает формат файла. |
| [IsUnicode](../../aspose.email.storage.pst/personalstorage/isunicode) { get; } | Получает значение, указывающее, является ли формат файла PST Unicode. Существуют две версии формата файла PST: Unicode и ANSI. |
| [RootFolder](../../aspose.email.storage.pst/personalstorage/rootfolder) { get; } | Получает корневую папку PST. |
| [Store](../../aspose.email.storage.pst/personalstorage/store) { get; } | Получает хранилище сообщений PST. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create)(Stream, FileFormatVersion) | Создает PST в потоке. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_4)(string, FileFormatVersion) | Создает новый файл PST с указанным именем файла. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_1)(Stream, FileFormatVersion, bool) | Создает PST в потоке. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_3)(Stream, FileFormatVersion, CancellationToken) | Создает PST в потоке. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_5)(string, FileFormatVersion, CancellationToken) | Создает новый файл PST с указанным именем файла. |
| static [Create](../../aspose.email.storage.pst/personalstorage/create#create_2)(Stream, FileFormatVersion, bool, CancellationToken) | Создает PST в потоке. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile)(string) | Загрузить PST из файла. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_3)(string, bool) | Загрузить PST из файла. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_5)(string, CancellationToken) | Загрузить PST из файла. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_1)(string, PersonalStorageLoadOptions) | Загрузить PST из файла. |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_4)(string, bool, CancellationToken) |  |
| static [FromFile](../../aspose.email.storage.pst/personalstorage/fromfile#fromfile_2)(string, PersonalStorageLoadOptions, CancellationToken) | Загрузить PST из файла. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream)(Stream) | Загрузить PST из потока. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_3)(Stream, bool) | Загрузить PST из потока. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_5)(Stream, CancellationToken) | Загрузить PST из файла. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_1)(Stream, PersonalStorageLoadOptions) | Загрузить PST из потока. |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_4)(Stream, bool, CancellationToken) |  |
| static [FromStream](../../aspose.email.storage.pst/personalstorage/fromstream#fromstream_2)(Stream, PersonalStorageLoadOptions, CancellationToken) | Загрузить PST из файла. |
| [ChangeMessage](../../aspose.email.storage.pst/personalstorage/changemessage)(string, MapiPropertyCollection) | Изменяет свойства сообщения. |
| [ConvertTo](../../aspose.email.storage.pst/personalstorage/convertto)(FileFormat) | Преобразует текущий объект в указанный формат. |
| [CreatePredefinedFolder](../../aspose.email.storage.pst/personalstorage/createpredefinedfolder#createpredefinedfolder)(string, StandardIpmFolder) | Создает папку стандартных межличностных сообщений (IPM). |
| [CreatePredefinedFolder](../../aspose.email.storage.pst/personalstorage/createpredefinedfolder#createpredefinedfolder_1)(string, StandardIpmFolder, bool) | Создает папку стандартных межличностных сообщений (IPM). |
| [Dispose](../../aspose.email.storage.pst/personalstorage/dispose)() | Выполняет определяемые приложением задачи, связанные с освобождением, выпуском или сбросом неуправляемых ресурсов. |
| [EnumerateMessages](../../aspose.email.storage.pst/personalstorage/enumeratemessages#enumeratemessages)(string) | Предоставляет перечислитель, поддерживающий итерацию сообщений в папке. |
| [EnumerateMessages](../../aspose.email.storage.pst/personalstorage/enumeratemessages#enumeratemessages_1)(string, int, int) | Предоставляет перечислитель, поддерживающий итерацию сообщений в папке. |
| [ExtractAttachments](../../aspose.email.storage.pst/personalstorage/extractattachments#extractattachments)(MessageInfo) | Извлекает вложения. |
| [ExtractAttachments](../../aspose.email.storage.pst/personalstorage/extractattachments#extractattachments_1)(string) | Извлекает вложения. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage_1)(byte[]) | Получить сообщение от PST. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage)(MessageInfo) | Получить сообщение от PST. |
| [ExtractMessage](../../aspose.email.storage.pst/personalstorage/extractmessage#extractmessage_2)(string) | Получить сообщение от PST. |
| [ExtractProperty](../../aspose.email.storage.pst/personalstorage/extractproperty)(byte[], long) | Получает указанное свойство элемента без полного извлечения элемента. |
| [FindMessages](../../aspose.email.storage.pst/personalstorage/findmessages)(string) | Находит идентификаторы сообщений для текущей папки. Может быть полезно в случае чтения поврежденного файла pst, когда методы GetContents и EnumerateMessages могли вызвать исключение. |
| [FindSubfolders](../../aspose.email.storage.pst/personalstorage/findsubfolders)(string) | Находит идентификаторы подпапок для текущей папки. Может быть полезно в случае чтения поврежденного файла pst, когда методы GetSubfolders и EnumerateFolders могли вызвать исключение. |
| [GetFolderById](../../aspose.email.storage.pst/personalstorage/getfolderbyid#getfolderbyid)(byte[]) | Получает личную папку из PST. |
| [GetFolderById](../../aspose.email.storage.pst/personalstorage/getfolderbyid#getfolderbyid_1)(string) | Получает личную папку из PST. |
| [GetParentFolder](../../aspose.email.storage.pst/personalstorage/getparentfolder#getparentfolder)(byte[]) | Получает родительскую папку сообщения. |
| [GetParentFolder](../../aspose.email.storage.pst/personalstorage/getparentfolder#getparentfolder_1)(string) | Получает родительскую папку сообщения. |
| [GetPredefinedFolder](../../aspose.email.storage.pst/personalstorage/getpredefinedfolder)(StandardIpmFolder) | Получает стандартную папку межличностных сообщений (IPM) из PST. Outlook может создавать несколько папок по умолчанию, , таких как Исходящие, Удаленные, Отправленные и т. д. |
| [Load](../../aspose.email.storage.pst/personalstorage/load#load)(Stream) | Загрузить PST из потока. Этот метод используется, когда объект PersonalStorage создается с помощью конструктора. |
| [Load](../../aspose.email.storage.pst/personalstorage/load#load_1)(string) | Загрузить PST из файла. Этот метод используется, когда объект PersonalStorage создается с помощью конструктора. |
| [MergeWith](../../aspose.email.storage.pst/personalstorage/mergewith#mergewith)(Stream[]) | Объединяет хранилище pst с одним или несколькими другими потоками pst. Таким образом, объединенный поток является источником. |
| [MergeWith](../../aspose.email.storage.pst/personalstorage/mergewith#mergewith_1)(string[]) | Объединяет хранилище pst с одним или несколькими другими файлами pst. Таким образом, объединенные файлы являются исходными файлами. |
| [MoveItem](../../aspose.email.storage.pst/personalstorage/moveitem#moveitem)(FolderInfo, FolderInfo) | Перемещает указанную папку в новую родительскую папку в текущем pst. |
| [MoveItem](../../aspose.email.storage.pst/personalstorage/moveitem#moveitem_1)(MessageInfo, FolderInfo) | Перемещает указанное сообщение в новую папку в текущем pst. |
| [SaveAs](../../aspose.email.storage.pst/personalstorage/saveas#saveas)(Stream, FileFormat) | Сохраняет текущий объект в указанный формат файла в потоке. |
| [SaveAs](../../aspose.email.storage.pst/personalstorage/saveas#saveas_1)(string, FileFormat) | Сохраняет текущий объект в указанном формате файла в другом файле. |
| [SaveMessageToStream](../../aspose.email.storage.pst/personalstorage/savemessagetostream)(string, Stream) | Сохраняет сообщение с указанным идентификатором записи в потоке. |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto#splitinto_1)(IList&lt;MailQuery&gt;, string) | Разбивает хранилище pst на основе критериев. |
| [SplitInto](../../aspose.email.storage.pst/personalstorage/splitinto#splitinto)(long, string) | Разбивает хранилище pst на части меньшего размера. |
| [TryToGetFolderById](../../aspose.email.storage.pst/personalstorage/trytogetfolderbyid)(string, out FolderInfo) | Получает папку, связанную с указанным идентификатором записи. |
| [TryToSaveMessage](../../aspose.email.storage.pst/personalstorage/trytosavemessage)(string, Stream) | Сохраняет сообщение с указанным идентификатором записи в потоке. |

### Смотрите также

* пространство имен [Aspose.Email.Storage.Pst](../../aspose.email.storage.pst)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
