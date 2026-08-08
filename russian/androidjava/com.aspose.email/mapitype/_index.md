---
title: MapiType
second_title: Aspose.Email for Android via Java API Reference
description: Содержит возможные типы свойств MAPI, которые могут быть сохранены вместе с объектом сообщения.
type: docs
weight: 294
url: /ru/androidjava/com.aspose.email/mapitype/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class MapiType extends System.Enum
```

Содержит возможные типы свойств MAPI, которые могут быть сохранены вместе с объектом сообщения.
## Constructors

| Constructor | Описание |
| --- | --- |
| [MapiType()](#MapiType--) | Конструктор для MapiType. |
## Поля

| Поле | Описание |
| --- | --- |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [None](#None) | Значения не заданы. |
| [PT_APPTIME](#PT-APPTIME) | 8 байт, 64-битное число с плавающей запятой, где целая часть представляет количество дней, прошедших с 30 декабря 1899 года, а дробная часть — долю дня с полуночи. |
| [PT_BINARY](#PT-BINARY) | Переменного размера массив байтов |
| [PT_BOOLEAN](#PT-BOOLEAN) | 1 байт, ограничен значениями 1 или 0 |
| [PT_CLSID](#PT-CLSID) | 16 байт, GUID с полями Data1, Data2 и Data3 в формате little-endian |
| [PT_CURRENCY](#PT-CURRENCY) | 8 байт, 64‑битное знаковое масштабируемое целое представление десятичного денежного значения с 4 знаками после запятой |
| [PT_DOUBLE](#PT-DOUBLE) | 8 байт, 64‑битное число с плавающей запятой |
| [PT_ERROR](#PT-ERROR) | 4 байта, 32‑битное целое, кодирующее информацию об ошибке |
| [PT_FLOAT](#PT-FLOAT) | 4 байта, 32‑битное число с плавающей запятой |
| [PT_LONG](#PT-LONG) | 4 байта, 32‑битное целое |
| [PT_LONGLONG](#PT-LONGLONG) | 8 байт, 64‑битное целое |
| [PT_MV_APPTIME](#PT-MV-APPTIME) | Переменный размер, набор значений [PT\_APPTIME](../../com.aspose.email/mapitype\#PT-APPTIME). |
| [PT_MV_BINARY](#PT-MV-BINARY) | Переменный размер, набор значений [PT\_BINARY](../../com.aspose.email/mapitype\#PT-BINARY). |
| [PT_MV_CLSID](#PT-MV-CLSID) | Переменный размер, набор значений [PT\_CLSID](../../com.aspose.email/mapitype\#PT-CLSID). |
| [PT_MV_CURRENCY](#PT-MV-CURRENCY) | Переменный размер, набор значений [PT\_CURRENCY](../../com.aspose.email/mapitype\#PT-CURRENCY). |
| [PT_MV_DOUBLE](#PT-MV-DOUBLE) | Переменный размер, набор значений [PT\_DOUBLE](../../com.aspose.email/mapitype\#PT-DOUBLE). |
| [PT_MV_FLOAT](#PT-MV-FLOAT) | Переменный размер, набор значений [PT\_FLOAT](../../com.aspose.email/mapitype\#PT-FLOAT). |
| [PT_MV_LONG](#PT-MV-LONG) | Переменный размер, набор значений [PT\_LONG](../../com.aspose.email/mapitype\#PT-LONG). |
| [PT_MV_LONGLONG](#PT-MV-LONGLONG) | Переменный размер, набор значений [PT\_LONGLONG](../../com.aspose.email/mapitype\#PT-LONGLONG). |
| [PT_MV_SHORT](#PT-MV-SHORT) | Переменный размер, набор значений [PT\_SHORT](../../com.aspose.email/mapitype\#PT-SHORT). |
| [PT_MV_STRING8](#PT-MV-STRING8) | Переменный размер, набор значений [PT\_STRING8](../../com.aspose.email/mapitype\#PT-STRING8). |
| [PT_MV_SYSTIME](#PT-MV-SYSTIME) | Переменный размер, набор значений [PT\_SYSTIME](../../com.aspose.email/mapitype\#PT-SYSTIME). |
| [PT_MV_UNICODE](#PT-MV-UNICODE) | Переменный размер, набор значений [PT\_UNICODE](../../com.aspose.email/mapitype\#PT-UNICODE). |
| [PT_OBJECT](#PT-OBJECT) | Значение свойства является объектом COM |
| [PT_SHORT](#PT-SHORT) | 2 байта, 16‑битное целое |
| [PT_STRING8](#PT-STRING8) | Переменный размер, строка из многобайтовых символов во внешне заданной кодировке с завершающим нулевым символом (один байт 0). |
| [PT_SYSTIME](#PT-SYSTIME) | 8 байт, 64‑битное целое, представляющее количество интервалов по 100 наносекунд, прошедших с 1 января 1601 года |
| [PT_UNICODE](#PT-UNICODE) | Переменный размер, строка из символов Unicode в кодировке UTF-16LE с завершающим нулевым символом (0x0000) |
## Methods

| Method | Описание |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(System.Enum arg0)](#CloneTo-com.aspose.ms.System.Enum-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [format(System.Type arg0, Object arg1, String arg2)](#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-) |  |
| [format(Class<?> arg0, long arg1, String arg2)](#format-java.lang.Class----long-java.lang.String-) |  |
| [getClass()](#getClass--) |  |
| [getName(System.Type arg0, Object arg1)](#getName-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [getName(Class<?> arg0, long arg1)](#getName-java.lang.Class----long-) |  |
| [getNames(System.Type arg0)](#getNames-com.aspose.ms.System.Type-) |  |
| [getNames(Class<?> arg0)](#getNames-java.lang.Class----) |  |
| [getUnderlyingType(System.Type arg0)](#getUnderlyingType-com.aspose.ms.System.Type-) |  |
| [getUnderlyingType(Class<?> arg0)](#getUnderlyingType-java.lang.Class----) |  |
| [getValue(Class<?> arg0, String arg1)](#getValue-java.lang.Class----java.lang.String-) |  |
| [getValues(System.Type arg0)](#getValues-com.aspose.ms.System.Type-) |  |
| [get_Caption()](#get-Caption--) |  |
| [get_Value()](#get-Value--) |  |
| [hashCode()](#hashCode--) |  |
| [isDefined(System.Type arg0, Object arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [isDefined(System.Type arg0, String arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.String-) |  |
| [isDefined(System.Type arg0, long arg1)](#isDefined-com.aspose.ms.System.Type-long-) |  |
| [isDefined(Class<?> arg0, long arg1)](#isDefined-java.lang.Class----long-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(System.Type arg0, String arg1)](#parse-com.aspose.ms.System.Type-java.lang.String-) |  |
| [parse(System.Type arg0, String arg1, Boolean arg2)](#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-) |  |
| [parse(Class<?> arg0, String arg1)](#parse-java.lang.Class----java.lang.String-) |  |
| [parse(Class<?> arg0, String arg1, Boolean arg2)](#parse-java.lang.Class----java.lang.String-java.lang.Boolean-) |  |
| [register(System.Enum.AbstractEnum arg0)](#register-com.aspose.ms.System.Enum.AbstractEnum-) |  |
| [toObject(System.Type arg0, Object arg1)](#toObject-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [toString()](#toString--) |  |
| [toString(Class<?> arg0, long arg1)](#toString-java.lang.Class----long-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiType() {#MapiType--}
```
public MapiType()
```


Конструктор для MapiType.

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### None {#None}
```
public static final int None
```


Значения не заданы.

### PT_APPTIME {#PT-APPTIME}
```
public static final int PT_APPTIME
```


8 байт, 64-битное число с плавающей запятой, где целая часть представляет количество дней, прошедших с 30 декабря 1899 года, а дробная часть — долю дня с полуночи.

### PT_BINARY {#PT-BINARY}
```
public static final int PT_BINARY
```


Переменного размера массив байтов

### PT_BOOLEAN {#PT-BOOLEAN}
```
public static final int PT_BOOLEAN
```


1 байт, ограничен значениями 1 или 0

### PT_CLSID {#PT-CLSID}
```
public static final int PT_CLSID
```


16 байт, GUID с полями Data1, Data2 и Data3 в формате little-endian

### PT_CURRENCY {#PT-CURRENCY}
```
public static final int PT_CURRENCY
```


8 байт, 64‑битное знаковое масштабируемое целое представление десятичного денежного значения с 4 знаками после запятой

### PT_DOUBLE {#PT-DOUBLE}
```
public static final int PT_DOUBLE
```


8 байт, 64‑битное число с плавающей запятой

### PT_ERROR {#PT-ERROR}
```
public static final int PT_ERROR
```


4 байта, 32‑битное целое, кодирующее информацию об ошибке

### PT_FLOAT {#PT-FLOAT}
```
public static final int PT_FLOAT
```


4 байта, 32‑битное число с плавающей запятой

### PT_LONG {#PT-LONG}
```
public static final int PT_LONG
```


4 байта, 32‑битное целое

### PT_LONGLONG {#PT-LONGLONG}
```
public static final int PT_LONGLONG
```


8 байт, 64‑битное целое

### PT_MV_APPTIME {#PT-MV-APPTIME}
```
public static final int PT_MV_APPTIME
```


Переменный размер, набор значений [PT\_APPTIME](../../com.aspose.email/mapitype\#PT-APPTIME).

### PT_MV_BINARY {#PT-MV-BINARY}
```
public static final int PT_MV_BINARY
```


Переменный размер, набор значений [PT\_BINARY](../../com.aspose.email/mapitype\#PT-BINARY).

### PT_MV_CLSID {#PT-MV-CLSID}
```
public static final int PT_MV_CLSID
```


Переменный размер, набор значений [PT\_CLSID](../../com.aspose.email/mapitype\#PT-CLSID).

### PT_MV_CURRENCY {#PT-MV-CURRENCY}
```
public static final int PT_MV_CURRENCY
```


Переменный размер, набор значений [PT\_CURRENCY](../../com.aspose.email/mapitype\#PT-CURRENCY).

### PT_MV_DOUBLE {#PT-MV-DOUBLE}
```
public static final int PT_MV_DOUBLE
```


Переменный размер, набор значений [PT\_DOUBLE](../../com.aspose.email/mapitype\#PT-DOUBLE).

### PT_MV_FLOAT {#PT-MV-FLOAT}
```
public static final int PT_MV_FLOAT
```


Переменный размер, набор значений [PT\_FLOAT](../../com.aspose.email/mapitype\#PT-FLOAT).

### PT_MV_LONG {#PT-MV-LONG}
```
public static final int PT_MV_LONG
```


Переменный размер, набор значений [PT\_LONG](../../com.aspose.email/mapitype\#PT-LONG).

### PT_MV_LONGLONG {#PT-MV-LONGLONG}
```
public static final int PT_MV_LONGLONG
```


Переменный размер, набор значений [PT\_LONGLONG](../../com.aspose.email/mapitype\#PT-LONGLONG).

### PT_MV_SHORT {#PT-MV-SHORT}
```
public static final int PT_MV_SHORT
```


Переменный размер, набор значений [PT\_SHORT](../../com.aspose.email/mapitype\#PT-SHORT).

### PT_MV_STRING8 {#PT-MV-STRING8}
```
public static final int PT_MV_STRING8
```


Переменный размер, набор значений [PT\_STRING8](../../com.aspose.email/mapitype\#PT-STRING8).

### PT_MV_SYSTIME {#PT-MV-SYSTIME}
```
public static final int PT_MV_SYSTIME
```


Переменный размер, набор значений [PT\_SYSTIME](../../com.aspose.email/mapitype\#PT-SYSTIME).

### PT_MV_UNICODE {#PT-MV-UNICODE}
```
public static final int PT_MV_UNICODE
```


Переменный размер, набор значений [PT\_UNICODE](../../com.aspose.email/mapitype\#PT-UNICODE).

### PT_OBJECT {#PT-OBJECT}
```
public static final int PT_OBJECT
```


Значение свойства является объектом COM

### PT_SHORT {#PT-SHORT}
```
public static final int PT_SHORT
```


2 байта, 16‑битное целое

### PT_STRING8 {#PT-STRING8}
```
public static final int PT_STRING8
```


Переменный размер, строка из многобайтовых символов во внешне заданной кодировке с завершающим нулевым символом (один байт 0).

### PT_SYSTIME {#PT-SYSTIME}
```
public static final int PT_SYSTIME
```


8 байт, 64‑битное целое, представляющее количество интервалов по 100 наносекунд, прошедших с 1 января 1601 года

### PT_UNICODE {#PT-UNICODE}
```
public static final int PT_UNICODE
```


Переменный размер, строка из символов Unicode в кодировке UTF-16LE с завершающим нулевым символом (0x0000)

### Clone() {#Clone--}
```
public System.Enum Clone()
```




**Returns:**
com.aspose.ms.System.Enum
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum |  |

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
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### format(Class<?> arg0, long arg1, String arg2) {#format-java.lang.Class----long-java.lang.String-}
```
public static String format(Class<?> arg0, long arg1, String arg2)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getName(System.Type arg0, Object arg1) {#getName-com.aspose.ms.System.Type-java.lang.Object-}
```
public static String getName(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.String
### getName(Class<?> arg0, long arg1) {#getName-java.lang.Class----long-}
```
public static String getName(Class<?> arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
java.lang.String
### getNames(System.Type arg0) {#getNames-com.aspose.ms.System.Type-}
```
public static String[] getNames(System.Type arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### getValues(System.Type arg0) {#getValues-com.aspose.ms.System.Type-}
```
public static System.Array getValues(System.Type arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Array
### get_Caption() {#get-Caption--}
```
public String get_Caption()
```




**Returns:**
java.lang.String
### get_Value() {#get-Value--}
```
public long get_Value()
```




**Returns:**
long
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDefined(System.Type arg0, Object arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.Object-}
```
public static boolean isDefined(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
boolean
### isDefined(System.Type arg0, String arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
boolean
### isDefined(System.Type arg0, long arg1) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | long |  |

**Returns:**
boolean
### isDefined(Class<?> arg0, long arg1) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

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




### parse(System.Type arg0, String arg1) {#parse-com.aspose.ms.System.Type-java.lang.String-}
```
public static long parse(System.Type arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(System.Type arg0, String arg1, Boolean arg2) {#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-}
```
public static long parse(System.Type arg0, String arg1, Boolean arg2)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1) {#parse-java.lang.Class----java.lang.String-}
```
public static long parse(Class<?> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1, Boolean arg2) {#parse-java.lang.Class----java.lang.String-java.lang.Boolean-}
```
public static long parse(Class<?> arg0, String arg1, Boolean arg2)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### register(System.Enum.AbstractEnum arg0) {#register-com.aspose.ms.System.Enum.AbstractEnum-}
```
public static void register(System.Enum.AbstractEnum arg0)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toString(Class<?> arg0, long arg1) {#toString-java.lang.Class----long-}
```
public static String toString(Class<?> arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

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

