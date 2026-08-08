---
title: MapiMessage
second_title: Aspose.Email for Android via Java API Reference
description: Представляет документ формата Outlook Message, который можно разобрать.
type: docs
weight: 260
url: /ru/androidjava/com.aspose.email/mapimessage/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer), [com.aspose.email.MapiMessageItemBase](../../com.aspose.email/mapimessageitembase)
```
public final class MapiMessage extends MapiMessageItemBase
```

Представляет документ формата Outlook Message, который можно разобрать.

--------------------

> The following exmaple demonstrates how to read Outlook Message files.
> 
> [Java]
> 
> ```
> //Open Outlook Message files
>   MapiMessage msg = MapiMessage.fromFile("outlookmessage.msg");
> 
>   //read subject
>   System.out.print("Subject:" + msg.getSubject());
> 
>   //sender name
>   System.out.print("From:" + msg.getSenderName());
> 
>   //message body
>   System.out.print("Body:" + msg.getBody());
> 
>   //Attachments
>   for(MapiAttachment att : msg.getAttachments())
>   {
>       System.out.print("Attachment Name:"+att.getFileName());
>       att.save(att.getFileName());
>   }
> ```

--------------------

Экземпляры класса MapiMessage используются для представления файлов документов Microsoft Outlook Message, которые разбираются классом MapiMessageReader. Чтобы получить доступ к отправителю, получателю и содержимому электронного сообщения, используйте соответствующие свойства класса MapiMessage.
## Constructors

