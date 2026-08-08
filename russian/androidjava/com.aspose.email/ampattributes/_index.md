---
title: AmpAttributes
second_title: Aspose.Email for Android via Java API Reference
description: Представляет атрибуты, используемые amp-компонентами.
type: docs
weight: 16
url: /ru/androidjava/com.aspose.email/ampattributes/
---

**Inheritance:**
java.lang.Object
```
public class AmpAttributes
```

Представляет атрибуты, используемые amp-компонентами.
## Constructors

| Constructor | Описание |
| --- | --- |
| [AmpAttributes()](#AmpAttributes--) |  |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeight()](#getHeight--) | Высота элемента. |
| [getHeigths()](#getHeigths--) | Значение этого атрибута — выражение sizes, основанное на медиавыражениях. |
| [getLayout()](#getLayout--) | AMP предоставляет набор макетов, определяющих, как компонент AMP ведет себя в макете документа. |
| [getMedia()](#getMedia--) | Значение media — медиазапрос. |
| [getOn()](#getOn--) | Атрибут on используется для установки обработчиков событий на элементах. |
| [getSizes()](#getSizes--) | Значение атрибута AMP sizes — выражение sizes, которое выбирает определённый размер, соответствующий медиазапросу, на основе текущего размера окна. |
| [getWidth()](#getWidth--) | Ширина элемента. |
| [hashCode()](#hashCode--) |  |
| [isFallback()](#isFallback--) | Определяет, что текущий элемент является резервным. |
| [isNoloading()](#isNoloading--) | Атрибут noloading указывает, следует ли отключить "индикатор загрузки" для этого элемента. |
| [isPlaceHolder()](#isPlaceHolder--) | Атрибут placeholder указывает, что элемент, помеченный этим атрибутом, выступает в качестве заполнителя для родительского элемента AMP. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFallback(boolean value)](#setFallback-boolean-) | Определяет, что текущий элемент является резервным. |
| [setHeight(int value)](#setHeight-int-) | Высота элемента. |
| [setHeigths(String value)](#setHeigths-java.lang.String-) | Значение этого атрибута — выражение sizes, основанное на медиавыражениях. |
| [setLayout(int value)](#setLayout-int-) | AMP предоставляет набор макетов, определяющих, как компонент AMP ведет себя в макете документа. |
| [setMedia(String value)](#setMedia-java.lang.String-) | Значение media — медиазапрос. |
| [setNoloading(boolean value)](#setNoloading-boolean-) | Атрибут noloading указывает, следует ли отключить "индикатор загрузки" для этого элемента. |
| [setOn(String value)](#setOn-java.lang.String-) | Атрибут on используется для установки обработчиков событий на элементах. |
| [setPlaceHolder(boolean value)](#setPlaceHolder-boolean-) | Атрибут placeholder указывает, что элемент, помеченный этим атрибутом, выступает в качестве заполнителя для родительского элемента AMP. |
| [setSizes(String value)](#setSizes-java.lang.String-) | Значение атрибута AMP sizes — выражение sizes, которое выбирает определённый размер, соответствующий медиазапросу, на основе текущего размера окна. |
| [setWidth(int value)](#setWidth-int-) | Ширина элемента. |
| [toAmpHtml()](#toAmpHtml--) | Представляет HTML-версию атрибутов amp. |
| [toHtml()](#toHtml--) | Представляет HTML-версию атрибутов. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AmpAttributes() {#AmpAttributes--}
```
public AmpAttributes()
```


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
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Высота элемента.

**Returns:**
int
### getHeigths() {#getHeigths--}
```
public final String getHeigths()
```


Значение этого атрибута — выражение sizes, основанное на медиавыражениях.

**Returns:**
java.lang.String
### getLayout() {#getLayout--}
```
public final int getLayout()
```


AMP предоставляет набор макетов, определяющих, как компонент AMP ведет себя в макете документа.

**Returns:**
int
### getMedia() {#getMedia--}
```
public final String getMedia()
```


Значение media — медиазапрос. Если запрос не совпадает, элемент не отображается, и его ресурсы, а также потенциально ресурсы его дочерних элементов, не загружаются. Если размер или ориентация окна браузера меняются, медиазапросы переоцениваются, и элементы скрываются или показываются в зависимости от новых результатов.

**Returns:**
java.lang.String
### getOn() {#getOn--}
```
public final String getOn()
```


Атрибут on используется для установки обработчиков событий на элементах.

**Returns:**
java.lang.String
### getSizes() {#getSizes--}
```
public final String getSizes()
```


Значение атрибута AMP sizes — выражение sizes, которое выбирает определённый размер, соответствующий медиазапросу, на основе текущего размера окна.

**Returns:**
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ширина элемента.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isFallback() {#isFallback--}
```
public final boolean isFallback()
```


Определяет, что текущий элемент является резервным.

**Returns:**
boolean
### isNoloading() {#isNoloading--}
```
public final boolean isNoloading()
```


Атрибут noloading указывает, следует ли отключить "индикатор загрузки" для этого элемента.

**Returns:**
boolean
### isPlaceHolder() {#isPlaceHolder--}
```
public final boolean isPlaceHolder()
```


Атрибут placeholder указывает, что элемент, помеченный этим атрибутом, выступает в качестве заполнителя для родительского элемента AMP.

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




### setFallback(boolean value) {#setFallback-boolean-}
```
public final void setFallback(boolean value)
```


Определяет, что текущий элемент является резервным.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Высота элемента.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setHeigths(String value) {#setHeigths-java.lang.String-}
```
public final void setHeigths(String value)
```


Значение этого атрибута — выражение sizes, основанное на медиавыражениях.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setLayout(int value) {#setLayout-int-}
```
public final void setLayout(int value)
```


AMP предоставляет набор макетов, определяющих, как компонент AMP ведет себя в макете документа.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setMedia(String value) {#setMedia-java.lang.String-}
```
public final void setMedia(String value)
```


Значение media — медиазапрос. Если запрос не совпадает, элемент не отображается, и его ресурсы, а также потенциально ресурсы его дочерних элементов, не загружаются. Если размер или ориентация окна браузера меняются, медиазапросы переоцениваются, и элементы скрываются или показываются в зависимости от новых результатов.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setNoloading(boolean value) {#setNoloading-boolean-}
```
public final void setNoloading(boolean value)
```


Атрибут noloading указывает, следует ли отключить "индикатор загрузки" для этого элемента.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setOn(String value) {#setOn-java.lang.String-}
```
public final void setOn(String value)
```


Атрибут on используется для установки обработчиков событий на элементах.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setPlaceHolder(boolean value) {#setPlaceHolder-boolean-}
```
public final void setPlaceHolder(boolean value)
```


Атрибут placeholder указывает, что элемент, помеченный этим атрибутом, выступает в качестве заполнителя для родительского элемента AMP.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | boolean |  |

### setSizes(String value) {#setSizes-java.lang.String-}
```
public final void setSizes(String value)
```


Значение атрибута AMP sizes — выражение sizes, которое выбирает определённый размер, соответствующий медиазапросу, на основе текущего размера окна.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ширина элемента.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### toAmpHtml() {#toAmpHtml--}
```
public String toAmpHtml()
```


Представляет HTML-версию атрибутов amp.

**Returns:**
java.lang.String -
### toHtml() {#toHtml--}
```
public String toHtml()
```


Представляет HTML-версию атрибутов.

**Returns:**
java.lang.String -
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

