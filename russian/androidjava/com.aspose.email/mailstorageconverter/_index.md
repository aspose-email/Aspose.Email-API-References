---
title: MailStorageConverter
second_title: Aspose.Email for Android via Java API Reference
description: Конвертер хранилища почты предоставляет услуги для операций конвертации хранилища.
type: docs
weight: 200
url: /ru/androidjava/com.aspose.email/mailstorageconverter/
---

**Inheritance:**
java.lang.Object
```
public class MailStorageConverter
```

Конвертер хранилища почты предоставляет услуги для операций конвертации хранилища.
## Constructors

| Constructor | Описание |
| --- | --- |
| [MailStorageConverter()](#MailStorageConverter--) |  |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMboxMessageOptions()](#getMboxMessageOptions--) | Получает или задает параметры загрузки электронной почты при разборе хранилища Mbox. |
| [hashCode()](#hashCode--) |  |
| [mboxToPst(MboxStorageReader mboxStorageReader, PersonalStorage pst, String pstFolderName, MailStorageConverter.MailHandler mailHandler)](#mboxToPst-com.aspose.email.MboxStorageReader-com.aspose.email.PersonalStorage-java.lang.String-com.aspose.email.MailStorageConverter.MailHandler-) | Преобразует хранилище Mbox в PST. |
| [mboxToPst(InputStream mboxrdDataStream, OutputStream pstDataStream)](#mboxToPst-java.io.InputStream-java.io.OutputStream-) | Преобразует хранилище Mbox в PST. |
| [mboxToPst(InputStream mboxrdDataStream, OutputStream pstDataStream, MailStorageConverter.MailHandler mailHandler)](#mboxToPst-java.io.InputStream-java.io.OutputStream-com.aspose.email.MailStorageConverter.MailHandler-) | Преобразует хранилище Mbox в PST. |
| [mboxToPst(InputStream mboxrdDataStream, String pstFileName)](#mboxToPst-java.io.InputStream-java.lang.String-) | Преобразует хранилище Mbox в PST. |
| [mboxToPst(InputStream mboxrdDataStream, String pstFileName, MailStorageConverter.MailHandler mailHandler)](#mboxToPst-java.io.InputStream-java.lang.String-com.aspose.email.MailStorageConverter.MailHandler-) | Преобразует хранилище Mbox в PST. |
| [mboxToPst(String mboxFileName, System.IO.Stream pstDataStream)](#mboxToPst-java.lang.String-com.aspose.ms.System.IO.Stream-) | Преобразует хранилище Mbox в PST. |
| [mboxToPst(String mboxFileName, System.IO.Stream pstDataStream, MailStorageConverter.MailHandler mailHandler)](#mboxToPst-java.lang.String-com.aspose.ms.System.IO.Stream-com.aspose.email.MailStorageConverter.MailHandler-) | Преобразует хранилище Mbox в PST. |
| [mboxToPst(String mboxFileName, OutputStream pstDataStream)](#mboxToPst-java.lang.String-java.io.OutputStream-) | Преобразует хранилище Mbox в PST. |
| [mboxToPst(String mboxFileName, OutputStream pstDataStream, MailStorageConverter.MailHandler mailHandler)](#mboxToPst-java.lang.String-java.io.OutputStream-com.aspose.email.MailStorageConverter.MailHandler-) | Преобразует хранилище Mbox в PST. |
| [mboxToPst(String mboxFileName, String pstFileName)](#mboxToPst-java.lang.String-java.lang.String-) | Преобразует хранилище Mbox в PST. |
| [mboxToPst(String mboxFileName, String pstFileName, MailStorageConverter.MailHandler mailHandler)](#mboxToPst-java.lang.String-java.lang.String-com.aspose.email.MailStorageConverter.MailHandler-) | Преобразует хранилище Mbox в PST. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMboxMessageOptions(EmlLoadOptions value)](#setMboxMessageOptions-com.aspose.email.EmlLoadOptions-) | Получает или задает параметры загрузки электронной почты при разборе хранилища Mbox. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailStorageConverter() {#MailStorageConverter--}
```
public MailStorageConverter()
```


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
### getMboxMessageOptions() {#getMboxMessageOptions--}
```
public static EmlLoadOptions getMboxMessageOptions()
```


Получает или задает параметры загрузки электронной почты при разборе хранилища Mbox.

Значение: [EmlLoadOptions](../../com.aspose.email/emlloadoptions), который определяет параметры загрузки.

**Returns:**
[EmlLoadOptions](../../com.aspose.email/emlloadoptions)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### mboxToPst(MboxStorageReader mboxStorageReader, PersonalStorage pst, String pstFolderName, MailStorageConverter.MailHandler mailHandler) {#mboxToPst-com.aspose.email.MboxStorageReader-com.aspose.email.PersonalStorage-java.lang.String-com.aspose.email.MailStorageConverter.MailHandler-}
```
public static void mboxToPst(MboxStorageReader mboxStorageReader, PersonalStorage pst, String pstFolderName, MailStorageConverter.MailHandler mailHandler)
```


Преобразует хранилище Mbox в PST.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| mboxStorageReader | [MboxStorageReader](../../com.aspose.email/mboxstoragereader) | Объект [MboxStorageReader](../../com.aspose.email/mboxstoragereader), представляющий читатель почтового хранилища на основе mbox. |
| pst | [PersonalStorage](../../com.aspose.email/personalstorage) | Объект [PersonalStorage](../../com.aspose.email/personalstorage), представляющий хранилище pst. |
| pstFolderName | java.lang.String | Имя папки в корне pst, в которую будут добавлены сообщения Mbox. Если эта папка не существует, она будет создана. Если папка существует и не пуста, новые сообщения будут добавлены к существующим. |
| mailHandler | [MailHandler](../../com.aspose.email/mailhandler) | Делегат [MailHandler](../../com.aspose.email/mailhandler) вызывается для каждого сообщения, считанного из Mbox. |

### mboxToPst(InputStream mboxrdDataStream, OutputStream pstDataStream) {#mboxToPst-java.io.InputStream-java.io.OutputStream-}
```
public static PersonalStorage mboxToPst(InputStream mboxrdDataStream, OutputStream pstDataStream)
```


Преобразует хранилище Mbox в PST.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| mboxrdDataStream | java.io.InputStream | Объект java.io.InputStream, представляющий данные в формате Mbox. |
| pstDataStream | java.io.OutputStream | Объект java.io.InputStream, представляющий данные в формате Pst. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(InputStream mboxrdDataStream, OutputStream pstDataStream, MailStorageConverter.MailHandler mailHandler) {#mboxToPst-java.io.InputStream-java.io.OutputStream-com.aspose.email.MailStorageConverter.MailHandler-}
```
public static PersonalStorage mboxToPst(InputStream mboxrdDataStream, OutputStream pstDataStream, MailStorageConverter.MailHandler mailHandler)
```


Преобразует хранилище Mbox в PST.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| mboxrdDataStream | java.io.InputStream | Объект java.io.InputStream, представляющий данные в формате Mbox. |
| pstDataStream | java.io.OutputStream | Объект java.io.InputStream, представляющий данные в формате Pst. |
| mailHandler | [MailHandler](../../com.aspose.email/mailhandler) | Делегат [MailHandler](../../com.aspose.email/mailhandler) вызывается для каждого сообщения, считанного из Mbox. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(InputStream mboxrdDataStream, String pstFileName) {#mboxToPst-java.io.InputStream-java.lang.String-}
```
public static PersonalStorage mboxToPst(InputStream mboxrdDataStream, String pstFileName)
```


Преобразует хранилище Mbox в PST.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| mboxrdDataStream | java.io.InputStream | Объект java.io.InputStream, представляющий данные в формате Mbox. |
|  | pstFileName | java.lang.String | Имя файла PST. |

--------------------

Кроме того, тот же набор исключений может быть выброшен, как при создании FileStream в режимах открытие/чтение, создание/запись. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(InputStream mboxrdDataStream, String pstFileName, MailStorageConverter.MailHandler mailHandler) {#mboxToPst-java.io.InputStream-java.lang.String-com.aspose.email.MailStorageConverter.MailHandler-}
```
public static PersonalStorage mboxToPst(InputStream mboxrdDataStream, String pstFileName, MailStorageConverter.MailHandler mailHandler)
```


Преобразует хранилище Mbox в PST.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| mboxrdDataStream | java.io.InputStream | Объект java.io.InputStream, представляющий данные в формате Mbox. |
| pstFileName | java.lang.String | Имя файла PST. |
|  | mailHandler | [MailHandler](../../com.aspose.email/mailhandler) | Делегат [MailHandler](../../com.aspose.email/mailhandler) вызывается для каждого сообщения, считанного из Mbox. |

--------------------

Кроме того, тот же набор исключений может быть выброшен, как при создании FileStream в режимах открытие/чтение, создание/запись. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(String mboxFileName, System.IO.Stream pstDataStream) {#mboxToPst-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public static PersonalStorage mboxToPst(String mboxFileName, System.IO.Stream pstDataStream)
```


Преобразует хранилище Mbox в PST.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| mboxFileName | java.lang.String | Имя файла Mbox. |
|  | pstDataStream | com.aspose.ms.System.IO.Stream | Объект Stream, представляющий данные в формате Pst. |

--------------------

Кроме того, тот же набор исключений может быть выброшен, как при создании FileStream в режимах открытие/чтение, создание/запись. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(String mboxFileName, System.IO.Stream pstDataStream, MailStorageConverter.MailHandler mailHandler) {#mboxToPst-java.lang.String-com.aspose.ms.System.IO.Stream-com.aspose.email.MailStorageConverter.MailHandler-}
```
public static PersonalStorage mboxToPst(String mboxFileName, System.IO.Stream pstDataStream, MailStorageConverter.MailHandler mailHandler)
```


Преобразует хранилище Mbox в PST.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| mboxFileName | java.lang.String | Имя файла Mbox. |
| pstDataStream | com.aspose.ms.System.IO.Stream | Объект Stream, представляющий данные в формате Pst. |
|  | mailHandler | [MailHandler](../../com.aspose.email/mailhandler) | Делегат [MailHandler](../../com.aspose.email/mailhandler) вызывается для каждого сообщения, считанного из Mbox. |

--------------------

Кроме того, тот же набор исключений может быть выброшен, как при создании FileStream в режимах открытие/чтение, создание/запись. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(String mboxFileName, OutputStream pstDataStream) {#mboxToPst-java.lang.String-java.io.OutputStream-}
```
public static PersonalStorage mboxToPst(String mboxFileName, OutputStream pstDataStream)
```


Преобразует хранилище Mbox в PST.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| mboxFileName | java.lang.String | Имя файла Mbox. |
|  | pstDataStream | java.io.OutputStream | Объект java.io.InputStream, представляющий данные в формате Pst. |

--------------------

Кроме того, тот же набор исключений может быть выброшен, как при создании FileStream в режимах открытие/чтение, создание/запись. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(String mboxFileName, OutputStream pstDataStream, MailStorageConverter.MailHandler mailHandler) {#mboxToPst-java.lang.String-java.io.OutputStream-com.aspose.email.MailStorageConverter.MailHandler-}
```
public static PersonalStorage mboxToPst(String mboxFileName, OutputStream pstDataStream, MailStorageConverter.MailHandler mailHandler)
```


Преобразует хранилище Mbox в PST.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| mboxFileName | java.lang.String | Имя файла Mbox. |
| pstDataStream | java.io.OutputStream | Объект java.io.InputStream, представляющий данные в формате Pst. |
|  | mailHandler | [MailHandler](../../com.aspose.email/mailhandler) | Делегат [MailHandler](../../com.aspose.email/mailhandler) вызывается для каждого сообщения, считанного из Mbox. |

--------------------

Кроме того, тот же набор исключений может быть выброшен, как при создании FileStream в режимах открытие/чтение, создание/запись. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(String mboxFileName, String pstFileName) {#mboxToPst-java.lang.String-java.lang.String-}
```
public static PersonalStorage mboxToPst(String mboxFileName, String pstFileName)
```


Преобразует хранилище Mbox в PST.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| mboxFileName | java.lang.String | Имя файла Mbox. |
|  | pstFileName | java.lang.String | Имя файла PST. |

--------------------

Кроме того, тот же набор исключений может быть выброшен, как при создании FileStream в режимах открытие/чтение, создание/запись. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(String mboxFileName, String pstFileName, MailStorageConverter.MailHandler mailHandler) {#mboxToPst-java.lang.String-java.lang.String-com.aspose.email.MailStorageConverter.MailHandler-}
```
public static PersonalStorage mboxToPst(String mboxFileName, String pstFileName, MailStorageConverter.MailHandler mailHandler)
```


Преобразует хранилище Mbox в PST.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| mboxFileName | java.lang.String | Имя файла Mbox. |
| pstFileName | java.lang.String | Имя файла PST. |
|  | mailHandler | [MailHandler](../../com.aspose.email/mailhandler) | Делегат [MailHandler](../../com.aspose.email/mailhandler) вызывается для каждого сообщения, считанного из Mbox. |

--------------------

Кроме того, тот же набор исключений может быть выброшен, как при создании FileStream в режимах открытие/чтение, создание/запись. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setMboxMessageOptions(EmlLoadOptions value) {#setMboxMessageOptions-com.aspose.email.EmlLoadOptions-}
```
public static void setMboxMessageOptions(EmlLoadOptions value)
```


Получает или задает параметры загрузки электронной почты при разборе хранилища Mbox.

Значение: [EmlLoadOptions](../../com.aspose.email/emlloadoptions), который определяет параметры загрузки.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [EmlLoadOptions](../../com.aspose.email/emlloadoptions) |  |

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

