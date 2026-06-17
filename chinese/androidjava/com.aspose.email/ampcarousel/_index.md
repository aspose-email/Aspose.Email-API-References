---
title: AmpCarousel
second_title: Aspose.Email for Android via Java API 参考
description: 组件允许沿水平轴显示多个相似的内容块。
type: docs
weight: 17
url: /zh/androidjava/com.aspose.email/ampcarousel/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.AmpComponent](../../com.aspose.email/ampcomponent)
```
public class AmpCarousel extends AmpComponent
```

组件允许沿水平轴显示多个相似的内容块。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AmpCarousel(int width, int height)](#AmpCarousel-int-int-) | 创建 AmpCarousel 表单的实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttributes()](#getAttributes--) | AMP 提供了一组通用属性，这些属性已扩展到许多 AMP 组件。 |
| [getClass()](#getClass--) |  |
| [getFallback()](#getFallback--) | 回退是一种约定，允许元素向阅读器传达浏览器不支持该元素的情况。 |
| [getImages()](#getImages--) | 用于显示的图像集合。 |
| [getPlaceholder()](#getPlaceholder--) | 带有 placeholder 属性的元素充当父 AMP 元素的占位符。 |
| [getRequiredScript()](#getRequiredScript--) | 必需的脚本必须添加到 head 部分。 |
| [getType()](#getType--) | 指定轮播项目的显示类型。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFallback(String value)](#setFallback-java.lang.String-) | 回退是一种约定，允许元素向阅读器传达浏览器不支持该元素的情况。 |
| [setPlaceholder(AmpComponent value)](#setPlaceholder-com.aspose.email.AmpComponent-) | 带有 placeholder 属性的元素充当父 AMP 元素的占位符。 |
| [setType(int value)](#setType-int-) | 指定轮播项目的显示类型。 |
| [toAmpHtml()](#toAmpHtml--) | 表示组件的 amp html 版本。 |
| [toHtml()](#toHtml--) | 表示组件的 html 版本。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AmpCarousel(int width, int height) {#AmpCarousel-int-int-}
```
public AmpCarousel(int width, int height)
```


创建 AmpCarousel 表单的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| width | int | AmpCarousel 的宽度 |
| height | int | AmpCarousel 的高度 |

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
### getFallback() {#getFallback--}
```
public final String getFallback()
```


回退是一种约定，允许元素向阅读器传达浏览器不支持该元素的情况。

**Returns:**
java.lang.String
### getImages() {#getImages--}
```
public final List<AmpImage> getImages()
```


用于显示的图像集合。

**Returns:**
java.util.List<com.aspose.email.AmpImage>
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
### getType() {#getType--}
```
public final int getType()
```


指定轮播项目的显示类型。

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

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


指定轮播项目的显示类型。

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

