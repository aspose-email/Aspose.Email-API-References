---
title: MhtSaveOptions
second_title: Aspose.Email for Android via Java API Reference
description: Позволяет указать дополнительные параметры при сохранении MailMessage в формат Mhtml.
type: docs
weight: 321
url: /ru/androidjava/com.aspose.email/mhtsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.SaveOptions](../../com.aspose.email/saveoptions), [com.aspose.email.HeadersFormattingOptions](../../com.aspose.email/headersformattingoptions)
```
public class MhtSaveOptions extends HeadersFormattingOptions
```

Позволяет указать дополнительные параметры при сохранении MailMessage в формат Mhtml.
## Constructors

| Constructor | Описание |
| --- | --- |
| [MhtSaveOptions()](#MhtSaveOptions--) | Инициализирует новый экземпляр этого класса, который можно использовать для сохранения MailMessage в формате Mhtml. |
## Methods

| Method | Описание |
| --- | --- |
| [createSaveOptions(MailMessageSaveType saveType)](#createSaveOptions-com.aspose.email.MailMessageSaveType-) | Создаёт объект параметров сохранения класса, подходящего для указанного типа сохранения. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAfterHeadersFormat()](#getAfterHeadersFormat--) | После формата заголовков. |
| [getBeforeHeadersFormat()](#getBeforeHeadersFormat--) | Перед форматом заголовков. |
| [getCheckBodyContentEncoding()](#getCheckBodyContentEncoding--) | Определяет, необходимо ли проверять кодировку содержимого тела сообщения при сохранении. |
| [getClass()](#getClass--) |  |
| [getCssStyles()](#getCssStyles--) | Получает или задаёт дополнительные CSS‑стили для форматировщика. |
| [getCustomProgressHandler()](#getCustomProgressHandler--) | Представляет метод, обычно предоставляемый вызывающей стороной и обрабатывающий события прогресса. |
| [getDefaultEml()](#getDefaultEml--) | Получает параметры со значениями по умолчанию для сохранения сообщения в формат Eml. |
| [getDefaultHeaderFormat()](#getDefaultHeaderFormat--) | Формат строки заголовка по умолчанию. |
| [getDefaultHtml()](#getDefaultHtml--) | Получает параметры со значениями по умолчанию для сохранения сообщения в формат Html. |
| [getDefaultMhtml()](#getDefaultMhtml--) | Получает параметры со значениями по умолчанию для сохранения сообщения в формат Mhtml. |
| [getDefaultMsg()](#getDefaultMsg--) | Получает параметры со значениями по умолчанию для сохранения сообщения в формат Msg(ASCII). |
| [getDefaultMsgUnicode()](#getDefaultMsgUnicode--) | Получает параметры со значениями по умолчанию для сохранения сообщения в формат Msg(Unicode). |
| [getDefaultPageHeaderFormat()](#getDefaultPageHeaderFormat--) | Формат заголовка страницы по умолчанию. |
| [getFormatTemplates()](#getFormatTemplates--) | Получает шаблоны формата. |
| [getMailMessageSaveType()](#getMailMessageSaveType--) | Представляет тип сохранения почтового сообщения. Он может быть в формате eml, msg (ASCII или Unicode), mhtml или html. |
| [getMhtFormatOptions()](#getMhtFormatOptions--) | Определяет дополнительные параметры при сохранении в формате MHTML. |
| [getPreserveOriginalBoundaries()](#getPreserveOriginalBoundaries--) | Определяет, нужно ли сохранять оригинальные границы в почтовом сообщении при сохранении или нет. |
| [getPreserveOriginalDate()](#getPreserveOriginalDate--) | Определяет, нужно ли сохранять оригинальную дату в почтовом сообщении при сохранении или нет. |
| [getRenderedContactFields()](#getRenderedContactFields--) | Определяет группы полей Contact, которые будут включены в выходной mhtml. |
| [getRenderingHeaders()](#getRenderingHeaders--) | Получает список заголовков для рендеринга. |
| [getSaveAttachments()](#getSaveAttachments--) | Получает или задает значение, указывающее, сохранять ли вложения. |
| [getSkipInlineImages()](#getSkipInlineImages--) | Определяет, следует ли пропускать ссылки на изображения при сохранении в mhtml, или нет. |
| [getTimeout()](#getTimeout--) | Ограничивает время в миллисекундах форматирования сообщения при сохранении в Mht. |
| [getTimeoutReachedHandler()](#getTimeoutReachedHandler--) | Вызывается, если время ожидания истекло при сохранении в Mhtml. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAfterHeadersFormat(String value)](#setAfterHeadersFormat-java.lang.String-) | После формата заголовков. |
| [setBeforeHeadersFormat(String value)](#setBeforeHeadersFormat-java.lang.String-) | Перед форматом заголовков. |
| [setCheckBodyContentEncoding(boolean value)](#setCheckBodyContentEncoding-boolean-) | Определяет, необходимо ли проверять кодировку содержимого тела сообщения при сохранении. |
| [setCssStyles(String value)](#setCssStyles-java.lang.String-) | Получает или задаёт дополнительные CSS‑стили для форматировщика. |
| [setCustomProgressHandler(ConversionProgressEventHandler value)](#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-) | Представляет метод, обычно предоставляемый вызывающей стороной и обрабатывающий события прогресса. |
| [setDefaultHeaderFormat(String value)](#setDefaultHeaderFormat-java.lang.String-) | Формат строки заголовка по умолчанию. |
| [setDefaultPageHeaderFormat(String value)](#setDefaultPageHeaderFormat-java.lang.String-) | Формат заголовка страницы по умолчанию. |
| [setMailMessageSaveType(MailMessageSaveType value)](#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-) | Представляет тип сохранения почтового сообщения. Он может быть в формате eml, msg (ASCII или Unicode), mhtml или html. |
| [setMhtFormatOptions(int value)](#setMhtFormatOptions-int-) | Определяет дополнительные параметры при сохранении в формате MHTML. |
| [setPreserveOriginalBoundaries(boolean value)](#setPreserveOriginalBoundaries-boolean-) | Определяет, нужно ли сохранять оригинальные границы в почтовом сообщении при сохранении или нет. |
| [setPreserveOriginalDate(boolean value)](#setPreserveOriginalDate-boolean-) | Определяет, нужно ли сохранять оригинальную дату в почтовом сообщении при сохранении или нет. |
| [setRenderedContactFields(int value)](#setRenderedContactFields-int-) | Определяет группы полей Contact, которые будут включены в выходной mhtml. |
| [setSaveAttachments(boolean value)](#setSaveAttachments-boolean-) | Получает или задает значение, указывающее, сохранять ли вложения. |
| [setSkipInlineImages(boolean value)](#setSkipInlineImages-boolean-) | Определяет, следует ли пропускать ссылки на изображения при сохранении в mhtml, или нет. |
| [setTimeout(int value)](#setTimeout-int-) | Ограничивает время в миллисекундах форматирования сообщения при сохранении в Mht. |
| [setTimeoutReachedHandler(TimeoutReachedHandler value)](#setTimeoutReachedHandler-com.aspose.email.TimeoutReachedHandler-) | Вызывается, если время ожидания истекло при сохранении в Mhtml. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MhtSaveOptions() {#MhtSaveOptions--}
```
public MhtSaveOptions()
```


Инициализирует новый экземпляр этого класса, который можно использовать для сохранения MailMessage в формате Mhtml.

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
### getAfterHeadersFormat() {#getAfterHeadersFormat--}
```
public final String getAfterHeadersFormat()
```


После формата заголовков.

Значение: Стили, которые будут внедрены в результирующее тело html.

**Returns:**
java.lang.String
### getBeforeHeadersFormat() {#getBeforeHeadersFormat--}
```
public final String getBeforeHeadersFormat()
```


Перед форматом заголовков.

Значение: Стили, которые будут внедрены в результирующее тело html.

**Returns:**
java.lang.String
### getCheckBodyContentEncoding() {#getCheckBodyContentEncoding--}
```
public final boolean getCheckBodyContentEncoding()
```


Определяет, необходимо ли проверять кодировку содержимого тела сообщения при сохранении. По умолчанию значение равно false.

--------------------

Если true, будет проверяться, соответствует ли кодировка содержимого MailMessage.HtmlBody ([MailMessage.getHtmlBody](../../com.aspose.email/mailmessage\#getHtmlBody)/[MailMessage.setHtmlBody(String)](../../com.aspose.email/mailmessage\#setHtmlBody-String-)) кодировке, указанной в свойстве MailMessage.BodyEncoding ([MailMessage.getBodyEncoding](../../com.aspose.email/mailmessage\#getBodyEncoding)/[MailMessage.setBodyEncoding(Encoding)](../../com.aspose.email/mailmessage\#setBodyEncoding-Encoding-)). Если кодировка HtmlBody не совпадает со свойством BodyEncoding, свойства MailMessage.BodyEncoding ([MailMessage.getBodyEncoding](../../com.aspose.email/mailmessage\#getBodyEncoding)/[MailMessage.setBodyEncoding(Encoding)](../../com.aspose.email/mailmessage\#setBodyEncoding-Encoding-)) и MailMessage.PreferredTextEncoding ([MailMessage.getPreferredTextEncoding](../../com.aspose.email/mailmessage\#getPreferredTextEncoding)/[MailMessage.setPreferredTextEncoding(Encoding)](../../com.aspose.email/mailmessage\#setPreferredTextEncoding-Encoding-)) будут изменены на значение по умолчанию System.Text.Encoding.UTF8 (java.nio.charset.Charset\#getUTF8.getUTF8).

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCssStyles() {#getCssStyles--}
```
public final String getCssStyles()
```


Получает или задаёт дополнительные CSS‑стили для форматировщика.

Значение: Стили, которые будут внедрены в результирующее тело html.

**Returns:**
java.lang.String
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
### getDefaultHeaderFormat() {#getDefaultHeaderFormat--}
```
public final String getDefaultHeaderFormat()
```


Формат строки заголовка по умолчанию.

Значение: Стили, которые будут внедрены в результирующее тело html.

**Returns:**
java.lang.String
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
### getDefaultPageHeaderFormat() {#getDefaultPageHeaderFormat--}
```
public final String getDefaultPageHeaderFormat()
```


Формат заголовка страницы по умолчанию.

Значение: Стили, которые будут внедрены в результирующее тело html.

**Returns:**
java.lang.String
### getFormatTemplates() {#getFormatTemplates--}
```
public final System.Collections.Specialized.StringDictionary getFormatTemplates()
```


Получает шаблоны формата.

Значение: Шаблоны формата.

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringDictionary
### getMailMessageSaveType() {#getMailMessageSaveType--}
```
public final MailMessageSaveType getMailMessageSaveType()
```


Представляет тип сохранения почтового сообщения. Он может быть в формате eml, msg (ASCII или Unicode), mhtml или html. Значение по умолчанию — Eml.

**Returns:**
[MailMessageSaveType](../../com.aspose.email/mailmessagesavetype)
### getMhtFormatOptions() {#getMhtFormatOptions--}
```
public final int getMhtFormatOptions()
```


Определяет дополнительные параметры при сохранении в формате MHTML. Значение по умолчанию — MhtFormatOptions.WriteHeader | MhtFormatOptions.WriteOutlineAttachments.

**Returns:**
int
### getPreserveOriginalBoundaries() {#getPreserveOriginalBoundaries--}
```
public final boolean getPreserveOriginalBoundaries()
```


Определяет, нужно ли сохранять оригинальные границы в почтовом сообщении при сохранении или нет.

**Returns:**
boolean
### getPreserveOriginalDate() {#getPreserveOriginalDate--}
```
public final boolean getPreserveOriginalDate()
```


Определяет, нужно ли сохранять оригинальную дату в почтовом сообщении при сохранении или нет. Значение по умолчанию — true.

**Returns:**
boolean
### getRenderedContactFields() {#getRenderedContactFields--}
```
public final int getRenderedContactFields()
```


Определяет группы полей Contact, которые будут включены в выходной mhtml. Значение по умолчанию — ContactFieldsSet.AllExisting.

**Returns:**
int
### getRenderingHeaders() {#getRenderingHeaders--}
```
public final List<String> getRenderingHeaders()
```


Получает список заголовков для рендеринга.

**Returns:**
java.util.List<java.lang.String>
### getSaveAttachments() {#getSaveAttachments--}
```
public final boolean getSaveAttachments()
```


Получает или задает значение, указывающее, сохранять ли вложения.

Значение:  true  если вложения должны быть сохранены; иначе —  false .

**Returns:**
boolean
### getSkipInlineImages() {#getSkipInlineImages--}
```
public final boolean getSkipInlineImages()
```


Определяет, следует ли пропускать ссылки на изображения при сохранении в mhtml, или нет. Значение по умолчанию — false.

**Returns:**
boolean
### getTimeout() {#getTimeout--}
```
public final int getTimeout()
```


Ограничивает время в миллисекундах форматирования сообщения при сохранении в Mht. Значение по умолчанию — 3 сек.

**Returns:**
int
### getTimeoutReachedHandler() {#getTimeoutReachedHandler--}
```
public final TimeoutReachedHandler getTimeoutReachedHandler()
```


Вызывается, если время ожидания истекло при сохранении в Mhtml.

**Returns:**
[TimeoutReachedHandler](../../com.aspose.email/timeoutreachedhandler)
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




### setAfterHeadersFormat(String value) {#setAfterHeadersFormat-java.lang.String-}
```
public final void setAfterHeadersFormat(String value)
```


После формата заголовков.

Значение: Стили, которые будут внедрены в результирующее тело html.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setBeforeHeadersFormat(String value) {#setBeforeHeadersFormat-java.lang.String-}
```
public final void setBeforeHeadersFormat(String value)
```


Перед форматом заголовков.

Значение: Стили, которые будут внедрены в результирующее тело html.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setCheckBodyContentEncoding(boolean value) {#setCheckBodyContentEncoding-boolean-}
```
public final void setCheckBodyContentEncoding(boolean value)
```


Определяет, необходимо ли проверять кодировку содержимого тела сообщения при сохранении. По умолчанию значение равно false.

--------------------

Если true, будет проверяться, соответствует ли кодировка содержимого MailMessage.HtmlBody ([MailMessage.getHtmlBody](../../com.aspose.email/mailmessage\#getHtmlBody)/[MailMessage.setHtmlBody(String)](../../com.aspose.email/mailmessage\#setHtmlBody-String-)) кодировке, указанной в свойстве MailMessage.BodyEncoding ([MailMessage.getBodyEncoding](../../com.aspose.email/mailmessage\#getBodyEncoding)/[MailMessage.setBodyEncoding(Encoding)](../../com.aspose.email/mailmessage\#setBodyEncoding-Encoding-)). Если кодировка HtmlBody не совпадает со свойством BodyEncoding, свойства MailMessage.BodyEncoding ([MailMessage.getBodyEncoding](../../com.aspose.email/mailmessage\#getBodyEncoding)/[MailMessage.setBodyEncoding(Encoding)](../../com.aspose.email/mailmessage\#setBodyEncoding-Encoding-)) и MailMessage.PreferredTextEncoding ([MailMessage.getPreferredTextEncoding](../../com.aspose.email/mailmessage\#getPreferredTextEncoding)/[MailMessage.setPreferredTextEncoding(Encoding)](../../com.aspose.email/mailmessage\#setPreferredTextEncoding-Encoding-)) будут изменены на значение по умолчанию System.Text.Encoding.UTF8 (java.nio.charset.Charset\#getUTF8.getUTF8).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setCssStyles(String value) {#setCssStyles-java.lang.String-}
```
public final void setCssStyles(String value)
```


Получает или задаёт дополнительные CSS‑стили для форматировщика.

Значение: Стили, которые будут внедрены в результирующее тело html.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setCustomProgressHandler(ConversionProgressEventHandler value) {#setCustomProgressHandler-com.aspose.email.ConversionProgressEventHandler-}
```
public final void setCustomProgressHandler(ConversionProgressEventHandler value)
```


Представляет метод, обычно предоставляемый вызывающей стороной и обрабатывающий события прогресса.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [ConversionProgressEventHandler](../../com.aspose.email/conversionprogresseventhandler) |  |

### setDefaultHeaderFormat(String value) {#setDefaultHeaderFormat-java.lang.String-}
```
public final void setDefaultHeaderFormat(String value)
```


Формат строки заголовка по умолчанию.

Значение: Стили, которые будут внедрены в результирующее тело html.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setDefaultPageHeaderFormat(String value) {#setDefaultPageHeaderFormat-java.lang.String-}
```
public final void setDefaultPageHeaderFormat(String value)
```


Формат заголовка страницы по умолчанию.

Значение: Стили, которые будут внедрены в результирующее тело html.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setMailMessageSaveType(MailMessageSaveType value) {#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-}
```
public final void setMailMessageSaveType(MailMessageSaveType value)
```


Представляет тип сохранения почтового сообщения. Он может быть в формате eml, msg (ASCII или Unicode), mhtml или html. Значение по умолчанию — Eml.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MailMessageSaveType](../../com.aspose.email/mailmessagesavetype) |  |

### setMhtFormatOptions(int value) {#setMhtFormatOptions-int-}
```
public final void setMhtFormatOptions(int value)
```


Определяет дополнительные параметры при сохранении в формате MHTML. Значение по умолчанию — MhtFormatOptions.WriteHeader | MhtFormatOptions.WriteOutlineAttachments.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setPreserveOriginalBoundaries(boolean value) {#setPreserveOriginalBoundaries-boolean-}
```
public final void setPreserveOriginalBoundaries(boolean value)
```


Определяет, нужно ли сохранять оригинальные границы в почтовом сообщении при сохранении или нет.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setPreserveOriginalDate(boolean value) {#setPreserveOriginalDate-boolean-}
```
public final void setPreserveOriginalDate(boolean value)
```


Определяет, нужно ли сохранять оригинальную дату в почтовом сообщении при сохранении или нет. Значение по умолчанию — true.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setRenderedContactFields(int value) {#setRenderedContactFields-int-}
```
public final void setRenderedContactFields(int value)
```


Определяет группы полей Contact, которые будут включены в выходной mhtml. Значение по умолчанию — ContactFieldsSet.AllExisting.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setSaveAttachments(boolean value) {#setSaveAttachments-boolean-}
```
public final void setSaveAttachments(boolean value)
```


Получает или задает значение, указывающее, сохранять ли вложения.

Значение:  true  если вложения должны быть сохранены; иначе —  false .

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setSkipInlineImages(boolean value) {#setSkipInlineImages-boolean-}
```
public final void setSkipInlineImages(boolean value)
```


Определяет, следует ли пропускать ссылки на изображения при сохранении в mhtml, или нет. Значение по умолчанию — false.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setTimeout(int value) {#setTimeout-int-}
```
public final void setTimeout(int value)
```


Ограничивает время в миллисекундах форматирования сообщения при сохранении в Mht. Значение по умолчанию — 3 сек.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setTimeoutReachedHandler(TimeoutReachedHandler value) {#setTimeoutReachedHandler-com.aspose.email.TimeoutReachedHandler-}
```
public final void setTimeoutReachedHandler(TimeoutReachedHandler value)
```


Вызывается, если время ожидания истекло при сохранении в Mhtml.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [TimeoutReachedHandler](../../com.aspose.email/timeoutreachedhandler) |  |

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

