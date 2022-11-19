---
title: AmpComponent
second_title: Aspose.Email for Android via Java API Reference
description: Base class to representation amp components.
type: docs
weight: 18
url: /androidjava/com.aspose.email/ampcomponent/
---

**Inheritance:**
java.lang.Object
```
public abstract class AmpComponent
```

Base class to representation amp components.
## Constructors

| Constructor | Description |
| --- | --- |
| [AmpComponent()](#AmpComponent--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttributes()](#getAttributes--) | AMP provides a set of common attributes that are extended to many AMP components. |
| [getClass()](#getClass--) |  |
| [getFallback()](#getFallback--) | A fallback is a convention that allows the element to communicate to the reader that the browser does not support the element. |
| [getPlaceholder()](#getPlaceholder--) | The element marked with the placeholder attribute acts as a placeholder for the parent AMP element. |
| [getRequiredScript()](#getRequiredScript--) | Required script that muct be added to head section. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFallback(String value)](#setFallback-java.lang.String-) | A fallback is a convention that allows the element to communicate to the reader that the browser does not support the element. |
| [setPlaceholder(AmpComponent value)](#setPlaceholder-com.aspose.email.AmpComponent-) | The element marked with the placeholder attribute acts as a placeholder for the parent AMP element. |
| [toAmpHtml()](#toAmpHtml--) | Represents amp html version of component. |
| [toHtml()](#toHtml--) | Represents html version of component. |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAttributes() {#getAttributes--}
```
public final AmpAttributes getAttributes()
```


AMP provides a set of common attributes that are extended to many AMP components.

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


A fallback is a convention that allows the element to communicate to the reader that the browser does not support the element.

**Returns:**
java.lang.String
### getPlaceholder() {#getPlaceholder--}
```
public final AmpComponent getPlaceholder()
```


The element marked with the placeholder attribute acts as a placeholder for the parent AMP element. If specified, a placeholder element must be a direct child of the AMP element.

**Returns:**
[AmpComponent](../../com.aspose.email/ampcomponent)
### getRequiredScript() {#getRequiredScript--}
```
public abstract String getRequiredScript()
```


Required script that muct be added to head section.

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


A fallback is a convention that allows the element to communicate to the reader that the browser does not support the element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPlaceholder(AmpComponent value) {#setPlaceholder-com.aspose.email.AmpComponent-}
```
public final void setPlaceholder(AmpComponent value)
```


The element marked with the placeholder attribute acts as a placeholder for the parent AMP element. If specified, a placeholder element must be a direct child of the AMP element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [AmpComponent](../../com.aspose.email/ampcomponent) |  |

### toAmpHtml() {#toAmpHtml--}
```
public abstract String toAmpHtml()
```


Represents amp html version of component.

**Returns:**
java.lang.String - 
### toHtml() {#toHtml--}
```
public abstract String toHtml()
```


Represents html version of component.

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

