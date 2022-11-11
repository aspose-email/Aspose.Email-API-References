---
title: AmpForm
second_title: Aspose.Email for Java API Reference
description: The amp-form extension allows you to create forms to submit input fields in an AMP document.
type: docs
weight: 24
url: /java/com.aspose.email/ampform/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.AmpComponent](../../com.aspose.email/ampcomponent)
```
public class AmpForm extends AmpComponent
```

The amp-form extension allows you to create forms to submit input fields in an AMP document.
## Constructors

| Constructor | Description |
| --- | --- |
| [AmpForm()](#AmpForm--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Specifies a server endpoint to handle the form input. |
| [getActionXhr()](#getActionXhr--) | Specifies a server endpoint to handle the form input and submit the form via XMLHttpRequest (XHR). |
| [getAttributes()](#getAttributes--) | AMP provides a set of common attributes that are extended to many AMP components. |
| [getClass()](#getClass--) |  |
| [getFallback()](#getFallback--) | A fallback is a convention that allows the element to communicate to the reader that the browser does not support the element. |
| [getFieldset()](#getFieldset--) | List of fields. |
| [getMethod()](#getMethod--) | The method attribute tells the server about the request method. |
| [getPlaceholder()](#getPlaceholder--) | The element marked with the placeholder attribute acts as a placeholder for the parent AMP element. |
| [getRequiredScript()](#getRequiredScript--) | Required script that muct be added to head section. |
| [getTarget()](#getTarget--) | Indicates where to display the form response after submitting the form.The value must be \_blank or \_top. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(String value)](#setAction-java.lang.String-) | Specifies a server endpoint to handle the form input. |
| [setActionXhr(String value)](#setActionXhr-java.lang.String-) | Specifies a server endpoint to handle the form input and submit the form via XMLHttpRequest (XHR). |
| [setFallback(String value)](#setFallback-java.lang.String-) | A fallback is a convention that allows the element to communicate to the reader that the browser does not support the element. |
| [setMethod(int value)](#setMethod-int-) | The method attribute tells the server about the request method. |
| [setPlaceholder(AmpComponent value)](#setPlaceholder-com.aspose.email.AmpComponent-) | The element marked with the placeholder attribute acts as a placeholder for the parent AMP element. |
| [setTarget(int value)](#setTarget-int-) | Indicates where to display the form response after submitting the form.The value must be \_blank or \_top. |
| [toAmpHtml()](#toAmpHtml--) | Represents amp html version of component. |
| [toHtml()](#toHtml--) | Represents html version of component. |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAction() {#getAction--}
```
public final String getAction()
```


Specifies a server endpoint to handle the form input. The value must be an https URL (absolute or relative) and must not be a link to a CDN

**Returns:**
java.lang.String
### getActionXhr() {#getActionXhr--}
```
public final String getActionXhr()
```


Specifies a server endpoint to handle the form input and submit the form via XMLHttpRequest (XHR).

**Returns:**
java.lang.String
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
### getFieldset() {#getFieldset--}
```
public final List<FormField> getFieldset()
```


List of fields.

**Returns:**
java.util.List<com.aspose.email.FormField>
### getMethod() {#getMethod--}
```
public final int getMethod()
```


The method attribute tells the server about the request method.

**Returns:**
int
### getPlaceholder() {#getPlaceholder--}
```
public final AmpComponent getPlaceholder()
```


The element marked with the placeholder attribute acts as a placeholder for the parent AMP element. If specified, a placeholder element must be a direct child of the AMP element.

**Returns:**
[AmpComponent](../../com.aspose.email/ampcomponent)
### getRequiredScript() {#getRequiredScript--}
```
public String getRequiredScript()
```


Required script that muct be added to head section.

**Returns:**
java.lang.String
### getTarget() {#getTarget--}
```
public final int getTarget()
```


Indicates where to display the form response after submitting the form.The value must be \_blank or \_top.

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


Specifies a server endpoint to handle the form input. The value must be an https URL (absolute or relative) and must not be a link to a CDN

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setActionXhr(String value) {#setActionXhr-java.lang.String-}
```
public final void setActionXhr(String value)
```


Specifies a server endpoint to handle the form input and submit the form via XMLHttpRequest (XHR).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setFallback(String value) {#setFallback-java.lang.String-}
```
public final void setFallback(String value)
```


A fallback is a convention that allows the element to communicate to the reader that the browser does not support the element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


The method attribute tells the server about the request method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPlaceholder(AmpComponent value) {#setPlaceholder-com.aspose.email.AmpComponent-}
```
public final void setPlaceholder(AmpComponent value)
```


The element marked with the placeholder attribute acts as a placeholder for the parent AMP element. If specified, a placeholder element must be a direct child of the AMP element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [AmpComponent](../../com.aspose.email/ampcomponent) |  |

### setTarget(int value) {#setTarget-int-}
```
public final void setTarget(int value)
```


Indicates where to display the form response after submitting the form.The value must be \_blank or \_top.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### toAmpHtml() {#toAmpHtml--}
```
public String toAmpHtml()
```


Represents amp html version of component.

**Returns:**
java.lang.String - 
### toHtml() {#toHtml--}
```
public String toHtml()
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

