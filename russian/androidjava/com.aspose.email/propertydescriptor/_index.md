---
title: PropertyDescriptor
second_title: Aspose.Email for Android via Java API Reference
description: Класс содержит информацию описания свойства.
type: docs
weight: 359
url: /ru/androidjava/com.aspose.email/propertydescriptor/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class PropertyDescriptor implements System.IEquatable<PropertyDescriptor>
```

Класс содержит информацию описания свойства.
## Methods

| Method | Описание |
| --- | --- |
| [equals(PropertyDescriptor other)](#equals-com.aspose.email.PropertyDescriptor-) | Указывает, равен ли текущий объект другому объекту того же типа. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCanonicalName()](#getCanonicalName--) | Имя, используемое для ссылки на свойство в документации. |
| [getClass()](#getClass--) |  |
| [getDataType()](#getDataType--) | Тип значения свойства, как описано в [MS-OXCDATA], который указывает тип допустимых значений для свойства. |
| [getInstance(MapiProperty property)](#getInstance-com.aspose.email.MapiProperty-) | Получает объект [PropertyDescriptor](../../com.aspose.email/propertydescriptor) из свойства MAPI. |
| [getInstance(int id, int dataType)](#getInstance-int-int-) | Получает объект [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor). |
| [getInstance(String name, int dataType, UUID propertySet)](#getInstance-java.lang.String-int-java.util.UUID-) | Получает объект [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor). |
| [getInstance(long tag)](#getInstance-long-) | Получает объект [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor). |
| [getInstance(long lid, int dataType, UUID propertySet)](#getInstance-long-int-java.util.UUID-) | Получает объект [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor). |
| [getMultipleValuesDataType()](#getMultipleValuesDataType--) | Указывает, содержит ли тип данных несколько значений. |
| [getName()](#getName--) | Получает строку, идентифицирующую свойство. |
| [getUse8BitStringAsUnicode()](#getUse8BitStringAsUnicode--) | Указывает, следует ли интерпретировать PropertyDataType.String8 как PropertyDataType.String. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Equality-com.aspose.email.PropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Определяет, равны ли указанные объекты друг другу. |
| [op_Inequality(PropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Inequality-com.aspose.email.PropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Определяет, не равны ли указанные объекты друг другу. |
| [parse(String data)](#parse-java.lang.String-) | Инициализирует новый экземпляр класса [PropertyDescriptor](../../com.aspose.email/propertydescriptor). |
| [setUse8BitStringAsUnicode(boolean value)](#setUse8BitStringAsUnicode-boolean-) | Указывает, следует ли интерпретировать PropertyDataType.String8 как PropertyDataType.String. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(PropertyDescriptor other) {#equals-com.aspose.email.PropertyDescriptor-}
```
public abstract boolean equals(PropertyDescriptor other)
```


Указывает, равен ли текущий объект другому объекту того же типа.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| other | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | Объект для сравнения с этим объектом. |

**Returns:**
boolean — true, если текущий объект равен другому параметру; иначе false.
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
### getCanonicalName() {#getCanonicalName--}
```
public final String getCanonicalName()
```


Имя, используемое для ссылки на свойство в документации. Префикс канонического имени определяет базовые характеристики свойства для разработчика. Каноническая структура именования использует три категории, обозначаемые следующими префиксами к каноническому имени свойства: \* префикс PidLid: Свойства, идентифицируемые беззнаковым 32‑битным значением вместе с набором свойств. \* префикс PidName: Свойства, идентифицируемые строковым именем вместе с набором свойств. \* префикс PidTag: Свойства, идентифицируемые беззнаковым 16‑битным значением.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataType() {#getDataType--}
```
public final int getDataType()
```


Тип значения свойства, как описано в [MS-OXCDATA], который указывает тип допустимых значений для свойства.

**Returns:**
int
### getInstance(MapiProperty property) {#getInstance-com.aspose.email.MapiProperty-}
```
public static PropertyDescriptor getInstance(MapiProperty property)
```


Получает объект [PropertyDescriptor](../../com.aspose.email/propertydescriptor) из свойства MAPI.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| property | [MapiProperty](../../com.aspose.email/mapiproperty) | [MapiProperty](../../com.aspose.email/mapiproperty) объект |

**Returns:**
[PropertyDescriptor](../../com.aspose.email/propertydescriptor)
### getInstance(int id, int dataType) {#getInstance-int-int-}
```
public static PidTagPropertyDescriptor getInstance(int id, int dataType)
```


Получает объект [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| id | int | Идентификатор свойства |
| dataType | int | Тип данных свойства |

**Returns:**
[PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) - [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) object
### getInstance(String name, int dataType, UUID propertySet) {#getInstance-java.lang.String-int-java.util.UUID-}
```
public static PidNamePropertyDescriptor getInstance(String name, int dataType, UUID propertySet)
```


Получает объект [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя свойства |
| dataType | int | Тип данных свойства |
| propertySet | java.util.UUID | PropertySet свойства |

**Returns:**
[PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) - [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) object
### getInstance(long tag) {#getInstance-long-}
```
public static PidTagPropertyDescriptor getInstance(long tag)
```


Получает объект [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег свойства |

**Returns:**
[PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) - [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) object
### getInstance(long lid, int dataType, UUID propertySet) {#getInstance-long-int-java.util.UUID-}
```
public static PidLidPropertyDescriptor getInstance(long lid, int dataType, UUID propertySet)
```


Получает объект [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| lid | long | Длинный идентификатор свойства |
| dataType | int | Тип данных свойства |
| propertySet | java.util.UUID | PropertySet свойства |

**Returns:**
[PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) - [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) object
### getMultipleValuesDataType() {#getMultipleValuesDataType--}
```
public final boolean getMultipleValuesDataType()
```


Указывает, содержит ли тип данных несколько значений.

**Returns:**
boolean
### getName() {#getName--}
```
public final String getName()
```


Получает строку, идентифицирующую свойство.

**Returns:**
java.lang.String
### getUse8BitStringAsUnicode() {#getUse8BitStringAsUnicode--}
```
public static boolean getUse8BitStringAsUnicode()
```


Указывает, следует ли интерпретировать PropertyDataType.String8 как PropertyDataType.String.

**Returns:**
boolean
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




### op_Equality(PropertyDescriptor pd1, PropertyDescriptor pd2) {#op-Equality-com.aspose.email.PropertyDescriptor-com.aspose.email.PropertyDescriptor-}
```
public static boolean op_Equality(PropertyDescriptor pd1, PropertyDescriptor pd2)
```


Определяет, равны ли указанные объекты друг другу.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| pd1 | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | Объект для сравнения с другим объектом. |
| pd2 | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | Объект для сравнения с другим объектом. |

**Returns:**
boolean — true, если указанный PropertyDescriptor равен другому PropertyDescriptor; иначе false.
### op_Inequality(PropertyDescriptor pd1, PropertyDescriptor pd2) {#op-Inequality-com.aspose.email.PropertyDescriptor-com.aspose.email.PropertyDescriptor-}
```
public static boolean op_Inequality(PropertyDescriptor pd1, PropertyDescriptor pd2)
```


Определяет, не равны ли указанные объекты друг другу.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| pd1 | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | Объект для сравнения с другим объектом. |
| pd2 | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | Объект для сравнения с другим объектом. |

**Returns:**
boolean — true, если указанный PropertyDescriptor не равен другому PropertyDescriptor; иначе false.
### parse(String data) {#parse-java.lang.String-}
```
public static PropertyDescriptor parse(String data)
```


Инициализирует новый экземпляр класса [PropertyDescriptor](../../com.aspose.email/propertydescriptor).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| данные | java.lang.String | Строка, представляющая описание свойства. |

**Returns:**
[PropertyDescriptor](../../com.aspose.email/propertydescriptor)
### setUse8BitStringAsUnicode(boolean value) {#setUse8BitStringAsUnicode-boolean-}
```
public static void setUse8BitStringAsUnicode(boolean value)
```


Указывает, следует ли интерпретировать PropertyDataType.String8 как PropertyDataType.String.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

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

