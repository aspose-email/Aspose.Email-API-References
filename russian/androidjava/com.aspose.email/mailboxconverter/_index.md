---
title: MailboxConverter
second_title: Aspose.Email for Android via Java API Reference
description: Предоставляет процедуры конвертации почтового ящика.
type: docs
weight: 201
url: /ru/androidjava/com.aspose.email/mailboxconverter/
---

**Inheritance:**
java.lang.Object
```
public class MailboxConverter
```

Предоставляет процедуры конвертации почтового ящика.
## Constructors

| Constructor | Описание |
| --- | --- |
| [MailboxConverter()](#MailboxConverter--) |  |
## Methods

| Method | Описание |
| --- | --- |
| [convertPersonalStorageToMbox(PersonalStorage personalStorage, MboxStorageWriter mboxStorageWriter, MessageAcceptanceCallback acceptanceCallback)](#convertPersonalStorageToMbox-com.aspose.email.PersonalStorage-com.aspose.email.MboxStorageWriter-com.aspose.email.MessageAcceptanceCallback-) | Преобразует [PersonalStorage](../../com.aspose.email/personalstorage) в формат mbox, используя указанный [MboxStorageWriter](../../com.aspose.email/mboxstoragewriter). |
| [convertPersonalStorageToMbox(PersonalStorage personalStorage, String storagePath, MessageAcceptanceCallback acceptanceCallback)](#convertPersonalStorageToMbox-com.aspose.email.PersonalStorage-java.lang.String-com.aspose.email.MessageAcceptanceCallback-) | Преобразует [PersonalStorage](../../com.aspose.email/personalstorage) в формат mbox, используя указанный путь. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailboxConverter() {#MailboxConverter--}
```
public MailboxConverter()
```


### convertPersonalStorageToMbox(PersonalStorage personalStorage, MboxStorageWriter mboxStorageWriter, MessageAcceptanceCallback acceptanceCallback) {#convertPersonalStorageToMbox-com.aspose.email.PersonalStorage-com.aspose.email.MboxStorageWriter-com.aspose.email.MessageAcceptanceCallback-}
```
public static void convertPersonalStorageToMbox(PersonalStorage personalStorage, MboxStorageWriter mboxStorageWriter, MessageAcceptanceCallback acceptanceCallback)
```


Преобразует [PersonalStorage](../../com.aspose.email/personalstorage) в формат mbox, используя указанный [MboxStorageWriter](../../com.aspose.email/mboxstoragewriter).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| personalStorage | [PersonalStorage](../../com.aspose.email/personalstorage) | Персональное хранилище. |
| mboxStorageWriter | [MboxStorageWriter](../../com.aspose.email/mboxstoragewriter) | Записыватель mbox-хранилища. |
|  | acceptanceCallback | [MessageAcceptanceCallback](../../com.aspose.email/messageacceptancecallback) | Коллбэк подтверждения, может быть null. |

--------------------

Получившееся mbox-хранилище будет содержать только одну обычную папку входящих со всеми сообщениями; если необходимо сохранить оригинальную структуру хранилища, используйте метод XXX\_method вместо этого. |

### convertPersonalStorageToMbox(PersonalStorage personalStorage, String storagePath, MessageAcceptanceCallback acceptanceCallback) {#convertPersonalStorageToMbox-com.aspose.email.PersonalStorage-java.lang.String-com.aspose.email.MessageAcceptanceCallback-}
```
public static void convertPersonalStorageToMbox(PersonalStorage personalStorage, String storagePath, MessageAcceptanceCallback acceptanceCallback)
```


Преобразует [PersonalStorage](../../com.aspose.email/personalstorage) в формат mbox, используя указанный путь.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| personalStorage | [PersonalStorage](../../com.aspose.email/personalstorage) | Персональное хранилище. |
| storagePath | java.lang.String | Путь для сохранения структуры personalStorage. |
|  | acceptanceCallback | [MessageAcceptanceCallback](../../com.aspose.email/messageacceptancecallback) | Коллбэк подтверждения, может быть null. |

--------------------

Получившаяся папка будет содержать точную копию personalStorage, например, дерево каталогов будет воссоздано на диске. |

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

