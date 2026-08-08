---
title: AmpAnim
second_title: Aspose.Email for Android via Java API 参考
description: 运行时管理的动画图像，通常为 GIF。
type: docs
weight: 15
url: /zh/androidjava/com.aspose.email/ampanim/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.AmpComponent](../../com.aspose.email/ampcomponent), [com.aspose.email.AmpImage](../../com.aspose.email/ampimage)
```
public class AmpAnim extends AmpImage
```

一种运行时管理的动画图像，通常为 GIF。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AmpAnim(int width, int height)](#AmpAnim-int-int-) | 创建 AmpAnim 的实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlt()](#getAlt--) | 一段备用文本字符串，类似于 img 上的 alt 属性。 |
| [getAttributes()](#getAttributes--) | AMP 提供了一组通用属性，这些属性已扩展到许多 AMP 组件。 |
| [getAttribution()](#getAttribution--) | 一个指示图像归属的字符串。 |
| [getClass()](#getClass--) |  |
| [getFallback()](#getFallback--) | 回退是一种约定，允许元素向阅读器传达浏览器不支持该元素的情况。 |
| [getPlaceholder()](#getPlaceholder--) | 带有 placeholder 属性的元素充当父 AMP 元素的占位符。 |
| [getRequiredScript()](#getRequiredScript--) | 必需的脚本必须添加到 head 部分。 |
| [getSrc()](#getSrc--) | 类似于 img 标签上的 src 属性。 |
| [hashCode()](#hashCode--) |  |
| [isValid()](#isValid--) | 指示此图像是否为有效的 AmpImage。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlt(String value)](#setAlt-java.lang.String-) | 一段备用文本字符串，类似于 img 上的 alt 属性。 |
| [setAttribution(String value)](#setAttribution-java.lang.String-) | 一个指示图像归属的字符串。 |
| [setFallback(String value)](#setFallback-java.lang.String-) | 回退是一种约定，允许元素向阅读器传达浏览器不支持该元素的情况。 |
| [setPlaceholder(AmpComponent value)](#setPlaceholder-com.aspose.email.AmpComponent-) | 带有 placeholder 属性的元素充当父 AMP 元素的占位符。 |
| [setSrc(String value)](#setSrc-java.lang.String-) | 类似于 img 标签上的 src 属性。 |
| [toAmpHtml()](#toAmpHtml--) | 表示组件的 amp html 版本。 |
| [toHtml()](#toHtml--) | 表示组件的 html 版本。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AmpAnim(int width, int height) {#AmpAnim-int-int-}
```
public AmpAnim(int width, int height)
```


创建 AmpAnim 的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| width | int | AmpAnim 的宽度 |
| height | int | AmpAnim 的高度 |

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
### getAlt() {#getAlt--}
```
public final String getAlt()
```


一段备用文本字符串，类似于 img 上的 alt 属性。

**Returns:**
java.lang.String
### getAttributes() {#getAttributes--}
```
public final AmpAttributes getAttributes()
```


AMP 提供了一组通用属性，这些属性已扩展到许多 AMP 组件。

**Returns:**
[AmpAttributes](../../com.aspose.email/ampattributes)
### getAttribution() {#getAttribution--}
```
public final String getAttribution()
```


一个指示图像归属的字符串。

**Returns:**
java.lang.String
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
### getSrc() {#getSrc--}
```
public final String getSrc()
```


类似于 img 标签上的 src 属性。该值必须是指向可公开缓存的图像文件的 URL

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isValid() {#isValid--}
```
public final boolean isValid()
```


指示此图像是否为有效的 AmpImage。

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAlt(String value) {#setAlt-java.lang.String-}
```
public final void setAlt(String value)
```


一段备用文本字符串，类似于 img 上的 alt 属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setAttribution(String value) {#setAttribution-java.lang.String-}
```
public final void setAttribution(String value)
```


一个指示图像归属的字符串。

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

### setPlaceholder(AmpComponent value) {#setPlaceholder-com.aspose.email.AmpComponent-}
```
public final void setPlaceholder(AmpComponent value)
```


带有 placeholder 属性的元素充当父 AMP 元素的占位符。如果指定，placeholder 元素必须是 AMP 元素的直接子元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [AmpComponent](../../com.aspose.email/ampcomponent) |  |

### setSrc(String value) {#setSrc-java.lang.String-}
```
public final void setSrc(String value)
```


类似于 img 标签上的 src 属性。该值必须是指向可公开缓存的图像文件的 URL

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

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

