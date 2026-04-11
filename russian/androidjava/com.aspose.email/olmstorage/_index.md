---
title: OlmStorage
second_title: Aspose.Email for Android via Java API Reference
description: Представляет хранилище Outlook для Mac, файл .OLM.
type: docs
weight: 339
url: /ru/androidjava/com.aspose.email/olmstorage/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class OlmStorage implements System.IDisposable, Closeable
```

Представляет файл хранилища Outlook for Mac (.OLM).
## Constructors

| Constructor | Описание |
| --- | --- |
| [OlmStorage(TraversalExceptionsCallback callback)](#OlmStorage-com.aspose.email.TraversalExceptionsCallback-) | Инициализирует новый экземпляр класса [OlmStorage](../../com.aspose.email/olmstorage). |
| [OlmStorage(String fileName)](#OlmStorage-java.lang.String-) | Инициализирует новый экземпляр класса [OlmStorage](../../com.aspose.email/olmstorage). |
| [OlmStorage(InputStream stream)](#OlmStorage-java.io.InputStream-) | Инициализирует новый экземпляр класса [OlmStorage](../../com.aspose.email/olmstorage). |
## Methods

| Method | Описание |
| --- | --- |
| [close()](#close--) |  |
| [dispose()](#dispose--) | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [enumerateMessages(OlmFolder folder)](#enumerateMessages-com.aspose.email.OlmFolder-) | Предоставляет перечислитель, поддерживающий итерацию сообщений в папке. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractMapiMessage(OlmMessageInfo messageInfo)](#extractMapiMessage-com.aspose.email.OlmMessageInfo-) | Получить сообщение из хранилища OLM. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | Загрузить хранилище OLM из файла. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Загрузить OLM из потока. |
| [getClass()](#getClass--) |  |
| [getFolder(String name, boolean ignoreCase)](#getFolder-java.lang.String-boolean-) | Получает папку по имени. |
| [getFolderHierarchy()](#getFolderHierarchy--) | Получает иерархию папок. |
| [getFolders()](#getFolders--) | Получает коллекцию папок. |
| [hashCode()](#hashCode--) |  |
| [load(InputStream stream)](#load-java.io.InputStream-) | Загрузить хранилище OLM из потока. |
| [load(String fileName)](#load-java.lang.String-) | Загрузить хранилище OLM из файла. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OlmStorage(TraversalExceptionsCallback callback) {#OlmStorage-com.aspose.email.TraversalExceptionsCallback-}
```
public OlmStorage(TraversalExceptionsCallback callback)
```


Инициализирует новый экземпляр класса [OlmStorage](../../com.aspose.email/olmstorage). Позволяет установить метод обратного вызова для обработки исключений, возникающих во время обхода хранилища OLM.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| callback | [TraversalExceptionsCallback](../../com.aspose.email/traversalexceptionscallback) | Обратный вызов исключения. |

### OlmStorage(String fileName) {#OlmStorage-java.lang.String-}
```
public OlmStorage(String fileName)
```


Инициализирует новый экземпляр класса [OlmStorage](../../com.aspose.email/olmstorage).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла OLM. |

### OlmStorage(InputStream stream) {#OlmStorage-java.io.InputStream-}
```
public OlmStorage(InputStream stream)
```


Инициализирует новый экземпляр класса [OlmStorage](../../com.aspose.email/olmstorage).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Исходный поток java.io.InputStream с данными хранилища OLM. |

### close() {#close--}
```
public void close()
```




### dispose() {#dispose--}
```
public final void dispose()
```


Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов.

### enumerateMessages(OlmFolder folder) {#enumerateMessages-com.aspose.email.OlmFolder-}
```
public final System.Collections.Generic.IGenericEnumerable<MapiMessage> enumerateMessages(OlmFolder folder)
```


Предоставляет перечислитель, поддерживающий итерацию сообщений в папке.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| folder | [OlmFolder](../../com.aspose.email/olmfolder) | [OlmFolder](../../com.aspose.email/olmfolder), представляющий информацию о папке в хранилище OLM. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MapiMessage> -  System.Collections.Generic.IEnumerableltTgt , который представляет перечислитель, проходящий по сообщениям в папке.
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
### extractMapiMessage(OlmMessageInfo messageInfo) {#extractMapiMessage-com.aspose.email.OlmMessageInfo-}
```
public final MapiMessage extractMapiMessage(OlmMessageInfo messageInfo)
```


Получить сообщение из хранилища OLM.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| messageInfo | [OlmMessageInfo](../../com.aspose.email/olmmessageinfo) | Объект OlmMessageInfo, представляющий информацию о сообщении. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - A MapiMessage object.
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static OlmStorage fromFile(String fileName)
```


Загрузить хранилище OLM из файла.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла .olm. |

**Returns:**
[OlmStorage](../../com.aspose.email/olmstorage) - An OlmStorage object that represents the current OLM file.
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static OlmStorage fromStream(InputStream stream)
```


Загрузить OLM из потока.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Объект System.IO.Stream. |

**Returns:**
[OlmStorage](../../com.aspose.email/olmstorage) - An OlmStorage object that represents the current OLM storage.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFolder(String name, boolean ignoreCase) {#getFolder-java.lang.String-boolean-}
```
public final OlmFolder getFolder(String name, boolean ignoreCase)
```


Получает папку по имени.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя папки. |
| ignoreCase | boolean | Значение, указывающее, является ли сравниваемое имя нечувствительным к регистру. |

**Returns:**
[OlmFolder](../../com.aspose.email/olmfolder) - An OlmFolder object.
### getFolderHierarchy() {#getFolderHierarchy--}
```
public final List<OlmFolder> getFolderHierarchy()
```


Получает иерархию папок.

Значение: Иерархия папок.

**Returns:**
java.util.List<com.aspose.email.OlmFolder>
### getFolders() {#getFolders--}
```
public final List<OlmFolder> getFolders()
```


Получает коллекцию папок.

**Returns:**
java.util.List<com.aspose.email.OlmFolder> — Коллекция папок, принадлежащих хранилищу, т.е. подпапок текущего объекта OLMStorage.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### load(InputStream stream) {#load-java.io.InputStream-}
```
public final boolean load(InputStream stream)
```


Загрузить хранилище OLM из потока. Этот метод используется, когда объект OlmStorage создаётся с помощью конструктора, принимающего параметр TraversalExceptionsCallback.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток. |

**Returns:**
boolean — 'true', если файл был успешно загружен и дальнейшее обход возможен; иначе — false.
### load(String fileName) {#load-java.lang.String-}
```
public final boolean load(String fileName)
```


Загрузить хранилище OLM из файла. Этот метод используется, когда объект OlmStorage создаётся с помощью конструктора, принимающего параметр TraversalExceptionsCallback.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |

**Returns:**
boolean — 'true', если файл был успешно загружен и дальнейшее обход возможен; иначе — false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

