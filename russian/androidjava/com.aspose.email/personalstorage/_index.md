---
title: PersonalStorage
second_title: Aspose.Email for Android via Java API Reference
description: Представляет файл Personal Storage Table (.pst).
type: docs
weight: 344
url: /ru/androidjava/com.aspose.email/personalstorage/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class PersonalStorage implements System.IDisposable, Closeable
```

Представляет файл Personal Storage Table (.pst).
## Constructors

| Constructor | Описание |
| --- | --- |
| [PersonalStorage(TraversalExceptionsCallback callback)](#PersonalStorage-com.aspose.email.TraversalExceptionsCallback-) | Инициализирует новый экземпляр класса [PersonalStorage](../../com.aspose.email/personalstorage). |
## Поля

| Поле | Описание |
| --- | --- |
| [ItemMoved](#ItemMoved) | Происходит, когда элемент перемещён в другую папку. |
| [StorageProcessed](#StorageProcessed) | Происходит при операциях разбиения и объединения, когда создаётся новый фрагмент pst или обрабатывается следующий файл, который будет объединён. |
## Methods

| Method | Описание |
| --- | --- |
| [canWrite()](#canWrite--) | Возвращает значение, указывающее, поддерживает ли текущий pst запись. |
| [changeMessage(String entryId, MapiPropertyCollection updatedProperties)](#changeMessage-java.lang.String-com.aspose.email.MapiPropertyCollection-) | Изменяет свойства сообщения. |
| [close()](#close--) |  |
| [convertTo(int format)](#convertTo-int-) | Преобразует текущий объект в указанный формат. |
| [create(System.IO.Stream stream, int version)](#create-com.aspose.ms.System.IO.Stream-int-) | Создаёт PST в потоке. |
| [create(System.IO.Stream stream, int version, boolean leaveStreamOpen)](#create-com.aspose.ms.System.IO.Stream-int-boolean-) | Создаёт PST в потоке. |
| [create(OutputStream stream, int version)](#create-java.io.OutputStream-int-) | Создаёт PST в потоке. |
| [create(OutputStream stream, int version, boolean leaveStreamOpen)](#create-java.io.OutputStream-int-boolean-) | Создаёт PST в потоке. |
| [create(OutputStream stream, int blockSize, int version)](#create-java.io.OutputStream-int-int-) | Создаёт PST в потоке. |
| [create(String fileName, int version)](#create-java.lang.String-int-) | Создаёт новый файл PST с указанным именем файла. |
| [createPredefinedFolder(String name, int defaultFolder)](#createPredefinedFolder-java.lang.String-int-) | Создаёт стандартную папку межличностных сообщений (IPM). |
| [createPredefinedFolder(String name, int defaultFolder, boolean createHierarchy)](#createPredefinedFolder-java.lang.String-int-boolean-) | Создаёт стандартную папку межличностных сообщений (IPM). |
| [dispose()](#dispose--) | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [enumerateMessages(String entryId)](#enumerateMessages-java.lang.String-) | Предоставляет перечислитель, поддерживающий итерацию сообщений в папке. |
| [enumerateMessages(String entryId, int startIndex, int count)](#enumerateMessages-java.lang.String-int-int-) | Предоставляет перечислитель, поддерживающий итерацию сообщений в папке. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractAttachments(MessageInfo messageInfo)](#extractAttachments-com.aspose.email.MessageInfo-) | Извлекает вложения. |
| [extractAttachments(String entryId)](#extractAttachments-java.lang.String-) | Извлекает вложения. |
| [extractMessage(byte[] entryId)](#extractMessage-byte---) | Получить сообщение из PST. |
| [extractMessage(MessageInfo messageInfo)](#extractMessage-com.aspose.email.MessageInfo-) | Получить сообщение из PST. |
| [extractMessage(String entryId)](#extractMessage-java.lang.String-) | Получить сообщение из PST. |
| [extractProperty(byte[] entryId, long tag)](#extractProperty-byte---long-) | Получает указанное свойство элемента без полного извлечения элемента. |
| [findMessages(String parentEntryId)](#findMessages-java.lang.String-) | Находит идентификаторы сообщений для текущей папки. |
| [findSubfolders(String parentEntryId)](#findSubfolders-java.lang.String-) | Находит идентификаторы подпапок для текущей папки. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | Загрузить PST из файла. |
| [fromFile(String fileName, boolean writable)](#fromFile-java.lang.String-boolean-) | Загрузить PST из файла. |
| [fromFile(String fileName, PersonalStorageLoadOptions loadOptions)](#fromFile-java.lang.String-com.aspose.email.PersonalStorageLoadOptions-) | Загрузить PST из файла. |
| [fromStream(System.IO.Stream stream)](#fromStream-com.aspose.ms.System.IO.Stream-) | Загрузить PST из потока. |
| [fromStream(System.IO.Stream stream, boolean writable)](#fromStream-com.aspose.ms.System.IO.Stream-boolean-) | Загрузить PST из потока. |
| [fromStream(System.IO.Stream stream, PersonalStorageLoadOptions loadOptions)](#fromStream-com.aspose.ms.System.IO.Stream-com.aspose.email.PersonalStorageLoadOptions-) | Загрузить PST из потока. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Загрузить PST из потока. |
| [fromStream(InputStream stream, boolean writable)](#fromStream-java.io.InputStream-boolean-) | Загрузить PST из потока. |
| [fromStream(InputStream stream, PersonalStorageLoadOptions loadOptions)](#fromStream-java.io.InputStream-com.aspose.email.PersonalStorageLoadOptions-) | Загрузить PST из потока. |
| [getClass()](#getClass--) |  |
| [getFolderById(byte[] entryId)](#getFolderById-byte---) | Получает личную папку из PST. |
| [getFolderById(String entryIdString)](#getFolderById-java.lang.String-) | Получает личную папку из PST. |
| [getFormat()](#getFormat--) | Получает формат файла. |
| [getParentFolder(byte[] entryId)](#getParentFolder-byte---) | Получает родительскую папку сообщения. |
| [getParentFolder(String entryIdString)](#getParentFolder-java.lang.String-) | Получает родительскую папку сообщения. |
| [getPredefinedFolder(int defaultFolder)](#getPredefinedFolder-int-) | Получает стандартную папку межличностных сообщений (IPM) из PST. |
| [getRootFolder()](#getRootFolder--) | Получает корневую папку PST. |
| [getStore()](#getStore--) | Получает хранилище сообщений PST. |
| [hashCode()](#hashCode--) |  |
| [isUnicode()](#isUnicode--) | Получает значение, указывающее, является ли формат файла PST Unicode. |
| [load(System.IO.Stream stream)](#load-com.aspose.ms.System.IO.Stream-) | Загрузить PST из потока. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Загрузить PST из потока. |
| [load(String fileName)](#load-java.lang.String-) | Загрузить PST из файла. |
| [mergeWith(InputStream[] sourceStreams)](#mergeWith-java.io.InputStream---) | Объединяет хранилище pst с одним или несколькими другими pst‑потоками. |
| [mergeWith(String[] sourceFileNames)](#mergeWith-java.lang.String---) | Объединяет хранилище pst с одним или несколькими другими pst‑файлами. |
| [moveItem(FolderInfo folder, FolderInfo newFolder)](#moveItem-com.aspose.email.FolderInfo-com.aspose.email.FolderInfo-) | Перемещает указанную папку в новую родительскую папку внутри текущего pst. |
| [moveItem(MessageInfo message, FolderInfo newFolder)](#moveItem-com.aspose.email.MessageInfo-com.aspose.email.FolderInfo-) | Перемещает указанное сообщение в новую папку внутри текущего pst. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveAs(OutputStream stream, int format)](#saveAs-java.io.OutputStream-int-) | Сохраняет текущий объект в указанный формат файла в потоке. |
| [saveAs(String fileName, int format)](#saveAs-java.lang.String-int-) | Сохраняет текущий объект в указанный формат файла в другом файле. |
| [saveMessageToFile(String entryId, String fileName)](#saveMessageToFile-java.lang.String-java.lang.String-) | saveMessageToFile. |
| [saveMessageToStream(String entryId, OutputStream stream)](#saveMessageToStream-java.lang.String-java.io.OutputStream-) | Сохраняет сообщение с указанным entryID в поток. |
| [splitInto(System.Collections.Generic.IGenericList<MailQuery> criteria, String path)](#splitInto-com.aspose.ms.System.Collections.Generic.IGenericList-com.aspose.email.MailQuery--java.lang.String-) | Разделяет хранилище pst на основе критериев. |
| [splitInto(long chunkSize, String path)](#splitInto-long-java.lang.String-) | Разделяет хранилище pst на части меньшего размера. |
| [toString()](#toString--) |  |
| [tryToGetFolderById(String entryIdString, FolderInfo[] folder)](#tryToGetFolderById-java.lang.String-com.aspose.email.FolderInfo---) | Получает папку, связанную с указанным entry ID. |
| [tryToSaveMessage(String entryId, OutputStream stream)](#tryToSaveMessage-java.lang.String-java.io.OutputStream-) | Сохраняет сообщение с указанным entryID в поток. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PersonalStorage(TraversalExceptionsCallback callback) {#PersonalStorage-com.aspose.email.TraversalExceptionsCallback-}
```
public PersonalStorage(TraversalExceptionsCallback callback)
```


Инициализирует новый экземпляр класса [PersonalStorage](../../com.aspose.email/personalstorage). Позволяет установить метод обратного вызова для обработки исключений, возникающих во время обхода PST.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| callback | [TraversalExceptionsCallback](../../com.aspose.email/traversalexceptionscallback) | Обратный вызов исключения. |

### ItemMoved {#ItemMoved}
```
public final Event<ItemMovedEventHandler> ItemMoved
```


Происходит, когда элемент перемещён в другую папку.

### StorageProcessed {#StorageProcessed}
```
public final Event<StorageProcessedEventHandler> StorageProcessed
```


Происходит при операциях разбиения и объединения, когда создаётся новый фрагмент pst или обрабатывается следующий файл, который будет объединён.

### canWrite() {#canWrite--}
```
public final boolean canWrite()
```


Возвращает значение, указывающее, поддерживает ли текущий pst запись.

**Returns:**
boolean
### changeMessage(String entryId, MapiPropertyCollection updatedProperties) {#changeMessage-java.lang.String-com.aspose.email.MapiPropertyCollection-}
```
public final void changeMessage(String entryId, MapiPropertyCollection updatedProperties)
```


Изменяет свойства сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| entryId | java.lang.String | Идентификатор записи сообщения. |
| updatedProperties | [MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) | Обновленные свойства. |

### close() {#close--}
```
public void close()
```




### convertTo(int format) {#convertTo-int-}
```
public final void convertTo(int format)
```


Преобразует текущий объект в указанный формат.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| формат | int | Формат FileFormat, в который нужно преобразовать текущий объект. |

### create(System.IO.Stream stream, int version) {#create-com.aspose.ms.System.IO.Stream-int-}
```
public static PersonalStorage create(System.IO.Stream stream, int version)
```


Создаёт PST в потоке.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Поток, в котором создаётся PST. |
|  | версия | int | Версия файла PST. |

--------------------

Примечание, сейчас поддерживается только создание версии файла Unicode. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the new PST.
### create(System.IO.Stream stream, int version, boolean leaveStreamOpen) {#create-com.aspose.ms.System.IO.Stream-int-boolean-}
```
public static PersonalStorage create(System.IO.Stream stream, int version, boolean leaveStreamOpen)
```


Создаёт PST в потоке.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Поток, в котором создаётся PST. |
| версия | int | Версия файла PST. |
|  | leaveStreamOpen | boolean | Оставлять поток открытым при освобождении PersonalStorage. |

--------------------

Примечание, сейчас поддерживается только создание версии файла Unicode. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the new PST.
### create(OutputStream stream, int version) {#create-java.io.OutputStream-int-}
```
public static PersonalStorage create(OutputStream stream, int version)
```


Создаёт PST в потоке.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток, в котором создаётся PST. |
|  | версия | int | Версия файла PST. |

--------------------

Примечание, сейчас поддерживается только создание версии файла Unicode. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the new PST.
### create(OutputStream stream, int version, boolean leaveStreamOpen) {#create-java.io.OutputStream-int-boolean-}
```
public static PersonalStorage create(OutputStream stream, int version, boolean leaveStreamOpen)
```


Создаёт PST в потоке.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток, в котором создаётся PST. |
| версия | int | Версия файла PST. |
|  | leaveStreamOpen | boolean | Оставлять поток открытым при освобождении PersonalStorage. |

--------------------

Примечание, сейчас поддерживается только создание версии файла Unicode. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the new PST.
### create(OutputStream stream, int blockSize, int version) {#create-java.io.OutputStream-int-int-}
```
public static PersonalStorage create(OutputStream stream, int blockSize, int version)
```


Создаёт PST в потоке.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток, в котором создаётся PST. |
| blockSize | int | Оптимальный размер блока для расширения кэш‑буфера (в байтах). |
|  | версия | int | Версия файла PST. |

--------------------

Примечание, сейчас поддерживается только создание версии файла Unicode. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the new PST.
### create(String fileName, int version) {#create-java.lang.String-int-}
```
public static PersonalStorage create(String fileName, int version)
```


Создаёт новый файл PST с указанным именем файла.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Полное имя файла. |
|  | версия | int | Версия файла PST. |

--------------------

Примечание, сейчас поддерживается только создание версии файла Unicode. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the new PST.
### createPredefinedFolder(String name, int defaultFolder) {#createPredefinedFolder-java.lang.String-int-}
```
public final FolderInfo createPredefinedFolder(String name, int defaultFolder)
```


Создаёт стандартную папку межличностных сообщений (IPM).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя папки. |
| defaultFolder | int | Значение перечисления [StandardIpmFolder](../../com.aspose.email/standardipmfolder). |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - A [FolderInfo](../../com.aspose.email/folderinfo) object that represents a standard IPM folder.
### createPredefinedFolder(String name, int defaultFolder, boolean createHierarchy) {#createPredefinedFolder-java.lang.String-int-boolean-}
```
public final FolderInfo createPredefinedFolder(String name, int defaultFolder, boolean createHierarchy)
```


Создаёт стандартную папку межличностных сообщений (IPM).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя папки. |
| defaultFolder | int | Значение перечисления [StandardIpmFolder](../../com.aspose.email/standardipmfolder). |
| createHierarchy | boolean | Если установить в  true , можно создать иерархию папок, используя строковую нотацию. Обратный слеш ('\\') используется в качестве разделителя пути. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - A [FolderInfo](../../com.aspose.email/folderinfo) object that represents a standard IPM folder.
### dispose() {#dispose--}
```
public final void dispose()
```


Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов.

### enumerateMessages(String entryId) {#enumerateMessages-java.lang.String-}
```
public final System.Collections.Generic.IGenericEnumerable<MessageInfo> enumerateMessages(String entryId)
```


Предоставляет перечислитель, поддерживающий итерацию сообщений в папке.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| entryId | java.lang.String | Строка, представляющая идентификатор записи родительской папки. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MessageInfo> -  System.Collections.Generic.IEnumerableltTgt , который представляет перечислитель, проходящий по сообщениям в папке.
### enumerateMessages(String entryId, int startIndex, int count) {#enumerateMessages-java.lang.String-int-int-}
```
public final System.Collections.Generic.IGenericEnumerable<MessageInfo> enumerateMessages(String entryId, int startIndex, int count)
```


Предоставляет перечислитель, поддерживающий итерацию сообщений в папке.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| entryId | java.lang.String | Строка, представляющая идентификатор записи родительской папки. |
| startIndex | int | Индекс начального сообщения. |
| count | int | Количество сообщений, которые будут получены. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MessageInfo> -  System.Collections.Generic.IEnumerableltTgt , который представляет перечислитель, проходящий по сообщениям в папке.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### extractAttachments(MessageInfo messageInfo) {#extractAttachments-com.aspose.email.MessageInfo-}
```
public final MapiAttachmentCollection extractAttachments(MessageInfo messageInfo)
```


Извлекает вложения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| messageInfo | [MessageInfo](../../com.aspose.email/messageinfo) | Информация о сообщении. |

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) - The [MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) that represents the collection of attachments.
### extractAttachments(String entryId) {#extractAttachments-java.lang.String-}
```
public final MapiAttachmentCollection extractAttachments(String entryId)
```


Извлекает вложения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| entryId | java.lang.String | Идентификатор записи сообщения. |

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) - The [MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) that represents the collection of attachments.
### extractMessage(byte[] entryId) {#extractMessage-byte---}
```
public final MapiMessage extractMessage(byte[] entryId)
```


Получить сообщение из PST.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| entryId | byte[] | EntryId сообщения. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - A MapiMessage object.
### extractMessage(MessageInfo messageInfo) {#extractMessage-com.aspose.email.MessageInfo-}
```
public final MapiMessage extractMessage(MessageInfo messageInfo)
```


Получить сообщение из PST.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| messageInfo | [MessageInfo](../../com.aspose.email/messageinfo) | Объект MessageInfo, представляющий информацию о сообщении. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - A MapiMessage object.
### extractMessage(String entryId) {#extractMessage-java.lang.String-}
```
public final MapiMessage extractMessage(String entryId)
```


Получить сообщение из PST.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| entryId | java.lang.String | Строковое представление EntryId. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - A MapiMessage object.
### extractProperty(byte[] entryId, long tag) {#extractProperty-byte---long-}
```
public final MapiProperty extractProperty(byte[] entryId, long tag)
```


Получает указанное свойство элемента без полного извлечения элемента.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| entryId | byte[] | Идентификатор записи элемента. |
|  | tag | long | Тег свойства. |

--------------------

Если свойство не найдено, возвращается null. |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - The MapiProperty.
### findMessages(String parentEntryId) {#findMessages-java.lang.String-}
```
public final System.Collections.Generic.IGenericList<String> findMessages(String parentEntryId)
```


Находит идентификаторы сообщений для текущей папки. Может быть полезно при чтении повреждённого pst, когда методы GetContents и EnumerateMessages могут вызвать исключение.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| parentEntryId | java.lang.String | Идентификатор записи родительской папки. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.String> - Коллекция идентификаторов записей.
### findSubfolders(String parentEntryId) {#findSubfolders-java.lang.String-}
```
public final System.Collections.Generic.IGenericList<String> findSubfolders(String parentEntryId)
```


Находит идентификаторы подпапок для текущей папки. Может быть полезно при чтении повреждённого pst, когда методы GetSubfolders и EnumerateFolders могут вызвать исключение.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| parentEntryId | java.lang.String | Идентификатор записи родительской папки. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.String> - Коллекция идентификаторов записей.
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static PersonalStorage fromFile(String fileName)
```


