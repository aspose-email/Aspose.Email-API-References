---
title: PropertyDataType
second_title: Aspose.Email for Android via Java API Reference
description: Структуры данных MS-OXCDATA
type: docs
weight: 358
url: /ru/androidjava/com.aspose.email/propertydatatype/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PropertyDataType extends System.Enum
```

[MS-OXCDATA]: Data Structures
## Поля

| Поле | Описание |
| --- | --- |
| [Binary](#Binary) | Переменный размер; поле COUNT, за которым следует указанное количество байтов. |
| [Boolean](#Boolean) | 1 байт; ограничено значениями 1 или 0. Название спецификации: PtypBoolean; Альтернативные имена: PT\_BOOLEAN. |
| [Currency](#Currency) | 8 байт; 64‑битное знаковое масштабируемое целое представление десятичного валютного значения с четырьмя знаками после запятой. Название спецификации: PtypCurrency; Альтернативные имена: PT\_CURRENCY, fixed.14.4; |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [ErrorCode](#ErrorCode) | 4 байта; 32‑битное целое, кодирующее информацию об ошибке. Название спецификации: PtypErrorCode; Альтернативные имена: PT\_ERROR; |
| [Floating32](#Floating32) | 4 байта; 32‑битное число с плавающей точкой. Название спецификации: PtypFloating32; Альтернативные имена: PT\_FLOAT, PT\_R4, float, r4; |
| [Floating64](#Floating64) | 8 байт; 64‑битное число с плавающей точкой. Название спецификации: PtypFloating64; Альтернативные имена: PT\_DOUBLE, PT\_R8, r8; |
| [FloatingTime](#FloatingTime) | 8 байт; 64‑битное число с плавающей точкой, где целая часть представляет количество дней, прошедших с 30 декабря 1899 года, а дробная часть — долю дня с полуночи. Название спецификации: PtypFloatingTime; Альтернативные имена: PT\_APPTIME; Информация о дате представлена целыми увеличениями, начиная с полуночи 30 декабря 1899 года как нулевого времени. |
| [Guid](#Guid) | 16 байт; GUID с полями Data1, Data2 и Data3 в формате little-endian. Название спецификации: PtypGuid; Альтернативные имена: PT\_CLSID, UUID; |
| [Integer16](#Integer16) | 2 байта; 16‑битное целое. Название спецификации: PtypInteger16; Альтернативные имена: PT\_SHORT, PT\_I2, i2, ui2; |
| [Integer32](#Integer32) | 4 байта; 32‑битное целое. Название спецификации: PtypInteger32; Альтернативные имена: PT\_LONG, PT\_I4, int, ui4; |
| [Integer64](#Integer64) | 8 байт; 64‑битное целое число. Имя спецификации: PtypInteger64; Альтернативные имена: PT\_LONGLONG, PT\_I8, i8, ui8; |
| [MultipleBinary](#MultipleBinary) | Переменного размера; поле COUNT, за которым следует указанное количество значений PtypBinary. |
| [MultipleBoolean](#MultipleBoolean) | Переменного размера; поле COUNT, за которым следует указанное количество значений PtypBoolean. |
| [MultipleCurrency](#MultipleCurrency) | Переменного размера; поле COUNT, за которым следует указанное количество значений PtypCurrency. |
| [MultipleFloating32](#MultipleFloating32) | Переменного размера; поле COUNT, за которым следует указанное количество значений PtypFloating32. |
| [MultipleFloating64](#MultipleFloating64) | Переменного размера; поле COUNT, за которым следует указанное количество значений PtypFloating64. |
| [MultipleFloatingTime](#MultipleFloatingTime) | Переменного размера; поле COUNT, за которым следует указанное количество значений PtypFloatingTime. |
| [MultipleGuid](#MultipleGuid) | Переменного размера; поле COUNT, за которым следует указанное количество значений PtypGuid. |
| [MultipleInteger16](#MultipleInteger16) | Переменного размера; поле COUNT, за которым следует указанное количество значений PtypInteger16. |
| [MultipleInteger32](#MultipleInteger32) | Переменного размера; поле COUNT, за которым следует указанное количество значений PtypInteger32. |
| [MultipleInteger64](#MultipleInteger64) | Переменного размера; поле COUNT, за которым следует указанное количество значений PtypInteger64. |
| [MultipleString](#MultipleString) | Переменного размера; поле COUNT, за которым следует указанное количество значений PtypString. |
| [MultipleString8](#MultipleString8) | Переменного размера; поле COUNT, за которым следует указанное количество значений PtypString8. |
| [MultipleTime](#MultipleTime) | Переменного размера; поле COUNT, за которым следует указанное количество значений PtypTime. |
| [Null](#Null) | Отсутствует: Это свойство является заполнителем. |
| [Object](#Object) | Значение свойства представляет собой объект модели компонентов (COM). |
| [Restriction](#Restriction) | Переменного размера; массив байтов, представляющий одну или несколько структур Restriction. Имя спецификации: PtypRestriction; Альтернативные имена: PT\_SRESTRICT; |
| [RuleAction](#RuleAction) | Переменного размера; 16‑битное поле COUNT, за которым следует указанное количество структур действий правила. Имя спецификации: PtypRuleAction; Альтернативные имена: PT\_ACTIONS; |
| [ServerId](#ServerId) | Переменного размера; 16‑битное поле COUNT, за которым следует структура. Имя спецификации: PtypServerId; Альтернативные имена: PT\_SVREID; |
| [String](#String) | Переменного размера; строка символов Unicode в кодировке UTF-16LE с завершающим нулевым символом (0x0000). |
| [String8](#String8) | Переменного размера; строка многобайтовых символов во внешне заданной кодировке с завершающим нулевым символом (один байт 0). |
| [Time](#Time) | 8 байт; 64‑битное целое число, представляющее количество интервалов по 100 наносекунд, прошедших с 1 января 1601 года. Имя спецификации: PtypTime; Альтернативные имена: PT\_SYSTIME, time, datetime, datetime.tz, datetime.rfc1123, Date, time, time.tz; |
| [Unspecified](#Unspecified) | Любой: значение типа этого свойства может соответствовать любому типу; сервер ДОЛЖЕН вернуть фактический тип в своем ответе. |
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
### Binary {#Binary}
```
public static final int Binary
```


Переменного размера; поле COUNT, за которым следует указанное количество байтов. Имя спецификации: PtypBinary; Альтернативные имена: PT\_BINARY;

### Boolean {#Boolean}
```
public static final int Boolean
```


1 байт; допускаются только значения 1 или 0. Имя спецификации: PtypBoolean; Альтернативные имена: PT\_BOOLEAN. bool;

### Currency {#Currency}
```
public static final int Currency
```


8 байт; 64‑битное знаковое масштабируемое целое представление десятичного валютного значения с четырьмя знаками после запятой. Название спецификации: PtypCurrency; Альтернативные имена: PT\_CURRENCY, fixed.14.4;

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### ErrorCode {#ErrorCode}
```
public static final int ErrorCode
```


4 байта; 32‑битное целое, кодирующее информацию об ошибке. Название спецификации: PtypErrorCode; Альтернативные имена: PT\_ERROR;

### Floating32 {#Floating32}
```
public static final int Floating32
```


4 байта; 32‑битное число с плавающей точкой. Название спецификации: PtypFloating32; Альтернативные имена: PT\_FLOAT, PT\_R4, float, r4;

### Floating64 {#Floating64}
```
public static final int Floating64
```


8 байт; 64‑битное число с плавающей точкой. Название спецификации: PtypFloating64; Альтернативные имена: PT\_DOUBLE, PT\_R8, r8;

### FloatingTime {#FloatingTime}
```
public static final int FloatingTime
```


8 байт; 64‑битное число с плавающей запятой, где целая часть представляет количество дней, прошедших с 30 декабря 1899 года, а дробная часть — долю дня с полуночи. Название спецификации: PtypFloatingTime; Альтернативные названия: PT\_APPTIME; Информация о дате представлена целочисленными приращениями, начиная с полуночи 30 декабря 1899 как нулевого времени. Информация о времени представлена долей дня, прошедшего с предыдущей полуночи. Например, 6:00 утра 4 января 1900 будет представлено значением 5.25 (5 и 1/4 дня после 30 декабря 1899).

### Guid {#Guid}
```
public static final int Guid
```


16 байт; GUID с полями Data1, Data2 и Data3 в формате little-endian. Название спецификации: PtypGuid; Альтернативные имена: PT\_CLSID, UUID;

### Integer16 {#Integer16}
```
public static final int Integer16
```


2 байта; 16‑битное целое. Название спецификации: PtypInteger16; Альтернативные имена: PT\_SHORT, PT\_I2, i2, ui2;

### Integer32 {#Integer32}
```
public static final int Integer32
```


4 байта; 32‑битное целое. Название спецификации: PtypInteger32; Альтернативные имена: PT\_LONG, PT\_I4, int, ui4;

### Integer64 {#Integer64}
```
public static final int Integer64
```


8 байт; 64‑битное целое число. Имя спецификации: PtypInteger64; Альтернативные имена: PT\_LONGLONG, PT\_I8, i8, ui8;

### MultipleBinary {#MultipleBinary}
```
public static final int MultipleBinary
```


Переменного размера; поле COUNT, за которым следует указанное количество значений PtypBinary. Название спецификации: PtypMultipleBinary; Альтернативные названия: PT\_MV\_BINARY, mv.bin.hex;

### MultipleBoolean {#MultipleBoolean}
```
public static final int MultipleBoolean
```


Переменного размера; поле COUNT, за которым следует указанное количество значений PtypBoolean. Название спецификации: PtypMultipleBoolean; Альтернативные названия: PT\_MV\_BOOLEAN;

### MultipleCurrency {#MultipleCurrency}
```
public static final int MultipleCurrency
```


Переменного размера; поле COUNT, за которым следует указанное количество значений PtypCurrency. Название спецификации: PtypMultipleCurrency; Альтернативные названия: PT\_MV\_CURRENCY, mv.fixed.14.4;

### MultipleFloating32 {#MultipleFloating32}
```
public static final int MultipleFloating32
```


Переменного размера; поле COUNT, за которым следует указанное количество значений PtypFloating32. Название спецификации: PtypMultipleFloating32; Альтернативные названия: PT\_MV\_FLOAT, PT\_MV\_R4, mv.float;

### MultipleFloating64 {#MultipleFloating64}
```
public static final int MultipleFloating64
```


Переменного размера; поле COUNT, за которым следует указанное количество значений PtypFloating64. Название спецификации: PtypMultipleFloating64; Альтернативные названия: PT\_MV\_DOUBLE, PT\_MV\_R8;

### MultipleFloatingTime {#MultipleFloatingTime}
```
public static final int MultipleFloatingTime
```


Переменного размера; поле COUNT, за которым следует указанное количество значений PtypFloatingTime. Название спецификации: PtypMultipleFloatingTime; Альтернативные названия: PT\_MV\_APPTIME;

### MultipleGuid {#MultipleGuid}
```
public static final int MultipleGuid
```


Переменного размера; поле COUNT, за которым следует указанное количество значений PtypGuid. Название спецификации: PtypMultipleGuid; Альтернативные названия: PT\_MV\_CLSID, mv.uuid;

### MultipleInteger16 {#MultipleInteger16}
```
public static final int MultipleInteger16
```


Переменного размера; поле COUNT, за которым следует указанное количество значений PtypInteger16. Название спецификации: PtypMultipleInteger16; Альтернативные названия: PT\_MV\_SHORT, PT\_MV\_I2, mv.i2;

### MultipleInteger32 {#MultipleInteger32}
```
public static final int MultipleInteger32
```


Переменного размера; поле COUNT, за которым следует указанное количество значений PtypInteger32. Название спецификации: PtypMultipleInteger32; Альтернативные названия: PT\_MV\_LONG, PT\_MV\_I4, mv.i4;

### MultipleInteger64 {#MultipleInteger64}
```
public static final int MultipleInteger64
```


Переменного размера; поле COUNT, за которым следует указанное количество значений PtypInteger64. Название спецификации: PtypMultipleInteger64; Альтернативные названия: PT\_MV\_I8, PT\_MV\_LONGLONG;

### MultipleString {#MultipleString}
```
public static final int MultipleString
```


Переменного размера; поле COUNT, за которым следует указанное количество значений PtypString. Название спецификации: PtypMultipleString; Альтернативные названия: PT\_MV\_UNICODE;

### MultipleString8 {#MultipleString8}
```
public static final int MultipleString8
```


Переменного размера; поле COUNT, за которым следует указанное количество значений PtypString8. Название спецификации: PtypMultipleString8; Альтернативные названия: PT\_MV\_STRING8, mv.string;

### MultipleTime {#MultipleTime}
```
public static final int MultipleTime
```


Переменного размера; поле COUNT, за которым следует указанное количество значений PtypTime. Название спецификации: PtypMultipleTime; Альтернативные названия: PT\_MV\_SYSTIME;

### Null {#Null}
```
public static final int Null
```


Отсутствует: это свойство является заполнителем. Название спецификации: PtypNull; Альтернативные названия: PT\_NULL;

### Object {#Object}
```
public static final int Object
```


Значение свойства представляет собой объект Component Object Model (COM). Название спецификации: PtypObject или PtypEmbeddedTable; Альтернативные названия: PT\_OBJECT;

### Restriction {#Restriction}
```
public static final int Restriction
```


Переменного размера; массив байтов, представляющий одну или несколько структур Restriction. Имя спецификации: PtypRestriction; Альтернативные имена: PT\_SRESTRICT;

### RuleAction {#RuleAction}
```
public static final int RuleAction
```


Переменного размера; 16‑битное поле COUNT, за которым следует указанное количество структур действий правила. Имя спецификации: PtypRuleAction; Альтернативные имена: PT\_ACTIONS;

### ServerId {#ServerId}
```
public static final int ServerId
```


Переменного размера; 16‑битное поле COUNT, за которым следует структура. Имя спецификации: PtypServerId; Альтернативные имена: PT\_SVREID;

### String {#String}
```
public static final int String
```


Переменного размера; строка символов Unicode в кодировке UTF-16LE с завершающим нулевым символом (0x0000). Название спецификации: PtypString; Альтернативные названия: PT\_UNICODE, string;

### String8 {#String8}
```
public static final int String8
```


Переменного размера; строка многобайтовых символов во внешне заданной кодировке с завершающим нулевым символом (один байт 0). Название спецификации: PtypString8; Альтернативные названия: PT\_STRING8;

### Time {#Time}
```
public static final int Time
```


8 байт; 64‑битное целое число, представляющее количество интервалов по 100 наносекунд, прошедших с 1 января 1601 года. Имя спецификации: PtypTime; Альтернативные имена: PT\_SYSTIME, time, datetime, datetime.tz, datetime.rfc1123, Date, time, time.tz;

### Unspecified {#Unspecified}
```
public static final int Unspecified
```


Любой: значение типа этого свойства может соответствовать любому типу; сервер ДОЛЖЕН вернуть фактический тип в своём ответе. Серверы НЕ ДОЛЖНЫ возвращать этот тип в ответе на запрос клиента, отличный от NspiGetIDsFromNames или RopGetPropertyIdsFromNames ROP‑запроса ([MS-OXCROPS] раздел 2.2.8.1). Название спецификации: PtypUnspecified; Альтернативные названия: PT\_UNSPECIFIED;

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

