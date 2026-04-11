---
title: NotesStorageFacility
second_title: Aspose.Email for Android via Java API Reference
description: Файл базы данных NSF Notes Storage Facility используется IBM Lotus Notes и Domino для хранения различных объектов, таких как электронная почта, встречи и документы, а также формы приложений и представления.
type: docs
weight: 331
url: /ru/androidjava/com.aspose.email/notesstoragefacility/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class NotesStorageFacility implements System.IDisposable, Closeable
```

Файл базы данных Notes Storage Facility (NSF) используется (IBM) Lotus Notes и Domino для хранения различных объектов, таких как электронная почта, встречи и документы, а также форм приложений и представлений.
## Constructors

| Constructor | Описание |
| --- | --- |
| [NotesStorageFacility(String fileName)](#NotesStorageFacility-java.lang.String-) | Инициализирует новый экземпляр класса [NotesStorageFacility](../../com.aspose.email/notesstoragefacility). |
| [NotesStorageFacility(InputStream stream)](#NotesStorageFacility-java.io.InputStream-) | Инициализирует новый экземпляр класса [NotesStorageFacility](../../com.aspose.email/notesstoragefacility). |
| [NotesStorageFacility(String fileName, NsfLoadOptions options)](#NotesStorageFacility-java.lang.String-com.aspose.email.NsfLoadOptions-) | Инициализирует новый экземпляр класса [NotesStorageFacility](../../com.aspose.email/notesstoragefacility). |
| [NotesStorageFacility(InputStream stream, NsfLoadOptions options)](#NotesStorageFacility-java.io.InputStream-com.aspose.email.NsfLoadOptions-) | Инициализирует новый экземпляр класса [NotesStorageFacility](../../com.aspose.email/notesstoragefacility). |
## Methods

| Method | Описание |
| --- | --- |
| [close()](#close--) |  |
| [dispose()](#dispose--) | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [enumerateMessages()](#enumerateMessages--) | Предоставляет перечислитель, поддерживающий перебор сообщений в хранилище. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NotesStorageFacility(String fileName) {#NotesStorageFacility-java.lang.String-}
```
public NotesStorageFacility(String fileName)
```


Инициализирует новый экземпляр класса [NotesStorageFacility](../../com.aspose.email/notesstoragefacility).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |

### NotesStorageFacility(InputStream stream) {#NotesStorageFacility-java.io.InputStream-}
```
public NotesStorageFacility(InputStream stream)
```


Инициализирует новый экземпляр класса [NotesStorageFacility](../../com.aspose.email/notesstoragefacility).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток. |

### NotesStorageFacility(String fileName, NsfLoadOptions options) {#NotesStorageFacility-java.lang.String-com.aspose.email.NsfLoadOptions-}
```
public NotesStorageFacility(String fileName, NsfLoadOptions options)
```


Инициализирует новый экземпляр класса [NotesStorageFacility](../../com.aspose.email/notesstoragefacility).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |
| options | [NsfLoadOptions](../../com.aspose.email/nsfloadoptions) | Дополнительные параметры загрузки. |

### NotesStorageFacility(InputStream stream, NsfLoadOptions options) {#NotesStorageFacility-java.io.InputStream-com.aspose.email.NsfLoadOptions-}
```
public NotesStorageFacility(InputStream stream, NsfLoadOptions options)
```


Инициализирует новый экземпляр класса [NotesStorageFacility](../../com.aspose.email/notesstoragefacility).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток. |
| options | [NsfLoadOptions](../../com.aspose.email/nsfloadoptions) | Дополнительные параметры загрузки. |

### close() {#close--}
```
public void close()
```




### dispose() {#dispose--}
```
public final void dispose()
```


Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов.

### enumerateMessages() {#enumerateMessages--}
```
public final System.Collections.Generic.IGenericEnumerable<MailMessage> enumerateMessages()
```


Предоставляет перечислитель, поддерживающий перебор сообщений в хранилище.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MailMessage> -  System.Collections.Generic.IEnumerableltTgt , который представляет перечислитель, перебирающий сообщения в хранилище.
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

