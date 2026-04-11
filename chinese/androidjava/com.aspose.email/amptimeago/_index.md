---
title: AmpTimeago
second_title: Aspose.Email for Android via Java API 参考
description: 通过将日期格式化为 X 时间前来提供模糊时间戳。
type: docs
weight: 23
url: /zh/androidjava/com.aspose.email/amptimeago/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.AmpComponent](../../com.aspose.email/ampcomponent)
```
public class AmpTimeago extends AmpComponent
```

通过将日期格式化为 \"X time ago\" 提供模糊时间戳
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AmpTimeago(Date dateTime)](#AmpTimeago-java.util.Date-) | 创建 AmpTimeago 的实例。 |
| [AmpTimeago(Date dateTime, int width, int height)](#AmpTimeago-java.util.Date-int-int-) | 创建 AmpTimeago 的实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttributes()](#getAttributes--) | AMP 提供了一组通用属性，这些属性已扩展到许多 AMP 组件。 |
| [getClass()](#getClass--) |  |
| [getCutoff()](#getCutoff--) | 如果时间间隔超过截断阈值（秒），显示原始日期。 |
| [getDateTime()](#getDateTime--) | 日期时间。 |
| [getFallback()](#getFallback--) | 回退是一种约定，允许元素向阅读器传达浏览器不支持该元素的情况。 |
| [getLocale()](#getLocale--) | 默认情况下，本地语言设置为 en；但是，您可以指定其他语言环境。 |
| [getPlaceholder()](#getPlaceholder--) | 带有 placeholder 属性的元素充当父 AMP 元素的占位符。 |
| [getRequiredScript()](#getRequiredScript--) | 必需的脚本必须添加到 head 部分。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCutoff(int value)](#setCutoff-int-) | 如果时间间隔超过截断阈值（秒），显示原始日期。 |
| [setDateTime(Date value)](#setDateTime-java.util.Date-) | 日期时间。 |
| [setFallback(String value)](#setFallback-java.lang.String-) | 回退是一种约定，允许元素向阅读器传达浏览器不支持该元素的情况。 |
| [setLocale(String value)](#setLocale-java.lang.String-) | 默认情况下，本地语言设置为 en；但是，您可以指定其他语言环境。 |
| [setPlaceholder(AmpComponent value)](#setPlaceholder-com.aspose.email.AmpComponent-) | 带有 placeholder 属性的元素充当父 AMP 元素的占位符。 |
| [toAmpHtml()](#toAmpHtml--) | 表示组件的 amp html 版本。 |
| [toHtml()](#toHtml--) | 表示组件的 html 版本。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AmpTimeago(Date dateTime) {#AmpTimeago-java.util.Date-}
```
public AmpTimeago(Date dateTime)
```


创建 AmpTimeago 的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dateTime | java.util.Date |  |

### AmpTimeago(Date dateTime, int width, int height) {#AmpTimeago-java.util.Date-int-int-}
```
public AmpTimeago(Date dateTime, int width, int height)
```


创建 AmpTimeago 的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dateTime | java.util.Date |  |
| width | int |  |
| height | int |  |

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
### getCutoff() {#getCutoff--}
```
public final int getCutoff()
```


如果时间间隔超过截断阈值（秒），显示原始日期。

**Returns:**
int
### getDateTime() {#getDateTime--}
```
public final Date getDateTime()
```


日期时间。

**Returns:**
java.util.Date
### getFallback() {#getFallback--}
```
public final String getFallback()
```


回退是一种约定，允许元素向阅读器传达浏览器不支持该元素的情况。

**Returns:**
java.lang.String
### getLocale() {#getLocale--}
```
public final String getLocale()
```


默认情况下，本地语言设置为 en；但是，您可以指定其他语言环境。查看受支持语言环境的完整列表 https://amp.dev/documentation/components/amp-timeago/?format=email

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




### setCutoff(int value) {#setCutoff-int-}
```
public final void setCutoff(int value)
```


如果时间间隔超过截断阈值（秒），显示原始日期。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setDateTime(Date value) {#setDateTime-java.util.Date-}
```
public final void setDateTime(Date value)
```


日期时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setFallback(String value) {#setFallback-java.lang.String-}
```
public final void setFallback(String value)
```


回退是一种约定，允许元素向阅读器传达浏览器不支持该元素的情况。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setLocale(String value) {#setLocale-java.lang.String-}
```
public final void setLocale(String value)
```


默认情况下，本地语言设置为 en；但是，您可以指定其他语言环境。查看受支持语言环境的完整列表 https://amp.dev/documentation/components/amp-timeago/?format=email

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

