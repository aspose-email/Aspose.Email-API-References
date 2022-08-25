---
title: AmpForm
second_title: Aspose.Email for Android via Java API Reference
description:  The amp-form extension allows you to create forms to submit input fields in an AMP document.
type: docs
weight: 20
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
| [getFieldset()](#getFieldset--) | List of fields. |
| [getMethod()](#getMethod--) | The method attribute tells the server about the request method. |
| [setMethod(int value)](#setMethod-int-) | The method attribute tells the server about the request method. |
| [getTarget()](#getTarget--) | Indicates where to display the form response after submitting the form.The value must be \_blank or \_top. |
| [setTarget(int value)](#setTarget-int-) | Indicates where to display the form response after submitting the form.The value must be \_blank or \_top. |
| [getAction()](#getAction--) | Specifies a server endpoint to handle the form input. |
| [setAction(String value)](#setAction-java.lang.String-) | Specifies a server endpoint to handle the form input. |
| [getActionXhr()](#getActionXhr--) | Specifies a server endpoint to handle the form input and submit the form via XMLHttpRequest (XHR). |
| [setActionXhr(String value)](#setActionXhr-java.lang.String-) | Specifies a server endpoint to handle the form input and submit the form via XMLHttpRequest (XHR). |
| [getRequiredScript()](#getRequiredScript--) | Required script that muct be added to head section. |
| [toAmpHtml()](#toAmpHtml--) | Represents amp html version of component. |
| [toHtml()](#toHtml--) | Represents html version of component. |
### AmpForm() {#AmpForm--}
```
public AmpForm()
```


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
### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


The method attribute tells the server about the request method.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTarget() {#getTarget--}
```
public final int getTarget()
```


Indicates where to display the form response after submitting the form.The value must be \_blank or \_top.

**Returns:**
int
### setTarget(int value) {#setTarget-int-}
```
public final void setTarget(int value)
```


Indicates where to display the form response after submitting the form.The value must be \_blank or \_top.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAction() {#getAction--}
```
public final String getAction()
```


Specifies a server endpoint to handle the form input. The value must be an https URL (absolute or relative) and must not be a link to a CDN

**Returns:**
java.lang.String
### setAction(String value) {#setAction-java.lang.String-}
```
public final void setAction(String value)
```


Specifies a server endpoint to handle the form input. The value must be an https URL (absolute or relative) and must not be a link to a CDN

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getActionXhr() {#getActionXhr--}
```
public final String getActionXhr()
```


Specifies a server endpoint to handle the form input and submit the form via XMLHttpRequest (XHR).

**Returns:**
java.lang.String
### setActionXhr(String value) {#setActionXhr-java.lang.String-}
```
public final void setActionXhr(String value)
```


Specifies a server endpoint to handle the form input and submit the form via XMLHttpRequest (XHR).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getRequiredScript() {#getRequiredScript--}
```
public String getRequiredScript()
```


Required script that muct be added to head section.

**Returns:**
java.lang.String
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
