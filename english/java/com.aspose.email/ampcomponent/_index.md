---
title: AmpComponent
second_title: Aspose.Email for Java API Reference
description:  Base class to representation amp components.
type: docs
weight: 22
url: /java/com.aspose.email/ampcomponent/
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
| [getRequiredScript()](#getRequiredScript--) | Required script that muct be added to head section. |
| [toAmpHtml()](#toAmpHtml--) | Represents amp html version of component. |
| [toHtml()](#toHtml--) | Represents html version of component. |
| [getAttributes()](#getAttributes--) | AMP provides a set of common attributes that are extended to many AMP components. |
| [getFallback()](#getFallback--) | A fallback is a convention that allows the element to communicate to the reader that the browser does not support the element. |
| [setFallback(String value)](#setFallback-java.lang.String-) | A fallback is a convention that allows the element to communicate to the reader that the browser does not support the element. |
| [getPlaceholder()](#getPlaceholder--) | The element marked with the placeholder attribute acts as a placeholder for the parent AMP element. |
| [setPlaceholder(AmpComponent value)](#setPlaceholder-com.aspose.email.AmpComponent-) | The element marked with the placeholder attribute acts as a placeholder for the parent AMP element. |
### AmpComponent() {#AmpComponent--}
```
public AmpComponent()
```


### getRequiredScript() {#getRequiredScript--}
```
public abstract String getRequiredScript()
```


Required script that muct be added to head section.

**Returns:**
java.lang.String
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
### getAttributes() {#getAttributes--}
```
public final AmpAttributes getAttributes()
```


AMP provides a set of common attributes that are extended to many AMP components.

**Returns:**
[AmpAttributes](../../com.aspose.email/ampattributes)
### getFallback() {#getFallback--}
```
public final String getFallback()
```


A fallback is a convention that allows the element to communicate to the reader that the browser does not support the element.

**Returns:**
java.lang.String
### setFallback(String value) {#setFallback-java.lang.String-}
```
public final void setFallback(String value)
```


A fallback is a convention that allows the element to communicate to the reader that the browser does not support the element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPlaceholder() {#getPlaceholder--}
```
public final AmpComponent getPlaceholder()
```


The element marked with the placeholder attribute acts as a placeholder for the parent AMP element. If specified, a placeholder element must be a direct child of the AMP element.

**Returns:**
[AmpComponent](../../com.aspose.email/ampcomponent)
### setPlaceholder(AmpComponent value) {#setPlaceholder-com.aspose.email.AmpComponent-}
```
public final void setPlaceholder(AmpComponent value)
```


The element marked with the placeholder attribute acts as a placeholder for the parent AMP element. If specified, a placeholder element must be a direct child of the AMP element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [AmpComponent](../../com.aspose.email/ampcomponent) |  |