| Constructor | Описание |
| --- | --- |
| [MapiMessage()](#MapiMessage--) | Инициализирует новый экземпляр класса [MapiMessage](../../com.aspose.email/mapimessage). |
| [MapiMessage(int format)](#MapiMessage-int-) | Инициализирует новый экземпляр класса [MapiMessage](../../com.aspose.email/mapimessage). |
| [MapiMessage(String from, String to, String subject, String body, int format)](#MapiMessage-java.lang.String-java.lang.String-java.lang.String-java.lang.String-int-) | Инициализирует новый экземпляр класса [MapiMessage](../../com.aspose.email/mapimessage). |
| [MapiMessage(String from, String to, String subject, String body)](#MapiMessage-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса [MapiMessage](../../com.aspose.email/mapimessage). |
## Methods

| Method | Описание |
| --- | --- |
| [addCustomProperty(MapiProperty property, String stringNameId)](#addCustomProperty-com.aspose.email.MapiProperty-java.lang.String-) | Добавляет пользовательское свойство. |
| [addCustomProperty(int type, byte[] data, String stringNameId)](#addCustomProperty-int-byte---java.lang.String-) | Добавляет пользовательское свойство. |
| [checkBounced()](#checkBounced--) | Проверяет, может ли это сообщение рассматриваться как сообщение‑отскок. |
| [close()](#close--) |  |
| [createMapiNode(String key)](#createMapiNode-java.lang.String-) | Создает узел mapi. |
| [deepClone()](#deepClone--) | Создаёт новый объект, являющийся копией текущего экземпляра. |
| [destroyAttachments(String path)](#destroyAttachments-java.lang.String-) | Удаляет вложения в указанных файлах Outlook Message. |
| [dispose()](#dispose--) | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromFile(String path)](#fromFile-java.lang.String-) | Создайте экземпляр MapiMessage из указанного файла. |
| [fromMailMessage(MailMessage message)](#fromMailMessage-com.aspose.email.MailMessage-) | Создаёт экземпляр MapiMessage из MailMessage. |
| [fromMailMessage(MailMessage message, MapiConversionOptions options)](#fromMailMessage-com.aspose.email.MailMessage-com.aspose.email.MapiConversionOptions-) | Создаёт экземпляр MapiMessage из MailMessage. |
| [fromMailMessage(String fileName)](#fromMailMessage-java.lang.String-) | Создаёт экземпляр MapiMessage из MailMessage. |
| [fromProperties(MapiPropertyCollection properties)](#fromProperties-com.aspose.email.MapiPropertyCollection-) | Создаёт экземпляр MapiMessage из коллекции свойств Mapi. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Создайте экземпляр MapiMessage из указанного потока. |
| [getAttachments()](#getAttachments--) | Получает вложения в сообщении. |
| [getBilling()](#getBilling--) | Содержит информацию о выставлении счета, связанную с элементом. |
| [getBody()](#getBody--) | Получает текст сообщения. |
| [getBodyHtml()](#getBodyHtml--) | Получает BodyRtf (\#getBodyRtf.getBodyRtf/\#setBodyRtf(String).setBodyRtf(String)) сообщения, преобразованного в HTML, если присутствует, иначе пустую строку. |
| [getBodyRtf()](#getBodyRtf--) | Получает или задает текст сообщения в формате RTF. |
| [getBodyType()](#getBodyType--) | Получает тип тела. |
| [getCategories()](#getCategories--) | Содержит ключевые слова или категории для объекта сообщения. |
| [getClass()](#getClass--) |  |
| [getClientSubmitTime()](#getClientSubmitTime--) | Получает или задаёт дату и время отправки сообщения отправителем. |
| [getCodePage()](#getCodePage--) | Получает кодовую страницу. |
| [getCompanies()](#getCompanies--) | Содержит названия компаний, связанных с элементом. |
| [getConversationTopic()](#getConversationTopic--) | Получает тему первого сообщения в цепочке разговора. |
| [getCustomProperties()](#getCustomProperties--) | Получает коллекцию пользовательских MapiProperties. |
| [getDeliveryTime()](#getDeliveryTime--) | Получает или задает дату и время доставки сообщения. |
| [getDisplayBcc()](#getDisplayBcc--) | Получает список отображаемых имен всех получателей скрытой копии (BCC), разделённых точками с запятой (;). |
| [getDisplayCc()](#getDisplayCc--) | Получает список отображаемых имен всех получателей копии (CC), разделённых точками с запятой (;). |
| [getDisplayName()](#getDisplayName--) | Получает отображаемое имя сообщения. |
| [getDisplayNamePrefix()](#getDisplayNamePrefix--) | Получает префикс отображаемого имени. |
| [getDisplayTo()](#getDisplayTo--) | Получает список отображаемых имен основных получателей (To), разделённых точками с запятой (;). |
| [getFlags()](#getFlags--) | Получает флаги сообщения. |
| [getHeaders()](#getHeaders--) | Получает заголовки транспортного сообщения |
| [getInternetMessageId()](#getInternetMessageId--) | Получает идентификатор сообщения. |
| [getItemId()](#getItemId--) | Идентификатор элемента, используется с сервером. |
| [getMessageClass()](#getMessageClass--) | Получает чувствительную к регистру строку, идентифицирующую пользовательский класс сообщения, например IPM.Note. |
| [getMessageFormat()](#getMessageFormat--) | Получает формат сообщения Outlook. |
| [getMileage()](#getMileage--) | Содержит информацию о пробеге, связанную с элементом. |
| [getNamedProperties()](#getNamedProperties--) | Получает именованные свойства сообщения. |
| [getNamedPropertyMapping()](#getNamedPropertyMapping--) | Получает сопоставление именованных свойств. |
| [getNormalizedSubject()](#getNormalizedSubject--) | Получает нормализованную тему сообщения. |
| [getProperties()](#getProperties--) | Получает коллекцию свойств. |
| [getProperty(PropertyDescriptor pd)](#getProperty-com.aspose.email.PropertyDescriptor-) | Получает свойство MAPI по дескриптору свойства. |
| [getPropertyBoolean(long tag)](#getPropertyBoolean-long-) | Получает значение свойства, указанного тегом, в виде типа Boolean. |
| [getPropertyBytes(long tag)](#getPropertyBytes-long-) | Получает строковое значение свойства, указанного тегом. |
| [getPropertyDateTime(long key)](#getPropertyDateTime-long-) | Получает значение свойства, указанного тегом, в виде типа DateTime. |
| [getPropertyInt32(long tag)](#getPropertyInt32-long-) | Получает значение int32 свойства, указанного тегом. |
| [getPropertyLong(long tag)](#getPropertyLong-long-) | Получает значение свойства, указанного тегом, в виде типа Long (int64). |
| [getPropertyShort(long tag)](#getPropertyShort-long-) | Получает значение свойства, указанного тегом, в виде типа Short. |
| [getPropertyStream()](#getPropertyStream--) | Получает поток свойства. |
| [getPropertyString(long tag)](#getPropertyString-long-) | Получает строковое значение свойства, указанного тегом. |
| [getPropertyString(long tag, int codepage)](#getPropertyString-long-int-) | Получает строковое значение свойства, указанного тегом. |
| [getReadReceiptRequested()](#getReadReceiptRequested--) | Получает или задает значение, указывающее, запрашивается ли подтверждение о прочтении. |
| [getRecipients()](#getRecipients--) | Получает получателей сообщения. |
| [getReplyTo()](#getReplyTo--) | Получает или задает имена получателей ответа. |
| [getSenderAddressType()](#getSenderAddressType--) | Получает тип электронного адреса отправителя сообщения. |
| [getSenderEmailAddress()](#getSenderEmailAddress--) | Получает или задает электронный адрес отправителя сообщения. |
| [getSenderName()](#getSenderName--) | Получает или задает отображаемое имя отправителя сообщения. |
| [getSenderSmtpAddress()](#getSenderSmtpAddress--) | Получает или задает электронный адрес отправителя сообщения. |
| [getSensitivity()](#getSensitivity--) | Gets the Sensitivity. |
| [getSentRepresentingAddressType()](#getSentRepresentingAddressType--) | Получает тип адреса для пользователя сообщений, представленного отправителем. |
| [getSentRepresentingEmailAddress()](#getSentRepresentingEmailAddress--) | Получает или задает электронный адрес для пользователя сообщений, представленного отправителем. |
| [getSentRepresentingName()](#getSentRepresentingName--) | Получает или задает отображаемое имя для пользователя сообщений, представленного отправителем. |
| [getSentRepresentingSmtpAddress()](#getSentRepresentingSmtpAddress--) | Получает или задает электронный адрес для пользователя сообщений, представленного отправителем. |
| [getSubStorages()](#getSubStorages--) | Получает вложенные хранилища. |
| [getSubject()](#getSubject--) | Получает или задает тему сообщения. |
| [getSubjectPrefix()](#getSubjectPrefix--) | Получает префикс темы, который обычно указывает на действие с сообщением, например \"FW: \" для пересылки. |
| [getTransportMessageHeaders()](#getTransportMessageHeaders--) | Получает транспортно-специфичную информацию о конверте сообщения. |
| [hashCode()](#hashCode--) |  |
| [isMsgFormat(InputStream stream)](#isMsgFormat-java.io.InputStream-) | Определяет, имеет ли указанный поток формат MSG. |
| [isMsgFormat(String fileName)](#isMsgFormat-java.lang.String-) | Определяет, имеет ли указанный файл формат MSG. |
| [isStoreUnicodeOk()](#isStoreUnicodeOk--) | Определяет, закодированы ли строковые свойства в Unicode. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Загружает сообщение из потока. |
| [load(InputStream stream, LoadOptions options)](#load-java.io.InputStream-com.aspose.email.LoadOptions-) | Загружает сообщение из потока с дополнительными параметрами. |
| [load(String fileName)](#load-java.lang.String-) | Загружает сообщение из файла. |
| [load(String fileName, LoadOptions options)](#load-java.lang.String-com.aspose.email.LoadOptions-) | Загружает сообщение из файла с дополнительными параметрами. |
| [loadFromTnef(InputStream stream)](#loadFromTnef-java.io.InputStream-) | Загружает сообщение из структуры данных Transport Neutral Encapsulation Format (TNEF) |
| [loadFromTnef(String fileName)](#loadFromTnef-java.lang.String-) | Загружает сообщение из структуры данных Transport Neutral Encapsulation Format (TNEF) |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeAttachments(String path)](#removeAttachments-java.lang.String-) | Удаляет все вложения из указанных файлов Outlook Message. |
| [removeProperty(long tag)](#removeProperty-long-) | Обеспечивает корректное удаление свойства из всех коллекций. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Сохраняет в указанный поток в формате Msg. |
| [save(OutputStream stream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.email.SaveOptions-) | Сохраняет сообщение в виде потока с дополнительными параметрами. |
| [save(String fileName)](#save-java.lang.String-) | Сохраняет в указанный файл в формате Msg. |
| [save(String fileName, SaveOptions options)](#save-java.lang.String-com.aspose.email.SaveOptions-) | Сохраняет сообщение в файл с дополнительными параметрами. |
| [saveAsTemplate(OutputStream stream)](#saveAsTemplate-java.io.OutputStream-) | Сохраняет в указанный поток в формате Outlook File Template (OFT). |
| [saveAsTemplate(String fileName)](#saveAsTemplate-java.lang.String-) | Сохраняет в указанный файл в формате Outlook File Template (OFT). |
| [saveAsTnef(OutputStream stream)](#saveAsTnef-java.io.OutputStream-) | Сохраняет сообщение в формате TNEF. |
| [saveAsTnef(String fileName)](#saveAsTnef-java.lang.String-) | Сохраняет сообщение в формате TNEF. |
| [setBilling(String value)](#setBilling-java.lang.String-) | Содержит информацию о выставлении счета, связанную с элементом. |
| [setBody(String value)](#setBody-java.lang.String-) | Получает текст сообщения. |
| [setBodyContent(String content, int contentType)](#setBodyContent-java.lang.String-int-) | Устанавливает содержимое тела. |
| [setBodyContent(String content, int contentType, boolean compression)](#setBodyContent-java.lang.String-int-boolean-) | Устанавливает содержимое тела. |
| [setBodyRtf(String value)](#setBodyRtf-java.lang.String-) | Получает или задает текст сообщения в формате RTF. |
| [setBodyRtf(String value, boolean compression)](#setBodyRtf-java.lang.String-boolean-) | Получает или задает текст сообщения в формате RTF. |
| [setCategories(String[] value)](#setCategories-java.lang.String---) | Содержит ключевые слова или категории для объекта сообщения. |
| [setClientSubmitTime(Date value)](#setClientSubmitTime-java.util.Date-) | Получает или задаёт дату и время отправки сообщения отправителем. |
| [setCompanies(String[] value)](#setCompanies-java.lang.String---) | Содержит названия компаний, связанных с элементом. |
| [setDeliveryTime(Date value)](#setDeliveryTime-java.util.Date-) | Получает или задает дату и время доставки сообщения. |
| [setHeaders(HeaderCollection value)](#setHeaders-com.aspose.email.HeaderCollection-) | Получает заголовки транспортного сообщения |
| [setMessageClass(String value)](#setMessageClass-java.lang.String-) | Получает чувствительную к регистру строку, идентифицирующую пользовательский класс сообщения, например IPM.Note. |
| [setMessageFlags(long flags)](#setMessageFlags-long-) | Устанавливает флаги сообщения. |
| [setMileage(String value)](#setMileage-java.lang.String-) | Содержит информацию о пробеге, связанную с элементом. |
| [setNamedPropertyMapping(MapiNamedPropertyMappingStorage value)](#setNamedPropertyMapping-com.aspose.email.MapiNamedPropertyMappingStorage-) | Устанавливает сопоставление именованных свойств. |
| [setProperty(MapiAttachment value, long signed, long key)](#setProperty-com.aspose.email.MapiAttachment-long-long-) | Устанавливает вложение. |
| [setProperty(MapiProperty value)](#setProperty-com.aspose.email.MapiProperty-) | Устанавливает свойство. |
| [setProperty(MapiRecipient value, long signed, long key)](#setProperty-com.aspose.email.MapiRecipient-long-long-) | Устанавливает получателя. |
| [setProperty(PropertyDescriptor pd, Object value)](#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-) | Устанавливает свойство MAPI. |
| [setReadReceiptRequested(boolean value)](#setReadReceiptRequested-boolean-) | Получает или задает значение, указывающее, запрашивается ли подтверждение о прочтении. |
| [setRecipients(MapiRecipientCollection value)](#setRecipients-com.aspose.email.MapiRecipientCollection-) | Получает получателей сообщения. |
| [setReplyTo(String value)](#setReplyTo-java.lang.String-) | Получает или задает имена получателей ответа. |
| [setSenderEmailAddress(String value)](#setSenderEmailAddress-java.lang.String-) | Получает или задает электронный адрес отправителя сообщения. |
| [setSenderName(String value)](#setSenderName-java.lang.String-) | Получает или задает отображаемое имя отправителя сообщения. |
| [setSenderSmtpAddress(String value)](#setSenderSmtpAddress-java.lang.String-) | Получает или задает электронный адрес отправителя сообщения. |
| [setSensitivity(int value)](#setSensitivity-int-) | Gets the Sensitivity. |
| [setSentRepresentingEmailAddress(String value)](#setSentRepresentingEmailAddress-java.lang.String-) | Получает или задает электронный адрес для пользователя сообщений, представленного отправителем. |
| [setSentRepresentingName(String value)](#setSentRepresentingName-java.lang.String-) | Получает или задает отображаемое имя для пользователя сообщений, представленного отправителем. |
| [setStringPropertyValue(long tag, String value)](#setStringPropertyValue-long-java.lang.String-) | Устанавливает значение строкового свойства. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Получает или задает тему сообщения. |
| [toMailMessage(MailConversionOptions options)](#toMailMessage-com.aspose.email.MailConversionOptions-) | Создаёт экземпляр MailMessage из этого MapiMessage. |
| [toMapiMessageItem()](#toMapiMessageItem--) | Преобразует MapiMessage в объект IMapiMessageItem в зависимости от MessageClass. |
| [toString()](#toString--) |  |
| [tryGetPropertyData(long tag)](#tryGetPropertyData-long-) | Попробуйте получить данные свойства с указанным ключом тега. |
| [tryGetPropertyDateTime(long tag, Date[] value)](#tryGetPropertyDateTime-long-java.util.Date---) | Получает значение указанного свойства как тип DateTime. |
| [tryGetPropertyInt32(long tag, int[] value)](#tryGetPropertyInt32-long-int---) | Получает значение указанного свойства как тип Int32. |
| [tryGetPropertyLong(long tag, long[] value)](#tryGetPropertyLong-long-long---) | Получает значение указанного свойства как тип Long. |
| [tryGetPropertyString(long tag)](#tryGetPropertyString-long-) | Попробуйте получить данные свойства в виде строки с указанным тегом. |
| [tryGetPropertyString(long tag, int codepage)](#tryGetPropertyString-long-int-) | Попробуйте получить данные свойства в виде строки с указанным тегом и кодовой страницей. |
| [tryGetPropertyString(long tag, String[] value)](#tryGetPropertyString-long-java.lang.String---) | Получает значение указанного свойства как тип String. |
| [tryGetPropertyString(long tag, String[] value, int codepage)](#tryGetPropertyString-long-java.lang.String---int-) | Получает значение указанного свойства как тип String. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiMessage() {#MapiMessage--}
```
public MapiMessage()
```


Инициализирует новый экземпляр класса [MapiMessage](../../com.aspose.email/mapimessage).

### MapiMessage(int format) {#MapiMessage-int-}
```
public MapiMessage(int format)
```


Инициализирует новый экземпляр класса [MapiMessage](../../com.aspose.email/mapimessage).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| формат | int | Определяет, использовать ли Unicode или ASCII кодировку для этого сообщения. |

### MapiMessage(String from, String to, String subject, String body, int format) {#MapiMessage-java.lang.String-java.lang.String-java.lang.String-java.lang.String-int-}
```
public MapiMessage(String from, String to, String subject, String body, int format)
```


Инициализирует новый экземпляр класса [MapiMessage](../../com.aspose.email/mapimessage).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| from | java.lang.String | Адрес отправителя. |
| к | java.lang.String | Адреса получателей. Обратите внимание, что адреса разделены точкой с запятой. |
| тема | java.lang.String | Тема сообщения. |
| тело | java.lang.String | Тело сообщения. |
| формат | int | Определяет, использовать ли Unicode или ASCII кодировку для этого сообщения. |

### MapiMessage(String from, String to, String subject, String body) {#MapiMessage-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public MapiMessage(String from, String to, String subject, String body)
```


Инициализирует новый экземпляр класса [MapiMessage](../../com.aspose.email/mapimessage).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| from | java.lang.String | Адрес отправителя. |
| к | java.lang.String | Адреса получателей. Обратите внимание, что адреса разделены точкой с запятой. |
| тема | java.lang.String | Тема сообщения. |
| тело | java.lang.String | Тело сообщения. |

### addCustomProperty(MapiProperty property, String stringNameId) {#addCustomProperty-com.aspose.email.MapiProperty-java.lang.String-}
```
public final void addCustomProperty(MapiProperty property, String stringNameId)
```


Добавляет пользовательское свойство.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| property | [MapiProperty](../../com.aspose.email/mapiproperty) | Свойство[MapiProperty](../../com.aspose.email/mapiproperty). |
| stringNameId | java.lang.String | Имя propertyString. |

### addCustomProperty(int type, byte[] data, String stringNameId) {#addCustomProperty-int-byte---java.lang.String-}
```
public final void addCustomProperty(int type, byte[] data, String stringNameId)
```


Добавляет пользовательское свойство.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| type | int | Тип MapiProperty[MapiPropertyType](../../com.aspose.email/mapipropertytype) |
| данные | byte[] | MapiProperty data.byte |
| stringNameId | java.lang.String | Имя propertyString. |

### checkBounced() {#checkBounced--}
```
public final BounceResult checkBounced()
```


Проверяет, может ли это сообщение рассматриваться как сообщение‑отскок.

**Returns:**
[BounceResult](../../com.aspose.email/bounceresult) - Result of checking[BounceResult](../../com.aspose.email/bounceresult).
### close() {#close--}
```
public void close()
```




### createMapiNode(String key) {#createMapiNode-java.lang.String-}
```
public IMapiNode createMapiNode(String key)
```


Создает узел mapi.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| ключ | java.lang.String | Ключ узла. |

**Returns:**
com.aspose.email.IMapiNode - Интерфейс IMapiNode.
### deepClone() {#deepClone--}
```
public final MapiMessage deepClone()
```


Создаёт новый объект, являющийся копией текущего экземпляра.

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - A new object that is a copy of this instance.
### destroyAttachments(String path) {#destroyAttachments-java.lang.String-}
```
public static void destroyAttachments(String path)
```


Уничтожает вложения в указанных файлах Outlook Message. DestroyAttachments будет игнорировать разбор вложений.

--------------------

> The following exmaple demonstrates how to destroy attachments in Outlook Message files.
> 
> [Java]
> 
> ```
> //Destroy attachments from Outlook Message files
>      MapiMessage.destroyAttachment("outlookmessage.msg");
> ```

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| путь | java.lang.String | Имя файла Outlook Message. |

### dispose() {#dispose--}
```
public void dispose()
```


Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов.

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
### fromFile(String path) {#fromFile-java.lang.String-}
```
public static MapiMessage fromFile(String path)
```


Создайте экземпляр MapiMessage из указанного файла.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| путь | java.lang.String | Имя файла, который будет загружен. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - Returns a MapiMessage instance which is loaded from the specified file.
### fromMailMessage(MailMessage message) {#fromMailMessage-com.aspose.email.MailMessage-}
```
public static MapiMessage fromMailMessage(MailMessage message)
```


Создаёт экземпляр MapiMessage из MailMessage.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | Объект MailMessage. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - Returns a MapiMessage instance which is loaded from the MailMessage.
### fromMailMessage(MailMessage message, MapiConversionOptions options) {#fromMailMessage-com.aspose.email.MailMessage-com.aspose.email.MapiConversionOptions-}
```
public static MapiMessage fromMailMessage(MailMessage message, MapiConversionOptions options)
```


Создаёт экземпляр MapiMessage из MailMessage.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | Объект MailMessage. |
| options | [MapiConversionOptions](../../com.aspose.email/mapiconversionoptions) | MapiFromMailMessageOptions [MapiConversionOptions](../../com.aspose.email/mapiconversionoptions) |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - [MapiMessage](../../com.aspose.email/mapimessage) that represents Outlook message.
### fromMailMessage(String fileName) {#fromMailMessage-java.lang.String-}
```
public static MapiMessage fromMailMessage(String fileName)
```


Создаёт экземпляр MapiMessage из MailMessage.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла MailMessage. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - Returns a MapiMessage instance which is loaded from the MailMessage.
### fromProperties(MapiPropertyCollection properties) {#fromProperties-com.aspose.email.MapiPropertyCollection-}
```
public static MapiMessage fromProperties(MapiPropertyCollection properties)
```


Создаёт экземпляр MapiMessage из коллекции свойств Mapi.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| properties | [MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) | Коллекция MapiProperty. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - Returns a MapiMessage instance which is loaded from the specified properties.
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static MapiMessage fromStream(InputStream stream)
```


Создайте экземпляр MapiMessage из указанного потока.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, который будет загружен. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - Returns a MapiMessage instance which is loaded from the specified stream.
### getAttachments() {#getAttachments--}
```
public final MapiAttachmentCollection getAttachments()
```


Получает вложения в сообщении.

Значение: Коллекция вложений.

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection)
### getBilling() {#getBilling--}
```
public final String getBilling()
```


Содержит информацию о выставлении счета, связанную с элементом.

**Returns:**
java.lang.String
### getBody() {#getBody--}
```
public final String getBody()
```


Получает текст сообщения.

Значение: Строка, представляющая тело сообщения.

**Returns:**
java.lang.String
### getBodyHtml() {#getBodyHtml--}
```
public final String getBodyHtml()
```


Получает BodyRtf (\#getBodyRtf.getBodyRtf/\#setBodyRtf(String).setBodyRtf(String)) сообщения, преобразованного в HTML, если присутствует, иначе пустую строку.

**Returns:**
java.lang.String
### getBodyRtf() {#getBodyRtf--}
```
public final String getBodyRtf()
```


Получает или задает текст сообщения в формате RTF.

Значение: Строка, представляющая тело сообщения в формате rtf.

--------------------

При установке значения обновляются свойства PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY. Устанавливаемое строковое значение должно иметь формат RTF. Поэтому, если необходимо задать значение в формате HTML, его сначала нужно закодировать в RTF в соответствии со спецификацией RTF Extensions. Чтобы быстро задать содержимое тела сообщения в форматах HTML или обычного текста, используйте метод SetBodyContent. При установке null или пустой строки свойства BodyRtf и Body устанавливаются в null.

**Returns:**
java.lang.String
### getBodyType() {#getBodyType--}
```
public final int getBodyType()
```


Получает тип тела.

Значение: Тип тела.

**Returns:**
int
### getCategories() {#getCategories--}
```
public final String[] getCategories()
```


Содержит ключевые слова или категории для объекта сообщения.

**Returns:**
java.lang.String[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClientSubmitTime() {#getClientSubmitTime--}
```
public final Date getClientSubmitTime()
```


Получает или задаёт дату и время отправки сообщения отправителем.

Значение: DateTime, представляющий время отправки клиентом.

--------------------

Если свойство недоступно, возвращается DateTime.MinValue.

**Returns:**
java.util.Date
### getCodePage() {#getCodePage--}
```
public int getCodePage()
```


Получает кодовую страницу.

Значение: Кодовая страница.

**Returns:**
int
### getCompanies() {#getCompanies--}
```
public final String[] getCompanies()
```


Содержит названия компаний, связанных с элементом.

**Returns:**
java.lang.String[]
### getConversationTopic() {#getConversationTopic--}
```
public final String getConversationTopic()
```


Получает тему первого сообщения в цепочке разговора.

Значение: строка, представляющая тему беседы.

**Returns:**
java.lang.String
### getCustomProperties() {#getCustomProperties--}
```
public final MapiPropertyCollection getCustomProperties()
```


Получает коллекцию пользовательских MapiProperties.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) - Collection of custom MapiProperties[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection).
### getDeliveryTime() {#getDeliveryTime--}
```
public final Date getDeliveryTime()
```


Получает или задает дату и время доставки сообщения.

Значение: DateTime, представляющий время доставки.

--------------------

Если свойство недоступно, возвращается DateTime.MinValue.

**Returns:**
java.util.Date
### getDisplayBcc() {#getDisplayBcc--}
```
public final String getDisplayBcc()
```


Получает список отображаемых имен всех получателей скрытой копии (BCC), разделённых точками с запятой (;).

Значение: строка, представляющая отображаемый BCC.

**Returns:**
java.lang.String
### getDisplayCc() {#getDisplayCc--}
```
public final String getDisplayCc()
```


Получает список отображаемых имен всех получателей копии (CC), разделённых точками с запятой (;).

Значение: строка, представляющая отображаемый CC.

**Returns:**
java.lang.String
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Получает отображаемое имя сообщения.

Значение: Строка, представляющая отображаемое имя.

**Returns:**
java.lang.String
### getDisplayNamePrefix() {#getDisplayNamePrefix--}
```
public final String getDisplayNamePrefix()
```


Получает префикс отображаемого имени.

Значение: строка, представляющая префикс отображаемого имени.

**Returns:**
java.lang.String
### getDisplayTo() {#getDisplayTo--}
```
public final String getDisplayTo()
```


Получает список отображаемых имен основных получателей (To), разделённых точками с запятой (;).

Значение: строка, представляющая отображаемый получатель.

**Returns:**
java.lang.String
### getFlags() {#getFlags--}
```
public final long getFlags()
```


Получает флаги сообщения.

Значение: флаги сообщения.

**Returns:**
long
### getHeaders() {#getHeaders--}
```
public final HeaderCollection getHeaders()
```


Получает заголовки транспортного сообщения

**Returns:**
[HeaderCollection](../../com.aspose.email/headercollection)
### getInternetMessageId() {#getInternetMessageId--}
```
public final String getInternetMessageId()
```


Получает идентификатор сообщения.

Значение: строка, представляющая идентификатор интернет‑сообщения.

**Returns:**
java.lang.String
### getItemId() {#getItemId--}
```
public String getItemId()
```


Идентификатор элемента, используется с сервером.

**Returns:**
java.lang.String
### getMessageClass() {#getMessageClass--}
```
public final String getMessageClass()
```


Возвращает чувствительную к регистру строку, идентифицирующую определённый отправителем класс сообщения, например IPM.Note. Класс сообщения указывает тип, назначение или содержание сообщения.

Значение: Строка, представляющая класс сообщения.

**Returns:**
java.lang.String
### getMessageFormat() {#getMessageFormat--}
```
public final int getMessageFormat()
```


Получает формат сообщения Outlook.

Значение: формат сообщения Outlook.

**Returns:**
int
### getMileage() {#getMileage--}
```
public final String getMileage()
```


Содержит информацию о пробеге, связанную с элементом.

**Returns:**
java.lang.String
### getNamedProperties() {#getNamedProperties--}
```
public final MapiPropertyCollection getNamedProperties()
```


Получает именованные свойства сообщения.

Значение: Коллекция именованных свойств.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getNamedPropertyMapping() {#getNamedPropertyMapping--}
```
public final MapiNamedPropertyMappingStorage getNamedPropertyMapping()
```


Получает сопоставление именованных свойств.

Значение: Сопоставление именованных свойств.

**Returns:**
[MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage)
### getNormalizedSubject() {#getNormalizedSubject--}
```
public final String getNormalizedSubject()
```


Получает нормализованную тему сообщения.

Значение: строка, представляющая нормализованную тему.

**Returns:**
java.lang.String
### getProperties() {#getProperties--}
```
public MapiPropertyCollection getProperties()
```


Получает коллекцию свойств.

Значение: Свойства.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getProperty(PropertyDescriptor pd) {#getProperty-com.aspose.email.PropertyDescriptor-}
```
public MapiProperty getProperty(PropertyDescriptor pd)
```


Получает свойство MAPI по дескриптору свойства.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | Дескриптор свойства для искомого свойства. |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - Mapi property if it is found, otherwise null.
### getPropertyBoolean(long tag) {#getPropertyBoolean-long-}
```
public final Boolean getPropertyBoolean(long tag)
```


Получает значение свойства, указанного тегом, в виде типа Boolean.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства MAPI. |

**Returns:**
java.lang.Boolean — значение свойства. Если свойство не существует, возвращает NULL; в противном случае возвращает значение.
### getPropertyBytes(long tag) {#getPropertyBytes-long-}
```
public final byte[] getPropertyBytes(long tag)
```


Получает строковое значение свойства, указанного тегом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства MAPI. |

**Returns:**
byte[] — значение свойства. Если свойство не существует, возвращает NULL; в противном случае возвращает значение.
### getPropertyDateTime(long key) {#getPropertyDateTime-long-}
```
public final Date getPropertyDateTime(long key)
```


Получает значение свойства, указанного тегом, в виде типа DateTime.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| ключ | long | Тег свойства MAPI. |

**Returns:**
java.util.Date — значение свойства. Если свойство не существует, возвращает NULL; в противном случае возвращает значение.
### getPropertyInt32(long tag) {#getPropertyInt32-long-}
```
public final Integer getPropertyInt32(long tag)
```


Получает значение int32 свойства, указанного тегом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства MAPI. |

**Returns:**
java.lang.Integer — значение свойства. Если свойство не существует, возвращает NULL; в противном случае возвращает значение.
### getPropertyLong(long tag) {#getPropertyLong-long-}
```
public final Long getPropertyLong(long tag)
```


Получает значение свойства, указанного тегом, в виде типа Long (int64).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства MAPI. |

**Returns:**
java.lang.Long — значение свойства. Если свойство не существует, возвращает NULL; в противном случае возвращает значение.
### getPropertyShort(long tag) {#getPropertyShort-long-}
```
public final Short getPropertyShort(long tag)
```


Получает значение свойства, указанного тегом, в виде типа Short.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства MAPI. |

**Returns:**
java.lang.Short — значение свойства. Если свойство не существует, возвращает NULL; в противном случае возвращает значение.
### getPropertyStream() {#getPropertyStream--}
```
public final MapiPropertyStream getPropertyStream()
```


Получает поток свойства.

Значение: Поток свойства.

**Returns:**
[MapiPropertyStream](../../com.aspose.email/mapipropertystream)
### getPropertyString(long tag) {#getPropertyString-long-}
```
public final String getPropertyString(long tag)
```


Получает строковое значение свойства, указанного тегом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства MAPI. |

**Returns:**
java.lang.String — значение свойства. Если свойство не существует, возвращает NULL; в противном случае возвращает значение.
### getPropertyString(long tag, int codepage) {#getPropertyString-long-int-}
```
public final String getPropertyString(long tag, int codepage)
```


Получает строковое значение свойства, указанного тегом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства MAPI. |
| кодовая страница | int | Указанная кодовая страница, используемая для получения строкового значения. |

**Returns:**
java.lang.String — значение свойства. Если свойство не существует, возвращает NULL; в противном случае возвращает значение.
### getReadReceiptRequested() {#getReadReceiptRequested--}
```
public final boolean getReadReceiptRequested()
```


Получает или задает значение, указывающее, запрашивается ли подтверждение о прочтении.

Значение: true, если запрошено подтверждение о прочтении; иначе false.

**Returns:**
boolean
### getRecipients() {#getRecipients--}
```
public final MapiRecipientCollection getRecipients()
```


Получает получателей сообщения.

Значение: Коллекция получателей.

**Returns:**
[MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection)
### getReplyTo() {#getReplyTo--}
```
public final String getReplyTo()
```


Получает или задает имена получателей ответа.

**Returns:**
java.lang.String
### getSenderAddressType() {#getSenderAddressType--}
```
public final String getSenderAddressType()
```


Получает тип электронного адреса отправителя сообщения.

Значение: строка, представляющая тип адреса отправителя.

**Returns:**
java.lang.String
### getSenderEmailAddress() {#getSenderEmailAddress--}
```
public final String getSenderEmailAddress()
```


Получает или задает электронный адрес отправителя сообщения.

**Returns:**
java.lang.String
### getSenderName() {#getSenderName--}
```
public final String getSenderName()
```


Получает или задает отображаемое имя отправителя сообщения.

Значение: строка, представляющая имя отправителя.

--------------------

При установке null или пустой строки значения свойства принимают значение, равное SenderEmailAddress.

**Returns:**
java.lang.String
### getSenderSmtpAddress() {#getSenderSmtpAddress--}
```
public final String getSenderSmtpAddress()
```


Получает или задает электронный адрес отправителя сообщения.

**Returns:**
java.lang.String
### getSensitivity() {#getSensitivity--}
```
public final int getSensitivity()
```


Gets the Sensitivity.

Значение: Чувствительность.

**Returns:**
int
### getSentRepresentingAddressType() {#getSentRepresentingAddressType--}
```
public final String getSentRepresentingAddressType()
```


Получает тип адреса для пользователя сообщений, представленного отправителем.

Значение: строка, представляющая тип адреса отправки.

**Returns:**
java.lang.String
### getSentRepresentingEmailAddress() {#getSentRepresentingEmailAddress--}
```
public final String getSentRepresentingEmailAddress()
```


Получает или задает электронный адрес для пользователя сообщений, представленного отправителем.

**Returns:**
java.lang.String
### getSentRepresentingName() {#getSentRepresentingName--}
```
public final String getSentRepresentingName()
```


Получает или задает отображаемое имя для пользователя сообщений, представленного отправителем.

Значение: Строка, представляющая отправляющее имя.

--------------------

При установке нулевого значения или пустой строки значения свойства задаются в SentRepresentingEmailAddress.

**Returns:**
java.lang.String
### getSentRepresentingSmtpAddress() {#getSentRepresentingSmtpAddress--}
```
public final String getSentRepresentingSmtpAddress()
```


Получает или задает электронный адрес для пользователя сообщений, представленного отправителем.

Значение: Строка, представляющая отправляющий адрес электронной почты.

**Returns:**
java.lang.String
### getSubStorages() {#getSubStorages--}
```
public final MapiPropertyCollection getSubStorages()
```


Получает вложенные хранилища.

Значение: Подхранилища.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Получает или задает тему сообщения.

Значение: Строка, представляющая тему сообщения.

--------------------

При установке значения также обновляются значения свойств SubjectPrefix(PR\_SUBJECT\_PREFIX) и NormalizedSubject(PR\_NORMALIZED\_SUBJECT). Если у Subject нет префикса, значение свойства SubjectPrefix устанавливается в null. При установке значения null или пустой строки значения свойств Subject, SubjectPrefix, NormalizedSubject устанавливаются в null.

**Returns:**
java.lang.String
### getSubjectPrefix() {#getSubjectPrefix--}
```
public final String getSubjectPrefix()
```


Получает префикс темы, который обычно указывает на действие с сообщением, например \"FW: \" для пересылки.

Значение: Строка, представляющая префикс темы.

**Returns:**
java.lang.String
### getTransportMessageHeaders() {#getTransportMessageHeaders--}
```
public final String getTransportMessageHeaders()
```


Получает транспортно-специфичную информацию о конверте сообщения.

Значение: Строка, представляющая заголовки транспортного сообщения.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isMsgFormat(InputStream stream) {#isMsgFormat-java.io.InputStream-}
```
public static boolean isMsgFormat(InputStream stream)
```


Определяет, имеет ли указанный поток формат MSG.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток сообщения. |

**Returns:**
boolean -  true  если поток представлен в формате MSG]; иначе,  false .
### isMsgFormat(String fileName) {#isMsgFormat-java.lang.String-}
```
public static boolean isMsgFormat(String fileName)
```


Определяет, имеет ли указанный файл формат MSG.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |

**Returns:**
boolean -  true  если файл представлен в формате MSG; иначе,  false .
### isStoreUnicodeOk() {#isStoreUnicodeOk--}
```
public final boolean isStoreUnicodeOk()
```


Определяет, закодированы ли строковые свойства в Unicode.

**Returns:**
boolean — True, если строковые свойства закодированы в Unicode.
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static MapiMessage load(InputStream stream)
```


Загружает сообщение из потока.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Исходный поток java.io.InputStream. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - 
### load(InputStream stream, LoadOptions options) {#load-java.io.InputStream-com.aspose.email.LoadOptions-}
```
public static MapiMessage load(InputStream stream, LoadOptions options)
```


Загружает сообщение из потока с дополнительными параметрами.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Исходный поток java.io.InputStream. |
| options | [LoadOptions](../../com.aspose.email/loadoptions) | Дополнительные параметры [LoadOptions](../../com.aspose.email/loadoptions). |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - 
### load(String fileName) {#load-java.lang.String-}
```
public static MapiMessage load(String fileName)
```


Загружает сообщение из файла.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Исходный путь к файлу pathString. |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - 
### load(String fileName, LoadOptions options) {#load-java.lang.String-com.aspose.email.LoadOptions-}
```
public static MapiMessage load(String fileName, LoadOptions options)
```


Загружает сообщение из файла с дополнительными параметрами.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Исходный путь к файлу pathString. |
| options | [LoadOptions](../../com.aspose.email/loadoptions) | Дополнительные параметры [LoadOptions](../../com.aspose.email/loadoptions). |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - 
### loadFromTnef(InputStream stream) {#loadFromTnef-java.io.InputStream-}
```
public static MapiMessage loadFromTnef(InputStream stream)
```


Загружает сообщение из структуры данных Transport Neutral Encapsulation Format (TNEF)

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, представляющий данные сообщения в формате TNEF |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - A read [MapiMessage](../../com.aspose.email/mapimessage)
### loadFromTnef(String fileName) {#loadFromTnef-java.lang.String-}
```
public static MapiMessage loadFromTnef(String fileName)
```


Загружает сообщение из структуры данных Transport Neutral Encapsulation Format (TNEF)

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла, содержащего данные сообщения в формате TNEF |

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - A read [MapiMessage](../../com.aspose.email/mapimessage)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeAttachments(String path) {#removeAttachments-java.lang.String-}
```
public static MapiAttachmentCollection removeAttachments(String path)
```


Удаляет все вложения из указанных файлов Outlook Message.

--------------------

> The following exmaple demonstrates how to destroy attachments in Outlook Message files.
> 
> [Java]
> 
> ```
> //Remove attachments from Outlook Message files
>      MapiAttachmentCollection attachments = MapiMessage.removeAttachments("outlookmessage.msg");
> 
>      //Attachments
>      for(MapiAttachment att : attachments)
>      {
>         System.out.print("Attachment Name:"+att.getFileName());
>         att.save(att.getFileName());
>      }
> ```

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| путь | java.lang.String | Имя файла Outlook Message. |

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) - The attachments collection.
### removeProperty(long tag) {#removeProperty-long-}
```
public final void removeProperty(long tag)
```


Обеспечивает корректное удаление свойства из всех коллекций.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег MapiProperty. |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public final void save(OutputStream stream)
```


Сохраняет в указанный поток в формате Msg.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток. |

### save(OutputStream stream, SaveOptions options) {#save-java.io.OutputStream-com.aspose.email.SaveOptions-}
```
public final void save(OutputStream stream, SaveOptions options)
```


Сохраняет сообщение в виде потока с дополнительными параметрами.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток, в который сохраняется сообщение. |
| options | [SaveOptions](../../com.aspose.email/saveoptions) | Дополнительные параметры для сохранения[SaveOptions](../../com.aspose.email/saveoptions). |

### save(String fileName) {#save-java.lang.String-}
```
public final void save(String fileName)
```


Сохраняет в указанный файл в формате Msg.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |

### save(String fileName, SaveOptions options) {#save-java.lang.String-com.aspose.email.SaveOptions-}
```
public final void save(String fileName, SaveOptions options)
```


Сохраняет сообщение в файл с дополнительными параметрами.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Поток, в который сохраняется сообщение. |
| options | [SaveOptions](../../com.aspose.email/saveoptions) | Дополнительные параметры для сохранения[SaveOptions](../../com.aspose.email/saveoptions). |

### saveAsTemplate(OutputStream stream) {#saveAsTemplate-java.io.OutputStream-}
```
public final void saveAsTemplate(OutputStream stream)
```


Сохраняет в указанный поток в формате Outlook File Template (OFT).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток. |

### saveAsTemplate(String fileName) {#saveAsTemplate-java.lang.String-}
```
public final void saveAsTemplate(String fileName)
```


Сохраняет в указанный файл в формате Outlook File Template (OFT).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |

### saveAsTnef(OutputStream stream) {#saveAsTnef-java.io.OutputStream-}
```
public final void saveAsTnef(OutputStream stream)
```


Сохраняет сообщение в формате TNEF.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток, в который будет сохранено сообщение. |

### saveAsTnef(String fileName) {#saveAsTnef-java.lang.String-}
```
public final void saveAsTnef(String fileName)
```


Сохраняет сообщение в формате TNEF.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла, в который будет сохранено сообщение. |

### setBilling(String value) {#setBilling-java.lang.String-}
```
public final void setBilling(String value)
```


Содержит информацию о выставлении счета, связанную с элементом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


Получает текст сообщения.

Значение: Строка, представляющая тело сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setBodyContent(String content, int contentType) {#setBodyContent-java.lang.String-int-}
```
public void setBodyContent(String content, int contentType)
```


Устанавливает содержимое тела.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| content | java.lang.String | Содержимое. |
|  | contentType | int | Тип содержимого. |

--------------------

Предназначено для установки содержимого основного сообщения в форматах RTF, HTML или Plain Text. При установке значения также обновляются значения свойств PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY. Обратите внимание, после установки значения в формате HTML свойство BodyRtf возвращает значение, закодированное в RTF. |

### setBodyContent(String content, int contentType, boolean compression) {#setBodyContent-java.lang.String-int-boolean-}
```
public void setBodyContent(String content, int contentType, boolean compression)
```


Устанавливает содержимое тела.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| content | java.lang.String | Содержимое. |
| contentType | int | Тип содержимого. |
|  | compression | boolean | Указывает, что содержимое должно быть сжато. |

--------------------

Предназначено для установки содержимого основного сообщения в форматах RTF, HTML или Plain Text. При установке значения также обновляются значения свойств PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY. Обратите внимание, после установки значения в формате HTML свойство BodyRtf возвращает значение, закодированное в RTF. |

### setBodyRtf(String value) {#setBodyRtf-java.lang.String-}
```
public final void setBodyRtf(String value)
```


Получает или задает текст сообщения в формате RTF.

Значение: Строка, представляющая тело сообщения в формате rtf.

--------------------

При установке значения обновляются свойства PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY. Устанавливаемое строковое значение должно иметь формат RTF. Поэтому, если необходимо задать значение в формате HTML, его сначала нужно закодировать в RTF в соответствии со спецификацией RTF Extensions. Чтобы быстро задать содержимое тела сообщения в форматах HTML или обычного текста, используйте метод SetBodyContent. При установке null или пустой строки свойства BodyRtf и Body устанавливаются в null.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setBodyRtf(String value, boolean compression) {#setBodyRtf-java.lang.String-boolean-}
```
public final void setBodyRtf(String value, boolean compression)
```


Получает или задает текст сообщения в формате RTF.

Значение: Строка, представляющая тело сообщения в формате rtf.

--------------------

При установке значения обновляются свойства PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY. Устанавливаемое строковое значение должно иметь формат RTF. Поэтому, если необходимо задать значение в формате HTML, его сначала нужно закодировать в RTF в соответствии со спецификацией RTF Extensions. Чтобы быстро задать содержимое тела сообщения в форматах HTML или обычного текста, используйте метод SetBodyContent. При установке null или пустой строки свойства BodyRtf и Body устанавливаются в null.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
| compression | boolean | Указывает, что содержимое должно быть сжато. |

### setCategories(String[] value) {#setCategories-java.lang.String---}
```
public final void setCategories(String[] value)
```


Содержит ключевые слова или категории для объекта сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setClientSubmitTime(Date value) {#setClientSubmitTime-java.util.Date-}
```
public final void setClientSubmitTime(Date value)
```


Получает или задаёт дату и время отправки сообщения отправителем.

Значение: DateTime, представляющий время отправки клиентом.

--------------------

Если свойство недоступно, возвращается DateTime.MinValue.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setCompanies(String[] value) {#setCompanies-java.lang.String---}
```
public final void setCompanies(String[] value)
```


Содержит названия компаний, связанных с элементом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setDeliveryTime(Date value) {#setDeliveryTime-java.util.Date-}
```
public final void setDeliveryTime(Date value)
```


Получает или задает дату и время доставки сообщения.

Значение: DateTime, представляющий время доставки.

--------------------

Если свойство недоступно, возвращается DateTime.MinValue.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setHeaders(HeaderCollection value) {#setHeaders-com.aspose.email.HeaderCollection-}
```
public final void setHeaders(HeaderCollection value)
```


Получает заголовки транспортного сообщения

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [HeaderCollection](../../com.aspose.email/headercollection) |  |

### setMessageClass(String value) {#setMessageClass-java.lang.String-}
```
public final void setMessageClass(String value)
```


Возвращает чувствительную к регистру строку, идентифицирующую определённый отправителем класс сообщения, например IPM.Note. Класс сообщения указывает тип, назначение или содержание сообщения.

Значение: Строка, представляющая класс сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setMessageFlags(long flags) {#setMessageFlags-long-}
```
public final void setMessageFlags(long flags)
```


Устанавливает флаги сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| flags | long | Флаги сообщения. |

### setMileage(String value) {#setMileage-java.lang.String-}
```
public final void setMileage(String value)
```


Содержит информацию о пробеге, связанную с элементом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setNamedPropertyMapping(MapiNamedPropertyMappingStorage value) {#setNamedPropertyMapping-com.aspose.email.MapiNamedPropertyMappingStorage-}
```
public final void setNamedPropertyMapping(MapiNamedPropertyMappingStorage value)
```


Устанавливает сопоставление именованных свойств.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage) | Эта MapiNamedPropertyMappingStorage. |

### setProperty(MapiAttachment value, long signed, long key) {#setProperty-com.aspose.email.MapiAttachment-long-long-}
```
public void setProperty(MapiAttachment value, long signed, long key)
```


Устанавливает вложение.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MapiAttachment](../../com.aspose.email/mapiattachment) | Значение свойства. |
| подписано | long | Значение, указывающее, что свойство подписано. |
| ключ | long | Тег свойства. |

### setProperty(MapiProperty value) {#setProperty-com.aspose.email.MapiProperty-}
```
public void setProperty(MapiProperty value)
```


Устанавливает свойство.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) | Свойство. |

### setProperty(MapiRecipient value, long signed, long key) {#setProperty-com.aspose.email.MapiRecipient-long-long-}
```
public void setProperty(MapiRecipient value, long signed, long key)
```


Устанавливает получателя.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MapiRecipient](../../com.aspose.email/mapirecipient) | Значение свойства. |
| подписано | long | Значение, указывающее, что свойство подписано. |
| ключ | long | Тег свойства. |

### setProperty(PropertyDescriptor pd, Object value) {#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-}
```
public void setProperty(PropertyDescriptor pd, Object value)
```


Устанавливает свойство MAPI.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | Дескриптор свойства. |
| value | java.lang.Object | Данные свойства. |

### setReadReceiptRequested(boolean value) {#setReadReceiptRequested-boolean-}
```
public final void setReadReceiptRequested(boolean value)
```


Получает или задает значение, указывающее, запрашивается ли подтверждение о прочтении.

Значение: true, если запрошено подтверждение о прочтении; иначе false.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setRecipients(MapiRecipientCollection value) {#setRecipients-com.aspose.email.MapiRecipientCollection-}
```
public final void setRecipients(MapiRecipientCollection value)
```


Получает получателей сообщения.

Значение: Коллекция получателей.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) |  |

### setReplyTo(String value) {#setReplyTo-java.lang.String-}
```
public final void setReplyTo(String value)
```


Получает или задает имена получателей ответа.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setSenderEmailAddress(String value) {#setSenderEmailAddress-java.lang.String-}
```
public final void setSenderEmailAddress(String value)
```


Получает или задает электронный адрес отправителя сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setSenderName(String value) {#setSenderName-java.lang.String-}
```
public final void setSenderName(String value)
```


Получает или задает отображаемое имя отправителя сообщения.

Значение: строка, представляющая имя отправителя.

--------------------

При установке null или пустой строки значения свойства принимают значение, равное SenderEmailAddress.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setSenderSmtpAddress(String value) {#setSenderSmtpAddress-java.lang.String-}
```
public final void setSenderSmtpAddress(String value)
```


Получает или задает электронный адрес отправителя сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setSensitivity(int value) {#setSensitivity-int-}
```
public final void setSensitivity(int value)
```


Gets the Sensitivity.

Значение: Чувствительность.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setSentRepresentingEmailAddress(String value) {#setSentRepresentingEmailAddress-java.lang.String-}
```
public final void setSentRepresentingEmailAddress(String value)
```


Получает или задает электронный адрес для пользователя сообщений, представленного отправителем.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setSentRepresentingName(String value) {#setSentRepresentingName-java.lang.String-}
```
public final void setSentRepresentingName(String value)
```


Получает или задает отображаемое имя для пользователя сообщений, представленного отправителем.

Значение: Строка, представляющая отправляющее имя.

--------------------

При установке нулевого значения или пустой строки значения свойства задаются в SentRepresentingEmailAddress.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setStringPropertyValue(long tag, String value) {#setStringPropertyValue-long-java.lang.String-}
```
public final void setStringPropertyValue(long tag, String value)
```


Устанавливает значение строкового свойства.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства. |
| value | java.lang.String | Значение свойства. |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Получает или задает тему сообщения.

Значение: Строка, представляющая тему сообщения.

--------------------

При установке значения также обновляются значения свойств SubjectPrefix(PR\_SUBJECT\_PREFIX) и NormalizedSubject(PR\_NORMALIZED\_SUBJECT). Если у Subject нет префикса, значение свойства SubjectPrefix устанавливается в null. При установке значения null или пустой строки значения свойств Subject, SubjectPrefix, NormalizedSubject устанавливаются в null.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### toMailMessage(MailConversionOptions options) {#toMailMessage-com.aspose.email.MailConversionOptions-}
```
public final MailMessage toMailMessage(MailConversionOptions options)
```


Создаёт экземпляр MailMessage из этого MapiMessage.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| options | [MailConversionOptions](../../com.aspose.email/mailconversionoptions) | Позволяет указать дополнительные параметры при преобразовании из MapiMessage в MailMessage. |

**Returns:**
[MailMessage](../../com.aspose.email/mailmessage) - Returns a MailMessage instance which is loaded from this MapiMessage.
### toMapiMessageItem() {#toMapiMessageItem--}
```
public final IMapiMessageItem toMapiMessageItem()
```


Преобразует MapiMessage в объект IMapiMessageItem в зависимости от MessageClass.

**Returns:**
[IMapiMessageItem](../../com.aspose.email/imapimessageitem) - The IMapiMessageItem interface.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryGetPropertyData(long tag) {#tryGetPropertyData-long-}
```
public final byte[] tryGetPropertyData(long tag)
```


Попробуйте получить данные свойства с указанным ключом тега.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Ключ тега. |

**Returns:**
byte[] — Данные свойства.
### tryGetPropertyDateTime(long tag, Date[] value) {#tryGetPropertyDateTime-long-java.util.Date---}
```
public final boolean tryGetPropertyDateTime(long tag, Date[] value)
```


Получает значение указанного свойства как тип DateTime. Возвращаемое значение указывает, удалось ли выполнить операцию.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства MAPI. |
| value | java.util.Date[] | При возврате этого метода содержит значение указанного свойства, если свойство существует. Этот параметр передаётся неинициализированным. |

**Returns:**
boolean - true, если s был успешно преобразован; иначе false.
### tryGetPropertyInt32(long tag, int[] value) {#tryGetPropertyInt32-long-int---}
```
public final boolean tryGetPropertyInt32(long tag, int[] value)
```


Получает значение указанного свойства как тип Int32. Возвращаемое значение указывает, удалось ли выполнить операцию.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства MAPI. |
| value | int[] | При возврате этого метода содержит значение указанного свойства, если свойство существует. Этот параметр передаётся неинициализированным. |

**Returns:**
boolean - true, если s был успешно преобразован; иначе false.
### tryGetPropertyLong(long tag, long[] value) {#tryGetPropertyLong-long-long---}
```
public final boolean tryGetPropertyLong(long tag, long[] value)
```


Получает значение указанного свойства как тип Long. Возвращаемое значение указывает, удалось ли выполнить операцию.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства MAPI. |
| value | long[] | При возврате этого метода содержит значение указанного свойства, если свойство существует. Этот параметр передаётся неинициализированным. |

**Returns:**
boolean - true, если s был успешно преобразован; иначе false.
### tryGetPropertyString(long tag) {#tryGetPropertyString-long-}
```
public final String tryGetPropertyString(long tag)
```


Попробуйте получить данные свойства в виде строки с указанным тегом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Ключ тега свойства. |

**Returns:**
java.lang.String — строка, содержащая данные свойства.
### tryGetPropertyString(long tag, int codepage) {#tryGetPropertyString-long-int-}
```
public final String tryGetPropertyString(long tag, int codepage)
```


Попробуйте получить данные свойства в виде строки с указанным тегом и кодовой страницей.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Ключ тега свойства. |
| кодовая страница | int | Кодовая страница. |

**Returns:**
java.lang.String — строка, содержащая данные свойства.
### tryGetPropertyString(long tag, String[] value) {#tryGetPropertyString-long-java.lang.String---}
```
public final boolean tryGetPropertyString(long tag, String[] value)
```


Получает значение указанного свойства как тип String. Возвращаемое значение указывает, удалось ли выполнить операцию.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства MAPI. |
| value | java.lang.String[] | При возврате этого метода содержит значение указанного свойства, если свойство существует. Этот параметр передаётся неинициализированным. |

**Returns:**
boolean - true, если s был успешно преобразован; иначе false.
### tryGetPropertyString(long tag, String[] value, int codepage) {#tryGetPropertyString-long-java.lang.String---int-}
```
public final boolean tryGetPropertyString(long tag, String[] value, int codepage)
```


Получает значение указанного свойства как тип String. Возвращаемое значение указывает, удалось ли выполнить операцию.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства MAPI. |
| value | java.lang.String[] | При возврате этого метода содержит значение указанного свойства, если свойство существует. Этот параметр передаётся неинициализированным. |
| кодовая страница | int | Указанная кодовая страница, используемая для получения строкового значения. |

**Returns:**
boolean - true, если s был успешно преобразован; иначе false.
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

