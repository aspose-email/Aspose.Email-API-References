---
title: EmlSaveOptions
second_title: Aspose.Email for Android via Java API Reference
description: Позволяет указать дополнительные параметры при сохранении MailMessage в форматы Eml и Emlx.
type: docs
weight: 118
url: /ru/androidjava/com.aspose.email/emlsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.SaveOptions](../../com.aspose.email/saveoptions)
```
public class EmlSaveOptions extends SaveOptions
```

Позволяет указать дополнительные параметры при сохранении MailMessage в форматы Eml и Emlx.
## Constructors

| Constructor | Описание |
| --- | --- |
| [EmlSaveOptions(MailMessageSaveType saveType)](#EmlSaveOptions-com.aspose.email.MailMessageSaveType-) | Инициализирует новый экземпляр этого класса, который можно использовать для сохранения MailMessage в форматах Eml и Emlx. |
## Methods

| Method | Описание |
| --- | --- |
| [createSaveOptions(MailMessageSaveType saveType)](#createSaveOptions-com.aspose.email.MailMessageSaveType-) | Создаёт объект параметров сохранения класса, подходящего для указанного типа сохранения. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCheckBodyContentEncoding()](#getCheckBodyContentEncoding--) | Определяет, необходимо ли проверять кодировку содержимого тела сообщения при сохранении. |
| [getClass()](#getClass--) |  |
| [getCustomProgressHandler()](#getCustomProgressHandler--) | Представляет метод, обычно предоставляемый вызывающей стороной и обрабатывающий события прогресса. |
| [getDefaultEml()](#getDefaultEml--) | Получает параметры со значениями по умолчанию для сохранения сообщения в формат Eml. |
| [getDefaultHtml()](#getDefaultHtml--) | Получает параметры со значениями по умолчанию для сохранения сообщения в формат Html. |
| [getDefaultMhtml()](#getDefaultMhtml--) | Получает параметры со значениями по умолчанию для сохранения сообщения в формат Mhtml. |
| [getDefaultMsg()](#getDefaultMsg--) | Получает параметры со значениями по умолчанию для сохранения сообщения в формат Msg(ASCII). |
| [getDefaultMsgUnicode()](#getDefaultMsgUnicode--) | Получает параметры со значениями по умолчанию для сохранения сообщения в формат Msg(Unicode). |
| [getFileCompatibilityMode()](#getFileCompatibilityMode--) | Определяет внутренние преобразования, которые необходимо выполнить при сохранении сообщения. |
| [getMailMessageSaveType()](#getMailMessageSaveType--) | Представляет тип сохранения почтового сообщения. Он может быть в формате eml, msg (ASCII или Unicode), mhtml или html. |
| [getPreserveEmbeddedMessageFormat()](#getPreserveEmbeddedMessageFormat--) | Получает или задает значение, указывающее, необходимо ли сохранять формат MSG вложенного сообщения при преобразовании в MailMessage. |
| [getPreserveSignedContent()](#getPreserveSignedContent--) | Получает или задает значение, указывающее, необходимо ли сохранять подписанное сообщение без изменений содержимого, чтобы обеспечить правильную структуру цифровой подписи. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCheckBodyContentEncoding(boolean value)](#setCheckBodyContentEncoding-boolean-) | Определяет, необходимо ли проверять кодировку содержимого тела сообщения при сохранении. |
| [setCustomProgressHandler(ConversionProgressEventHandler value)](#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-) | Представляет метод, обычно предоставляемый вызывающей стороной и обрабатывающий события прогресса. |
| [setFileCompatibilityMode(int value)](#setFileCompatibilityMode-int-) | Определяет внутренние преобразования, которые необходимо выполнить при сохранении сообщения. |
| [setMailMessageSaveType(MailMessageSaveType value)](#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-) | Представляет тип сохранения почтового сообщения. Он может быть в формате eml, msg (ASCII или Unicode), mhtml или html. |
| [setPreserveEmbeddedMessageFormat(boolean value)](#setPreserveEmbeddedMessageFormat-boolean-) | Получает или задает значение, указывающее, необходимо ли сохранять формат MSG вложенного сообщения при преобразовании в MailMessage. |
| [setPreserveSignedContent(boolean value)](#setPreserveSignedContent-boolean-) | Получает или задает значение, указывающее, необходимо ли сохранять подписанное сообщение без изменений содержимого, чтобы обеспечить правильную структуру цифровой подписи. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EmlSaveOptions(MailMessageSaveType saveType) {#EmlSaveOptions-com.aspose.email.MailMessageSaveType-}
```
public EmlSaveOptions(MailMessageSaveType saveType)
```


Инициализирует новый экземпляр этого класса, который можно использовать для сохранения MailMessage в форматах Eml и Emlx.

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
### getCheckBodyContentEncoding() {#getCheckBodyContentEncoding--}
```
public final boolean getCheckBodyContentEncoding()
```


Определяет, необходимо ли проверять кодировку содержимого тела сообщения при сохранении. По умолчанию значение равно false.

--------------------

Если значение true, будет проверяться, соответствует ли кодировка содержимого MailMessage.HtmlBody ([MailMessage.getHtmlBody](../../com.aspose.email/mailmessage\#getHtmlBody)/[MailMessage.setHtmlBody(String)](../../com.aspose.email/mailmessage\#setHtmlBody-String-)) кодировке, указанной в свойстве MailMessage.BodyEncoding ([MailMessage.getBodyEncoding](../../com.aspose.email/mailmessage\#getBodyEncoding)/[MailMessage.setBodyEncoding(Encoding)](../../com.aspose.email/mailmessage\#setBodyEncoding-Encoding-)). Если кодировка содержимого HtmlBody не соответствует свойству BodyEncoding, свойства MailMessage.BodyEncoding ([MailMessage.getBodyEncoding](../../com.aspose.email/mailmessage\#getBodyEncoding)/[MailMessage.setBodyEncoding(Encoding)](../../com.aspose.email/mailmessage\#setBodyEncoding-Encoding-)) и MailMessage.PreferredTextEncoding ([MailMessage.getPreferredTextEncoding](../../com.aspose.email/mailmessage\#getPreferredTextEncoding)/[MailMessage.setPreferredTextEncoding(Encoding)](../../com.aspose.email/mailmessage\#setPreferredTextEncoding-Encoding-)) будут изменены на значение по умолчанию System.Text.Encoding.UTF8 (java.nio.charset.Charset\#getUTF8.getUTF8).

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
### getFileCompatibilityMode() {#getFileCompatibilityMode--}
```
public final int getFileCompatibilityMode()
```


Определяет внутренние преобразования, которые необходимо выполнять при сохранении сообщения. Значение по умолчанию — FileCompatibilityMode.None.

**Returns:**
int
### getMailMessageSaveType() {#getMailMessageSaveType--}
```
public final MailMessageSaveType getMailMessageSaveType()
```


Представляет тип сохранения почтового сообщения. Он может быть в формате eml, msg (ASCII или Unicode), mhtml или html. Значение по умолчанию — Eml.

**Returns:**
[MailMessageSaveType](../../com.aspose.email/mailmessagesavetype)
### getPreserveEmbeddedMessageFormat() {#getPreserveEmbeddedMessageFormat--}
```
public final boolean getPreserveEmbeddedMessageFormat()
```


Получает или задает значение, указывающее, необходимо ли сохранять формат MSG вложенного сообщения при преобразовании в MailMessage. По умолчанию значение равно false.

--------------------

Как правило, вложенные сообщения имеют тот же формат (EML или MSG), что и исходное сообщение. По умолчанию при преобразовании из MSG в EML и наоборот вложенные сообщения также преобразуются в целевой формат. Установка свойства в true сохраняет оригинальный формат вложенных сообщений.

**Returns:**
boolean
### getPreserveSignedContent() {#getPreserveSignedContent--}
```
public final boolean getPreserveSignedContent()
```


Получает или задает значение, указывающее, необходимо ли сохранять подписанное сообщение без изменений содержимого, чтобы обеспечить правильную структуру цифровой подписи. По умолчанию значение равно false.

--------------------

Это свойство имеет смысл только для подписанных сообщений; оно не влияет на неподписанные сообщения. Свойство предназначено для некоторых сложных подписанных сообщений с отдельной подписью, созданных другими клиентами, различия в реализации которых мешают Aspose.Email точно воспроизводить их генерацию MIME‑содержимого. Сохранение таких сообщений без использования PreserveSignedContent приведёт к ошибке подписи в сохранённых сообщениях. Некоторые простые сообщения и сообщения с вложенной подписью могут быть сохранены корректно без использования этого свойства.

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




### setCheckBodyContentEncoding(boolean value) {#setCheckBodyContentEncoding-boolean-}
```
public final void setCheckBodyContentEncoding(boolean value)
```


Определяет, необходимо ли проверять кодировку содержимого тела сообщения при сохранении. По умолчанию значение равно false.

--------------------

Если значение true, будет проверяться, соответствует ли кодировка содержимого MailMessage.HtmlBody ([MailMessage.getHtmlBody](../../com.aspose.email/mailmessage\#getHtmlBody)/[MailMessage.setHtmlBody(String)](../../com.aspose.email/mailmessage\#setHtmlBody-String-)) кодировке, указанной в свойстве MailMessage.BodyEncoding ([MailMessage.getBodyEncoding](../../com.aspose.email/mailmessage\#getBodyEncoding)/[MailMessage.setBodyEncoding(Encoding)](../../com.aspose.email/mailmessage\#setBodyEncoding-Encoding-)). Если кодировка содержимого HtmlBody не соответствует свойству BodyEncoding, свойства MailMessage.BodyEncoding ([MailMessage.getBodyEncoding](../../com.aspose.email/mailmessage\#getBodyEncoding)/[MailMessage.setBodyEncoding(Encoding)](../../com.aspose.email/mailmessage\#setBodyEncoding-Encoding-)) и MailMessage.PreferredTextEncoding ([MailMessage.getPreferredTextEncoding](../../com.aspose.email/mailmessage\#getPreferredTextEncoding)/[MailMessage.setPreferredTextEncoding(Encoding)](../../com.aspose.email/mailmessage\#setPreferredTextEncoding-Encoding-)) будут изменены на значение по умолчанию System.Text.Encoding.UTF8 (java.nio.charset.Charset\#getUTF8.getUTF8).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setCustomProgressHandler(ConversionProgressEventHandler value) {#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-}
```
public final void setCustomProgressHandler(ConversionProgressEventHandler value)
```


Представляет метод, обычно предоставляемый вызывающей стороной и обрабатывающий события прогресса.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [ConversionProgressEventHandler](../../com.aspose.email/conversionprogresseventhandler) |  |

### setFileCompatibilityMode(int value) {#setFileCompatibilityMode-int-}
```
public final void setFileCompatibilityMode(int value)
```


Определяет внутренние преобразования, которые необходимо выполнять при сохранении сообщения. Значение по умолчанию — FileCompatibilityMode.None.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setMailMessageSaveType(MailMessageSaveType value) {#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-}
```
public final void setMailMessageSaveType(MailMessageSaveType value)
```


Представляет тип сохранения почтового сообщения. Он может быть в формате eml, msg (ASCII или Unicode), mhtml или html. Значение по умолчанию — Eml.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MailMessageSaveType](../../com.aspose.email/mailmessagesavetype) |  |

### setPreserveEmbeddedMessageFormat(boolean value) {#setPreserveEmbeddedMessageFormat-boolean-}
```
public final void setPreserveEmbeddedMessageFormat(boolean value)
```


Получает или задает значение, указывающее, необходимо ли сохранять формат MSG вложенного сообщения при преобразовании в MailMessage. По умолчанию значение равно false.

--------------------

Как правило, вложенные сообщения имеют тот же формат (EML или MSG), что и исходное сообщение. По умолчанию при преобразовании из MSG в EML и наоборот вложенные сообщения также преобразуются в целевой формат. Установка свойства в true сохраняет оригинальный формат вложенных сообщений.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setPreserveSignedContent(boolean value) {#setPreserveSignedContent-boolean-}
```
public final void setPreserveSignedContent(boolean value)
```


Получает или задает значение, указывающее, необходимо ли сохранять подписанное сообщение без изменений содержимого, чтобы обеспечить правильную структуру цифровой подписи. По умолчанию значение равно false.

--------------------

Это свойство имеет смысл только для подписанных сообщений; оно не влияет на неподписанные сообщения. Свойство предназначено для некоторых сложных подписанных сообщений с отдельной подписью, созданных другими клиентами, различия в реализации которых мешают Aspose.Email точно воспроизводить их генерацию MIME‑содержимого. Сохранение таких сообщений без использования PreserveSignedContent приведёт к ошибке подписи в сохранённых сообщениях. Некоторые простые сообщения и сообщения с вложенной подписью могут быть сохранены корректно без использования этого свойства.

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

