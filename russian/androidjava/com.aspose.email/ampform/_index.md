---
title: AmpForm
second_title: Aspose.Email for Android via Java API Reference
description: Расширение amp-form позволяет создавать формы для отправки полей ввода в документе AMP.
type: docs
weight: 20
url: /ru/androidjava/com.aspose.email/ampform/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.AmpComponent](../../com.aspose.email/ampcomponent)
```
public class AmpForm extends AmpComponent
```

Расширение amp-form позволяет создавать формы для отправки полей ввода в документе AMP.
## Constructors

| Constructor | Описание |
| --- | --- |
| [AmpForm()](#AmpForm--) |  |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Указывает конечную точку сервера для обработки ввода формы. |
| [getActionXhr()](#getActionXhr--) | Указывает конечную точку сервера для обработки ввода формы и отправки формы через XMLHttpRequest (XHR). |
| [getAttributes()](#getAttributes--) | AMP предоставляет набор общих атрибутов, которые расширяются многими компонентами AMP. |
| [getClass()](#getClass--) |  |
| [getFallback()](#getFallback--) | Fallback — это соглашение, позволяющее элементу сообщать читателю, что браузер не поддерживает данный элемент. |
| [getFieldset()](#getFieldset--) | Список полей. |
| [getMethod()](#getMethod--) | Атрибут method сообщает серверу о методе запроса. |
| [getPlaceholder()](#getPlaceholder--) | Элемент, помеченный атрибутом placeholder, служит заполнителем для родительского элемента AMP. |
| [getRequiredScript()](#getRequiredScript--) | Требуемый скрипт, который необходимо добавить в раздел head. |
| [getTarget()](#getTarget--) | Указывает, где отображать ответ формы после её отправки. Значение должно быть \\_blank или \\_top. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(String value)](#setAction-java.lang.String-) | Указывает конечную точку сервера для обработки ввода формы. |
| [setActionXhr(String value)](#setActionXhr-java.lang.String-) | Указывает конечную точку сервера для обработки ввода формы и отправки формы через XMLHttpRequest (XHR). |
| [setFallback(String value)](#setFallback-java.lang.String-) | Fallback — это соглашение, позволяющее элементу сообщать читателю, что браузер не поддерживает данный элемент. |
| [setMethod(int value)](#setMethod-int-) | Атрибут method сообщает серверу о методе запроса. |
| [setPlaceholder(AmpComponent value)](#setPlaceholder-com.aspose.email.AmpComponent-) | Элемент, помеченный атрибутом placeholder, служит заполнителем для родительского элемента AMP. |
| [setTarget(int value)](#setTarget-int-) | Указывает, где отображать ответ формы после её отправки. Значение должно быть \\_blank или \\_top. |
| [toAmpHtml()](#toAmpHtml--) | Представляет HTML-версию компонента amp. |
| [toHtml()](#toHtml--) | Представляет HTML-версию компонента. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AmpForm() {#AmpForm--}
```
public AmpForm()
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
### getAction() {#getAction--}
```
public final String getAction()
```


Указывает конечную точку сервера для обработки ввода формы. Значение должно быть URL https (абсолютным или относительным) и не должно быть ссылкой на CDN.

**Returns:**
java.lang.String
### getActionXhr() {#getActionXhr--}
```
public final String getActionXhr()
```


Указывает конечную точку сервера для обработки ввода формы и отправки формы через XMLHttpRequest (XHR).

**Returns:**
java.lang.String
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
### getFieldset() {#getFieldset--}
```
public final List<FormField> getFieldset()
```


Список полей.

**Returns:**
java.util.List<com.aspose.email.FormField>
### getMethod() {#getMethod--}
```
public final int getMethod()
```


Атрибут method сообщает серверу о методе запроса.

**Returns:**
int
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
### getTarget() {#getTarget--}
```
public final int getTarget()
```


Указывает, где отображать ответ формы после её отправки. Значение должно быть \\_blank или \\_top.

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




### setAction(String value) {#setAction-java.lang.String-}
```
public final void setAction(String value)
```


Указывает конечную точку сервера для обработки ввода формы. Значение должно быть URL https (абсолютным или относительным) и не должно быть ссылкой на CDN.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setActionXhr(String value) {#setActionXhr-java.lang.String-}
```
public final void setActionXhr(String value)
```


Указывает конечную точку сервера для обработки ввода формы и отправки формы через XMLHttpRequest (XHR).

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

### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


Атрибут method сообщает серверу о методе запроса.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | int |  |

### setPlaceholder(AmpComponent value) {#setPlaceholder-com.aspose.email.AmpComponent-}
```
public final void setPlaceholder(AmpComponent value)
```


Элемент, помеченный атрибутом placeholder, служит заполнителем для родительского элемента AMP. Если указано, элемент placeholder должен быть непосредственным дочерним элементом элемента AMP.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| value | [AmpComponent](../../com.aspose.email/ampcomponent) |  |

### setTarget(int value) {#setTarget-int-}
```
public final void setTarget(int value)
```


Указывает, где отображать ответ формы после её отправки. Значение должно быть \\_blank или \\_top.

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

