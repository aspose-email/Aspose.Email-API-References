---
title: MessageObjectProperty
second_title: Aspose.Email for Android via Java API Reference
description: Представляет свойство в .
type: docs
weight: 314
url: /ru/androidjava/com.aspose.email/messageobjectproperty/
---

**Inheritance:**
java.lang.Object
```
public final class MessageObjectProperty
```

Представляет свойство в объекте [MessageObject](../../com.aspose.email/messageobject).
## Constructors

| Constructor | Описание |
| --- | --- |
| [MessageObjectProperty(long propertyTag, int flags, Object value)](#MessageObjectProperty-long-int-java.lang.Object-) | Инициализирует новый экземпляр класса [MessageObjectProperty](../../com.aspose.email/messageobjectproperty). |
| [MessageObjectProperty(int id, int type, int flags, Object value)](#MessageObjectProperty-int-int-int-java.lang.Object-) | Инициализирует новый экземпляр класса [MessageObjectProperty](../../com.aspose.email/messageobjectproperty). |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAtomic()](#getAtomic--) | Возвращает значение, указывающее, является ли данный [MessageObjectProperty](../../com.aspose.email/messageobjectproperty) атомарным. |
| [getClass()](#getClass--) |  |
| [getFlags()](#getFlags--) | Возвращает флаги, установленные для свойства. |
| [getGuid()](#getGuid--) | Получает или задает GUID для именованного свойства. |
| [getId()](#getId--) | Получает идентификатор свойства. |
| [getName()](#getName--) | Получает или задает имя свойства, если оно именовано. |
| [getNameId()](#getNameId--) | Получает или задает идентификатор имени свойства, если оно именовано. |
| [getNamed()](#getNamed--) | Получает значение, указывающее, является ли этот [MessageObjectProperty](../../com.aspose.email/messageobjectproperty) именованным свойством. |
| [getPropertyKind()](#getPropertyKind--) | Получает или задает тип свойства, если оно именовано. |
| [getPropertyTag()](#getPropertyTag--) | Получает тег свойства, комбинированное значение, которое содержит Id (\#getId.getId) и PropertyType (\#getPropertyType.getPropertyType) |
| [getPropertyType()](#getPropertyType--) | Получает тип свойства. |
| [getValue()](#getValue--) | Получает или задает значение свойства. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setGuid(UUID value)](#setGuid-java.util.UUID-) | Получает или задает GUID для именованного свойства. |
| [setName(String value)](#setName-java.lang.String-) | Получает или задает имя свойства, если оно именовано. |
| [setNameId(long value)](#setNameId-long-) | Получает или задает идентификатор имени свойства, если оно именовано. |
| [setPropertyKind(int value)](#setPropertyKind-int-) | Получает или задает тип свойства, если оно именовано. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Получает или задает значение свойства. |
| [toDateTime()](#toDateTime--) | Преобразует значение свойства в DateTime. |
| [toGuid()](#toGuid--) | Преобразует значение свойства в Guid (\#getGuid.getGuid/\#setGuid(Guid).setGuid(Guid)). |
| [toInt()](#toInt--) | Преобразует значение свойства в целое число. |
| [toList()](#toList--) | Преобразует значение свойства в список значений. |
| [toString()](#toString--) |  |
| [toStringRepresentation()](#toStringRepresentation--) | Преобразует значение свойства в строку. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MessageObjectProperty(long propertyTag, int flags, Object value) {#MessageObjectProperty-long-int-java.lang.Object-}
```
public MessageObjectProperty(long propertyTag, int flags, Object value)
```


Инициализирует новый экземпляр класса [MessageObjectProperty](../../com.aspose.email/messageobjectproperty).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| propertyTag | long | Тег свойства. |
| flags | int | Флаги, которые необходимо установить. |
| value | java.lang.Object | Значение свойства. |

### MessageObjectProperty(int id, int type, int flags, Object value) {#MessageObjectProperty-int-int-int-java.lang.Object-}
```
public MessageObjectProperty(int id, int type, int flags, Object value)
```


Инициализирует новый экземпляр класса [MessageObjectProperty](../../com.aspose.email/messageobjectproperty).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| id | int | Идентификатор. |
| type | int | Тип свойства. |
| flags | int | Флаги, которые необходимо установить. |
| value | java.lang.Object | Значение свойства. |

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
### getAtomic() {#getAtomic--}
```
public final boolean getAtomic()
```


Возвращает значение, указывающее, является ли данный [MessageObjectProperty](../../com.aspose.email/messageobjectproperty) атомарным.

Значение:  true  если атомарно; иначе,  false .

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFlags() {#getFlags--}
```
public final int getFlags()
```


Возвращает флаги, установленные для свойства.

Значение: Флаги.

**Returns:**
int
### getGuid() {#getGuid--}
```
public final UUID getGuid()
```


Получает или задает GUID для именованного свойства.

Значение: GUID.

**Returns:**
java.util.UUID
### getId() {#getId--}
```
public final int getId()
```


Получает идентификатор свойства.

Значение: Идентификатор свойства.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Получает или задает имя свойства, если оно именовано.

Значение: имя.

**Returns:**
java.lang.String
### getNameId() {#getNameId--}
```
public final long getNameId()
```


Получает или задает идентификатор имени свойства, если оно именовано.

Значение: Идентификатор имени.

**Returns:**
long
### getNamed() {#getNamed--}
```
public final boolean getNamed()
```


Получает значение, указывающее, является ли этот [MessageObjectProperty](../../com.aspose.email/messageobjectproperty) именованным свойством.

Значение:  true  если именовано; иначе,  false .

--------------------

Именованное свойство определяется по его ID, диапазон таких идентификаторов: [0x8000,0xfffe].

**Returns:**
boolean
### getPropertyKind() {#getPropertyKind--}
```
public final int getPropertyKind()
```


Получает или задает тип свойства, если оно именовано.

Value: Вид свойства.

**Returns:**
int
### getPropertyTag() {#getPropertyTag--}
```
public final long getPropertyTag()
```


Получает тег свойства, комбинированное значение, которое содержит Id (\#getId.getId) и PropertyType (\#getPropertyType.getPropertyType)

Value: Тег свойства.

**Returns:**
long
### getPropertyType() {#getPropertyType--}
```
public final int getPropertyType()
```


Получает тип свойства.

Value: Тип свойства.

**Returns:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```


Получает или задает значение свойства.

**Returns:**
java.lang.Object
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




### setGuid(UUID value) {#setGuid-java.util.UUID-}
```
public final void setGuid(UUID value)
```


Получает или задает GUID для именованного свойства.

Значение: GUID.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.UUID |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Получает или задает имя свойства, если оно именовано.

Значение: имя.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setNameId(long value) {#setNameId-long-}
```
public final void setNameId(long value)
```


Получает или задает идентификатор имени свойства, если оно именовано.

Значение: Идентификатор имени.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | long |  |

### setPropertyKind(int value) {#setPropertyKind-int-}
```
public final void setPropertyKind(int value)
```


Получает или задает тип свойства, если оно именовано.

Value: Вид свойства.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Получает или задает значение свойства.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.Object |  |

### toDateTime() {#toDateTime--}
```
public final Date toDateTime()
```


Преобразует значение свойства в DateTime.

**Returns:**
java.util.Date - значение DateTime, если тип нельзя преобразовать в DateTime, возвращается java.util.Date\#MinValue.MinValue.

--------------------

Этот метод не обеспечивает автоматическое преобразование типов данных, например, если свойство MessageObjectProperty.Value (\#getValue.getValue/\#setValue(Object).setValue(Object)) имеет тип, будет возвращено значение по умолчанию.
### toGuid() {#toGuid--}
```
public final UUID toGuid()
```


Преобразует значение свойства в Guid (\#getGuid.getGuid/\#setGuid(Guid).setGuid(Guid)).

**Returns:**
java.util.UUID - объект Guid, если тип нельзя преобразовать в Guid, возвращается пустой GUID.

--------------------

Этот метод не обеспечивает автоматическое преобразование типов данных, например, если свойство MessageObjectProperty.Value (\#getValue.getValue/\#setValue(Object).setValue(Object)) имеет тип, будет возвращено значение по умолчанию.
### toInt() {#toInt--}
```
public final int toInt()
```


Преобразует значение свойства в целое число.

**Returns:**
int - целочисленное значение, если тип нельзя преобразовать в целое, возвращается 0.
### toList() {#toList--}
```
public System.Collections.IList toList()
```


Преобразует значение свойства в список значений.

**Returns:**
com.aspose.ms.System.Collections.IList - реализация IList, если тип нельзя преобразовать в IList, возвращается пустая реализация списка.

--------------------

Этот метод не обеспечивает автоматическое преобразование типов данных, например, если свойство MessageObjectProperty.Value (\#getValue.getValue/\#setValue(Object).setValue(Object)) имеет тип, будет возвращено значение по умолчанию.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toStringRepresentation() {#toStringRepresentation--}
```
public final String toStringRepresentation()
```


Преобразует значение свойства в строку.

**Returns:**
java.lang.String - строковое значение, если тип нельзя преобразовать в строку, возвращается пустая строка.

--------------------

Этот метод не обеспечивает автоматическое преобразование типов данных, например, если свойство MessageObjectProperty.Value (\#getValue.getValue/\#setValue(Object).setValue(Object)) имеет тип, будет возвращено значение по умолчанию.
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

