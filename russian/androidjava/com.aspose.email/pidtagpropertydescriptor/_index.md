---
title: PidTagPropertyDescriptor
second_title: Aspose.Email for Android via Java API Reference
description: Класс содержит информацию описания свойства.
type: docs
weight: 352
url: /ru/androidjava/com.aspose.email/pidtagpropertydescriptor/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.PropertyDescriptor](../../com.aspose.email/propertydescriptor)
```
public class PidTagPropertyDescriptor extends PropertyDescriptor
```

Класс содержит информацию описания свойства.
## Constructors

| Constructor | Описание |
| --- | --- |
| [PidTagPropertyDescriptor(int id, int type)](#PidTagPropertyDescriptor-int-int-) | Инициализирует новый экземпляр класса [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) свойство, которое определяется 16-битным идентификатором свойства и 16-битным типом свойства. |
| [PidTagPropertyDescriptor(String canonicalName, int id, int type)](#PidTagPropertyDescriptor-java.lang.String-int-int-) | Инициализирует новый экземпляр класса [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) свойство, которое определяется 16-битным идентификатором свойства и 16-битным типом свойства. |
| [PidTagPropertyDescriptor(String canonicalName, String name, int id, int type)](#PidTagPropertyDescriptor-java.lang.String-java.lang.String-int-int-) | Инициализирует новый экземпляр класса [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) свойство, которое определяется 16-битным идентификатором свойства и 16-битным типом свойства. |
| [PidTagPropertyDescriptor(long tag)](#PidTagPropertyDescriptor-long-) | Инициализирует новый экземпляр класса [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) свойство, которое определяется 16-битным идентификатором свойства и 16-битным типом свойства. |
| [PidTagPropertyDescriptor(String canonicalName, String name, long tag)](#PidTagPropertyDescriptor-java.lang.String-java.lang.String-long-) | Инициализирует новый экземпляр класса [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) свойство, которое определяется 16-битным идентификатором свойства и 16-битным типом свойства. |
## Methods

| Method | Описание |
| --- | --- |
| [equals(PropertyDescriptor other)](#equals-com.aspose.email.PropertyDescriptor-) | Указывает, равен ли текущий объект другому объекту того же типа. |
| [equals(Object other)](#equals-java.lang.Object-) | Определяет, равен ли указанный System.Object текущему System.Object. |
| [getCanonicalName()](#getCanonicalName--) | Имя, используемое для ссылки на свойство в документации. |
| [getClass()](#getClass--) |  |
| [getDataType()](#getDataType--) | Тип значения свойства, как описано в [MS-OXCDATA], который указывает тип допустимых значений для свойства. |
| [getId()](#getId--) | Получает беззнаковое 16-битное значение, идентифицирующее помеченное свойство. |
| [getInstance(MapiProperty property)](#getInstance-com.aspose.email.MapiProperty-) | Получает объект [PropertyDescriptor](../../com.aspose.email/propertydescriptor) из свойства MAPI. |
| [getInstance(int id, int dataType)](#getInstance-int-int-) | Получает объект [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor). |
| [getInstance(String name, int dataType, UUID propertySet)](#getInstance-java.lang.String-int-java.util.UUID-) | Получает объект [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor). |
| [getInstance(long tag)](#getInstance-long-) | Получает объект [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor). |
| [getInstance(long lid, int dataType, UUID propertySet)](#getInstance-long-int-java.util.UUID-) | Получает объект [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor). |
| [getMultipleValuesDataType()](#getMultipleValuesDataType--) | Указывает, содержит ли тип данных несколько значений. |
| [getName()](#getName--) | Получает строку, идентифицирующую свойство. |
| [getTag()](#getTag--) | Тег свойства — это 32-битное число, которое содержит уникальный идентификатор свойства в битах 16–31 и тип свойства в битах 0–15. |
| [getUse8BitStringAsUnicode()](#getUse8BitStringAsUnicode--) | Указывает, следует ли интерпретировать PropertyDataType.String8 как PropertyDataType.String. |
| [hashCode()](#hashCode--) | Служит хеш-функцией для типа. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PidTagPropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Equality-com.aspose.email.PidTagPropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Определяет, равны ли указанные объекты друг другу. |
| [op_Equality(PropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Equality-com.aspose.email.PropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Определяет, равны ли указанные объекты друг другу. |
| [op_Inequality(PidTagPropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Inequality-com.aspose.email.PidTagPropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Определяет, не равны ли указанные объекты друг другу. |
| [op_Inequality(PropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Inequality-com.aspose.email.PropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Определяет, не равны ли указанные объекты друг другу. |
| [parse(String data)](#parse-java.lang.String-) | Инициализирует новый экземпляр класса [PropertyDescriptor](../../com.aspose.email/propertydescriptor). |
| [setUse8BitStringAsUnicode(boolean value)](#setUse8BitStringAsUnicode-boolean-) | Указывает, следует ли интерпретировать PropertyDataType.String8 как PropertyDataType.String. |
| [toString()](#toString--) | Возвращает строку, представляющую описание свойства. |
| [to_PidTagPropertyDescriptor(long tag)](#to-PidTagPropertyDescriptor-long-) | Преобразует значение тега в помеченное свойство |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PidTagPropertyDescriptor(int id, int type) {#PidTagPropertyDescriptor-int-int-}
```
public PidTagPropertyDescriptor(int id, int type)
```


Инициализирует новый экземпляр класса [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor). Свойство определяется 16‑битным идентификатором свойства и 16‑битным типом свойства. Идентификатор свойства для помеченного свойства находится в диапазоне 0x001 \u2013 0x7FFF. Идентификаторы свойств в диапазоне 0x8000 \u2013 0x8FFF зарезервированы для назначения именованным свойствам

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| id | int | Беззнаковое 16‑битное значение, идентифицирующее помеченное свойство. |
| type | int | Указывает тип допустимых значений для свойства. |

### PidTagPropertyDescriptor(String canonicalName, int id, int type) {#PidTagPropertyDescriptor-java.lang.String-int-int-}
```
public PidTagPropertyDescriptor(String canonicalName, int id, int type)
```


Инициализирует новый экземпляр класса [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor). Свойство определяется 16‑битным идентификатором свойства и 16‑битным типом свойства. Идентификатор свойства для помеченного свойства находится в диапазоне 0x001 \u2013 0x7FFF. Идентификаторы свойств в диапазоне 0x8000 \u2013 0x8FFF зарезервированы для назначения именованным свойствам

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| canonicalName | java.lang.String | Имя, используемое для ссылки на свойство в документации. |
| id | int | Беззнаковое 16‑битное значение, идентифицирующее помеченное свойство. |
| type | int | Указывает тип допустимых значений для свойства. |

### PidTagPropertyDescriptor(String canonicalName, String name, int id, int type) {#PidTagPropertyDescriptor-java.lang.String-java.lang.String-int-int-}
```
public PidTagPropertyDescriptor(String canonicalName, String name, int id, int type)
```


Инициализирует новый экземпляр класса [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor). Свойство определяется 16‑битным идентификатором свойства и 16‑битным типом свойства. Идентификатор свойства для помеченного свойства находится в диапазоне 0x001 \u2013 0x7FFF. Идентификаторы свойств в диапазоне 0x8000 \u2013 0x8FFF зарезервированы для назначения именованным свойствам

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| canonicalName | java.lang.String | Имя, используемое для ссылки на свойство в документации. |
| name | java.lang.String | Имя MAPI, используемое для ссылки на свойство в документации. |
| id | int | Беззнаковое 16‑битное значение, идентифицирующее помеченное свойство. |
| type | int | Указывает тип допустимых значений для свойства. |

### PidTagPropertyDescriptor(long tag) {#PidTagPropertyDescriptor-long-}
```
public PidTagPropertyDescriptor(long tag)
```


Инициализирует новый экземпляр класса [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor). Свойство определяется 16‑битным идентификатором свойства и 16‑битным типом свойства. Идентификатор свойства для помеченного свойства находится в диапазоне 0x001 \u2013 0x7FFF. Идентификаторы свойств в диапазоне 0x8000 \u2013 0x8FFF зарезервированы для назначения именованным свойствам

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | Тег — это 32‑битное число, содержащее уникальный идентификатор свойства в битах 16‑31 и тип свойства в битах 0‑15. |

### PidTagPropertyDescriptor(String canonicalName, String name, long tag) {#PidTagPropertyDescriptor-java.lang.String-java.lang.String-long-}
```
public PidTagPropertyDescriptor(String canonicalName, String name, long tag)
```


Инициализирует новый экземпляр класса [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor). Свойство определяется 16‑битным идентификатором свойства и 16‑битным типом свойства. Идентификатор свойства для помеченного свойства находится в диапазоне 0x001 \u2013 0x7FFF. Идентификаторы свойств в диапазоне 0x8000 \u2013 0x8FFF зарезервированы для назначения именованным свойствам

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| canonicalName | java.lang.String | Имя, используемое для ссылки на свойство в документации. |
| name | java.lang.String | Имя MAPI, используемое для ссылки на свойство в документации. |
| tag | long | Тег — это 32‑битное число, содержащее уникальный идентификатор свойства в битах 16‑31 и тип свойства в битах 0‑15. |

### equals(PropertyDescriptor other) {#equals-com.aspose.email.PropertyDescriptor-}
```
public boolean equals(PropertyDescriptor other)
```


Указывает, равен ли текущий объект другому объекту того же типа.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| other | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | Объект для сравнения с этим объектом. |

**Returns:**
boolean — true, если текущий объект равен другому параметру; иначе false.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Определяет, равен ли указанный System.Object текущему System.Object.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| other | java.lang.Object |  |

**Returns:**
boolean — true, если указанный System.Object равен текущему System.Object; иначе false.
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
### getId() {#getId--}
```
public final int getId()
```


Получает беззнаковое 16‑битное значение, идентифицирующее помеченное свойство. Идентификаторы свойств не обязательно уникальны. За исключением идентификаторов свойств в диапазоне от 0x6800 до 0x7BFF, комбинация идентификатора свойства и типа данных уникальна. Идентификаторы свойств в диапазоне от 0x6800 до 0x7BFF определяются классом сообщения.

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
### getTag() {#getTag--}
```
public final long getTag()
```


Тег свойства — это 32-битное число, которое содержит уникальный идентификатор свойства в битах 16–31 и тип свойства в битах 0–15.

**Returns:**
long
### getUse8BitStringAsUnicode() {#getUse8BitStringAsUnicode--}
```
public static boolean getUse8BitStringAsUnicode()
```


Указывает, следует ли интерпретировать PropertyDataType.String8 как PropertyDataType.String.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


Служит хеш-функцией для типа.

**Returns:**
int — Хеш-код текущего объекта.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(PidTagPropertyDescriptor pd1, PropertyDescriptor pd2) {#op-Equality-com.aspose.email.PidTagPropertyDescriptor-com.aspose.email.PropertyDescriptor-}
```
public static boolean op_Equality(PidTagPropertyDescriptor pd1, PropertyDescriptor pd2)
```


Определяет, равны ли указанные объекты друг другу.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| pd1 | [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) | Объект для сравнения с другим объектом. |
| pd2 | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | Объект для сравнения с другим объектом. |

**Returns:**
boolean — true, если указанный PropertyDescriptor равен другому PropertyDescriptor; иначе false.
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
### op_Inequality(PidTagPropertyDescriptor pd1, PropertyDescriptor pd2) {#op-Inequality-com.aspose.email.PidTagPropertyDescriptor-com.aspose.email.PropertyDescriptor-}
```
public static boolean op_Inequality(PidTagPropertyDescriptor pd1, PropertyDescriptor pd2)
```


Определяет, не равны ли указанные объекты друг другу.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| pd1 | [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) | Объект для сравнения с другим объектом. |
| pd2 | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | Объект для сравнения с другим объектом. |

**Returns:**
boolean — true, если указанный PropertyDescriptor не равен другому PropertyDescriptor; иначе false.
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


Возвращает строку, представляющую описание свойства.

**Returns:**
java.lang.String — Строка, представляющая описание свойства.
### to_PidTagPropertyDescriptor(long tag) {#to-PidTagPropertyDescriptor-long-}
```
public static PidTagPropertyDescriptor to_PidTagPropertyDescriptor(long tag)
```


Преобразует значение тега в помеченное свойство

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| tag | long | значение тега свойства тега |

**Returns:**
[PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor)
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

