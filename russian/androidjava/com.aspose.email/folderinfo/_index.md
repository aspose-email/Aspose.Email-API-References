---
title: FolderInfo
second_title: Aspose.Email for Android via Java API Reference
description: Представляет информацию о личной папке в PST.
type: docs
weight: 141
url: /ru/androidjava/com.aspose.email/folderinfo/
---

**Inheritance:**
java.lang.Object
```
public final class FolderInfo
```

Представляет информацию о личной папке в PST.
## Constructors

| Constructor | Описание |
| --- | --- |
| [FolderInfo()](#FolderInfo--) | Инициализирует новый экземпляр класса [FolderInfo](../../com.aspose.email/folderinfo). |
## Поля

| Поле | Описание |
| --- | --- |
| [ItemMoved](#ItemMoved) | Происходит, когда элемент перемещён в другую папку. |
| [MessageAdded](#MessageAdded) | Происходит, когда сообщение добавляется в текущую папку. |
## Methods

| Method | Описание |
| --- | --- |
| [addFile(String fileName, String messageClass)](#addFile-java.lang.String-java.lang.String-) | Добавляет файл в папку pst. |
| [addMapiMessageItem(IMapiMessageItem item)](#addMapiMessageItem-com.aspose.email.IMapiMessageItem-) | Добавляет объект IMapiMessageItem в папку. |
| [addMessage(MapiMessage message)](#addMessage-com.aspose.email.MapiMessage-) | Добавляет новое сообщение в папку. |
| [addMessages(Iterable<MapiMessage> messages)](#addMessages-java.lang.Iterable-com.aspose.email.MapiMessage--) | Обеспечивает добавление сообщений в пакетном режиме. |
| [addSubFolder(String name)](#addSubFolder-java.lang.String-) | Добавляет новую подпапку. |
| [addSubFolder(String name, boolean createHierarchy)](#addSubFolder-java.lang.String-boolean-) | Добавляет новую подпапку. |
| [addSubFolder(String name, String containerClass)](#addSubFolder-java.lang.String-java.lang.String-) | Добавляет новую подпапку. |
| [changeContainerClass(String containerClass)](#changeContainerClass-java.lang.String-) | Изменяет класс контейнера. |
| [changeDisplayName(String newName)](#changeDisplayName-java.lang.String-) | Изменяет отображаемое имя. |
| [changeMessages(MapiPropertyCollection updatedProperties)](#changeMessages-com.aspose.email.MapiPropertyCollection-) | Изменяет все сообщения в папке. |
| [changeMessages(Iterable<String> entryIdCollection, MapiPropertyCollection updatedProperties)](#changeMessages-java.lang.Iterable-java.lang.String--com.aspose.email.MapiPropertyCollection-) | Изменяет сообщения в папке. |
| [deleteChildItem(byte[] entryId)](#deleteChildItem-byte---) | Удаляет элемент (папку или сообщение) по его entryId. |
| [deleteChildItems(Iterable<String> entryIdCollection)](#deleteChildItems-java.lang.Iterable-java.lang.String--) | Удаляет дочерние сообщения. |
| [enumerateFolders()](#enumerateFolders--) | Предоставляет перечислитель, который поддерживает итерацию подпапок в папке. |
| [enumerateFolders(int kind)](#enumerateFolders-int-) | Предоставляет перечислитель, который поддерживает итерацию подпапок в папке. |
| [enumerateMapiMessages()](#enumerateMapiMessages--) | Предоставляет перечислитель, поддерживающий итерацию сообщений в папке. |
| [enumerateMessageObjects()](#enumerateMessageObjects--) | Предоставляет перечислитель, поддерживающий итерацию сообщений в папке. |
| [enumerateMessages()](#enumerateMessages--) | Предоставляет перечислитель, поддерживающий итерацию сообщений в папке. |
| [enumerateMessagesEntryId()](#enumerateMessagesEntryId--) | Перечисляет entryID сообщений. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContainerClass()](#getContainerClass--) | Получает класс контейнера объекта папки. |
| [getContentCount()](#getContentCount--) | Получает общее количество элементов в папке. |
| [getContentUnreadCount()](#getContentUnreadCount--) | Получает количество непрочитанных элементов в папке. |
|  | [getContents()](#getContents--) | Получить коллекцию сообщений. |
Метод используется для отображения краткой информации о сообщении [MessageInfo](../../com.aspose.email/messageinfo), такой как тема, отправитель, получатели. |
|  | [getContents(boolean tryToReadCorruptedContents)](#getContents-boolean-) | Получить коллекцию сообщений. |
Метод используется для отображения краткой информации о сообщении [MessageInfo](../../com.aspose.email/messageinfo), такой как тема, отправитель, получатели. |
|  | [getContents(MailQuery query)](#getContents-com.aspose.email.MailQuery-) | Получить коллекцию сообщений. |
Метод используется для отображения краткой информации о сообщении [MessageInfo](../../com.aspose.email/messageinfo), такой как тема, отправитель, получатели. |
|  | [getContents(int kind)](#getContents-int-) | Получить коллекцию сообщений. |
Метод используется для отображения краткой информации о сообщении [MessageInfo](../../com.aspose.email/messageinfo), такой как тема, отправитель, получатели. |
|  | [getContents(int startIndex, int count)](#getContents-int-int-) | Получает коллекцию сообщений. |
Метод используется для отображения краткой информации о сообщении [MessageInfo](../../com.aspose.email/messageinfo), такой как тема, отправитель, получатели. |
| [getDisplayName()](#getDisplayName--) | Получает отображаемое имя папки. |
| [getEntryId()](#getEntryId--) | Gets the entry ID. |
| [getEntryIdString()](#getEntryIdString--) | Gets string representation of entry ID. |
| [getLastModificationTime()](#getLastModificationTime--) | Получает время последнего изменения. |
| [getProperties()](#getProperties--) | Получает свойства папки. |
| [getSubFolder(String name)](#getSubFolder-java.lang.String-) | Получить подпапку. |
| [getSubFolder(String name, boolean ignoreCase)](#getSubFolder-java.lang.String-boolean-) | Получает подпапку. |
| [getSubFolders()](#getSubFolders--) | Получает коллекцию подпапок. |
| [getSubFolders(MailQuery query)](#getSubFolders-com.aspose.email.MailQuery-) | Получает коллекцию подпапок. |
| [getSubFolders(int kind)](#getSubFolders-int-) | Получает коллекцию подпапок. |
| [hasSubFolders()](#hasSubFolders--) | Получает значение, указывающее, имеет ли объект Folder какие-либо подпапки. |
| [hashCode()](#hashCode--) |  |
| [mergeWith(FolderInfo sourceFolder)](#mergeWith-com.aspose.email.FolderInfo-) | Объединяет папку с папкой из другого pst. |
| [mergeWith(FolderInfo sourceFolder, boolean recursiveHandler)](#mergeWith-com.aspose.email.FolderInfo-boolean-) | Объединяет папку с папкой из другого pst. |
| [moveContents(FolderInfo newFolder)](#moveContents-com.aspose.email.FolderInfo-) | Перемещает содержимое в новую папку. |
| [moveSubfolders(FolderInfo newFolder)](#moveSubfolders-com.aspose.email.FolderInfo-) | Перемещает подпапки в новую родительскую папку. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [retrieveFullPath()](#retrieveFullPath--) | Получает полный путь к папке внутри файла PST. |
| [toString()](#toString--) |  |
| [updateMessage(String entryId, MapiMessageItemBase updatedMessage)](#updateMessage-java.lang.String-com.aspose.email.MapiMessageItemBase-) | Обновляет сообщение в папке. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FolderInfo() {#FolderInfo--}
```
public FolderInfo()
```


Инициализирует новый экземпляр класса [FolderInfo](../../com.aspose.email/folderinfo).

### ItemMoved {#ItemMoved}
```
public Event<ItemMovedEventHandler> ItemMoved
```


Происходит, когда элемент перемещён в другую папку.

### MessageAdded {#MessageAdded}
```
public final Event<MessageAddedEventHandler> MessageAdded
```


Происходит, когда сообщение добавляется в текущую папку.

### addFile(String fileName, String messageClass) {#addFile-java.lang.String-java.lang.String-}
```
public final String addFile(String fileName, String messageClass)
```


Добавляет файл в папку pst.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла, необходимого для добавления. |
| messageClass | java.lang.String | Класс сообщения. |

**Returns:**
java.lang.String — строка, представляющая EntryId добавленного сообщения.
### addMapiMessageItem(IMapiMessageItem item) {#addMapiMessageItem-com.aspose.email.IMapiMessageItem-}
```
public final String addMapiMessageItem(IMapiMessageItem item)
```


Добавляет объект IMapiMessageItem в папку.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| item | [IMapiMessageItem](../../com.aspose.email/imapimessageitem) | Элемент, необходимый для добавления. |

**Returns:**
java.lang.String — строка, представляющая EntryId добавленного элемента.
### addMessage(MapiMessage message) {#addMessage-com.aspose.email.MapiMessage-}
```
public final String addMessage(MapiMessage message)
```


Добавляет новое сообщение в папку.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | Сообщение, необходимое для добавления. |

**Returns:**
java.lang.String — строка, представляющая EntryId добавленного сообщения.
### addMessages(Iterable<MapiMessage> messages) {#addMessages-java.lang.Iterable-com.aspose.email.MapiMessage--}
```
public final void addMessages(Iterable<MapiMessage> messages)
```


Обеспечивает добавление сообщений в пакетном режиме.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| messages | java.lang.Iterable<com.aspose.email.MapiMessage> | IEnumerator, представляющий перечислитель, который поддерживает итерацию по коллекции [MapiMessage](../../com.aspose.email/mapimessage). |

### addSubFolder(String name) {#addSubFolder-java.lang.String-}
```
public final FolderInfo addSubFolder(String name)
```


Добавляет новую подпапку.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя подпапки. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The new sub-folder.
### addSubFolder(String name, boolean createHierarchy) {#addSubFolder-java.lang.String-boolean-}
```
public final FolderInfo addSubFolder(String name, boolean createHierarchy)
```


Добавляет новую подпапку.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя подпапки. |
| createHierarchy | boolean | Если установить в  true , можно создать иерархию папок, используя строковую нотацию. Обратный слеш ('\\') используется в качестве разделителя пути. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The new sub-folder.
### addSubFolder(String name, String containerClass) {#addSubFolder-java.lang.String-java.lang.String-}
```
public final FolderInfo addSubFolder(String name, String containerClass)
```


Добавляет новую подпапку.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя подпапки. |
| containerClass | java.lang.String | Класс контейнера объекта подпапки. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The new subfolder.
### changeContainerClass(String containerClass) {#changeContainerClass-java.lang.String-}
```
public final void changeContainerClass(String containerClass)
```


Изменяет класс контейнера.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| containerClass | java.lang.String | Класс контейнера объекта папки. |

### changeDisplayName(String newName) {#changeDisplayName-java.lang.String-}
```
public final void changeDisplayName(String newName)
```


Изменяет отображаемое имя.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| newName | java.lang.String | Новое имя. |

### changeMessages(MapiPropertyCollection updatedProperties) {#changeMessages-com.aspose.email.MapiPropertyCollection-}
```
public final void changeMessages(MapiPropertyCollection updatedProperties)
```


Изменяет все сообщения в папке.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| updatedProperties | [MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) | Обновленные свойства. |

### changeMessages(Iterable<String> entryIdCollection, MapiPropertyCollection updatedProperties) {#changeMessages-java.lang.Iterable-java.lang.String--com.aspose.email.MapiPropertyCollection-}
```
public final void changeMessages(Iterable<String> entryIdCollection, MapiPropertyCollection updatedProperties)
```


Изменяет сообщения в папке.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| entryIdCollection | java.lang.Iterable<java.lang.String> | Коллекция идентификаторов записей. |
| updatedProperties | [MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) | Обновленные свойства. |

### deleteChildItem(byte[] entryId) {#deleteChildItem-byte---}
```
public final void deleteChildItem(byte[] entryId)
```


Удаляет элемент (папку или сообщение) по его entryId.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
|  | entryId | byte[] | Идентификатор записи. |

--------------------

Элемент должен находиться в папке. |

### deleteChildItems(Iterable<String> entryIdCollection) {#deleteChildItems-java.lang.Iterable-java.lang.String--}
```
public final void deleteChildItems(Iterable<String> entryIdCollection)
```


Удаляет дочерние сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| entryIdCollection | java.lang.Iterable<java.lang.String> | Коллекция идентификаторов записей. |

### enumerateFolders() {#enumerateFolders--}
```
public final System.Collections.Generic.IGenericEnumerable<FolderInfo> enumerateFolders()
```


Предоставляет перечислитель, который поддерживает итерацию подпапок в папке.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.FolderInfo> -  System.Collections.Generic.IEnumerableltTgt , который представляет перечислитель, проходящий по подпапкам в папке.
### enumerateFolders(int kind) {#enumerateFolders-int-}
```
public final System.Collections.Generic.IGenericEnumerable<FolderInfo> enumerateFolders(int kind)
```


Предоставляет перечислитель, который поддерживает итерацию подпапок в папке.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| kind | int | Тип [FolderKind](../../com.aspose.email/folderkind), который представляет тип папки. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.FolderInfo> -  System.Collections.Generic.IEnumerableltTgt , который представляет перечислитель, проходящий по подпапкам в папке.
### enumerateMapiMessages() {#enumerateMapiMessages--}
```
public final System.Collections.Generic.IGenericEnumerable<MapiMessage> enumerateMapiMessages()
```


Предоставляет перечислитель, поддерживающий итерацию сообщений в папке.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MapiMessage> -  System.Collections.Generic.IEnumerableltTgt , который представляет перечислитель, проходящий по сообщениям в папке.
### enumerateMessageObjects() {#enumerateMessageObjects--}
```
public final System.Collections.Generic.IGenericEnumerable<MessageObject> enumerateMessageObjects()
```


Предоставляет перечислитель, поддерживающий итерацию сообщений в папке.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MessageObject> -  System.Collections.Generic.IEnumerableltTgt , который представляет перечислитель, проходящий по сообщениям в папке.
### enumerateMessages() {#enumerateMessages--}
```
public final System.Collections.Generic.IGenericEnumerable<MessageInfo> enumerateMessages()
```


Предоставляет перечислитель, поддерживающий итерацию сообщений в папке.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MessageInfo> -  System.Collections.Generic.IEnumerableltTgt , который представляет перечислитель, проходящий по сообщениям в папке.
### enumerateMessagesEntryId() {#enumerateMessagesEntryId--}
```
public final System.Collections.Generic.IGenericEnumerable<String> enumerateMessagesEntryId()
```


Перечисляет entryID сообщений.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<java.lang.String> -  System.Collections.Generic.IEnumerableltTgt , который представляет перечислитель, проходящий по entryID сообщений в папке.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainerClass() {#getContainerClass--}
```
public final String getContainerClass()
```


Получает класс контейнера объекта папки.

Значение: Класс контейнера.

**Returns:**
java.lang.String
### getContentCount() {#getContentCount--}
```
public final int getContentCount()
```


Получает общее количество элементов в папке.

Значение: Количество содержимого.

**Returns:**
int
### getContentUnreadCount() {#getContentUnreadCount--}
```
public final int getContentUnreadCount()
```


Получает количество непрочитанных элементов в папке.

Значение: Количество непрочитанных элементов.

**Returns:**
int
### getContents() {#getContents--}
```
public final MessageInfoCollection getContents()
```


Получить коллекцию сообщений.
Метод используется для отображения краткой информации о сообщении [MessageInfo](../../com.aspose.email/messageinfo), такой как тема, отправитель, получатели. С точки зрения производительности это наиболее подходящий вариант для получения основной информации о сообщениях. Для извлечения полных данных сообщения предоставлен метод [PersonalStorage.extractMessage(MessageInfo)](../../com.aspose.email/personalstorage\#extractMessage-MessageInfo-).

**Returns:**
[MessageInfoCollection](../../com.aspose.email/messageinfocollection) - Collection of MessageInfo.
### getContents(boolean tryToReadCorruptedContents) {#getContents-boolean-}
```
public final MessageInfoCollection getContents(boolean tryToReadCorruptedContents)
```


Получить коллекцию сообщений.
Метод используется для отображения краткой информации о сообщении [MessageInfo](../../com.aspose.email/messageinfo), такой как тема, отправитель, получатели. С точки зрения производительности это наиболее подходящий вариант для получения основной информации о сообщениях. Для извлечения полных данных сообщения предоставлен метод [PersonalStorage.extractMessage(MessageInfo)](../../com.aspose.email/personalstorage\#extractMessage-MessageInfo-).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tryToReadCorruptedContents | boolean | Если значение этого параметра равно true, метод попытается прочитать содержимое, даже если файл повреждён. Это значение можно использовать, если метод GetContents() бросает исключение о повреждении файла. Если значение этого параметра равно false, метод работает так же, как метод GetContents() без параметров. |

**Returns:**
[MessageInfoCollection](../../com.aspose.email/messageinfocollection) - Collection of MessageInfo.
### getContents(MailQuery query) {#getContents-com.aspose.email.MailQuery-}
```
public final MessageInfoCollection getContents(MailQuery query)
```


Получить коллекцию сообщений.
Метод используется для отображения краткой информации о сообщении [MessageInfo](../../com.aspose.email/messageinfo), такой как тема, отправитель, получатели. С точки зрения производительности это наиболее подходящий вариант для получения основной информации о сообщениях. Для извлечения полных данных сообщения предоставлен метод [PersonalStorage.extractMessage(MessageInfo)](../../com.aspose.email/personalstorage\#extractMessage-MessageInfo-).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| query | [MailQuery](../../com.aspose.email/mailquery) | [MailQuery](../../com.aspose.email/mailquery), который представляет поисковый запрос. |

**Returns:**
[MessageInfoCollection](../../com.aspose.email/messageinfocollection) - Collection of MessageInfo.
### getContents(int kind) {#getContents-int-}
```
public final MessageInfoCollection getContents(int kind)
```


Получить коллекцию сообщений.
Метод используется для отображения краткой информации о сообщении [MessageInfo](../../com.aspose.email/messageinfo), такой как тема, отправитель, получатели. С точки зрения производительности это наиболее подходящий вариант для получения основной информации о сообщениях. Для извлечения полных данных сообщения предоставлен метод [PersonalStorage.extractMessage(MessageInfo)](../../com.aspose.email/personalstorage\#extractMessage-MessageInfo-).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| вид | int | Тип сообщения. |

**Returns:**
[MessageInfoCollection](../../com.aspose.email/messageinfocollection) - Collection of MessageInfo.
### getContents(int startIndex, int count) {#getContents-int-int-}
```
public final MessageInfoCollection getContents(int startIndex, int count)
```


Получает коллекцию сообщений.
Метод используется для отображения краткой информации о сообщении [MessageInfo](../../com.aspose.email/messageinfo), такой как тема, отправитель, получатели. С точки зрения производительности это наиболее подходящий вариант для получения основной информации о сообщениях. Для извлечения полных данных сообщения предоставлен метод [PersonalStorage.extractMessage(MessageInfo)](../../com.aspose.email/personalstorage\#extractMessage-MessageInfo-).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| startIndex | int | Индекс начального сообщения. |
|  | count | int | Количество сообщений, которые будут получены. |

--------------------

Если параметр "count" меньше 0 или больше оставшегося количества сообщений, будет возвращено оставшееся количество сообщений. |

**Returns:**
[MessageInfoCollection](../../com.aspose.email/messageinfocollection) - Collection of MessageInfo.
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Получает отображаемое имя папки.

Значение: Отображаемое имя.

**Returns:**
java.lang.String
### getEntryId() {#getEntryId--}
```
public final byte[] getEntryId()
```


Gets the entry ID.

Значение: Идентификатор записи.

**Returns:**
byte[]
### getEntryIdString() {#getEntryIdString--}
```
public final String getEntryIdString()
```


Gets string representation of entry ID.

Значение: Строка идентификатора записи.

**Returns:**
java.lang.String
### getLastModificationTime() {#getLastModificationTime--}
```
public final Date getLastModificationTime()
```


Получает время последнего изменения.

Значение: Время последнего изменения. Если у папки нет свойства PR\_LAST\_MODIFICATION\_TIME, возвращается DateTime.MinValue.

**Returns:**
java.util.Date
### getProperties() {#getProperties--}
```
public final MapiPropertyCollection getProperties()
```


Получает свойства папки.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getSubFolder(String name) {#getSubFolder-java.lang.String-}
```
public final FolderInfo getSubFolder(String name)
```


Получить подпапку.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя подпапки. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - A FolderInfo object.
### getSubFolder(String name, boolean ignoreCase) {#getSubFolder-java.lang.String-boolean-}
```
public final FolderInfo getSubFolder(String name, boolean ignoreCase)
```


Получает подпапку.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя подпапки. |
| ignoreCase | boolean | Указывает, что поиск должен игнорировать регистр при сопоставлении имени папки. |

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - A FolderInfo object.
### getSubFolders() {#getSubFolders--}
```
public final FolderInfoCollection getSubFolders()
```


Получает коллекцию подпапок.

**Returns:**
[FolderInfoCollection](../../com.aspose.email/folderinfocollection) - The FolderInfo collection.
### getSubFolders(MailQuery query) {#getSubFolders-com.aspose.email.MailQuery-}
```
public final FolderInfoCollection getSubFolders(MailQuery query)
```


Получает коллекцию подпапок.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| query | [MailQuery](../../com.aspose.email/mailquery) | [MailQuery](../../com.aspose.email/mailquery), который представляет поисковый запрос. |

**Returns:**
[FolderInfoCollection](../../com.aspose.email/folderinfocollection) - The FolderInfo collection.
### getSubFolders(int kind) {#getSubFolders-int-}
```
public final FolderInfoCollection getSubFolders(int kind)
```


Получает коллекцию подпапок.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| kind | int | Тип [FolderKind](../../com.aspose.email/folderkind), который представляет тип папки. |

**Returns:**
[FolderInfoCollection](../../com.aspose.email/folderinfocollection) - The FolderInfo collection.
### hasSubFolders() {#hasSubFolders--}
```
public final boolean hasSubFolders()
```


Получает значение, указывающее, имеет ли объект Folder какие-либо подпапки.

Значение: У него есть подпапки.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### mergeWith(FolderInfo sourceFolder) {#mergeWith-com.aspose.email.FolderInfo-}
```
public final void mergeWith(FolderInfo sourceFolder)
```


Объединяет папку с папкой из другого pst.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| sourceFolder | [FolderInfo](../../com.aspose.email/folderinfo) | Исходная папка. |

### mergeWith(FolderInfo sourceFolder, boolean recursiveHandler) {#mergeWith-com.aspose.email.FolderInfo-boolean-}
```
public final void mergeWith(FolderInfo sourceFolder, boolean recursiveHandler)
```


Объединяет папку с папкой из другого pst. Событие OnItemMoved вызывается как для сообщений, так и для каталогов.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| sourceFolder | [FolderInfo](../../com.aspose.email/folderinfo) | Исходная папка. |
| recursiveHandler | boolean | Если true, событие OnItemMoved будет вызываться для всех сообщений, включая сообщения в подпапках; иначе OnItemMoved будет вызываться только для сообщений в текущем каталоге. |

### moveContents(FolderInfo newFolder) {#moveContents-com.aspose.email.FolderInfo-}
```
public final void moveContents(FolderInfo newFolder)
```


Перемещает содержимое в новую папку.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| newFolder | [FolderInfo](../../com.aspose.email/folderinfo) | Новая папка. |

### moveSubfolders(FolderInfo newFolder) {#moveSubfolders-com.aspose.email.FolderInfo-}
```
public final void moveSubfolders(FolderInfo newFolder)
```


Перемещает подпапки в новую родительскую папку.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| newFolder | [FolderInfo](../../com.aspose.email/folderinfo) | Новая родительская папка. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### retrieveFullPath() {#retrieveFullPath--}
```
public final String retrieveFullPath()
```


Получает полный путь к папке внутри файла PST.

**Returns:**
java.lang.String — строка, представляющая полный путь.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateMessage(String entryId, MapiMessageItemBase updatedMessage) {#updateMessage-java.lang.String-com.aspose.email.MapiMessageItemBase-}
```
public final void updateMessage(String entryId, MapiMessageItemBase updatedMessage)
```


Обновляет сообщение в папке.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| entryId | java.lang.String | Идентификатор записи сообщения. |
| updatedMessage | [MapiMessageItemBase](../../com.aspose.email/mapimessageitembase) | Обновлённое сообщение. |

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

