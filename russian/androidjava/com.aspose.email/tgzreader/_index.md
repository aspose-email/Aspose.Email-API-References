---
title: TgzReader
second_title: Aspose.Email for Android via Java API Reference
description: Читатель элементов почтового ящика хранилища Zimbra tgz.
type: docs
weight: 402
url: /ru/androidjava/com.aspose.email/tgzreader/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class TgzReader implements System.IDisposable, Closeable
```

Читатель элементов почтового ящика хранилища Zimbra tgz.
## Constructors

| Constructor | Описание |
| --- | --- |
| [TgzReader(String fileName)](#TgzReader-java.lang.String-) | Инициализирует новый экземпляр класса [TgzReader](../../com.aspose.email/tgzreader). |
## Methods

| Method | Описание |
| --- | --- |
| [close()](#close--) |  |
| [dispose()](#dispose--) | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportTo(String path)](#exportTo-java.lang.String-) | Сохраняет сообщения и структуру каталогов, используя указанный путь. |
| [getClass()](#getClass--) |  |
| [getCurrentDirectory()](#getCurrentDirectory--) | Получает имя текущего каталога. |
| [getCurrentMessage()](#getCurrentMessage--) | Получает текущее сообщение. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readNextMessage()](#readNextMessage--) | Читает следующее сообщение. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TgzReader(String fileName) {#TgzReader-java.lang.String-}
```
public TgzReader(String fileName)
```


Инициализирует новый экземпляр класса [TgzReader](../../com.aspose.email/tgzreader).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |

### close() {#close--}
```
public void close()
```




### dispose() {#dispose--}
```
public final void dispose()
```


Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов.

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
### exportTo(String path) {#exportTo-java.lang.String-}
```
public final void exportTo(String path)
```


Сохраняет сообщения и структуру каталогов, используя указанный путь.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| путь | java.lang.String | Основной путь каталога для сохранения структуры хранилища. |

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCurrentDirectory() {#getCurrentDirectory--}
```
public final String getCurrentDirectory()
```


Получает имя текущего каталога.

Значение: имя каталога.

**Returns:**
java.lang.String
### getCurrentMessage() {#getCurrentMessage--}
```
public final MailMessage getCurrentMessage()
```


Получает текущее сообщение.

Значение: [MailMessage](../../com.aspose.email/mailmessage).

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage)
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




### readNextMessage() {#readNextMessage--}
```
public final boolean readNextMessage()
```


Читает следующее сообщение.

**Returns:**
boolean -
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

