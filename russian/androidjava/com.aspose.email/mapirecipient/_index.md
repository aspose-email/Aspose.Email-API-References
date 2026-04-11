---
title: MapiRecipient
second_title: Aspose.Email for Android via Java API Reference
description: Представляет информацию о получателе в сообщении Microsoft Outlook.
type: docs
weight: 278
url: /ru/androidjava/com.aspose.email/mapirecipient/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer)
```
public class MapiRecipient extends MapiPropertyContainer
```

Представляет информацию о получателе в сообщении Microsoft Outlook.
## Methods

| Method | Описание |
| --- | --- |
| [createMapiNode(String key)](#createMapiNode-java.lang.String-) | Создает узел mapi. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressType()](#getAddressType--) | Получает тип адреса получателя или отправителя сообщения. |
| [getClass()](#getClass--) |  |
| [getCodePage()](#getCodePage--) | Получает кодовую страницу. |
| [getContent()](#getContent--) | Получает содержимое. |
| [getDisplayName()](#getDisplayName--) | Получает или задает отображаемое имя получателя или отправителя сообщения. |
| [getEmailAddress()](#getEmailAddress--) | Получает или задает адрес электронной почты получателя или отправителя сообщения. |
| [getNamedProperties()](#getNamedProperties--) | Получает именованные свойства сообщения. |
| [getOrganizationEmailAddress()](#getOrganizationEmailAddress--) | Получает адрес электронной почты организации. |
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
| [getRecipientClass()](#getRecipientClass--) | Получает тип получателя. |
| [getRecipientTrackStatus()](#getRecipientTrackStatus--) | Статус ответа получателя на запрос встречи. |
| [getRecipientType()](#getRecipientType--) | Получает тип получателя или отправителя. |
| [getSubStorages()](#getSubStorages--) | Получает вложенные хранилища. |
| [hashCode()](#hashCode--) |  |
| [isStoreUnicodeOk()](#isStoreUnicodeOk--) | Определяет, закодированы ли строковые свойства в Unicode. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Получает или задает отображаемое имя получателя или отправителя сообщения. |
| [setEmailAddress(String value)](#setEmailAddress-java.lang.String-) | Получает или задает адрес электронной почты получателя или отправителя сообщения. |
| [setProperty(MapiProperty value)](#setProperty-com.aspose.email.MapiProperty-) | Устанавливает свойство. |
| [setProperty(PropertyDescriptor pd, Object value)](#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-) | Устанавливает свойство MAPI. |
| [setRecipientTrackStatus(int value)](#setRecipientTrackStatus-int-) | Статус ответа получателя на запрос встречи. |
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
### getAddressType() {#getAddressType--}
```
public final String getAddressType()
```


Получает тип адреса получателя или отправителя сообщения.

Значение: тип адреса.

--------------------

Это свойство указывает тип для свойства mapi PR\_EMAIL\_ADDRESS.

**Returns:**
java.lang.String
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
### getContent() {#getContent--}
```
public final Object getContent()
```


Получает содержимое.

Значение: Содержимое.

**Returns:**
java.lang.Object
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Получает или задает отображаемое имя получателя или отправителя сообщения.

Значение: Отображаемое имя.

--------------------

При установке значения также обновляются значения MapiMessage.DisplayTo, MapiMessage.DisplayBcc или MapiMessage.DisplayCC в зависимости от типа получателя.

**Returns:**
java.lang.String
### getEmailAddress() {#getEmailAddress--}
```
public final String getEmailAddress()
```


Получает или задает адрес электронной почты получателя или отправителя сообщения.

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
### getOrganizationEmailAddress() {#getOrganizationEmailAddress--}
```
public final String getOrganizationEmailAddress()
```


Получает адрес электронной почты организации.

Значение: адрес электронной почты организации.

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
### getRecipientClass() {#getRecipientClass--}
```
public final int getRecipientClass()
```


Получает тип получателя.

Значение: класс получателя.

**Returns:**
int
### getRecipientTrackStatus() {#getRecipientTrackStatus--}
```
public final int getRecipientTrackStatus()
```


Статус ответа получателя на запрос встречи.

**Returns:**
int
### getRecipientType() {#getRecipientType--}
```
public final int getRecipientType()
```


Получает тип получателя или отправителя.

Значение: тип получателя.

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




### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


Получает или задает отображаемое имя получателя или отправителя сообщения.

Значение: Отображаемое имя.

--------------------

При установке значения также обновляются значения MapiMessage.DisplayTo, MapiMessage.DisplayBcc или MapiMessage.DisplayCC в зависимости от типа получателя.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setEmailAddress(String value) {#setEmailAddress-java.lang.String-}
```
public final void setEmailAddress(String value)
```


Получает или задает адрес электронной почты получателя или отправителя сообщения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

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

### setRecipientTrackStatus(int value) {#setRecipientTrackStatus-int-}
```
public final void setRecipientTrackStatus(int value)
```


Статус ответа получателя на запрос встречи.

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

