---
title: MboxrdStorageReader
second_title: Aspose.Email for Android via Java API Reference
description: Represents mboxrd format storage reader this format is being used by Thunderbird and other mail clients.
type: docs
weight: 299
url: /ru/androidjava/com.aspose.email/mboxrdstoragereader/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MboxStorageReader](../../com.aspose.email/mboxstoragereader)
```
public final class MboxrdStorageReader extends MboxStorageReader
```

Представляет читатель хранилища формата mboxrd, этот формат используется в Thunderbird и других почтовых клиентах.
## Constructors

| Constructor | Описание |
| --- | --- |
| [MboxrdStorageReader(InputStream stream, boolean leaveOpen)](#MboxrdStorageReader-java.io.InputStream-boolean-) | Инициализирует новый экземпляр класса [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader). |
| [MboxrdStorageReader(System.IO.Stream stream, boolean leaveOpen)](#MboxrdStorageReader-com.aspose.ms.System.IO.Stream-boolean-) | Инициализирует новый экземпляр класса [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader). |
| [MboxrdStorageReader(String fileName, boolean leaveOpen)](#MboxrdStorageReader-java.lang.String-boolean-) | Инициализирует новый экземпляр класса [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader). |
| [MboxrdStorageReader(InputStream stream, MboxLoadOptions options)](#MboxrdStorageReader-java.io.InputStream-com.aspose.email.MboxLoadOptions-) | Инициализирует новый экземпляр класса [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader). |
| [MboxrdStorageReader(System.IO.Stream stream, MboxLoadOptions options)](#MboxrdStorageReader-com.aspose.ms.System.IO.Stream-com.aspose.email.MboxLoadOptions-) | Инициализирует новый экземпляр класса [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader). |
| [MboxrdStorageReader(String fileName, MboxLoadOptions options)](#MboxrdStorageReader-java.lang.String-com.aspose.email.MboxLoadOptions-) | Инициализирует новый экземпляр класса [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader). |
## Methods

| Method | Описание |
| --- | --- |
| [close()](#close--) |  |
| [createReader(System.IO.Stream stream, boolean leaveOpen)](#createReader-com.aspose.ms.System.IO.Stream-boolean-) | Создает экземпляр считывателя. |
| [createReader(System.IO.Stream stream, MboxLoadOptions options)](#createReader-com.aspose.ms.System.IO.Stream-com.aspose.email.MboxLoadOptions-) | Создает экземпляр считывателя. |
| [createReader(InputStream stream, boolean leaveOpen)](#createReader-java.io.InputStream-boolean-) | Создает экземпляр считывателя. |
| [createReader(InputStream stream, MboxLoadOptions options)](#createReader-java.io.InputStream-com.aspose.email.MboxLoadOptions-) | Создает экземпляр считывателя. |
| [createReader(String fileName, boolean leaveOpen)](#createReader-java.lang.String-boolean-) | Создает экземпляр считывателя. |
| [createReader(String fileName, MboxLoadOptions options)](#createReader-java.lang.String-com.aspose.email.MboxLoadOptions-) | Создает экземпляр считывателя. |
| [dispose()](#dispose--) | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [enumerateMessages()](#enumerateMessages--) | Предоставляет перечислитель, поддерживающий перебор сообщений в хранилище. |
| [enumerateMessages(EmlLoadOptions options)](#enumerateMessages-com.aspose.email.EmlLoadOptions-) | Предоставляет перечислитель, поддерживающий перебор сообщений в хранилище. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCurrentDataSize()](#getCurrentDataSize--) | Получает количество байтов, считываемых методом ReadNextMessage. |
| [getTotalItemsCount()](#getTotalItemsCount--) | Возвращает количество сообщений в хранилище. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readNextMessage()](#readNextMessage--) | Считывает следующее сообщение из базового потока хранилища. |
| [readNextMessage(EmlLoadOptions options)](#readNextMessage-com.aspose.email.EmlLoadOptions-) | Считывает следующее сообщение из базового потока хранилища. |
| [readNextMessage(String[] fromMarker)](#readNextMessage-java.lang.String---) | Считывает следующее сообщение из базового потока хранилища. |
| [readNextMessage(String[] fromMarker, EmlLoadOptions options)](#readNextMessage-java.lang.String---com.aspose.email.EmlLoadOptions-) | Считывает следующее сообщение из базового потока хранилища. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MboxrdStorageReader(InputStream stream, boolean leaveOpen) {#MboxrdStorageReader-java.io.InputStream-boolean-}
```
public MboxrdStorageReader(InputStream stream, boolean leaveOpen)
```


Инициализирует новый экземпляр класса [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток. |
| leaveOpen | boolean | если установлено значение true, оставляет базовый поток открытым после освобождения. |

### MboxrdStorageReader(System.IO.Stream stream, boolean leaveOpen) {#MboxrdStorageReader-com.aspose.ms.System.IO.Stream-boolean-}
```
public MboxrdStorageReader(System.IO.Stream stream, boolean leaveOpen)
```


Инициализирует новый экземпляр класса [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Поток. |
| leaveOpen | boolean | если установлено значение true, оставляет базовый поток открытым после освобождения. |

### MboxrdStorageReader(String fileName, boolean leaveOpen) {#MboxrdStorageReader-java.lang.String-boolean-}
```
public MboxrdStorageReader(String fileName, boolean leaveOpen)
```


Инициализирует новый экземпляр класса [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |
| leaveOpen | boolean | если установлено значение true, оставляет базовый поток открытым после освобождения. |

### MboxrdStorageReader(InputStream stream, MboxLoadOptions options) {#MboxrdStorageReader-java.io.InputStream-com.aspose.email.MboxLoadOptions-}
```
public MboxrdStorageReader(InputStream stream, MboxLoadOptions options)
```


Инициализирует новый экземпляр класса [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток. |
| options | [MboxLoadOptions](../../com.aspose.email/mboxloadoptions) | дополнительные параметры при загрузке хранилища Mbox[MboxLoadOptions](../../com.aspose.email/mboxloadoptions). |

### MboxrdStorageReader(System.IO.Stream stream, MboxLoadOptions options) {#MboxrdStorageReader-com.aspose.ms.System.IO.Stream-com.aspose.email.MboxLoadOptions-}
```
public MboxrdStorageReader(System.IO.Stream stream, MboxLoadOptions options)
```


Инициализирует новый экземпляр класса [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Поток. |
| options | [MboxLoadOptions](../../com.aspose.email/mboxloadoptions) | дополнительные параметры при загрузке хранилища Mbox[MboxLoadOptions](../../com.aspose.email/mboxloadoptions). |

### MboxrdStorageReader(String fileName, MboxLoadOptions options) {#MboxrdStorageReader-java.lang.String-com.aspose.email.MboxLoadOptions-}
```
public MboxrdStorageReader(String fileName, MboxLoadOptions options)
```


Инициализирует новый экземпляр класса [MboxrdStorageReader](../../com.aspose.email/mboxrdstoragereader).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |
| options | [MboxLoadOptions](../../com.aspose.email/mboxloadoptions) | дополнительные параметры при загрузке хранилища Mbox[MboxLoadOptions](../../com.aspose.email/mboxloadoptions). |

### close() {#close--}
```
public void close()
```




### createReader(System.IO.Stream stream, boolean leaveOpen) {#createReader-com.aspose.ms.System.IO.Stream-boolean-}
```
public static MboxStorageReader createReader(System.IO.Stream stream, boolean leaveOpen)
```


Создает экземпляр считывателя.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Поток. |
| leaveOpen | boolean | если установлено значение true, оставляет базовый поток открытым после освобождения. |

**Returns:**
[MboxStorageReader](../../com.aspose.email/mboxstoragereader) - 
### createReader(System.IO.Stream stream, MboxLoadOptions options) {#createReader-com.aspose.ms.System.IO.Stream-com.aspose.email.MboxLoadOptions-}
```
public static MboxStorageReader createReader(System.IO.Stream stream, MboxLoadOptions options)
```


Создает экземпляр считывателя.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Поток. |
| options | [MboxLoadOptions](../../com.aspose.email/mboxloadoptions) | дополнительные параметры при загрузке хранилища Mbox[MboxLoadOptions](../../com.aspose.email/mboxloadoptions). |

**Returns:**
[MboxStorageReader](../../com.aspose.email/mboxstoragereader) - 
### createReader(InputStream stream, boolean leaveOpen) {#createReader-java.io.InputStream-boolean-}
```
public static MboxStorageReader createReader(InputStream stream, boolean leaveOpen)
```


Создает экземпляр считывателя.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток. |
| leaveOpen | boolean | если установлено значение true, оставляет базовый поток открытым после освобождения. |

**Returns:**
[MboxStorageReader](../../com.aspose.email/mboxstoragereader) - 
### createReader(InputStream stream, MboxLoadOptions options) {#createReader-java.io.InputStream-com.aspose.email.MboxLoadOptions-}
```
public static MboxStorageReader createReader(InputStream stream, MboxLoadOptions options)
```


Создает экземпляр считывателя.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток. |
| options | [MboxLoadOptions](../../com.aspose.email/mboxloadoptions) | дополнительные параметры при загрузке хранилища Mbox[MboxLoadOptions](../../com.aspose.email/mboxloadoptions). |

**Returns:**
[MboxStorageReader](../../com.aspose.email/mboxstoragereader) - 
### createReader(String fileName, boolean leaveOpen) {#createReader-java.lang.String-boolean-}
```
public static MboxStorageReader createReader(String fileName, boolean leaveOpen)
```


Создает экземпляр считывателя.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String |  |
| leaveOpen | boolean |  |

**Returns:**
[MboxStorageReader](../../com.aspose.email/mboxstoragereader) - 
### createReader(String fileName, MboxLoadOptions options) {#createReader-java.lang.String-com.aspose.email.MboxLoadOptions-}
```
public static MboxStorageReader createReader(String fileName, MboxLoadOptions options)
```


Создает экземпляр считывателя.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [MboxLoadOptions](../../com.aspose.email/mboxloadoptions) | дополнительные параметры при загрузке хранилища Mbox[MboxLoadOptions](../../com.aspose.email/mboxloadoptions). |

**Returns:**
[MboxStorageReader](../../com.aspose.email/mboxstoragereader) - 
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
### enumerateMessages(EmlLoadOptions options) {#enumerateMessages-com.aspose.email.EmlLoadOptions-}
```
public final System.Collections.Generic.IGenericEnumerable<MailMessage> enumerateMessages(EmlLoadOptions options)
```


Предоставляет перечислитель, поддерживающий перебор сообщений в хранилище.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| options | [EmlLoadOptions](../../com.aspose.email/emlloadoptions) | Указывает [EmlLoadOptions](../../com.aspose.email/emlloadoptions) при чтении сообщения из хранилища Mbox. |

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
### getCurrentDataSize() {#getCurrentDataSize--}
```
public final long getCurrentDataSize()
```


Получает количество байтов, считываемых методом ReadNextMessage.

**Returns:**
long
### getTotalItemsCount() {#getTotalItemsCount--}
```
public int getTotalItemsCount()
```


Возвращает количество сообщений в хранилище.

**Returns:**
int — возвращает количество сообщений в хранилище.
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
public MailMessage readNextMessage()
```


Считывает следующее сообщение из базового потока хранилища.

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - A [MailMessage](../../com.aspose.email/mailmessage) object if it can be read or  **null**  if no more messages are available.
### readNextMessage(EmlLoadOptions options) {#readNextMessage-com.aspose.email.EmlLoadOptions-}
```
public MailMessage readNextMessage(EmlLoadOptions options)
```


Считывает следующее сообщение из базового потока хранилища.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| options | [EmlLoadOptions](../../com.aspose.email/emlloadoptions) | Указывает [EmlLoadOptions](../../com.aspose.email/emlloadoptions) при чтении сообщения из хранилища Mbox. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - A [MailMessage](../../com.aspose.email/mailmessage) object if it can be read or  **null**  if no more messages are available.
### readNextMessage(String[] fromMarker) {#readNextMessage-java.lang.String---}
```
public MailMessage readNextMessage(String[] fromMarker)
```


Считывает следующее сообщение из базового потока хранилища.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fromMarker | java.lang.String[] | Получает маркер From при разборе файла хранилища MBox. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - A [MailMessage](../../com.aspose.email/mailmessage) object if it can be read or  **null**  if no more messages are available.
### readNextMessage(String[] fromMarker, EmlLoadOptions options) {#readNextMessage-java.lang.String---com.aspose.email.EmlLoadOptions-}
```
public MailMessage readNextMessage(String[] fromMarker, EmlLoadOptions options)
```


Считывает следующее сообщение из базового потока хранилища.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fromMarker | java.lang.String[] | Получает маркер From при разборе файла хранилища MBox. |
| options | [EmlLoadOptions](../../com.aspose.email/emlloadoptions) | Указывает [EmlLoadOptions](../../com.aspose.email/emlloadoptions) при чтении сообщения из хранилища Mbox. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - A [MailMessage](../../com.aspose.email/mailmessage) object if it can be read or  **null**  if no more messages are available.
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

