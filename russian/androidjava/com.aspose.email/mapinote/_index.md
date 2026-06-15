---
title: MapiNote
second_title: Aspose.Email for Android via Java API Reference
description: Представляет объект Outlook Note — липкую заметку
type: docs
weight: 268
url: /ru/androidjava/com.aspose.email/mapinote/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer), [com.aspose.email.MapiMessageItemBase](../../com.aspose.email/mapimessageitembase)
```
public final class MapiNote extends MapiMessageItemBase
```

Представляет объект заметки Outlook ("липкая заметка")
## Constructors

| Constructor | Описание |
| --- | --- |
| [MapiNote()](#MapiNote--) | Инициализирует новый экземпляр класса [MapiNote](../../com.aspose.email/mapinote). |
| [MapiNote(String subject, String body)](#MapiNote-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса [MapiNote](../../com.aspose.email/mapinote). |
## Methods

| Method | Описание |
| --- | --- |
| [close()](#close--) |  |
| [createMapiNode(String key)](#createMapiNode-java.lang.String-) | Создает узел mapi. |
| [dispose()](#dispose--) | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttachments()](#getAttachments--) | Получает вложения в сообщении. |
| [getBilling()](#getBilling--) | Содержит информацию о выставлении счета, связанную с элементом. |
| [getBody()](#getBody--) | Получает текст сообщения. |
| [getBodyHtml()](#getBodyHtml--) | Получает BodyRtf (\#getBodyRtf.getBodyRtf/\#setBodyRtf(String).setBodyRtf(String)) сообщения, преобразованного в HTML, если присутствует, иначе пустую строку. |
| [getBodyRtf()](#getBodyRtf--) | Получает или задает текст сообщения в формате RTF. |
| [getBodyType()](#getBodyType--) | Получает тип тела. |
| [getCategories()](#getCategories--) | Содержит ключевые слова или категории для объекта сообщения. |
| [getClass()](#getClass--) |  |
| [getCodePage()](#getCodePage--) | Получает кодовую страницу. |
| [getColor()](#getColor--) | Получает или задает предлагаемый цвет фона объекта Note |
| [getCompanies()](#getCompanies--) | Содержит названия компаний, связанных с элементом. |
| [getCreationDate()](#getCreationDate--) | Получает или задает дату создания заметки |
| [getHeight()](#getHeight--) | Получает или задает высоту видимого окна сообщения в пикселях |
| [getItemId()](#getItemId--) | Идентификатор элемента, используется с сервером. |
| [getMessageClass()](#getMessageClass--) | Получает чувствительную к регистру строку, идентифицирующую пользовательский класс сообщения, например IPM.Note. |
| [getMileage()](#getMileage--) | Содержит информацию о пробеге, связанную с элементом. |
| [getNamedProperties()](#getNamedProperties--) | Получает именованные свойства сообщения. |
| [getNamedPropertyMapping()](#getNamedPropertyMapping--) | Получает сопоставление именованных свойств. |
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
| [getRecipients()](#getRecipients--) | Получает получателей сообщения. |
| [getSensitivity()](#getSensitivity--) | Gets the Sensitivity. |
| [getSubStorages()](#getSubStorages--) | Получает вложенные хранилища. |
| [getSubject()](#getSubject--) | Получает или задает тему сообщения. |
| [getSubjectPrefix()](#getSubjectPrefix--) | Получает префикс темы, который обычно указывает на действие с сообщением, например \"FW: \" для пересылки. |
| [getWidth()](#getWidth--) | Получает или задает ширину видимого окна сообщения в пикселях |
| [getXPosition()](#getXPosition--) | Получает или задает расстояние в пикселях от левого края экрана, где пользовательский интерфейс отображает объект Note |
| [getYPosition()](#getYPosition--) | Получает или задает расстояние в пикселях от верхнего края экрана, где пользовательский интерфейс отображает объект Note |
| [hashCode()](#hashCode--) |  |
| [isStoreUnicodeOk()](#isStoreUnicodeOk--) | Определяет, закодированы ли строковые свойства в Unicode. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(long tag)](#removeProperty-long-) | Обеспечивает корректное удаление свойства из всех коллекций. |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | Сохраняет этот [MapiNote](../../com.aspose.email/mapinote) в указанный поток, используя заданный формат. |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | Сохраняет этот [MapiNote](../../com.aspose.email/mapinote) в файл, используя заданный формат. |
| [setBilling(String value)](#setBilling-java.lang.String-) | Содержит информацию о выставлении счета, связанную с элементом. |
| [setBody(String value)](#setBody-java.lang.String-) | Получает текст сообщения. |
| [setBodyContent(String content, int contentType)](#setBodyContent-java.lang.String-int-) | Устанавливает содержимое тела. |
| [setBodyContent(String content, int contentType, boolean compression)](#setBodyContent-java.lang.String-int-boolean-) | Устанавливает содержимое тела. |
| [setBodyRtf(String value)](#setBodyRtf-java.lang.String-) | Получает или задает текст сообщения в формате RTF. |
| [setBodyRtf(String value, boolean compression)](#setBodyRtf-java.lang.String-boolean-) | Получает или задает текст сообщения в формате RTF. |
| [setCategories(String[] value)](#setCategories-java.lang.String---) | Содержит ключевые слова или категории для объекта сообщения. |
| [setColor(int value)](#setColor-int-) | Получает или задает предлагаемый цвет фона объекта Note |
| [setCompanies(String[] value)](#setCompanies-java.lang.String---) | Содержит названия компаний, связанных с элементом. |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | Получает или задает дату создания заметки |
| [setHeight(int value)](#setHeight-int-) | Получает или задает высоту видимого окна сообщения в пикселях |
| [setMessageClass(String value)](#setMessageClass-java.lang.String-) | Получает чувствительную к регистру строку, идентифицирующую пользовательский класс сообщения, например IPM.Note. |
| [setMessageFlags(long flags)](#setMessageFlags-long-) | Устанавливает флаги сообщения. |
| [setMileage(String value)](#setMileage-java.lang.String-) | Содержит информацию о пробеге, связанную с элементом. |
| [setNamedPropertyMapping(MapiNamedPropertyMappingStorage value)](#setNamedPropertyMapping-com.aspose.email.MapiNamedPropertyMappingStorage-) | Устанавливает сопоставление именованных свойств. |
| [setProperty(MapiProperty value)](#setProperty-com.aspose.email.MapiProperty-) | Устанавливает свойство. |
| [setProperty(PropertyDescriptor pd, Object value)](#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-) | Устанавливает свойство MAPI. |
| [setRecipients(MapiRecipientCollection value)](#setRecipients-com.aspose.email.MapiRecipientCollection-) | Получает получателей сообщения. |
| [setSensitivity(int value)](#setSensitivity-int-) | Gets the Sensitivity. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Получает или задает тему сообщения. |
| [setWidth(int value)](#setWidth-int-) | Получает или задает ширину видимого окна сообщения в пикселях |
| [setXPosition(int value)](#setXPosition-int-) | Получает или задает расстояние в пикселях от левого края экрана, где пользовательский интерфейс отображает объект Note |
| [setYPosition(int value)](#setYPosition-int-) | Получает или задает расстояние в пикселях от верхнего края экрана, где пользовательский интерфейс отображает объект Note |
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
### MapiNote() {#MapiNote--}
```
public MapiNote()
```


Инициализирует новый экземпляр класса [MapiNote](../../com.aspose.email/mapinote).

### MapiNote(String subject, String body) {#MapiNote-java.lang.String-java.lang.String-}
```
public MapiNote(String subject, String body)
```


Инициализирует новый экземпляр класса [MapiNote](../../com.aspose.email/mapinote).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| тема | java.lang.String | Тема сообщения. |
| тело | java.lang.String | Тело сообщения. |

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
public String getBody()
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
### getCodePage() {#getCodePage--}
```
public int getCodePage()
```


Получает кодовую страницу.

Значение: Кодовая страница.

**Returns:**
int
### getColor() {#getColor--}
```
public final int getColor()
```


Получает или задает предлагаемый цвет фона объекта Note

**Returns:**
int
### getCompanies() {#getCompanies--}
```
public final String[] getCompanies()
```


Содержит названия компаний, связанных с элементом.

**Returns:**
java.lang.String[]
### getCreationDate() {#getCreationDate--}
```
public final Date getCreationDate()
```


Получает или задает дату создания заметки

**Returns:**
java.util.Date
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Получает или задает высоту видимого окна сообщения в пикселях

**Returns:**
int
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
### getRecipients() {#getRecipients--}
```
public final MapiRecipientCollection getRecipients()
```


Получает получателей сообщения.

Значение: Коллекция получателей.

**Returns:**
[MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection)
### getSensitivity() {#getSensitivity--}
```
public final int getSensitivity()
```


Gets the Sensitivity.

Значение: Чувствительность.

**Returns:**
int
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
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Получает или задает ширину видимого окна сообщения в пикселях

**Returns:**
int
### getXPosition() {#getXPosition--}
```
public final int getXPosition()
```


Получает или задает расстояние в пикселях от левого края экрана, где пользовательский интерфейс отображает объект Note

**Returns:**
int
### getYPosition() {#getYPosition--}
```
public final int getYPosition()
```


Получает или задает расстояние в пикселях от верхнего края экрана, где пользовательский интерфейс отображает объект Note

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isStoreUnicodeOk() {#isStoreUnicodeOk--}
```
public final boolean isStoreUnicodeOk()
```


Определяет, закодированы ли строковые свойства в Unicode.

**Returns:**
boolean — True, если строковые свойства закодированы в Unicode.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeProperty(long tag) {#removeProperty-long-}
```
public final void removeProperty(long tag)
```


Обеспечивает корректное удаление свойства из всех коллекций.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег MapiProperty. |

### save(OutputStream stream, int saveFormat) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int saveFormat)
```


Сохраняет этот [MapiNote](../../com.aspose.email/mapinote) в указанный поток, используя заданный формат.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream |  |
| saveFormat | int |  |

### save(String filePath, int saveFormat) {#save-java.lang.String-int-}
```
public final void save(String filePath, int saveFormat)
```


Сохраняет этот [MapiNote](../../com.aspose.email/mapinote) в файл, используя заданный формат.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveFormat | int |  |

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
public void setBody(String value)
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

### setColor(int value) {#setColor-int-}
```
public final void setColor(int value)
```


Получает или задает предлагаемый цвет фона объекта Note

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setCompanies(String[] value) {#setCompanies-java.lang.String---}
```
public final void setCompanies(String[] value)
```


Содержит названия компаний, связанных с элементом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public final void setCreationDate(Date value)
```


Получает или задает дату создания заметки

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Получает или задает высоту видимого окна сообщения в пикселях

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

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

### setProperty(MapiProperty value) {#setProperty-com.aspose.email.MapiProperty-}
```
public void setProperty(MapiProperty value)
```


Устанавливает свойство.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) | Свойство. |

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

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Получает или задает ширину видимого окна сообщения в пикселях

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setXPosition(int value) {#setXPosition-int-}
```
public final void setXPosition(int value)
```


Получает или задает расстояние в пикселях от левого края экрана, где пользовательский интерфейс отображает объект Note

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setYPosition(int value) {#setYPosition-int-}
```
public final void setYPosition(int value)
```


Получает или задает расстояние в пикселях от верхнего края экрана, где пользовательский интерфейс отображает объект Note

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

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

