---
title: AmpAttributes
second_title: Aspose.Email for Android via Java API 参考
description: 表示 amp-components 使用的属性。
type: docs
weight: 16
url: /zh/androidjava/com.aspose.email/ampattributes/
---

**Inheritance:**
java.lang.Object
```
public class AmpAttributes
```

表示 amp-components 使用的属性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AmpAttributes()](#AmpAttributes--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeight()](#getHeight--) | 元素的高度。 |
| [getHeigths()](#getHeigths--) | 此属性的值是基于媒体表达式的 sizes 表达式。 |
| [getLayout()](#getLayout--) | AMP 提供一组布局，指定 AMP 组件在文档布局中的行为方式。 |
| [getMedia()](#getMedia--) | media 的值是媒体查询。 |
| [getOn()](#getOn--) | on 属性用于在元素上安装事件处理程序。 |
| [getSizes()](#getSizes--) | AMP sizes 属性的值是一个 sizes 表达式，根据当前窗口大小选择对应媒体查询的定义尺寸。 |
| [getWidth()](#getWidth--) | 元素的宽度。 |
| [hashCode()](#hashCode--) |  |
| [isFallback()](#isFallback--) | 定义当前元素为回退元素。 |
| [isNoloading()](#isNoloading--) | noloading 属性指示是否应为此元素关闭“加载指示器”。 |
| [isPlaceHolder()](#isPlaceHolder--) | placeholder 属性指示带有此属性的元素充当父 AMP 元素的占位符。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFallback(boolean value)](#setFallback-boolean-) | 定义当前元素为回退元素。 |
| [setHeight(int value)](#setHeight-int-) | 元素的高度。 |
| [setHeigths(String value)](#setHeigths-java.lang.String-) | 此属性的值是基于媒体表达式的 sizes 表达式。 |
| [setLayout(int value)](#setLayout-int-) | AMP 提供一组布局，指定 AMP 组件在文档布局中的行为方式。 |
| [setMedia(String value)](#setMedia-java.lang.String-) | media 的值是媒体查询。 |
| [setNoloading(boolean value)](#setNoloading-boolean-) | noloading 属性指示是否应为此元素关闭“加载指示器”。 |
| [setOn(String value)](#setOn-java.lang.String-) | on 属性用于在元素上安装事件处理程序。 |
| [setPlaceHolder(boolean value)](#setPlaceHolder-boolean-) | placeholder 属性指示带有此属性的元素充当父 AMP 元素的占位符。 |
| [setSizes(String value)](#setSizes-java.lang.String-) | AMP sizes 属性的值是一个 sizes 表达式，根据当前窗口大小选择对应媒体查询的定义尺寸。 |
| [setWidth(int value)](#setWidth-int-) | 元素的宽度。 |
| [toAmpHtml()](#toAmpHtml--) | 表示属性的 amp html 版本。 |
| [toHtml()](#toHtml--) | 表示属性的 html 版本。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AmpAttributes() {#AmpAttributes--}
```
public AmpAttributes()
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getHeight() {#getHeight--}
```
public final int getHeight()
```


元素的高度。

**Returns:**
int
### getHeigths() {#getHeigths--}
```
public final String getHeigths()
```


此属性的值是基于媒体表达式的 sizes 表达式。

**Returns:**
java.lang.String
### getLayout() {#getLayout--}
```
public final int getLayout()
```


AMP 提供一组布局，指定 AMP 组件在文档布局中的行为方式。

**Returns:**
int
### getMedia() {#getMedia--}
```
public final String getMedia()
```


media 的值是媒体查询。如果查询不匹配，则元素不会渲染，其资源以及可能的子资源也不会被获取。如果浏览器窗口的大小或方向改变，媒体查询将重新评估，元素会根据新的结果隐藏或显示。

**Returns:**
java.lang.String
### getOn() {#getOn--}
```
public final String getOn()
```


on 属性用于在元素上安装事件处理程序。

**Returns:**
java.lang.String
### getSizes() {#getSizes--}
```
public final String getSizes()
```


AMP sizes 属性的值是一个 sizes 表达式，根据当前窗口大小选择对应媒体查询的定义尺寸。

**Returns:**
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```


元素的宽度。

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isFallback() {#isFallback--}
```
public final boolean isFallback()
```


定义当前元素为回退元素。

**Returns:**
boolean
### isNoloading() {#isNoloading--}
```
public final boolean isNoloading()
```


noloading 属性指示是否应为此元素关闭“加载指示器”。

**Returns:**
boolean
### isPlaceHolder() {#isPlaceHolder--}
```
public final boolean isPlaceHolder()
```


placeholder 属性指示带有此属性的元素充当父 AMP 元素的占位符。

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




### setFallback(boolean value) {#setFallback-boolean-}
```
public final void setFallback(boolean value)
```


定义当前元素为回退元素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


元素的高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setHeigths(String value) {#setHeigths-java.lang.String-}
```
public final void setHeigths(String value)
```


此属性的值是基于媒体表达式的 sizes 表达式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setLayout(int value) {#setLayout-int-}
```
public final void setLayout(int value)
```


AMP 提供一组布局，指定 AMP 组件在文档布局中的行为方式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setMedia(String value) {#setMedia-java.lang.String-}
```
public final void setMedia(String value)
```


media 的值是媒体查询。如果查询不匹配，则元素不会渲染，其资源以及可能的子资源也不会被获取。如果浏览器窗口的大小或方向改变，媒体查询将重新评估，元素会根据新的结果隐藏或显示。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setNoloading(boolean value) {#setNoloading-boolean-}
```
public final void setNoloading(boolean value)
```


noloading 属性指示是否应为此元素关闭“加载指示器”。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setOn(String value) {#setOn-java.lang.String-}
```
public final void setOn(String value)
```


on 属性用于在元素上安装事件处理程序。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setPlaceHolder(boolean value) {#setPlaceHolder-boolean-}
```
public final void setPlaceHolder(boolean value)
```


placeholder 属性指示带有此属性的元素充当父 AMP 元素的占位符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setSizes(String value) {#setSizes-java.lang.String-}
```
public final void setSizes(String value)
```


AMP sizes 属性的值是一个 sizes 表达式，根据当前窗口大小选择对应媒体查询的定义尺寸。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


元素的宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### toAmpHtml() {#toAmpHtml--}
```
public String toAmpHtml()
```


表示属性的 amp html 版本。

**Returns:**
java.lang.String -
### toHtml() {#toHtml--}
```
public String toHtml()
```


表示属性的 html 版本。

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

