---
title: AmpTimeago
second_title: Aspose.Email for Android via Java API Reference
description: Предоставляет нечёткие метки времени, форматируя даты как X времени назад
type: docs
weight: 23
url: /ru/androidjava/com.aspose.email/amptimeago/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.AmpComponent](../../com.aspose.email/ampcomponent)
```
public class AmpTimeago extends AmpComponent
```

Предоставляет нечёткие метки времени, форматируя даты как "X time ago".
## Constructors

| Constructor | Описание |
| --- | --- |
| [AmpTimeago(Date dateTime)](#AmpTimeago-java.util.Date-) | Создать экземпляр AmpTimeago. |
| [AmpTimeago(Date dateTime, int width, int height)](#AmpTimeago-java.util.Date-int-int-) | Создать экземпляр AmpTimeago. |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttributes()](#getAttributes--) | AMP предоставляет набор общих атрибутов, которые расширяются многими компонентами AMP. |
| [getClass()](#getClass--) |  |
| [getCutoff()](#getCutoff--) | Отображать исходную дату, если промежуток времени превышает порог (секунды). |
| [getDateTime()](#getDateTime--) | Дата и время. |
| [getFallback()](#getFallback--) | Fallback — это соглашение, позволяющее элементу сообщать читателю, что браузер не поддерживает данный элемент. |
| [getLocale()](#getLocale--) | По умолчанию локаль установлена на en; однако вы можете указать другие локали. |
| [getPlaceholder()](#getPlaceholder--) | Элемент, помеченный атрибутом placeholder, служит заполнителем для родительского элемента AMP. |
| [getRequiredScript()](#getRequiredScript--) | Требуемый скрипт, который необходимо добавить в раздел head. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCutoff(int value)](#setCutoff-int-) | Отображать исходную дату, если промежуток времени превышает порог (секунды). |
| [setDateTime(Date value)](#setDateTime-java.util.Date-) | Дата и время. |
| [setFallback(String value)](#setFallback-java.lang.String-) | Fallback — это соглашение, позволяющее элементу сообщать читателю, что браузер не поддерживает данный элемент. |
| [setLocale(String value)](#setLocale-java.lang.String-) | По умолчанию локаль установлена на en; однако вы можете указать другие локали. |
| [setPlaceholder(AmpComponent value)](#setPlaceholder-com.aspose.email.AmpComponent-) | Элемент, помеченный атрибутом placeholder, служит заполнителем для родительского элемента AMP. |
| [toAmpHtml()](#toAmpHtml--) | Представляет HTML-версию компонента amp. |
| [toHtml()](#toHtml--) | Представляет HTML-версию компонента. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AmpTimeago(Date dateTime) {#AmpTimeago-java.util.Date-}
```
public AmpTimeago(Date dateTime)
```


Создать экземпляр AmpTimeago.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| dateTime | java.util.Date |  |

### AmpTimeago(Date dateTime, int width, int height) {#AmpTimeago-java.util.Date-int-int-}
```
public AmpTimeago(Date dateTime, int width, int height)
```


Создать экземпляр AmpTimeago.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| dateTime | java.util.Date |  |
| ширина | int |  |
| высота | int |  |

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
### getAttributes() {#getAttributes--}
```
public final AmpAttributes getAttributes()
```


AMP предоставляет набор общих атрибутов, которые расширяются многими компонентами AMP.

**Returns:**
[AmpAttributes](../../com.aspose.email/ampattributes)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCutoff() {#getCutoff--}
```
public final int getCutoff()
```


Отображать исходную дату, если промежуток времени превышает порог (секунды).

**Returns:**
int
### getDateTime() {#getDateTime--}
```
public final Date getDateTime()
```


Дата и время.

**Returns:**
java.util.Date
### getFallback() {#getFallback--}
```
public final String getFallback()
```


Fallback — это соглашение, позволяющее элементу сообщать читателю, что браузер не поддерживает данный элемент.

**Returns:**
java.lang.String
### getLocale() {#getLocale--}
```
public final String getLocale()
```


По умолчанию локаль установлена на en; однако вы можете указать другие локали. См. полный список поддерживаемых локалей https://amp.dev/documentation/components/amp-timeago/?format=email

**Returns:**
java.lang.String
### getPlaceholder() {#getPlaceholder--}
```
public final AmpComponent getPlaceholder()
```


Элемент, помеченный атрибутом placeholder, служит заполнителем для родительского элемента AMP. Если указано, элемент placeholder должен быть непосредственным дочерним элементом элемента AMP.

**Returns:**
[AmpComponent](../../com.aspose.email/ampcomponent)
### getRequiredScript() {#getRequiredScript--}
```
public String getRequiredScript()
```


Требуемый скрипт, который необходимо добавить в раздел head.

**Returns:**
java.lang.String
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




### setCutoff(int value) {#setCutoff-int-}
```
public final void setCutoff(int value)
```


Отображать исходную дату, если промежуток времени превышает порог (секунды).

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setDateTime(Date value) {#setDateTime-java.util.Date-}
```
public final void setDateTime(Date value)
```


Дата и время.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### setFallback(String value) {#setFallback-java.lang.String-}
```
public final void setFallback(String value)
```


Fallback — это соглашение, позволяющее элементу сообщать читателю, что браузер не поддерживает данный элемент.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setLocale(String value) {#setLocale-java.lang.String-}
```
public final void setLocale(String value)
```


По умолчанию локаль установлена на en; однако вы можете указать другие локали. См. полный список поддерживаемых локалей https://amp.dev/documentation/components/amp-timeago/?format=email

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setPlaceholder(AmpComponent value) {#setPlaceholder-com.aspose.email.AmpComponent-}
```
public final void setPlaceholder(AmpComponent value)
```


Элемент, помеченный атрибутом placeholder, служит заполнителем для родительского элемента AMP. Если указано, элемент placeholder должен быть непосредственным дочерним элементом элемента AMP.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [AmpComponent](../../com.aspose.email/ampcomponent) |  |

### toAmpHtml() {#toAmpHtml--}
```
public String toAmpHtml()
```


Представляет HTML-версию компонента amp.

**Returns:**
java.lang.String -
### toHtml() {#toHtml--}
```
public String toHtml()
```


Представляет HTML-версию компонента.

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

