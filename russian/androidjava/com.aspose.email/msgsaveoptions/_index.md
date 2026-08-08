---
title: MsgSaveOptions
second_title: Aspose.Email for Android via Java API Reference
description: Этот класс позволяет пользователю указывать дополнительные параметры при сохранении MailMessage в формате MsgASCII и MsgUnicode.
type: docs
weight: 327
url: /ru/androidjava/com.aspose.email/msgsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.SaveOptions](../../com.aspose.email/saveoptions)
```
public class MsgSaveOptions extends SaveOptions
```

Этот класс позволяет пользователю указать дополнительные настройки при сохранении MailMessage в форматах Msg(ASCII) и Msg(Unicode).
## Constructors

| Constructor | Описание |
| --- | --- |
| [MsgSaveOptions(MailMessageSaveType saveType)](#MsgSaveOptions-com.aspose.email.MailMessageSaveType-) | Инициализирует новый экземпляр этого класса, который может использоваться для сохранения MailMessage в формате Msg(ASCII) и Msg(Unicode). |
## Methods

| Method | Описание |
| --- | --- |
| [createSaveOptions(MailMessageSaveType saveType)](#createSaveOptions-com.aspose.email.MailMessageSaveType-) | Создаёт объект параметров сохранения класса, подходящего для указанного типа сохранения. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomProgressHandler()](#getCustomProgressHandler--) | Представляет метод, обычно предоставляемый вызывающей стороной и обрабатывающий события прогресса. |
| [getDefaultEml()](#getDefaultEml--) | Получает параметры со значениями по умолчанию для сохранения сообщения в формат Eml. |
| [getDefaultHtml()](#getDefaultHtml--) | Получает параметры со значениями по умолчанию для сохранения сообщения в формат Html. |
| [getDefaultMhtml()](#getDefaultMhtml--) | Получает параметры со значениями по умолчанию для сохранения сообщения в формат Mhtml. |
| [getDefaultMsg()](#getDefaultMsg--) | Получает параметры со значениями по умолчанию для сохранения сообщения в формат Msg(ASCII). |
| [getDefaultMsgUnicode()](#getDefaultMsgUnicode--) | Получает параметры со значениями по умолчанию для сохранения сообщения в формат Msg(Unicode). |
| [getMailMessageSaveType()](#getMailMessageSaveType--) | Представляет тип сохранения почтового сообщения. Он может быть в формате eml, msg (ASCII или Unicode), mhtml или html. |
| [getPreserveOriginalDates()](#getPreserveOriginalDates--) | Получает или задает значение, указывающее, необходимо ли генерировать новые даты сохранения и изменения при сохранении сообщения. |
| [getPreserveSignature()](#getPreserveSignature--) | Установите значение true, если подпись должна быть сохранена. |
| [getSaveAsTemplate()](#getSaveAsTemplate--) | Установите значение true, если необходимо сохранить как шаблон файла Outlook (формат OFT). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomProgressHandler(ConversionProgressEventHandler value)](#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-) | Представляет метод, обычно предоставляемый вызывающей стороной и обрабатывающий события прогресса. |
| [setMailMessageSaveType(MailMessageSaveType value)](#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-) | Представляет тип сохранения почтового сообщения. Он может быть в формате eml, msg (ASCII или Unicode), mhtml или html. |
| [setPreserveOriginalDates(boolean value)](#setPreserveOriginalDates-boolean-) | Получает или задает значение, указывающее, необходимо ли генерировать новые даты сохранения и изменения при сохранении сообщения. |
| [setPreserveSignature(boolean value)](#setPreserveSignature-boolean-) | Установите значение true, если подпись должна быть сохранена. |
| [setSaveAsTemplate(boolean value)](#setSaveAsTemplate-boolean-) | Установите значение true, если необходимо сохранить как шаблон файла Outlook (формат OFT). |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MsgSaveOptions(MailMessageSaveType saveType) {#MsgSaveOptions-com.aspose.email.MailMessageSaveType-}
```
public MsgSaveOptions(MailMessageSaveType saveType)
```


Инициализирует новый экземпляр этого класса, который может использоваться для сохранения MailMessage в формате Msg(ASCII) и Msg(Unicode).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| saveType | [MailMessageSaveType](../../com.aspose.email/mailmessagesavetype) |  |

### createSaveOptions(MailMessageSaveType saveType) {#createSaveOptions-com.aspose.email.MailMessageSaveType-}
```
public static SaveOptions createSaveOptions(MailMessageSaveType saveType)
```


Создаёт объект параметров сохранения класса, подходящего для указанного типа сохранения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| saveType | [MailMessageSaveType](../../com.aspose.email/mailmessagesavetype) | Тип сохранения MailMessageSaveType (\#getMailMessageSaveType.getMailMessageSaveType/\#setMailMessageSaveType(MailMessageSaveType).setMailMessageSaveType(MailMessageSaveType)), для которого нужно создать объект параметров сохранения. |

**Returns:**
[SaveOptions](../../com.aspose.email/saveoptions) - An object of a class that derives from [SaveOptions](../../com.aspose.email/saveoptions).
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
### getCustomProgressHandler() {#getCustomProgressHandler--}
```
public final ConversionProgressEventHandler getCustomProgressHandler()
```


Представляет метод, обычно предоставляемый вызывающей стороной и обрабатывающий события прогресса.

**Returns:**
[ConversionProgressEventHandler](../../com.aspose.email/conversionprogresseventhandler)
### getDefaultEml() {#getDefaultEml--}
```
public static EmlSaveOptions getDefaultEml()
```


Получает параметры со значениями по умолчанию для сохранения сообщения в формат Eml.

**Returns:**
[EmlSaveOptions](../../com.aspose.email/emlsaveoptions)
### getDefaultHtml() {#getDefaultHtml--}
```
public static HtmlSaveOptions getDefaultHtml()
```


Получает параметры со значениями по умолчанию для сохранения сообщения в формат Html.

**Returns:**
[HtmlSaveOptions](../../com.aspose.email/htmlsaveoptions)
### getDefaultMhtml() {#getDefaultMhtml--}
```
public static MhtSaveOptions getDefaultMhtml()
```


Получает параметры со значениями по умолчанию для сохранения сообщения в формат Mhtml.

**Returns:**
[MhtSaveOptions](../../com.aspose.email/mhtsaveoptions)
### getDefaultMsg() {#getDefaultMsg--}
```
public static MsgSaveOptions getDefaultMsg()
```


Получает параметры со значениями по умолчанию для сохранения сообщения в формат Msg(ASCII).

**Returns:**
[MsgSaveOptions](../../com.aspose.email/msgsaveoptions)
### getDefaultMsgUnicode() {#getDefaultMsgUnicode--}
```
public static MsgSaveOptions getDefaultMsgUnicode()
```


Получает параметры со значениями по умолчанию для сохранения сообщения в формат Msg(Unicode).

**Returns:**
[MsgSaveOptions](../../com.aspose.email/msgsaveoptions)
### getMailMessageSaveType() {#getMailMessageSaveType--}
```
public final MailMessageSaveType getMailMessageSaveType()
```


Представляет тип сохранения почтового сообщения. Он может быть в формате eml, msg (ASCII или Unicode), mhtml или html. Значение по умолчанию — Eml.

**Returns:**
[MailMessageSaveType](../../com.aspose.email/mailmessagesavetype)
### getPreserveOriginalDates() {#getPreserveOriginalDates--}
```
public final boolean getPreserveOriginalDates()
```


Получает или задает значение, указывающее, необходимо ли генерировать новые даты сохранения и изменения при сохранении сообщения. По умолчанию значение равно false, что означает, что даты создания и изменения будут установлены в DateTime.Now.

**Returns:**
boolean
### getPreserveSignature() {#getPreserveSignature--}
```
public final boolean getPreserveSignature()
```


Установите значение true, если подпись должна быть сохранена.

**Returns:**
boolean
### getSaveAsTemplate() {#getSaveAsTemplate--}
```
public final boolean getSaveAsTemplate()
```


Установите значение true, если необходимо сохранить как шаблон файла Outlook (формат OFT).

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


Представляет метод, обычно предоставляемый вызывающей стороной и обрабатывающий события прогресса.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [ConversionProgressEventHandler](../../com.aspose.email/conversionprogresseventhandler) |  |

### setMailMessageSaveType(MailMessageSaveType value) {#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-}
```
public final void setMailMessageSaveType(MailMessageSaveType value)
```


Представляет тип сохранения почтового сообщения. Он может быть в формате eml, msg (ASCII или Unicode), mhtml или html. Значение по умолчанию — Eml.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MailMessageSaveType](../../com.aspose.email/mailmessagesavetype) |  |

### setPreserveOriginalDates(boolean value) {#setPreserveOriginalDates-boolean-}
```
public final void setPreserveOriginalDates(boolean value)
```


Получает или задает значение, указывающее, необходимо ли генерировать новые даты сохранения и изменения при сохранении сообщения. По умолчанию значение равно false, что означает, что даты создания и изменения будут установлены в DateTime.Now.

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

### setSaveAsTemplate(boolean value) {#setSaveAsTemplate-boolean-}
```
public final void setSaveAsTemplate(boolean value)
```


Установите значение true, если необходимо сохранить как шаблон файла Outlook (формат OFT).

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

