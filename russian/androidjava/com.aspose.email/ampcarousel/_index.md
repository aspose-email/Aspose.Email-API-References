---
title: AmpCarousel
second_title: Aspose.Email for Android via Java API Reference
description: Компонент позволяет отображать несколько похожих фрагментов контента по горизонтальной оси.
type: docs
weight: 17
url: /ru/androidjava/com.aspose.email/ampcarousel/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.AmpComponent](../../com.aspose.email/ampcomponent)
```
public class AmpCarousel extends AmpComponent
```

Компонент позволяет отображать несколько похожих фрагментов контента по горизонтальной оси.
## Constructors

| Constructor | Описание |
| --- | --- |
| [AmpCarousel(int width, int height)](#AmpCarousel-int-int-) | Создать экземпляр формы AmpCarousel. |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttributes()](#getAttributes--) | AMP предоставляет набор общих атрибутов, которые расширяются многими компонентами AMP. |
| [getClass()](#getClass--) |  |
| [getFallback()](#getFallback--) | Fallback — это соглашение, позволяющее элементу сообщать читателю, что браузер не поддерживает данный элемент. |
| [getImages()](#getImages--) | Набор изображений для отображения. |
| [getPlaceholder()](#getPlaceholder--) | Элемент, помеченный атрибутом placeholder, служит заполнителем для родительского элемента AMP. |
| [getRequiredScript()](#getRequiredScript--) | Требуемый скрипт, который необходимо добавить в раздел head. |
| [getType()](#getType--) | Указывает тип отображения элементов карусели. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFallback(String value)](#setFallback-java.lang.String-) | Fallback — это соглашение, позволяющее элементу сообщать читателю, что браузер не поддерживает данный элемент. |
| [setPlaceholder(AmpComponent value)](#setPlaceholder-com.aspose.email.AmpComponent-) | Элемент, помеченный атрибутом placeholder, служит заполнителем для родительского элемента AMP. |
| [setType(int value)](#setType-int-) | Указывает тип отображения элементов карусели. |
| [toAmpHtml()](#toAmpHtml--) | Представляет HTML-версию компонента amp. |
| [toHtml()](#toHtml--) | Представляет HTML-версию компонента. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AmpCarousel(int width, int height) {#AmpCarousel-int-int-}
```
public AmpCarousel(int width, int height)
```


Создать экземпляр формы AmpCarousel.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| ширина | int | ширина AmpCarousel |
| высота | int | высота AmpCarousel |

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
### getImages() {#getImages--}
```
public final List<AmpImage> getImages()
```


Набор изображений для отображения.

**Returns:**
java.util.List<com.aspose.email.AmpImage>
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
### getType() {#getType--}
```
public final int getType()
```


Указывает тип отображения элементов карусели.

**Returns:**
int
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

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Указывает тип отображения элементов карусели.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

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

