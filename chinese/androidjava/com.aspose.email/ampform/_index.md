---
title: AmpForm
second_title: Aspose.Email for Android via Java API 参考
description: amp-form 扩展允许您在 AMP 文档中创建表单以提交输入字段。
type: docs
weight: 20
url: /zh/androidjava/com.aspose.email/ampform/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.AmpComponent](../../com.aspose.email/ampcomponent)
```
public class AmpForm extends AmpComponent
```

amp-form 扩展允许您在 AMP 文档中创建表单以提交输入字段。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AmpForm()](#AmpForm--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | 指定用于处理表单输入的服务器端点。 |
| [getActionXhr()](#getActionXhr--) | 指定用于处理表单输入并通过 XMLHttpRequest (XHR) 提交表单的服务器端点。 |
| [getAttributes()](#getAttributes--) | AMP 提供了一组通用属性，这些属性已扩展到许多 AMP 组件。 |
| [getClass()](#getClass--) |  |
| [getFallback()](#getFallback--) | 回退是一种约定，允许元素向阅读器传达浏览器不支持该元素的情况。 |
| [getFieldset()](#getFieldset--) | 字段列表。 |
| [getMethod()](#getMethod--) | method 属性告诉服务器请求方法。 |
| [getPlaceholder()](#getPlaceholder--) | 带有 placeholder 属性的元素充当父 AMP 元素的占位符。 |
| [getRequiredScript()](#getRequiredScript--) | 必需的脚本必须添加到 head 部分。 |
| [getTarget()](#getTarget--) | 指示提交表单后在何处显示表单响应。值必须为 \\_blank 或 \\_top。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(String value)](#setAction-java.lang.String-) | 指定用于处理表单输入的服务器端点。 |
| [setActionXhr(String value)](#setActionXhr-java.lang.String-) | 指定用于处理表单输入并通过 XMLHttpRequest (XHR) 提交表单的服务器端点。 |
| [setFallback(String value)](#setFallback-java.lang.String-) | 回退是一种约定，允许元素向阅读器传达浏览器不支持该元素的情况。 |
| [setMethod(int value)](#setMethod-int-) | method 属性告诉服务器请求方法。 |
| [setPlaceholder(AmpComponent value)](#setPlaceholder-com.aspose.email.AmpComponent-) | 带有 placeholder 属性的元素充当父 AMP 元素的占位符。 |
| [setTarget(int value)](#setTarget-int-) | 指示提交表单后在何处显示表单响应。值必须为 \\_blank 或 \\_top。 |
| [toAmpHtml()](#toAmpHtml--) | 表示组件的 amp html 版本。 |
| [toHtml()](#toHtml--) | 表示组件的 html 版本。 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAction() {#getAction--}
```
public final String getAction()
```


指定用于处理表单输入的服务器端点。该值必须是 https URL（绝对或相对），且不能是 CDN 链接。

**Returns:**
java.lang.String
### getActionXhr() {#getActionXhr--}
```
public final String getActionXhr()
```


指定用于处理表单输入并通过 XMLHttpRequest (XHR) 提交表单的服务器端点。

**Returns:**
java.lang.String
### getAttributes() {#getAttributes--}
```
public final AmpAttributes getAttributes()
```


AMP 提供了一组通用属性，这些属性已扩展到许多 AMP 组件。

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


回退是一种约定，允许元素向阅读器传达浏览器不支持该元素的情况。

**Returns:**
java.lang.String
### getFieldset() {#getFieldset--}
```
public final List<FormField> getFieldset()
```


字段列表。

**Returns:**
java.util.List<com.aspose.email.FormField>
### getMethod() {#getMethod--}
```
public final int getMethod()
```


method 属性告诉服务器请求方法。

**Returns:**
int
### getPlaceholder() {#getPlaceholder--}
```
public final AmpComponent getPlaceholder()
```


带有 placeholder 属性的元素充当父 AMP 元素的占位符。如果指定，placeholder 元素必须是 AMP 元素的直接子元素。

**Returns:**
[AmpComponent](../../com.aspose.email/ampcomponent)
### getRequiredScript() {#getRequiredScript--}
```
public String getRequiredScript()
```


必需的脚本必须添加到 head 部分。

**Returns:**
java.lang.String
### getTarget() {#getTarget--}
```
public final int getTarget()
```


指示提交表单后在何处显示表单响应。值必须为 \\_blank 或 \\_top。

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


指定用于处理表单输入的服务器端点。该值必须是 https URL（绝对或相对），且不能是 CDN 链接。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setActionXhr(String value) {#setActionXhr-java.lang.String-}
```
public final void setActionXhr(String value)
```


指定用于处理表单输入并通过 XMLHttpRequest (XHR) 提交表单的服务器端点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setFallback(String value) {#setFallback-java.lang.String-}
```
public final void setFallback(String value)
```


回退是一种约定，允许元素向阅读器传达浏览器不支持该元素的情况。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


method 属性告诉服务器请求方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setPlaceholder(AmpComponent value) {#setPlaceholder-com.aspose.email.AmpComponent-}
```
public final void setPlaceholder(AmpComponent value)
```


带有 placeholder 属性的元素充当父 AMP 元素的占位符。如果指定，placeholder 元素必须是 AMP 元素的直接子元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [AmpComponent](../../com.aspose.email/ampcomponent) |  |

### setTarget(int value) {#setTarget-int-}
```
public final void setTarget(int value)
```


指示提交表单后在何处显示表单响应。值必须为 \\_blank 或 \\_top。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### toAmpHtml() {#toAmpHtml--}
```
public String toAmpHtml()
```


表示组件的 amp html 版本。

**Returns:**
java.lang.String -
### toHtml() {#toHtml--}
```
public String toHtml()
```


表示组件的 html 版本。

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

