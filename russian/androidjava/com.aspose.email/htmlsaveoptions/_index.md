---
title: HtmlSaveOptions
second_title: Aspose.Email for Android via Java API Reference
description: Позволяет указать дополнительные параметры при сохранении MailMessage в формат Html.
type: docs
weight: 161
url: /ru/androidjava/com.aspose.email/htmlsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.SaveOptions](../../com.aspose.email/saveoptions), [com.aspose.email.HeadersFormattingOptions](../../com.aspose.email/headersformattingoptions)
```
public class HtmlSaveOptions extends HeadersFormattingOptions
```

Позволяет указать дополнительные параметры при сохранении MailMessage в формат Html.
## Constructors

| Constructor | Описание |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) | Инициализирует новый экземпляр этого класса, который можно использовать для сохранения MailMessage в формате Html. |
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
| [getEmbedResources()](#getEmbedResources--) | Определяет, нужно ли встраивать ресурсы в HTML‑контент при сохранении. |
| [getFormatTemplates()](#getFormatTemplates--) | Получает шаблоны формата. |
| [getHtmlFormatOptions()](#getHtmlFormatOptions--) | Получает или задаёт дополнительные параметры при сохранении в формате HTML. |
| [getMailMessageSaveType()](#getMailMessageSaveType--) | Представляет тип сохранения почтового сообщения. Он может быть в формате eml, msg (ASCII или Unicode), mhtml или html. |
| [getRenderedContactFields()](#getRenderedContactFields--) | Определяет группы полей Contact, которые будут включены в выходной mhtml. |
| [getRenderingHeaders()](#getRenderingHeaders--) | Получает список заголовков для рендеринга. |
| [getResourceHtmlRenderingHandler()](#getResourceHtmlRenderingHandler--) | Обеспечивает настройку рендеринга ресурсов в HTML. |
| [getResourceRenderingMode()](#getResourceRenderingMode--) | Обеспечивает установку различных режимов рендеринга ресурсов в HTML. |
| [getSaveResourceHandler()](#getSaveResourceHandler--) | Этот обработчик вызывается для сохранения всех вложений сообщения, если EmbedResources равно false. |
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
| [setEmbedResources(boolean value)](#setEmbedResources-boolean-) | Определяет, нужно ли встраивать ресурсы в HTML‑контент при сохранении. |
| [setHtmlFormatOptions(int value)](#setHtmlFormatOptions-int-) | Получает или задаёт дополнительные параметры при сохранении в формате HTML. |
| [setMailMessageSaveType(MailMessageSaveType value)](#setMailMessageSaveType-com.aspose.email.MailMessageSaveType-) | Представляет тип сохранения почтового сообщения. Он может быть в формате eml, msg (ASCII или Unicode), mhtml или html. |
| [setRenderedContactFields(int value)](#setRenderedContactFields-int-) | Определяет группы полей Contact, которые будут включены в выходной mhtml. |
| [setResourceHtmlRenderingHandler(ResourceHtmlRenderingHandler value)](#setResourceHtmlRenderingHandler-com.aspose.email.ResourceHtmlRenderingHandler-) | Обеспечивает настройку рендеринга ресурсов в HTML. |
| [setResourceRenderingMode(int value)](#setResourceRenderingMode-int-) | Обеспечивает установку различных режимов рендеринга ресурсов в HTML. |
| [setSaveResourceHandler(SaveResourceHandler value)](#setSaveResourceHandler-com.aspose.email.SaveResourceHandler-) | Этот обработчик вызывается для сохранения всех вложений сообщения, если EmbedResources равно false. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HtmlSaveOptions() {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```


Инициализирует новый экземпляр этого класса, который можно использовать для сохранения MailMessage в формате Html.

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
### getEmbedResources() {#getEmbedResources--}
```
public final boolean getEmbedResources()
```


Определяет, нужно ли встраивать ресурсы в html‑контент при сохранении. Значение по умолчанию — true.

**Returns:**
boolean
### getFormatTemplates() {#getFormatTemplates--}
```
public final System.Collections.Specialized.StringDictionary getFormatTemplates()
```


Получает шаблоны формата.

Значение: Шаблоны формата.

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringDictionary
### getHtmlFormatOptions() {#getHtmlFormatOptions--}
```
public final int getHtmlFormatOptions()
```


Получает или задает дополнительные параметры при сохранении в формате HTML. Значение по умолчанию — HtmlFormatOptions.None.

**Returns:**
int
### getMailMessageSaveType() {#getMailMessageSaveType--}
```
public final MailMessageSaveType getMailMessageSaveType()
```


Представляет тип сохранения почтового сообщения. Он может быть в формате eml, msg (ASCII или Unicode), mhtml или html. Значение по умолчанию — Eml.

**Returns:**
[MailMessageSaveType](../../com.aspose.email/mailmessagesavetype)
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
### getResourceHtmlRenderingHandler() {#getResourceHtmlRenderingHandler--}
```
public final ResourceHtmlRenderingHandler getResourceHtmlRenderingHandler()
```


Обеспечивает настройку рендеринга ресурсов в HTML.

**Returns:**
[ResourceHtmlRenderingHandler](../../com.aspose.email/resourcehtmlrenderinghandler)
### getResourceRenderingMode() {#getResourceRenderingMode--}
```
public final int getResourceRenderingMode()
```


Предоставляет набор различных режимов рендеринга ресурсов в html. Значение по умолчанию — EmbedIntoHtml.

**Returns:**
int
### getSaveResourceHandler() {#getSaveResourceHandler--}
```
public final SaveResourceHandler getSaveResourceHandler()
```


Этот обработчик вызывается для сохранения всех вложений сообщения, если EmbedResources равно false.

**Returns:**
[SaveResourceHandler](../../com.aspose.email/saveresourcehandler)
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

### setEmbedResources(boolean value) {#setEmbedResources-boolean-}
```
public final void setEmbedResources(boolean value)
```


Определяет, нужно ли встраивать ресурсы в html‑контент при сохранении. Значение по умолчанию — true.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setHtmlFormatOptions(int value) {#setHtmlFormatOptions-int-}
```
public final void setHtmlFormatOptions(int value)
```


Получает или задает дополнительные параметры при сохранении в формате HTML. Значение по умолчанию — HtmlFormatOptions.None.

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

### setRenderedContactFields(int value) {#setRenderedContactFields-int-}
```
public final void setRenderedContactFields(int value)
```


Определяет группы полей Contact, которые будут включены в выходной mhtml. Значение по умолчанию — ContactFieldsSet.AllExisting.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setResourceHtmlRenderingHandler(ResourceHtmlRenderingHandler value) {#setResourceHtmlRenderingHandler-com.aspose.email.ResourceHtmlRenderingHandler-}
```
public final void setResourceHtmlRenderingHandler(ResourceHtmlRenderingHandler value)
```


Обеспечивает настройку рендеринга ресурсов в HTML.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [ResourceHtmlRenderingHandler](../../com.aspose.email/resourcehtmlrenderinghandler) |  |

### setResourceRenderingMode(int value) {#setResourceRenderingMode-int-}
```
public final void setResourceRenderingMode(int value)
```


Предоставляет набор различных режимов рендеринга ресурсов в html. Значение по умолчанию — EmbedIntoHtml.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setSaveResourceHandler(SaveResourceHandler value) {#setSaveResourceHandler-com.aspose.email.SaveResourceHandler-}
```
public final void setSaveResourceHandler(SaveResourceHandler value)
```


Этот обработчик вызывается для сохранения всех вложений сообщения, если EmbedResources равно false.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [SaveResourceHandler](../../com.aspose.email/saveresourcehandler) |  |

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

