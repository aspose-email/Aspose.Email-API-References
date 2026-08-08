---
title: SaveOptions
second_title: Aspose.Email for Android via Java API Reference
description: Это абстрактный базовый класс для классов, позволяющих пользователю указывать дополнительные параметры при сохранении MailMessage в определённый формат.
type: docs
weight: 378
url: /ru/androidjava/com.aspose.email/saveoptions/
---

**Inheritance:**
java.lang.Object
```
public abstract class SaveOptions
```

Это абстрактный базовый класс для классов, позволяющих пользователю указывать дополнительные параметры при сохранении MailMessage в определённый формат.
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
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomProgressHandler(ConversionProgressEventHandler value)](#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-) | Представляет метод, обычно предоставляемый вызывающей стороной и обрабатывающий события прогресса. |
| [setMailMessageSaveType(MailMessageSaveType value)](#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-) | Представляет тип сохранения почтового сообщения. Он может быть в формате eml, msg (ASCII или Unicode), mhtml или html. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

