---
title: FileAsMapping
second_title: Aspose.Email for Android via Java API 参考
description: 指定在其他联系人名称属性更改时如何生成和重新计算 dispidFileAs 属性的值。
type: docs
weight: 133
url: /zh/androidjava/com.aspose.email/fileasmapping/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class FileAsMapping extends System.Enum
```

指定在其他联系人名称属性更改时，如何生成和重新计算 dispidFileAs 属性的值。对应 MS-OXPROPS 2014 年 7 月 31 日的第 16.2 版修订。
## 字段

| 字段 | 描述 |
| --- | --- |
| [AccordingToLocale](#AccordingToLocale) | 指定在显示联系人时，应用程序应根据语言区域选择适当的默认值（针对 dispidFileUnderId），并更新 dispidFileUnder 以匹配该选择。 |
| [BestMatch](#BestMatch) | 指定在显示联系人时，应用程序应尝试使用当前的 dispidFileUnder 值及其他联系人属性，以在此表中的先前值中找到与 dispidFileUnderId 的“最佳匹配”。 |
| [DisplayName](#DisplayName) | DisplayName |
| [Empty](#Empty) | 空值。 |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
| [FirstMiddleLastGen](#FirstMiddleLastGen) | GivenName MiddleName Surname Generation |
| [FirstName](#FirstName) | GivenName |
| [LastFirstMiddle](#LastFirstMiddle) | Surname, GivenName MiddleName |
| [LastFirstMiddle2](#LastFirstMiddle2) | SurnameGivenName MiddleName |
| [LastFirstMiddle3](#LastFirstMiddle3) | Surname GivenName MiddleName |
| [LastFirstMiddleGen](#LastFirstMiddleGen) | Surname GivenName MiddleName Generation |
| [LastFirstMiddleGen2](#LastFirstMiddleGen2) | SurnameGivenName MiddleName Generation |
| [LastFirstMiddleOrg](#LastFirstMiddleOrg) | Surname, GivenName MiddleName\\r\\nCompanyName |
| [LastFirstMiddleOrg2](#LastFirstMiddleOrg2) | SurnameGivenName MiddleName\\r\\nCompanyName |
| [LastFirstMiddleOrg3](#LastFirstMiddleOrg3) | Surname GivenName PidTagMiddleName\\r\\nCompanyName |
| [LastName](#LastName) | Surname |
| [None](#None) | 指定 FileUnder 是用户提供的，在其他联系人名称属性更改时不应被修改。 |
| [OrgLastFirstMiddle](#OrgLastFirstMiddle) | CompanyName\\r\\nSurname, GivenName MiddleName |
| [OrgLastFirstMiddle2](#OrgLastFirstMiddle2) | CompanyName\\r\\nSurnameGivenName MiddleName |
| [OrgLastFirstMiddle3](#OrgLastFirstMiddle3) | CompanyName\\r\\nSurname GivenName MiddleName |
| [Organization](#Organization) | CompanyName |
## 方法

| 方法 | 描述 |
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
### AccordingToLocale {#AccordingToLocale}
```
public static final long AccordingToLocale
```


指定在显示联系人时，应用程序应根据语言区域选择适当的默认值（针对 dispidFileUnderId），并更新 dispidFileUnder 以匹配该选择。

### BestMatch {#BestMatch}
```
public static final long BestMatch
```


指定在显示联系人时，应用程序应尝试使用当前的 dispidFileUnder 值及其他联系人属性，以在此表中的先前值中找到与 dispidFileUnderId 的“最佳匹配”。

### DisplayName {#DisplayName}
```
public static final long DisplayName
```


DisplayName

### Empty {#Empty}
```
public static final long Empty
```


空值。

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### FirstMiddleLastGen {#FirstMiddleLastGen}
```
public static final long FirstMiddleLastGen
```


GivenName MiddleName Surname Generation

### FirstName {#FirstName}
```
public static final long FirstName
```


GivenName

### LastFirstMiddle {#LastFirstMiddle}
```
public static final long LastFirstMiddle
```


Surname, GivenName MiddleName

### LastFirstMiddle2 {#LastFirstMiddle2}
```
public static final long LastFirstMiddle2
```


SurnameGivenName MiddleName

### LastFirstMiddle3 {#LastFirstMiddle3}
```
public static final long LastFirstMiddle3
```


Surname GivenName MiddleName

### LastFirstMiddleGen {#LastFirstMiddleGen}
```
public static final long LastFirstMiddleGen
```


Surname GivenName MiddleName Generation

### LastFirstMiddleGen2 {#LastFirstMiddleGen2}
```
public static final long LastFirstMiddleGen2
```


SurnameGivenName MiddleName Generation

### LastFirstMiddleOrg {#LastFirstMiddleOrg}
```
public static final long LastFirstMiddleOrg
```


Surname, GivenName MiddleName\\r\\nCompanyName

### LastFirstMiddleOrg2 {#LastFirstMiddleOrg2}
```
public static final long LastFirstMiddleOrg2
```


SurnameGivenName MiddleName\\r\\nCompanyName

### LastFirstMiddleOrg3 {#LastFirstMiddleOrg3}
```
public static final long LastFirstMiddleOrg3
```


Surname GivenName PidTagMiddleName\\r\\nCompanyName

### LastName {#LastName}
```
public static final long LastName
```


Surname

### None {#None}
```
public static final long None
```


指定 FileUnder 是用户提供的，在其他联系人名称属性更改时不应被修改。即 FileUnder 的值不是由其他属性构建的。

### OrgLastFirstMiddle {#OrgLastFirstMiddle}
```
public static final long OrgLastFirstMiddle
```


CompanyName\\r\\nSurname, GivenName MiddleName

### OrgLastFirstMiddle2 {#OrgLastFirstMiddle2}
```
public static final long OrgLastFirstMiddle2
```


CompanyName\\r\\nSurnameGivenName MiddleName

### OrgLastFirstMiddle3 {#OrgLastFirstMiddle3}
```
public static final long OrgLastFirstMiddle3
```


CompanyName\\r\\nSurname GivenName MiddleName

### Organization {#Organization}
```
public static final long Organization
```


CompanyName

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

