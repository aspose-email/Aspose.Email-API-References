---
title: InlineAttachmentExtractor
second_title: Aspose.Email for Android via Java API Reference
description: Обеспечивает возможность извлекать файлы из пакетов MSO.
type: docs
weight: 164
url: /ru/androidjava/com.aspose.email/inlineattachmentextractor/
---

**Inheritance:**
java.lang.Object
```
public class InlineAttachmentExtractor
```

Обеспечивает возможность извлекать файлы из пакетов MSO. Может использоваться для обработки "oledata.mso" и подобных файлов, обычно прикрепляемых к сообщениям, созданным в Outlook.
## Constructors

| Constructor | Описание |
| --- | --- |
| [InlineAttachmentExtractor()](#InlineAttachmentExtractor--) |  |
## Methods

| Method | Описание |
| --- | --- |
| [enumerateMsoPackage(InputStream stream)](#enumerateMsoPackage-java.io.InputStream-) | Перечисляет пакет MSO и возвращает словарь, содержащий данные файлов. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### InlineAttachmentExtractor() {#InlineAttachmentExtractor--}
```
public InlineAttachmentExtractor()
```


### enumerateMsoPackage(InputStream stream) {#enumerateMsoPackage-java.io.InputStream-}
```
public static System.Collections.Generic.IGenericDictionary<String,byte[]> enumerateMsoPackage(InputStream stream)
```


Перечисляет пакет MSO и возвращает словарь, содержащий данные файлов. Ключ — идентификатор файла, а значение содержит фактические данные. Файлы обычно ссылаются в теле сообщения с использованием предоставленных идентификаторов.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
|  | stream | java.io.InputStream | Поток для разбора. |

--------------------

В режиме оценки из данного потока MSO извлекается только один файл. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,byte[]> - Словарь с данными файлов.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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

