---
title: MapiConversionOptions
second_title: Aspose.Email for Android via Java API Reference
description: Этот класс позволяет пользователю указать дополнительные параметры при преобразовании из MailMessage в MapiMessage.
type: docs
weight: 248
url: /ru/androidjava/com.aspose.email/mapiconversionoptions/
---

**Inheritance:**
java.lang.Object
```
public class MapiConversionOptions
```

Этот класс позволяет пользователю указать дополнительные параметры при преобразовании из MailMessage в MapiMessage.
## Constructors

| Constructor | Описание |
| --- | --- |
| [MapiConversionOptions()](#MapiConversionOptions--) | Инициализирует новый экземпляр класса [MapiConversionOptions](../../com.aspose.email/mapiconversionoptions). |
| [MapiConversionOptions(int format)](#MapiConversionOptions-int-) | Инициализирует новый экземпляр класса [MapiConversionOptions](../../com.aspose.email/mapiconversionoptions) с указанным OutlookMessageFormat. |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getASCIIFormat()](#getASCIIFormat--) | Возвращает MapiConversionOptions с OutlookMessageFormat, равным ASCII (PreserveSignature = False, UseBodyCompression = False). |
| [getClass()](#getClass--) |  |
| [getCustomProgressHandler()](#getCustomProgressHandler--) |  |
| [getForcedRtfBodyForAppointment()](#getForcedRtfBodyForAppointment--) | Получает или задает значение, указывающее, необходимо ли использовать принудительное тело RTF для встречи. |
| [getFormat()](#getFormat--) | Представляет формат сообщения Outlook. |
| [getPreserveEmbeddedMessageFormat()](#getPreserveEmbeddedMessageFormat--) | Получает или задает значение, указывающее, необходимо ли сохранять формат EML вложенного сообщения при преобразовании в MapiMessage. |
| [getPreserveEmptyDates()](#getPreserveEmptyDates--) | Получает или задает значение, указывающее, необходимо ли сохранять пустые даты при преобразовании сообщения. |
| [getPreserveOriginalAddresses()](#getPreserveOriginalAddresses--) | Получает или задает значение, указывающее, необходимо ли сохранять оригинальное значение почтовых адресов (без проверки). |
| [getPreserveOriginalDates()](#getPreserveOriginalDates--) | Получает или задает значение, указывающее, необходимо ли генерировать новые даты сохранения и изменения при преобразовании сообщения. |
| [getPreserveSignature()](#getPreserveSignature--) | Установите значение true, если подпись должна быть сохранена. |
| [getUnicodeFormat()](#getUnicodeFormat--) | Возвращает MapiConversionOptions с OutlookMessageFormat, равным Unicode (PreserveSignature = False, UseBodyCompression = False). |
| [getUseBodyCompression()](#getUseBodyCompression--) | Установите в true, если требуется сжатие тела RTF. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomProgressHandler(ConversionProgressEventHandler value)](#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-) |  |
| [setForcedRtfBodyForAppointment(boolean value)](#setForcedRtfBodyForAppointment-boolean-) | Получает или задает значение, указывающее, необходимо ли использовать принудительное тело RTF для встречи. |
| [setFormat(int value)](#setFormat-int-) | Представляет формат сообщения Outlook. |
| [setPreserveEmbeddedMessageFormat(boolean value)](#setPreserveEmbeddedMessageFormat-boolean-) | Получает или задает значение, указывающее, необходимо ли сохранять формат EML вложенного сообщения при преобразовании в MapiMessage. |
| [setPreserveEmptyDates(boolean value)](#setPreserveEmptyDates-boolean-) | Получает или задает значение, указывающее, необходимо ли сохранять пустые даты при преобразовании сообщения. |
| [setPreserveOriginalAddresses(boolean value)](#setPreserveOriginalAddresses-boolean-) | Получает или задает значение, указывающее, необходимо ли сохранять оригинальное значение почтовых адресов (без проверки). |
| [setPreserveOriginalDates(boolean value)](#setPreserveOriginalDates-boolean-) | Получает или задает значение, указывающее, необходимо ли генерировать новые даты сохранения и изменения при преобразовании сообщения. |
| [setPreserveSignature(boolean value)](#setPreserveSignature-boolean-) | Установите значение true, если подпись должна быть сохранена. |
| [setUseBodyCompression(boolean value)](#setUseBodyCompression-boolean-) | Установите в true, если требуется сжатие тела RTF. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiConversionOptions() {#MapiConversionOptions--}
```
public MapiConversionOptions()
```


Инициализирует новый экземпляр класса [MapiConversionOptions](../../com.aspose.email/mapiconversionoptions).

### MapiConversionOptions(int format) {#MapiConversionOptions-int-}
```
public MapiConversionOptions(int format)
```


Инициализирует новый экземпляр класса [MapiConversionOptions](../../com.aspose.email/mapiconversionoptions) с указанным OutlookMessageFormat.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| format | int | Формат MapiMessage [OutlookMessageFormat](../../com.aspose.email/outlookmessageformat). |

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
### getASCIIFormat() {#getASCIIFormat--}
```
public static MapiConversionOptions getASCIIFormat()
```


Возвращает MapiConversionOptions с OutlookMessageFormat, равным ASCII (PreserveSignature = False, UseBodyCompression = False).

**Returns:**
[MapiConversionOptions](../../com.aspose.email/mapiconversionoptions)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCustomProgressHandler() {#getCustomProgressHandler--}
```
public final ConversionProgressEventHandler getCustomProgressHandler()
```




**Returns:**
[ConversionProgressEventHandler](../../com.aspose.email/conversionprogresseventhandler)
### getForcedRtfBodyForAppointment() {#getForcedRtfBodyForAppointment--}
```
public final boolean getForcedRtfBodyForAppointment()
```


Получает или задает значение, указывающее, необходимо ли использовать принудительное тело RTF для встречи. Значение по умолчанию — true.

**Returns:**
boolean
### getFormat() {#getFormat--}
```
public final int getFormat()
```


Представляет формат сообщения Outlook.

**Returns:**
int
### getPreserveEmbeddedMessageFormat() {#getPreserveEmbeddedMessageFormat--}
```
public final boolean getPreserveEmbeddedMessageFormat()
```


Получает или задает значение, указывающее, необходимо ли сохранять формат EML вложенного сообщения при преобразовании в MapiMessage. По умолчанию значение — false.

--------------------

Как правило, вложенные сообщения имеют тот же формат (EML или MSG), что и исходное сообщение. По умолчанию при конвертации из EML в MSG и наоборот вложенные сообщения также преобразуются в целевой формат. Установка свойства в true сохраняет оригинальный формат вложенных сообщений.

**Returns:**
boolean
### getPreserveEmptyDates() {#getPreserveEmptyDates--}
```
public final boolean getPreserveEmptyDates()
```


Получает или задает значение, указывающее, необходимо ли сохранять пустые даты при преобразовании сообщения.

**Returns:**
boolean
### getPreserveOriginalAddresses() {#getPreserveOriginalAddresses--}
```
public final boolean getPreserveOriginalAddresses()
```


Получает или задает значение, указывающее, необходимо ли сохранять оригинальное значение почтовых адресов (без проверки).

**Returns:**
boolean
### getPreserveOriginalDates() {#getPreserveOriginalDates--}
```
public final boolean getPreserveOriginalDates()
```


Получает или задает значение, указывающее, необходимо ли генерировать новые даты сохранения и изменения при преобразовании сообщения.

**Returns:**
boolean
### getPreserveSignature() {#getPreserveSignature--}
```
public final boolean getPreserveSignature()
```


Установите значение true, если подпись должна быть сохранена.

**Returns:**
boolean
### getUnicodeFormat() {#getUnicodeFormat--}
```
public static MapiConversionOptions getUnicodeFormat()
```


Возвращает MapiConversionOptions с OutlookMessageFormat, равным Unicode (PreserveSignature = False, UseBodyCompression = False).

**Returns:**
[MapiConversionOptions](../../com.aspose.email/mapiconversionoptions)
### getUseBodyCompression() {#getUseBodyCompression--}
```
public final boolean getUseBodyCompression()
```


Установите в true, если требуется сжатие тела RTF.

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




### setCustomProgressHandler(ConversionProgressEventHandler value) {#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-}
```
public final void setCustomProgressHandler(ConversionProgressEventHandler value)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [ConversionProgressEventHandler](../../com.aspose.email/conversionprogresseventhandler) |  |

### setForcedRtfBodyForAppointment(boolean value) {#setForcedRtfBodyForAppointment-boolean-}
```
public final void setForcedRtfBodyForAppointment(boolean value)
```


Получает или задает значение, указывающее, необходимо ли использовать принудительное тело RTF для встречи. Значение по умолчанию — true.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setFormat(int value) {#setFormat-int-}
```
public final void setFormat(int value)
```


Представляет формат сообщения Outlook.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setPreserveEmbeddedMessageFormat(boolean value) {#setPreserveEmbeddedMessageFormat-boolean-}
```
public final void setPreserveEmbeddedMessageFormat(boolean value)
```


Получает или задает значение, указывающее, необходимо ли сохранять формат EML вложенного сообщения при преобразовании в MapiMessage. По умолчанию значение — false.

--------------------

Как правило, вложенные сообщения имеют тот же формат (EML или MSG), что и исходное сообщение. По умолчанию при конвертации из EML в MSG и наоборот вложенные сообщения также преобразуются в целевой формат. Установка свойства в true сохраняет оригинальный формат вложенных сообщений.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setPreserveEmptyDates(boolean value) {#setPreserveEmptyDates-boolean-}
```
public final void setPreserveEmptyDates(boolean value)
```


Получает или задает значение, указывающее, необходимо ли сохранять пустые даты при преобразовании сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setPreserveOriginalAddresses(boolean value) {#setPreserveOriginalAddresses-boolean-}
```
public final void setPreserveOriginalAddresses(boolean value)
```


Получает или задает значение, указывающее, необходимо ли сохранять оригинальное значение почтовых адресов (без проверки).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setPreserveOriginalDates(boolean value) {#setPreserveOriginalDates-boolean-}
```
public final void setPreserveOriginalDates(boolean value)
```


Получает или задает значение, указывающее, необходимо ли генерировать новые даты сохранения и изменения при преобразовании сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setPreserveSignature(boolean value) {#setPreserveSignature-boolean-}
```
public final void setPreserveSignature(boolean value)
```


Установите значение true, если подпись должна быть сохранена.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setUseBodyCompression(boolean value) {#setUseBodyCompression-boolean-}
```
public final void setUseBodyCompression(boolean value)
```


Установите в true, если требуется сжатие тела RTF.

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

