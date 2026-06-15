---
title: AmpComponent
second_title: Aspose.Email for Android via Java API Reference
description: Базовый класс для представления amp-компонентов.
type: docs
weight: 18
url: /ru/androidjava/com.aspose.email/ampcomponent/
---

**Inheritance:**
java.lang.Object
```
public abstract class AmpComponent
```

Базовый класс для представления amp-компонентов.
## Constructors

| Constructor | Описание |
| --- | --- |
| [AmpComponent()](#AmpComponent--) |  |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttributes()](#getAttributes--) | AMP предоставляет набор общих атрибутов, которые расширяются многими компонентами AMP. |
| [getClass()](#getClass--) |  |
| [getFallback()](#getFallback--) | Fallback — это соглашение, позволяющее элементу сообщать читателю, что браузер не поддерживает данный элемент. |
| [getPlaceholder()](#getPlaceholder--) | Элемент, помеченный атрибутом placeholder, служит заполнителем для родительского элемента AMP. |
| [getRequiredScript()](#getRequiredScript--) | Требуемый скрипт, который необходимо добавить в раздел head. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFallback(String value)](#setFallback-java.lang.String-) | Fallback — это соглашение, позволяющее элементу сообщать читателю, что браузер не поддерживает данный элемент. |
| [setPlaceholder(AmpComponent value)](#setPlaceholder-com.aspose.email.AmpComponent-) | Элемент, помеченный атрибутом placeholder, служит заполнителем для родительского элемента AMP. |
| [toAmpHtml()](#toAmpHtml--) | Представляет HTML-версию компонента amp. |
| [toHtml()](#toHtml--) | Представляет HTML-версию компонента. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AmpComponent() {#AmpComponent--}
```
public AmpComponent()
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
public abstract String getRequiredScript()
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

### toAmpHtml() {#toAmpHtml--}
```
public abstract String toAmpHtml()
```


Представляет HTML-версию компонента amp.

**Returns:**
java.lang.String -
### toHtml() {#toHtml--}
```
public abstract String toHtml()
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

