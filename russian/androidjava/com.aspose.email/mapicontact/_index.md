---
title: MapiContact
second_title: Aspose.Email for Android via Java API Reference
description: Представляет информацию о контакте Outlook
type: docs
weight: 233
url: /ru/androidjava/com.aspose.email/mapicontact/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer), [com.aspose.email.MapiMessageItemBase](../../com.aspose.email/mapimessageitembase)
```
public final class MapiContact extends MapiMessageItemBase
```

Представляет информацию о контакте Outlook
## Constructors

| Constructor | Описание |
| --- | --- |
| [MapiContact()](#MapiContact--) | Инициализирует новый экземпляр класса [MapiContact](../../com.aspose.email/mapicontact) |
| [MapiContact(String displayName, String electonicAddress)](#MapiContact-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса [MapiContact](../../com.aspose.email/mapicontact). |
| [MapiContact(String displayName, String electonicAddress, String companyName)](#MapiContact-java.lang.String-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса [MapiContact](../../com.aspose.email/mapicontact). |
| [MapiContact(String displayName, String electonicAddress, String companyName, String primaryTelephoneNumber)](#MapiContact-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса [MapiContact](../../com.aspose.email/mapicontact). |
## Methods

| Method | Описание |
| --- | --- |
| [close()](#close--) |  |
| [createMapiNode(String key)](#createMapiNode-java.lang.String-) | Создает узел mapi. |
| [dispose()](#dispose--) | Выполняет задачи, определённые приложением, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromVCard(InputStream stream)](#fromVCard-java.io.InputStream-) | Читает [MapiContact](../../com.aspose.email/mapicontact) из указанного потока, содержащего vCard. |
| [fromVCard(InputStream stream, Charset encoding)](#fromVCard-java.io.InputStream-java.nio.charset.Charset-) | Читает [MapiContact](../../com.aspose.email/mapicontact) из указанного потока, содержащего vCard. |
| [fromVCard(String filePath)](#fromVCard-java.lang.String-) | Читает [MapiContact](../../com.aspose.email/mapicontact) из указанного файла vCard. Поддерживаемые версии vCard: 2.1 и 3.0 |
| [fromVCard(String filePath, Charset encoding)](#fromVCard-java.lang.String-java.nio.charset.Charset-) | Читает [MapiContact](../../com.aspose.email/mapicontact) из указанного файла vCard. Поддерживаемые версии vCard: 2.1 и 3.0 |
| [getAttachments()](#getAttachments--) | Получает вложения в сообщении. |
| [getBilling()](#getBilling--) | Содержит информацию о выставлении счета, связанную с элементом. |
| [getBody()](#getBody--) | Получает текст сообщения. |
| [getBodyHtml()](#getBodyHtml--) | Получает BodyRtf (\#getBodyRtf.getBodyRtf/\#setBodyRtf(String).setBodyRtf(String)) сообщения, преобразованного в HTML, если присутствует, иначе пустую строку. |
| [getBodyRtf()](#getBodyRtf--) | Получает или задает текст сообщения в формате RTF. |
| [getBodyType()](#getBodyType--) | Получает тип тела. |
| [getCategories()](#getCategories--) | Содержит ключевые слова или категории для объекта сообщения. |
| [getClass()](#getClass--) |  |
| [getCodePage()](#getCodePage--) | Получает кодовую страницу. |
| [getCompanies()](#getCompanies--) | Содержит названия компаний, связанных с элементом. |
| [getElectronicAddresses()](#getElectronicAddresses--) | Укажите свойства для до трёх разных адресов электронной почты и трёх разных факсовых адресов. |
| [getEvents()](#getEvents--) | Указывает события, связанные с контактом |
| [getItemId()](#getItemId--) | Используется для указания идентификатора сервера контакта только в EWS. |
| [getMessageClass()](#getMessageClass--) | Получает чувствительную к регистру строку, идентифицирующую пользовательский класс сообщения, например IPM.Note. |
| [getMileage()](#getMileage--) | Содержит информацию о пробеге, связанную с элементом. |
| [getNameInfo()](#getNameInfo--) | Свойства используются для указания имени лица, представленного контактом |
| [getNamedProperties()](#getNamedProperties--) | Получает именованные свойства сообщения. |
| [getNamedPropertyMapping()](#getNamedPropertyMapping--) | Получает сопоставление именованных свойств. |
| [getOtherFields()](#getOtherFields--) | Укажите другие поля контакта. |
| [getPersonalInfo()](#getPersonalInfo--) | Укажите другую дополнительную информацию о контакте |
| [getPhoto()](#getPhoto--) | Содержит фотографию контакта[MapiContactPhoto](../../com.aspose.email/mapicontactphoto). |
| [getPhysicalAddresses()](#getPhysicalAddresses--) | Укажите три физических адреса: домашний адрес, рабочий адрес и другой адрес. |
| [getProfessionalInfo()](#getProfessionalInfo--) | Свойства используются для хранения профессиональных данных о лице, представленном контактом. |
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
| [getTelephones()](#getTelephones--) | Укажите телефонные номера для контакта. |
| [getUnderlyingMessage()](#getUnderlyingMessage--) | Получите объект MapiMessage, представляющий контакт. |
| [hashCode()](#hashCode--) |  |
| [isStoreUnicodeOk()](#isStoreUnicodeOk--) | Определяет, закодированы ли строковые свойства в Unicode. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(long tag)](#removeProperty-long-) | Обеспечивает корректное удаление свойства из всех коллекций. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Сохраняет этот [MapiContact](../../com.aspose.email/mapicontact) в указанный поток в формате vCard. |
| [save(OutputStream stream, ContactSaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.email.ContactSaveOptions-) | Сохраняет этот [MapiContact](../../com.aspose.email/mapicontact) в указанный поток, используя заданные параметры сохранения. |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | Сохраняет этот [MapiContact](../../com.aspose.email/mapicontact) в указанный поток в формате, используя параметры по умолчанию. |
| [save(String filePath)](#save-java.lang.String-) | Сохраняет этот [MapiContact](../../com.aspose.email/mapicontact) в файл vCard с параметрами по умолчанию. |
| [save(String filePath, ContactSaveOptions saveOptions)](#save-java.lang.String-com.aspose.email.ContactSaveOptions-) | Сохраняет этот [MapiContact](../../com.aspose.email/mapicontact) в файл, используя заданные параметры сохранения. |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | Сохраняет этот [MapiContact](../../com.aspose.email/mapicontact) в указанный файл в формате, используя параметры по умолчанию. |
| [setBilling(String value)](#setBilling-java.lang.String-) | Содержит информацию о выставлении счета, связанную с элементом. |
| [setBody(String value)](#setBody-java.lang.String-) | Получает текст сообщения. |
| [setBodyContent(String content, int contentType)](#setBodyContent-java.lang.String-int-) | Устанавливает содержимое тела. |
| [setBodyContent(String content, int contentType, boolean compression)](#setBodyContent-java.lang.String-int-boolean-) | Устанавливает содержимое тела. |
| [setBodyRtf(String value)](#setBodyRtf-java.lang.String-) | Получает или задает текст сообщения в формате RTF. |
| [setBodyRtf(String value, boolean compression)](#setBodyRtf-java.lang.String-boolean-) | Получает или задает текст сообщения в формате RTF. |
| [setCategories(String[] value)](#setCategories-java.lang.String---) | Содержит ключевые слова или категории для объекта сообщения. |
| [setCompanies(String[] value)](#setCompanies-java.lang.String---) | Содержит названия компаний, связанных с элементом. |
| [setElectronicAddresses(MapiContactElectronicAddressPropertySet value)](#setElectronicAddresses-com.aspose.email.MapiContactElectronicAddressPropertySet-) | Укажите свойства для до трёх разных адресов электронной почты и трёх разных факсовых адресов. |
| [setEvents(MapiContactEventPropertySet value)](#setEvents-com.aspose.email.MapiContactEventPropertySet-) | Указывает события, связанные с контактом |
| [setMessageClass(String value)](#setMessageClass-java.lang.String-) | Получает чувствительную к регистру строку, идентифицирующую пользовательский класс сообщения, например IPM.Note. |
| [setMessageFlags(long flags)](#setMessageFlags-long-) | Устанавливает флаги сообщения. |
| [setMileage(String value)](#setMileage-java.lang.String-) | Содержит информацию о пробеге, связанную с элементом. |
| [setNameInfo(MapiContactNamePropertySet value)](#setNameInfo-com.aspose.email.MapiContactNamePropertySet-) | Свойства используются для указания имени лица, представленного контактом |
| [setNamedPropertyMapping(MapiNamedPropertyMappingStorage value)](#setNamedPropertyMapping-com.aspose.email.MapiNamedPropertyMappingStorage-) | Устанавливает сопоставление именованных свойств. |
| [setOtherFields(MapiContactOtherPropertySet value)](#setOtherFields-com.aspose.email.MapiContactOtherPropertySet-) | Укажите другие поля контакта. |
| [setPersonalInfo(MapiContactPersonalInfoPropertySet value)](#setPersonalInfo-com.aspose.email.MapiContactPersonalInfoPropertySet-) | Укажите другую дополнительную информацию о контакте |
| [setPhoto(MapiContactPhoto value)](#setPhoto-com.aspose.email.MapiContactPhoto-) | Содержит фотографию контакта[MapiContactPhoto](../../com.aspose.email/mapicontactphoto). |
| [setPhysicalAddresses(MapiContactPhysicalAddressPropertySet value)](#setPhysicalAddresses-com.aspose.email.MapiContactPhysicalAddressPropertySet-) | Укажите три физических адреса: домашний адрес, рабочий адрес и другой адрес. |
| [setProfessionalInfo(MapiContactProfessionalPropertySet value)](#setProfessionalInfo-com.aspose.email.MapiContactProfessionalPropertySet-) | Свойства используются для хранения профессиональных данных о лице, представленном контактом. |
| [setProperty(MapiProperty value)](#setProperty-com.aspose.email.MapiProperty-) | Устанавливает свойство. |
| [setProperty(PropertyDescriptor pd, Object value)](#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-) | Устанавливает свойство MAPI. |
| [setRecipients(MapiRecipientCollection value)](#setRecipients-com.aspose.email.MapiRecipientCollection-) | Получает получателей сообщения. |
| [setSensitivity(int value)](#setSensitivity-int-) | Gets the Sensitivity. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Получает или задает тему сообщения. |
| [setTelephones(MapiContactTelephonePropertySet value)](#setTelephones-com.aspose.email.MapiContactTelephonePropertySet-) | Укажите телефонные номера для контакта. |
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
### MapiContact() {#MapiContact--}
```
public MapiContact()
```


Инициализирует новый экземпляр класса [MapiContact](../../com.aspose.email/mapicontact)

### MapiContact(String displayName, String electonicAddress) {#MapiContact-java.lang.String-java.lang.String-}
```
public MapiContact(String displayName, String electonicAddress)
```


Инициализирует новый экземпляр класса [MapiContact](../../com.aspose.email/mapicontact).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| displayName | java.lang.String | The display name. |
| electonicAddress | java.lang.String | Электронный адрес. |

### MapiContact(String displayName, String electonicAddress, String companyName) {#MapiContact-java.lang.String-java.lang.String-java.lang.String-}
```
public MapiContact(String displayName, String electonicAddress, String companyName)
```


Инициализирует новый экземпляр класса [MapiContact](../../com.aspose.email/mapicontact).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| displayName | java.lang.String | The display name. |
| electonicAddress | java.lang.String | Электронный адрес. |
| companyName | java.lang.String | Название компании. |

### MapiContact(String displayName, String electonicAddress, String companyName, String primaryTelephoneNumber) {#MapiContact-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public MapiContact(String displayName, String electonicAddress, String companyName, String primaryTelephoneNumber)
```


Инициализирует новый экземпляр класса [MapiContact](../../com.aspose.email/mapicontact).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| displayName | java.lang.String | The display name. |
| electonicAddress | java.lang.String | Электронный адрес. |
| companyName | java.lang.String | Название компании. |
| primaryTelephoneNumber | java.lang.String | Телефонный номер. |

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
### fromVCard(InputStream stream) {#fromVCard-java.io.InputStream-}
```
public static MapiContact fromVCard(InputStream stream)
```


Читает [MapiContact](../../com.aspose.email/mapicontact) из указанного потока, содержащего vCard. Поддерживаемые версии vCard: 2.1 и 3.0

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток для чтения |

**Returns:**
[MapiContact](../../com.aspose.email/mapicontact) - A read [MapiContact](../../com.aspose.email/mapicontact)
### fromVCard(InputStream stream, Charset encoding) {#fromVCard-java.io.InputStream-java.nio.charset.Charset-}
```
public static MapiContact fromVCard(InputStream stream, Charset encoding)
```


Читает [MapiContact](../../com.aspose.email/mapicontact) из указанного потока, содержащего vCard. Поддерживаемые версии vCard: 2.1 и 3.0

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток для чтения |
| кодировка | java.nio.charset.Charset | Кодировка данных потока |

**Returns:**
[MapiContact](../../com.aspose.email/mapicontact) - A read [MapiContact](../../com.aspose.email/mapicontact)
### fromVCard(String filePath) {#fromVCard-java.lang.String-}
```
public static MapiContact fromVCard(String filePath)
```


Читает [MapiContact](../../com.aspose.email/mapicontact) из указанного файла vCard. Поддерживаемые версии vCard: 2.1 и 3.0

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Имя файла для чтения |

**Returns:**
[MapiContact](../../com.aspose.email/mapicontact) - A read [MapiContact](../../com.aspose.email/mapicontact)
### fromVCard(String filePath, Charset encoding) {#fromVCard-java.lang.String-java.nio.charset.Charset-}
```
public static MapiContact fromVCard(String filePath, Charset encoding)
```


Читает [MapiContact](../../com.aspose.email/mapicontact) из указанного файла vCard. Поддерживаемые версии vCard: 2.1 и 3.0

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Имя файла для чтения |
| кодировка | java.nio.charset.Charset | Кодировка данных файла |

**Returns:**
[MapiContact](../../com.aspose.email/mapicontact) - A read [MapiContact](../../com.aspose.email/mapicontact)
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
### getCompanies() {#getCompanies--}
```
public final String[] getCompanies()
```


Содержит названия компаний, связанных с элементом.

**Returns:**
java.lang.String[]
### getElectronicAddresses() {#getElectronicAddresses--}
```
public final MapiContactElectronicAddressPropertySet getElectronicAddresses()
```


Укажите свойства для до трёх разных адресов электронной почты и трёх разных факсовых адресов.

**Returns:**
[MapiContactElectronicAddressPropertySet](../../com.aspose.email/mapicontactelectronicaddresspropertyset)
### getEvents() {#getEvents--}
```
public final MapiContactEventPropertySet getEvents()
```


Указывает события, связанные с контактом

**Returns:**
[MapiContactEventPropertySet](../../com.aspose.email/mapicontacteventpropertyset)
### getItemId() {#getItemId--}
```
public final String getItemId()
```


Используется для указания идентификатора сервера контакта только в EWS.

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
### getNameInfo() {#getNameInfo--}
```
public final MapiContactNamePropertySet getNameInfo()
```


Свойства используются для указания имени лица, представленного контактом

**Returns:**
[MapiContactNamePropertySet](../../com.aspose.email/mapicontactnamepropertyset)
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
### getOtherFields() {#getOtherFields--}
```
public final MapiContactOtherPropertySet getOtherFields()
```


Укажите другие поля контакта.

**Returns:**
[MapiContactOtherPropertySet](../../com.aspose.email/mapicontactotherpropertyset)
### getPersonalInfo() {#getPersonalInfo--}
```
public final MapiContactPersonalInfoPropertySet getPersonalInfo()
```


Укажите другую дополнительную информацию о контакте

**Returns:**
[MapiContactPersonalInfoPropertySet](../../com.aspose.email/mapicontactpersonalinfopropertyset)
### getPhoto() {#getPhoto--}
```
public final MapiContactPhoto getPhoto()
```


Содержит фотографию контакта[MapiContactPhoto](../../com.aspose.email/mapicontactphoto).

**Returns:**
[MapiContactPhoto](../../com.aspose.email/mapicontactphoto)
### getPhysicalAddresses() {#getPhysicalAddresses--}
```
public final MapiContactPhysicalAddressPropertySet getPhysicalAddresses()
```


Укажите три физических адреса: Home Address, Work Address и Other Address. Один из адресов может быть отмечен как Mailing Address

**Returns:**
[MapiContactPhysicalAddressPropertySet](../../com.aspose.email/mapicontactphysicaladdresspropertyset)
### getProfessionalInfo() {#getProfessionalInfo--}
```
public final MapiContactProfessionalPropertySet getProfessionalInfo()
```


Свойства используются для хранения профессиональных данных о лице, представленном контактом.

**Returns:**
[MapiContactProfessionalPropertySet](../../com.aspose.email/mapicontactprofessionalpropertyset)
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
### getTelephones() {#getTelephones--}
```
public final MapiContactTelephonePropertySet getTelephones()
```


Укажите телефонные номера для контакта.

**Returns:**
[MapiContactTelephonePropertySet](../../com.aspose.email/mapicontacttelephonepropertyset)
### getUnderlyingMessage() {#getUnderlyingMessage--}
```
public final MapiMessage getUnderlyingMessage()
```


Получите объект MapiMessage, представляющий контакт.

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The [MapiMessage](../../com.aspose.email/mapimessage) object.
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

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public final void save(OutputStream stream)
```


Сохраняет этот [MapiContact](../../com.aspose.email/mapicontact) в указанный поток в формате vCard. Поддерживаемая версия vCard: 2.1.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток для сохранения |

### save(OutputStream stream, ContactSaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.email.ContactSaveOptions-}
```
public final void save(OutputStream stream, ContactSaveOptions saveOptions)
```


Сохраняет этот [MapiContact](../../com.aspose.email/mapicontact) в указанный поток, используя указанные параметры сохранения. Поддерживаемый параметр сохранения — [VCardSaveOptions](../../com.aspose.email/vcardsaveoptions).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток для сохранения |
| saveOptions | [ContactSaveOptions](../../com.aspose.email/contactsaveoptions) | Параметры сохранения |

### save(OutputStream stream, int saveFormat) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int saveFormat)
```


Сохраняет этот [MapiContact](../../com.aspose.email/mapicontact) в указанный поток в формате, используя параметры по умолчанию. Поддерживаемый формат сохранения — vCard.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток для сохранения |
| saveFormat | int | Формат сохранения |

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Сохраняет этот [MapiContact](../../com.aspose.email/mapicontact) в файл vCard с параметрами по умолчанию. Поддерживаемая версия vCard — 2.1.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Имя файла vCard |

### save(String filePath, ContactSaveOptions saveOptions) {#save-java.lang.String-com.aspose.email.ContactSaveOptions-}
```
public final void save(String filePath, ContactSaveOptions saveOptions)
```


Сохраняет этот [MapiContact](../../com.aspose.email/mapicontact) в файл, используя указанные параметры сохранения. Поддерживаемый параметр сохранения — [VCardSaveOptions](../../com.aspose.email/vcardsaveoptions).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Имя файла vCard |
| saveOptions | [ContactSaveOptions](../../com.aspose.email/contactsaveoptions) | Параметры сохранения |

### save(String filePath, int saveFormat) {#save-java.lang.String-int-}
```
public final void save(String filePath, int saveFormat)
```


Сохраняет этот [MapiContact](../../com.aspose.email/mapicontact) в указанный файл в формате, используя параметры по умолчанию. Поддерживаемый формат сохранения — vCard.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Имя файла vCard |
| saveFormat | int | Формат сохранения |

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

### setCompanies(String[] value) {#setCompanies-java.lang.String---}
```
public final void setCompanies(String[] value)
```


Содержит названия компаний, связанных с элементом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setElectronicAddresses(MapiContactElectronicAddressPropertySet value) {#setElectronicAddresses-com.aspose.email.MapiContactElectronicAddressPropertySet-}
```
public final void setElectronicAddresses(MapiContactElectronicAddressPropertySet value)
```


Укажите свойства для до трёх разных адресов электронной почты и трёх разных факсовых адресов.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MapiContactElectronicAddressPropertySet](../../com.aspose.email/mapicontactelectronicaddresspropertyset) |  |

### setEvents(MapiContactEventPropertySet value) {#setEvents-com.aspose.email.MapiContactEventPropertySet-}
```
public final void setEvents(MapiContactEventPropertySet value)
```


Указывает события, связанные с контактом

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MapiContactEventPropertySet](../../com.aspose.email/mapicontacteventpropertyset) |  |

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

### setNameInfo(MapiContactNamePropertySet value) {#setNameInfo-com.aspose.email.MapiContactNamePropertySet-}
```
public final void setNameInfo(MapiContactNamePropertySet value)
```


Свойства используются для указания имени лица, представленного контактом

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MapiContactNamePropertySet](../../com.aspose.email/mapicontactnamepropertyset) |  |

### setNamedPropertyMapping(MapiNamedPropertyMappingStorage value) {#setNamedPropertyMapping-com.aspose.email.MapiNamedPropertyMappingStorage-}
```
public final void setNamedPropertyMapping(MapiNamedPropertyMappingStorage value)
```


Устанавливает сопоставление именованных свойств.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage) | Эта MapiNamedPropertyMappingStorage. |

### setOtherFields(MapiContactOtherPropertySet value) {#setOtherFields-com.aspose.email.MapiContactOtherPropertySet-}
```
public final void setOtherFields(MapiContactOtherPropertySet value)
```


Укажите другие поля контакта.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MapiContactOtherPropertySet](../../com.aspose.email/mapicontactotherpropertyset) |  |

### setPersonalInfo(MapiContactPersonalInfoPropertySet value) {#setPersonalInfo-com.aspose.email.MapiContactPersonalInfoPropertySet-}
```
public final void setPersonalInfo(MapiContactPersonalInfoPropertySet value)
```


Укажите другую дополнительную информацию о контакте

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MapiContactPersonalInfoPropertySet](../../com.aspose.email/mapicontactpersonalinfopropertyset) |  |

### setPhoto(MapiContactPhoto value) {#setPhoto-com.aspose.email.MapiContactPhoto-}
```
public final void setPhoto(MapiContactPhoto value)
```


Содержит фотографию контакта[MapiContactPhoto](../../com.aspose.email/mapicontactphoto).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MapiContactPhoto](../../com.aspose.email/mapicontactphoto) |  |

### setPhysicalAddresses(MapiContactPhysicalAddressPropertySet value) {#setPhysicalAddresses-com.aspose.email.MapiContactPhysicalAddressPropertySet-}
```
public final void setPhysicalAddresses(MapiContactPhysicalAddressPropertySet value)
```


Укажите три физических адреса: Home Address, Work Address и Other Address. Один из адресов может быть отмечен как Mailing Address

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MapiContactPhysicalAddressPropertySet](../../com.aspose.email/mapicontactphysicaladdresspropertyset) |  |

### setProfessionalInfo(MapiContactProfessionalPropertySet value) {#setProfessionalInfo-com.aspose.email.MapiContactProfessionalPropertySet-}
```
public final void setProfessionalInfo(MapiContactProfessionalPropertySet value)
```


Свойства используются для хранения профессиональных данных о лице, представленном контактом.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MapiContactProfessionalPropertySet](../../com.aspose.email/mapicontactprofessionalpropertyset) |  |

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

### setTelephones(MapiContactTelephonePropertySet value) {#setTelephones-com.aspose.email.MapiContactTelephonePropertySet-}
```
public final void setTelephones(MapiContactTelephonePropertySet value)
```


Укажите телефонные номера для контакта.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [MapiContactTelephonePropertySet](../../com.aspose.email/mapicontacttelephonepropertyset) |  |

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

