---
title: OlmFolder
second_title: Aspose.Email for Android via Java API Reference
description: Представляет информацию о папке в хранилище OLM.
type: docs
weight: 337
url: /ru/androidjava/com.aspose.email/olmfolder/
---

**Inheritance:**
java.lang.Object
```
public class OlmFolder
```

Представляет информацию о папке в хранилище OLM.
## Methods

| Method | Описание |
| --- | --- |
| [enumerateMapiMessages()](#enumerateMapiMessages--) | Предоставляет перечислитель, поддерживающий итерацию сообщений в папке. |
| [enumerateMessages()](#enumerateMessages--) | Предоставляет перечислитель, поддерживающий итерацию сообщений в папке. |
| [enumerateMessages(MailQuery query)](#enumerateMessages-com.aspose.email.MailQuery-) | Предоставляет перечислитель, поддерживающий итерацию сообщений в папке. |
| [enumerateMessages(int startIndex, int count)](#enumerateMessages-int-int-) | Предоставляет перечислитель, поддерживающий итерацию сообщений в папке. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMessageCount()](#getMessageCount--) | Получает количество сообщений. |
| [getName()](#getName--) | Получает имя папки. |
| [getPath()](#getPath--) | Получает путь. |
| [getSubFolder(String subfolderName, boolean ignoreCase)](#getSubFolder-java.lang.String-boolean-) | Получает подпапку по имени. |
| [getSubFolders()](#getSubFolders--) | Получает список подпапок. |
| [hasMessages()](#hasMessages--) | Получает значение, указывающее, содержит ли текущая папка сообщения. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Возвращает String, представляющий этот экземпляр. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### enumerateMapiMessages() {#enumerateMapiMessages--}
```
public final System.Collections.Generic.IGenericEnumerable<MapiMessage> enumerateMapiMessages()
```


Предоставляет перечислитель, поддерживающий итерацию сообщений в папке.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MapiMessage> -  System.Collections.Generic.IEnumerableltTgt , который представляет перечислитель, проходящий по сообщениям в папке.
### enumerateMessages() {#enumerateMessages--}
```
public final System.Collections.Generic.IGenericEnumerable<OlmMessageInfo> enumerateMessages()
```


Предоставляет перечислитель, поддерживающий итерацию сообщений в папке.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.OlmMessageInfo> -  System.Collections.Generic.IEnumerableltTgt , который представляет перечислитель, проходящий через сообщения в папке.
### enumerateMessages(MailQuery query) {#enumerateMessages-com.aspose.email.MailQuery-}
```
public final System.Collections.Generic.IGenericEnumerable<OlmMessageInfo> enumerateMessages(MailQuery query)
```


Предоставляет перечислитель, поддерживающий итерацию сообщений в папке.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| query | [MailQuery](../../com.aspose.email/mailquery) | [MailQuery](../../com.aspose.email/mailquery), который представляет поисковый запрос. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.OlmMessageInfo> -  System.Collections.Generic.IEnumerableltTgt , который представляет перечислитель, проходящий через сообщения в папке.
### enumerateMessages(int startIndex, int count) {#enumerateMessages-int-int-}
```
public final System.Collections.Generic.IGenericEnumerable<OlmMessageInfo> enumerateMessages(int startIndex, int count)
```


Предоставляет перечислитель, поддерживающий итерацию сообщений в папке.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| startIndex | int | Индекс начального сообщения. |
|  | count | int | Количество сообщений, которые будут получены. |

--------------------

Если параметр "count" меньше 0 или больше оставшегося количества сообщений, будет возвращено оставшееся количество сообщений. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.OlmMessageInfo> -  System.Collections.Generic.IEnumerableltTgt , который представляет перечислитель, проходящий через сообщения в папке.
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
### getMessageCount() {#getMessageCount--}
```
public final int getMessageCount()
```


Получает количество сообщений.

Значение: количество сообщений.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Получает имя папки.

Значение: имя.

**Returns:**
java.lang.String
### getPath() {#getPath--}
```
public final String getPath()
```


Получает путь.

Значение: путь к папке.

**Returns:**
java.lang.String
### getSubFolder(String subfolderName, boolean ignoreCase) {#getSubFolder-java.lang.String-boolean-}
```
public final OlmFolder getSubFolder(String subfolderName, boolean ignoreCase)
```


Получает подпапку по имени.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| subfolderName | java.lang.String | Имя подпапки. |
| ignoreCase | boolean | Значение, указывающее, является ли сравниваемое имя нечувствительным к регистру. |

**Returns:**
[OlmFolder](../../com.aspose.email/olmfolder) - An OlmFolder object.
### getSubFolders() {#getSubFolders--}
```
public final List<OlmFolder> getSubFolders()
```


Получает список подпапок.

Значение: список подпапок.

**Returns:**
java.util.List<com.aspose.email.OlmFolder>
### hasMessages() {#hasMessages--}
```
public final boolean hasMessages()
```


Получает значение, указывающее, содержит ли текущая папка сообщения.

**Returns:**
boolean - true, если текущая папка содержит сообщения; иначе false.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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


Возвращает String, представляющий этот экземпляр.

**Returns:**
java.lang.String — Строка, представляющая этот экземпляр.
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

