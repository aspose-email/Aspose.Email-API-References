---
title: EmlxLoadOptions
second_title: Aspose.Email for Android via Java API Reference
description: Позволяет указать дополнительные параметры при загрузке MailMessage из формата Eml.
type: docs
weight: 122
url: /ru/androidjava/com.aspose.email/emlxloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.LoadOptions](../../com.aspose.email/loadoptions)
```
public class EmlxLoadOptions extends LoadOptions
```

Позволяет указать дополнительные параметры при загрузке MailMessage из формата Eml.
## Constructors

| Constructor | Описание |
| --- | --- |
| [EmlxLoadOptions()](#EmlxLoadOptions--) | Инициализирует новый экземпляр этого класса, который может использоваться для загрузки MailMessage из формата Eml. |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMessageFormat()](#getMessageFormat--) | Представляет формат почтового сообщения. Он может быть в формате eml, msg или mhtml. |
| [getPreferredTextEncoding()](#getPreferredTextEncoding--) | Получает или задаёт предпочтительную кодировку для сообщения. |
| [getPrefferedTextEncoding()](#getPrefferedTextEncoding--) | Получает или задаёт предпочтительную кодировку для сообщения. |
| [getPreserveEmbeddedMessageFormat()](#getPreserveEmbeddedMessageFormat--) | Получает или задаёт значение, указывающее, необходимо ли сохранять формат вложенного сообщения при загрузке. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPreferredTextEncoding(Charset value)](#setPreferredTextEncoding-java.nio.charset.Charset-) | Получает или задаёт предпочтительную кодировку для сообщения. |
| [setPrefferedTextEncoding(Charset value)](#setPrefferedTextEncoding-java.nio.charset.Charset-) | Получает или задаёт предпочтительную кодировку для сообщения. |
| [setPreserveEmbeddedMessageFormat(boolean value)](#setPreserveEmbeddedMessageFormat-boolean-) | Получает или задаёт значение, указывающее, необходимо ли сохранять формат вложенного сообщения при загрузке. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EmlxLoadOptions() {#EmlxLoadOptions--}
```
public EmlxLoadOptions()
```


Инициализирует новый экземпляр этого класса, который может использоваться для загрузки MailMessage из формата Eml.

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
### getMessageFormat() {#getMessageFormat--}
```
public final MessageFormat getMessageFormat()
```


Представляет формат почтового сообщения. Может быть в формате eml, msg или mhtml. Значение по умолчанию — Eml.

**Returns:**
[MessageFormat](../../com.aspose.email/messageformat)
### getPreferredTextEncoding() {#getPreferredTextEncoding--}
```
public final Charset getPreferredTextEncoding()
```


Получает или задаёт предпочтительную кодировку для сообщения. Принудительно задаёт предпочтительную кодировку для темы и тела сообщения. Значение по умолчанию — null.

**Returns:**
java.nio.charset.Charset
### getPrefferedTextEncoding() {#getPrefferedTextEncoding--}
```
public final Charset getPrefferedTextEncoding()
```


Получает или задаёт предпочтительную кодировку для сообщения. Принудительно задаёт предпочтительную кодировку для темы и тела сообщения. Значение по умолчанию — null.

**Returns:**
java.nio.charset.Charset
### getPreserveEmbeddedMessageFormat() {#getPreserveEmbeddedMessageFormat--}
```
public final boolean getPreserveEmbeddedMessageFormat()
```


Получает или задаёт значение, указывающее, необходимо ли сохранять формат вложенного сообщения при загрузке. По умолчанию значение — false.

--------------------

Как правило, вложенные сообщения имеют тот же формат (EML или MSG), что и исходное сообщение. По умолчанию при конвертации из EML в MSG и наоборот вложенные сообщения также преобразуются в целевой формат. Установка свойства в true сохраняет оригинальный формат вложенных сообщений.

**Returns:**
boolean
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




### setPreferredTextEncoding(Charset value) {#setPreferredTextEncoding-java.nio.charset.Charset-}
```
public final void setPreferredTextEncoding(Charset value)
```


Получает или задаёт предпочтительную кодировку для сообщения. Принудительно задаёт предпочтительную кодировку для темы и тела сообщения. Значение по умолчанию — null.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setPrefferedTextEncoding(Charset value) {#setPrefferedTextEncoding-java.nio.charset.Charset-}
```
public final void setPrefferedTextEncoding(Charset value)
```


Получает или задаёт предпочтительную кодировку для сообщения. Принудительно задаёт предпочтительную кодировку для темы и тела сообщения. Значение по умолчанию — null.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setPreserveEmbeddedMessageFormat(boolean value) {#setPreserveEmbeddedMessageFormat-boolean-}
```
public final void setPreserveEmbeddedMessageFormat(boolean value)
```


Получает или задаёт значение, указывающее, необходимо ли сохранять формат вложенного сообщения при загрузке. По умолчанию значение — false.

--------------------

Как правило, вложенные сообщения имеют тот же формат (EML или MSG), что и исходное сообщение. По умолчанию при конвертации из EML в MSG и наоборот вложенные сообщения также преобразуются в целевой формат. Установка свойства в true сохраняет оригинальный формат вложенных сообщений.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

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