Загрузить PST из файла.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
|  | fileName | java.lang.String | Имя файла .pst. |

--------------------

По умолчанию pst будет поддерживать запись. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### fromFile(String fileName, boolean writable) {#fromFile-java.lang.String-boolean-}
```
public static PersonalStorage fromFile(String fileName, boolean writable)
```


Загрузить PST из файла.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла .pst. |
| writable | boolean | Если установить значение  true , то файл pst будет поддерживать запись, иначе он откроется в режиме только для чтения. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### fromFile(String fileName, PersonalStorageLoadOptions loadOptions) {#fromFile-java.lang.String-com.aspose.email.PersonalStorageLoadOptions-}
```
public static PersonalStorage fromFile(String fileName, PersonalStorageLoadOptions loadOptions)
```


Загрузить PST из файла.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла .pst. |
| loadOptions | [PersonalStorageLoadOptions](../../com.aspose.email/personalstorageloadoptions) | Параметры загрузки. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### fromStream(System.IO.Stream stream) {#fromStream-com.aspose.ms.System.IO.Stream-}
```
public static PersonalStorage fromStream(System.IO.Stream stream)
```


Загрузить PST из потока.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | Объект System.IO.Stream. |

--------------------

По умолчанию pst будет поддерживать запись. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### fromStream(System.IO.Stream stream, boolean writable) {#fromStream-com.aspose.ms.System.IO.Stream-boolean-}
```
public static PersonalStorage fromStream(System.IO.Stream stream, boolean writable)
```


