---
title: AmpImage
second_title: Aspose.Email for Java API Reference
description:  
type: docs
weight: 25
url: /java/com.aspose.email/ampimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.AmpComponent](../../com.aspose.email/ampcomponent)
```
public class AmpImage extends AmpComponent
```
## Constructors

| Constructor | Description |
| --- | --- |
| [AmpImage(int width, int height)](#AmpImage-int-int-) | Create instance of AmpImage. |
## Methods

| Method | Description |
| --- | --- |
| [getSrc()](#getSrc--) | Similar to the src attribute on the img tag. |
| [setSrc(String value)](#setSrc-java.lang.String-) | Similar to the src attribute on the img tag. |
| [getAlt()](#getAlt--) | A string of alternate text, similar to the alt attribute on img. |
| [setAlt(String value)](#setAlt-java.lang.String-) | A string of alternate text, similar to the alt attribute on img. |
| [isValid()](#isValid--) | Indicates whether this image is valid of AmpImage. |
| [getRequiredScript()](#getRequiredScript--) | Required script that muct be added to head section. |
| [toAmpHtml()](#toAmpHtml--) | Represents amp html version of component. |
| [toHtml()](#toHtml--) | Represents html version of component. |
### AmpImage(int width, int height) {#AmpImage-int-int-}
```
public AmpImage(int width, int height)
```


Create instance of AmpImage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | width of AmpImage |
| height | int | height of AmpImage |

### getSrc() {#getSrc--}
```
public final String getSrc()
```


Similar to the src attribute on the img tag. The value must be a URL that points to a publicly-cacheable image file

**Returns:**
java.lang.String
### setSrc(String value) {#setSrc-java.lang.String-}
```
public final void setSrc(String value)
```


Similar to the src attribute on the img tag. The value must be a URL that points to a publicly-cacheable image file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlt() {#getAlt--}
```
public final String getAlt()
```


A string of alternate text, similar to the alt attribute on img.

**Returns:**
java.lang.String
### setAlt(String value) {#setAlt-java.lang.String-}
```
public final void setAlt(String value)
```


A string of alternate text, similar to the alt attribute on img.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isValid() {#isValid--}
```
public final boolean isValid()
```


Indicates whether this image is valid of AmpImage.

**Returns:**
boolean
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
