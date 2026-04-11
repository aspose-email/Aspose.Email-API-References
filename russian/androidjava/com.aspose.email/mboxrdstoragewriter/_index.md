---
title: MboxrdStorageWriter
second_title: Aspose.Email for Android via Java API Reference
description: Представляет writer хранилища в формате mboxrd; этот формат используется Thunderbird и другими почтовыми клиентами.
type: docs
weight: 300
url: /ru/androidjava/com.aspose.email/mboxrdstoragewriter/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MboxStorageWriter](../../com.aspose.email/mboxstoragewriter)
```
public final class MboxrdStorageWriter extends MboxStorageWriter
```

Представляет писатель хранилища формата mboxrd, этот формат используется в Thunderbird и других почтовых клиентах.
## Constructors

| Constructor | Описание |
| --- | --- |
| [MboxrdStorageWriter(OutputStream stream, boolean leaveOpen)](#MboxrdStorageWriter-java.io.OutputStream-boolean-) | Инициализирует новый экземпляр класса [MboxrdStorageWriter](../../com.aspose.email/mboxrdstoragewriter). |
| [MboxrdStorageWriter(System.IO.Stream stream, boolean leaveOpen)](#MboxrdStorageWriter-com.aspose.ms.System.IO.Stream-boolean-) | Инициализирует новый экземпляр класса [MboxrdStorageWriter](../../com.aspose.email/mboxrdstoragewriter). |
| [MboxrdStorageWriter(String fileName, boolean leaveOpen)](#MboxrdStorageWriter-java.lang.String-boolean-) | Инициализирует новый экземпляр класса [MboxrdStorageWriter](../../com.aspose.email/mboxrdstoragewriter). |
| [MboxrdStorageWriter(String fileName)](#MboxrdStorageWriter-java.lang.String-) | Конструктор для MboxrdStorageWriter. |
## Methods

| Method | Описание |
| --- | --- |
| [close()](#close--) |  |
| [dispose()](#dispose--) | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | flush. |
| [getBaseStream()](#getBaseStream--) | Получает базовый поток. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeMessage(MailMessage message)](#writeMessage-com.aspose.email.MailMessage-) | Записывает сообщение во вложенный поток хранилища. |
| [writeMessage(MailMessage message, String[] fromMarker)](#writeMessage-com.aspose.email.MailMessage-java.lang.String---) | Записывает сообщение во вложенный поток хранилища. |
### MboxrdStorageWriter(OutputStream stream, boolean leaveOpen) {#MboxrdStorageWriter-java.io.OutputStream-boolean-}
```
public MboxrdStorageWriter(OutputStream stream, boolean leaveOpen)
```


Инициализирует новый экземпляр класса [MboxrdStorageWriter](../../com.aspose.email/mboxrdstoragewriter).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток. |
| leaveOpen | boolean | если установлено значение true, оставляет базовый поток открытым после освобождения. |

### MboxrdStorageWriter(System.IO.Stream stream, boolean leaveOpen) {#MboxrdStorageWriter-com.aspose.ms.System.IO.Stream-boolean-}
```
public MboxrdStorageWriter(System.IO.Stream stream, boolean leaveOpen)
```


Инициализирует новый экземпляр класса [MboxrdStorageWriter](../../com.aspose.email/mboxrdstoragewriter).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Поток. |
| leaveOpen | boolean | если установлено значение true, оставляет базовый поток открытым после освобождения. |

### MboxrdStorageWriter(String fileName, boolean leaveOpen) {#MboxrdStorageWriter-java.lang.String-boolean-}
```
public MboxrdStorageWriter(String fileName, boolean leaveOpen)
```


Инициализирует новый экземпляр класса [MboxrdStorageWriter](../../com.aspose.email/mboxrdstoragewriter).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |
| leaveOpen | boolean | если установлено значение true, оставляет базовый поток открытым после освобождения. |

### MboxrdStorageWriter(String fileName) {#MboxrdStorageWriter-java.lang.String-}
```
public MboxrdStorageWriter(String fileName)
```


Конструктор для MboxrdStorageWriter.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Объект java.lang.String. |

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
### flush() {#flush--}
```
public void flush()
```


flush.

### getBaseStream() {#getBaseStream--}
```
public InputStream getBaseStream()
```


Получает базовый поток.

Значение: Базовый поток.

**Returns:**
java.io.InputStream
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

### writeMessage(MailMessage message) {#writeMessage-com.aspose.email.MailMessage-}
```
public void writeMessage(MailMessage message)
```


Записывает сообщение во вложенный поток хранилища.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | Сообщение, в которое нужно записать. |

### writeMessage(MailMessage message, String[] fromMarker) {#writeMessage-com.aspose.email.MailMessage-java.lang.String---}
```
public void writeMessage(MailMessage message, String[] fromMarker)
```


Записывает сообщение во вложенный поток хранилища.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | Сообщение, в которое нужно записать. |
| fromMarker | java.lang.String[] | Получает маркер From при записи файла хранилища MBox. |