Загрузить PST из потока.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Объект System.IO.Stream. |
| writable | boolean | Если установить значение  true , то файл pst будет поддерживать запись, иначе он откроется в режиме только для чтения. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### fromStream(System.IO.Stream stream, PersonalStorageLoadOptions loadOptions) {#fromStream-com.aspose.ms.System.IO.Stream-com.aspose.email.PersonalStorageLoadOptions-}
```
public static PersonalStorage fromStream(System.IO.Stream stream, PersonalStorageLoadOptions loadOptions)
```


Загрузить PST из потока.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Объект System.IO.Stream. |
| loadOptions | [PersonalStorageLoadOptions](../../com.aspose.email/personalstorageloadoptions) | Параметры загрузки. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static PersonalStorage fromStream(InputStream stream)
```


Загрузить PST из потока.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
|  | stream | java.io.InputStream | Объект System.IO.Stream. |

--------------------

По умолчанию pst будет поддерживать запись. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### fromStream(InputStream stream, boolean writable) {#fromStream-java.io.InputStream-boolean-}
```
public static PersonalStorage fromStream(InputStream stream, boolean writable)
```


Загрузить PST из потока.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Объект System.IO.Stream. |
| writable | boolean | Если установить значение  true , то файл pst будет поддерживать запись, иначе он откроется в режиме только для чтения. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### fromStream(InputStream stream, PersonalStorageLoadOptions loadOptions) {#fromStream-java.io.InputStream-com.aspose.email.PersonalStorageLoadOptions-}
```
public static PersonalStorage fromStream(InputStream stream, PersonalStorageLoadOptions loadOptions)
```


Загрузить PST из потока.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Объект System.IO.Stream. |
| loadOptions | [PersonalStorageLoadOptions](../../com.aspose.email/personalstorageloadoptions) | Параметры загрузки. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A PersonalStorage object that represents the current PST.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFolderById(byte[] entryId) {#getFolderById-byte---}
```
public final FolderInfo getFolderById(byte[] entryId)
```


Получает личную папку из PST.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| entryId | byte[] | Идентификатор записи. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - A FolderInfo object.
### getFolderById(String entryIdString) {#getFolderById-java.lang.String-}
```
public final FolderInfo getFolderById(String entryIdString)
```


Получает личную папку из PST.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| entryIdString | java.lang.String | Строковое представление идентификатора записи. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - A FolderInfo object.
### getFormat() {#getFormat--}
```
public final int getFormat()
```


Получает формат файла.

Значение: [FileFormat](../../com.aspose.email/fileformat), указывающий формат файла.

--------------------

Форматы файлов .pst и .ost теперь поддерживаются.

**Returns:**
int
### getParentFolder(byte[] entryId) {#getParentFolder-byte---}
```
public final FolderInfo getParentFolder(byte[] entryId)
```


Получает родительскую папку сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| entryId | byte[] | Идентификатор записи сообщения или папки. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The parent folder[FolderInfo](../../com.aspose.email/folderinfo) of message.
### getParentFolder(String entryIdString) {#getParentFolder-java.lang.String-}
```
public final FolderInfo getParentFolder(String entryIdString)
```


Получает родительскую папку сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| entryIdString | java.lang.String | Строковое представление идентификатора записи сообщения или папки. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The parent folder[FolderInfo](../../com.aspose.email/folderinfo) of message.
### getPredefinedFolder(int defaultFolder) {#getPredefinedFolder-int-}
```
public final FolderInfo getPredefinedFolder(int defaultFolder)
```


Получает стандартную папку межличностных сообщений (IPM) из PST. Outlook может создавать несколько папок по умолчанию, таких как Исходящие, Удалённые элементы, Отправленные элементы и т.д.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| defaultFolder | int | Значение перечисления [StandardIpmFolder](../../com.aspose.email/standardipmfolder). |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - A [FolderInfo](../../com.aspose.email/folderinfo) object that represents a standard IPM folder.
### getRootFolder() {#getRootFolder--}
```
public final FolderInfo getRootFolder()
```


Получает корневую папку PST.

Значение: [FolderInfo](../../com.aspose.email/folderinfo), представляющий корневую папку.

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo)
### getStore() {#getStore--}
```
public final MessageStore getStore()
```


Получает хранилище сообщений PST.

Значение: [MessageStore](../../com.aspose.email/messagestore), который примерно соответствует верхней части почтового ящика.

**Returns:**
[MessageStore](../../com.aspose.email/messagestore)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isUnicode() {#isUnicode--}
```
public final boolean isUnicode()
```


Возвращает значение, указывающее, является ли формат файла PST Unicode. Существует две версии формата PST: Unicode и ANSI.

**Returns:**
boolean
### load(System.IO.Stream stream) {#load-com.aspose.ms.System.IO.Stream-}
```
public final boolean load(System.IO.Stream stream)
```


Загружает PST из потока. Этот метод используется, когда объект PersonalStorage создаётся с помощью конструктора.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Объект System.IO.Stream. |

**Returns:**
boolean
### load(InputStream stream) {#load-java.io.InputStream-}
```
public final boolean load(InputStream stream)
```


Загружает PST из потока. Этот метод используется, когда объект PersonalStorage создаётся с помощью конструктора.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Объект System.IO.Stream. |

**Returns:**
boolean — 'true', если файл был успешно загружен и дальнейшее обход возможен; иначе — false.
### load(String fileName) {#load-java.lang.String-}
```
public final boolean load(String fileName)
```


Загрузить PST из файла. Этот метод используется, когда объект PersonalStorage создаётся с помощью конструктора.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла .pst. |

**Returns:**
boolean — 'true', если файл был успешно загружен и дальнейшее обход возможен; иначе — false.
### mergeWith(InputStream[] sourceStreams) {#mergeWith-java.io.InputStream---}
```
public final void mergeWith(InputStream[] sourceStreams)
```


Объединяет хранилище pst с одним или несколькими другими pst‑потоками. Таким образом, объединённые потоки являются источниками.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| sourceStreams | java.io.InputStream[] | Исходные потоки. |

### mergeWith(String[] sourceFileNames) {#mergeWith-java.lang.String---}
```
public final void mergeWith(String[] sourceFileNames)
```


Объединяет хранилище pst с одним или несколькими другими pst‑файлами. Таким образом, объединённые файлы являются источниками.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| sourceFileNames | java.lang.String[] | Имена исходных файлов. |

### moveItem(FolderInfo folder, FolderInfo newFolder) {#moveItem-com.aspose.email.FolderInfo-com.aspose.email.FolderInfo-}
```
public final void moveItem(FolderInfo folder, FolderInfo newFolder)
```


Перемещает указанную папку в новую родительскую папку внутри текущего pst.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| folder | [FolderInfo](../../com.aspose.email/folderinfo) | Папка для перемещения. |
| newFolder | [FolderInfo](../../com.aspose.email/folderinfo) | Новая родительская папка. |

### moveItem(MessageInfo message, FolderInfo newFolder) {#moveItem-com.aspose.email.MessageInfo-com.aspose.email.FolderInfo-}
```
public final void moveItem(MessageInfo message, FolderInfo newFolder)
```


Перемещает указанное сообщение в новую папку внутри текущего pst.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MessageInfo](../../com.aspose.email/messageinfo) | Сообщение для перемещения. |
| newFolder | [FolderInfo](../../com.aspose.email/folderinfo) | Новая папка для сообщения. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### saveAs(OutputStream stream, int format) {#saveAs-java.io.OutputStream-int-}
```
public final void saveAs(OutputStream stream, int format)
```


Сохраняет текущий объект в указанный формат файла в потоке.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток для сохранения. |
| format | int | Необходимо использовать [FileFormat](../../com.aspose.email/fileformat). |

### saveAs(String fileName, int format) {#saveAs-java.lang.String-int-}
```
public final void saveAs(String fileName, int format)
```


Сохраняет текущий объект в указанный формат файла в другом файле.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла для сохранения. |
| format | int | [FileFormat](../../com.aspose.email/fileformat) необходимо использовать при сохранении файла. |

### saveMessageToFile(String entryId, String fileName) {#saveMessageToFile-java.lang.String-java.lang.String-}
```
public void saveMessageToFile(String entryId, String fileName)
```


saveMessageToFile.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| entryId | java.lang.String | Объект java.lang.String. |
| fileName | java.lang.String | Объект java.lang.String. |

### saveMessageToStream(String entryId, OutputStream stream) {#saveMessageToStream-java.lang.String-java.io.OutputStream-}
```
public final void saveMessageToStream(String entryId, OutputStream stream)
```


Сохраняет сообщение с указанным entryID в поток.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| entryId | java.lang.String | Идентификатор записи. |
| stream | java.io.OutputStream | Поток для записи. |

### splitInto(System.Collections.Generic.IGenericList<MailQuery> criteria, String path) {#splitInto-com.aspose.ms.System.Collections.Generic.IGenericList-com.aspose.email.MailQuery--java.lang.String-}
```
public final void splitInto(System.Collections.Generic.IGenericList<MailQuery> criteria, String path)
```


Разделяет хранилище pst на основе критериев.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| criteria | com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.email.MailQuery> | Коллекция [MailQuery](../../com.aspose.email/mailquery), представляющая критерии разделения pst. |
| путь | java.lang.String | Путь к папке, где будут создаваться фрагменты. |

### splitInto(long chunkSize, String path) {#splitInto-long-java.lang.String-}
```
public final void splitInto(long chunkSize, String path)
```


Разделяет хранилище pst на части меньшего размера.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| chunkSize | long | Приблизительный размер фрагмента в байтах. |
| путь | java.lang.String | Путь к папке, где будут создаваться фрагменты. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryToGetFolderById(String entryIdString, FolderInfo[] folder) {#tryToGetFolderById-java.lang.String-com.aspose.email.FolderInfo---}
```
public final boolean tryToGetFolderById(String entryIdString, FolderInfo[] folder)
```


Получает папку, связанную с указанным entry ID.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| entryIdString | java.lang.String | Строка, представляющая идентификатор записи. |
| folder | [FolderInfo\[\]](../../com.aspose.email/folderinfo) | Когда этот метод возвращает true, содержит объект [FolderInfo](../../com.aspose.email/folderinfo), связанный с указанным идентификатором. |

**Returns:**
boolean — true, если папка успешно найдена; иначе false.
### tryToSaveMessage(String entryId, OutputStream stream) {#tryToSaveMessage-java.lang.String-java.io.OutputStream-}
```
public final SaveResult tryToSaveMessage(String entryId, OutputStream stream)
```


Сохраняет сообщение с указанным entryID в поток.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| entryId | java.lang.String | Идентификатор записи. |
| stream | java.io.OutputStream | Поток для записи. |

**Returns:**
[SaveResult](../../com.aspose.email/saveresult) - The [SaveResult](../../com.aspose.email/saveresult) that represents the result of item saving.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

