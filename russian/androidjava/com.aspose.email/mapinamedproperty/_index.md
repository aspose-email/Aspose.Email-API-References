---
title: MapiNamedProperty
second_title: Aspose.Email for Android via Java API Reference
description: Представляет тип данных именованного свойства.
type: docs
weight: 266
url: /ru/androidjava/com.aspose.email/mapinamedproperty/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiProperty](../../com.aspose.email/mapiproperty)
```
public final class MapiNamedProperty extends MapiProperty
```

Представляет тип данных именованного свойства.
## Constructors

| Constructor | Описание |
| --- | --- |
| [MapiNamedProperty()](#MapiNamedProperty--) | Инициализирует новый экземпляр класса [MapiNamedProperty](../../com.aspose.email/mapinamedproperty). |
| [MapiNamedProperty(long propertyTag, String nameIdentifier, UUID propertyGuid, byte[] propertyValue)](#MapiNamedProperty-long-java.lang.String-java.util.UUID-byte---) | Инициализирует новый экземпляр класса [MapiNamedProperty](../../com.aspose.email/mapinamedproperty). |
| [MapiNamedProperty(long propertyTag, long nameIdentifier, UUID propertyGuid, byte[] propertyValue)](#MapiNamedProperty-long-long-java.util.UUID-byte---) | Инициализирует новый экземпляр класса [MapiNamedProperty](../../com.aspose.email/mapinamedproperty). |
| [MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidLidPropertyDescriptor pd, Object data)](#MapiNamedProperty-com.aspose.email.INamedPropertyTagProvider-com.aspose.email.PidLidPropertyDescriptor-java.lang.Object-) | Инициализирует новый экземпляр класса [MapiNamedProperty](../../com.aspose.email/mapinamedproperty). |
| [MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidNamePropertyDescriptor pd, Object data)](#MapiNamedProperty-com.aspose.email.INamedPropertyTagProvider-com.aspose.email.PidNamePropertyDescriptor-java.lang.Object-) | Инициализирует новый экземпляр класса [MapiNamedProperty](../../com.aspose.email/mapinamedproperty). |
## Methods

| Method | Описание |
| --- | --- |
| [createMapiPropertyFromBytes(long tag, byte[] data)](#createMapiPropertyFromBytes-long-byte---) | Создаёт свойство mapi из байтов. |
| [createMapiPropertyFromDateTime(long tag, Date data)](#createMapiPropertyFromDateTime-long-java.util.Date-) | Создаёт свойство mapi из даты и времени. |
| [createMapiPropertyFromLong(long tag, long data)](#createMapiPropertyFromLong-long-long-) | Создаёт свойство mapi из long. |
| [createMapiPropertyFromLong(long tag, long data, long delimiter)](#createMapiPropertyFromLong-long-long-long-) | Создаёт свойство mapi из long. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBoolean()](#getBoolean--) | Получает первые байты двоичных данных как boolean. |
| [getClass()](#getClass--) |  |
| [getCurrency()](#getCurrency--) | Получает валюту как строку, используя указанную кодовую страницу. |
| [getData()](#getData--) | Получает двоичные данные. |
| [getDataType()](#getDataType--) | Получает тип данных. |
| [getDateTime()](#getDateTime--) | Получает первые байты двоичных данных как datetime. |
| [getDescriptor()](#getDescriptor--) | Получает дескриптор свойства MAPI |
| [getDouble()](#getDouble--) | Получает байты двоичных данных как double. |
| [getFloat()](#getFloat--) | Получает байты двоичных данных как float. |
| [getFloatingDate()](#getFloatingDate--) | Получает байты двоичных данных как DateTime. |
| [getGuid()](#getGuid--) | получает именованное свойство GUID |
| [getGuidValue()](#getGuidValue--) | Получает байты двоичных данных как Guid. |
| [getIdentifier()](#getIdentifier--) | Получает идентификатор. |
| [getInt32()](#getInt32--) | Получает первые 4 байта двоичных данных как int32. |
| [getKind()](#getKind--) | получает тип именованного свойства |
| [getLong()](#getLong--) | Получает первые 8 байт двоичных данных как long. |
| [getMVEntries()](#getMVEntries--) | Получает список записей MV. |
| [getMultipleBinary()](#getMultipleBinary--) | Получает множественные двоичные данные. |
| [getMultipleBoolean()](#getMultipleBoolean--) | Получает множественные логические значения. |
| [getMultipleCurrency()](#getMultipleCurrency--) | Получает множественные десятичные значения. |
| [getMultipleFloating32()](#getMultipleFloating32--) | Получает множественные float значения. |
| [getMultipleFloating64()](#getMultipleFloating64--) | Получает множественные double значения. |
| [getMultipleFloatingTime()](#getMultipleFloatingTime--) | Получает множественные DateTime значения. |
| [getMultipleGuid()](#getMultipleGuid--) | Получает множественные Guid значения. |
| [getMultipleInteger16()](#getMultipleInteger16--) | Получает множественные Int16 значения. |
| [getMultipleInteger32()](#getMultipleInteger32--) | Получает множественные Int32 значения. |
| [getMultipleInteger64()](#getMultipleInteger64--) | Получает несколько значений Int64. |
| [getMultipleString()](#getMultipleString--) | Получает несколько строковых данных. |
| [getMultipleTime()](#getMultipleTime--) | Получает множественные DateTime значения. |
| [getName()](#getName--) | Получает имя. |
| [getNameId()](#getNameId--) | получает идентификатор именованного свойства |
| [getOom()](#getOom--) | получает значение OOM |
| [getPropertyTagName()](#getPropertyTagName--) | Получает PropertyName. |
| [getShort()](#getShort--) | Получает первые 2 байта бинарных данных как short. |
| [getString()](#getString--) | Получает бинарные данные как строку. |
| [getString(int codepage)](#getString-int-) | Получает бинарные данные как строку, используя указанную кодовую страницу. |
| [getTag()](#getTag--) | Получает тег. |
| [getValue()](#getValue--) | Получает значение как объект |
| [hashCode()](#hashCode--) |  |
| [isNamed()](#isNamed--) | Указывает, является ли свойство именованным. |
| [isSigned()](#isSigned--) | Указывает, подписаны ли бинарные данные. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setSigned(boolean value)](#setSigned-boolean-) | Указывает, подписаны ли бинарные данные. |
| [toString()](#toString--) | Возвращает String, представляющий текущий Object. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiNamedProperty() {#MapiNamedProperty--}
```
public MapiNamedProperty()
```


Инициализирует новый экземпляр класса [MapiNamedProperty](../../com.aspose.email/mapinamedproperty).

### MapiNamedProperty(long propertyTag, String nameIdentifier, UUID propertyGuid, byte[] propertyValue) {#MapiNamedProperty-long-java.lang.String-java.util.UUID-byte---}
```
public MapiNamedProperty(long propertyTag, String nameIdentifier, UUID propertyGuid, byte[] propertyValue)
```


Инициализирует новый экземпляр класса [MapiNamedProperty](../../com.aspose.email/mapinamedproperty).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| propertyTag | long | Тег свойства представляет 32-битное значение, содержащее тип свойства и идентификатор свойства. Низшие 16 бит представляют тип свойства. Старшие 16 бит представляют идентификатор свойства. |
| nameIdentifier | java.lang.String | Идентификатор имени, используемый для ссылки на именованное свойство. |
| propertyGuid | java.util.UUID | Уникальный идентификатор свойства. |
| propertyValue | byte[] | Значение свойства. |

### MapiNamedProperty(long propertyTag, long nameIdentifier, UUID propertyGuid, byte[] propertyValue) {#MapiNamedProperty-long-long-java.util.UUID-byte---}
```
public MapiNamedProperty(long propertyTag, long nameIdentifier, UUID propertyGuid, byte[] propertyValue)
```


Инициализирует новый экземпляр класса [MapiNamedProperty](../../com.aspose.email/mapinamedproperty).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| propertyTag | long | Тег свойства представляет 32-битное значение, содержащее тип свойства и идентификатор свойства. Низшие 16 бит представляют тип свойства. Старшие 16 бит представляют идентификатор свойства. |
| nameIdentifier | long | Идентификатор имени, используемый для ссылки на именованное свойство. |
| propertyGuid | java.util.UUID | Уникальный идентификатор свойства. |
| propertyValue | byte[] | Значение свойства. |

### MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidLidPropertyDescriptor pd, Object data) {#MapiNamedProperty-com.aspose.email.INamedPropertyTagProvider-com.aspose.email.PidLidPropertyDescriptor-java.lang.Object-}
```
public MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidLidPropertyDescriptor pd, Object data)
```


Инициализирует новый экземпляр класса [MapiNamedProperty](../../com.aspose.email/mapinamedproperty).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tagProvider | [INamedPropertyTagProvider](../../com.aspose.email/inamedpropertytagprovider) | Хранилище свойства, которое может предоставлять тег для именованного свойства |
| pd | [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) | Дескриптор свойства |
| данные | java.lang.Object | Значение свойства. |

### MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidNamePropertyDescriptor pd, Object data) {#MapiNamedProperty-com.aspose.email.INamedPropertyTagProvider-com.aspose.email.PidNamePropertyDescriptor-java.lang.Object-}
```
public MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidNamePropertyDescriptor pd, Object data)
```


Инициализирует новый экземпляр класса [MapiNamedProperty](../../com.aspose.email/mapinamedproperty).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tagProvider | [INamedPropertyTagProvider](../../com.aspose.email/inamedpropertytagprovider) | Хранилище свойства, которое может предоставлять тег для именованного свойства |
| pd | [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) | Дескриптор свойства |
| данные | java.lang.Object | Значение свойства. |

### createMapiPropertyFromBytes(long tag, byte[] data) {#createMapiPropertyFromBytes-long-byte---}
```
public static MapiProperty createMapiPropertyFromBytes(long tag, byte[] data)
```


Создаёт свойство mapi из байтов.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег. |
| данные | byte[] | Данные. |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - 
### createMapiPropertyFromDateTime(long tag, Date data) {#createMapiPropertyFromDateTime-long-java.util.Date-}
```
public static MapiProperty createMapiPropertyFromDateTime(long tag, Date data)
```


Создаёт свойство mapi из даты и времени.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег. |
| данные | java.util.Date | Данные. |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - 
### createMapiPropertyFromLong(long tag, long data) {#createMapiPropertyFromLong-long-long-}
```
public static MapiProperty createMapiPropertyFromLong(long tag, long data)
```


Создаёт свойство mapi из long.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег. |
| данные | long | Данные. |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - 
### createMapiPropertyFromLong(long tag, long data, long delimiter) {#createMapiPropertyFromLong-long-long-long-}
```
public static MapiProperty createMapiPropertyFromLong(long tag, long data, long delimiter)
```


Создаёт свойство mapi из long.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег. |
| данные | long | Данные. |
| delimiter | long | Разделитель. |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - 
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
### getBoolean() {#getBoolean--}
```
public boolean getBoolean()
```


Получает первые байты двоичных данных как boolean.

**Returns:**
boolean - Булевое значение.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCurrency() {#getCurrency--}
```
public BigDecimal getCurrency()
```


Получает валюту как строку, используя указанную кодовую страницу.

**Returns:**
java.math.BigDecimal - Строка, содержащая двоичные данные.
### getData() {#getData--}
```
public byte[] getData()
```


Получает двоичные данные.

**Returns:**
byte[]
### getDataType() {#getDataType--}
```
public int getDataType()
```


Получает тип данных.

**Returns:**
int
### getDateTime() {#getDateTime--}
```
public Date getDateTime()
```


Получает первые байты двоичных данных как datetime.

**Returns:**
java.util.Date - Значение даты и времени.
### getDescriptor() {#getDescriptor--}
```
public final PropertyDescriptor getDescriptor()
```


Получает дескриптор свойства MAPI

**Returns:**
[PropertyDescriptor](../../com.aspose.email/propertydescriptor)
### getDouble() {#getDouble--}
```
public double getDouble()
```


Получает байты двоичных данных как double.

**Returns:**
double - Значение double.
### getFloat() {#getFloat--}
```
public float getFloat()
```


Получает байты двоичных данных как float.

**Returns:**
float - Значение double.
### getFloatingDate() {#getFloatingDate--}
```
public Date getFloatingDate()
```


Получает байты двоичных данных как DateTime.

**Returns:**
java.util.Date - Значение DateTime.
### getGuid() {#getGuid--}
```
public final UUID getGuid()
```


получает именованное свойство GUID

**Returns:**
java.util.UUID
### getGuidValue() {#getGuidValue--}
```
public UUID getGuidValue()
```


Получает байты двоичных данных как Guid.

**Returns:**
java.util.UUID - Значение Guid.
### getIdentifier() {#getIdentifier--}
```
public long getIdentifier()
```


Получает идентификатор.

**Returns:**
long
### getInt32() {#getInt32--}
```
public int getInt32()
```


Получает первые 4 байта двоичных данных как int32.

**Returns:**
int - Значение int32.
### getKind() {#getKind--}
```
public final int getKind()
```


получает тип именованного свойства

**Returns:**
int
### getLong() {#getLong--}
```
public long getLong()
```


Получает первые 8 байт двоичных данных как long.

**Returns:**
long - Значение long.
### getMVEntries() {#getMVEntries--}
```
public final System.Collections.IList getMVEntries()
```


Получает список записей MV.

**Returns:**
com.aspose.ms.System.Collections.IList
### getMultipleBinary() {#getMultipleBinary--}
```
public final byte[][] getMultipleBinary()
```


Получает множественные двоичные данные.

**Returns:**
byte[][] - Несколько массивов байтов.
### getMultipleBoolean() {#getMultipleBoolean--}
```
public final boolean[] getMultipleBoolean()
```


Получает множественные логические значения.

**Returns:**
boolean[] - Массив логических значений.
### getMultipleCurrency() {#getMultipleCurrency--}
```
public final BigDecimal[] getMultipleCurrency()
```


Получает множественные десятичные значения.

**Returns:**
java.math.BigDecimal[] - Массив десятичных чисел.
### getMultipleFloating32() {#getMultipleFloating32--}
```
public final float[] getMultipleFloating32()
```


Получает множественные float значения.

**Returns:**
float[] - Массив float.
### getMultipleFloating64() {#getMultipleFloating64--}
```
public final double[] getMultipleFloating64()
```


Получает множественные double значения.

**Returns:**
double[] - Массив double.
### getMultipleFloatingTime() {#getMultipleFloatingTime--}
```
public final Date[] getMultipleFloatingTime()
```


Получает множественные DateTime значения.

**Returns:**
java.util.Date[] - Массив DateTime.
### getMultipleGuid() {#getMultipleGuid--}
```
public final UUID[] getMultipleGuid()
```


Получает множественные Guid значения.

**Returns:**
java.util.UUID[] - Массив Guid.
### getMultipleInteger16() {#getMultipleInteger16--}
```
public final short[] getMultipleInteger16()
```


Получает множественные Int16 значения.

**Returns:**
short[] - Массив Int16.
### getMultipleInteger32() {#getMultipleInteger32--}
```
public final int[] getMultipleInteger32()
```


Получает множественные Int32 значения.

**Returns:**
int[] - Массив Int32.
### getMultipleInteger64() {#getMultipleInteger64--}
```
public final long[] getMultipleInteger64()
```


Получает несколько значений Int64.

**Returns:**
long[] - Массив Int64.
### getMultipleString() {#getMultipleString--}
```
public final String[] getMultipleString()
```


Получает несколько строковых данных.

**Returns:**
java.lang.String[] - Массив строк.
### getMultipleTime() {#getMultipleTime--}
```
public final Date[] getMultipleTime()
```


Получает множественные DateTime значения.

**Returns:**
java.util.Date[] - Массив DateTime.
### getName() {#getName--}
```
public String getName()
```


Получает имя.

**Returns:**
java.lang.String
### getNameId() {#getNameId--}
```
public final String getNameId()
```


получает идентификатор именованного свойства

**Returns:**
java.lang.String
### getOom() {#getOom--}
```
public final String getOom()
```


получает значение OOM

**Returns:**
java.lang.String
### getPropertyTagName() {#getPropertyTagName--}
```
public String getPropertyTagName()
```


Получает PropertyName.

**Returns:**
java.lang.String
### getShort() {#getShort--}
```
public short getShort()
```


Получает первые 2 байта бинарных данных как short.

**Returns:**
short - Значение short.
### getString() {#getString--}
```
public String getString()
```


Получает бинарные данные как строку.

**Returns:**
java.lang.String - Строка, содержащая двоичные данные.
### getString(int codepage) {#getString-int-}
```
public String getString(int codepage)
```


Получает бинарные данные как строку, используя указанную кодовую страницу.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| кодовая страница | int | Кодовая страница. |

**Returns:**
java.lang.String - Строка, содержащая двоичные данные.
### getTag() {#getTag--}
```
public long getTag()
```


Получает тег.

**Returns:**
long
### getValue() {#getValue--}
```
public final Object getValue()
```


Получает значение как объект

**Returns:**
java.lang.Object - значение свойства
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isNamed() {#isNamed--}
```
public final boolean isNamed()
```


Указывает, является ли свойство именованным.

**Returns:**
boolean
### isSigned() {#isSigned--}
```
public boolean isSigned()
```


Указывает, подписаны ли бинарные данные.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setSigned(boolean value) {#setSigned-boolean-}
```
public void setSigned(boolean value)
```


Указывает, подписаны ли бинарные данные.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Возвращает String, представляющий текущий Object.

**Returns:**
java.lang.String - String, представляющий текущий Object.
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

