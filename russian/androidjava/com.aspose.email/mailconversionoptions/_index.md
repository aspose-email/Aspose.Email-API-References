---
title: MailConversionOptions
second_title: Aspose.Email for Android via Java API Reference
description: Укажите дополнительные параметры при преобразовании из MapiMessage в MailMessage.
type: docs
weight: 190
url: /ru/androidjava/com.aspose.email/mailconversionoptions/
---

**Inheritance:**
java.lang.Object
```
public class MailConversionOptions
```

Укажите дополнительные параметры при преобразовании из MapiMessage в MailMessage.
## Constructors

| Constructor | Описание |
| --- | --- |
| [MailConversionOptions()](#MailConversionOptions--) |  |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getConvertAsTnef()](#getConvertAsTnef--) | Установите в true, чтобы импортировать информацию MapiMessage в объект MailMessage с MapiMessage в виде вложения TNEF. |
| [getKeepOriginalEmailAddresses()](#getKeepOriginalEmailAddresses--) | Получает или задает значение, указывающее, нужно ли сохранять оригинальный адрес электронной почты. |
| [getPreserveEmbeddedMessageFormat()](#getPreserveEmbeddedMessageFormat--) | Получает или задает значение, указывающее, необходимо ли сохранять формат MSG вложенного сообщения при преобразовании в MailMessage. |
| [getPreserveRtfContent()](#getPreserveRtfContent--) | Получает или задает значение, указывающее, нужно ли сохранять тело в формате RTF в MailMessage. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setConvertAsTnef(boolean value)](#setConvertAsTnef-boolean-) | Установите в true, чтобы импортировать информацию MapiMessage в объект MailMessage с MapiMessage в виде вложения TNEF. |
| [setKeepOriginalEmailAddresses(boolean value)](#setKeepOriginalEmailAddresses-boolean-) | Получает или задает значение, указывающее, нужно ли сохранять оригинальный адрес электронной почты. |
| [setPreserveEmbeddedMessageFormat(boolean value)](#setPreserveEmbeddedMessageFormat-boolean-) | Получает или задает значение, указывающее, необходимо ли сохранять формат MSG вложенного сообщения при преобразовании в MailMessage. |
| [setPreserveRtfContent(boolean value)](#setPreserveRtfContent-boolean-) | Получает или задает значение, указывающее, нужно ли сохранять тело в формате RTF в MailMessage. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailConversionOptions() {#MailConversionOptions--}
```
public MailConversionOptions()
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
### getConvertAsTnef() {#getConvertAsTnef--}
```
public final boolean getConvertAsTnef()
```


Установите в true, чтобы импортировать информацию MapiMessage в объект MailMessage с MapiMessage в виде вложения TNEF.

**Returns:**
boolean
### getKeepOriginalEmailAddresses() {#getKeepOriginalEmailAddresses--}
```
public final boolean getKeepOriginalEmailAddresses()
```


Получает или задает значение, указывающее, нужно ли сохранять оригинальный адрес электронной почты.

**Returns:**
boolean
### getPreserveEmbeddedMessageFormat() {#getPreserveEmbeddedMessageFormat--}
```
public final boolean getPreserveEmbeddedMessageFormat()
```


Получает или задает значение, указывающее, необходимо ли сохранять формат MSG вложенного сообщения при преобразовании в MailMessage. По умолчанию значение равно false.

--------------------

Как правило, встроенные сообщения имеют тот же формат (EML или MSG), что и исходное сообщение. По умолчанию при конвертации из MSG в EML и обратно встроенные сообщения также преобразуются в целевой формат. Установка свойства в true сохраняет оригинальный формат встроенных сообщений.

**Returns:**
boolean
### getPreserveRtfContent() {#getPreserveRtfContent--}
```
public final boolean getPreserveRtfContent()
```


Получает или задает значение, указывающее, нужно ли сохранять тело в формате RTF в MailMessage.

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




### setConvertAsTnef(boolean value) {#setConvertAsTnef-boolean-}
```
public final void setConvertAsTnef(boolean value)
```


Установите в true, чтобы импортировать информацию MapiMessage в объект MailMessage с MapiMessage в виде вложения TNEF.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setKeepOriginalEmailAddresses(boolean value) {#setKeepOriginalEmailAddresses-boolean-}
```
public final void setKeepOriginalEmailAddresses(boolean value)
```


Получает или задает значение, указывающее, нужно ли сохранять оригинальный адрес электронной почты.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setPreserveEmbeddedMessageFormat(boolean value) {#setPreserveEmbeddedMessageFormat-boolean-}
```
public final void setPreserveEmbeddedMessageFormat(boolean value)
```


Получает или задает значение, указывающее, необходимо ли сохранять формат MSG вложенного сообщения при преобразовании в MailMessage. По умолчанию значение равно false.

--------------------

Как правило, встроенные сообщения имеют тот же формат (EML или MSG), что и исходное сообщение. По умолчанию при конвертации из MSG в EML и обратно встроенные сообщения также преобразуются в целевой формат. Установка свойства в true сохраняет оригинальный формат встроенных сообщений.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setPreserveRtfContent(boolean value) {#setPreserveRtfContent-boolean-}
```
public final void setPreserveRtfContent(boolean value)
```


Получает или задает значение, указывающее, нужно ли сохранять тело в формате RTF в MailMessage.

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

