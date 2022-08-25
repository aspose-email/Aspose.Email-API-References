---
title: AmpAnim
second_title: Aspose.Email for Java API Reference
description:  A runtime-managed animated image typically a GIF.
type: docs
weight: 19
url: /java/com.aspose.email/ampanim/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.AmpComponent](../../com.aspose.email/ampcomponent), [com.aspose.email.AmpImage](../../com.aspose.email/ampimage)
```
public class AmpAnim extends AmpImage
```

A runtime-managed animated image, typically a GIF.
## Constructors

| Constructor | Description |
| --- | --- |
| [AmpAnim(int width, int height)](#AmpAnim-int-int-) | Creates instance of AmpAnim. |
## Methods

| Method | Description |
| --- | --- |
| [getAttribution()](#getAttribution--) | A string that indicates the attribution of the image. |
| [setAttribution(String value)](#setAttribution-java.lang.String-) | A string that indicates the attribution of the image. |
| [getRequiredScript()](#getRequiredScript--) | Required script that muct be added to head section. |
| [toAmpHtml()](#toAmpHtml--) | Represents amp html version of component. |
### AmpAnim(int width, int height) {#AmpAnim-int-int-}
```
public AmpAnim(int width, int height)
```


Creates instance of AmpAnim.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | width of AmpAnim |
| height | int | height of AmpAnim |

### getAttribution() {#getAttribution--}
```
public final String getAttribution()
```


A string that indicates the attribution of the image.

**Returns:**
java.lang.String
### setAttribution(String value) {#setAttribution-java.lang.String-}
```
public final void setAttribution(String value)
```


A string that indicates the attribution of the image.

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
