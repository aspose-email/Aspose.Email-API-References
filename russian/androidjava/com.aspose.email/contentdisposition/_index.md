---
title: ContentDisposition
second_title: Aspose.Email for Android via Java API Reference
description: Представляет заголовок Content-Disposition.
type: docs
weight: 85
url: /ru/androidjava/com.aspose.email/contentdisposition/
---

**Inheritance:**
java.lang.Object
```
public class ContentDisposition
```

Представляет заголовок Content-Disposition.
## Constructors

| Constructor | Описание |
| --- | --- |
| [ContentDisposition()](#ContentDisposition--) | Инициализирует новый экземпляр класса [ContentDisposition](../../com.aspose.email/contentdisposition). |
| [ContentDisposition(String disposition)](#ContentDisposition-java.lang.String-) | Инициализирует новый экземпляр класса [ContentDisposition](../../com.aspose.email/contentdisposition). |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный Object текущему экземпляру. |
| [getClass()](#getClass--) |  |
| [getCreationDate()](#getCreationDate--) | Получает или задает дату создания. |
| [getDispositionType()](#getDispositionType--) | Получает или задает тип disposition. |
| [getFileName()](#getFileName--) | Получает или задает имя файла вложения. |
| [getInline()](#getInline--) | Получает или задает значение, определяющее тип disposition. |
| [getModificationDate()](#getModificationDate--) | Получает или задает дату изменения. |
| [getParameters()](#getParameters--) | Получает параметры. |
| [getReadDate()](#getReadDate--) | Получает или задает дату чтения. |
| [getSize()](#getSize--) | Получает или задает размер вложенного файла. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | Получает или задает дату создания. |
| [setDispositionType(String value)](#setDispositionType-java.lang.String-) | Получает или задает тип disposition. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Получает или задает имя файла вложения. |
| [setInline(boolean value)](#setInline-boolean-) | Получает или задает значение, определяющее тип disposition. |
| [setModificationDate(Date value)](#setModificationDate-java.util.Date-) | Получает или задает дату изменения. |
| [setReadDate(Date value)](#setReadDate-java.util.Date-) | Получает или задает дату чтения. |
| [setSize(long value)](#setSize-long-) | Получает или задает размер вложенного файла. |
| [toString()](#toString--) | Возвращает String, представляющий этот экземпляр. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ContentDisposition() {#ContentDisposition--}
```
public ContentDisposition()
```


Инициализирует новый экземпляр класса [ContentDisposition](../../com.aspose.email/contentdisposition).

### ContentDisposition(String disposition) {#ContentDisposition-java.lang.String-}
```
public ContentDisposition(String disposition)
```


Инициализирует новый экземпляр класса [ContentDisposition](../../com.aspose.email/contentdisposition).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| disposition | java.lang.String | Значение, содержащее disposition. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный Object текущему экземпляру.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Object для сравнения с этим экземпляром. |

**Returns:**
boolean —  true  если указанный Object равен этому экземпляру; иначе,  false .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreationDate() {#getCreationDate--}
```
public final Date getCreationDate()
```


Получает или задает дату создания.

Value: Значение DateTime, указывающее дату создания файла; иначе, MinValue, если дата не указана.

**Returns:**
java.util.Date
### getDispositionType() {#getDispositionType--}
```
public final String getDispositionType()
```


Получает или задает тип disposition.

Value: String, содержащий тип disposition.

**Returns:**
java.lang.String
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Получает или задает имя файла вложения.

Значение: Имя файла.

**Returns:**
java.lang.String
### getInline() {#getInline--}
```
public final boolean getInline()
```


Получает или задает значение, определяющее тип disposition.

Value: true, если содержимое вложения отображается встроенно; иначе, false.

**Returns:**
boolean
### getModificationDate() {#getModificationDate--}
```
public final Date getModificationDate()
```


Получает или задает дату изменения.

Value: Значение DateTime, указывающее дату изменения файла; иначе, MinValue, если дата не указана.

**Returns:**
java.util.Date
### getParameters() {#getParameters--}
```
public final TrackingStringDictionary getParameters()
```


Получает параметры.

Значение: StringDictionary, содержащий пары имён/значений параметров.

**Returns:**
[TrackingStringDictionary](../../com.aspose.email/trackingstringdictionary)
### getReadDate() {#getReadDate--}
```
public final Date getReadDate()
```


Получает или задает дату чтения.

Значение: DateTime, указывающий дату чтения файла; иначе MinValue, если дата не указана.

**Returns:**
java.util.Date
### getSize() {#getSize--}
```
public final long getSize()
```


Получает или задает размер вложенного файла.

Значение: Int32, указывающий количество байтов во вложении файла.

**Returns:**
long
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.

**Returns:**
int — Хеш‑код этого экземпляра, пригодный для использования в алгоритмах хеширования и структурах данных, таких как хеш‑таблица.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public final void setCreationDate(Date value)
```


Получает или задает дату создания.

Value: Значение DateTime, указывающее дату создания файла; иначе, MinValue, если дата не указана.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setDispositionType(String value) {#setDispositionType-java.lang.String-}
```
public final void setDispositionType(String value)
```


Получает или задает тип disposition.

Value: String, содержащий тип disposition.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public final void setFileName(String value)
```


Получает или задает имя файла вложения.

Значение: Имя файла.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setInline(boolean value) {#setInline-boolean-}
```
public final void setInline(boolean value)
```


Получает или задает значение, определяющее тип disposition.

Value: true, если содержимое вложения отображается встроенно; иначе, false.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setModificationDate(Date value) {#setModificationDate-java.util.Date-}
```
public final void setModificationDate(Date value)
```


Получает или задает дату изменения.

Value: Значение DateTime, указывающее дату изменения файла; иначе, MinValue, если дата не указана.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setReadDate(Date value) {#setReadDate-java.util.Date-}
```
public final void setReadDate(Date value)
```


Получает или задает дату чтения.

Значение: DateTime, указывающий дату чтения файла; иначе MinValue, если дата не указана.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setSize(long value) {#setSize-long-}
```
public final void setSize(long value)
```


Получает или задает размер вложенного файла.

Значение: Int32, указывающий количество байтов во вложении файла.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | long |  |

### toString() {#toString--}
```
public String toString()
```


Возвращает String, представляющий этот экземпляр.

**Returns:**
java.lang.String — Строка, представляющая этот экземпляр.
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

