---
title: MapiProperty
second_title: Aspose.Email for Android via Java API Reference
description: Представляет свойство MAPI.
type: docs
weight: 271
url: /ru/androidjava/com.aspose.email/mapiproperty/
---

**Inheritance:**
java.lang.Object
```
public class MapiProperty
```

Представляет свойство MAPI.
## Constructors

| Constructor | Описание |
| --- | --- |
| [MapiProperty(long tag, byte[] data)](#MapiProperty-long-byte---) | Инициализирует новый экземпляр класса MapiProperty. |
| [MapiProperty(long tag)](#MapiProperty-long-) | Инициализирует новый экземпляр класса MapiProperty. |
| [MapiProperty(PidTagPropertyDescriptor pd, Object data)](#MapiProperty-com.aspose.email.PidTagPropertyDescriptor-java.lang.Object-) | Инициализирует новый экземпляр класса MapiProperty. |
| [MapiProperty(PidLidPropertyDescriptor pd, Object data)](#MapiProperty-com.aspose.email.PidLidPropertyDescriptor-java.lang.Object-) | Инициализирует новый экземпляр класса MapiProperty. |
| [MapiProperty(long tag, Iterable<?> values)](#MapiProperty-long-java.lang.Iterable----) | Инициализирует новый экземпляр класса [MapiProperty](../../com.aspose.email/mapiproperty). |
| [MapiProperty(long tag, long signedParam, byte[] data)](#MapiProperty-long-long-byte---) | Инициализирует новый экземпляр класса [MapiProperty](../../com.aspose.email/mapiproperty). |
| [MapiProperty(String name, long tag, long signedParam, byte[] data)](#MapiProperty-java.lang.String-long-long-byte---) | Инициализирует новый экземпляр класса MapiProperty. |
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
| [getGuidValue()](#getGuidValue--) | Получает байты двоичных данных как Guid. |
| [getIdentifier()](#getIdentifier--) | Получает идентификатор. |
| [getInt32()](#getInt32--) | Получает первые 4 байта двоичных данных как int32. |
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
### MapiProperty(long tag, byte[] data) {#MapiProperty-long-byte---}
```
public MapiProperty(long tag, byte[] data)
```


Инициализирует новый экземпляр класса MapiProperty.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Ключ тега свойства. |
| данные | byte[] | Бинарные данные свойства. |

### MapiProperty(long tag) {#MapiProperty-long-}
```
public MapiProperty(long tag)
```


Инициализирует новый экземпляр класса MapiProperty.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Ключ тега свойства. |

### MapiProperty(PidTagPropertyDescriptor pd, Object data) {#MapiProperty-com.aspose.email.PidTagPropertyDescriptor-java.lang.Object-}
```
public MapiProperty(PidTagPropertyDescriptor pd, Object data)
```


Инициализирует новый экземпляр класса MapiProperty.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| pd | [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) | Дескриптор свойства |
| данные | java.lang.Object | Данные свойства. |

### MapiProperty(PidLidPropertyDescriptor pd, Object data) {#MapiProperty-com.aspose.email.PidLidPropertyDescriptor-java.lang.Object-}
```
public MapiProperty(PidLidPropertyDescriptor pd, Object data)
```


Инициализирует новый экземпляр класса MapiProperty.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| pd | [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) | Дескриптор свойства |
| данные | java.lang.Object | Данные свойства. |

### MapiProperty(long tag, Iterable<?> values) {#MapiProperty-long-java.lang.Iterable----}
```
public MapiProperty(long tag, Iterable<?> values)
```


Инициализирует новый экземпляр класса [MapiProperty](../../com.aspose.email/mapiproperty). Эта перегрузка используется для создания многозначного свойства, PT\_MV\_\*.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства. |
| значения | java.lang.Iterable<?> | Значения. |

### MapiProperty(long tag, long signedParam, byte[] data) {#MapiProperty-long-long-byte---}
```
public MapiProperty(long tag, long signedParam, byte[] data)
```


Инициализирует новый экземпляр класса [MapiProperty](../../com.aspose.email/mapiproperty).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства. |
| signedParam | long | Подписано. |
| данные | byte[] | Данные свойства. |

### MapiProperty(String name, long tag, long signedParam, byte[] data) {#MapiProperty-java.lang.String-long-long-byte---}
```
public MapiProperty(String name, long tag, long signedParam, byte[] data)
```


Инициализирует новый экземпляр класса MapiProperty.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя. |
| tag | long | Ключ тега свойства. |
| signedParam | long | Указывает, подписаны данные или нет. |
| данные | byte[] | Бинарные данные свойства. |

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

