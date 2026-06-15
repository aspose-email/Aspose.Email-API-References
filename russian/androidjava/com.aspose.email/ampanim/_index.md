---
title: AmpAnim
second_title: Aspose.Email for Android via Java API Reference
description: Анимированное изображение, управляемое во время выполнения, обычно GIF.
type: docs
weight: 15
url: /ru/androidjava/com.aspose.email/ampanim/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.AmpComponent](../../com.aspose.email/ampcomponent), [com.aspose.email.AmpImage](../../com.aspose.email/ampimage)
```
public class AmpAnim extends AmpImage
```

Анимированное изображение, управляемое во время выполнения, обычно GIF.
## Constructors

| Constructor | Описание |
| --- | --- |
| [AmpAnim(int width, int height)](#AmpAnim-int-int-) | Creates instance of AmpAnim. |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlt()](#getAlt--) | Строка альтернативного текста, аналогичная атрибуту alt в img. |
| [getAttributes()](#getAttributes--) | AMP предоставляет набор общих атрибутов, которые расширяются многими компонентами AMP. |
| [getAttribution()](#getAttribution--) | A string that indicates the attribution of the image. |
| [getClass()](#getClass--) |  |
| [getFallback()](#getFallback--) | Fallback — это соглашение, позволяющее элементу сообщать читателю, что браузер не поддерживает данный элемент. |
| [getPlaceholder()](#getPlaceholder--) | Элемент, помеченный атрибутом placeholder, служит заполнителем для родительского элемента AMP. |
| [getRequiredScript()](#getRequiredScript--) | Требуемый скрипт, который необходимо добавить в раздел head. |
| [getSrc()](#getSrc--) | Аналогично атрибуту src в теге img. |
| [hashCode()](#hashCode--) |  |
| [isValid()](#isValid--) | Указывает, является ли это изображение действительным для AmpImage. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlt(String value)](#setAlt-java.lang.String-) | Строка альтернативного текста, аналогичная атрибуту alt в img. |
| [setAttribution(String value)](#setAttribution-java.lang.String-) | A string that indicates the attribution of the image. |
| [setFallback(String value)](#setFallback-java.lang.String-) | Fallback — это соглашение, позволяющее элементу сообщать читателю, что браузер не поддерживает данный элемент. |
| [setPlaceholder(AmpComponent value)](#setPlaceholder-com.aspose.email.AmpComponent-) | Элемент, помеченный атрибутом placeholder, служит заполнителем для родительского элемента AMP. |
| [setSrc(String value)](#setSrc-java.lang.String-) | Аналогично атрибуту src в теге img. |
| [toAmpHtml()](#toAmpHtml--) | Представляет HTML-версию компонента amp. |
| [toHtml()](#toHtml--) | Представляет HTML-версию компонента. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AmpAnim(int width, int height) {#AmpAnim-int-int-}
```
public AmpAnim(int width, int height)
```


Creates instance of AmpAnim.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| ширина | int | width of AmpAnim |
| высота | int | height of AmpAnim |

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
### getAlt() {#getAlt--}
```
public final String getAlt()
```


Строка альтернативного текста, аналогичная атрибуту alt в img.

**Returns:**
java.lang.String
### getAttributes() {#getAttributes--}
```
public final AmpAttributes getAttributes()
```


AMP предоставляет набор общих атрибутов, которые расширяются многими компонентами AMP.

**Returns:**
[AmpAttributes](../../com.aspose.email/ampattributes)
### getAttribution() {#getAttribution--}
```
public final String getAttribution()
```


A string that indicates the attribution of the image.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFallback() {#getFallback--}
```
public final String getFallback()
```


Fallback — это соглашение, позволяющее элементу сообщать читателю, что браузер не поддерживает данный элемент.

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
### getSrc() {#getSrc--}
```
public final String getSrc()
```


Аналогично атрибуту src в теге img. Значение должно быть URL, указывающим на общедоступный кэшируемый файл изображения.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isValid() {#isValid--}
```
public final boolean isValid()
```


Указывает, является ли это изображение действительным для AmpImage.

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




### setAlt(String value) {#setAlt-java.lang.String-}
```
public final void setAlt(String value)
```


Строка альтернативного текста, аналогичная атрибуту alt в img.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setAttribution(String value) {#setAttribution-java.lang.String-}
```
public final void setAttribution(String value)
```


A string that indicates the attribution of the image.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setFallback(String value) {#setFallback-java.lang.String-}
```
public final void setFallback(String value)
```


Fallback — это соглашение, позволяющее элементу сообщать читателю, что браузер не поддерживает данный элемент.

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

### setSrc(String value) {#setSrc-java.lang.String-}
```
public final void setSrc(String value)
```


Аналогично атрибуту src в теге img. Значение должно быть URL, указывающим на общедоступный кэшируемый файл изображения.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

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

